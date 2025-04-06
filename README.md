# HelloMCP

A simple Flask application that provides a ping-pong API endpoint.

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/mattintech/testMCP.git
   cd testMCP
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

The server will start at `http://localhost:5000`

## API Documentation

### Ping Endpoint

**Endpoint:** `/ping`

**Method:** GET

**Description:** Returns a simple pong response.

**Response Example:**
```json
{
  "response": "pong"
}
```

**cURL Example:**
```
curl http://localhost:5000/ping
```

## License

MIT