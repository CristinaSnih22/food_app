<template>
  <div class="app">
    <div class="header">
     <div class="content"> <h1><i>WELCOME TO TEXAS RESTAURANT</i></h1></div>
      </div>
      <h1 style="color:red">MENU</h1>
    <div class="contentt">
      <div class='image'>
        <a href="/det.vue">
       <img src='../imagee/1.jpg' width="450px" height="300px"/>
       </a>
       <h3>Burger Meat</h3>
      <p>PRICE=11$</p><button>order </button>
      </div>
      <div >
       <div class='image2'>
      <img src='../imagee/B.jpg' width="450px" height="300px"/>
      <h3>Burger Meat</h3>
      <p>PRICE=10$</p><button>order </button>
      </div></div>
       <div class='image3'>
      <img src='../imagee/s.jpg' width="450px" height="300px">
      <h3>Chicken Burger </h3>
      <p>PRICE=8$</p><button>order </button>
      </div>
       <div class='image1'>
      <img src='../imagee/R.jpg' width="450px" height="300px"/>
      <h3>Fries</h3>
      <p>PRICE=5$</p><button>order </button>
      </div>
       <div class='image1'>
      <img src='../imagee/o.jpg' width="450px" height="300px"/>
      <h3>Fried Onions</h3>
      <p>PRICE=7$</p><button>order </button>
      </div>
      <div class='image1'>
      <img src='../imagee/w.jpg' width="450px" height="300px"/>
      <h3>Wedges</h3>
      <p>PRICE=5$</p><button>order </button>
      </div>
      <div class='image1'>
      <img src='../imagee/pp.jpg' width="450px" height="300px"/>
      <h3>Pepsi</h3>
      <p>PRICE=3$</p><button>order </button>
      </div>
      <div class='image1'>
      <img src='../imagee/mi.jpg' width="450px" height="300px"/>
      <h3>Fanta</h3>
      <p>PRICE=2$</p><button>order </button>
      </div>
      <div class='image1'>
      <img src='../imagee/ora.jpg' width="450px" height="300px"/>
      <h3>CocaCola</h3>
      <p>PRICE=3$</p>
      <button>order </button>
      </div>
      <div class="order">
      <h1 style="text-align:center"><i>Order from our delicious restaurant now</i></h1>
       <a href="http://localhost:8081/">  <button>order now </button></a></div>
     
    </div>
    </div>
</template>



<style>
.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.header{
  background-image:url('../imagee/p.jpg');
  background-position: center;
  background-size: cover;
   height:90vh;
}
.content h1{
  position: absolute;
  top:50%;
  left:50%;
  transform: translate(-50%,-50%);
  color: white;
  font-size: 70px;

}
.content{
  background:rgb(0,0,0,.5);
  height: 90vh;


}
.contentt{
  display:grid;
  grid-template-columns: repeat(3,1fr);
  padding: 30px 20px;
  grid-column-gap: 20px;
  grid-row-gap: 30px;
  background-color: rgb(228, 115, 10);
  color: white;
}
.image1 button{
  background-color: white;
  color:rgb(228, 115, 10);
}
.image1 button:hover{
  background-color: black;
}
.order button{
  background-color: white;
  color:rgb(228, 115, 10);
}
.order button:hover{
   background-color: black; 
}

.image {
  opacity: 1;
  display: inline-block;
   /* width: 100%; */
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}
/* .contentt:hover .image {
  opacity: 0.2;

} */

.image2 {
  opacity: 1;
  /* display: block; */
   /* width: 450px;
  height: auto; */
  transition: .5s ease;
  backface-visibility: hidden;
}

/* .contentt:hover .image2 {
  opacity: 0.2;

} */
.image3 {
  opacity: 1;
  /* display: block; */
   /* width: 450px;
  height: auto; */
  transition: .5s ease;
  backface-visibility: hidden;
}

/* .contentt:hover .image3 {
  opacity: 0.2;
} */
</style>
