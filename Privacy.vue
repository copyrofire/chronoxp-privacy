<template>
    <q-page padding class="q-pa-md">
        <h1 class="text-primary">Privacy Policy – ChronoXP</h1>
        <p>
            Akironex only uses the <strong>software and hardware functionality integrated into the app</strong> to
            operate as intended.
        </p>

        <h2 class="text-primary">Important information regarding data collection and usage:</h2>
        <ul class="text-primary">
            <li><strong>No data collection:</strong> The app does not collect any personal data from users.</li>
            <li><strong>No data transmission:</strong> No data is sent to third parties, except for the optional use of
                <strong>Google Drive</strong>, if explicitly enabled by the user.
            </li>
            <li><strong>Local storage:</strong> All data created or stored in the app remains exclusively on the device.
            </li>
            <li><strong>Push notifications:</strong> If the app uses push notifications, they are solely for app
                functionality. No advertising IDs or tracking information is collected.</li>
            <li><strong>No advertising or tracking:</strong> The app contains no ads and does not use user tracking.
            </li>
        </ul>

        <p class="text-primary">
            <strong>Contact:</strong><br>
            For questions regarding this privacy policy or the app functionality, users can contact the developer at:
            <a href="mailto:akironex@gmail.com" class="text-primary">akironex@gmail.com</a>
        </p>
    </q-page>
</template>

<script setup lang="ts">
defineOptions({
    name: 'Privacy'
});
</script>

<style scoped>
h1 {
    margin-bottom: 1em;
    color: #222;
}

h2 {
    margin-top: 1.5em;
    margin-bottom: 0.5em;
    color: #333;
}

ul {
    margin-left: 20px;
    margin-bottom: 1em;
}

p {
    margin-bottom: 1em;
    line-height: 1.6;
}

a {
    color: #007bff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
</style>