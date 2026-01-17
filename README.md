

<!--
**ghassyaa-kai7fiq/ghassyaa-kai7fiq** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div align="center" style="
  background-image:url('https://raw.githubusercontent.com/USERNAME_KAMU/USERNAME_KAMU/main/assets/banner-bg.jpg');
  background-size:cover;
  background-position:center;
  padding:70px 20px;
  border-radius:16px;
  margin-bottom:30px;
">

  <!-- TITLE (STATIC, TIDAK DIUBAH) -->
  <h1 class="glitch-title" data-text="KAI SYAFIQ">
    KAI SYAFIQ
  </h1>

  <!-- ROLE (ANIMATED) -->
  <div class="role-container">
    <span class="role">
      Software Engineering Student · SV IPB
    </span>
    <span class="role">
      AI & Cybersecurity Enthusiast
    </span>
    <span class="role">
      Analytical Thinker & Problem Solver
    </span>
  </div>

</div>

<style>
/* ===== TITLE GLITCH (STATIC) ===== */
.glitch-title{
  position:relative;
  font-family:monospace;
  font-size:38px;
  letter-spacing:3px;
  color:#e5e7eb;
  margin:0;
}
.glitch-title::before,
.glitch-title::after{
  content:attr(data-text);
  position:absolute;
  left:0;
  width:100%;
}
.glitch-title::before{
  color:#9ca3af;
  transform:translate(-2px,0);
}
.glitch-title::after{
  color:#f3f4f6;
  transform:translate(2px,0);
}

/* ===== ROLE CONTAINER ===== */
.role-container{
  position:relative;
  height:32px;
  margin-top:14px;
  font-family:monospace;
  font-size:18px;
  color:#d1d5db;
  overflow:visible;
}

/* ===== ROLE TEXT ===== */
.role{
  position:absolute;
  left:0; right:0;
  text-align:center;
  opacity:0;

  /* AUTO "SCROLL-LIKE" ZOOM */
  animation:scrollZoom 5s infinite;

  /* MANUAL CURSOR ZOOM */
  transition:transform .25s ease;
  cursor:pointer;
}

/* ROLE ROTATION */
.role:nth-child(1){animation-delay:0s}
.role:nth-child(2){animation-delay:5s}
.role:nth-child(3){animation-delay:10s}

/* MANUAL ZOOM */
.role:hover{
  transform:scale(1.25);
  z-index:10;
}
.role:active{
  transform:scale(1.45);
}

/* ===== KEYFRAMES (SIMULASI SCROLL ZOOM) ===== */
@keyframes scrollZoom{
  0%{
    opacity:0;
    transform:scale(.9);
  }
  15%{
    opacity:1;
    transform:scale(1);
  }
  40%{
    transform:scale(1.35);
  }
  60%{
    transform:scale(1);
  }
  85%{
    opacity:0;
    transform:scale(.9);
  }
  100%{
    opacity:0;
  }
}

/* RESPONSIVE */
@media (max-width:600px){
  .glitch-title{font-size:26px}
  .role-container{font-size:14px}
}
</style>
