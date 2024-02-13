<footer class="footer">
  <nav>
    <a class="profile" href="/Card.svelte"> Short profile </a>
  </nav>
  <p class="copyright">&copy; Craighead Diocesan School 2024</p>
</footer>

<style>
  .profile {
    background: rgb(150, 186, 150);
    color: #104e0f;
    font-weight: medium;
    text-align: center;
    text-transform: uppercase;
    size: is-medium;
    text-shadow: 1px 1px rgb(0, 2, 1);
    padding: 10px;
  }
  .profile:hover {
    margin: 10px;
    background-color: #ffffff;
    color: #000;
    border-bottom: 3px solid #b1b1b0;
  }
  /* footer {
    background: green;
  } */
  .footer {
    background-color: green;
    color: black;
    size: is-small;
  }
  .copyright {
    margin: 10px;
  }
</style>
