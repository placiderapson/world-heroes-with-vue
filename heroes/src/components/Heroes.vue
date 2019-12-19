<template>
    <div id="heroes-wrapper">
        <ol id="heroes-wrapper__list">
            <li>Abraham Lincoln</li>
            <li>Nelson Mandela</li>
            <li>Leonardo Da Vinci</li>
            <li>Martin Luther King Jr.</li>
            <li>Mahatma Gandhi</li>
            <li>William Shakespeare</li>
            <li>George Washington</li>
            <li>Isaac Newton</li>
            <li>Alexander the Great</li>
            <li>Queen Elizabeth I</li>
            <li>Benjamin Franklin</li>
            <li>Michelangelo</li>
            <li>Helen Keller</li>
            <li>Ludwig van Beethoven</li>
            <li>Walt Disney</li>
            <li>Wright brothers</li>
            <li>Franklin D. Roosevelt</li>
            <li>Charles Darwin</li>
            <li>Albert Einstein</li>
            <li>Thomas Jefferson</li>
            <li>Jackie Robinson</li>
            <li>Harriet Tubman</li>
            <li>Galileo Galilei</li>
            <li>Rosa Parks</li>
            <li>Neil Armstrong</li>
            <li>Napoleon Bonaparte</li>
            <li>Spartacus</li>
        </ol>
    </div>
</template>

<script>
export default {
    name: 'Heroes'
}
</script>

<style lang="scss" scoped>
    #heroes-wrapper {
        border: solid 0.4rem #41B883;
        &__list {
            list-style: none;

            li {
                font-weight: bold;
                font-size: 1rem;
            }
        }
    }
</style>