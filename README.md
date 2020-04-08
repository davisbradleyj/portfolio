# Portfolio page

## Technologies Used
- HTML - used to create elements on the DOM
- CSS - present to add styling elements
- JavaScript - controls minor functionality on the page
- Bulma - automate syling elements
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed to GitHub Pages

## Summary

With exposure to Bulma as the HTML/CSS framework in Project One, I thought this would be a great opportunity to experienment with some of the possibilities that framework provides.  I find the aesthetics and ease of use to be appealing feature, though the fact that there are some JavaScript elements that need to be added in makes some features a little tricky to implement at this stage. An example of this is seen in the code snippet, where I had to add in the toggle to allow the mobile responsive "burger" to show the dropdown menu of page links.

The header nav bar has links to the various sections of the page, and a link to a resume for any interested client.  The Skills section include some soft skills and known languages/technologies relevant for Front-End Development.  The Projects section include the Team Project deployed application, and my two most recently deployed solo applications - each tile is linked to the deployed site through the title, has a short description of the application, a link to the Gibhub repo, and the month/year of first live deployment.  Contact details includes and email prompt, a link to my LinkedIn page, a link to my Github site, and a link to my Medium page.

<img src="https://github.com/davisbradleyj/portfolio/blob/master/assets/images/portfolio_mobile.gif">

## Code Snippet

```html
    <section class="hero-head is-mobile">
        <nav class="navbar is-link">
            <div class="container">
                <div class="navbar-brand">
                    <span class="navbar-burger burger" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" data-target="navbarMenuHeroA">
                        <span></span>
                        <span></span>
                        <span></span>
                    </span>
                </div>
                <div id="navbarMenuHeroA" class="navbar-menu has-background-link">
                    <div class="navbar-end has-background-link">
                        <a class="navbar-item has-background-link has-text-white-ter">
                            Home
                        </a>
                        <a class="navbar-item has-background-link has-text-white-ter" href="#skills">
                            Skills
                        </a>
                        <a class="navbar-item has-background-link has-text-white-ter" href="#projects">
                            Projects
                        </a>
                        <a class="navbar-item has-background-link has-text-white-ter" href="#contact">
                            Contact
                        </a>
                        <a class="navbar-item has-background-link has-text-white-ter" href="./assets/Brad_Davis_April_2020.pdf" target="_new">
                            Resume
                        </a>
                    </div>
                </div>
            </div>
        </nav>
    </section>
```


## Acknowledgements

Jerome Chenette, Kerwin Hy, Mahisha Manikandan, Corbin Brockbank

## Author Links

Brad Davis
[Email](davis.bradleyj@gmail.com)
[LinkedIn](https://www.linkedin.com/in/brad-davis-7885884/)
[GitHub](https://github.com/davisbradleyj)
[Medium](https://medium.com/@davis.bradleyj)
