<template>
  <section class="product" id="product">
    <h1 class="heading"><span>marvelous</span> products</h1>

    <div class="box-container">
      <div class="box">
        <h3>product 1</h3>
        <img src="../assets/images/p1-min.png" alt="" />
        <div class="price">$30.00</div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit
          fugiat perspiciatis libero mollitia non accusamus recusandae modi iste
          harum animi?
        </p>
        <a href="#" class="btn">add to cart</a>
      </div>

      <div class="box">
        <h3>product 2</h3>
        <img src="../assets/images/p2-min.png" alt="" />
        <div class="price">$30.00</div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit
          fugiat perspiciatis libero mollitia non accusamus recusandae modi iste
          harum animi?
        </p>
        <a href="#" class="btn">add to cart</a>
      </div>

      <div class="box">
        <h3>product 3</h3>
        <img src="../assets/images/p3-min.png" alt="" />
        <div class="price">$30.00</div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit
          fugiat perspiciatis libero mollitia non accusamus recusandae modi iste
          harum animi?
        </p>
        <a href="#" class="btn">add to cart</a>
      </div>

      <div class="box">
        <h3>product 4</h3>
        <img src="../assets/images/p4-min.png" alt="" />
        <div class="price">$30.00</div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit
          fugiat perspiciatis libero mollitia non accusamus recusandae modi iste
          harum animi?
        </p>
        <a href="#" class="btn">add to cart</a>
      </div>
    </div>
  </section>
</template>
<style>
.product {
  /* background: #eee; */
  background-image: linear-gradient(
    89.8deg,
    rgba(42, 93, 38, 1) 7.8%,
    rgba(162, 226, 175, 1) 94.2%
  );
}

.product .box-container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
}

.product .box-container .box {
  margin: 1rem;
  padding: 2rem;
  background: #fff;
  border: 0.1rem solid rgba(0, 0, 0, 0.1);
  text-align: center;
  width: 27rem;
}

.product .box-container .box:hover {
  box-shadow: 0 0.7rem 1rem rgba(0, 0, 0, 0.1);
}

.product .box-container .box img {
  margin: 2rem 0;
  height: 17rem;
}

.product .box-container .box h3 {
  color: #444;
  font-size: 3rem;
}

.product .box-container .box p {
  color: #999;
  font-size: 2rem;
  padding: 1rem 0;
}

.product .box-container .box .price {
  color: #666;
  font-size: 3rem;
}
</style>
