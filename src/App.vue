<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView /> -->
  <div class="gpt">
    <div class="sidebar"></div>
    <div class="main">
        <div class="main-content">
          <div class="main-content_item me">
            <div class="container container_item">
              <div class="logo logo_me">
                <span>TO</span>
              </div>
              <div class="text">ChatGPT không sử dụng một font chữ cụ thể, vì đây là một trình tạo lời nói tự động trên nền tảng web. ChatGPT sử dụng các thư viện mặc định của trình duyệt web để hiển thị văn bản và phông chữ có thể khác nhau trên các trình duyệt khác nhau hoặc trên các thiết bị khác nhau.</div>
            </div>
          </div>
          <div class="main-content_item">
            <div class="container container_item">
              <div class="logo logo_gpt">
                <svg width="41" height="41" viewBox="0 0 41 41" fill="none" xmlns="http://www.w3.org/2000/svg" stroke-width="1.5" class="h-6 w-6"><path d="M37.5324 16.8707C37.9808 15.5241 38.1363 14.0974 37.9886 12.6859C37.8409 11.2744 37.3934 9.91076 36.676 8.68622C35.6126 6.83404 33.9882 5.3676 32.0373 4.4985C30.0864 3.62941 27.9098 3.40259 25.8215 3.85078C24.8796 2.7893 23.7219 1.94125 22.4257 1.36341C21.1295 0.785575 19.7249 0.491269 18.3058 0.500197C16.1708 0.495044 14.0893 1.16803 12.3614 2.42214C10.6335 3.67624 9.34853 5.44666 8.6917 7.47815C7.30085 7.76286 5.98686 8.3414 4.8377 9.17505C3.68854 10.0087 2.73073 11.0782 2.02839 12.312C0.956464 14.1591 0.498905 16.2988 0.721698 18.4228C0.944492 20.5467 1.83612 22.5449 3.268 24.1293C2.81966 25.4759 2.66413 26.9026 2.81182 28.3141C2.95951 29.7256 3.40701 31.0892 4.12437 32.3138C5.18791 34.1659 6.8123 35.6322 8.76321 36.5013C10.7141 37.3704 12.8907 37.5973 14.9789 37.1492C15.9208 38.2107 17.0786 39.0587 18.3747 39.6366C19.6709 40.2144 21.0755 40.5087 22.4946 40.4998C24.6307 40.5054 26.7133 39.8321 28.4418 38.5772C30.1704 37.3223 31.4556 35.5506 32.1119 33.5179C33.5027 33.2332 34.8167 32.6547 35.9659 31.821C37.115 30.9874 38.0728 29.9178 38.7752 28.684C39.8458 26.8371 40.3023 24.6979 40.0789 22.5748C39.8556 20.4517 38.9639 18.4544 37.5324 16.8707ZM22.4978 37.8849C20.7443 37.8874 19.0459 37.2733 17.6994 36.1501C17.7601 36.117 17.8666 36.0586 17.936 36.0161L25.9004 31.4156C26.1003 31.3019 26.2663 31.137 26.3813 30.9378C26.4964 30.7386 26.5563 30.5124 26.5549 30.2825V19.0542L29.9213 20.998C29.9389 21.0068 29.9541 21.0198 29.9656 21.0359C29.977 21.052 29.9842 21.0707 29.9867 21.0902V30.3889C29.9842 32.375 29.1946 34.2791 27.7909 35.6841C26.3872 37.0892 24.4838 37.8806 22.4978 37.8849ZM6.39227 31.0064C5.51397 29.4888 5.19742 27.7107 5.49804 25.9832C5.55718 26.0187 5.66048 26.0818 5.73461 26.1244L13.699 30.7248C13.8975 30.8408 14.1233 30.902 14.3532 30.902C14.583 30.902 14.8088 30.8408 15.0073 30.7248L24.731 25.1103V28.9979C24.7321 29.0177 24.7283 29.0376 24.7199 29.0556C24.7115 29.0736 24.6988 29.0893 24.6829 29.1012L16.6317 33.7497C14.9096 34.7416 12.8643 35.0097 10.9447 34.4954C9.02506 33.9811 7.38785 32.7263 6.39227 31.0064ZM4.29707 13.6194C5.17156 12.0998 6.55279 10.9364 8.19885 10.3327C8.19885 10.4013 8.19491 10.5228 8.19491 10.6071V19.808C8.19351 20.0378 8.25334 20.2638 8.36823 20.4629C8.48312 20.6619 8.64893 20.8267 8.84863 20.9404L18.5723 26.5542L15.206 28.4979C15.1894 28.5089 15.1703 28.5155 15.1505 28.5173C15.1307 28.5191 15.1107 28.516 15.0924 28.5082L7.04046 23.8557C5.32135 22.8601 4.06716 21.2235 3.55289 19.3046C3.03862 17.3858 3.30624 15.3413 4.29707 13.6194ZM31.955 20.0556L22.2312 14.4411L25.5976 12.4981C25.6142 12.4872 25.6333 12.4805 25.6531 12.4787C25.6729 12.4769 25.6928 12.4801 25.7111 12.4879L33.7631 17.1364C34.9967 17.849 36.0017 18.8982 36.6606 20.1613C37.3194 21.4244 37.6047 22.849 37.4832 24.2684C37.3617 25.6878 36.8382 27.0432 35.9743 28.1759C35.1103 29.3086 33.9415 30.1717 32.6047 30.6641C32.6047 30.5947 32.6047 30.4733 32.6047 30.3889V21.188C32.6066 20.9586 32.5474 20.7328 32.4332 20.5338C32.319 20.3348 32.154 20.1698 31.955 20.0556ZM35.3055 15.0128C35.2464 14.9765 35.1431 14.9142 35.069 14.8717L27.1045 10.2712C26.906 10.1554 26.6803 10.0943 26.4504 10.0943C26.2206 10.0943 25.9948 10.1554 25.7963 10.2712L16.0726 15.8858V11.9982C16.0715 11.9783 16.0753 11.9585 16.0837 11.9405C16.0921 11.9225 16.1048 11.9068 16.1207 11.8949L24.1719 7.25025C25.4053 6.53903 26.8158 6.19376 28.2383 6.25482C29.6608 6.31589 31.0364 6.78077 32.2044 7.59508C33.3723 8.40939 34.2842 9.53945 34.8334 10.8531C35.3826 12.1667 35.5464 13.6095 35.3055 15.0128ZM14.2424 21.9419L10.8752 19.9981C10.8576 19.9893 10.8423 19.9763 10.8309 19.9602C10.8195 19.9441 10.8122 19.9254 10.8098 19.9058V10.6071C10.8107 9.18295 11.2173 7.78848 11.9819 6.58696C12.7466 5.38544 13.8377 4.42659 15.1275 3.82264C16.4173 3.21869 17.8524 2.99464 19.2649 3.1767C20.6775 3.35876 22.0089 3.93941 23.1034 4.85067C23.0427 4.88379 22.937 4.94215 22.8668 4.98473L14.9024 9.58517C14.7025 9.69878 14.5366 9.86356 14.4215 10.0626C14.3065 10.2616 14.2466 10.4877 14.2479 10.7175L14.2424 21.9419ZM16.071 17.9991L20.4018 15.4978L24.7325 17.9975V22.9985L20.4018 25.4983L16.071 22.9985V17.9991Z" fill="currentColor"></path></svg>
              </div>
              <div class="text">ChatGPT không sử dụng một font chữ cụ thể, vì đây là một trình tạo lời nói tự động trên nền tảng web. ChatGPT sử dụng các thư viện mặc định của trình duyệt web để hiển thị văn bản và phông chữ có thể khác nhau trên các trình duyệt khác nhau hoặc trên các thiết bị khác nhau.</div>
            </div>
          </div>
        </div>
        <div class="main-form">
          <audio :src="audio" id="audio"></audio>
          <button @click="startRecording">Record</button>
          <button @click="endRecording">End</button>
          <svg xmlns="http://www.w3.org/2000/svg" width="52" height="56"><g fill="none" fill-rule="evenodd"><path d="M15.614 1.265c3.137-.64 7.88 0 10.902.638 3.022.639 6.122 2.356 7.378 5.262 1.257 2.906 2.015 7.794 1.61 10.524-.406 2.731-3.442 6.736-4.151 8.193-1.018 1.381-1.96 2.645-2.676 3.439-.715.793-4.03 1.574-6.265 2.178-2.236.604-5.36 0-6.798 0-1.438 0-1.9.15-3.207 0-1.308-.15-4.375-2.337-4.666-3.716-.195-.919-.041-2.171.46-3.758-.631-1.003-.967-1.551-1.009-1.647-1.386-3.196-2.101-5.387-2.146-6.572-.047-1.239.006-2.122.16-2.648C4.67 14.44 3.98 15.08 3.132 15.08c-1.271 0-1.558-.817-1.93-1.923-.37-1.107-.219-2.85.33-4.653.547-1.802 1.51-3.516 2.27-3.954 2.606-1.5 3.938-1.82 5.515-1.5 1.127.229 3.16-1.146 6.297-1.784z" fill="#FFF"/><path d="M7.703 31.751l-2.525 4.375L3.38 43.36l-.843 3.336v3.801l.843 2.95h2.691l2.955-3.384h4.326l1.026 3.383 3.282.63 2.44-2.575 1.439.568.963 2.006L32.306 53l5.53-3.432v-2.872c2.65-2.239 4.499-4.091 5.55-5.559 1.051-1.467 1.534-2.869 1.448-4.206l-7.708 3.52-3.34-5.613-4.811-7.685-21.272 4.6z" fill="#FFF"/><path d="M21.768 31.763c2.251 2.151 3.793 3.769 4.626 4.854.833 1.085 1.977 1.905 3.432 2.462.11 1.815.51 3.484 1.204 5.005.693 1.522 2.875 3.57 6.546 6.144L38.69 47.9l-1.81-6.518-1.65-5.719-2.057-3.444-2.944-3.528h-1.094l-3.86 2.446-3.507.626zM14.076 2.538c-1.484 2.681-2.827 4.531-4.03 5.55-2.025 1.715-.903 6.196-3.537 8.296-.632 0-1.415-.551-2.35-1.653H1.734L1 10.504l1.046-2.416 1.242-2.612 3.22-1.787 7.568-1.15z" fill="#B97A57"/><path d="M15.614 1.265c3.137-.64 7.88 0 10.902.638 3.022.639 6.122 2.356 7.378 5.262 1.257 2.906 2.015 7.794 1.61 10.524-.406 2.731-3.442 6.736-4.151 8.193-1.018 1.381-1.96 2.645-2.676 3.439-.715.793-4.03 1.574-6.265 2.178-2.236.604-5.36 0-6.798 0-1.438 0-1.26-.258-2.802-.702-1.54-.445-3.203-1.449-3.495-2.827-.194-.919-.566-2.234-1.116-3.945-.631-1.003-.967-1.551-1.009-1.647-1.386-3.196-2.101-5.387-2.146-6.572-.047-1.239.006-2.122.16-2.648C4.67 14.44 3.98 15.08 3.132 15.08c-1.271 0-1.558-.817-1.93-1.923-.37-1.107-.219-2.85.33-4.653.547-1.802 1.51-3.516 2.27-3.954 2.606-1.5 3.938-1.82 5.515-1.5 1.127.229 3.16-1.146 6.297-1.784z" stroke="#222" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M29.437 7.923c-.864 3.191-1.352 5.182-1.462 5.972-.166 1.186 0 2.1 1.13 2.86 1.132.76 2.949.296 3.447-.267l2.29-2.593M9.43 29.46c-2.69 4.861-4.39 8.73-5.102 11.609-1.066 4.317-2.505 9.712-1.381 11.427 1.123 1.714 2.584 1.672 3.931 1.497 1.22-.475 2.594-3.61 4.121-9.407m-1.538 5.258h3.846m3.29-5.769c-1.454 3.002-2.294 5.467-2.52 7.394 0 2.922 2.943 2.594 3.457 2.594.514 0 2.502-.988 3.237-3.56.735-2.57 1.498-2.7 2.535-6.428m6.806 3.871c-2.57.425-4.739 1.02-6.508 1.788-2.515 1.452-1.38 2.92-1.131 3.353.25.433 2.038.784 4.445.501 2.057-.241 4.417-.633 7.576-1.698 1.757-.592 3.53-2 4.087-3.088.717-1.809-.133-4.13-.926-7.003a38.846 38.846 0 0 0-2.483-6.632c-.735-1.518-2.364-3.957-4.887-7.318m8.888 17.764c2.919-2.405 4.722-4.234 5.409-5.49.686-1.254 1.03-3.27 1.03-6.048-1.22 2.567-2.631 4.302-4.232 5.205-1.6.904-2.754 1.512-3.46 1.825" stroke="#222" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.228 17.942c1.145.174 2.243-.365 2.452-1.205.21-.84-.506-1.832-1.6-2.216-1.092-.383-2.19.156-2.451 1.206-.262 1.049.454 2.04 1.599 2.215zm10.129 2.525c1.145.175 2.243-.365 2.452-1.205.21-.84-.506-1.832-1.6-2.215-1.092-.384-2.19.156-2.451 1.205-.262 1.05.454 2.041 1.599 2.215z" fill="#222"/><g transform="rotate(14 -67 70.792)"><ellipse fill="#222" cx="5.219" cy="1.468" rx="2.088" ry="1.468"/><path d="M3.42 3.911c.855-.303 1.51-.462 1.966-.476.456-.014.836.114 1.14.382l-.263 3.036H4.176L3.42 3.91z" fill="#FF8D90"/><path d="M9.526 2.738c-.496.59-1.068 1.179-2.085 1.179-1.016 0-1.758-.327-2.224-.98M.496 2.778c.284.49 1.098 1.137 2.115 1.137 1.016 0 1.758-.327 2.225-.98m1.912 1.283l-.155 1.5c0 .627-.754 1.135-1.619 1.135s-1.566-.508-1.566-1.134l.138-1.561" stroke="#222" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></g><path d="M42.536 32.537c1.266-1.539 2.548-2.308 3.846-2.308 1.947 0 3.361 1.154 3.846 2.308m-4.57-6.035c.978-.376 1.998-.263 3.059.34 1.061.605 1.807 1.437 2.236 2.499" stroke="#222" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M20.999 51.06l1.282.404" stroke="#222" stroke-width="2" stroke-linecap="square" stroke-linejoin="round"/></g></svg>
        </div>
    </div>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400&display=swap');
.gpt {
  font-family: 'Montserrat', sans-serif;
  position: fixed;
  width: 100%;
  height: 100%;
  display: flex;
  left: 0;
  top: 0;
  .sidebar {
    width: 231px;
    height: 100%;
    background-color: #202123;
  }
  .main {
    background-color: #434654;
    width: calc(100% - 231px);
    height: 100%;
    &-content {
      width: 100%;
      height: calc(100% - 231px);
      &_item {
        display: flex;
        background-color: #434654;
        padding: 25px 0;
        .logo {
          width: 35px;
          height: 35px;
          
          border-radius: 3px;
          display: flex;
          align-items: center;
          justify-content: center;
          margin-right: 25px;
          svg {
            width: 24px;
            height: 24px;
            color: #fff;
          }
          span {
            font-weight: bold;
            color: #fff;
          }
        }
        .logo_gpt {
          background-color: #0BA37F;
        }
        .logo_me {
          background-color: #be50ad;
        }
        .text {
          font-size: 16px;
          width: calc(100% - 87px);
          color: #fff;
          letter-spacing: 1px;
        }
        .container {
          width: 760px;
          margin: 0 auto;
          &_item {
            display: flex;
            gap: 20px;
          }
        }
      }
      .me {
        background-color: #343541;
      }

    }
    &-form {
      height: 231px;
      background-color: #343740;
      background-image: linear-gradient(rgba(53, 55, 64, 0), rgb(53, 55, 64) 58.85%);
      border-top: 0.1px solid #bbb;
    }
  }
}
</style>

<script lang="ts" setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'


import { ref, onMounted } from "vue";

// import webkitSpeechRecognition from 'webkitSpeechRecognition';

const questions = ref([]);

const data= ref('');

let audio = ref();



const recognition = ref();

const startRecording = async () => {

  // if ('speechSynthesis' in window) {
  //   console.log("co");

  //   const synth = window.speechSynthesis;

  //   const utterance = new SpeechSynthesisUtterance();

  //   console.log(window);
    
  //   utterance.text  = 'ChatGPT không sử dụng một';
  //   utterance.lang  = 'vi';
  //   utterance.voice = speechSynthesis.getVoices()[0];
  //   utterance.pitch = 1;
  //   utterance.rate  = 1;
  //   console.log(speechSynthesis.getVoices());

  //   let a = new SpeechRecognitionAlternative();
  //   // a.transcript;
  //   let b = new SpeechRecognitionResult();
  //   let c = new SpeechRecognitionResultList();

  //   console.log(b.item);
  

  //   synth.speak(utterance)
  //   // speechSynthesis.speak(utterance);
  //   // console.log(utterance);
  // }
  // else {
  //   console.log("khong");
  // }

  // return;
  try {
    const stream:any = await navigator.mediaDevices.getUserMedia({ audio: true });

    recognition.value = new MediaRecorder(stream);
    recognition.value.start();
    recognition.value.onstart = (event:any) => {
      console.log(event, "start");
    }
    recognition.value.ondataavailable = (event:any) => {
      console.log(event, 'available');
      data.value = event.data;
      
    }

  
    
    // recognition.addEventListener('dataavailable', (event) => {
    //   console.log(event);
    // })

    // recognition.addEventListener('stop', () => {
    //   console.log("stopped");
    // })
  }
  catch(error) {
    console.error('Error accessing microphone:', error);
  }

  // recognition.ondataavailable = async (event) => {
  //   console.log(event);

  // }
}

const endRecording = () => {
  recognition.value.stop();
  recognition.value.onstop = (event:any) => {
    console.log(event);
    let dataBlog = data.value;

    const blob = new Blob([dataBlog], { type: "audio/webm; codecs=opus" });
    let audioUrl = URL.createObjectURL(blob);
    console.log(audioUrl);

    // audio.value = audioUrl;
    // console.log(data.value, 'data');

    const audioTag = document.createElement("audio");
    audioTag.src = audioUrl;
    audioTag.play();

  }
}


onMounted(async () => {
  
})

const createChatGPT = async (content:any) => {
    let url = 'http://localhost:3000/api/chatGpt';
    let response = await fetch(url, {
        method: "POST",
        headers: {
            "Content-Type": "application/json",
        },
        body: JSON.stringify({
            'content': content
        }),
    });
    const jsonData = await response.json();
    console.log(jsonData);
    return jsonData.message.content;
}

</script>
<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }
  

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
