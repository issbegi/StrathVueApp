<script>
import homepage from "./homepage.vue";
import aboutus from "./aboutus.vue";
import alumni from "./alumni.vue";
import events from "./events.vue";
import contactus from "./contactus.vue";
import courses from "./courses.vue";
import library from "./library.vue";
import partnership from "./partnership.vue";
</script>
<template>
   <v-app-bar color = "white">
        <div>
            <v-btn to="/" color="Black" dark>HomePage</v-btn>
        </div>
        <div>
            <v-btn to="/aboutus" color="Black" dark>AboutUs</v-btn>
        </div>
        <div>
            <v-btn to="/alumni" color="Black" dark>Alumni</v-btn>
        </div>
        <div>
            <v-btn to="/events" color="Black" dark>Events</v-btn>
        </div>
        <div>
            <v-btn to="/contactus" color="Black" dark>ContactUs</v-btn>
        </div>
        <div>
            <v-btn to="/courses" color="Black" dark>Courses</v-btn>
        </div>
        <div>
            <v-btn to="/library" color="Black" dark>Library</v-btn>
        </div>
        <div>
            <v-btn to="/partnership" color="Black" dark>Partnership</v-btn>
        </div>
    </v-app-bar>
</template>