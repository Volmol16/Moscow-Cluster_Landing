<template>
    <div
        class="flex justify-between max-md:flex-col max-md:items-start max-md:gap-y-5 max-md:px-20 items-start bg-PrimaryOrange px-10 py-16">

        <div>
            <h2 class="text-2xl text-white font-bold uppercase">Мир</h2>
            <ul class="mt-6 text-Background leading-5 max-md:text-xl">
                <li>МПК "МИР"</li>
                <li>ИНН 6164130352</li>
                <li>ОГРН 1206100001249</li>
            </ul>
            <ul class="mt-6 text-Background leading-5 max-md:text-xl">
                <p>Банк:</p>
                <li>ФИЛИАЛ "РОСТОВСКИЙ" АО "АЛЬФА-БАНК"</li>
                <li>БИК: 046015207</li>
                <li>к/с №: 30101810500000000207</li>
                <li>Счёт №: 40703810226270000043</li>
            </ul>
            <ul class="mt-6 text-Background leading-5 max-md:text-xl">
              <p>Банк:</p>
              <li>ООО "Банк Точка"</li>
              <li>БИК: 044525104</li>
              <li>к/с №: 30101810745374525104</li>
              <li>Счёт №: 40703810320000004535</li>
            </ul>
            <ul class="mt-6 text-Background leading-5 max-md:text-xl">
              <p>Банк:</p>
              <li>МОСКОВСКИЙ ФИЛИАЛ АО КБ "МОДУЛЬБАНК</li>
              <li>БИК: 044525092</li>
              <li>к/с №: 30101810645250000092</li>
              <li>Счёт №: 40703810770010004182</li>
            </ul>
            <p class="mt-6 text-Background leading-5">Адрес: 344002, Ростовская Область, г Ростов-на-дону, ул Социалистическая, зд. 69/21, офис 10</p>
        </div>

        <div>
            <h2 class="text-2xl text-white font-bold uppercase">О нас</h2>
            <ul class="mt-6 text-Background leading-5 max-md:text-xl">
                <li v-for="item in list" :key="item"><a href="#">{{ item }}</a></li>
            </ul>
        </div>

        <div>
            <h2 class="text-2xl text-white font-bold uppercase">Контакты</h2>
            <ul class="flex flex-col gap-y-4 mt-6">
                <li><a class="flex items-center gap-x-3 text-Background leading-5" href="#"><img
                            src="/image/footer/telegram.svg" alt="Telegram">https://t.me/mpkuniverse</a></li>
                <li><a class="flex items-center gap-x-3 text-Background leading-5" href="#"><img
                            src="/image/footer/Phone.svg" alt="Telephone">+79094230110</a></li>
                <li><a class="flex items-center gap-x-3 text-Background leading-5" href="#"><img
                            src="/image/footer/Letter.svg" alt="e-mail">universe.incc@gmail.com</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<script setup>
const list = ['Главная страница', 'О кооперативе', 'Стать пайщиком', 'Целевые программы', 'Кооперативные участки', 'Предложить проект', 'Контакты']
</script>