<template>
  <div class="outer-wrapper">
    <div class="wrapper">
      <div class="avatar">
        <img src="./assets/images/avatar-jessica.jpeg" />
      </div>
      <div class="name">Jessica Randall</div>
      <div class="location">London, United Kingdom</div>
      <div class="quote">"Front-end developer and avid reader."</div>
      <div class="buttons">
        <a>GitHub</a>
        <a>Frontend Mentor</a>
        <a>LinkedIn</a>
        <a>Twitter</a>
        <a>Instagram</a>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style>
.outer-wrapper {
  padding-top: 40px;
}

.wrapper {
  margin: auto;
  width: 375px;
  border-radius: 10px;
  text-align: center;
  background-color: hsl(0, 0%, 12%);
}

.avatar img {
  margin-top: 35px;
  border-radius: 50%;
  width: 90px;
}

.name {
  font-weight: 600;
  margin-top: 1.125em;
  font-size: 1.5rem;
}

.location {
  margin-top: 0.75em;
  margin-bottom: 2em;
  color: hsl(75, 94%, 57%);
  font-weight: 600;
}

.buttons {
  margin-top: 1.75em;
  display: flex;
  flex-direction: column;
  gap: 20px;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 20px;
}

.buttons a {
  font-weight: 600;
  width: full;
  text-align: center;
  padding: 13px 0;
  border-radius: 7px;
  background-color: hsl(0, 0%, 20%);
}
.buttons a:hover {
  background-color: hsl(75, 94%, 57%);
  cursor: pointer;
  color: hsl(0, 0%, 12%);
}
</style>
