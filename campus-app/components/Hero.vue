<template>
    <div class="hero">
    <v-container>
        <div class="hero_top">
            <div class="hero_top_wrapper">
                <v-icon icon="mdi-arrow-left-thin-circle-outline" class="hero_top_wrapper_icon"></v-icon>
                <v-divider vertical></v-divider>
                <v-breadcrumbs class="hero_top_wrapper_nav" :items="['Launched', 'Details', 'Project', '1']"></v-breadcrumbs>
                <a href="#" class="hero_top_wrapper_link">Open Campus</a></div>
            </div>
            <div class="hero_bottom">
            <div class="hero_bottom_bcg"></div>
             <div class="hero_bottom_wrapper">
                <h1 class="title hero_bottom_wrapper_title">Open Campus</h1>
                <v-btn color="#2196F3" style="color: white">
                Pending
                </v-btn>
             </div>
        </div>
       </v-container>
    </div>
</template>