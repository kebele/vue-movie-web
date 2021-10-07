<template>
  <section class="about" id="about">
    <h1 class="heading"><span>about</span> avengers</h1>

    <div class="row">
      <div class="image">
        <img src="../assets/images/about-img-min.png" alt="" />
      </div>

      <div class="content">
        <h3>marvel avengers is amazing</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque,
          optio consequuntur. Iusto molestias harum, doloremque recusandae at
          voluptate et voluptatibus, dolore, in reiciendis pariatur. Veritatis
          dicta ab dolor dignissimos eius!
        </p>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptates
          maxime nulla fuga ratione et commodi expedita qui suscipit culpa
          similique.
        </p>
        <a href="#" class="btn">learn more</a>
      </div>
    </div>
  </section>
</template>
<style>
.about {
  /* background: #eee; */
  background-image: linear-gradient(
    109.6deg,
    rgba(255, 207, 84, 1) 11.2%,
    rgba(255, 158, 27, 1) 91.1%
  );
  padding-bottom: 3rem;
}

.about .row {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
}

.about .row .image {
  flex: 1 1 40rem;
  padding: 2rem 0;
  text-align: center;
}

.about .row .image img {
  height: 50rem;
}

.about .row .content {
  flex: 1 1 40rem;
}

.about .row .content h3 {
  font-size: 5.5rem;
  color: #333;
}

.about .row .content p {
  font-size: 2.2rem;
  color: #666;
  padding: 1rem 0;
}
</style>
