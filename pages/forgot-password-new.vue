<template>
    <div>
        <Head>
            <Title>Forgot password new | Inventory Ahead Dashboard</Title>
            <Meta name="description" content="Inventory Ahead Dashboard" />
        </Head>
        <div class="grid grid-cols-12">
            <div class="col-span-6 ">
                <div class="col-start-2 col-span-4 slider-bg">
                    <LoginSlider />
                </div>
            </div>

            <div class="login-form col-span-6">
                <div class="bg-white ">
                    <div class="xl:container mx-auto grid grid-cols-6">

                        <div class="col-start-2 col-span-4">
                            <div class="w-full max-w-md ">
                                <div class="flex flex-col justify-between min-h-screen h-full py-20">
                                    <NuxtLink to="/" class="site-logo">
                                        <img class="max-w-[160px] w-full" src="../assets/img/login-2-logo.svg"
                                            alt="Company logo" />
                                    </NuxtLink>

                                    <div class="">
                                        <h2 class="text-4xl font-bold tracking-tight text-dark1">Forgot Password?</h2>
                                        <p class="text-sm text-dark2 font-medium mt-4">Enter Email to reset password.</p>
                                        <form class="mt-8 space-y-6" action="#" method="POST">
                                            <input type="hidden" name="remember" value="true" />
                                            <div class="-space-y-px rounded-md gap-6 grid">
                                                <label for="email-address"
                                                    class="text-base font-medium text-dark1 pb-2.5 inline-block">Email</label>
                                                <input id="email-address" name="email" type="email" autocomplete="email"
                                                    required=""
                                                    class="relative block w-full appearance-none rounded-lg border-2 border-dark5 px-3 py-2 text-dark1 placeholder-dark4 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-indigo-500 font-medium" placeholder="Email address" />
                                            </div>

                                            <NuxtLink to="/login-new">
                                                <button type="submit"
                                                    class="group relative flex w-full justify-center rounded-md bg-main_purple text-lg py-2 px-4 font-semibold text-white hover:bg-indigo-700 focus:outline-none mt-7">
                                                    Reset
                                                </button>
                                            </NuxtLink>
                                        </form>
                                    </div>

                                    <div class="">
                                        <p class="mt-12 font-medium text-dark2">
                                        Don't have an account yet ? <NuxtLink class="text-main_purple" to="/registration-new">Create an account</NuxtLink>
                                    </p></div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>