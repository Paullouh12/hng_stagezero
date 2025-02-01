# HNG Stage One Task

## Project Description
This is a Stage One task for HNG Internship. It's a REST API built with Node.js and Express that serves specific personal information in JSON format. The API provides dynamic access to the developer's email, current UTC timestamp in ISO 8601 format, and the project's GitHub repository URL.

## API Documentation

### Base URL
```
https://hng-stagezero-hr1h.onrender.com
```

### Endpoint
```
GET /
```

### Request Format
No parameters required.

### Response Format
```json
{
    "email": "Paullouh12.pp@gmail.com",
    "current_datetime": "2025-01-30T09:30:00Z",
    "github_url": "https://github.com/Paullouh12/hng_stagezero"
}
```

### Example Usage

Using curl:
```bash
curl https://hng-stagezero-hr1h.onrender.com
```

Using JavaScript fetch:
```javascript
fetch('https://hng-stagezero-hr1h.onrender.com')
  .then(response => response.json())
  .then(data => console.log(data));
```

### Status Codes
- 200: Successful response
- 500: Internal server error

## Setup Instructions

1. Clone the repository
```bash
git https://github.com/Paullouh12/hng_stagezero
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add:
```
EMAIL=your-email@example.com
GITHUB_URL=https://github.com/yourusername/your-repo
PORT=4000
```

4. Run the application
```bash
# Development mode
npm run dev

# Production mode
npm start
```

## Technologies Used
- Node.js
- Express.js
- CORS middleware
- Dotenv for environment variables

## Related Links
- [Node.js Developers](https://hng.tech/hire/nodejs-developers)
- [Python Developers](https://hng.tech/hire/python-developers)
- [C# Developers](https://hng.tech/hire/csharp-developers)
- [Golang Developers](https://hng.tech/hire/golang-developers)
- [PHP Developers](https://hng.tech/hire/php-developers)
- [Java Developers](https://hng.tech/hire/java-developers)