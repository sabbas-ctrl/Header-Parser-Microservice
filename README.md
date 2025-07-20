# Request Header Parser Microservice

A simple and reliable API that returns information about your device based on the HTTP headers sent with your request.  
Perfect for quickly retrieving your IP address, preferred language, and software details.

## Features

- Returns your public IP address.
- Detects your preferred language from the request headers.
- Identifies your operating system and browser from the user-agent string.

## Usage

- **GET /**  
  Home page.

- **GET /api/whoami**  
  Returns a JSON object with the following keys:
  - `ipaddress`: Your public IP address.
  - `language`: Your preferred language(s).
  - `software`: Information about your operating system and browser.

## Example Response

```json
{
  "ipaddress": "159.20.14.100",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64)"
}
```

## Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**
   ```sh
   git clone https://github.com/sabbas-ctrl/Header-Parser-Microservice.git
   cd Header-Parser-Microservice
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Start the server**
   ```sh
   npm run dev
   ```
   The API will be running at `http://localhost:3000/`.

---

Part of a microservice challenge from freeCodeCamp.# Request Header Parser Microservice
