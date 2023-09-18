<template>
    <main id="main">
        <div class="main-item1">
            <div class="container">
                <h1>Making brands stand out</h1>
                <h1>is our obsession</h1>
                <p>Let us help your brand stand out.</p>
            </div>
        </div>
        <div class="main-item2">
            <div class="container">
                <p>
                    Minimalist is a full-service digital creative agency located
                    in Ontorio Canada. We focus on design, consulting,
                    technology, and photography. We’ve been building unique
                    digital products, platforms, and experiences for the past 6
                    years. Let us help your company grow.
                </p>
                <button>Get in Touch</button>
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&family=Vollkorn&display=swap");
.container {
    width: 940px;
    // border: 1px solid red;
}

main {
    width: 100%;
    height: 684px;
    // border: 1px solid red;
}

.main-item1 {
    width: 100%;
    height: 391px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url("../assets/images/IMAGE.png");
    background-size: cover;
    background-repeat: no-repeat;
    object-fit: cover;
    background-position: center;
    .container {
        h1 {
            color: #fff;
            text-align: center;
            font-family: "Montserrat", sans-serif;
            font-size: 43px;
            font-style: normal;
            font-weight: 400;
            line-height: 55px; /* 127.907% */
            text-transform: uppercase;
        }
        p {
            color: rgba(255, 255, 255, 0.81);
            text-align: center;
            font-family: "Vollkorn", serif;
            font-size: 15px;
            font-style: normal;
            font-weight: 400;
            line-height: 20px; /* 133.333% */
            margin-top: 25px;
        }
        img {
            bottom: -26px;
            left: calc(50% - 26px);
            width: 52px;
            height: 52px;
            flex-shrink: 0;
        }
    }
}
.main-item2 {
    width: 100%;
    height: 289px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #fefec9;
    // border: 2px solid green;

    .container {
        p {
            color: #47474f;
            text-align: center;
            font-family: "Vollkorn", serif;
            font-size: 18px;
            font-style: normal;
            font-weight: 400;
            line-height: 25px; /* 138.889% */
        }
        button {
            color: #47474f;
            text-align: center;
            font-family: "Vollkorn", serif;
            font-size: 16px;
            font-style: normal;
            font-weight: 400;
            line-height: 20px; /* 125% */
            width: 159px;
            height: 53px;
            flex-shrink: 0;
            background: transparent;
            border: 1px solid #47474f;
            border-radius: 5px;
            outline: none;
            cursor: pointer;
            margin-top: 40px;
            margin-left: 41%;
            transition: all 0.3s linear;
        }
        button:hover {
            background: #47474f;
            color: #fefec9;
            transform: scale(1.1);
        }
    }
}

@media (max-width: 992px) {
    .main-item1 .container h1 {
        font-size: 36px;
        width: 80%;
        margin: 0 auto;
    }
}
@media (max-width: 776px) {
    .main-item1 .container h1 {
        font-size: 32px;
        width: 70%;
        margin: 0 auto;
    }
}
@media (max-width: 567px) {
    .main-item1 .container h1 {
        font-size: 20px;
        width: 70%;
        margin: 0 auto;
    }
    .main-item2 .container p {
        font-size: 16px;
        margin-top: 50px;
    }
    .main-item2 .container button {
        margin-top: 20px;
        margin-bottom: 40px;
    }
}
</style>

<script></script>
