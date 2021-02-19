<template>
    <div class="pt-32 container mx-auto lg:px-52">
        <div
            class="text-gray-500 text-base font-medium inline-flex items-center hover:text-green-600 mb-12"
        >
            <svg
                xmlns="http://www.w3.org/2000/svg"
                aria-hidden="true"
                data-icon="long-arrow-left"
                data-prefix="fad"
                focusable="false"
                role="img"
                viewBox="0 0 448 512"
                class="svg-inline--fa fa-long-arrow-left fa-w-14 h-5 mr-2"
            >
                <g class="fa-group">
                    <path
                        fill="currentColor"
                        d="M128.09 220H424a24 24 0 0 1 24 24v24a24 24 0 0 1-24 24H128.09l-35.66-36z"
                        opacity=".4"
                        class="fa-secondary"
                    ></path>
                    <path
                        fill="currentColor"
                        d="M142.56 409L7 273.5v-.06a25.23 25.23 0 0 1 0-34.84l.06-.06 135.5-135.49a24 24 0 0 1 33.94 0l17 17a24 24 0 0 1 0 33.94L92.43 256 193.5 358a24 24 0 0 1 0 33.94l-17 17a24 24 0 0 1-33.94.06z"
                        class="fa-primary"
                    ></path>
                </g>
            </svg>
            <p>back to blog list</p>
        </div>
        <!-- Head Post and Title -->
        <div class="mb-24">
            <h1 class="text-4xl font-semibold text-gray-600 mb-3">
                Nuxt Static Improvements
            </h1>
            <div class="flex justify-between mb-8">
                <div class="space-x-2">
                    <div class="inline-flex space-x-2 items-center">
                        <img
                            src="https://pbs.twimg.com/profile_images/1316077440414998528/mY2rcM7__400x400.jpg"
                            alt=""
                            srcset=""
                            class="h-6 w-6 rounded-full"
                        />
                        <p
                            class="text-gray-500 text-sm font-medium hover:text-green-500"
                        >
                            Alexander Lichter
                        </p>
                    </div>
                    <div class="inline-flex space-x-2 items-center">
                        <img
                            src="https://pbs.twimg.com/profile_images/1042510623962275840/1Iw_Mvud_400x400.jpg"
                            alt=""
                            srcset=""
                            class="h-6 w-6 rounded-full"
                        />
                        <p
                            class="text-gray-500 text-sm font-medium hover:text-green-500"
                        >
                            Sebasten Choopen
                        </p>
                    </div>
                    <div class="inline-flex space-x-2 items-center">
                        <img
                            src="https://pbs.twimg.com/profile_images/1268227177612541952/9-fujxqt_400x400.jpg"
                            alt=""
                            srcset=""
                            class="h-6 w-6 rounded-full"
                        />
                        <p
                            class="text-gray-500 text-sm font-medium hover:text-green-500"
                        >
                            Pooya Parsa
                        </p>
                    </div>
                </div>
                <div>
                    <p class="text-gray-500 font-medium text-sm">
                        July 27, 2020 • 5 min read
                    </p>
                </div>
            </div>
            <img
                src="https://res.cloudinary.com/nuxt/image/upload/w_800,h_450,c_fill,f_auto/remote/nuxt-org/blog/nuxt-static-improvements/main.jpg"
                alt=""
                class="w-full object-cover"
                srcset=""
            />
        </div>
        <div class="inline-flex mb-2">
            <h2 class="text-2xl font-medium text-gray-600 mb-2 borderku">
                Introduction
            </h2>
        </div>
        <div class="mb-4">
            <p class="text-base font-medium text-gray-600 leading-relaxed mb-6">
                With Nuxt.js version 2.13, the
                <span class="text-green-500">full-static mode</span> has been
                introduced. In addition, a new command
                <span class="text-red-400 bg-gray-100 px-2 rounded-lg"
                    >nuxt export</span
                >
                was added to pre-render your pages without triggering a webpack
                build with the goal to separate the rendering and build process.
                The only issue was that most Nuxt.js users weren't able to
                unleash the full potential of the separation...
                <span class="font-semibold">until now</span>.
            </p>
            <p class="text-base font-medium text-gray-600 leading-relaxed mb-6">
                With Nuxt.js version 2.13, the
                <span class="text-green-500">full-static mode</span> has been
                introduced. In addition, a new command
                <span class="text-red-400 bg-gray-100 px-2 rounded-lg"
                    >nuxt export</span
                >
                was added to pre-render your pages without triggering a webpack
                build with the goal to separate the rendering and build process.
                The only issue was that most Nuxt.js users weren't able to
                unleash the full potential of the separation...
                <span class="font-semibold">until now</span>. Lorem ipsum dolor,
                sit amet consectetur adipisicing elit. Quidem earum iure eos sit
                deleniti nulla modi consequuntur alias voluptatum, nihil in
                ullam rerum reiciendis, omnis quam debitis quisquam fuga maxime?
            </p>
            <p class="text-base font-medium text-gray-600 leading-relaxed mb-6">
                With Nuxt.js version 2.13, the
                <span class="text-green-500">full-static mode</span> has been
                introduced. In addition, a new command
                <span class="text-red-400 bg-gray-100 px-2 rounded-lg"
                    >nuxt export</span
                >
                was added to pre-render your pages without triggering a webpack
                build with the goal to separate the rendering and build process.
                The only issue was that most Nuxt.js users weren't able to
                unleash the full potential of the separation...
                <span class="font-semibold">until now</span>. Lorem ipsum dolor
                sit amet consectetur adipisicing elit. Nisi, consequuntur
                numquam reprehenderit earum alias saepe quo ipsa harum, eius
                est, sed unde commodi quae repellat assumenda repellendus
                recusandae odio magni autem nam. Illum velit et ipsam quo
                facilis provident commodi itaque laboriosam debitis dolor neque
                cupiditate nam, culpa nostrum totam incidunt voluptas. Deserunt
                rem explicabo incidunt autem molestias. Doloribus, porro!
            </p>
        </div>
        <div class="border-t border-gray-300 my-10">
            <div
                class="flex flex-row flex-wrap justify-start my-10 text-gray-400"
            >
                <span
                    class="truncate uppercase tracking-wider font-medium text-ss px-2 py-1 rounded-full mr-2 mb-2 border border-gray-300 duration-300 ease-linear"
                >
                    release </span
                ><span
                    class="truncate uppercase tracking-wider font-medium text-ss px-2 py-1 rounded-full mr-2 mb-2 border border-gray-300 duration-300 ease-linear"
                >
                    full-static </span
                ><span
                    class="truncate uppercase tracking-wider font-medium text-ss px-2 py-1 rounded-full mr-2 mb-2 border border-gray-300 duration-300 ease-linear"
                >
                    framework
                </span>
            </div>
        </div>
        <div class="flex justify-between">
            <div
                class="text-gray-500 text-base font-medium inline-flex items-center hover:text-green-600 mb-12"
            >
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    aria-hidden="true"
                    data-icon="long-arrow-left"
                    data-prefix="fad"
                    focusable="false"
                    role="img"
                    viewBox="0 0 448 512"
                    class="svg-inline--fa fa-long-arrow-left fa-w-14 h-5 mr-2"
                >
                    <g class="fa-group">
                        <path
                            fill="currentColor"
                            d="M128.09 220H424a24 24 0 0 1 24 24v24a24 24 0 0 1-24 24H128.09l-35.66-36z"
                            opacity=".4"
                            class="fa-secondary"
                        ></path>
                        <path
                            fill="currentColor"
                            d="M142.56 409L7 273.5v-.06a25.23 25.23 0 0 1 0-34.84l.06-.06 135.5-135.49a24 24 0 0 1 33.94 0l17 17a24 24 0 0 1 0 33.94L92.43 256 193.5 358a24 24 0 0 1 0 33.94l-17 17a24 24 0 0 1-33.94.06z"
                            class="fa-primary"
                        ></path>
                    </g>
                </svg>
                <p>Creating a Nuxt Module Create a Blog with Nuxt Content</p>
            </div>
            <div
                class="text-gray-500 text-base font-medium inline-flex items-center hover:text-green-600 mb-12"
            >
                <p>Create a Blog with Nuxt Content</p>
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    aria-hidden="true"
                    data-icon="long-arrow-right"
                    data-prefix="fad"
                    focusable="false"
                    role="img"
                    viewBox="0 0 448 512"
                    class="svg-inline--fa fa-long-arrow-right fa-w-14 h-5 ml-2"
                >
                    <g class="fa-group">
                        <path
                            fill="currentColor"
                            d="M319.91 292H24a24 24 0 0 1-24-24v-24a24 24 0 0 1 24-24h295.91l35.66 36z"
                            opacity=".4"
                            class="fa-secondary"
                        ></path>
                        <path
                            fill="currentColor"
                            d="M305.44 103.05L441 238.54l.06.06a25.23 25.23 0 0 1 0 34.84l-.06.06L305.44 409a24 24 0 0 1-33.94 0l-17-17a24 24 0 0 1 0-33.94L355.57 256 254.5 154a24 24 0 0 1 0-33.94l17-17a24 24 0 0 1 33.94-.01z"
                            class="fa-primary"
                        ></path>
                    </g>
                </svg>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style>
.borderku {
    display: block;
    margin-top: 5px;
    border-bottom: 5px solid #108775;
    /* border-radius: 10px; */
    /* border-bottom-left-radius: 10px; */
    /* border-bottom-right-radius: 10px; */
    width: 80%;
}
</style>
