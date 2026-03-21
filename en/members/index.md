# Members

<script setup>
import { data as d } from '../../.vitepress/data/members-zh.data.ts'
</script>

SiiWay Team now has {{ d.count }} members (in order of joining):

> [!WARNING]
> Some contents below are only available in Chinese, you may need a translator to view them.

<div class="members-list" v-html="d.members" />
