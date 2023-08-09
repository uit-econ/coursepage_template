# To obtain this design from courspage_template:
1. Remove all but {% include_relative navbar.html %} in navbar_closed.html and navbar_open.html
2. Remove `<a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>` from navbar.html
3. Replace _includes/css.html in the target repository with the corresponding css here
4. add breaks to top-box.html

## Easy way: 

1, Remove `<a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>` from navbar.html
2. Replace navbar_closed.html, navbar_open.html, css.html, top-box.html

## The changes to the css were:
1. all occurences of "sidenav"
2. css between #top-box and #fagundertittel 

# Todo:
1. Remove  navbar_closed.html and navbar_open.html and include in stead just navbar.html
2. Simplify by removing start.md and in stead let user edit index.md
   
