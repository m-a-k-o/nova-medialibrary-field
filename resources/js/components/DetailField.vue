<template>
    <panel-item :field="field" class="medialibrary-detail-field">
        <Medialibrary slot="value" :field="field"/>
    </panel-item>
</template>

<script>
import Medialibrary from './Medialibrary/Medialibrary'

export default {
    props: ['resource', 'resourceName', 'resourceId', 'field'],

    components: { Medialibrary }
}
</script>
