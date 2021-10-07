<template>
  <div>
    <section class="home" id="home">
      <div class="content">
        <h3>amazing marvel movies</h3>
        <h1>welcome marvel fans</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus
          suscipit eum obcaecati dolorem unde. Iusto possimus sequi officiis
          harum architecto! Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Alias, earum!
        </p>
        <a href="#" class="btn">get started</a>
      </div>

      <div class="image">
        <img src="../assets/images/home-bg-min.jpg" alt="" />
      </div>
    </section>
  </div>
</template>
<style>
.home {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  /* background-image: radial-gradient( circle farthest-corner at 32.7% 82.7%,  rgba(173,0,171,1) 8.3%, rgba(15,51,92,1) 79.4% ); */
  background: linear-gradient(
    110.1deg,
    rgba(30, 2, 83, 1) 44.2%,
    rgba(198, 55, 160, 1) 138.2%
  );
  /* url(~static/images/home-bg-min.jpg) no-repeat; */
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}

.home .image {
  flex: 1 1 40rem;
}

.home .image img {
  width: 100%;
}

.home .content {
  flex: 1 1 40rem;
  padding: 4rem 0;
}

.home .content h3 {
  color: var(--red);
  font-size: 4rem;
  padding-bottom: 1rem;
}

.home .content h1 {
  color: #fff;
  font-size: 6rem;
}

.home .content p {
  color: #aaa;
  font-size: 2.5rem;
  padding: 1rem 0;
}
</style>
