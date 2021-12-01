# MetropolisBurgerMenu

 https://hennadiiz.github.io/MetropolisBurgerMenu/
 
 HTML CSS jQuery




//jQuery
// $(document).ready(function() {
//     $('.header__burger').click(function(event) {
//       $('.header__burger, .header__menu').toggleClass('active');
//       $('body').toggleClass('lock');
//     });
// });

//JS
const header__burger = document.querySelector('.header__burger');
const header__menu = document.querySelector('.header__menu');

header__burger.addEventListener('click', function(event) {
  header__burger.classList.toggle('active');
  header__menu.classList.toggle('active');
  document.body.classList.toggle('lock');
})
