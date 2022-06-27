<script>
import Button from "./button.svelte";
import Card from "./card.svelte";

let icon1 = '../src/public/icone1.png'
let icon2 = '../src/public/icone2.png'
let icon3 = '../src/public/icone3.png'

</script>

<main class="grid grid-rows-7 gap-5 ">
    <div class="w-1058 h-621 border-solid border rounded-[3px] border-[#ECECEC]">
        <div class="w-1058 h-45 border border-solid rounded-[3px] bg-[#FDF1EB]">
            <h1 class="pl-[15px] pr-[15px] pt-[10px] pb-[10px] font-medium text-[20px] leading-8 text-[#4E4E4E] flex items-center">
                Discussões 
            </h1>
        </div>
        <div class="grid grid-rows-3 gap-4 pb-[17px]">
            <div class="pl-[15px] pr-[15px] pt-[10px] pb-[10px] static w-1028 h-114 items-center text-center" >
                <p class="static font-bold text-[18px] leading-8 text-[#ED7839] flex-none order-0 self-stretch tracking-wide">
                    Compartilhe suas ideias ou dúvidas com os autores!
                </p>
            </div>
            <div class="px-[335px] grid grid-cols-3 items-center self-center">
                <img src={icon1} alt="Adubo" />
                <img src={icon2} alt="Letras" />
                <img src={icon3} alt="Conversa" />
            </div>
            <div class="w-62 text-center text-[14px] leading-5 text-[#595959] flex-none order-0 items-center self-stretch tracking-wide">
                Sabia que o maior estímulo no desenvolvimento científico e cultural é a curiosidade? Deixe seus questionamentos ou sugestões para o autor!
            </div>
            <div class="pl-[45px] ">
                <div class="px-[15px] w-[900px] h-[1px] items-center top-[1024px] border-solid border border-grey">
                    <div class="absolute pl-[370px]">
                        <Button />
                    </div>
                </div>
            </div>
            <div class="px-[15px] pb-[17px]">
                <Card />
            </div>
            <div class="px-[15px] pb-[17px]">
                <Card />
            </div>
        </div>
        
    </div>
    
</main>

<style>
   
</style>