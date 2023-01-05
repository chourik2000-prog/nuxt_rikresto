<template>
    <div class="w-full shadow pt-10">
        <p aria-label="CodePen" class="flex justify-center ">
        <span data-text="R">R</span>
        <span data-text="I">I</span>
        <span data-text="K">K</span>
        <span data-text="R">R</span>
        <span data-text="E">E</span>
        <span data-text="S">S</span>
        <span data-text="T">T</span>
        <span data-text="O">O</span>
    </p>
    </div>
</template>
<style scoped>
 p {
    color: #fff;
    font-family: Avenir Next, Helvetica Neue, Helvetica, Tahoma, sans-serif;
    font-size: 1em;
    font-weight: 700;
    }
    p span {
    display: inline-block;
    position: relative;
    transform-style: preserve-3d;
    perspective: 500;
    -webkit-font-smoothing: antialiased;
    }
    p span::before,
    p span::after {
    display: none;
    position: absolute;
    top: 0;
    left: -1px;
    transform-origin: left top;
    transition: all ease-out 0.3s;
    content: attr(data-text);
    }
    p span::before {
    z-index: 1;
    color: rgba(0,0,0,0.2);
    transform: scale(1.1, 1) skew(0deg, 20deg);
    }
    p span::after {
    z-index: 2;
    color: #166534;
    text-shadow: -1px 0 1px #684da3, 1px 0 1px rgba(0,0,0,0.8);
    transform: rotateY(-40deg);
    }
    p span:hover::before {
    transform: scale(1.1, 1) skew(0deg, 5deg);
    }
    p span:hover::after {
    transform: rotateY(-10deg);
    }
    p span + span {
    margin-left: 0.3em;
    }
    @media (min-width: 20em) {
    p {
    font-size: 2em;
    }
    p span::before,
    p span::after {
    display: block;
    }
    }
    @media (min-width: 30em) {
    p {
    font-size: 3em;
    }
    }
    @media (min-width: 40em) {
    p {
    font-size: 5em;
    }
    }
    @media (min-width: 60em) {
    p {
    font-size: 8em;
    }
    }
</style>