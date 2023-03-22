# Hi <span class="wave">👋</span> , my name is Bobi!
.wave {
  animation-name: wave-animation;  /* Name of @keyframes element below */
  animation-duration: .75s;  /* Wave speed */
  animation-iteration-count: infinite;
  animation-timing-function: linear;
  animation-play-state: paused;
  transform-origin: 70% 70%;  /* Pivot from bottom-left palm */
  display: inline-block;
  font-size: 8rem;
}

.wave:hover {
  animation-play-state: running; /* Play animation on mouse hover */
}

@keyframes wave-animation {
  0% { transform: rotate( 0deg ) }
  25% { transform: rotate( -10deg ) }
  75% { transform: rotate( 12deg ) }
  100% { transform: rotate( 0deg ) }
}
Ackno

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=BorisAnastasov&theme=transparent&show_icons=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=BorisAnastasov&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
