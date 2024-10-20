<script>
    import { page } from '$app/stores';
  </script>
  
  <div class="error-container">
    <h1>{$page.status}: {$page.error.message}</h1>
    <p>Oops! The page you're looking for seems to have wandered off.</p>
    <a href="/">Go back home</a>
  </div>
  
  <style>
    .error-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      font-family: Arial, sans-serif;
      background-color: #000000;
    }
  
    h1 {
      font-size: 3rem;
      color: #ffffff;
      margin-bottom: 1rem;
    }
  
    p {
      font-size: 1.2rem;
      color: #34495e;
      margin-bottom: 2rem;
    }
  
    a {
      padding: 10px 20px;
      background-color: #dab12cc4;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
  
    a:hover {
      background-color: #c99b1f;
    }
  </style>