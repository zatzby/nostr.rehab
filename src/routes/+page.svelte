<script lang="ts">
    import Footer from '$lib/components/Footer.svelte'; 
  </script>
  
  <style>
    .container {
      background-image: url('https://nostr.build/p/nb4903.jpeg');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
      font-family: cypherpunk, sans-serif;
      font-size: 75px;
      color: orange;
      display: flex;
      justify-content: center;
      align-items: center;
      height: calc(100vh - 80px);
      width: 100%;
    }
  
    a {
      color: blue;
      text-decoration: underline;
    }
  
    @media screen and (max-width: 1024px) {
      .container { font-size: 40px; }
    }
    @media screen and (max-width: 768px) {
      .container { font-size: 30px; }
    }
    @media screen and (max-width: 480px) {
      .container { font-size: 20px; }
    }
  </style>
  
  <div class="container">
    <a href="https://nostr.build/p/nb3918.mp4">Get</a> nostr.rehab
  </div>
  
  <Footer />