
<template>
  <div class="text">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <div class="w3-container">
        <p><i class="fa fa-spinner w3-spin" style="font-size:72px"></i></p>
    </div>
    <a class="title">
      JINGYAO GU
    </a>
    <a class="subtitle">
      MCS @UIUC 2022-2023<br>
      CS & AMS @Macalester 2018-2022<br>    
      <span class="Introtext">Web Development</span><br>
      <span class="Introtext">Game Development</span><br>
      <span class="Introtext">Data Analysis</span><br>
      <span class="Introtext">Database</span><br>
      <span class="Introtext">UI/UX Design</span>
    </a>
    <div class="links">
      <div class="actual_link" @click="github">
        <img src="@/assets/Git.png" />
      </div>
      <div class="actual_link" @click="linkedin">
        <img src="@/assets/LinkedIn.png" />
      </div>
      <div class="actual_link" @click="email">
        <img src="@/assets/Gmail.png" />
      </div>
      <div class="actual_link" @click="wechat">
        <img src="@/assets/Wechat.png" />
      </div>
      <div class="avatar">
			<img src="@/assets/self1.jpg" />
      </div>
    </div>
  </div>

  <a class="social-link social-link--dribbble" id="dribbble">
    <svg class="social-svg" viewBox="0 0 600 600" xmlns="http://www.w3.org/2000/svg">
      <g class="social-group" fill="none" fill-rule="evenodd">
        <circle class="social-group__outline" stroke="#000" stroke-width="20" cx="300" cy="300" r="262.5" />
        <circle class="social-group__inner-circle" fill="#F5DADF" cx="300" cy="300" r="252.5" />
        <path class="social-group__icon" d="M446.58 270.912c-1.944-9.528-4.866-18.912-8.646-27.876-3.714-8.802-8.322-17.274-13.674-25.194-5.31-7.854-11.4-15.234-18.108-21.936-6.702-6.714-14.088-12.81-21.936-18.108-7.92-5.37-16.404-9.96-25.194-13.686-8.964-3.774-18.342-6.702-27.876-8.634-9.762-2.004-19.818-3.024-29.862-3.024-10.056 0-20.1 1.02-29.874 3.024-9.528 1.932-18.912 4.866-27.87 8.634-8.79 3.726-17.274 8.322-25.206 13.686-7.854 5.298-15.234 11.388-21.936 18.108-6.708 6.702-12.792 14.088-18.096 21.936-5.358 7.92-9.96 16.392-13.674 25.194-3.798 8.964-6.708 18.348-8.658 27.876-1.998 9.75-3.012 19.806-3.012 29.856 0 10.068 1.014 20.124 3.012 29.88 1.95 9.528 4.866 18.912 8.652 27.87 3.714 8.79 8.322 17.286 13.674 25.206 5.304 7.854 11.388 15.222 18.096 21.936 6.702 6.702 14.088 12.786 21.936 18.096 7.932 5.358 16.416 9.96 25.206 13.674 8.952 3.798 18.342 6.69 27.87 8.646 9.774 2.016 19.818 3.024 29.874 3.024 10.044 0 20.1-1.008 29.862-3.024 9.54-1.956 18.912-4.854 27.876-8.646 8.79-3.714 17.274-8.322 25.194-13.674 7.854-5.31 15.234-11.388 21.936-18.096 6.702-6.714 12.798-14.088 18.108-21.936 5.358-7.92 9.96-16.416 13.674-25.206 3.786-8.952 6.702-18.342 8.646-27.87 2.004-9.762 3.012-19.818 3.012-29.88.006-10.05-1.002-20.106-3.006-29.856zm-18.684 28.602c-1.83-.396-44.694-9.624-88.218-4.152-.888-2.166-1.794-4.35-2.73-6.54-2.634-6.198-5.472-12.342-8.424-18.372 50.028-20.412 70.338-49.782 70.572-50.13 17.766 21.564 28.512 49.128 28.8 79.194zm-42.96-93.804c-.318.492-18.354 27.948-66.162 45.87-21.654-39.786-45.444-71.388-47.346-73.896 9.576-2.322 19.56-3.576 29.85-3.576 32.076 0 61.338 11.952 83.658 31.602zm-114-27.924c0 .012-.024.024-.024.024s-.138.036-.372.084c.126-.036.27-.06.396-.108zm-23.706 8.424c1.686 2.262 25.116 34.02 47.04 72.984-60.822 16.158-113.604 15.528-116.952 15.468 8.232-39.234 34.59-71.766 69.912-88.452zm-72.618 114.558c0-1.35.06-2.67.108-4.002 2.232.048 64.824 1.47 130.038-18.048 3.63 7.104 7.104 14.322 10.278 21.534-1.674.468-3.342.972-4.992 1.512-68.358 22.092-103.032 83.604-103.032 83.604s.048.036.048.06c-20.166-22.446-32.448-52.116-32.448-84.66zm126.666 126.678c-30.654 0-58.77-10.896-80.682-29.028 1.662 1.35 2.838 2.214 2.838 2.214s24.282-52.956 99.396-79.128c.282-.108.564-.186.846-.27 17.826 46.314 25.182 85.104 27.06 96.174-15.204 6.468-31.914 10.038-49.458 10.038zm70.782-21.606c-1.29-7.65-8.04-44.826-24.654-90.48 40.884-6.54 76.326 4.674 78.936 5.532-5.64 35.292-25.842 65.736-54.282 84.948z"
          fill="#000" fill-rule="nonzero" />
      </g>
    </svg>
  </a>
  



</template>

<script>
export default {
  name: 'HeroText',
  methods: {
    github: function () {   
      window.open("https://github.com/RaymondJYGu", "_blank");    
    },
    linkedin: function () {   
      window.open("https://www.linkedin.com/in/jingyao-gu-1496b1168/", "_blank");    
    },
    email: function () {   
      window.open("mailto:gjyraymond@gmail.com", "_blank");    
    },
    wechat: function () {   
      window.open("https://www.linkedin.com/in/jingyao-gu-1496b1168/", "_blank");    
    },
  }
}
</script>

<style scoped>
.text {
  position: -webkit-sticky;
  position: sticky;
  z-index: 100;
  top: 0%;
  left: 0%;
  height: 100%;
  width: 1000%;
  padding: 100px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  font-family: Arial;
}
.Introtext {
  color: #a93058;
  font-family: Monaco;
}
.title {
  position: relative;
  width: 100%;
  color: #123c69;
  font-size: 72px;
  font-weight: 300;
  letter-spacing: 15px;
  margin-bottom: 20px;
  font-family: Monaco;
}
.subtitle {
  position: relative;
  width: 100%;
  max-width: 800px;
  color: #81787c;
  font-size: 30px;
  letter-spacing: 2px;
  line-height: 40px;
  font-family: Monaco;
}
.links {
  position: relative;
  width: 100%;
  margin-top: 20px;
  display: flex;
  align-items: center;
}
.actual_link {
  position: relative;
  width: 60px;
  height: 60px;
  margin-right: 20px;
  border-radius: 8px;
  cursor: pointer;
  transition: 1s cubic-bezier(0.075, 0.82, 0.165, 1) all;
  display: flex;
  justify-content: center;
  align-items: center;
}
.actual_link:hover {
  border-color: #123c69;
  box-shadow: 0 0 8px 2px #123c69;
}
.actual_link:hover img {
  filter: drop-shadow(0 0 8px #123c69);
}

@keyframes float {
	0% {
		box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
		transform: translatey(0px);
	}
	50% {
		box-shadow: 0 25px 15px 0px rgba(0,0,0,0.2);
		transform: translatey(-20px);
	}
	100% {
		box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
		transform: translatey(0px);
	}
}

.avatar {
	width: 150px;
	height: 150px;
	box-sizing: border-box;
	border: 5px rgb(239, 235, 235) solid;
	border-radius: 50%;
	overflow: hidden;
	box-shadow: 30px 35px 35px 30px rgba(0,0,0,0.6);
	transform: translatey(0px);
	animation: float 4s ease-in-out infinite;
	img { width: 100%; height: 100%; }
}

</style>