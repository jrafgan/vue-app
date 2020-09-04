<template>
    <b-container class="bv-example-row">
        <h2>Кыргызы всех стран, объединяйтесь !<b-badge>New</b-badge></h2>
        <b-row>
            <b-col sm="12" md="9">Это большая колонка
                <b-list-group horizontal>
                    <b-list-group-item>Default list group item</b-list-group-item>
                    <b-list-group-item variant="primary">Primary list group item</b-list-group-item>
                    <b-list-group-item variant="secondary">Secondary list group item</b-list-group-item>
                    <b-list-group-item variant="success">Success list group item</b-list-group-item>
                    <b-list-group-item variant="danger">Danger list group item</b-list-group-item>
                    <b-list-group-item variant="warning">Warning list group item</b-list-group-item>
                    <b-list-group-item variant="info">Info list group item</b-list-group-item>
                    <b-list-group-item variant="light">Light list group item</b-list-group-item>
                    <b-list-group-item variant="dark">Dark list group item</b-list-group-item>
                </b-list-group>
            </b-col>
            <b-col sm="12" md="3">Это маленькая колонка
                <b-list-group>
                    <b-list-group-item>Default list group item</b-list-group-item>
                    <b-list-group-item variant="primary">Primary list group item</b-list-group-item>
                    <b-list-group-item variant="secondary">Secondary list group item</b-list-group-item>
                    <b-list-group-item variant="success">Success list group item</b-list-group-item>
                    <b-list-group-item variant="danger">Danger list group item</b-list-group-item>
                    <b-list-group-item variant="warning">Warning list group item</b-list-group-item>
                    <b-list-group-item variant="info">Info list group item</b-list-group-item>
                    <b-list-group-item variant="light">Light list group item</b-list-group-item>
                    <b-list-group-item variant="dark">Dark list group item</b-list-group-item>
                </b-list-group>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
    import './BodyCustom.css'
    export default {
        name: "Body"
    }
</script>
