<template lang="html">
  <Container class="noticebar-page">
    <PageHeader title="通告栏 NoticeBar" />
    <Demo></Demo>
    <PageFooter />
  </Container>
</template>

<script>
import Container from '../common/Container.vue';
import PageHeader from '../common/PageHeader.vue';
import PageFooter from '../common/PageFooter.vue';
import Demo from '../docs/noticeBar.md';

import '../styles/pages/NoticeBarPage.scss';

export default {
  components: {
    Container,
    PageHeader,
    PageFooter,
    Demo
  }
};
</script>
