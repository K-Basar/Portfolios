<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
  }

  /* ===== TOP NAVIGATION BAR ===== */
  .top-nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: white;
    z-index: 1000;
    padding: 14px 10px; /* slightly taller */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .nav-container {
    display: flex;
    gap: 10px;
    justify-content: center;
    flex-wrap: wrap;
  }

  .top-nav a {
    text-decoration: none;
    padding: 8px 14px;
    background-color: #6c757d;
    color: white;
    border-radius: 5px;
    font-size: 14px;
    transition: 0.2s ease-in-out;
  }

  .top-nav a:hover {
    background-color: #495057;
  }

  /* 🔥 THIS is what prevents content from hiding */
  .content {
    margin-top: 140px;  /* MUST be >= navbar height */
    padding: 0 20px 40px 20px;
    max-width: 1000px;
    margin-left: auto;
    margin-right: auto;
  }

  /* 🔥 Prevent section titles from hiding when clicked */
  section {
    scroll-margin-top: 140px;
  }

  h2 {
    border-bottom: 2px solid #eee;
    padding-bottom: 5px;
    margin-top: 40px;
  }

  details {
    margin-bottom: 15px;
  }
</style>
