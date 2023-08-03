<template>
  <!-- <div>
    <router-link :to="{ name: 'SplashScreen' }">Splash</router-link> |

  </div> -->

  <!-- <router-view /> -->
  <SplashScreenPage/>
  <SignInPage /> 
  <SignUpPage/>
  <ForgotPasswordPage/>
  <WelcomeBackPage/>
  <HomePage/>
  <CameraSearchPage/>
  <SearchCameraResultPage/>
</template>

<script setup>
// import router from './router';

// import CategorySlider from '@/components/sections/CategorySlider.vue'
// import CategoriesSection from '@/components/sections/CategoriesSection.vue'

// import HomePage from './pages/public/HomePage.vue'
//import SplashScreenPage from './pages/public/SplashScreenPage.vue'
//import SignInPage from './pages/public/SignInPage.vue'
//import SignUpPage from './pages/public/SignUpPage.vue'
//import ForgotPasswordPage from './pages/public/ForgotPasswordPage.vue'
//import RecoveryPage from './pages/public/RecoveryPage.vue'
//import NewPasswordPage from './pages/public/NewPasswordPage.vue'
// import PwResetSuccessPage from './pages/public/PwResetSuccessPage.vue'
//import WelcomeBackPage from './pages/public/WelcomeBackPage.vue'
//import HomePage from './pages/public/HomePage.vue'
//import CameraSearchPage from './pages/public/CameraSearchPage.vue'
import SearchCameraResultPage from './pages/public/SearchCameraResultPage.vue'
</script>


<style>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 400px;
  height: 850px;
  background-color: #d0cccc;
}

.margin {
  margin-left: 10px;
}
</style>