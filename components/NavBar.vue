<template>
    <div>
        <nav class="nav-bar">
            <ul class="menu-items">
                <li class="item">Page 1</li>
                <li class="item">Page 2</li>
                <li class="item">Page 3</li>
                <li class="item">Page 4</li>
                <li class="item">Page 5</li>
            </ul>
        </nav>
    </div>
</template>

<script>

export default {
    name: 'nav-bar',
}
</script>

<style>

.nav-bar {
    width: 100%;
}

.menu-items {
    width: 100%;
    display: flex;
    list-style: none;
    justify-content: space-around;
    padding: 10px;
    border-bottom: 1px solid rgb(200, 200, 200);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}

.item {
    font-size: 1.5rem;
    transition: color 0.2 ease-in;
}

.item:hover {
    cursor: pointer;
    color: rgb(163, 120, 204);
}
</style>