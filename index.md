---
layout: page
title: Pyrocake's Projects
subtitle: the home of my projects
nav-short: false
---

<head>
    <title>{{ site.title }}</title>
</head>

<style>
:root {
    --large-box-count: 2; /* Change this number to set the count of large boxes */
}

.center-text {
    text-align: center;
}

.center-box {
    max-width: fit-content;
    margin-left: auto;
    margin-right: auto;
}

.getting-started {
    background-color: rgba(187, 187, 187, 0.1);
    border-radius: 5px;
}

.large-features-container {
    gap: 1em;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Allow flexibility while keeping them side by side */
    margin: 1em auto;
    max-width: 90%; /* Keep the large boxes wide without stacking */
}

.large-feature-item {
    margin: 0;
    padding: 1em 1.5em; /* Reduced padding to minimize wasted space */
    font-size: 1.2em;
    border-radius: 10px;
    text-decoration: none;
    display: block;
    color: inherit;
    transition: background-color 0.3s ease;
}

/* Radiant box color */
.large-feature-item:nth-child(1) {
    background-color: #FFD700; /* Warm golden sunlight color */
}

.large-feature-item:nth-child(1):hover {
    background-color: #E6C200; /* Slightly darker golden on hover */
}

/* Grass mod box color */
.large-feature-item:nth-child(2) {
    background-color: #4CAF50; /* Fresh grassy green */
}

.large-feature-item:nth-child(2):hover {
    background-color: #3D8B40; /* Darker green on hover */
    color: #f1f1f1; /* Lighter text color when hovered for better contrast */
}

.features-container {
    gap: 1em;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    margin: 1em auto;
    max-width: 75%; /* Keep small boxes contained for better contrast */
}

.feature-item {
    margin: 0;
    padding-left: 0.6em;
    padding-right: 0.6em;
    font-size: 0.9em;
    background-color: rgba(187, 187, 187, 0.1);
    border-radius: 10px;
}

.feature-item * {
    margin-top: 0.5em;
    margin-bottom: 0.5em;
}

.item-header {
    font-size: 1.1em;
}

@media (max-width: 719px) {
    .large-features-container {
        grid-template-columns: 1fr;
        max-width: 100%;
    }

    .features-container {
        grid-template-columns: 1fr;
        grid-template-rows: repeat(3, 1fr);
        max-width: 100%;
    }

    .intro-header .page-heading h1 {
        margin-top: 0;
        font-size: 2.5em;
    }
}


</style>

<div class="large-features-container">
    <a href="#" class="large-feature-item">
        <i class="fa-solid fa-sun"></i> <strong class="item-header">Radiant</strong>
        <p>A sunlight-based magic mod where the sky gives you no limits</p>
    </a>
    <a href="#" class="large-feature-item">
        <i class="fa-solid fa-seedling"></i> <strong class="item-header">UGM</strong>
        <p>A mod that increases the biodiversity of minecraft's permaculture</p>
    </a>
</div>

<div class="features-container" markdown="1">

> <i class="fa-solid fa-calendar"></i> **Up to Date**{:.item-header}
>
> Extra care will always be made to keep mods up to date, even if most are outdated.
{:.note.center-text.feature-item}
^

> <i class="fas fa-terminal"></i> **NeoForge**{:.item-header}
>
> NeoForge comes first, but I may support more at a later date
{:.note.center-text.feature-item}
^

> <i class="fa-brands fa-github"></i> **Open Source**{:.item-header}
>
> All my modern projects are open source and can be found on [Github][MY GITHUB]
{:.note.center-text.feature-item}

</div>

> **License** \
> _All projects are under the [MIT License][MIT]_
{:.note.getting-started.center-box.center-text}

[MIT]: https://www.tldrlegal.com/license/mit-license
[MY GITHUB]: https://github.com/Pyrocake
