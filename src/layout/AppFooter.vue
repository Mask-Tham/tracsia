<template>
    <footer class="footer text-white has-cards">
        <!-- <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/landing.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/profile.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
        </div> -->
        <div class="container">
      
           
            <div class="row  justify-content-md-between">
                <div class="col-md-4 col-lg-8">
                 <div style="position: relative">
          <img
            style="width: 275px; height: 130px"
            src="img/brand/image/logo_darkmode.png"
            alt="logo"
          />
        
        </div>
                    <!-- <div class="copyright">
                        &copy; {{year}}
                        <a href="https://www.creative-tim.com" target="_blank" rel="noopener">Creative Tim</a> & <a href="https://www.binarcode.com" target="_blank" rel="noopener">Binar Code</a>
                    </div> -->
                </div>
                <div class="col-md-4  col-lg-2">
                    <!-- <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="https://www.creative-tim.com" class="nav-link" target="_blank" rel="noopener">Creative Tim</a>
                        </li>
                        <li class="nav-item">
                            <a href="https://www.creative-tim.com/presentation" class="nav-link" target="_blank" rel="noopener">About
                                Us</a>
                        </li>
                        <li class="nav-item">
                            <a href="http://blog.creative-tim.com" class="nav-link" target="_blank" rel="noopener">Blog</a>
                        </li>
                        <li class="nav-item">
                            <a href="https://github.com/creativetimofficial/argon-design-system/blob/master/LICENSE.md"
                               class="nav-link" target="_blank" rel="noopener">MIT License</a>
                        </li>
                    </ul> -->
                        <ul class="list-unstyled ">
                            <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <h5 class="mb-0 text-white">About us</h5>
                            </div>
                            </li>
                            <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <p class="mb-0">About us</p>
                            </div>
                            </li>
                            <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <p class="mb-0">Team</p>
                            </div>
                            </li>
                             <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <p class="mb-0">Career</p>
                            </div>
                            </li>
                             <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <p class="mb-0">Services</p>
                            </div>
                            </li>
                             <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <p class="mb-0">Contact</p>
                            </div>
                            </li>
                        </ul> 
                 </div>
                    <div class="col-md-4 col-lg-2">
                
                           <ul class="list-unstyled ">
                            <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                                <h5 class="mb-0 text-white">Contact</h5>
                            </div>
                            </li>
                            <li >
                            <div class="d-flex align-items-center">
                            
                             <p>
                3280 Thompson Drive Oakland <br/> CA California 94621
              </p>
                            </div>
                            </li>
                              
                            <li >
                            <div class="d-flex align-items-center">
                            
                             <p>
                mike101050@omtecha.com 
              </p>
                            </div>
                            </li>
                              <li >
                            <div class="d-flex align-items-center">
                            
                             <p>
               
                (+66) 510-430-6581
              </p>
                            </div>
                            </li>
                             <li class="py-2">
                            <div class="d-flex align-items-center">
                            
                            
                    <a target="_blank" rel="noopener" href="https://twitter.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-twitter"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://www.facebook.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Like us">
                        <i class="fa fa-facebook-square"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://dribbble.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-dribbble"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://github.com/creativetimofficial"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa fa-github"></i>
                    </a>
              
                            </div>
                            </li>
                           
                        </ul> 
                 </div>
              
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
