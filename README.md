# Refactoring-code-example-site

Develop a portfolio site using navbar, responsive, layout, responsive images. Minimize the use of media queries. On an xs screen, content should take up the entire screen. On larger screens, you should have some margins on the left and right sides of the screen.

<br>

## Refactor While Maintaining Accessibility Standards

===========
![Image](/assets/images/Screenshot.png)

<br>

## Condense Css Elements

```
.benefit-lead, .benefit-cost, .benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
    text-align: center;
}
```
<br>

## Correct Html Semantics

```
<article class="content">
    <article class="search-engine-optimization">
        <img src="./assets/images/search-engine-optimization.jpg" alt="notebook" class="float-left" />
        <h2>Search Engine Optimization</h2>
        <p>The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.</p>
    </article>
    <article class="online-reputation-management">
        <img src="./assets/images/online-reputation-management.jpg" alt="laptop and phone" class="float-right" />
        <h2>Online Reputation Management</h2>
        <p>The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.</p>
    </article>
    <article class="social-media-marketing">
        <img src="./assets/images/social-media-marketing.jpg" alt= "conference table" class="float-left" />
        <h2>Social Media Marketing</h2>
        <p>Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.</p>
    </article>
</article>
```
<br>

## HTLM Elements Follow Logical Structure

```
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li><a href="#search-engine-optimization">Search Engine Optimization</a></li>
                <li><a href="#online-reputation-management">Online Reputation Management</a></li>
                <li><a href="#social-media-marketing">Social Media Marketing</a></li>
            </ul>
        </div>
</header>
```

<br>

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Deployed Link

* [See Live Site](https://jas-f.github.io/Refactoring-example-site/)

## License

This project is licensed under the MIT License 

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## Prerequisites

Git hub
Git lab
Git bash
Visual studio
Google chrome
## Authors

**Jasmine Franklin** 

- [Link to Portfolio Site](https://github.com/Jas-F/responsive-portfolio)
- [Link to Github](https://github.com/)
- [Link to LinkedIn](https://www.linkedin.com/in/jasmine-franklin-8b08ba121)

<p>&copy; UC Berkeley Extension Bootcamp.</p>


