<template>
    <form>
        <label>Username: </label>
        <input type="username" id="username" name="username" placeholder="Enter your username"> <br><br>
        <label>Password: </label>
        <input type="password" id="password" name="password" placeholder="Enter your password"><br><br>
        <input type="submit" name="login" value="Log in">
    </form>
    <p> New member? Please <router-link to="/signin">CLICK ME </router-link></p>
</template>