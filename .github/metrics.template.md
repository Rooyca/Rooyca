<p align="center">
    <!-- <img src="https://avatars.githubusercontent.com/u/56601352" width="192" alt="hyro's pfp" /> -->
    <h1 align="center">Hi, my name is {{ LOGIN }} 👋</h1>
</p>


___
**Data**

<%- await embed(`base`, {base:"activity, community, repositories"}) %>

___

<%- await include(`partials/activity.ejs`) %>

___

<%- await embed(`isocalendar`, {isocalendar:true, isocalendar_duration:"half-year", config_display:"large"}) %>

___

<%- await embed(`languages`, {languages:true, languages_details:"percentage, bytes-size", config_display:"large"}) %>

___

<%- await embed(`achievements`, { achievements: true, achievements_secrets: true, achievements_threshold: "C" }) %>

___
