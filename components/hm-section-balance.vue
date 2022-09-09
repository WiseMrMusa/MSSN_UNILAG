<template>
    <section class="balance">
        <h2>Building a balanced personality</h2>
        <div class="card-wrapper">
            <div class="hi-card" v-for="item in items" v-bind:key="item.id">
                <h3>{{item.title}}</h3>
                <p>{{item.text}}</p>
            </div>
        </div>
    </section>
</template>

<style>
    section.balance {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        padding: 50px;
    }

    h2 {
        font-family: Archivo;
        font-size: 42px;
        font-weight: 400;
    }

    .card-wrapper {
        display: flex;
        flex-direction: row;
        align-items: center;
        column-gap: 32px;
    }

    .hi-card {
        border: 1px solid black;
        padding: 20px;
        max-width: 10rem;
        text-align: center;
    }
</style>

<script>
   export default {
    data() {
        return {
            items: [
                {id:0, title: 'Spirituality', text:'We are going to write a little explanation about spirituality here'},
                {id:1, title:'Intellectuality', text: 'We are going to write a little explanation about spirituality here'},
                {id:2, title:'Morality', text: 'We are going to write a little explanation about spirituality here'}
            ]
        }
    }
   }
</script>