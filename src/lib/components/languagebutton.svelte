<script>

    let src2 = "../src/public/language_image.png"
    let src3 = "../src/public/dropdown.png"

</script>

<main>
    <div class="static border border-solid w-[97px] h-[34px] border-box rounded items-center self-center">
        <div class="grid grid-cols-3 gap-1">
            <figure class="w-[22px] h-[21px]">
                <img src={src2} alt="Language" />   
            </figure>
            <p class="text-[14px]">PT, BR</p>
            <figure class="w-[22px] h-[21px]">
                <img src={src3} alt="Dropdown" />
            </figure> 
        </div>
    </div>
</main>

<style>
    main {
        font-family: 'Quicksand';
    }
</style>