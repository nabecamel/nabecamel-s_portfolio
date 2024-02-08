<template>
  <div class="portfolio">
    <h1>{{ msg }}</h1>
    <p>明治大学情報コミュニケーション学部情報コミュニケーション学科3年の渡辺 航です。</p>
    <p>さまざまな技術領域に興味を持ち日々学習をしています。</p>
    
    <h3>連絡先</h3>
    <p>Email: watanabe.wataru.2025@gmail.com</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/%E8%88%AA-%E6%B8%A1%E8%BE%BA-ba8709281/m" target="_blank" rel="noopener">私のLinkedIn</a></p>
    <p>GitHub: <a href="https://github.com/nabecamel" target="_blank" rel="noopener">私のGitHub</a></p>
    
    <h3>スキルセット</h3>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript (ES6+)</li>
      <li>Python</li>
      <li>C/C++</li>
      <li>Java</li>
      <li>R</li>
      <li>Vue.js</li>
      <li>PHP</li>
      <li>Node.js</li>
      <li>ShellScript</li>
      <li>laravel</li>

    </ul>

  </div>
</template>

<script>
export default {
  name: 'PortfolioIntro',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 20px;
}
ul {
  list-style-type: circle;
  padding-left: 20px;
}
a {
  color: #42b983;
}
</style>
