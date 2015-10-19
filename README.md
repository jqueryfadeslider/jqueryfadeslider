# jquery-fade-slider

A jQuery plugin to add fade effect to your slider items

# Examples

### Default

    $(selector).fadeSlider()

### Number of Visible Elements

    $(selector).fadeSlider({itemPerPage: 5})

### Animation Timeout

    // Set the number of milliseconds for animation
    // If the timeout is limited to 2000
    $(selector).fadeSlider({timeout: 5000})

### Set a start point

    // Start rendering the slider from the element at 5th index
    $(selector).fadeSlider({startIndex: 5})

### Let the elements slide

    $(selector).fadeSlider({fade: false})

### Stop Autoplay

    $(selector).fadeSlider({autoplay: false})

### Add event listeners

    $(selector).fadeSlider({
      fade: false,
      autoplay: false,
      beforeInit: function(element, fadeSliderSettings){
        // beforeInit Handler
      },
      afterInit: function(element, fadeSliderSettings){
        // afterInit Handler
      },
      beforePrevious: function(element, fadeSliderSettings){
        // beforePrevious Handler
      },
      afterPrevious: function(element, fadeSliderSettings){
        // afterPrevious Handler
      },
      beforeNext: function(element, fadeSliderSettings){
        // beforeNext Handler
      },
      afterNext: function(element, fadeSliderSettings){
        // afterNext Handler
      },
      beforeDestroy: function(element){
        // beforeDestroy Handler
      },
      afterDestroy: function(element){
        // afterDestroy Handler
      }
    })

### Load Data from remote sources

    $(selector).fadeSlider({
      remote: {
        url:     "url for the remote source",
        field:   "field to be used from response",
        isImage: true
      }
    })


# Documentation

http://jqueryfadeslider.com/

# Demo

http://jqueryfadeslider.com/demo