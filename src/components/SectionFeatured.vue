<template>
    <section class="sectiion-featured">
        <div class="container">
            <h2 class="heading-featured-in">As featured in</h2>
            <div class="logos">
                <img src="../assets/img/logos/techcrunch.png" alt="techcrunch logo">
                <img src="../assets/img/logos/business-insider.png" alt="business insider logo">
                <img src="../assets/img/logos/the-new-york-times.png" alt="the new york times logo">
                <img src="../assets/img/logos/forbes.png" alt="forbes logo">
                <img src="../assets/img/logos/usa-today.png" alt="usa today logo">
            </div>
        </div>
    </section>
</template>
<style>
.sectiion-featured{
    padding: 4.8rem 0 3.2rem 0;
}
.heading-featured-in{
    font-size: 1.4rem;
    text-transform: uppercase;
    letter-spacing: 0.75;
    font-weight: 500;
    text-align: center;
    margin-bottom: 2.4rem;
    color: #888;
}
.logos{
    display: flex;
    justify-content: space-around;
}
.logos img{
    height: 3.2rem;
    filter: brightness(0);
    opacity: 50%;
}
</style>