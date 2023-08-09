To obtain this design from courspage_template:
1. replace all css of "sidenav" in _includes/css.html with the corresponding css here
2. Remove all but {% include_relative navbar.html %} in navbar_closed.html and navbar_open.html
3. Remove `<a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>` from navbar.html

Todo:
1. Remove  navbar_closed.html and navbar_open.html and include in stead just navbar.html
2. Simplify by removing start.md and in stead let user edit index.md
3. Change the topbox to one that streches over the entire page
