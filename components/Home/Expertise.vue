<script>
export default {
    data() {
        return {
            expertise: [
                { id: '01', name: 'MBBS' },
                { id: '02', name: 'Bachelor Dental Sciences' },
                { id: '03', name: 'Bachelor of Nursing' },
                { id: '04', name: 'Bachelor of Physiotherapy' },
                { id: '05', name: 'Bachelor of Audiology & Speech' },
                { id: '06', name: 'Bachelor of Medical Imaging Technology' },
            ]
        };
    }
};
</script>

<template>
    <section id="expertise" class="expertise-container relative z-20">
        <div class="h-full absolute left-0 top-0 w-full hidden md:block">
            <img class="absolute right-[12%] top-[5%] w-48" src="@/assets/imgs/expertise/expertise-1.jpg" />
            <img class="absolute right-0 top-[40%] w-48" src="@/assets/imgs/expertise/expertise-2.jpg" />
            <img class="absolute left-[10%] top-[70%] w-52" src="@/assets/imgs/expertise/expertise-3.jpg" />
            <img class="absolute right-1/4 top-[80%] w-40" src="@/assets/imgs/expertise/expertise-4.jpg" />
            <img class="absolute right-0 top-[-7%] w-40" src="@/assets/imgs/expertise/expertise-5.jpg" />
        </div>
        <div class="flex mx-auto px-12">
            <h1 class="w-1/2 ml-[15.75%] text-white">Transforming Discoveries</h1>
        </div>
        <div class="bio-list-container z-50 relative flex flex-col md:flex-row px-6 md:px-12 mt-12 md:mt-20 text-white">
            <div class="flex mx-auto w-full md:w-1/4 ml-0 md:ml-[15.75%]">
                <div>
                    <span class="subtitle flex gap-3 items-center">
                        <span>Our Bio</span>
                        <span class="line"></span>
                    </span>
                    <p class="mt-3">Our expertised, counseling and guidance teams have the experience needed to propel
                        students
                        towards novel educational discoveries and the development of personalized academic paths.
                    </p>
                </div>
            </div>
            <div class="flex mr-auto mt-8 md:mt-0 w-full md:w-[31.25%] ml-0 md:ml-[0.25%]">
                <div>
                    <span class="subtitle flex gap-3 items-center">
                        <span>Expertise</span>
                        <span class="line"></span>
                    </span>
                    <ul class="mt-3">
                        <li class="list" v-for="item in expertise" :key="item.id">
                            <span class="flex text-base mb-1 items-center justify-between cursor-pointer">
                                <span class="grow-0">{{ item.id }}</span>
                                <span class="label text-start grow mx-3 font-semibold">{{ item.name }}</span>
                                <IconsArrowRight />
                            </span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.expertise-container {
    padding: 7.5rem 0 25rem;

    @media screen and (max-width: 768px) {
        padding: 3rem 1rem;

        h1 {
            font-size: calc(1.79688rem + 5.10417vw);
            margin-left: 0;
        }
    }

    .line {
        background-color: #fff;
        display: block;
        flex-grow: 1;
        height: 1px;
        position: relative;
    }

    .list {
        &:hover {
            .label {
                transform: translateX(4px);
                opacity: 0.7;
            }
        }
        .label {
            flex-grow: 1;
            transition: transform .5s cubic-bezier(.19,1,.22,1), opacity .5s cubic-bezier(.19,1,.22,1);
        }
    }
}
</style>