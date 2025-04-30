# Chat App - Continum

You can view the working demo from here: [Video Link](https://drive.google.com/file/d/1rCmjxKkTVnVIFoVkpb-LQff-VqEmUg8B/view?usp=drive_link)

## Steps to Run

1. Go into each directory:

   - `continum-backend/`
   - `continum-frontend/`

2. Install the libraries using:

   ```bash
   npm install
   ```

3. Run the apps using the following commands:

   - For backend:

     ```bash
     npm run start:dev
     ```

   - For frontend:

     ```bash
     npm run dev
     ```

## Features Implemented

1. Google Login
2. Auth Mechanism
3. RBAC - Investor, Innovator
4. Websockets - Real-time chat app
5. S3 File Upload
6. Profile Image Upload
7. Upload Image While Chatting

## Notes

- While testing in Postman, you need to add the following header for WebSockets to work:
  ```
  Sec-WebSocket-Protocol: jwt-token
  ```
  Without this header, WebSockets will return an `Unauthorized` error.
