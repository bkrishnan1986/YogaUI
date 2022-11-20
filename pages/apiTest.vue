<template>
	{{ data }}
	{{ data[0].SchoolId }}
</template>

<script setup>
const { data } = await useFetch('https://devteam.yogaalliance.org/DesktopModules/YAServices/API/School/GetSchoolByUserID?userId=159930')
</script>