<script>
import Dashboard from "./dashboard/dashboard.svelte";
import Header from "./header.svelte";
import LeftMenu from "./leftMenu.svelte";

</script>
<div class="container">
<Header />
<div class="body">
    <div class="left-section">
    <LeftMenu />
    </div>
    <div class="right-section">
        <Dashboard />
    </div>

</div>
</div>