# My Thinking Process 👍

* ## Preparing Phase
1. Understand the purposes and details project, then prepare and import any resources into project.
2. Initialize project such as <!link>import css, reset css,import fonts, define var(--color-in-project), and etc.

* ## HTML Structuring Phase
1. Define .container to set the default big box of my site. (1200px width)
2. Now I already have a big black box, then i need some .wrapper to help me wrap up and arrange any mini-box for each Section.
3. It's construction time.. (like this)
```
<body>
    <!-- <h1>42-ong-colmar</h1> -->

    <!-- Start of Header -->
    <header>
        <div class="container">
            <nav class="nav-wrapper">
                
            </nav>
        </div>
    </header>
    <!-- End of Header -->

    <!-- Start of Main -->
    <main>
        <!-- Start of Section hero -->
        <section class="hero">
            <div class="container">
                <div class="hero-wrapper">
...
</body>
```
4. Ok, It's about time to push the first commit. 😋 