<h1 align="center">Twidemia</h1>
<p align="center">
Twidemia create an interactive platform where CUHK student can connect, share knowledge, and promote cross-cultural understanding.
It aims to facilitate an open exchange of academic resources, insights, and ideas across borders.
Through Twidemia GPTutor , we seek to build a supportive virtual community that enhances learning and nurtures intercultural relationships. Twidemia promises to expand minds and open minds by bringing students together in a shared passion for learning environment.
    <br> 
</p>
<h1></h1>
<h3>🛠&nbsp;Getting started with Twidemia</h3>

1. First install nodejs at https://nodejs.org/en/download/
1. Clone this repository
1. Install required libraries in the cloned directory
    ```
    npm install
    ```

1. Create a file called `.env.local` in the root folder, with the following contents:
    ```
    MONGODB_URI=YOUR_URL

    NEXTAUTH_SECRET=YOUR_SECRET
    NEXTAUTH_URL=http://localhost:3000
    OPENAIKEY=YOUR_REQUESTED_KEY

    DOMAIN=http://localhost:3000

    ```
    
    Alternatively, use another email account:
    ```
    SMTP_USER=YOUR_USER
    SMTP_PASSWORD=YOUR_PASSWORD
    ```

1. Run nextjs server in development mode
    ```
    npm run dev
    ```

1. Access the project with the "guest login" button from the login page:
    ```
    localhost:3000
    ```
![login](https://github.com/Saiph1/Twidemia-xt/assets/75319087/787aae64-551d-4f17-afcb-cd5d4eee887a)

## Developement
1. Code linting: run `npm run lint` in terminanl
1. Code formatting: run `npm run format` in terminal

## ⛏️ Built Using <a name = "built_using"></a>

- [NodeJs](https://nodejs.org/en/) - Server Environment
- [Next.js](https://nextjs.org/) - Server Framework
- [MongoDB](https://www.mongodb.com/) - Database
- [React](https://reactjs.org/) - Web Framework
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Socket.io](https://socket.io/) - Real-time Chat System
- [Openai](https://openai.com/blog/openai-api) - GPT3 API


## :framed_picture: Project overview <a name = "overview"></a>

![Alt Text](public/overview.jpeg)

## 🎓 Credits <a name = "authors"></a>
- Li Chi-Hsuan 
- Wang Han-Yi 
- Ng Hoi Leong 
- Tung Chun Ting 
- Tam Chi Hang 

