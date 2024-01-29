                        SECTION 11: BOOTSTRAP
          LESSON 64: What is Bootstrap?
Bootstrap is an external css framework which was developed by 2 twitter developers which are by Mark Otto and Jacob Thornton 2010 . It is also an open source. They are prebuild css.
The bootstrap also uses the 12 columns layout system build on top of flexbox which makes it easy to build responsive websites that looks great on mobile, desktop and other devices


                TYPES of CSS FRAMEWORK
They are:
1. Bootstrap
2. Foundation
3. Bulma
4. Tailwind 
5. Materialize
6. Skeleton e.t.c....

                How To Use Bootstrap
We use the framework by using a CDN which means Content Delivery Network; which is simply a hub all across the world which knows where our uses are located, so when they load up our website it looks for the shortest distance and location on the server and load up the css file and makes it to deliver it very fast.

- To use it we copy and paste link in the head section:
- To use functionality like our clickable button and dropdown menu we add the bootstrap script link just before closing body tag

LESSON 65: Bootstrap Layout
Understanding the 12 column layout of bootstrap; this is the most powerful features of bootstrap.
The 12 column system
has a       - div called container
has an inner- div called row
and another - div called items which most likely the columns e.g
<div class="container">
  <div class="row">
    <div class="col"></div> The 12 column system makes the items to Auto Fit
  </div>
</div>
what happens is that the 12 column layout makes the items very responsive to the screen sizes whether mobile, tab, laptop and desktop or tv screens which are xxlarge

we have the following which set the width dimensions:
container: This gives a margin bw left and right
container-sm:
container-md:
container-lg
container-xl:
container-xxl
container-fluid: This gives the edge to edge behaviour
The container and container-fluid is mostly used!

                                Sized Columns
we can simply use the col-2, col-4, col-6 which takes the proportion in the 12 colum system

                          Bootstrap BreakPoints
Bootstrap has 6 default breakpoints referred to as grid tiers for building responsiveness. This breakpoints can be customized if you're using our source Sass files.
Breakpoint            infix         Dimension              
Xtra small            None           <576px
small                 sm             >=576px
medium                md             >=768px
large                 lg             >=992px
extra large           xlg            >=1200px
extra extra large     xxlg           >=5400px

the extra small are phones that have narrower widths. Even though the dimensions are always changing the small is for phones, md is for Tablets/iPads, lg for Laptops, xlarge for Destop and xxlarge is for TV


Note: 
- We don't need the media query that much
- The breakpoints alway overflow from top to bottom as their declared. e.g. col-sm-2. That is this is from the range >576px to <768px


Examples of Bootstrap Breakpoint: col-sm-2; col-sm-4; col-sm-6; col-sm; e.t.c
This that is declared will affect from small screen downwards (all the phone, tablet, laptop e.t.c) except it his been declared!
but if the dimension is less than the delcared screen size it takes the full width of the column which takes 100%

                      Multiple Breakpoints
multiple breakpoint can be declared in a div for different screen sizes. Examples col-sm-12, col-md-8, col-lg-4;
          
                      Mix and Match
we can Mix and Match the breakpoint for the following: col-2, col-4, col which is automatically takes the remaining space of the the remaining space or column.

Verify the following: .col-6 .col-md-4, .col-6 .col-md-4, .col-6 .col-md-4



                  Lesson 66: Bootstrap Components
Learning to use the pre-built and pre-styled components.
Here we have the following:
Components
Examples
Snippets e.t.c
Basically using them to create website from scratch at a very fast pace.