<template>
    <!-- Footer -->
    <footer class="mt-auto bg-transparent border-t border-gray-100/10">
        <div class="px-6 py-8 mx-auto overflow-hidden max-w-7xl lg:px-8">
            <!-- Social Media Icons -->
            <div class="flex justify-center space-x-10">
                <a class="text-gray-400 hover:text-gray-500" href="#">
                    <span class="sr-only">Facebook</span>
                    <!-- Facebook SVG code -->
                </a>
                <a class="text-gray-400 hover:text-gray-500" href="#">
                    <span class="sr-only">Instagram</span>
                    <!-- Instagram SVG code -->
                </a>
                <a class="text-gray-400 hover:text-gray-500" href="#">
                    <span class="sr-only">Twitter</span>
                    <!-- Twitter SVG code -->
                </a>
                <a class="text-gray-400 hover:text-gray-500" href="#">
                    <span class="sr-only">GitHub</span>
                    <!-- GitHub SVG code -->
                </a>
                <a class="text-gray-400 hover:text-gray-500" href="#">
                    <span class="sr-only">YouTube</span>
                    <!-- YouTube SVG code -->
                </a>
            </div>
            <!-- /Social Media Icons -->

            <p class="mt-10 text-xs leading-5 text-center text-gray-500">
                &copy; {{ new Date().getFullYear() }} - ChakriBakri | All rights
                reserved.
            </p>
        </div>
    </footer>
    <!-- /Footer -->
</template>

<script setup>
import { usePage } from "@inertiajs/vue3";

const { app_name } = usePage().props;
</script>
