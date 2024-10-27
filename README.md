/* From Uiverse.io by SmookyDev */ 
<div class="center_div">
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
</div>
/* From Uiverse.io by SmookyDev */ 
.center_div {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 5px;
}

.wave {
  width: 1.8rem;
  height: 150px;
  background-color: #ff6b6b;
  margin: 0 4px;
  border-radius: 0.4rem;
  animation: wave 1.5s linear infinite;
  transform-origin: center;
}

@keyframes wave {
  0% {
    transform: scale(0);
    filter: hue-rotate(90deg) blur(100px);
  }
  25% {
    transform: scale(0);
    filter: hue-rotate(120deg) blur(50px);
  }
  50% {
    transform: scale(1);
    filter: hue-rotate(180deg) blur(25px);
  }
  25% {
    transform: scale(0);
    filter: hue-rotate(360deg) blur(2px);
  }
  100% {
    transform: scale(0);
    filter: hue-rotate(0deg) blur(0);
  }
}

.wave:nth-child(2) {
  animation-delay: 0.1s;
}

.wave:nth-child(3) {
  animation-delay: 0.2s;
}

.wave:nth-child(4) {
  animation-delay: 0.3s;
}

.wave:nth-child(5) {
  animation-delay: 0.4s;
}

.wave:nth-child(6) {
  animation-delay: 0.5s;
}

.wave:nth-child(7) {
  animation-delay: 0.6s;
}

.wave:nth-child(8) {
  animation-delay: 0.7s;
}

.wave:nth-child(9) {
  animation-delay: 0.8s;
}

.wave:nth-child(10) {
  animation-delay: 0.9s;
}
