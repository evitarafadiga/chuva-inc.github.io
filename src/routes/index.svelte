<script>
import Video from "$lib/components/Video.svelte";
import Button from "$lib/objects/Button.svelte";
import Content from "$lib/objects/Content.svelte";
import Detalhes from "$lib/objects/Detalhes.svelte";

import Footer from "$lib/objects/Footer.svelte";
import Header from "$lib/objects/Header.svelte";
import Sidemenu from "$lib/objects/Sidemenu.svelte";
</script>

<div class="grid grid-cols-[220px_minmax(1058px,_1fr)_45px] gap-0">
    <div class="w-[220px]">
        <Sidemenu />
    </div>
    <div class="bg-local">
        <div class="">
            <Header />
        </div>
        <div class="grid grid-cols-[659px_minmax(242px,_1fr)_45px] gap-4 pb-[30px] pt-[19px] pl-[45px] pr-[30px]">
            <div>
                <h1 class="h-[54px] leading-8 font-bold text-[20px] text-[#ED7839]">Análise sensorial de preparações funcionais desenvolvidas para escolares entre 09 e 15 anos, do município de Campinas/SP </h1>
                <Video />
            </div>
            <div>
                <div class="grid grid-cols-[100px_minmax(43px,_1fr)_43px] gap-1 px-[12px] py-[12px]">
                    <Button>Download</Button>
                    <Button />
                    <Button />
                </div>
                <p class="text-right pt-[12px] pb-[15px] font-medium text-[14px] text-[#ED7839] leading-6">COMO CITAR ESSE TRABALHO?</p>
                <Detalhes />
            </div>
            
        </div>
        
        <Content />
        <Footer />
    </div>
    <div>

    </div>
    
    
</div>

<style>
    @import url("https://fonts.googleapis.com/css?family=Roboto&display=swap");
    @import url("https://fonts.googleapis.com/css?family=Quicksand&display=swap");
</style>