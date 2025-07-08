<template>
    <nav class="apptaskbar">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Tasks</a></li>
            <li><a href="#">Profile</a></li>
            <li><a href="#">Settings</a></li>
        </ul>
    </nav>
</template>

<style scoped>
.apptaskbar {
    background: #054425;
    width: 180px;
    height: 100vh;
    padding: 2rem 0 2rem 0;
    position: fixed;
    left: 0;
    top: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.apptaskbar ul {
    list-style: none;   
    display: flex;
    flex-direction: column;
    gap: 2rem;
    margin: 0;
    padding: 0;
    width: 100%;
    align-items: center;
}
.apptaskbar li a {
    color: #ecf0f1;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.2s;
    font-size: 1.1rem;
    display: block;
    width: 100%;
    text-align: center;
    padding: 0.5rem 0;
    border-radius: 6px;
}
.apptaskbar li a:hover {
    color: #42b983;
    background: rgba(236, 240, 241, 0.08);
}
</style>