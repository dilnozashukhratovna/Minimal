<template>
    <div class="comment" id="comment">
        <div class="container">
            <div class="comment-items">
                <div class="comment-logo">
                    <img src="../assets/images/loggo.svg" alt="comment-logo" />
                </div>
                <div class="comment-cards">
                    <div class="comment-card border">
                        <div class="comment-card-desc">
                            <p>
                                “I love these guys! They did a great job. I
                                would recommend them to anyone.”
                            </p>
                        </div>
                        <div class="comment-card-img">
                            <img
                                src="../assets/images/IMAGE15.png"
                                alt="comment1"
                            />
                            <p>Julius Von Uberstien</p>
                        </div>
                    </div>
                    <div class="comment-card">
                        <div class="comment-card-desc">
                            <p>
                                “Elexis Corp. has grown immensely with the help
                                of Minimal.”
                            </p>
                        </div>
                        <div class="comment-card-img">
                            <img
                                src="../assets/images/IMAGE16.png"
                                alt="comment2"
                            />
                            <p>Rachel Stamos</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Oswald&family=Vollkorn&display=swap");
.container {
    width: 940px;
}
.comment {
    width: 100%;
    height: 620px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 0px;
    background: #f5f5f5;
}
.comment-items {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    padding: 10px;
}
.comment-logo img {
    width: 62px;
    height: 62px;
}
.comment-cards {
    width: 100%;
    display: flex;
    padding: 70px 0;
}
.comment-card {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 10px;
    padding-bottom: 5px;
}
.comment-card-img {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: #f5f5f5;
    margin-top: 12px;
    gap: 10px;
    img {
        width: 64px;
        height: 64px;
    }
}
.comment-card-img p {
    color: #ababab;
    text-align: center;
    font-family: "Montserrat", sans-serif;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px; /* 142.857% */
    text-transform: uppercase;
}
.comment-card-desc p {
    color: #333;
    text-align: center;
    font-family: "Vollkorn", serif;
    font-size: 26px;
    font-style: normal;
    font-weight: 400;
    line-height: 33px; /* 126.923% */
    width: 70%;
    margin: 0 auto;
}
.border {
    border-right: 1px solid #e2d9d9;
}
@media (max-width: 992px) {
    .comment-card-desc p {
        font-size: 16px;
    }
}
@media (max-width: 776px) {
    .comment {
        height: 750px;
    }
    .comment-items {
        padding: 100px auto;
    }
    .comment-logo {
        width: 40px;
        height: 40px;
        img {
            width: 100%;
            height: 100%;
        }
    }
    .comment-cards {
        flex-direction: column;
        gap: 20px;
        padding: 40px 0px;
        padding-bottom: 0px;
    }
    .comment-card {
        margin: 0 auto;
    }
    .comment-card-desc {
        width: 100%;
    }
    .border {
        border-right: none;
        border-bottom: 1px solid #e2d9d9;
        padding-bottom: 20px;
    }
}
@media (max-width: 567px) {
    .comment {
        height: 650px;
    }
    .comment-card-desc {
        width: 100%;
    }
    .comment-card {
        width: 100%;
    }
}
</style>
