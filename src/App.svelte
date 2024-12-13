<script>
  import Header from './lib/Header/Header.svelte';
  import Slider from './lib/Slider/Slider.svelte';
  import Sidebar from './lib/Sidebar/Sidebar.svelte';
  import Content from './lib/Content/Content.svelte';
  import Footer from './lib/Footer/Footer.svelte';
  import Navbar from './lib/Nav/Nav.svelte';
  
 
</script>

<main>
  <Header />
  <Navbar/>
  <Slider />
  <div class="main-body">
    <Sidebar />
    <Content />
  </div>
  <Footer />
</main>

<style>
  *{
    margin: 0;
    padding: 0;
  }
  main {
    display: flex;
    flex-direction: column;
    width: 100%;
    border: 5px solid black
  }

  .main-body {
    display: flex;
    width: 95%;
   
  }
</style>
