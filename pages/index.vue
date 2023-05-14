<template>
    <div class="w-full flex h-screen">

        <div class="w-3/12 bg-gray-100">
            <div class="relative  right-[50%] top-[30%]">
                <div class="absolute w-full bg-white rounded-xl shadow-lg py-12 px-6">
                    <form class="flex flex-col space-y-8 w-full" action="">
                        <label class="text-3xl font-bold text-emerald-700 text-center" for="">ورود</label>
                        <input class="bg-gray-100 shadow-md rounded-lg w-full p-2 " type="text" placeholder="ایمیل کاربری" name="" id="">
                        <input class="bg-gray-100 shadow-md rounded-lg w-full p-2" type="password" placeholder="رمز عبور" name="" id="">
                        <button class="bg-emerald-700 text-white p-2 rounded-xl">ورود</button>
                    </form>
                </div>
            </div>
        </div>

        <div
            class="w-11/12 rounded-r-3xl bg-gradient-to-tr from-black from-10% via-black via-30% to-green-2 to-90% flex flex-col justify-center items-center space-y-20 ">
            <img class="w-3/12" src="/img/bg.png" alt="">
            <div class="space-y-10 text-center">
                <p class="text-5xl text-white font-semibold">پنل ادمین سایت</p>
                <p class="text-xl text-emerald-500">منوآف ارائه دهنده راهکارهای هوشمند تبلیغات و مدیریت رستوران ها و کافه ها</p>
            </div>
        </div>

        
    </div>
</template>