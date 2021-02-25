# CSS Dimensions Sizes and Units

In this section we will look at following

* Which units can we use
* % and containing block
* Min width and max width
* rem and em units
* Working with vw and vh

## Units

* Pixels px
* Percentages %
* root em rem
* em
* view port height vh
* viewport width vw

## Which properties can we use with these units

Some of the properties that do need units are

1. Font-size
2. Padding
3. Border
4. Margin
5. Width
6. Height
7. top
8. bottom
9. Left
10. Right

## How is the size calculated for different units?

### Absolute Lengths

These mostly ignore user settings and are in Px, cm, mm and more. You dont use cm etc in development. Using these units will lead to a total mess. Just stick to pixels in these cases

### View port lengths

Adjust to current viewport. We use Vh and Vw, vmin and vmax. These length allow us to adjust to visible part on our user's screen or browser

### Font relative lengths

Adjust to default font size. We rem and em 

### Percentages

Percentages are special case 
