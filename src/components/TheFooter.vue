<template>
  <div class="footer-container">
    <footer>
      <div class="footer-text">Powered by <a href="https://openai.com/" target="_blank">OpenAI</a>, <a href="https://vercel.com/" target="_blank">Vercel.</a></div>
      <div class="footer-img">
        <a href="https://github.com/Rustam-Fozilov/ReadGPT" target="_blank">
          <span>
            <img src="@/assets/image/github-mark.svg" alt="Github">
          </span>
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "TheFooter"
}
</script>

<style scoped>

.footer-container {
  width: 100%;
  height: 80px;
  margin-top: 2rem;
}

footer {
  background-color: var(--navbar-bg-color);
  border-top: 1px solid rgba(0, 0, 0, 0.5);
  height: 100%;
  display: flex;
  gap: 10px;
  justify-content: center;
  align-items: center;
}

.footer-text {
  font-family: NeueHaasDisplay-Roman;
  font-size: 1rem;
  opacity: 0.5;
}

.footer-text a {
  font-family: NeueHaasDisplay-Medium;
  color: black;
  text-decoration: none;
}

.footer-text a:hover {
  cursor: pointer;
  text-decoration: underline;
}

.footer-img {
  width: 25px;
}

.footer-img img {
  width: 100%;
}

</style>