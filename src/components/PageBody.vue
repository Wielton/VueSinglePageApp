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
    #bodydiv {
        color: rgb(253, 241, 226);
        background-color: bisque;
    }
    #leagueStandings {
        grid-column: 1 / 2;
    }
    #draftList {
        grid-column: 3 / 4;
    }
    #leagueMenu {
        grid-column: 1 / 4;
        grid-row: 2 / 3;
    }
</style>