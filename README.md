# Screen Shopper - A place to shop 

Demo link : https://screenshopper.herokuapp.com/

Setup:

1. Clone the repository
    ```cmd
    git clone https://github.com/mananjoshi2000/Screen-Shopper.git
    ```
2. Install dependencies
    ```cmd
    npm install
    cd client
    npm install
    ```
3. Set up environment variables
    
    In .env - 
    ```cmd
    MONGODB_URL = mongodb+srv://username:password@CLUSTER/COLLECTION
    ACCESS_TOKEN_SECRET = a string
    REFRESH_TOKEN_SECRET = a string

    CLOUD_NAME = your cloud name (cloudinary)
    CLOUD_API_KEY = your cloud API key (cloudinary)
    CLOUD_API_SECRET = your cloud API secret (cloudinary)
    ```
4. Run Server and Client concurrently
    ```cmd
    npm run dev
