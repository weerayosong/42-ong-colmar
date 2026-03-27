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

* ## header(nav) section build Phase
1. Everyday I'm shuffling, lol. but today I'll use pure CSS (because I'm not ready to use TailwindCSS yet.)
2. I'm not proficient in mobile-first or responsive yet, then I'll start with what I good at first. (Yup, it's desktop view.)
3. I'll make my website with each section from top to bottom. one-by-one at a time.
4. first section >> header(nav) with its css
  - html >> nothing much .nav-logo on the left, ul.nav-menu on the right
  - css >> justify them with flex "space-between" (like this)
```
/* Start of nav */
.nav-wrapper {
    height: 64px;
    background-color: var(--white);
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 24px;

    .nav-logo { ...
```
5. Boom! it's time for second commit to push. 🤩

* ## super HERO! section build Phase 😈
1. Yup, left box image, right one's h1 slogan some p and my cool button with a.
2. flex default for box left(banner) and right(info)
3. add some details eg. margin padding etc.
4. HERO's time! Push!

* ## information section build Phase
1. It's look complicate at first sight but nah, you can do it!
2. first, see it as a 2 boxes >> left one and right  💊🩹..Which one do you choose? Neo.
3. just complete the left one first, .information-main >> img h2 q and p, flex column for this box, cool~ 😎
4. Now, solve the another mystery, the right one, flex column'll bless you, cool~ 😎
5. Makeup them with padding margin and etc. cool? cool~ 😎
5. Push? cool~ 😎😎😎

* ## ofcourse? yup! it's course section build Phase
1. grid for the life!
2. yup, display: grid'll make this section easy like a magic >> 3 columns? "1fr 1fr 1r" 🪄
3. But this section not that's so easy, just focus on its details. 🤔
4. git add ., git commit -m "something else", git push origin main

* ## thesis section build Phase 📖📚📚📚📚📚📚📚📚📚📚📚📚📄🎓
1. This layout look familiar? yup it's information section's layout!
2. Just do it, and don't forget any details.
3. add >> commit and push.

