<template>
  <div class="footer__container">
    <div class="intro">
      <div class="tabs info">
        <h2 class="template">zoracles</h2>
        <p>
          We are building a platform powered by Zoracles technology that
          empowers DeFi users with the data, tools and capital to be competitive
          in global decentralized financial markets.
        </p>
      </div>
      <div class="tabs quick__links">
        <h3 class="template">QUICK LINKS</h3>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Docs</a></li>
          <li><a href="#">NFT Swap</a></li>
          <li><a href="#">DeFi Prime</a></li>
          <li><a href="#">Whitepaper</a></li>
          <li><a href="#">Github</a></li>
        </ul>
      </div>
      <div class="tabs more__links">
        <h3 class="template">MORE LINKS</h3>
        <ul>
          <li><a href="#">Discord</a></li>
          <li><a href="#">Telegram</a></li>
          <li><a href="#">Medium</a></li>
          <li><a href="#">Twitter</a></li>
          <li><a href="#">Reddit</a></li>
          <li><a href="#">YouTube</a></li>
        </ul>
      </div>
      <div class="tabs subscribe">
        <h3 class="template">SUBSCRIBE</h3>
        <div class="form">
          <input class="input" type="email" placeholder="Enter your email" required>
          <button class="btn">Send</button>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.footer__container {
	max-width: 1440px;
	font-family: "RobotoCondensed";
  background: #131d41;
  color: #fff;
}
.intro {
  display: flex;
	justify-content: space-between;
	text-align: left;
}
.tabs {
	margin: 50px;
	width: 25%;
}
.template {
	margin: 20px 0;
}
.info {
  list-style: none;
  text-decoration: none;
  color: #fff;
	margin-top: 35px;
}
.intro a {
  color: #fff;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0.01em;
  text-align: left;
}
.info h2 {
  font-family: "Jockey";
  font-style: normal;
  font-weight: normal;
  font-size: 36px;
  // line-height: 150%;
}
.info p {
	color: rgba(255, 255, 255, 0.6);
	max-width: 300px;
	font-size: 14px;
	font-style: normal;
	font-weight: 400;
	line-height: 24px;
	letter-spacing: 0.01em;
	text-align: left;

}
.intro h3 {
  font-family: "RobotoCondensed";
  font-size: 16px;
  font-style: normal;
  font-weight: 700;
  line-height: 24px;
  letter-spacing: 0.01em;
  text-align: left;
}
.form {
	display: flex;
  flex-direction: row;
}
.subscribe {

}
.input {
  border-radius: 8px;
  background: #0D173E;;
  color: #fff;
	font-size: 16px;
	height: 64px;
	width: 302px;
	text-indent: 25px;
	border: 0px;

}
input::placeholder {
	color: #fff;
}
.btn {
  background: #ff5547;
  color: #fff;
	font-size: 20px;
	height: 64px;
	width: 103px;
	border-radius: 8px;
}

@media screen and (max-width: 576px) {
	.intro {
		flex-direction: column;
	}
	.tabs {
		margin: 20px 50px;
	}
	.input {
		font-size: 12px;
    height: 46px;
    width: 130px;
	}
	.btn {
		font-size: 12px;
    height: 46px;
    width: 60px;
	}
	.info p {
		max-width: 200px;
	}
}

</style>