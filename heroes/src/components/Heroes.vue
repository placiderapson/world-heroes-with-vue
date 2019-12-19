<template>
    <div class="heroes-wrapper">
        <ol class="heroes-wrapper__list">
            <li>Abraham Lincoln</li>
                <div class="heroes-wrapper__bg-wrapper">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>Abraham Lincoln (February 12, 1809 – April 15, 1865)</strong> was the 16th President of the United States, serving from March 1861 until his assassination in April 1865. Lincoln led the United States through its greatest constitutional, military, and moral crises—the American Civil War—preserving the Union, abolishing slavery, strengthening the national government and modernizing the economy. Reared in a poor family on the western frontier, Lincoln was self-educated, and became a country lawyer, a Whig Party leader, Illinois state legislator during the 1830s, and a one-term member of the United States House of Representatives during the 1840s.
                    </p>
                    <button class="heroes-wrapper__bg-btn">Hide</button>
                </div>
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
    .heroes-wrapper {
        width: 60%;
        margin: 0 auto;
        
        &__list {
            list-style: none;
            
            li {
                font-weight: bold;
                font-size: 1.2rem;
                border-bottom: solid #E9F0F2;
                margin-bottom: 1.2rem;
            }

            li:hover {
                cursor: pointer;
            }
        }

        &__bg-wrapper {
            margin: 1.5rem 0;
            background: #E9F0F2;
            padding: 0.8rem;
        }

        &__bg-title {
            text-transform: uppercase;
        }

        &__bg-detail {
            font-size: 0.9rem;
        }

        &__bg-btn {
            font-size: 0.65rem;
            text-transform: uppercase;
        }
    }
</style>