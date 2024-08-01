<script setup>
import { ref } from 'vue'
import FloatingInput from '../../WebCommoncomponents/FloatingInput.vue';
import SelectDropdown from '../../WebCommoncomponents/SelectDropdown.vue';

const selectOptions = [
    { value: 'us', label: 'United States' },
    { value: 'ca', label: 'Canada' },
    { value: 'uk', label: 'United Kingdom' },
    // ... more options
]

const selectedCountry = ref('')

</script>

<template>
    <form class="mt-2">
        <!-- Import Common Compoennts -->
        <FloatingInput id="custom-input" label="Floating Input" placeholder="" />
        <SelectDropdown id="country" label="Select your country" placeholder="Select your country"
                        :options="selectOptions" v-model="selectedCountry" />
    </form>
</template>
