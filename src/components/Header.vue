<template>
    <header>
        <div class="container">
            <div class="nav-items">
                <div class="nav-item">
                    <div class="nav-item-brand">
                        <img src="../assets/images/logo.png" alt="brand" />
                        <h1>MINIMAL</h1>
                    </div>
                </div>
                <div class="nav-item">
                    <ul class="nav-item-links">
                        <li><a href="#process">process</a></li>
                        <li><a href="#project">projects</a></li>
                        <li><a href="#team">team</a></li>
                        <li><a href="#contact">contact</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&display=swap");
header {
    width: 100%;
    padding: 18px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 106px;
    flex-shrink: 0;
}

.container {
    width: 940px;
}
.nav-items {
    width: 100%;
    display: flex;
    justify-content: space-between;
}
.nav-item {
    display: flex;
    align-items: center;
}
.nav-item-brand {
    display: flex;
    align-items: center;
    gap: 18px;
    cursor: pointer;
    img {
        width: 65px;
        height: 70px;
    }
    h1 {
        color: #333;
        font-family: "Oswald", sans-serif;
        font-size: 22px;
        font-style: normal;
        font-weight: 400;
        line-height: 38px; /* 172.727% */
        text-transform: uppercase;
    }
}
.nav-item-links {
    display: flex;
    justify-content: space-between;
    gap: 34px;
    padding-left: 34px;
    li a {
        color: #404040;
        font-family: "Montserrat", sans-serif;
        font-size: 12px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 166.667% */
        text-transform: uppercase;
    }
}

li {
    list-style: none;
    transition: all 0.3s linear;
    padding: 10px;
}

li:hover {
    transform: scale(1.1);
    border: 1px solid #59bbb1;
    a {
        color: #59bbb1;
    }
}

a {
    text-decoration: none;
}

@media (max-width: 567px) {
    .header {
        width: 100%;
    }

    .nav-item-brand {
        display: none;
    }

    .nav-item-links {
        font-size: 10px;
    }
}
</style>

<script></script>
