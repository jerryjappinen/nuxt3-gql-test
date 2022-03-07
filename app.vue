<script>
import GetItemsQuery from './GetItemsQuery.gql'

export default {

  data () {
    return {
      GetItemsQuery
    }
  }
  
}
</script>

<template>
  <div>
    <pre><code>{{ JSON.stringify(GetItemsQuery, null, 2) }}</code></pre>
  </div>
</template>
