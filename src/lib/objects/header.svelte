<script>
import LanguageButton from "$lib/components/languagebutton.svelte";

</script>

<main>
    <div class="px-[35px] pt-[5px] flex grid grid-cols-[789px_minmax(260px,_1fr)_260px] gap-2 bg-[#FDF1EB] w-[1146px] h-[68px]">
        <div class="">
            <p class="leading-3 text-[14px] text-[#725C5C]">Anais do Simpósio Latino Americano de Ciências de Alimentos </p>
            <p class="leading-6 text-[22px] text-[#725C5C]">Anais do 13º Simpósio Latino Americano de Ciência de Alimentos</p>
            <p class="leading-2 text-[14px] text-[#725C5C]">ISSN: 1234-5678</p>
        </div>
        <div class="self-center">
            <LanguageButton />
        </div>
    </div>
    
</main>

<style>
    main {
        font-family: 'Roboto';
    }
</style>