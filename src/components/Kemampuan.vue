<script setup>
    import WelcomeItem from './WelcomeItem.vue'
    import DocumentationIcon from './icons/IconDocumentation.vue'
    import ToolingIcon from './icons/IconTooling.vue'
    import EcosystemIcon from './icons/IconEcosystem.vue'
    import CommunityIcon from './icons/IconCommunity.vue'
    import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
    <div class="ability mb-5">
        <h5>HTML, CSS</h5>
        <div class="progress mb-3">
            <div class="progress-bar bg-warning" role="progressbar" style="width: 85%" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100"></div>
        </div>
        <h5>User Interface Design</h5>
        <div class="progress mb-3">
            <div class="progress-bar bg-warning" role="progressbar" style="width: 80%" aria-valuenow="50" aria-valuemin="0"
                aria-valuemax="100"></div>
        </div>
        <h5>User Experience</h5>
        <div class="progress mb-3">
            <div class="progress-bar bg-warning" role="progressbar" style="width: 55%" aria-valuenow="75"
                aria-valuemin="0" aria-valuemax="100"></div>
        </div>
        <h5>Javascript</h5>
        <div class="progress">
            <div class="progress-bar bg-warning" role="progressbar" style="width: 10%" aria-valuenow="100"
                aria-valuemin="0" aria-valuemax="100"></div>
        </div>
    </div>
</template>