<template>
  <header>
    <div class="container">
      <div class="logo">
        <a href="/">ZK Sync Era zkBitcoin DAPP</a>
      </div>
      <nav>
        <ul>
          <li><router-link to="/">Auctions DAPP</router-link></li>
          <li><router-link to="/about">Staking ETH - zkBitcoin DAPP</router-link></li>
          <li><a href="https://example.com">Staking 0xBTC - zkBitcoin DAPP</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped>
header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 960px;
  margin: 0 auto;
}

.logo a {
  font-size: 24px;
  font-weight: bold;
  color: #fff;
  text-decoration: none;
}

nav ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

nav li {
  margin-right: 20px;
}

nav li:last-child {
  margin-right: 0;
}

nav a {
  font-size: 16px;
  color: #fff;
  text-decoration: none;
}
</style>
