<template>
  <div class="home flex-grow-1 d-flex flex-column">
    <div class="row">
      <div class="col-md-5 d-flex align-items-center">
        <div class="welcome shadow m-5 py-5 px-3">
          <h5>Welcome, my name is <span class="name text-nowrap">Kevin Powell</span></h5>
          <h5 class="mt-3">
            Software Developer
          </h5>
        </div>
      </div>
      <div class="col-md-6">
        <div class="mt-2">
          <img src="../src/assets/img/profile.png" alt="">
        </div>
      </div>
    </div>
    <div class="row mt-3">
      <div class="col">
        <h2 class="pl-5">
          About Me
        </h2>
        <p class="p-5">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis, laudantium aut sint natus placeat temporibus voluptate esse fugit exercitationem ab veritatis ea voluptas et maxime officiis magnam provident velit sit!
          At, illum beatae. Repudiandae fugiat expedita animi at eum optio sint, cupiditate, fugit obcaecati illum dolorum et impedit doloremque consequatur perspiciatis. Magnam odio sit voluptas hic eligendi debitis. Modi, incidunt?
          Cupiditate reprehenderit ea eius eligendi commodi nesciunt, cumque, nulla, officiis sed fugiat neque deserunt. Cumque repellendus doloribus earum a assumenda similique voluptate delectus, error dignissimos voluptatum aspernatur numquam! Aut, laudantium!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home{
  user-select: none;
  > img{
    height: 200px;
    width: 200px;
  }
}
.home{
  background-color: var(--secondary);
}
.name{
  font-size: 48px;
  color:#e8e4f5;
  text-shadow: 2px 2px black;
}
</style>
