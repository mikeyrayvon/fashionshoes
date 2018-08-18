/* jshint browser: true, devel: true, indent: 2, curly: true, eqeqeq: true, futurehostile: true, latedef: true, undef: true, unused: true */
/* global jQuery, $, document, Site, Modernizr */

Site = {
  mobileThreshold: 601,
  init: function() {
    var _this = this;

    $(window).resize(function(){
      _this.onResize();
    });

    this.Extras.init();

    if ($('body').hasClass('template-product')) {
      this.Product.init();
    }

  },

  onResize: function() {
    var _this = this;

    if ($('#product-gallery').length) {
      _this.Product.setGalleryWidth();
    }
  },

  fixWidows: function() {
    // utility class mainly for use on headines to avoid widows [single words on a new line]
    $('.js-fix-widows').each(function(){
      var string = $(this).html();
      string = string.replace(/ ([^ ]*)$/,'&nbsp;$1');
      $(this).html(string);
    });
  },

};

Site.Extras = {
  init: function() {
    this.startTime();
  },

  checkTime: function(i) {
    return (i < 10) ? "0" + i : i;
  },

  startTime: function () {
    const weekday = ['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat'];

    const _this = this,
      today = new Date(),
      h = this.checkTime(today.getHours()),
      m = this.checkTime(today.getMinutes()),
      s = this.checkTime(today.getSeconds());

    console.log(today);

    $('#current-time').html(weekday[today.getDay()] + ' ' + h + ':' + m + ':' + s);

    const t = setTimeout(function () {
      _this.startTime()
    }, 500);
  },

}

Site.Product = {
  init: function() {
    var _this = this;

    if ($('#product-gallery').length) {
      _this.setGalleryWidth();
    }

    if ($('#related-products').length) {
      _this.pickRelated();
    }
  },

  setGalleryWidth: function() {
    var galleryWidth = 0;

    $('.product-gallery-item').each(function() {
      galleryWidth += $(this).width();
    });

    $('#product-gallery-row').width(galleryWidth);
  },

  pickRelated: function() {
    $('.related-products-item').pick(4);

    $('#related-products').removeClass('u-hidden');
  },
}

jQuery(document).ready(function () {
  'use strict';

  Site.init();

});
