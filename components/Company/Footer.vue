<script setup>
const footerData = [
    {
        title: 'Courses',
        links: [
            'MBBS',
            'Bachelor of Dental Sciences',
            'Bachelor of Nursing',
            'Bachelor of Physiotherapy',
            'Bachelor in Audiology & Speech',
            'Bachelor of Imaging Technology'
        ]
    },
    {
        title: 'Colleges',
        links: [
            'AJ Institute',
            'Yenepoya Institute',
            'Nitte Institute',
            'Srinivas Institute',
            'Mangala Institute',
            'Father Mullers',
            'Kanachur Institute',
            'Tejasvini Institute'
        ]
    },
    {
        title: 'Fee Structure',
        links: [
            'Medical',
            'Paramedical',
            'Pharmacy',
            'Nursing'
        ]
    },
    {
        title: 'Services',
        links: [
            'Career Guidance',
            'College Selection',
            'Application Support',
            'Loan Assistance',
            'Application Review',
            'Scholarship Assistance',
            'Campus Visit'
        ]
    },
    {
        title: 'Company',
        links: [
            'About',
            'Leader',
            'History',
            'Culture',
            'Mission',
            'Career'
        ]
    },
]
</script>

<template>
    <footer class="page-footer-wrapper">
        <div class="main-links-container hidden md:grid grid-cols-4 mx-4">
            <div class="logo-wrapper mx-4">
                <svg class="block md:hidden" data-v-08cfe74b="" width="218" height="54" viewBox="0 0 218 54" fill="none"
                    xmlns="http://www.w3.org/2000/svg">
                    <title data-v-08cfe74b="">Hematogenix Home</title>
                    <path data-v-08cfe74b=""
                        d="M68.187 18.8913H70.9937V26.0911H78.9257V18.8913H81.7324V36H78.9257V28.5805H70.9937V36H68.187V18.8913ZM84.1149 29.7764C84.1149 28.491 84.3671 27.3683 84.8715 26.4084C85.3921 25.4321 86.1081 24.6837 87.0192 24.163C87.9467 23.6261 89.0043 23.3576 90.192 23.3576C91.3961 23.3576 92.4537 23.6017 93.3648 24.0898C94.2923 24.5779 95.0163 25.2694 95.537 26.1643C96.0739 27.0592 96.3505 28.1087 96.3668 29.3127C96.3668 29.6381 96.3424 29.9717 96.2936 30.3134H86.8728V30.4598C86.9379 31.5499 87.2796 32.4123 87.8978 33.0469C88.5161 33.6814 89.3378 33.9987 90.3629 33.9987C91.1764 33.9987 91.8598 33.8116 92.413 33.4374C92.9662 33.0469 93.3323 32.5018 93.5113 31.8021H96.1471C95.9193 33.0713 95.3011 34.1126 94.2923 34.9261C93.2997 35.7397 92.055 36.1464 90.5581 36.1464C89.2565 36.1464 88.1175 35.8861 87.1413 35.3654C86.1813 34.8285 85.4328 34.08 84.8959 33.1201C84.3752 32.1601 84.1149 31.0455 84.1149 29.7764ZM93.6821 28.3853C93.5682 27.4741 93.2021 26.7663 92.5838 26.2619C91.9818 25.7413 91.2171 25.4809 90.2897 25.4809C89.4273 25.4809 88.6788 25.7494 88.0443 26.2863C87.426 26.807 87.068 27.5067 86.9704 28.3853H93.6821ZM112.922 23.3576C114.289 23.3576 115.403 23.805 116.265 24.6999C117.128 25.5786 117.559 26.9941 117.559 28.9466V36H114.923V28.971C114.923 27.8809 114.703 27.0511 114.264 26.4816C113.825 25.9121 113.174 25.6274 112.312 25.6274C111.4 25.6274 110.676 25.9528 110.14 26.6036C109.619 27.2382 109.359 28.1168 109.359 29.2395V36H106.698V28.971C106.698 27.8646 106.47 27.0348 106.015 26.4816C105.576 25.9121 104.925 25.6274 104.062 25.6274C103.167 25.6274 102.452 25.9609 101.915 26.628C101.394 27.2951 101.134 28.19 101.134 29.3127V36H98.4978V23.504H100.792L101.085 25.1393C101.98 23.9678 103.2 23.3739 104.746 23.3576C105.624 23.3576 106.397 23.5447 107.064 23.9189C107.731 24.2932 108.244 24.8626 108.602 25.6274C109.041 24.9115 109.619 24.3583 110.335 23.9678C111.051 23.561 111.913 23.3576 112.922 23.3576ZM132.078 23.504V36H129.76L129.467 34.0963C129.028 34.7146 128.466 35.2109 127.783 35.5851C127.1 35.9593 126.302 36.1464 125.391 36.1464C124.252 36.1464 123.235 35.8942 122.34 35.3898C121.445 34.8692 120.746 34.1289 120.241 33.1689C119.737 32.1926 119.485 31.0537 119.485 29.752C119.485 28.4829 119.737 27.3683 120.241 26.4084C120.762 25.4321 121.47 24.6837 122.365 24.163C123.26 23.6261 124.268 23.3576 125.391 23.3576C126.319 23.3576 127.124 23.5366 127.807 23.8945C128.491 24.2362 129.044 24.7162 129.467 25.3345L129.784 23.504H132.078ZM125.83 33.9255C126.921 33.9255 127.799 33.5431 128.466 32.7784C129.133 32.0137 129.467 31.0211 129.467 29.8008C129.467 28.5643 129.133 27.5555 128.466 26.7745C127.799 25.9935 126.921 25.603 125.83 25.603C124.74 25.603 123.862 25.9935 123.195 26.7745C122.527 27.5392 122.194 28.5317 122.194 29.752C122.194 30.9886 122.527 31.9974 123.195 32.7784C123.862 33.5431 124.74 33.9255 125.83 33.9255ZM135.46 25.8226H133.287V23.504H135.46V20.014H138.12V23.504H141.122V25.8226H138.12V32.3391C138.12 32.8272 138.217 33.177 138.413 33.3885C138.608 33.5838 138.942 33.6814 139.413 33.6814H141.415V36H138.876C137.689 36 136.818 35.7234 136.265 35.1702C135.728 34.617 135.46 33.7628 135.46 32.6075V25.8226ZM148.473 36.1464C147.221 36.1464 146.106 35.8861 145.13 35.3654C144.17 34.8285 143.421 34.08 142.884 33.1201C142.364 32.1438 142.103 31.0211 142.103 29.752C142.103 28.4992 142.364 27.3928 142.884 26.4328C143.421 25.4565 144.17 24.6999 145.13 24.163C146.106 23.6261 147.221 23.3576 148.473 23.3576C149.726 23.3576 150.833 23.6261 151.793 24.163C152.769 24.6999 153.517 25.4565 154.038 26.4328C154.575 27.3928 154.843 28.4992 154.843 29.752C154.843 31.0211 154.575 32.1438 154.038 33.1201C153.517 34.08 152.769 34.8285 151.793 35.3654C150.833 35.8861 149.726 36.1464 148.473 36.1464ZM148.473 33.9011C149.58 33.9011 150.467 33.5187 151.134 32.754C151.817 31.973 152.159 30.9723 152.159 29.752C152.159 28.5317 151.817 27.5392 151.134 26.7745C150.467 25.9935 149.58 25.603 148.473 25.603C147.367 25.603 146.48 25.9935 145.813 26.7745C145.146 27.5392 144.812 28.5317 144.812 29.752C144.812 30.9723 145.146 31.973 145.813 32.754C146.48 33.5187 147.367 33.9011 148.473 33.9011ZM169.093 23.504V35.4875C169.093 37.2447 168.572 38.6033 167.531 39.5633C166.489 40.5395 164.879 41.0277 162.698 41.0277C161.006 41.0277 159.631 40.6453 158.574 39.8806C157.516 39.1321 156.93 38.0664 156.817 36.6834H159.501C159.664 37.383 160.038 37.92 160.624 38.2942C161.21 38.6847 161.966 38.8799 162.894 38.8799C165.285 38.8799 166.481 37.7166 166.481 35.3898V33.9987C165.57 35.3654 164.212 36.0488 162.406 36.0488C161.267 36.0488 160.25 35.7966 159.355 35.2922C158.46 34.7716 157.76 34.0394 157.256 33.0957C156.751 32.1357 156.499 31.0049 156.499 29.7032C156.499 28.4504 156.751 27.3439 157.256 26.384C157.776 25.424 158.484 24.6837 159.379 24.163C160.274 23.6261 161.283 23.3576 162.406 23.3576C163.349 23.3576 164.163 23.5447 164.846 23.9189C165.53 24.2932 166.083 24.8057 166.506 25.4565L166.799 23.504H169.093ZM162.845 33.8279C163.935 33.8279 164.814 33.4536 165.481 32.7052C166.148 31.9404 166.481 30.9561 166.481 29.752C166.481 28.5154 166.148 27.5148 165.481 26.7501C164.814 25.9691 163.935 25.5786 162.845 25.5786C161.755 25.5786 160.876 25.9609 160.209 26.7257C159.542 27.4904 159.208 28.4829 159.208 29.7032C159.208 30.9235 159.542 31.916 160.209 32.6808C160.876 33.4455 161.755 33.8279 162.845 33.8279ZM171.205 29.7764C171.205 28.491 171.457 27.3683 171.961 26.4084C172.482 25.4321 173.198 24.6837 174.109 24.163C175.037 23.6261 176.094 23.3576 177.282 23.3576C178.486 23.3576 179.544 23.6017 180.455 24.0898C181.382 24.5779 182.106 25.2694 182.627 26.1643C183.164 27.0592 183.441 28.1087 183.457 29.3127C183.457 29.6381 183.432 29.9717 183.384 30.3134H173.963V30.4598C174.028 31.5499 174.37 32.4123 174.988 33.0469C175.606 33.6814 176.428 33.9987 177.453 33.9987C178.266 33.9987 178.95 33.8116 179.503 33.4374C180.056 33.0469 180.422 32.5018 180.601 31.8021H183.237C183.009 33.0713 182.391 34.1126 181.382 34.9261C180.39 35.7397 179.145 36.1464 177.648 36.1464C176.346 36.1464 175.208 35.8861 174.231 35.3654C173.271 34.8285 172.523 34.08 171.986 33.1201C171.465 32.1601 171.205 31.0455 171.205 29.7764ZM180.772 28.3853C180.658 27.4741 180.292 26.7663 179.674 26.2619C179.072 25.7413 178.307 25.4809 177.38 25.4809C176.517 25.4809 175.769 25.7494 175.134 26.2863C174.516 26.807 174.158 27.5067 174.06 28.3853H180.772ZM192.177 23.3576C193.658 23.3576 194.862 23.8132 195.79 24.7243C196.733 25.6355 197.205 27.0999 197.205 29.1175V36H194.545V29.2639C194.545 28.0761 194.293 27.1731 193.788 26.5548C193.284 25.9365 192.544 25.6274 191.567 25.6274C190.526 25.6274 189.704 25.9935 189.102 26.7257C188.516 27.4416 188.224 28.4341 188.224 29.7032V36H185.588V23.504H187.882L188.175 25.1393C189.119 23.9515 190.453 23.3576 192.177 23.3576ZM200.92 18.5008C201.376 18.5008 201.758 18.6553 202.067 18.9645C202.376 19.2574 202.531 19.6316 202.531 20.0872C202.531 20.5428 202.376 20.9251 202.067 21.2343C201.758 21.5271 201.376 21.6736 200.92 21.6736C200.465 21.6736 200.082 21.5271 199.773 21.2343C199.464 20.9251 199.309 20.5428 199.309 20.0872C199.309 19.6316 199.464 19.2574 199.773 18.9645C200.082 18.6553 200.465 18.5008 200.92 18.5008ZM199.602 23.504H202.238V36H199.602V23.504ZM208.361 29.6056L203.943 23.504H207.018L210.02 27.7263L213.071 23.504H215.951L211.509 29.6056L216.22 36H213.144L209.85 31.4605L206.53 36H203.675L208.361 29.6056Z"
                        fill="#FFFFFF"></path>
                    <path data-v-08cfe74b=""
                        d="M55.751 26.9966C55.751 29.4498 54.2628 30.9176 51.728 30.9176C49.2001 30.9176 47.7051 29.4498 47.7051 26.9966C47.7051 24.5434 49.1933 23.0756 51.728 23.0756C54.2628 23.0756 55.751 24.5434 55.751 26.9966ZM54.9287 26.9966C54.9287 25.0123 53.7327 23.8367 51.7348 23.8367C49.7369 23.8367 48.5341 25.0123 48.5341 26.9966C48.5341 28.9809 49.7302 30.1565 51.7348 30.1565C53.7327 30.1565 54.9287 28.9809 54.9287 26.9966ZM52.8697 27.88L53.5153 28.8993H52.6522L51.7688 27.4451H50.9466V28.8993H50.1447V24.9987H51.9319C52.8561 24.9987 53.3998 25.4472 53.3998 26.2355C53.3998 26.983 52.8493 27.4111 51.9319 27.4111V27.4519C52.3396 27.4519 52.693 27.6082 52.8697 27.88ZM51.8708 26.8403C52.3057 26.8403 52.5571 26.6228 52.5571 26.2491C52.5571 25.8753 52.2989 25.6579 51.8708 25.6579H50.9466V26.8335H51.8708V26.8403Z"
                        fill="#FFFFFF"></path>
                    <path data-v-08cfe74b=""
                        d="M15.0182 23.9386C14.1687 23.1163 12.9931 22.5251 11.532 22.1854L8.6983 21.4786C8.41968 21.4107 8.22261 21.1592 8.22261 20.8738V0H0V14.6695C0 18.5837 2.96286 21.798 6.75477 22.2533C7.0198 22.2873 7.25085 22.4708 7.30521 22.729C7.60422 24.1153 7.76731 25.5695 7.76731 27.0849C7.76731 28.5052 7.60422 29.8847 7.30521 31.271C7.25085 31.536 7.0198 31.7195 6.75477 31.7535C2.96286 32.2088 0 35.4231 0 39.3373V54H8.22261V33.167C8.22261 32.8747 8.42648 32.6165 8.71869 32.5554L11.5117 31.9574C12.9863 31.638 14.1619 31.0671 15.0114 30.2585C15.9016 29.409 16.3569 28.3421 16.3569 27.0849C16.3569 25.8549 15.9084 24.7948 15.0182 23.9386Z"
                        fill="#FFFFFF"></path>
                    <path data-v-08cfe74b=""
                        d="M29.1122 23.9386C29.9617 23.1163 31.1373 22.5251 32.5984 22.1854L35.4321 21.4786C35.7107 21.4107 35.9078 21.1592 35.9078 20.8738V0H44.1304V14.6695C44.1304 18.5837 41.1675 21.798 37.3756 22.2533C37.1106 22.2873 36.8795 22.4708 36.8252 22.729C36.5262 24.1153 36.3631 25.5695 36.3631 27.0849C36.3631 28.5052 36.5262 29.8847 36.8252 31.271C36.8795 31.536 37.1106 31.7195 37.3756 31.7535C41.1743 32.2088 44.1304 35.4231 44.1304 39.3373V54H35.9078V33.167C35.9078 32.8747 35.7039 32.6165 35.4117 32.5554L32.6187 31.9574C31.1441 31.638 29.9685 31.0671 29.119 30.2585C28.2288 29.409 27.7735 28.3421 27.7735 27.0849C27.7667 25.8549 28.222 24.7948 29.1122 23.9386Z"
                        fill="#FFFFFF"></path>
                </svg>
            </div>
            <div class="links-wrapper col-span-3 ml-20 px-4">
                <div class="grid grid-cols-5">
                    <div v-for="(data, index) of footerData" :key="index" class="px-4">
                        <h2 class="title">{{ data.title }}</h2>
                        <ul>
                            <li v-for="(link, index) of data.links" :key="index">
                                <a href="#">
                                    <span class="label">{{ link }}</span>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="lower-footer-wrapper flex items-center px-6 mt-20">
            <div class="first-col w-1/2 px-3">
                <span class="trademark">2024 © CampusEntri</span>
            </div>
            <div class="second-col w-1/2 px-3">
                <a href="#">
                    <span class="label">Made by CampusEntri</span>
                </a>
            </div>
        </div>
        <div class="next-page-wrapper flex items-center justify-center">
            <div class="image-wrapper">
                <img src="/images/technologies/expertise-footer-img.png" />
            </div>
            <div class="text-container">
                <NuxtLink class="next-page-btn" to="/courses">
                    <button class="big-circle-btn">
                        <span class="icon-container">
                            <IconsArrowRightBtn />
                        </span>
                    </button>
                </NuxtLink>
                <h2 class="title">Courses</h2>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
.page-footer-wrapper {
    padding-top: 3.75rem;
    background: radial-gradient(82.35% 83.58% at 95.5% 2.89%,#fa8a7d 0,#f47c6e 100%);
    overflow: hidden;
    position: relative;

    @media screen and (max-width: 768px) {
        display: flex;
        flex-direction: column;
        height: 99.9vh;
        justify-content: space-between;
        padding-top: 60px;
        margin-top: 1rem;
    }

    .main-links-container {
        .links-wrapper {
            .title {
                color: #2c2c2c;
                font-family: 'Aeonik-Medium';
                font-size: .9411764706vw;
                line-height: 1.3em;
                margin-bottom: 20px;
            }

            a {
                color: #2c2c2c;
                display: block;
                font-family: 'Aeonik-Regular';
                font-size: .875rem;
                line-height: 2.1em;
                opacity: .7;
                position: relative;
                transition: opacity 1s cubic-bezier(.19, 1, .22, 1);

                &:before {
                    color: #2c2c2c;
                    content: "—";
                    display: block;
                    left: 0;
                    position: absolute;
                    top: 0;
                    transform: scaleX(0);
                    transform-origin: left;
                    transition: transform 1s cubic-bezier(.19, 1, .22, 1);
                }

                &:hover {
                    opacity: 1;

                    &:before {
                        transform: scaleX(.8);
                    }

                    .label {
                        transform: translateX(.8em);
                    }
                }

                .label {
                    display: block;
                    position: relative;
                    transition: transform 1s cubic-bezier(.19, 1, .22, 1);
                }
            }
        }
    }

    .lower-footer-wrapper {
        @media screen and (max-width: 768px) {
            order: 2;
        }

        .first-col {
            align-items: flex-start;
            border-bottom: 1px solid rgba(44, 44, 44, .4);
            border-right: 1px solid rgba(44, 44, 44, .4);
            border-top: 1px solid rgba(44, 44, 44, .4);
            display: flex;
            flex-direction: column;
            height: 100px;
            justify-content: center;

            .trademark {
                color: #2c2c2c;
                font-family: 'Aeonik-Regular';
                font-size: 15px;
                line-height: 1.5em;
                opacity: .5;
            }
        }

        .second-col {
            align-items: center;
            border-bottom: 1px solid rgba(44, 44, 44, .4);
            border-top: 1px solid rgba(44, 44, 44, .4);
            display: flex;
            height: 100px;
            justify-content: flex-end;

            a {
                opacity: .5;
                position: relative;
                transition: opacity 1s cubic-bezier(.19, 1, .22, 1);

                &:before {
                    color: #fff;
                    content: "—";
                    display: block;
                    left: 0;
                    position: absolute;
                    top: 0;
                    transform: scaleX(0);
                    transform-origin: left;
                    transition: transform 1s cubic-bezier(.19, 1, .22, 1);
                }

                &:hover {
                    opacity: 1;

                    &:before {
                        transform: scaleX(.8);
                    }

                    .label {
                        transform: translateX(1em);
                    }
                }

                .label {
                    color: #2c2c2c;
                    display: block;
                    font-family: 'Aeonik-Regular';
                    font-size: 15px;
                    line-height: 1.5em;
                    position: relative;
                    transition: transform 1s cubic-bezier(.19, 1, .22, 1);
                }
            }
        }
    }

    .next-page-wrapper {
        height: 90vh;
        position: relative;

        .image-wrapper {
            display: block;
            height: 100%;
            left: 0;
            position: absolute;
            top: 0;
            width: 100%;

            img {
                display: block;
                height: 110%;
                margin: 0 auto;
                position: relative;
                top: -10%;
                width: auto;

                @media screen and (max-width: 768px) {
                    height: 100%;
                    max-height: none;
                    max-width: none;
                    object-fit: cover;
                    top: 0%;
                    width: 100%;
                }
            }
        }

        .text-container {
            position: relative;
            top: -1rem;
            text-align: center;
            max-width: 87.5%;

            .next-page-btn {
                display: inline-block;
                margin: 0 auto;
                position: relative;

                .big-circle-btn {
                    .icon-container {

                        svg {
                            path {
                                stroke: #E0F5DF !important;
                                margin-top: 10px;
                            }
                        }
                    }
                }
            }

            .title {
                color: #fff;
                font-family: 'Aeonik-Regular';
                font-size: 8.8235294118vw;
                letter-spacing: -.03em;
                line-height: 1em;

                @media screen and (max-width: 768px) {
                    font-size: calc(2.03125rem + 7.29167vw);
                    margin-top: 10px;
                }
            }
        }
    }
}
</style>