<template>
    <div>
        <Content v-for="pageItem in pageList" :key="'pageList-'+pageItem.title" :title="pageItem.title" :timestamp="pageItem.timestamp" :desc="pageItem.desc" :avatar="pageItem.avatar" />
    </div>
</template>

<script>
import Content from './Content.vue';

    export default {
        name: 'Header',
        components: {
            Content
            },
            data(){
                return{
                    pageList: [
                        {
                            title:'“We Keep Us Safe” Community Call Video',
                            timestamp: 'January 18, 2021',
                            desc: 'As MLK famously said, “Darkness cannot drive out darkness; only light can do that. Hate cannot drive out hate; only love can do that.” On Monday, Black Lives Matter Global Network will launch its newest arts and culture endeavor centering life, love, joy, rest, and pleasure…',
                            avatar: ''
                        },
                        {
                            title:'Black Lives Matter Global Network Launches New MLK Artist Series',
                            timestamp: 'January 18, 2021',
                            desc: 'Watch the #BlackLivesMatter “We Keep Us Safe” community call. Movement elders and BLM leaders (Patrisse Cullors and Melina Abdullah) share critical safety tips and resources to remember and utilize for the 2021 inauguration and after…'
                        },
                        {
                            title:'MLK’s Dream. Our Fight.',
                            timestamp: 'January 19, 2021',
                            desc: 'Today, as we honor the life and legacy of Dr. Martin Luther King Jr. (who was born on January 15th, 1929), we are still carrying so much of our own pain and grief…'
                        },
                        {
                            title:'We Keep Us Safe Convo',
                            timestamp: 'January 18, 2021',
                            desc: 'A conversation between Melina Abdullah, Co-Founder of Black Lives Matter – Los Angeles, and Patrisse Cullors, Co-Founder and Executive Director of Black Lives Matter Global Network Foundation…'
                        },
                        {
                            title:'Our Six Demands for Accountability for This Moment',
                            timestamp: 'January 16, 2021',
                            desc: 'January 6th was another dark day in America. People across the country — and the world — watched as white supremacists, incited by the white supremacist-in-chief, Donald Trump, carried out an attack inside our nation’s Capitol…'
                        },
                        {
                            title:'Black Lives Matters Global Network Foundation Statement About President Trump’s Impeachment',
                            timestamp: 'January 13, 2021',
                            desc: 'Patrisse Cullors, Co-Founder and Executive Director of Black Lives Matter Global Network Foundation (BLMGNF), released the following statement in response to the U.S. House of Representatives vote today to impeach President Trump…'
                        }
                    ]
                }
            }
    }
</script>

<style scoped>

</style>