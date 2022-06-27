<script>
import MenuItem from "$lib/components/menuitem.svelte";
import MenuItemLogo from "$lib/components/menuitemlogo.svelte";
import MenuItemTop from "$lib/components/menuitemtop.svelte";

</script>

<main class="block fixed ">
    <div class="w-[220px] h-[2508px]">
        <div class="grid grid-rows-20">
            <div><MenuItemTop /></div>
            <div><MenuItemLogo /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
            <div><MenuItem /></div>
        </div>
    </div>    

</main>

<style>
    main {
        background: #FFFFFF;
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
    }
</style>