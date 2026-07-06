<script setup>
</script>

<template>
    <main>
        <section>
            <p>First solve the problem then write the code</p>
            <span>John johnson</span>
        </section>

        <button>Another!</button>
    </main>

</template>

<style scoped>
    main{
        background: #ccd6d9;
        max-width: 90%;
        border-radius: 0 15px 0 15px;
        padding: 35px;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 10px;
    }

    section {
        display: flex;
        width: 100%;
        flex-direction: column;
        gap: 10px;
        margin-bottom: 25px;
    }

    p {
        font-weight: bold;
        font-style: italic;
        font-size: 2rem;
        text-align: left;
    }

    button{
        background: #406473;
        color: whitesmoke;
        padding: 10px;
        border: 0;
        font-size: 1.2rem;
        border-radius: 0 5px 0 5px;
        margin-top: 20px;
        cursor: pointer;
        transition: transform 0.2s;
    }

    button:hover{
        transform: scale(1.05);
    }

    span{
        align-self: end;
        color: #406473;
    }



</style>