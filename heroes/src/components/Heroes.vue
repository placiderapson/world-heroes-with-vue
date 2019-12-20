<template>
    <div class="heroes-wrapper">
        <ol class="heroes-wrapper__list">
            <li @click="displayBackground('one')">{{ heroes[0].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--one">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[0].nameAndLifeTime }}</strong> {{ heroes[0].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('one')">Hide</button>
                </div>
            <li @click="displayBackground('two')">{{ heroes[1].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--two">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[1].nameAndLifeTime }}</strong> {{ heroes[1].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('two')">Hide</button>
                </div>
            <li @click="displayBackground('three')">{{ heroes[2].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--three">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[2].nameAndLifeTime }}</strong> {{ heroes[2].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('three')">Hide</button>
                </div>
            <li @click="displayBackground('four')">{{ heroes[3].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--four">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[3].nameAndLifeTime }}</strong> {{ heroes[3].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('four')">Hide</button>
                </div>
            <li @click="displayBackground('five')">{{ heroes[4].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--five">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[4].nameAndLifeTime }}</strong> {{ heroes[4].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('five')">Hide</button>
                </div>
            <li @click="displayBackground('six')">{{ heroes[5].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--six">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[5].nameAndLifeTime }}</strong> {{ heroes[5].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('six')">Hide</button>
                </div>
            <li @click="displayBackground('seven')">{{ heroes[6].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--seven">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[6].nameAndLifeTime }}</strong> {{ heroes[6].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('seven')">Hide</button>
                </div>
            <li @click="displayBackground('eight')">{{ heroes[7].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--eight">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[8].nameAndLifeTime }}</strong> {{ heroes[7].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('eight')">Hide</button>
                </div>
            <li @click="displayBackground('nine')">{{ heroes[8].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--nine">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[8].nameAndLifeTime }}</strong> {{ heroes[8].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('nine')">Hide</button>
                </div>
            <li @click="displayBackground('ten')">{{ heroes[9].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--ten">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[9].nameAndLifeTime }}</strong> {{ heroes[9].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('ten')">Hide</button>
                </div>
            <li @click="displayBackground('eleven')">{{ heroes[10].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--eleven">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[10].nameAndLifeTime }}</strong> {{ heroes[10].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('eleven')">Hide</button>
                </div>
            <li @click="displayBackground('twelve')">{{ heroes[11].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twelve">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[11].nameAndLifeTime }}</strong> {{ heroes[11].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twelve')">Hide</button>
                </div>
            <li @click="displayBackground('thirteen')">{{ heroes[12].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--thirteen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[12].nameAndLifeTime }}</strong> {{ heroes[12].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('thirteen')">Hide</button>
                </div>
            <li @click="displayBackground('fourteen')">{{ heroes[13].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--fourteen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[13].nameAndLifeTime }}</strong> {{ heroes[13].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('fourteen')">Hide</button>
                </div>
            <li @click="displayBackground('fifteen')">{{ heroes[14].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--fifteen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[14].nameAndLifeTime }}</strong> {{ heroes[14].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('fifteen')">Hide</button>
                </div>
            <li @click="displayBackground('sixteen')">{{ heroes[15].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--sixteen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[15].nameAndLifeTime }}</strong> {{ heroes[15].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('sixteen')">Hide</button>
                </div>
            <li @click="displayBackground('seventeen')">{{ heroes[16].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--seventeen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[16].nameAndLifeTime }}</strong> {{ heroes[16].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('seventeen')">Hide</button>
                </div>
            <li @click="displayBackground('eighteen')">{{ heroes[17].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--eighteen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[17].nameAndLifeTime }}</strong> {{ heroes[17].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('eighteen')">Hide</button>
                </div>
            <li @click="displayBackground('nineteen')">{{ heroes[18].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--nineteen">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[18].nameAndLifeTime }}</strong> {{ heroes[18].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('nineteen')">Hide</button>
                </div>
            <li @click="displayBackground('twenty')">{{ heroes[19].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[19].nameAndLifeTime }}</strong> {{ heroes[19].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-one')">{{ heroes[20].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-one">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[20].nameAndLifeTime }}</strong> {{ heroes[20].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-one')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-two')">{{ heroes[21].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-two">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[21].nameAndLifeTime }}</strong> {{ heroes[21].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-two')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-three')">{{ heroes[22].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-three">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[22].nameAndLifeTime }}</strong> {{ heroes[22].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-three')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-four')">{{ heroes[23].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-four">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[23].nameAndLifeTime }}</strong> {{ heroes[23].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-four')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-five')">{{ heroes[24].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-five">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[24].nameAndLifeTime }}</strong> {{ heroes[24].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-five')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-six')">{{ heroes[25].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-six">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[25].nameAndLifeTime }}</strong> {{ heroes[25].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-six')">Hide</button>
                </div>
            <li @click="displayBackground('twenty-seven')">{{ heroes[26].fullName }}</li>
                <div class="heroes-wrapper__bg-wrapper heroes-wrapper__bg-wrapper--twenty-seven">
                    <h5 class="heroes-wrapper__bg-title">Background</h5>
                    <p class="heroes-wrapper__bg-detail">
                        <strong>{{ heroes[26].nameAndLifeTime }}</strong> {{ heroes[26].background }}
                    </p>
                    <button class="heroes-wrapper__bg-btn" @click="hideBackground('twenty-seven')">Hide</button>
                </div>
        </ol>
    </div>
</template>

<script>
export default {
    name: 'Heroes',
    data() {
        return {
            heroes: [
                {
                    fullName: 'Abraham Lincoln',
                    nameAndLifeTime: 'Abraham Lincoln (February 12, 1809 – April 15, 1865)',
                    background: 'was the 16th President of the United States, serving from March 1861 until his assassination in April 1865. Lincoln led the United States through its greatest constitutional, military, and moral crises—the American Civil War—preserving the Union, abolishing slavery, strengthening the national government and modernizing the economy. Reared in a poor family on the western frontier, Lincoln was self-educated, and became a country lawyer, a Whig Party leader, Illinois state legislator during the 1830s, and a one-term member of the United States House of Representatives during the 1840s.'
                },
                {
                    fullName: 'Nelson Mandela',
                    nameAndLifeTime: 'Nelson Rolihlahla Mandela born 18 July 1918',
                    background: 'is a South African politician who was the President of South Africa from 1994 to 1999, the first ever to be elected in a fully representative and multi-racial election. His administration focused on dismantling the legacy of apartheid, as well as tackling racism, poverty and inequality.'
                },
                {
                    fullName: 'Leonardo Da Vinci',
                    nameAndLifeTime: 'Leonardo di ser Piero da Vinci (April 15, 1452 – May 2, 1519, Old Style)',
                    background: 'was an Italian Renaissance polymath: painter, sculptor, architect, musician, mathematician, engineer, inventor, anatomist, geologist, cartographer, botanist, and writer. His genius, perhaps more than that of any other figure, epitomized the Renaissance humanist ideal.'
                },
                {
                    fullName: 'Martin Luther King Jr.',
                    nameAndLifeTime: 'Martin Luther King, Jr. (January 15, 1929 – April 4, 1968)',
                    background: 'was an American clergyman, activist, and leader in the African-American Civil Rights Movement. He is best known for his role in the advancement of civil rights using nonviolent civil disobedience.'
                },
                {
                    fullName: 'Mahatma Gandhi',
                    nameAndLifeTime: 'Mohandas Karamchand Gandhi 2 October 1869 – 30 January 1948)',
                    background: ', commonly known as Mahatma Gandhi, was the preeminent leader of Indian nationalism in British-ruled India. Employing non-violent civil disobedience, Gandhi led India to independence and inspired movements for non-violence, civil rights and freedom across the world.'
                },
                {
                    fullName: 'William Shakespeare',
                    nameAndLifeTime: 'William Shakespeare (26 April 1564 (baptised) – 23 April 1616)',
                    background: 'was an English poet and playwright, widely regarded as the greatest writer in the English language and the world\'s pre-eminent dramatist. He is often called England\'s national poet and the "Bard of Avon".'
                },
                {
                    fullName: 'George Washington',
                    nameAndLifeTime: 'George Washington (February 22, 1732 [O.S. February 11, 1731] – December 14, 1799)',
                    background: 'was one of the Founding Fathers of the United States, serving as the commander-in-chief of the Continental Army during the American Revolutionary War.'
                },
                {
                    fullName: 'Isaac Newton',
                    nameAndLifeTime: 'Sir Isaac Newton PRS MP (25 December 1642 – 20 March 1727)',
                    background: 'was an English physicist and mathematician who is widely regarded as one of the most influential scientists of all time and as a key figure in the scientific revolution. His book Philosophiæ Naturalis Principia Mathematica ("Mathematical Principles of Natural Philosophy"), first published in 1687, laid the foundations for most of classical mechanics.'
                },
                {
                    fullName: 'Alexander the Great',
                    nameAndLifeTime: 'Alexander III of Macedon (20/21 July 356 – 10/11 June 323 BC)',
                    background: ', commonly known as Alexander the Great was a king of Macedon, a state in northern ancient Greece. Born in Pella in 356 BC, Alexander was tutored by Aristotle until the age of 16. By the age of thirty, he had created one of the largest empires of the ancient world, stretching from the Ionian Sea to the Himalayas.'
                },
                {
                    fullName: 'Queen Elizabeth I',
                    nameAndLifeTime: 'Elizabeth I (7 September 1533 – 24 March 1603)',
                    background: 'was queen of England and Ireland from 17 November 1558 until her death. Sometimes called "The Virgin Queen", "Gloriana" or "Good Queen Bess", Elizabeth was the fifth and last monarch of the Tudor dynasty.'
                },
                {
                    fullName: 'Benjamin Franklin',
                    nameAndLifeTime: 'Benjamin Franklin (January 17, 1706 [O.S. January 6, 1705] – April 17, 1790)',
                    background: 'was one of the Founding Fathers of the United States.'
                },
                {
                    fullName: 'Michelangelo',
                    nameAndLifeTime: 'Michelangelo di Lodovico Buonarroti Simoni (6 March 1475 – 18 February 1564)',
                    background: ', commonly known as Michelangelo was an Italian sculptor, painter, architect, poet, and engineer of the High Renaissance who exerted an unparalleled influence on the development of Western art.'
                },
                {
                    fullName: 'Helen Keller',
                    nameAndLifeTime: 'Helen Adams Keller (June 27, 1880 – June 1, 1968)',
                    background: 'was an American author, political activist, and lecturer. She was the first deafblind person to earn a Bachelor of Arts degree.'
                },
                {
                    fullName: 'Ludwig van Beethoven',
                    nameAndLifeTime: 'Ludwig van Beethoven (17 December 1770 – 26 March 1827)',
                    background: 'was a German composer and pianist. A crucial figure in the transition between the Classical and Romantic eras in Western art music, he remains one of the most famous and influential of all composers.'
                },
                {
                    fullName: 'Walt Disney',
                    nameAndLifeTime: 'Walter Elias "Walt" Disney (December 5, 1901 – December 15, 1966)',
                    background: 'was an American business magnate, animator, cartoonist, producer, director, screenwriter, entrepreneur, and voice actor. A major figure within the American animation industry and throughout the world, he is regarded as an international icon, and philanthropist, well known for his influence and contributions to the field of entertainment during the 20th century.'
                },
                {
                    fullName: 'Wright brothers',
                    nameAndLifeTime: 'The Wright brothers, Orville (August 19, 1871 – January 30, 1948) and Wilbur (April 16, 1867 – May 30, 1912)',
                    background: ', were two American brothers, inventors, and aviation pioneers who were credited with inventing and building the world\'s first successful airplane and making the first controlled, powered and sustained heavier-than-air human flight, on December 17, 1903. In the two years afterward, the brothers developed their flying machine into the first practical fixed-wing aircraft. Although not the first to build and fly experimental aircraft, the Wright brothers were the first to invent aircraft controls that made fixed-wing powered flight possible.'
                },
                {
                    fullName: 'Franklin D. Roosevelt',
                    nameAndLifeTime: 'Franklin Delano Roosevelt; January 30, 1882 – April 12, 1945)',
                    background: ', commonly known by his initials, FDR, 32nd President of the United States (1933–1945), served for 12 years and four terms until his death in 1945, the only president ever to do so, and a central figure in world events during the mid-20th century, leading the United States during a time of worldwide economic depression and total war.'
                },
                {
                    fullName: 'Charles Darwin',
                    nameAndLifeTime: 'Charles Robert Darwin, FRS (12 February 1809 – 19 April 1882)',
                    background: 'was an English naturalist. He established that all species of life have descended over time from common ancestors, and proposed the scientific theory that this branching pattern of evolution resulted from a process that he called natural selection, in which the struggle for existence has a similar effect to the artificial selection involved in selective breeding.'
                },
                {
                    fullName: 'Albert Einstein',
                    nameAndLifeTime: 'Albert Einstein (14 March 1879 – 18 April 1955)',
                    background: 'was a German-born theoretical physicist who developed the general theory of relativity, one of the two pillars of modern physics (alongside quantum mechanics). While best known for his mass–energy equivalence formula E = mc2 (which has been dubbed "the world\'s most famous equation"), he received the 1921 Nobel Prize in Physics "for his services to theoretical physics, and especially for his discovery of the law of the photoelectric effect".'
                },
                {
                    fullName: 'Thomas Jefferson',
                    nameAndLifeTime: 'Thomas Jefferson (April 13, 1743 (April 2, 1743 O.S.) – July 4, 1826)',
                    background: 'was an American Founding Father, the principal author of the Declaration of Independence (1776) and the third President of the United States (1801–1809). At the beginning of the American Revolution, he served in the Continental Congress, representing Virginia and then served as a wartime Governor of Virginia (1779–1781).'
                },
                {
                    fullName: 'Jackie Robinson',
                    nameAndLifeTime: 'Jack Roosevelt "Jackie" Robinson (January 31, 1919 – October 24, 1972)',
                    background: 'was an American baseball player who became the first African American to play in Major League Baseball (MLB) in the modern era. Robinson broke the baseball color line when the Brooklyn Dodgers started him at first base on April 15, 1947. As the first major league team to play a black man since the 1880s, the Dodgers ended racial segregation that had relegated black players to the Negro leagues for six decades.'
                },
                {
                    fullName: 'Harriet Tubman',
                    nameAndLifeTime: 'Harriet Tubman (born Araminta Harriet Ross; 1820 – March 10, 1913)',
                    background: 'was an African-American abolitionist, humanitarian, and Union spy during the American Civil War. Born into slavery, Tubman escaped and subsequently made more than thirteen missions to rescue more than 70 slaves using the network of antislavery activists and safe houses known as the Underground Railroad.'
                },
                {
                    fullName: 'Galileo Galilei',
                    nameAndLifeTime: 'Galileo Galilei (15 February 1564 – 8 January 1642)',
                    background: ', often known mononymously as Galileo, was an Italian physicist, mathematician, engineer, astronomer, and philosopher who played a major role in the scientific revolution. His achievements include improvements to the telescope and consequent astronomical observations and support for Copernicanism.'
                },
                {
                    fullName: 'Rosa Parks',
                    nameAndLifeTime: 'Rosa Louise McCauley Parks (February 4, 1913 – October 24, 2005)',
                    background: 'was an African-American civil rights activist, whom the U.S. Congress called "the first lady of civil rights" and "the mother of the freedom movement".'
                },
                {
                    fullName: 'Neil Armstrong',
                    nameAndLifeTime: 'Neil Alden Armstrong (August 5, 1930 – August 25, 2012)',
                    background: 'was an American astronaut and the first person to walk on the Moon. He was also an aerospace engineer, naval aviator, test pilot, and university professor.'
                },
                {
                    fullName: 'Napoleon Bonaparte',
                    nameAndLifeTime: 'Napoleon Bonaparte,(15 August 1769 – 5 May 1821)',
                    background: 'was a French military and political leader who rose to prominence during the latter stages of the French Revolution and its associated wars in Europe.'
                },
                {
                    fullName: 'Spartacus',
                    nameAndLifeTime: 'Spartacus (c. 109–71 BC)',
                    background: 'was a Thracian gladiator, who along with the Gauls Crixus and Oenomaus, a Roman Castus, and a Celt Gannicus, was one of the slave leaders in the Third Servile War, a major slave uprising against the Roman Republic.'
                }
            ]
        }
    },
    methods: {
        displayBackground(heroe) {
            const background = document.querySelector(`.heroes-wrapper__bg-wrapper--${heroe}`);
            background.style.display = 'block';
        },

        hideBackground(heroe) {
            const background = document.querySelector(`.heroes-wrapper__bg-wrapper--${heroe}`);
            background.style.display = 'none';
        }
    },
}
</script>

<style lang="scss" scoped>
    .heroes-wrapper {
        width: 60%;
        margin: 0 auto;
        
        &__list {
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
            display: none;
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