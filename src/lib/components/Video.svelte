<script>
    let src = '../src/public/dewey1.png'
    let src1 = '../src/public/overlay.png'
    let profile = '../src/public/image.png'
</script>

<main>
    <figure class="py-[19px] pr-[31px]">
        <div class="w-[628px] absolute flex opacity-50">
            <img src={src1} alt="Overlay">
        </div>
        
        <div class="grid grid-cols-2">
            <div class="absolute pt-[220px] pl-[20px] pb-[52px] pr-[500px]">
            <img class="border rounded-full border-[#ED7839] p-[3px]" src={profile} alt="Profile">
            
        </div>
        </div>
        <div class="absolute pl-[32px] pt-[28px] h-[54px] w-[628px]">
            <p class="text-[24px] font-black leading-8 text-[#FFFFFF]">Análise sensorial de preparações funcionais desenvolvidas para escolares entre 09 e 15 anos, do município de Campinas/SP </p>
        </div>
        <div class="absolute pl-[130px] pt-[228px]">
            <p class="text-[34px] font-black leading-8 text-[#FFFFFF]">Beatriz Christiane Melo</p>
            <p class="text-[20px] font-black leading-5 text-[#FFFFFF] pb-[60px]">FCA / Universidade Estadual de Campinas</p>
        </div>
        <img src={src} alt="Video">
    </figure>
</main>

<style>
   main {
       font-family: 'Roboto';
   }
</style>