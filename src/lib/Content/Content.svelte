<script>
 
</script>

<div class="content">
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 1">
    <p>Pie de foto 1</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 2">
    <p>Pie de foto 2</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 3">
    <p>Pie de foto 3</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 4">
    <p>Pie de foto 4</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 5">
    <p>Pie de foto 6</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 5">
    <p>Pie de foto 7</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 5">
    <p>Pie de foto 8</p>
  </div>
  <div class="item">
    <img src="https://via.placeholder.com/150" alt="Imagen 5">
    <p>Pie de foto 9</p>
  </div>
</div>

<style>
  .content {
    width: 80%;
    flex: 1;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    padding: 10px;
    justify-content: space-between;
  
  }

  .item {
    width: calc(20% - 10px); 
    padding: 10px;
    background-color: #ddd;
    border-radius: 5px;
    text-align: center;
  }

  .item img {
    width: 100%;
    height: auto;
    border-radius: 5px;
  }

  .item p {
    margin-top: 10px;
    font-size: 14px;
  }
</style>
