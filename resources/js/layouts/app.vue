<template>
    <div>
        <router-link :to="{name: 'Home'}">Home</router-link> | 
        <router-link to="/login">Login</router-link> | 
        <router-link to="/register">Register</router-link>
    </div>
    <router-view></router-view>
</template>