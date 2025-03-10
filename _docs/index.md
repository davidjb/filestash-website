---
layout: documentation
title: Getting started
order: 1
permalink: /docs
---

To use Filestash, you can either:
1. selfhost it on your own server and manage everything yourself: [see the documentation](/docs/install-and-upgrade/)
2. get the best solution for your needs by becoming a customer: [see the pricing](/pricing/)

<p class="center">
    Also, you can try Filestash with your own backend:
</p>
<iframe style="width: 100%;height: 500px;border: 9px solid #0000001a;border-radius: 5px;" id="appframe" frameborder="0" src="https://demo.filestash.app/login" allow="fullscreen;speaker"></iframe>

<div class="related">
    <div class="title">
        Related Pages <br>
        <img src="https://mickael.kerjean.me/assets/img/arrow_bottom.png"/>
    </div>
    <div class="related_content">
        <a href="https://demo.filestash.app/"><h3 class="no-anchor">Demo Instance</h3></a><a href="{% post_url 2019-11-26-ftp-web-client %}"><h3 class="no-anchor">FTP Client</h3></a><a href="{% post_url 2019-11-21-s3-browser %}"><h3 class="no-anchor">S3 Client</h3></a>
    </div>
</div>

<style>
.related{ text-align:center;margin-top:50px;}
.related .title{
    font-size: 1.5em;
    margin-top: 30px;
}
.related .title img{
    animation: bounce 1s infinite alternate;
    width: 16px;
    height: 17px;
}
.related .related_content { margin-top:5px; }
.related .related_content h3 {
    background: var(--bg-color);
    padding: 50px 0;
    border-radius: 5px;
    margin: 0!important;
}
.related .related_content a{
    display: inline-block;
    width: 33%;
    padding: 5px;
    text-decoration: none!important;
}
.related .related_content a:hover{
    transform: scale(1.1);
    transition: ease 0.3s transform;
}
.related .related_content a:hover h3{
    background: var(--emphasis-primary);
    transition: ease 0.3s background;
}

@media only screen and (max-width: 550px) {
    .related .related_content a{ width: 100%; }
}
@keyframes bounce {
    from {
        transform: translate3d(0,0,0);
    }
    to {
        transform: translate3d(0,-8px,0);
    }
}
</style>
