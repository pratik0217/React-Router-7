# React Router 7 Setup 
<img width="800" height="283" alt="Screenshot 2025-08-01 033024" src="https://github.com/user-attachments/assets/e07ac0ef-28ca-41a6-8469-92a9115750b3" />

Installation React router 7 version
- Basically React router have two parts
  - Framework
  - Library
-When use router in React project application then have use router library.

Following step of Installation React Router
- Step 1 Create react vite application.
  - syntax ( npm create vite@latest projectName ).
- Step 2 If already have vite react application then just added React router.
  - syntax ( npm i react-router ).

How to check react router is install in React Project ?
- Go to package.json.
- Search dependencies.
- Dependencies already existed two properties
  - react
  - react-dom
- If install react router then automatically added react-router on dependencies.
  - react-router

- Step 3 Finally, Render a { BrowserRouter } around the application
<img width="564" height="33" alt="Screenshot 2025-08-01 204121" src="https://github.com/user-attachments/assets/e6308a19-5b7e-4102-b200-1d01fad9db6f" />

- Wrap <BrowserRouter> in main.jsx
<img width="659" height="148" alt="Screenshot 2025-08-01 204247" src="https://github.com/user-attachments/assets/a2278c95-17e6-44e9-956c-7eb1ed375036" />

- Step 4 Add Pages Using Routers & Route.
- Step 5 import { Routes, Route, Link} from 'react-router'
<img width="616" height="30" alt="Screenshot 2025-08-01 204436" src="https://github.com/user-attachments/assets/3f5ec21d-4fc2-4a02-8e4e-a290b8382b88" />

- Step 6 import Routes & Route added on App.jsx
<img width="805" height="452" alt="Screenshot 2025-08-01 204932" src="https://github.com/user-attachments/assets/fa11d157-c089-47d3-9a4b-89dfef9e0da7" />

Interview Question 
Q). What is current version of React Router ?

# Basic Routing
<img width="789" height="412" alt="Screenshot 2025-08-01 195441" src="https://github.com/user-attachments/assets/baaa847e-5d35-4399-83a4-48b83d9c1738" />

# Header with React Router
<img width="799" height="276" alt="Screenshot 2025-08-01 205827" src="https://github.com/user-attachments/assets/2f0c4e36-271f-4a73-8626-706e90163489" />

# 404 Page & Rediraction 
<img width="793" height="298" alt="Screenshot 2025-08-01 232255" src="https://github.com/user-attachments/assets/24825438-9324-44e8-912e-ffd99089e8c6" />

What is 404 Page ? 
- 404 Page stand for Page not found.
- If user get something URL(path) in page and user URL(path) not existed then create new 404 page for showing as error throw.

Final UI 

<img width="1919" height="1016" alt="Screenshot 2025-08-02 010113" src="https://github.com/user-attachments/assets/2a9c52f9-a3c1-4a60-b8fe-d708545f346d" />

# Nested Navigation with React Router 
<img width="803" height="286" alt="Screenshot 2025-08-02 005127" src="https://github.com/user-attachments/assets/67fbaf92-603a-442a-8c38-c67c5170f218" />

- Which page have make nested navigation then create navigation
  - ( Example - College page and also inside nested navigation ).
- When college page declare app function inside of route this time college route not declare self close.
- If make nested navigation in college page.

Code College Page - 

<img width="1052" height="371" alt="Screenshot 2025-08-02 014855" src="https://github.com/user-attachments/assets/b549b73c-8eb9-499b-9767-acfe6b2771c0" />

- { Outlet } use when have Nested Navigation for Nested navigation child component show on Browser UI

code App function -

<img width="826" height="460" alt="Screenshot 2025-08-02 014821" src="https://github.com/user-attachments/assets/22119043-16b5-40c1-ac64-2bb1ab009efd" />

Final UI - 

<img width="1919" height="511" alt="Screenshot 2025-08-02 015557" src="https://github.com/user-attachments/assets/13d6c7ab-e112-452c-8c3d-25e2a6ff4c42" />

# Layout and Index Route in React
<img width="806" height="301" alt="Screenshot 2025-08-02 020205" src="https://github.com/user-attachments/assets/7b419abc-48c6-4071-b576-ed55c9ab7120" />

What is Layout route
- When you want to be all page have navbar showing on UI but ( ex- college page not have navbar show ) then used layout routes.

<img width="615" height="232" alt="Screenshot 2025-08-02 133929" src="https://github.com/user-attachments/assets/75b2744a-bc02-4df5-8411-48b85ae9e178" />

- Showing child component of nested navigation then use {Outlet}.

<img width="842" height="486" alt="Screenshot 2025-08-02 143630" src="https://github.com/user-attachments/assets/540e6bda-61f7-4627-8940-bc1aa9e7a543" />

- { index } use for something page have default show in UI.

<img width="750" height="200" alt="Screenshot 2025-08-02 143823" src="https://github.com/user-attachments/assets/6010b192-d1d5-40b6-9270-9e16d671c777" />

# Route Prefixes 
Step 1 - App function.
<img width="642" height="110" alt="Screenshot 2025-08-02 144027" src="https://github.com/user-attachments/assets/a0b98c6f-4aab-4062-86a5-9b749f6fb5d7" />

Step 2 - Navbar component.
<img width="788" height="38" alt="Screenshot 2025-08-02 143959" src="https://github.com/user-attachments/assets/94bd6a20-7222-4e1e-b04d-6faf69c9cb39" />

# Dynamic Routes
<img width="672" height="295" alt="Screenshot 2025-08-02 143217" src="https://github.com/user-attachments/assets/165f4c7d-b370-41a5-8b0f-92e1d332ef17" />
What is dynamic routes ? 
- When one page open to multiple routes then this data depend with route it called Dynamic Routes.


Interview Question 
- What is useParams ?
- Why use params in react component ?

# Optional Segment
<img width="728" height="252" alt="Screenshot 2025-08-03 125541" src="https://github.com/user-attachments/assets/ced79a20-2e43-4188-9350-a23328784d67" />

Note : this chapter does't properly learn If in future want to be learn optional segment again then goto be {code step by step chapter : Optional Segment}

Chapter Link : https://www.youtube.com/watch?v=OmvoQ9Y3vv8&list=PL8p2I9GklV463WUKdVzUZ17IDZ3SwoSTu&index=66
