# newlayout

1. Better names for the elements like main-content, news-item etc. These should then have a single class with the styles that they share like height: 80px.

2. Please clear the floats with the direct parent always. That's because if you don't the float property will then apply also to the parents all the way to the top of the DOM.

3. Remove the spacing between the elements in the markup.
