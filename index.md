---
layout: page
title: Pyrocake's Projects
subtitle: the home of my projects
nav-short: false
---

<div class="features-container" markdown="1">

> <i class="fa-solid fa-calendar"></i> **Up to Date**{:.item-header}
>
> Extra care will always be made to keep mods up to date, even if most are outdated.
{:.note.center-text.feature-item}
^

> <i class="fas fa-terminal"></i> **Mod Loader**{:.item-header}
>
> All mods are currently prioritizing NeoForge, but I may support more at a later date
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

<style>
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

.features-container {
    gap: 1em;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    margin: 1em auto;
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
    .features-container {
        grid-template-columns: 1fr;
        grid-template-rows: repeat(3, 1fr);
    }

    .intro-header .page-heading h1 {
        margin-top: 0;
        font-size: 2.5em;
    }
}
</style>