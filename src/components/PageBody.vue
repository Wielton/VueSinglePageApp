<template>
    <div id="bodydiv">
        <LeagueStandings/>
        <DraftList/>
        <LeagueMenu/>
    </div>
</template>

<script>
import LeagueStandings from './LeagueStandings.vue';
import DraftList from './DraftList.vue';
import LeagueMenu from './LeagueMenu.vue';
    export default {
        name: 'PageBody',
        components : {
                LeagueStandings,
                DraftList,
                LeagueMenu
                }
        }
</script>

<style scoped>
    #leagueStandings {
        height: 90%;
    }
</style>