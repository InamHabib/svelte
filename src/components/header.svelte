<script>
import {Arrival} from "carbon-icons-svelte/lib";
import {UserAvatarFilledAlt} from "carbon-icons-svelte/lib/";
</script>
<div class="header-container">
<div class="left-section">
    <Arrival size={24}/>
    <span >KL Dasboard</span>
</div>
<div class="right-section">
    <UserAvatarFilledAlt /> <h4 >Inam Habib</h4>
</div>
</div>

<style>
    span{
        font-size:24px;
        font-weight: bold;
        padding-left: 1rem;
    }
</style>