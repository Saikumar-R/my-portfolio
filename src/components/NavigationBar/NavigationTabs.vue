<template>
    <div class="tabs">
        <h3>
            <a href="#AboutTab" @click="alertFunction">About</a>
        </h3>
        <h3>
            <a href="#TechnicalSkillsTab" @click="alertFunction">Technical Skills</a>
        </h3>
        <h3>
            <a href="#ExperienceTab" @click="alertFunction">Experience</a>
        </h3>
        <h3>
            <a href="#EducationTab" @click="alertFunction">Education</a>
        </h3>
        <h3>
            <a href="#PersonalDetailsTab" @click="alertFunction">Personal Details</a>
        </h3>
    </div>
</template>

<script>
    export default {
        name:"NavigationTabs",
    }
</script>

<style lang="scss" scoped>
    .tabs{
        margin-top: 55px;
        h3{
            display: inline;
            margin: 0 35px;
            padding: 15px 0px;
            a{
                text-decoration: none;
                color: whitesmoke;
                &:hover{
                    text-decoration: underline;
                }
            }
        }
    }
</style>