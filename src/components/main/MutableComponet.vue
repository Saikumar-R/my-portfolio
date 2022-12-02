<template>
    <div class="mutable">
        <AboutTab />
        <EducationTab />
        <ExperienceTab />
        <PersonalDetailsTab />
        <TechnicalSkillsTab />
    </div>
</template>

<script>
import AboutTab from './MutableComponents/About-Component.vue'
import EducationTab from './MutableComponents/EducationComponent.vue'
import ExperienceTab from './MutableComponents/ExperienceComponent.vue'
import PersonalDetailsTab from './MutableComponents/PersonalDetails.vue'
import TechnicalSkillsTab from './MutableComponents/TechnicalSkills.vue'
    export default {
        name:"AboutComponent",
        components:{
            AboutTab,
            EducationTab,
            ExperienceTab,
            PersonalDetailsTab,
            TechnicalSkillsTab
        },
    }
</script>

<style lang="scss" scoped>
    .mutable{
        box-shadow: inset 0 0 500px rgb(227 220 220 / 40%);
        filter: hue-rotate(45deg);
        z-index: 100;
        border-radius: 15px;
        width: 800px;
    }
</style>