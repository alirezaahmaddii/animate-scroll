<template>
  <header class="header show-on-scroll">
    <div class="main-photo"></div>
  </header>
  <div class="text-center ">
    <h1 class="scroll-text">Scroll down</h1>

  </div>
  <article class="content">
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
  <section class="card-page">
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
  <section class="comment">
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
                    <span style="opacity: 0.3;font-size: 12px"  >2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p >7 reply</p>

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
                    <span style="opacity: 0.3;font-size: 12px"  >2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p >7 reply</p>

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
                    <span style="opacity: 0.3;font-size: 12px"  >2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p >7 reply</p>

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
                    <span style="opacity: 0.3;font-size: 12px"  >2 hours ago</span>
                  </p>

                </div>
                <span class="px-4" style="font-size: 12px;padding-bottom: 3rem">Let's swap out the image
                  here for the other one we have</span>
              </div>
              <div class="d-flex justify-content-between px-4 reply">
                <p >7 reply</p>

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

</template>
<script>
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
                && rect.bottom <= 0)
            ||
            (rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) &&
                rect.top <= (window.innerHeight || document.documentElement.clientHeight))
            ||
            (rect.top >= 0 &&
                rect.bottom <= (window.innerHeight || document.documentElement.clientHeight))
        );
      }
    }
  },
  mounted() {
    this.scr();
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
html {
  background: #000;
  box-sizing: border-box;
  font-family: 'Vollkorn', sans-serif;
  font-size: 1rem;
  color: #000;
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
.scroll-text {
  padding-top: 100px;

  &::after {
    content: '';
    position: absolute;
    width: 35px;
    height: 35px;
    background-image: url("./public/media/svg/down-arrow-svgrepo-com.svg");
    background-size: cover;
    transform: rotate(90deg);
    animation: scroll-down 1s infinite;
  }
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
      background-image: url("./public/media/svg/pig.svg");
      background-repeat: no-repeat;
    }

    .background2 {
      background-image: url("./public/media/svg/medal.svg");
      background-repeat: no-repeat;
    }

    .background3 {
      background-image: url("./public/media/svg/user.svg");
      background-repeat: no-repeat;
    }

    .background4 {
      background-image: url("./public/media/svg/laptop.svg");
      background-repeat: no-repeat;
    }
  }
}
.comment {
  padding-bottom: 5rem;

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
.fig-img{
  border-radius: 100%;
img{
  border: 1px solid #1D15FF;
  border-radius: 100%;
  padding: 2px;

}
}
.reply{
  position: relative;
  p{
    color: #0074FF;
  }
  @keyframes arrow {
    0%{
      transform: translateX(0px);
    }
    50%{
      transform: translateX(2px);
    }
    100%{
      transform: translateX(0px);
    }
  }
  &::before{
    content: '';
    position: absolute;
    width: 25px;
    height: 25px;
    right:20px;
    background-image: url("./public/media/svg/arrow-right-dark.svg");
    animation:arrow 1s infinite ;
  }
}
</style>
