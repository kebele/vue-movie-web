<template>
  <div class="footer">
    <div class="share">
      <a href="#"> <i class="fab fa-youtube"></i> youtube </a>
      <a href="#"> <i class="fab fa-facebook-f"></i> facebook </a>
      <a href="#"> <i class="fab fa-twitter"></i> twitter </a>
      <a href="#"> <i class="fab fa-instagram"></i> instagram </a>
      <a href="#"> <i class="fab fa-linkedin"></i> linkedin </a>
    </div>

    <h1 class="credit">
      created by <a href="#"> mr. web designer </a> all rights reserved!
    </h1>
  </div>
</template>
<style>
.footer {
  text-align: center;
  background: #222;
}

.footer .share {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  padding: 2rem 0;
}

.footer .share a {
  font-size: 2rem;
  color: #ccc;
  padding: 2rem;
}

.footer .share a:hover {
  color: #eee;
}

.footer a:hover {
  text-decoration: underline;
}

.footer .credit {
  padding: 2rem 1rem;
  font-size: 3rem;
  color: #fff;
  background: #111;
}

.footer .credit a {
  color: var(--red);
}
</style>
