<script setup>
const props = defineProps({
    pictures: {
        type: Array,
        default() {
            return [
                {
                    'src': 'https://flowbite.com/docs/images/carousel/carousel-1.svg',
                    'alt': 'Picture 1',
                },
                {
                    'src': 'https://flowbite.com/docs/images/carousel/carousel-2.svg',
                    'alt': 'Picture 2',
                },
                {
                    'src': 'https://flowbite.com/docs/images/carousel/carousel-3.svg',
                    'alt': 'Picture 3',
                },
            ]
        },
    },
})
</script>