# Bank REST API

This is a REST API built using Node.js that allows users to access bank details using IFSC (Indian Financial System Code) code.

## Endpoints

### Get Bank Details by IFSC Code

- **URL:** `/bank/:ifsc_code`
- **Method:** `GET`
- **Description:** Retrieves details of a bank branch based on the provided IFSC code.
- **Parameters:**
  - `ifsc_code`: The IFSC code of the bank branch.
- **Response:**
  - Status Code: `200 OK`
  - Body: JSON object containing bank details such as bank name, branch name, address, etc.
- **Example:**
  ```bash
  curl http://localhost:8000/bank/HDFC0001245
  
## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/bank-rest-api.git
    ```

2. Navigate to the project directory:

    ```bash
    cd bank-rest-api
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Running the Server

To start the server, use the following command:

```bash
npm start

