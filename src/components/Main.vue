<template>
  <main>
    <article>
      <header>
        <h2>The Basic Language of the Web: HTML</h2>
        <section class="author-section">
          <img 
            src="../../public/laura-jones.jpg" 
            alt="Picture of Laura Jones"
            width="75"
            height="75"
          >
          <p id="author">Posted by <strong>Laura Jones</strong> on Monday, June 21st 2027</p>
        </section>
        <img
          class="post-img"
          src="../../public/post-img.jpg" 
          alt="Picture of some HTML code"
        >
      </header>
      <div class="article-body">
        <p>
          All modern websites and web applications are built using three <em>fundamental</em> technologies: HTML, CSS and JavaScript. These are the languages of the web.
        </p>
        <p>
          In this post, let's focus on HTML. We will learn what HTML is all about, and why you too should learn it.
        </p>
        <section>
          <h3>What is HTML?</h3>
          <p>
            HTML stands for HyperText Markup Language. It's a markup language that web developers use to structure and describe the content of a webpage (not a programming language).
          </p>
          <p>
            HTML consists of elements that describe different types of content: paragraphs, links, headings, images, video, etc. Web browsers understand HTML and render HTML code as websites.
          </p>
          <p>In HTML, each element is made up of 3 parts:</p>
          <ol>
            <li>The opening tag</li>
            <li>The closing tag</li>
            <li>The actual element</li>
            <li>
              You can learn more at the <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">MDN Web Docs</a>.
            </li>
          </ol>
        </section>
        <section>
          <h3>Why should you learn HTML?</h3>
          <p>
            There are countless reasons for learning the fundamental language of the web. Here are 5 of them:
          </p>
          <ul>
            <li>To be able to use the fundamental web dev language</li>
            <li>
              To hand-craft beautiful websites instead of relying on tools like Worpress or Wix
            </li>
            <li>To build web applications</li>
            <li>To impress friends</li>
            <li>To have fun 😃</li>
          </ul>
        </section>
        <p>
          Hopefully you learned something new here. See you next time!
        </p>
      </div>
    </article>
  </main>
</template>

<script>
export default {
  name: 'Main',
}
</script>