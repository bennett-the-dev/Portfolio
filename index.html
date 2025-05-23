

const audioPlayer = document.getElementById('background-music') as HTMLAudioElement;
const toggleAudioBtn = document.getElementById('toggleAudio') as HTMLButtonElement;
const audioIcon = toggleAudioBtn.querySelector('i') as HTMLElement;


const musicTrack = 'https://files.freemusicarchive.org/storage-freemusicarchive-org/music/no_curator/Tours/Enthusiast/Tours_-_01_-_Enthusiast.mp3';
audioPlayer.src = musicTrack;


toggleAudioBtn.addEventListener('click', () => {
  if (audioPlayer.paused) {
    audioPlayer.play();
    audioIcon.className = 'fa-solid fa-volume-high';
  } else {
    audioPlayer.pause();
    audioIcon.className = 'fa-solid fa-volume-xmark';
  }
});


const hamburger = document.querySelector('.hamburger') as HTMLElement;
const navLinks = document.querySelector('.nav-links') as HTMLElement;

hamburger.addEventListener('click', () => {
  hamburger.classList.toggle('active');
  navLinks.classList.toggle('active');
});


const navItems = document.querySelectorAll('.nav-links a');
navItems.forEach(item => {
  item.addEventListener('click', () => {
    hamburger.classList.remove('active');
    navLinks.classList.remove('active');
  });
});


const observerOptions = {
  root: null,
  rootMargin: '0px',
  threshold: 0.1
};

const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('in-view');
    }
  });
}, observerOptions);

const sections = document.querySelectorAll('section');
sections.forEach(section => {
  section.classList.add('fade-in');
  observer.observe(section);
});


if (typeof particlesJS !== 'undefined') {
  particlesJS('particles-js', {
    particles: {
      number: { value: 90, density: { enable: true, value_area: 800 } },
      color: { value: "#ffffff" },
      shape: { type: "circle" },
      opacity: {
        value: 0.4,
        random: false,
        anim: { enable: false }
      },
      size: {
        value: 3,
        random: true,
        anim: { enable: false }
      },
      line_linked: {
        enable: true,
        distance: 150,
        color: "#ffffff",
        opacity: 0.3,
        width: 1
      },
      move: {
        enable: true,
        speed: 2,
        direction: "none",
        random: false,
        straight: false,
        out_mode: "out",
        bounce: false
      }
    },
    interactivity: {
      detect_on: "canvas",
      events: {
        onhover: { enable: true, mode: "grab" },
        onclick: { enable: true, mode: "push" },
        resize: true
      },
      modes: {
        grab: { distance: 180, line_linked: { opacity: 0.5 } },
        push: { particles_nb: 4 }
      }
    },
    retina_detect: true
  });
}


const contactForm = document.getElementById('contact-form') as HTMLFormElement;
if (contactForm) {
  contactForm.addEventListener('submit', (e) => {
    e.preventDefault();


    const formData = new FormData(contactForm);
    const formValues = Object.fromEntries(formData.entries());

    console.log('Form submitted:', formValues);


    const button = contactForm.querySelector('button') as HTMLButtonElement;
    const originalText = button.textContent;
    button.textContent = 'Message Sent!';
    button.classList.add('success');

    contactForm.reset();


    setTimeout(() => {
      button.textContent = originalText;
      button.classList.remove('success');
    }, 3000);
  });
}


const yearSpan = document.getElementById('year');
if (yearSpan) {
  yearSpan.textContent = new Date().getFullYear().toString();
}


const addFadeInClass = () => {
  document.querySelectorAll('.fade-in').forEach((el, index) => {
    setTimeout(() => {
      el.classList.add('visible');
    }, index * 200);
  });
};


window.addEventListener('load', () => {

  document.body.classList.add('loaded');


  sections.forEach((section, index) => {
    setTimeout(() => {
      section.classList.add('visible');
    }, index * 200);
  });


  const style = document.createElement('style');
  style.textContent = `
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s ease, transform 0.6s ease;
    }
    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .success {
      background-color: #00b894 !important;
    }
  `;
  document.head.appendChild(style);
});
