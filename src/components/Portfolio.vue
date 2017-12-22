<template>
  <div class='portfolio'>
    <div class='portfolio-item'>
      <img src='../assets/ss-ipaws.png' />
      <h3>iPaws</h3>
      <p>A proof-of-concept site for a pet adoption organization. Built using Mongoose, Express, React and Node (MERN stack).</p>
    </div>
    <div class='portfolio-item'>
      <img src='../assets/ss-photos.png' />
      <h3>Photos-on-Rails</h3>
      <p>A fully-functional photo sharing site inspired by Flickr. Built with Ruby on Rails and utilizing Amazon S3 for storage.</p>
    </div>
    <div class='portfolio-item'>
      <img src='../assets/ss-irish.png' />
      <h3>Irish Fire Logs</h3>
      <p>An ecommerce site for the Irish Fire Logs brand. Build with Bootstrap, PHP, and utilizing Stripe for payment processing.</p>
    </div>
    <div class='portfolio-item'>
      <img src='../assets/ss-simon.png' />
      <h3>JS-Simon</h3>
      <p>The classic electronic game of memory skill Simon, re-created for the web. Built using vanilla JavaScript, HTML and CSS.</p>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Portfolio'
  }
</script>
<style>
  .portfolio {
    width: 75%;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
  .portfolio-item {
    width: 50%;
    min-width: 350px;
    max-width: 400px;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: justify;
    margin: 20px;
    height: 500px;
  }
  .portfolio-item img {
    max-width: 100%;
    display: block;
  }

</style>
