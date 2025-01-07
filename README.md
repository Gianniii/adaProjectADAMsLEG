# Mental health during lockdowns through the eyes of Wikipedia
Analysing wikipedia and other data sources to evalutate the impact of lockdowns during covid on mental health.

Data story available: https://gianniii.github.io/adaProjectADAMsLEG/


<!--
1. # [Start Bootstrap - Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) - Official Jekyll Version
2. 
3. [Clean Blog Jekyll](https://startbootstrap.com/themes/clean-blog-jekyll/) is a stylish, responsive blog theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). This theme features a blog homepage, about page, contact page, and an example post page along with a working contact form powered by [Formspree](https://formspree.io/).
4. 
5. This repository holds the official Jekyll version of the Clean Blog theme on Start Bootstrap!
6. 
7. ## Preview
8. 
9. [![Clean Blog (Jekyll) Preview](https://startbootstrap.com/assets/img/screenshots/themes/clean-blog-jekyll.png)](http://StartBootstrap.github.io/startbootstrap-clean-blog-jekyll/)
10. 
11. **[View Live Preview](http://StartBootstrap.github.io/startbootstrap-clean-blog-jekyll/)**
12. 
13. ## Installation & Setup
14. 
15. ### Using RubyGems
16. 
17. When installing the theme using RubyGems, demo images, posts, and pages are not included. Follow the instructions below for complete setup.
18. 
19. 1. (Optional) Create a new Jekyll site: `jekyll new my-site`
20. 2. Replace the current theme in your `Gemfile` with `gem "jekyll-theme-clean-blog"`.
21. 3. Install the theme (run the command inside your site directory): `bundle install`
22. 4. Replace the current theme in your `_config.yml` file with `theme: jekyll-theme-clean-blog`.
23. 5. Build your site: `bundle exec jekyll serve`
24. 
25. Assuming there are no errors and the site is building properly, follow these steps next:
26. 
27. 1. Create the following pages if they do not exist already (or change the extension of existing markdown files from `.md` to `.html`):
28. 
29.    * `index.html` - set to `layout: home`
30.    * `about.html` - set to `layout: page`
31.    * `contact.html` - set to `layout: page`
32.    * `posts/index.html` - set to `layout: page` (you will also need to create a `posts` directory)
33. 
34. 2. Configure the `index.html` front matter. Example:
35. 
36.     ```markdown
37.     ---
38.     layout: home
39.     background: '/PATH_TO_IMAGE'
40.     ---
41.     ```
42. 
43. 3. Configure the `about.html`, `contact.html`, and `posts/index.html` front matter. Example:
44. 
45.     ```markdown
46.     ---
47.     layout: page
48.     title: Page Title
49.     description: This is the page description.
50.     background: '/PATH_TO_IMAGE'
51.     ---
52.     ```
53. 
54. 4. For each post in the `_posts` directory, update the front matter. Example:
55. 
56.     ```markdown
57.     ---
58.     layout: post
59.     title: "Post Title"
60.     subtitle: "This is the post subtitle."
61.     date: YYYY-MM-DD HH:MM:SS
62.     background: '/PATH_TO_IMAGE'
63.     ---
64.     ```
65. 
66.     For reference, look at the [demo repository](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) to see how the files are set up.
67. 
68. 5. Add the form to the `contact.html` page. Add the following code to your `contact.html` page:
69. 
70.     ```html
71.     <form name="sentMessage" id="contactForm" novalidate>
72.       <div class="control-group">
73.         <div class="form-group floating-label-form-group controls">
74.           <label>Name</label>
75.           <input type="text" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Please enter your name.">
76.           <p class="help-block text-danger"></p>
77.         </div>
78.       </div>
79.       <div class="control-group">
80.         <div class="form-group floating-label-form-group controls">
81.           <label>Email Address</label>
82.           <input type="email" class="form-control" placeholder="Email Address" id="email" required data-validation-required-message="Please enter your email address.">
83.           <p class="help-block text-danger"></p>
84.         </div>
85.       </div>
86.       <div class="control-group">
87.         <div class="form-group col-xs-12 floating-label-form-group controls">
88.           <label>Phone Number</label>
89.           <input type="tel" class="form-control" placeholder="Phone Number" id="phone" required data-validation-required-message="Please enter your phone number.">
90.           <p class="help-block text-danger"></p>
91.         </div>
92.       </div>
93.       <div class="control-group">
94.         <div class="form-group floating-label-form-group controls">
95.           <label>Message</label>
96.           <textarea rows="5" class="form-control" placeholder="Message" id="message" required data-validation-required-message="Please enter a message."></textarea>
97.           <p class="help-block text-danger"></p>
98.         </div>
99.       </div>
100.       <br>
101.       <div id="success"></div>
102.       <div class="form-group">
103.         <button type="submit" class="btn btn-primary" id="sendMessageButton">Send</button>
104.       </div>
105.     </form>
106.     ```
107. 
108.     Make sure you have the `email` setting in your `_config.yml` file set to a working email address! Once this is set, fill out the form and then check your email, verify the email address using the link sent to you by Formspree, and then the form will be working!
109. 
110. 6. Build your site: `bundle exec jekyll serve`
111. 
112. ### Using Core Files
113. 
114. When using the core files, the demo images, posts, and pages are all included with the download. After following the instructions below, you can then go and change the content of the pages and posts.
115. 
116. 1. [Download](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/archive/master.zip) or Clone the repository.
117. 2. Update the following configuration settings in your `_config.yml` file:
118. 
119.     * `baseurl`
120.     * `url`
121.     * `title`
122.     * `email` (after setting this setting to a working email address, fill out the form on the contact page and send it - then check your email and verify the address and the form will send you messages when used)
123.     * `description`
124.     * `author`
125.     * `twitter_username` (Optional)
126.     * `facebook_username` (Optional)
127.     * `github_username` (Optional)
128.     * `linkedin_username` (Optional)
129.     * `instagram_username` (Optional)
130. 
131. 3. Build your site: `bundle exec jekyll serve`
132. 
133. ## Bugs and Issues
134. 
135. Have a bug or an issue with this template? [Open a new issue](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/issues) here on GitHub!
136. 
137. ## About
138. 
139. Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.
140. 
141. * <https://startbootstrap.com>
142. * <https://twitter.com/SBootstrap>
143. 
144. Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**.
145. 
146. * <http://davidmiller.io>
147. * <https://twitter.com/davidmillerhere>
148. * <https://github.com/davidtmiller>
149. 
150. Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).
151. 
## Copyright and License

Copyright 2013-2021 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE) license.
