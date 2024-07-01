+++
title = "Tool Design"
description = "Hugo, the world’s fastest framework for building websites"
date = "2024-02-28"
aliases = ["about-us","about-hugo","contact"]
author = "Hugo Authors"
+++

During the spring semester of my freshman year, I enrolled in
<span class="interactive-word">Tool Design.</span><span class="hidden-text"> [aka 2.S02; one of the successors to the beloved and now discontinued 2.00B :pensive:]</span>
I wanted to get a taste of what mechanical engineering looks like and Tool Design I thought was (now I truly believe) the best class to do so.

As my first "real" project-based mechanical engineering course at MIT, the work we did stayed true to the title of the course; we built tools

<style>
    .interactive-word {
        color: #FA8072 !important; /* Highlight color */
        cursor: pointer !important;
        font-weight: bold !important;
        transition: background-color 0.5s ease, color 0.5s ease !important;
    }

    .interactive-word:hover {
        background-color: #D0E2FF !important; /* Light blue background on hover */
        color: #0056b3 !important; /* Darker blue on hover */
    }

    .hidden-text {
        display: none !important;
        opacity: 0 !important;
        color: #FA8072 !important; /* Text color for the hidden text */
        padding: 0 0.2em !important; /* Optional: Adds a bit of padding for better readability */
        font-weight: bold !important;
        transition: opacity 5s ease !important;
    }

    .hidden-text.show {
        display: inline !important;
        opacity: 1 !important;
    }
</style>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        var word = document.querySelector('.interactive-word');
        var hiddenText = document.querySelector('.hidden-text');

        word.addEventListener('click', function() {
            hiddenText.classList.toggle('show');
        });
    });
</script>




Written in Go, Hugo is an open source static site generator available under the [Apache Licence 2.0.](https://github.com/gohugoio/hugo/blob/master/LICENSE) Hugo supports TOML, YAML and JSON data file types, Markdown and HTML content files and uses shortcodes to add rich content. Other notable features are taxonomies, multilingual mode, image processing, custom output formats, HTML/CSS/JS minification and support for Sass SCSS workflows.

Hugo makes use of a variety of open source projects including:

* https://github.com/yuin/goldmark
* https://github.com/alecthomas/chroma
* https://github.com/muesli/smartcrop
* https://github.com/spf13/cobra
* https://github.com/spf13/viper

Hugo is ideal for blogs, corporate websites, creative portfolios, online magazines, single page applications or even a website with thousands of pages.

Hugo is for people who want to hand code their own website without worrying about setting up complicated runtimes, dependencies and databases.

Websites built with Hugo are extremelly fast, secure and can be deployed anywhere including, AWS, GitHub Pages, Heroku, Netlify and any other hosting provider.

Learn more and contribute on [GitHub](https://github.com/gohugoio).
