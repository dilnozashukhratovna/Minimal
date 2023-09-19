<template>
    <div class="footer" id="footer">
        <div class="container">
            <div class="footer-items">
                <div class="footer-form">
                    <input type="text" placeholder="Name" />
                    <input type="email" placeholder="Email" />
                    <input type="text" placeholder="Budget" />
                    <textarea
                        cols="30"
                        rows="10"
                        placeholder="Describe your project..."
                    ></textarea>
                    <button>Send Message</button>
                </div>
                <div class="footer-logo">
                    <img src="../assets/images/logo2.png" alt="footer_logo" />
                </div>
                <p>Minimal Template made in Webflow. All rights reserved.</p>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&family=Vollkorn&display=swap");

.container {
    width: 940px;
    margin: auto;
}
.footer {
    width: 100%;
    background: #000;
}
.footer-items {
    width: 60%;
    display: flex;
    flex-direction: column;
    gap: 15px;
    padding-top: 70px;
    padding-bottom: 20px;
    margin: 0 auto;

    p {
        color: rgba(255, 255, 255, 0.4);
        text-align: center;
        font-family: "Vollkorn", serif;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 146.667% */
        margin: 0 auto;
    }
}

.footer-form {
    input {
        width: 100%;
        padding: 18px 30px;
        color: #fff;
        font-size: 16px;
        color: #fff;
        font-family: "Vollkorn", serif;
        font-style: italic;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
        outline: none;
        border: none;
        &::placeholder {
            color: #fff;
        }
        &:nth-child(odd) {
            background: rgba(255, 255, 255, 0.18);
        }
        &:nth-child(even) {
            background: rgba(255, 255, 255, 0.2);
        }
    }
    textarea {
        width: 100%;
        padding: 18px 30px;
        color: #fff;
        font-size: 16px;
        color: #fff;
        font-family: "Vollkorn", serif;
        font-style: italic;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
        background: rgba(255, 255, 255, 0.2);
        height: 127px;
        flex-shrink: 0;
        resize: none;
        border: none;
        outline: none;
        &::placeholder {
            color: #fff;
        }
    }
    button {
        width: 40%;
        padding: 15px;
        margin: 20px 30%;
        border: 1px solid #7ec4bd;
        color: #8bcac3;
        text-align: center;
        font-family: "Vollkorn", serif;
        font-size: 17px;
        font-style: italic;
        font-weight: 400;
        line-height: 22px; /* 129.412% */
        background: transparent;
        cursor: pointer;
        transition: all 0.2s linear;
    }
    button:hover {
        background: #7ec4bd;
        color: #000;
        transform: scale(1.1);
    }
}
.footer-logo {
    margin: auto;
}

@media (max-width: 776px) {
    .footer-items {
        width: 100%;
    }
}
@media (max-width: 567px) {
    .footer-form {
        input,
        textarea {
            padding: 12px 25px;
        }
        button {
            padding: 12px;
            font-size: 14px;
            border-radius: 5px;
        }
    }
    .footer-logo {
        width: 40px;
        img {
            width: 100%;
        }
    }
    .footer-items {
        p {
            font-size: 12px;
        }
    }
}
</style>
