<script setup>
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
</script>

<template>
    <div>
        <div class="p-6 lg:p-8 bg-white dark:bg-gray-800 dark:bg-gradient-to-bl dark:from-gray-700/50 dark:via-transparent border-b border-gray-200 dark:border-gray-700">
            <div class="relative">
                <input type="text" class="border rounded-md p-2 w-64" placeholder="Cerca...">
            </div>

            <table class="w-full border-collapse text-white mt-5">
                <thead>
                <tr class="border-b dark:border-gray-600 text-left uppercase">
                    <th class="p-2">Codice</th>
                    <th class="p-2">Nome</th>
                    <th class="p-2">Email</th>
                    <th class="p-2">Telefono</th>
                    <th class="p-2">Partita IVA</th>
                    <th class="p-2"></th>
                </tr>
                </thead>
                <tbody>
                <tr class="hover:bg-gray-100 dark:hover:bg-gray-700">
                    <td class="p-2">...</td>
                    <td class="p-2">...</td>
                    <td class="p-2">...</td>
                    <td class="p-2">...</td>
                    <td class="p-2">...</td>
                    <td class="p-2">
                        <button class="text-white bg-dark-blue py-1 px-3 rounded dark:bg-blue-500 hover:bg-blue-700">Visualizza</button>
                    </td>
                </tr>
                <!-- Add more rows as needed -->
                </tbody>
            </table>
        </div>

    </div>
</template>
