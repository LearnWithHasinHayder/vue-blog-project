//create home component
<script setup>
function authenticate() {
    localStorage.setItem('token', '123');
}

function logout() {
    localStorage.setItem('token', 'abc');
}
</script>
<template>
    <h1 class="text-2xl mb-3">This is Login page</h1>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam doloremque natus eligendi. Dicta ullam obcaecati quidem blanditiis, illum minus possimus earum adipisci sunt accusantium autem. Saepe molestias quaerat enim. Autem.
    </p>

    <p class="mt-10">
        <button @click="authenticate()" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
            Authenticate
        </button>

        <button @click="logout()" class="ml-5 bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
            Log out
        </button>
    </p>
</template>

<style></style>