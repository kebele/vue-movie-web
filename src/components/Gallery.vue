<template>
  <section class="gallery" id="gallery">
    <h1 class="heading"><span>superheroes</span> gallery</h1>

    <div class="box-container">
      <div class="box">
        <!-- <img src="images/img1-min.png" alt="" /> -->
        <img src="../assets/images/img1-min.png" alt="" />
        <div class="info">
          <h3>captain america</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <!-- <img src="images/img2-min.png" alt="" /> -->
        <img src="../assets/images/img2-min.png" alt="" />

        <div class="info">
          <h3>thor</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img3-min.png" alt="" />
        <div class="info">
          <h3>ant-man</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img4-min.png" alt="" />
        <div class="info">
          <h3>drax</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img5-min.png" alt="" />
        <div class="info">
          <h3>captain marvel</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img6-min.png" alt="" />
        <div class="info">
          <h3>spider-man</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img7-min.png" alt="" />
        <div class="info">
          <h3>doctor strange</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img8-min.png" alt="" />
        <div class="info">
          <h3>black panther</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>

      <div class="box">
        <img src="../assets/images/img9-min.png" alt="" />
        <div class="info">
          <h3>iron-man</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum,
            harum.
          </p>
          <a href="#" class="btn">learn more</a>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.gallery {
  /* background: #f0f0f0; */
  background-image: linear-gradient(
    108.9deg,
    rgba(251, 140, 0, 1) 11.2%,
    rgba(0, 139, 155, 1) 88.9%
  );
}

.gallery .box-container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
}

.gallery .box-container .box {
  flex: 1 1 30rem;
  height: 40rem;
  overflow: hidden;
  /* background: #333; */
  background-image: linear-gradient(
    358.7deg,
    rgba(42, 136, 157, 1) 1.7%,
    rgba(122, 197, 214, 1) 51.1%,
    rgba(211, 232, 242, 1) 95.5%
  );
  text-align: center;
  padding: 2rem;
  margin: 2rem;
  border-radius: 0.5rem;
  position: relative;
}

.gallery .box-container .box img {
  height: 100%;
  object-fit: cover;
}

.gallery .box-container .box .info {
  position: absolute;
  bottom: -120%;
  left: 50%;
  transform: translateX(-50%);
  width: 75%;
  background: #fff;
  padding: 2rem;
  border: 0.3rem solid var(--red);
  border-radius: 0.5rem;
}

.gallery .box-container .box:hover .info {
  bottom: 2rem;
}

.gallery .box-container .box:hover img {
  transform: scale(1.2);
}

.gallery .box-container .box:hover {
  /* background: #111; */
  background-image: radial-gradient(
    circle farthest-corner at 22.4% 21.7%,
    rgba(4, 189, 228, 1) 0%,
    rgba(2, 83, 185, 1) 100.2%
  );
}

.gallery .box-container .box .info h3 {
  background: var(--red);
  color: #fff;
  border-radius: 0.5rem;
  margin: 0 5rem;
  margin-top: -3.7rem;
  padding: 0.5rem 2rem;
  font-size: 2.5rem;
}

.gallery .box-container .box .info p {
  font-size: 2rem;
  color: #666;
  padding: 0.5rem;
  padding-top: 2rem;
}
</style>
