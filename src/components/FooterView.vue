<template>
  <div class="footer">
    <p>Copyright © 2023 Leapp</p>
    <div class="social-links">
      <a href="https://github.com/kavi94n?tab=repositories" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github"></i>
      </a>
      <a href="https://twitter.com/leapp_dev" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-twitter"></i>
      </a>
      <a href="https://www.linkedin.com/company/leapp-dev" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin"></i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterView',
}
</script>

<style scoped>
.footer {
  background-color: #f5f5f5;
  padding: 20px;
  text-align: center;
}

.social-links {
  display: flex;
  justify-content: center;
  margin-top: 20px;
}

.social-links a {
  margin: 0 10px;
  font-size: 24px;
  color: #333;
  text-decoration: none;
}

.social-links a:hover {
  color: #666;
}
</style>