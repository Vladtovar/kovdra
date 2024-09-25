$(document).ready(function () {

    $('a[href^="#"]').click(function () {
        var elementClick = $(this).attr("href");
        var destination = $(elementClick).offset().top;
        jQuery("html:not(:animated), body:not(:animated)").animate({scrollTop: destination}, 600);
        return false;
    });

    $('.slider-photo').slick({
        dots: true,
        arrows: false,
        infinite: true,
        speed: 250,
        fade: false,
        autoplay: false,
        autoplaySpeed: 1600,
        cssEase: 'linear'
    });

});

