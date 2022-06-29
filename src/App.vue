<template>
  <header class=" header show-on-scroll">
    <div class="main-photo"></div>
  </header>
  <div class="scroll text-center d-flex justify-content-center">
    <h1 class="scroll-text  ">S</h1>
    <h1 class="scroll-text ">c</h1>
    <h1 class="scroll-text ">r</h1>
    <h1 class="scroll-text ">o</h1>
    <h1 class="scroll-text ">l</h1>
    <h1 class="scroll-text ">l</h1>
    <h1 class="scroll-text "> </h1>
    <h1 class="scroll-text ">d</h1>
    <h1 class="scroll-text ">o</h1>
    <h1 class="scroll-text ">w</h1>
    <h1 class="scroll-text ">n</h1>
    <h1 class="scroll-down-text"></h1>

  </div>
  <article class=" content  ">
    <div class="container">
      <section></section>
      <section>
        <div class="d-flex" style="background: #ffffff">
          <div class="d-flex flex-column">
            <p><strong>The history of pizza begins in antiquity, when various ancient cultures produced flatbreads with
              toppings.</strong></p>

            <p>The word pizza was first documented in AD 997 in Gaeta and successively in different parts of Central and
              Southern Italy. The precursor of pizza was probably the focaccia, a flat bread known to the Romans as
              panis
              focacius, to which toppings were then added.</p>

            <p>Modern pizza developed in Naples, when tomato was added to the focaccia in the late 18th century.
              However,
              pizza
              was mainly eaten in the country of Italy and by immigrants from there. This changed after World War II,
              when
              Allied troops stationed in Italy came to enjoy pizza along with other Italian foods.</p>
          </div>
        </div>
      </section>
      <section>

        <figure>
          <img src="/media/image/mobility.jpg"
               class="inline-photo show-on-scroll">
        </figure>
      </section>
      <section>
        <div class="d-flex" style="background: #ffffff">
          <div class="d-flex flex-column">
            <h2>Make an Italian pizza</h2>

            <p>(makes dough for 4 pizzas, each one about 12 inches in diameter)</p>

            <h3>Ingredients</h3>

            <ul>
              <li>600 mL of warm water</li>
              <li>7 cups (1kg) flour</li>
              <li>2.5 – 3 tablespoons (25 grams) of fresh yeast or 2 teaspoons (7-8 grams) of dried yeast</li>
              <li>6 tablespoons of extra virgin olive oil</li>
              <li>1.5 teaspoons salt</li>
              <li>2 teaspoons sugar</li>
            </ul>
          </div>
        </div>
      </section>
      <section>
        <figure>
          <img src="/media/image/strength-score-v4.jpg" class="inline-photo show-on-scroll">
        </figure>
      </section>
      <section>

        <div class="d-flex" style="background: #ffffff">
          <div class=" d-flex flex-column">
            <h3>Method</h3>

            <p>Sprinkle the yeast into a medium bowl with the warm water. We don’t mean hot, and we don’t mean cold… we
              mean
              warm! That’s the kind the yeast likes best. Stir until the yeast dissolves.</p>

            <p>Place almost all of the flour on the table in the shape of a volcano. (Think Mt. Vesuvius… appropriate
              since
              Naples is the king of all pizza cities!).</p>

            <p>Pour the yeast-and-warm-water mix, along with the other ingredients, into the “crater” of the
              volcano.</p>

            <p>Knead everything together for 10 to 15 minutes until the dough is smooth and elastic, keeping your
              surface
              floured.</p>
          </div>
        </div>
      </section>
      <section>
        <div>
          <figure>
            <img src="media/image/yoga.jpg"
                 class="inline-photo show-on-scroll">
          </figure>
        </div>
      </section>
      <section>
        <div class="d-flex" style="background: #ffffff">
          <div>
            <p>Transfer the dough onto an oiled pizza pan or baking sheet.</p>

            <p>Add tomato sauce, if you want a pizza rossa (red pizza). Lots of pizzas in Italy are actually pizza
              bianca,
              without tomato sauce, so don’t feel like you have to! Brush the edges of the crust with a little bit of
              olive
              oil.</p>

            <p>Bake each pizza for about 10 minutes, then add mozzarella cheese (sliced or grated) on top, as well as
              any
              other
              ingredients.</p>

            <p>Let the pizzas bake until the crust is browned and the cheese is melted. By lifting up the pizza to peek
              underneath, you can make sure the bottom has browned, too.</p>

            <p>Remove your pizzas from the oven and, for a real Italian touch, garnish with a few basil leaves. And
              enjoy!</p>
          </div>
        </div>

      </section>
      <section>
        <figure>
          <img src="/media/image/mobility.jpg"
               class="inline-photo show-on-scroll">
        </figure>
      </section>
    </div>
  </article>
  <section class=" card-page  ">
    <div class="container mt-5">
      <div class="items-card">
        <h1 class="mb-5 text-center">What Dashcore template offers</h1>

        <div class="row row-cols-1 row-cols-md-2">
          <div class="col mb-4" v-for="items in carditem">
            <div class="card " :class="items.background">
              <div class="card-body">
                <h5 class="card-title">{{ items.title }}</h5>
                <p class="card-text">{{ items.text }}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class=" comment  ">
    <div class="container">
      <div class="d-flex justify-content-between">
        <div class="comment__box box__4 d-flex flex-column justify-content-center align-items-center ">
          <figcaption>
            <div class="fig-text d-flex flex-column w-100 h-100">
              <div class="text-comment-box d-flex justify-content-between">
                <p class="fw-bold px-4">comment</p>
                <span class="px-4">...</span>
              </div>
              <div class="d-flex flex-column">
                <span class="px-4 pt-2">Text</span>
                <div class="d-flex pt-2 px-4 fig-img">
                  <figure>
                    <img src="/media/image/user.jpg" alt="" width="44px" height="44px">
                  </figure>
                  <p class="d-flex flex-column px-2">
                    <span style="font-size: 13px">Louis Ringal</span>
                    <span style="opacity: 0.3;font-size: 12px">2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p>7 reply</p>

              </div>
            </div>
          </figcaption>
          <div class="comment__image">
            <div class="image__border">

            </div>
            <figure>
              <img src="/media/image/user.jpg" alt="user">
            </figure>
          </div>
          <div class="d-flex flex-column text-center pt-4">
            <span>Jack Ringel</span>
            <span>Jackringel@gmail.com</span>
          </div>
        </div>
        <div class="comment__box box__4 d-flex flex-column justify-content-center align-items-center ">
          <figcaption>
            <div class="fig-text d-flex flex-column w-100 h-100">
              <div class="text-comment-box d-flex justify-content-between">
                <p class="fw-bold px-4">comment</p>
                <span class="px-4">...</span>
              </div>
              <div class="d-flex flex-column">
                <span class="px-4 pt-2">Text</span>
                <div class="d-flex pt-2 px-4 fig-img">
                  <figure>
                    <img src="/media/image/user.jpg" alt="" width="44px" height="44px">
                  </figure>
                  <p class="d-flex flex-column px-2">
                    <span style="font-size: 13px">Louis Ringal</span>
                    <span style="opacity: 0.3;font-size: 12px">2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p>7 reply</p>

              </div>
            </div>
          </figcaption>
          <div class="comment__image">
            <div class="image__border">

            </div>
            <figure>
              <img src="/media/image/user.jpg" alt="user">
            </figure>
          </div>
          <div class="d-flex flex-column text-center pt-4">
            <span>Jack Ringel</span>
            <span>Jackringel@gmail.com</span>
          </div>
        </div>
        <div class="comment__box box__4 d-flex flex-column justify-content-center align-items-center ">
          <figcaption>
            <div class="fig-text d-flex flex-column w-100 h-100">
              <div class="text-comment-box d-flex justify-content-between">
                <p class="fw-bold px-4">comment</p>
                <span class="px-4">...</span>
              </div>
              <div class="d-flex flex-column">
                <span class="px-4 pt-2">Text</span>
                <div class="d-flex pt-2 px-4 fig-img">
                  <figure>
                    <img src="/media/image/user.jpg" alt="" width="44px" height="44px">
                  </figure>
                  <p class="d-flex flex-column px-2">
                    <span style="font-size: 13px">Louis Ringal</span>
                    <span style="opacity: 0.3;font-size: 12px">2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p>7 reply</p>

              </div>
            </div>
          </figcaption>
          <div class="comment__image">
            <div class="image__border">

            </div>
            <figure>
              <img src="/media/image/user.jpg" alt="user">
            </figure>
          </div>
          <div class="d-flex flex-column text-center pt-4">
            <span>Jack Ringel</span>
            <span>Jackringel@gmail.com</span>
          </div>
        </div>
        <div class="comment__box box__4 d-flex flex-column justify-content-center align-items-center ">
          <figcaption>
            <div class="fig-text d-flex flex-column w-100 h-100">
              <div class="text-comment-box d-flex justify-content-between">
                <p class="fw-bold px-4">comment</p>
                <span class="px-4">...</span>
              </div>
              <div class="d-flex flex-column">
                <span class="px-4 pt-2">Text</span>
                <div class="d-flex pt-2 px-4 fig-img">
                  <figure>
                    <img src="/media/image/user.jpg" alt="" width="44px" height="44px">
                  </figure>
                  <p class="d-flex flex-column px-2">
                    <span style="font-size: 13px">Louis Ringal</span>
                    <span style="opacity: 0.3;font-size: 12px">2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p>7 reply</p>

              </div>
            </div>
          </figcaption>
          <div class="comment__image">
            <div class="image__border">

            </div>
            <figure>
              <img src="/media/image/user.jpg" alt="user">
            </figure>
          </div>
          <div class="d-flex flex-column text-center pt-4">
            <span>Jack Ringel</span>
            <span>Jackringel@gmail.com</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="company">
    <div class="container">
      <div class="d-flex align-items-center">
        <div class="scrollShow box" v-for="items in company">
          <figure class="col-12">
            <img :src="items.img" alt="image" class="col-12">
          </figure>
        </div>
      </div>
    </div>
  </section>
  <section class="text-animation">

  </section>


</template>
<script>
import gsap from 'gsap';
import ScrollTrigger from 'gsap/ScrollTrigger.js';
import 'gsap/ScrollToPlugin';

export default {
  data: () => ({
    carditem: [
      {
        background: 'background1',
        title: 'save time',
        text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error eveniet nihil perspiciatis quia quidem quod ratione sapiente sint?'
      },
      {
        background: 'background2',
        title: 'Get things done',
        text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error eveniet nihil perspiciatis quia quidem quod ratione sapiente sint?'
      },
      {
        background: 'background3',
        title: 'Grow your business',
        text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error eveniet nihil perspiciatis quia quidem quod ratione sapiente sint?'
      },
      {
        background: 'background4',
        title: 'Accomplish your goals',
        text: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error eveniet nihil perspiciatis quia quidem quod ratione sapiente sint?'
      }
    ],
    company: [
      {
        img: '/media/image/logo-1.png'
      },
      {
        img: '/media/image/logo-2.png'
      },
      {
        img: '/media/image/logo-3.png'
      },
      {
        img: '/media/image/logo-4.png'
      },
      {
        img: '/media/image/logo-5.png'
      },

    ]
  }),
  methods: {
    scr() {
      // Detect request animation frame
      let scroll = window.requestAnimationFrame ||
          // IE Fallback
          function (callback) {
            window.setTimeout(callback, 100 * 100)
          };
      let elementsToShow = document.querySelectorAll('.show-on-scroll');

      function loop() {

        Array.prototype.forEach.call(elementsToShow, function (element) {
          if (isElementInViewport(element)) {
            element.classList.add('is-visible');
          } else {
            element.classList.remove('is-visible');
          }
        });

        scroll(loop);
      }

// Call the loop for the first time
      loop();

// Helper function from: http://stackoverflow.com/a/7557433/274826
      function isElementInViewport(el) {
        // special bonus for those using jQuery
        if (typeof jQuery === "function" && el instanceof jQuery) {
          el = el[0];
        }
        let rect = el.getBoundingClientRect();
        return (
            (rect.top <= 0
                && rect.bottom >= 0)
            ||
            (rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) &&
                rect.top <= (window.innerHeight || document.documentElement.clientHeight))
            ||
            (rect.top >= 0 &&
                rect.bottom <= (window.innerHeight || document.documentElement.clientHeight))
        );
      }
    },
    //this is animation company box
    companyScroll() {
      let scrollShow = {
        items: [], // arary of objects containing DOM element and parameters for scrollShow
        delay: 0.4, // time delay (seconds) on simutaneously showing elements
        default_element_percent: 100, // default percentage of element in viewport to be "in view"
        default_viewport_percent: 0, // default percentage of viewport to be used for "in view checking"
        hide_on_scroll_back: false, // hide if scrolling back up

        // populate this.items to keep track of scrollShow elements
        addItems: function (classname = "scrollShow") {
          let elements = document.getElementsByClassName(classname)
          for (let i = 0; i < elements.length; i++) {
            const el = elements[i]
            const showClass = el.getAttribute('scroll-show') || 'show'
            let elPercent = parseInt(el.getAttribute('scroll-show') || this.default_element_percent)
            let vpPercent = parseInt(el.getAttribute('scroll-show') || this.default_viewport_percent)
            let item = {
              element: el,
              showClass: showClass,
              elPercent: elPercent,
              vpPercent: vpPercent,
              top: null,
              height: null,
              keyY: null
            }
            item = this.updateRect(item)
            this.items.push(item)
          }
          this.onScroll()
        },

        // update scrollShow elements rectangular position
        updateRect: function (item) {
          const rect = item.element.getBoundingClientRect()
          item.top = rect.top + scrollY
          item.height = rect.height
          item.keyY = item.top + item.height * item.elPercent / 100 - innerHeight * (1 - item.vpPercent / 100)
          return item
        },

        onResize: function () {
          for (let i = 0; i < this.items.length; i++) {
            this.items[i] = this.updateRect(this.items[i])
          }
          this.onScroll()
        },

        onScroll: function () {
          const isAfterY = this.items.map(function (item) {
            return item.keyY <= scrollY
          })
          const alreadyShown = this.items.map(function (item) {
            return item.element.classList.contains(item.showClass)
          })

          let count = 0
          for (let i = 0; i < isAfterY.length; i++) {
            const showClass = this.items[i].showClass
            let el = this.items[i].element
            el.style.transitionDelay = null
            if (isAfterY[i] && !alreadyShown[i]) {
              el.style.transitionDelay = `${this.delay * count}s`
              count++
              el.classList.add(showClass)
            } else if (this.hide_on_scroll_back && !isAfterY[i] && alreadyShown[i]) {
              el.classList.remove(showClass)
            }
          }
        },
      };

// listens to window resize and scroll events
      window.addEventListener('resize', () => scrollShow.onResize());
      window.addEventListener('scroll', () => scrollShow.onScroll());
      scrollShow.addItems();
      scrollShow.hide_on_scroll_back = true
    },
    look() {
      gsap.registerPlugin(ScrollTrigger)
      let sections = gsap.utils.toArray("section"),
          currentSection = sections[0];

      gsap.defaults({overwrite: 'auto', duration: 0.3});

// stretch out the body height according to however many sections there are.
      gsap.set("body", {height: (sections.length * 100) + "%"});

// create a ScrollTrigger for each section
      sections.forEach((section, i) => {
        ScrollTrigger.create({
          // use dynamic scroll positions based on the window height (offset by half to make it feel natural)
          start: () => (i - 0.5) * innerHeight,
          end: () => (i + 0.5) * innerHeight,
          // when a new section activates (from either direction), set the section accordinglyl.
          onToggle: self => self.isActive && setSection(section)
        });
      });

      function setSection(newSection) {
        if (newSection !== currentSection) {
          gsap.to(currentSection, {opacity: 1, autoAlpha: 0})
          gsap.to(newSection, {opacity: 1, autoAlpha: 1});
          currentSection = newSection;
        }
      }

// handles the infinite part, wrapping around at either end....
      ScrollTrigger.create({
        start: 1,
        end: () => ScrollTrigger.maxScroll(window) - 1,
        onLeaveBack: self => self.scroll(ScrollTrigger.maxScroll(window) - 2),
        onLeave: self => self.scroll(2)
      }).scroll(2);
    },
    box() {
      // usage:
      batch(".card", {
        interval: 0.1, // time window (in seconds) for batching to occur. The first callback that occurs (of its type) will start the timer, and when it elapses, any other similar callbacks for other targets will be batched into an array and fed to the callback. Default is 0.1
        batchMax: 3,   // maximum batch size (targets)
        onEnter: batch => gsap.to(batch, {autoAlpha: 1, stagger: 1, overwrite: true}),
        onLeave: batch => gsap.set(batch, {autoAlpha: 0, overwrite: true}),
        onEnterBack: batch => gsap.to(batch, {autoAlpha: 1, stagger: 0.1, overwrite: true}),
        onLeaveBack: batch => gsap.set(batch, {autoAlpha: 0, overwrite: true})
        // you can also define things like start, end, etc.
      });


// the magical helper function (no longer necessary in GSAP 3.3.1 because it was added as ScrollTrigger.batch())...
      function batch(targets, vars) {
        let varsCopy = {},
            interval = vars.interval || 0.1,
            proxyCallback = (type, callback) => {
              let batch = [],
                  delay = gsap.delayedCall(interval, () => {
                    callback(batch);
                    batch.length = 0;
                  }).pause();
              return self => {
                batch.length || delay.restart(true);
                batch.push(self.trigger);
                vars.batchMax && vars.batchMax <= batch.length && delay.progress(1);
              };
            },
            p;
        for (p in vars) {
          varsCopy[p] = (~p.indexOf("Enter") || ~p.indexOf("Leave")) ? proxyCallback(p, vars[p]) : vars[p];
        }
        gsap.utils.toArray(targets).forEach(target => {
          let config = {};
          for (p in varsCopy) {
            config[p] = varsCopy[p];
          }
          config.trigger = target;
          ScrollTrigger.create(config);
        });
      }
    },
    text() {
      const tl = gsap.timeline({
        // repeat: -1,
        // yoyo: false,
      });
      tl.to('.header-letter', {duration: 0.65,top: -100,y: -100,right: 100,x: 100,opacity: 1,stagger: 0.25,ease: "slow"});

    },
    scrollanimatext(){
      const tl=gsap.timeline({

      });
      tl.to('.scroll-text ',{duration: 0.65,top: 100,y: 100,right: 100,x: 100,opacity: 1,stagger: 0.25,ease: "slow"})
      tl.to('.scroll ',{duration: 0.65,top: 100,y: 100,right: 100,x: 100,opacity: 1,stagger: 0.25,ease: "slow"})
      tl.to('.scroll-down-text',{duration: 0.65,right: 811,y: 100,opacity: 1,stagger: 0.25,ease: "slow"})
    },


  },
  mounted() {
    this.scr();
    //company animation
    this.companyScroll();

    // this.look();
    this.box();
    //this for animation text
    this.text();
    this.scrollanimatext();

  }
}
</script>
<style lang="scss">
*, *:before, *:after {
  box-sizing: inherit;
  margin: 0;
  padding: 0;
  border: 0 none;
  position: relative;
}



article {
  .inline-photo {
    //border: 1em solid #fff;
    //border-bottom: 4em solid #fff;
    border-radius: 11px;
    box-shadow: 0em 0em 1px 3px rgb(122 122 122 / 16%);
    //margin: 2em auto;
    opacity: 0;
    transform: translateY(120px);
    transition: transform 0.3s 0.3s cubic-bezier(0, 1, .3, 1),
    opacity .3s .3s ease-out;
    max-width: 600px;
    width: 90%;
    will-change: transform, opacity;


  }

  .inline-photo.is-visible {
    opacity: 1;
    transition: 0.3s all ease-in-out;
    //transform: rotateZ(0deg);
    transform: translateY(0px);
  }

  header {
    opacity: 0;
    transition: opacity .5s .25s ease-out;
  }

  header.is-visible {
    transition: 0.3s all ease-in-out;
    opacity: 1;
  }

  .main-photo {
    transform: scale(.8);
  }

  .heading {
    transform: translate(-50%, calc(-50% + 1em));
  }

  .is-visible .main-photo {
    transform: none;
  }

  .is-visible .heading {
    transform: translate(-50%, -50%);
  }

  .main-photo,
  .heading {
    transition: transform 4s .25s cubic-bezier(0, 1, .3, 1),
    filter 10s 5s ease-out;
    will-change: transform;
  }


  figure:nth-of-type(n)::after {
    right: 45%;
    left: 5vmin;
  }

  section {
    width: calc(50% + 1px);
    height: 100vh;
    margin: 0 0 0 auto;
    position: sticky;
    top: 0;
    overflow: hidden;
    padding: 5vmin;
  }

  section:nth-of-type(1) {
    margin: 0 0 10vh 0;
    width: 50%;
  }

  figure:nth-of-type(2n) {
    margin: 0 0 10vh auto;
  }

  section:nth-of-type(2n) {
    margin: 0 auto 0 0;
  }

  figure:last-of-type,
  section:last-of-type {
    margin-bottom: 0;
  }

  figure img {
    min-width: 100%;
    min-height: 100%;
    object-fit: cover;
    object-position: center;
  }

  section > div {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100%;
    //padding: 1rem;
  }
}

@keyframes scroll-down {
  0% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(10px);

  }
  100% {
    transform: translateY(0px);

  }
}

.scroll-down-text{
    content: '';
    position: absolute;
    width: 35px;
    height: 35px;
    background-image: url("/media/svg/down-arrow-svgrepo-com.svg");
    background-size: cover;
    animation: scroll-down 1s infinite;
    top: 19rem;
    opacity: 0;
}
.scroll-text {
  padding-top: 100px;
  opacity: 0;
    //&::after {
    //  content: '';
    //  position: absolute;
    //  width: 35px;
    //  height: 35px;
    //  background-image: url("/media/svg/down-arrow-svgrepo-com.svg");
    //  background-size: cover;
    //  transform: rotate(90deg);
    //  animation: scroll-down 1s infinite;
    //}
}

.card-page {
  background-color: #F7FAFC;
  padding-top: 5px;
  padding-bottom: 45px;

  .items-card {

    .card-body {
      padding: 2rem 6rem;
    }

    .card {
      border-radius: 11px;
      box-shadow: 0px 1px 3px #d4d4d4;
      transition: 0.3s all ease-in-out;

      &:hover {
        transform: translateY(-10px);
        background-position: 0px -20px;
      }
    }

    .background1 {
      background-image: url("/media/svg/pig.svg");
      background-repeat: no-repeat;
    }

    .background2 {
      background-image: url("/media/svg/medal.svg");
      background-repeat: no-repeat;
    }

    .background3 {
      background-image: url("/media/svg/user.svg");
      background-repeat: no-repeat;
    }

    .background4 {
      background-image: url("/media/svg/laptop.svg");
      background-repeat: no-repeat;
    }
  }
}

.comment {
  padding-bottom: 5rem;
  padding-top: 7rem;

  .comment__box {
    width: 18%;
    border: 1px solid #d4d4d4;
    align-items: center;
    padding: 2rem 0;
    transition: 2s all ease-in-out;
    position: relative;
    overflow: hidden;
    cursor: pointer;

    &:hover {
      figcaption {
        transform: translateY(0px);
        position: absolute;
        z-index: 99;
        opacity: 1;
      }

      &:hover .image__border {
        transform: rotate(206deg);
        z-index: 0;
      }
    }

    .comment__image {
      z-index: 1;

      .image__border {
        border: 1px solid #1D15FF;
        border-radius: 100%;
        position: absolute;
        z-index: 99 !important;
        width: 161px;
        height: 161px;
        transition: 0.9s all ease-in-out;

        &::before {
          content: "";
          width: 18px;
          height: 18px;
          position: absolute;
          border: 2px solid #ffffff;
          border-radius: 100%;
          background-color: #1D15FF;
          right: 27px;
          top: 6px;
          z-index: 99;
        }
      }

      figure {
        border-radius: 100%;
        margin: 0;
      }

      img {
        border-radius: 100%;
        padding: 6px;
      }
    }
  }
}

.box__4 {
  figcaption {
    left: 0;
    transform: translateX(-900px);
    max-width: 100%;
    width: 100%;
    opacity: 0;

  }
}

figcaption {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: absolute;
  background: #ffffff;
  transition: 1.5s all ease;
  max-width: 0;
  width: 0;
  opacity: 1;
  z-index: 99;
}

.fig-text {
  padding-top: 15px;
  padding-bottom: 15px;
}

.text-comment-box {
  position: relative;

  &::after {
    content: '';
    width: 100%;
    height: 1px;
    background-color: #d4d4d4;
    position: absolute;
    bottom: 5px;


  }
}

.fig-img {
  border-radius: 100%;

  img {
    border: 1px solid #1D15FF;
    border-radius: 100%;
    padding: 2px;

  }
}

.reply {
  position: relative;

  p {
    color: #0074FF;
  }

  @keyframes arrow {
    0% {
      transform: translateX(0px);
    }
    50% {
      transform: translateX(2px);
    }
    100% {
      transform: translateX(0px);
    }
  }

  &::before {
    content: '';
    position: absolute;
    width: 25px;
    height: 25px;
    right: 20px;
    background-image: url("./public/media/svg/arrow-right-dark.svg");
    animation: arrow 1s infinite;
  }
}

.box {
  //margin: 10px;
  //height: 200px;
  //width: 200px;
  transition: 1s all ease-in-out;
  //display: inline-block;
  border-radius: 10px;
  padding: 20px;
}

.scrollShow {
  opacity: 0;
  transition: 0.8s all ease-in-out;
  transform: translateY(200px);
  overflow: hidden;

}

.scrollShow .show {
  opacity: 1;
  transform: translateY(0px);
  overflow: hidden;
}

.show {
  opacity: 1;
  transform: translateY(0px);
  overflow: hidden;
}


/*just layout*/
.header-letter {
  position: relative;
  //font-family: "iransans-bold";
  //color: $oneColor;
  opacity: 1;
  text-transform: capitalize;
}
</style>
