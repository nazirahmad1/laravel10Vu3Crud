<template>

  <div class="container">
    <header>
      <div class="px-3 py-2 bg-light">
        <div class="container text-center">
          <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
            <router-link to="/" class="d-flex align-items-center my-2 my-lg-0 me-lg-auto text-white text-decoration-none">
            
            </router-link>
            <ul class="nav col-12 col-lg-auto my-2 justify-content-center my-md-0 text-small">
              <li>
                  <router-link to="/" class="nav-link text-dark">Home</router-link>
              </li>
              <li>
                  <router-link to="/products/create" class="nav-link text-dark">Add Product</router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
  
    <div class="card">
      <div class="card-body">
        <div class="container-fluid">
          <router-view></router-view>
        </div>
      </div>
    </div>
  
  </div>
  
  </template>
  
  <script>
  export default {
    name: 'App'
  }
  </script>