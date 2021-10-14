<template>
  <div id="app-content">
    <Header />
    <Main />
    <Aside />
    <footer>
      <p id="coypright">Copyright &copy; 2017 by The Code Magazine</p>
      </footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Aside from './components/Aside.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Aside,    
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400;1,700&display=swap');

  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');

  #app {
    font-family: 'Montserrat', sans-serif;
    color: #444;
  }

  * {
    margin: 0;
    padding: 0;
  }

  h1 {
    font-size: 26px;
    text-transform: uppercase;
    font-style: italic;
  }

  h2 {
    font-size: 40px;
  }

  h3 {
    font-size: 30px;
  }

  h1, h2, h3 {
    color: #1098ad;
  }

  h4 {
    font-size: 20px;
    text-align: center;
    text-transform: uppercase;
  }

  p {
    line-height: 1.5;
    font-size: 22px;
    text-align: justify;
  }

  li {
    font-size: 20px;
    margin: 0.7rem 0;
  }

  .article-body p, h2, h3 {
    margin: 1.5rem auto;
    width: 75vw;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  ol, ul {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    align-items: center;
    margin: 1.5rem auto;
  }

  li:first-child {
    font-weight: 700;
  }

  li:last-child {
    font-style: italic;
  }

  /* li:nth-child(even) {
    color: red;
  } */

  aside {
    background-color: #f7f7f7;
    border-top: 5px solid #1098ad;
    border-bottom: 5px solid #1098ad;
  }

  a:link {
    color: #1098ad;
  }

  a:visited {
    color: #1098ad;
  }

  a:hover {
    color: orangered;
    font-weight: bold;
    text-decoration: underline orangered;
  }

  a:active {
    font-size: 22px;
  }

  .related {
    list-style: none;
    display: flex;
    justify-content: space-around;
    flex-direction: row;
  }

  .related li * {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0.2rem auto;
  }

  .post-img {
    width: 100vw;
    display: block;
    margin: 1.5em auto;
  }

  .main-header {
    background-color: #f7f7f7;
    padding: 20px 60px;
    margin-bottom: 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-top: #1098ad 10px solid;
  }

  .navbar a {
    margin: 0 15px;
  }

  .author-section {
    display: flex;
    align-items: center;
    margin: 30px 50px;
  }
  .aside-block {
    margin: 1.5rem 0;
  }

  #author {
    font-style: italic;
  }

  #copyright {
    font-size: 14px;
  }

</style>
