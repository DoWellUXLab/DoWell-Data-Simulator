## **DoWell Random Table**

Welcome to the documentation for the DoWell Random Table API. This API service provides access to a vast database containing up to 10 million numeric data points, each consisting of 8-digit numbers. The primary purpose of this API is to offer users the ability to retrieve and utilize large datasets for various testing purposes.

### **Introduction:**
The DoWell Random Table API offers developers a convenient and efficient means of accessing randomized numeric data for testing and analysis. Whether you're a software engineer, data scientist, or quality assurance professional, our API provides the necessary tools to access and manipulate vast datasets with ease.

### **Key Features:**
- Access to up to 10 million numeric data points.
- Flexible filtering methods to fine-tune data retrieval.
- Designed for testing purposes, catering to developers and professionals who require large datasets.
- Secure and reliable access through API endpoints.
- Simple integration into existing applications and workflows.

### **Getting Started:**
To begin using the DoWell Random Table API, you will need an API key, which can be obtained by registering for an account on our [platform](https://ll05-ai-dowell.github.io/100105-DowellApiKeySystem/). Once you have your API key, you can start making requests to retrieve data from our extensive database.

### **Authentication:**
Authentication is required for accessing the API endpoints. You will need to include your API key in the request headers for authentication purposes.

### **Endpoints:**
- **Base URL**: `https://uxlivinglab200112.pythonanywhere.com/api/`
- **GET /service**: Retrieve random numeric data from the database based on the filtering condition.

### **Request and Response Formats:**
- **GET /service**:
  - Query Parameters:
    - api_key: Your unique API key for authentication.
    - filter_method: The method used for filtering data (e.g., contains, multiple of, between, etc.).
    - size: The size of the data to retrieve (e.g., maximum number of results).
    - value (optional): The value to filter the data by.

  - Response Format: JSON

For detailed information on how to use specific endpoints, filtering methods, and query parameters, please refer to the [API documentation](https://documenter.getpostman.com/view/24860974/2sA2xmWB7B)

### **Web App Interface**:
 - Explore our user-friendly [web app](https://uxlivinglab200112.pythonanywhere.com/) for an intuitive way to access and interact with the data.
- Easily download data as CSV files directly from the web app interface.



---------------------------------------------------------------------------------------------------------------------------------------------
The DoWell Random Table API provides developers and professionals with access to a vast repository of numeric data for testing purposes. With its flexible filtering methods and straightforward integration, our API simplifies the process of accessing and utilizing large datasets. Start exploring the possibilities today and unlock the potential of big data for your projects.


Thank you for choosing the DoWell Random Table API!
Happy exploring!
