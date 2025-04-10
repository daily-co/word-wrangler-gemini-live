# Word Wrangler

This repo consists of two demos where you can play a word guessing game with an AI partner. One demo version is web-based and the other is phone-based.

## Web version

### Running the Server

1. Switch to the server directory:

```bash
cd server
```

2. Set up and activate your virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Create an .env file and add your `GOOGLE_API_KEY`:

```bash
cp env.example .env
```

5. Run the server:

```bash
python server.py
```

### Running the client

1. In a new terminal window, navigate to client:

```bash
cd client
```

2. Install dependencies:

```bash
npm install
```

3. Run the app

```bash
npm run dev
```

4. Open http:localhost:3000 in your browser

## Phone version

TBD
