<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
/* default setting */
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Comfortaa', cursive;
    // word-break: break-all;
  }
  html, body{ font-size: 10px; }

  a{ display: inline-block; text-decoration: none; color: inherit; }
  button{
    border: none;
    padding: 10px 20px;
    cursor: pointer;
  }
  button:focus{ outline: none; }
  input:focus{ outline: none; }
  img{ width: 100%; display: block; }

  .mw1440{ max-width: 1440px; margin: 0 auto; padding: 40px; }
  .padding-40{ padding: 40px; }
  .padding-20{ padding: 20px; }

  .b-main-head{ font-size: 60px; text-transform: uppercase; }
  .b-head{
    font-size: 30px;
    margin-bottom: 30px;
    text-transform: uppercase;
  }
  .b-title{
    font-size: 20px;
    margin-bottom: 20px;
    text-transform: uppercase;
  }
  .b-text{ font-size: 16px; line-height: 1.5; }
  .fs16{ font-size: 16px; }

  .title-line{ position: relative; }
  .title-line::before, .title-line::after{
    content: "";
    width: 80px;
    height: 4px;
    background-color: #C4E4F8;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
  }
  .title-line::before{ top: -14px; }
  .title-line::after{ bottom: -14px; }






/* 반응형 */
  @media ( max-width: 768px ) {
    .mw1440{ padding: 30px; }
    .padding-40{ padding: 30px; }
    .b-main-head{ font-size: 50px; }
    .b-head{
      font-size: 26px;
      margin-bottom: 26px;
    }
    .b-title{
      font-size: 18px;
      margin-bottom: 18px;
    }
    .b-text{ font-size: 14px; }
    .fs16{ font-size: 14px; }
  }


  @media ( max-width: 500px ) {
    .mw1440{ padding: 20px; }
    .padding-40{ padding: 20px; }
    .padding-20{ padding: 10px; }
    .b-main-head{ font-size: 32px; }
    .b-head{
      font-size: 20px;
      margin-bottom: 20px;
    }
    .b-title{
      font-size: 16px;
      margin-bottom: 16px;
    }
    .b-text{ font-size: 12px; }
    .fs16{ font-size: 12px; }
  }
</style>
