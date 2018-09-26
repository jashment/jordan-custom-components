<template>
    <v-list>
        <v-list-tile
          value="true"
          v-for="(item, i) in items"
          :key="i"
        >
          <v-list-tile-action>
            <v-icon v-html="item.icon"></v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title v-text="item.title"></v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
      </v-list>
</template>

<script>
export default {
    name: 'Servers'
,
data () {
    return {
        items: [{
            icon: 'compare_arrows',
            title: 'Server #1'
        },
        {
            icon: 'compare_arrows',
            title: 'Server #2'
        },
        {
            icon: 'compare_arrows',
            title: 'Server #3'
        },
        {
            icon: 'compare_arrows',
            title: 'Server #4'
        },
        {
            icon: 'compare_arrows',
            title: 'Server #5'
        },
        ]
    }
}
}
</script>

<style>

</style>
