<template>
  <section class="movies" id="movies">
    <h1 class="heading"><span>marvel</span> movies</h1>

    <div class="box-container">
      <div class="box">
        <img src="../assets/images/m1-min.jpg" alt="" />
        <div class="info">
          <h3>marvel avengers 2012</h3>
          <span> action, sci-fi, thriller, comedy </span>
          <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero eos
            sint velit magni. Exercitationem modi assumenda odio, enim sequi
            voluptatem.
          </p>
          <a href="#" class="btn">watch online</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/m2-min.jpg" alt="" />
        <div class="info">
          <h3>avengers age of ultron</h3>
          <span> action, sci-fi, thriller, comedy </span>
          <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero eos
            sint velit magni. Exercitationem modi assumenda odio, enim sequi
            voluptatem.
          </p>
          <a href="#" class="btn">watch online</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/m3-min.jpg" alt="" />
        <div class="info">
          <h3>captain america civil war</h3>
          <span> action, sci-fi, thriller, comedy </span>
          <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero eos
            sint velit magni. Exercitationem modi assumenda odio, enim sequi
            voluptatem.
          </p>
          <a href="#" class="btn">watch online</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/m4-min.jpg" alt="" />
        <div class="info">
          <h3>avengers infinity war</h3>
          <span> action, sci-fi, thriller, comedy </span>
          <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero eos
            sint velit magni. Exercitationem modi assumenda odio, enim sequi
            voluptatem.
          </p>
          <a href="#" class="btn">watch online</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/m5-min.jpg" alt="" />
        <div class="info">
          <h3>thor ragnarok</h3>
          <span> action, sci-fi, thriller, comedy </span>
          <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero eos
            sint velit magni. Exercitationem modi assumenda odio, enim sequi
            voluptatem.
          </p>
          <a href="#" class="btn">watch online</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/m6-min.jpg" alt="" />
        <div class="info">
          <h3>avengers endgame</h3>
          <span> action, sci-fi, thriller, comedy </span>
          <div class="stars">
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero eos
            sint velit magni. Exercitationem modi assumenda odio, enim sequi
            voluptatem.
          </p>
          <a href="#" class="btn">watch online</a>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.movies {
  /* background: #222; */
  background-image: linear-gradient(
    171.8deg,
    rgba(5, 111, 146, 1) 13.5%,
    rgba(6, 57, 84, 1) 78.6%
  );
}

.movies .heading span {
  color: #fff;
}

.movies .box-container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
}

.movies .box-container .box {
  flex: 1 1 30rem;
  height: 40rem;
  overflow: hidden;
  position: relative;
  margin: 2rem;
  box-shadow: 0 0.3rem 0.5rem #000;
}

.movies .box-container .box img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.movies .box-container .box .info {
  padding: 2rem;
  width: 100%;
  position: absolute;
  bottom: -100%;
  left: 0;
  background: rgba(0, 0, 0, 0.7);
}

.movies .box-container .box:hover .info {
  bottom: 0;
}

.movies .box-container .box .info h3 {
  font-size: 3rem;
  color: #fff;
  padding-bottom: 0.5rem;
}

.movies .box-container .box .info span {
  font-size: 2rem;
  color: var(--red);
}

.movies .box-container .box .info .stars i {
  font-size: 2rem;
  color: orange;
  padding: 1rem 0.1rem;
}

.movies .box-container .box .info p {
  font-size: 2rem;
  color: #ccc;
  padding: 0.5rem 0;
}
</style>
