<script setup>

</script>

<template>
  <div>
    <h1>Test and debug a WebRTC Stream Connection here.</h1>
    <h2>TODO:</h2>
    <ul>
        <li>Form to gather User Creds and Camera ID</li>
        <li>Function to login and get/show session data</li>
        <li>Get/Show the Camera Stream URL</li>
        <li>Check In on this camera</li>
        <li>Get Whitpaper and test ports and other conditions</li>
        <li>Include a video feed using the streaming URL</li>
    </ul>
  </div>
  <div>
    <h2>Get Creds and Camera</h2>
    <div>
        <lable>Username</lable>  <input :value="text" @input="event => text = event.target.value">
    </div>
    <div>
        <lable>Password</lable> .<input :value="text" @input="event => text = event.target.value">
    </div>
  </div>
</template>
