<template>
  <div class="home">
    <div class="header-wrapper">
      <div class="header-content">
      <h1>Stephany Esposito</h1>
      <h2> A book lover and nerd with 15 years of experience as an eagle-eyed editor. </h2>
      </div>
      <div class="img-container">
        <img src="../assets/images/steph.jpg" alt="Stephany Esposito" />
      </div>
    </div>
    <div class="blurb-wrapper">
      <div class="blurb-content">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in
          reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
          pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
          culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    </div>
    <div class="socials-wrapper">
      <div class="socials-content">
        <h1><a href="https://www.linkedin.com/in/stephany-esposito-9750563b/" class="fa fa-linkedin"> LinkedIn</a></h1>
        <h1><a href="https://reedsy.com/stephany-renfrow" class="fa fa-book"> Reedsy</a></h1>
      </div>
    </div>
  </div>
</template>
<style scoped>
.home {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  margin-top:65px;
  margin-left:65px;
  width:100%;
}

.header-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  width: 45%;
  height: 300px;
  margin-top: 50px;
}

.header-content{
  display:flex;
  flex-direction: column;
  margin-left:28vw;
  width:100%;
}
.header-wrapper h1 {
  font-family: var(--font-family-header);
  font-size: 3.5rem;
  font-weight: bold;
  margin:0px;
  padding:0px;
}

.header-wrapper h2{
  font: size 1.25rem;
  color:rgba(0, 0, 0, 0.699);
  margin: -15px 0px -10px 0px;
  padding:0px;
}

.header-wrapper .img-container {
  position: absolute;
  width: 400px;
  height: 400px;
  border: 3px solid var(--color-background);
  border-radius: 100%;
  top: 150px;
  overflow: hidden;
  filter:drop-shadow(5px 15px 15px rgba(0, 0, 0, 0.637));
  z-index: 1;

}
.header-wrapper .img-container img {
  display: block;
  object-fit: cover;
  width: 100%;
  transform: translate(0, -55px);
  height: auto;
}

.blurb-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  left:-350px;
  top:215px;
  width: 50%;
  height: 200px;
  background-color: var(--c-grey-light);
  box-shadow: 5px 10px 25px rgba(0, 0, 0, 0.363);
}

.blurb-content{
  display:flex;
  padding:5px;
  width:70%;
  margin-left:28%;
}

.blurb-wrapper .blurb-content p{
  font-size:20px;
}

.socials-wrapper{
  display: flex;
  position: relative;
  top:150px;
  left:410px;
  width:20%;
}

.socials-content{
  display: flex;
  flex-direction: row;
  width:90%;
  justify-content: space-around;
  align-items: flex-end;
}
</style>
