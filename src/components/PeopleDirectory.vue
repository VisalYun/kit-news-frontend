<template>
    <div class="directory">
        <h2>People Directory</h2>
        <input
            type="text"
            class="text-input"
            placeholder="search for people"
        />
    </div>
</template>

<script>
export default {
    name: "PeopleDirectory",
    setup(){

    }
}
</script>

<style scoped>
.directory {
    padding: 20px;
    background-color: #fbfbfb;
}

.text-input {
    display: block;
    margin: 10px 0px;
    width: 100%;
    padding: 10px;
    border: none;
    outline: none;
    font-size: 1.1em;
}
</style>