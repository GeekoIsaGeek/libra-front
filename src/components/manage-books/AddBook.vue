<script setup>
import BookForm from '@/components/manage-books/BookForm.vue';

const initialObject = {
	title: { en: '', ka: '' },
	author: { en: '', ka: '' },
	description: { en: '', ka: '' },
	language: { en: '', ka: '' },
	year: '',
	pages: '',
	tags: null,
	image: '',
	slug: '',
	file: null,
};
</script>

<template>
	<BookForm mode="add" :bookData="initialObject" />
</template>
