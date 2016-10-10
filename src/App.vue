<template>

  <div id="app" >
    <a href="#" id="nav-button" @click="toggleSideMenu()" v-bind:class="{open: sideMenu}">
        <span>
          NAV
          <img src="https://lord.github.io/slate/images/navbar.png">
        </span>
      </a>
    <div class="tocify-wrapper" v-bind:class="{open: sideMenu}">
        <img src="https://lord.github.io/slate/images/logo.png">
        <div class="lang-selector">
            <a href="#" data-language-name="shell" class="active">shell</a>
            <a href="#" data-language-name="ruby" class="">ruby</a>
            <a href="#" data-language-name="python" class="">python</a>
        </div>
        <!-- <div class="search">
            <input type="text" class="search" id="input-search" placeholder="Search">
        </div>
        <ul class="search-results">
          <li><a href="#get-a-specific-kitten">Get a Specific Kitten</a></li>
          <li><a href="#introduction">Introduction</a></li>
          <li><a href="#errors">Errors</a></li>
          <li><a href="#authentication">Authentication</a></li>
          <li><a href="#get-all-kittens">Get All Kittens</a></li>
        </ul> -->
        <div id="toc" class="tocify">
        <!-- <ul id="tocify-header0" class="tocify-header">
            <li class="tocify-item tocify-focus" data-unique="introduction" style="cursor: pointer;"><a>Introduction</a></li>
        </ul>
        <ul id="tocify-header1" class="tocify-header">
            <li class="tocify-item" data-unique="authentication" style="cursor: pointer;"><a>Authentication</a></li>
        </ul>
        <ul id="tocify-header2" class="tocify-header">
            <li class="tocify-item" data-unique="kittens" style="cursor: pointer;"><a>Kittens</a></li>
              <ul class="tocify-subheader" data-tag="2" style="display: none;">
                <li class="tocify-item" data-unique="get-all-kittens"><a>Get All Kittens</a></li>
                <li class="tocify-item" data-unique="get-a-specific-kitten"><a>Get a Specific Kitten</a></li>
              </ul>
            </ul>
            <ul id="tocify-header3" class="tocify-header">
              <li class="tocify-item" data-unique="errors"><a>Errors</a></li>
            </ul> -->


<nav id="myscroll">
            <ul class="nav nav-pills nav-stacked tocify-header" @click="toggleSideMenu()" data-spy="affix" data-offset-top="0">
              <li class="tocify-item"><a href="#section1">Section 1</a></li>
              <li class="tocify-item"><a href="#section2">Section 2</a></li>
              <li class="tocify-item"><a href="#section3">Section 3</a></li>
              <li class="tocify-item">
                <a class="dropdown-toggle" href="#section4">Section 4</a>
                <ul class="dropdown-menu tocify-subheader">
                  <li class="tocify-item"><a href="#section41">Section 4-1</a></li>
                  <li class="tocify-item"><a href="#section42">Section 4-2</a></li>
                </ul>
              </li>
              <li class="tocify-item"><a href="#section5">Section 5</a></li>
            </ul>
</nav>
</div><!-- .tocify -->
        <ul class="toc-footer">
            <li><a href="#">Sign Up for a Developer Key</a></li>
            <li><a href="https://github.com/tripit/slate">Documentation Powered by Slate</a></li>
        </ul>
  </div><!-- .tocify-wrapper -->

  <div class="page-wrapper">
    <div class="dark-box"></div>
    <div class="content">
      <div name="introduction" data-unique="introduction"></div>

      <h1 id="introduction">Introduction</h1>

      <p>Welcome to the Kittn API! You can use our API to access Kittn API endpoints,
          which can get information on various cats, kittens, and breeds in our database.
        <br/>
        We have language bindings in Shell, Ruby, and Python! You can view code examples in
        the dark area to the right, and you can switch the programming language of the examples
        with the tabs in the top right.
        <br/>
        This example API documentation page was created with Slate. Feel free to edit it and use
        it as a base for your own API’s documentation.
      </p>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>

      <aside class="notice">
      You must replace <code>meowmeowmeow</code> with your personal API key.
      </aside>

      <h1 id="section1">Section A</h1>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>

      <h3 id="http-request">HTTP Request</h3>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>

      <table><thead>
      <tr>
      <th>Parameter</th>
      <th>Default</th>
      <th>Description</th>
      </tr>
      </thead><tbody>
      <tr>
      <td>include_cats</td>
      <td>false</td>
      <td>If set to true, the result will also include cats.</td>
      </tr>
      <tr>
      <td>available</td>
      <td>true</td>
      <td>If set to false, the result will include kittens that have already been adopted.</td>
      </tr>
      </tbody></table>

      <blockquote>
      <p>To authorize, use this code:</p>
      </blockquote>


      <h1 id="section2">Section 2</h1>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>

      <pre class="highlight json">
        <code >
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Max",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
        </code>
      </pre>
      <table><thead>
      <tr>
      <th>Parameter</th>
      <th>Default</th>
      <th>Description</th>
      </tr>
      </thead><tbody>
      <tr>
      <td>include_cats</td>
      <td>false</td>
      <td>If set to true, the result will also include cats.</td>
      </tr>
      <tr>
      <td>available</td>
      <td>true</td>
      <td>If set to false, the result will include kittens that have already been adopted.</td>
      </tr>
      </tbody></table>

      <blockquote>
      <p>To authorize, use this code:</p>
      </blockquote>



      <aside class="success">
      Remember — a happy kitten is an authenticated kitten!
      </aside>



      <h1 id="section3">Section 3</h1>
      <test></test>
      <h1 id="section4">Section 4</h1>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>


      <table><thead>
      <tr>
      <th>Parameter</th>
      <th>Default</th>
      <th>Description</th>
      </tr>
      </thead><tbody>
      <tr>
      <td>include_cats</td>
      <td>false</td>
      <td>If set to true, the result will also include cats.</td>
      </tr>
      <tr>
      <td>available</td>
      <td>true</td>
      <td>If set to false, the result will include kittens that have already been adopted.</td>
      </tr>
      </tbody></table>
      <h1 id="section41">Section 41</h1>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>

<test></test>
      <table><thead>
      <tr>
      <th>Parameter</th>
      <th>Default</th>
      <th>Description</th>
      </tr>
      </thead><tbody>
      <tr>
      <td>include_cats</td>
      <td>false</td>
      <td>If set to true, the result will also include cats.</td>
      </tr>
      <tr>
      <td>available</td>
      <td>true</td>
      <td>If set to false, the result will include kittens that have already been adopted.</td>
      </tr>
      </tbody></table>


      <h1 id="section42">Section 42</h1>
      <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>


      <table><thead>
      <tr>
      <th>Parameter</th>
      <th>Default</th>
      <th>Description</th>
      </tr>
      </thead><tbody>
      <tr>
      <td>include_cats</td>
      <td>false</td>
      <td>If set to true, the result will also include cats.</td>
      </tr>
      <tr>
      <td>available</td>
      <td>true</td>
      <td>If set to false, the result will include kittens that have already been adopted.</td>
      </tr>
      </tbody></table>


    </div><!-- /content -->
  </div>
</div>
</template>
<script>
export default {
  data () {
    return {
      'sideMenu': false
    }
  },
  components: {
    test: require('./components/test.vue')
  },
  methods: {
    toggleSideMenu: function () {
      console.log('toggleSideMenu')
      this.sideMenu = !this.sideMenu
    }
  }
}
</script>

<style>

a{
  color:#fff;
}
.page-wrapper .dark-box,
.content pre, .content blockquote{
  width: 45%;
}
.content>h1, .content>h2, .content>h3,
.content>h4, .content>h5, .content>h6,
.content>p, .content>table, .content>ul,
.content>ol, .content>aside, .content>dl{
  width: 55%;
}
.nav-stacked>li+li{
  margin-top: 0;
}
.tocify-item{

}
blockquote{
  font-size: inherit;
  border: none;
}
pre{
  border: none;
  border-radius: 0;
}
.tocify-item:hover > a{
  background-color: transparent;
}
.nav-pills>li>a, .nav-pills>li>a:focus, .nav-pills>li>a:hover{
    transition: all linear 250ms;
}
.nav-pills>li.active>a, .nav-pills>li.active>a:focus, .nav-pills>li.active>a:hover{
  box-shadow: 0px 1px 0px #000;
  background-color: #2467af;
  transition: all linear 250ms;
}
.nav-pills>li>a{
  border-radius: 0;
}
.tocify-wrapper .tocify-item>a, .tocify-wrapper .toc-footer li{
  height: 28px;
  line-height: 28px;
}
.nav{
  width: 100%;
}
.affix{
  position: relative;
}
.open>.dropdown-menu{
  width: 100%;
  transition: all ease-in 500ms;
}
.dropdown-menu li:hover a{
  background-color: #2467af;
}
.open .tocify-item >a{
  height: 28px;
  line-height: 28px;
  color: #fff;
}
.tocify-wrapper .tocify-subheader .tocify-item>a{
  color: #fff;
}
.dropdown-menu>.active>a, .dropdown-menu>.active>a:focus, .dropdown-menu>.active>a:hover{
  background-color: #2467af;
}
.nav-pills>li:hover>a{
  background: transparent;
  color: #fff;
}
.open .nav-pills>li:hover>a{
  background: transparent;
}
.nav .open>a, .nav .open>a:focus, .nav .open>a:hover{
  background: transparent;
}
.dropdown-toggle{
  padding: 0 15px;
}

.active>.dropdown-menu,.open>.dropdown-menu {
    display: block;;
    transition: all linear 250ms;
    border-radius: 0;
}
.tocify-subheader{
  width: 100%;
}
.dropdown-menu{
  position: relative;
}
.nav-pills>li.active>a:focus{
background: transparent;
}
table{
  font-size: 13px;
}
.tocify-item:hover{
  background: #2467af;
}
@media (max-width: 700px){
  .page-wrapper .dark-box,
  .content pre, .content blockquote{
    width: 100%;
  }
  .content>h1, .content>h2, .content>h3,
  .content>h4, .content>h5, .content>h6,
  .content>p, .content>table, .content>ul,
  .content>ol, .content>aside, .content>dl{
    width: 100%;
  }
}

</style>
