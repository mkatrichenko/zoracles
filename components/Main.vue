<template>
  <div class="main">
    <div class="content">
      <h1 class="main__title">
        DEFI <span class="brand">O</span>RACLE PLATFORM
      </h1>
      <p class="main__text">
        Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
        sint. Velit officia consequat duis enim velit mollit. Exercitation
        veniam consequat sunt nostrud amet.
      </p>
      <a href="google.com" class="main__btn">see swaps</a>
    </div>
    <div class="bg">
      <img src="@/assets/img/main_bg.png" alt="" class="bg__img" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
  data() {
    return {
      isLoaded: false
    };
  },
  created() {
    setTimeout(() => {
      this.isLoaded = true;
    }, 500);
  }
};
</script>

<style scoped lang="scss">
.main {
  width: 100%;
  position: relative;

  .content {
    position: absolute;
    top: 185px;
    left: 182px;
    text-align: left;
    max-width: 525px;
  }

  .main__title {
    margin-bottom: 32px;
    font-family: "Jockey";
    font-style: normal;
    font-weight: normal;
    font-size: 106px;
    line-height: 88.5%;

    color: #f8f8f8;
  }

  .main__text {
    margin-bottom: 30px;
    font-family: "RobotoCondensed";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #f8f8f8;
  }

  .main__btn {
    padding: 16px 60px;
    font-family: Lato;
    font-weight: 600;
    font-size: 18px;
    line-height: 1.14;
    text-transform: capitalize;
    color: #ffffff;
    background-color: var(--brand);
    transition: 0.3 opacity ease-out;
    cursor: pointer;
    border-radius: 8px;

    &:hover {
      opacity: 0.8;
    }
  }
}

.bg__img {
  width: 100%;
  max-width: 1920px;
}
</style>
