<template>
  <main>
    <div class="overlay">
      <div class="modal">
        <textarea name="note" id="note" cols="30" rows="10"></textarea>
        <button>Add Note</button>
      </div>
    </div>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
      <div class="cards-container">
        <div class="card">
          <p class="main-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo quae amet doloribus totam tempore quibusdam.</p>
          <p class="date">11/08/2023</p>
        </div>
        <div class="card">
          <p class="main-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo quae amet doloribus totam tempore quibusdam.</p>
          <p class="date">11/08/2023</p>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
 main {
  height: 100vh;
  width: 100vw;
 }

 .container {
  max-width: 1000px;
  padding: 10px;
  margin: 0 auto;
 }

 header {
  display: flex;
  justify-content: space-between;
  align-content: center;
 }

 h1 {
  font-weight: bold;
  margin-bottom: 25px;
  font-size: 75px;
 }

 header button {
  border: none;
  padding: 10px;
  width: 50px;
  height: 50px;
  cursor: pointer;
  background-color: rgb(21,20,20);;
  border-radius: 100px;
  color: white;
  font-size: 20px;
  align-content: center;
 }
.card {
  width: 225px;
  height: 225px;
  background-color: rgb(237, 182, 44);
  padding: 10px;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-right: 20px;
  margin-bottom: 20px;
}

.date {
  font-size: 12.5px;
  font-weight: bold;
}
.cards-container {
  display: flex;
  flex-wrap: wrap;
  
}
.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.77);
  z-index: 10;
  display: flex;
  align-items: center;
  justify-content: center;
}

</style>