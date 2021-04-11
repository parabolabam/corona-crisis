<script lang="ts">
    import { Map } from '@beyonk/svelte-mapbox';

    const style = 'mapbox://styles/mapbox/satellite-v9'
    const accessToken = 'pk.eyJ1IjoicGFyYWJvbGFiYW0iLCJhIjoiY2tnZzVpMzA5MW5tYjJxcWF0Yjd5dWxleCJ9.aawEheRBWMx3lkW8NwXZRA'
</script>

<Map {accessToken} {style} />