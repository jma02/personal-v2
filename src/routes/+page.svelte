<script lang="ts">
    import { Separator } from "$lib/components/ui/separator/index.js";
    import * as Carousel from "$lib/components/ui/carousel/index.js";
</script>
<div class="max-w-screen-md mx-auto px-4 py-16">
    <h1 class="py-3 text-2xl font-medium">Jonathan Ma</h1>
    <h2 class="py-2 font-light">I am a <span class="text-gray-500">software engineer</span>
        as well as <span class="text-gray-500">amateur mathematician.</span>
    </h2>
    <h2 class="py-2 font-light">I currently work for
        <a class="text-blue-950" href={"https://www.chathamfinancial.com/"}>Chatham Financial,</a>
        where I help develop analytic software products for private equity companies such as Blackstone.
    </h2>
    <h2 class="py-2 font-light">
       I am graduating from the University of Delaware this Spring with degrees in Mathematics and Computer Science.
    </h2>
    <h2 class="py-2 font-light">
        My other interests are olympic weightlifting, and cycling.
    </h2>
    <Carousel.Root class="p-20 text-center items-center">
        <Carousel.Content>
            <Carousel.Item ><img src="/me_and_mk1.jpg" alt="Me and the Harvard Mk 1"/>
                <p class="py-5 font-light">Me and the Harvard Mark 1</p>
            </Carousel.Item>
            <Carousel.Item class="items-center">
                <video class="w-full h-auto" controls loop src="/squatting.mov" title="454lb/205kg Squat video">
                    Your browser does not support the video tag.
                </video>
                <p class="py-5 font-light">455lb/205kg Squat</p>
            </Carousel.Item>
            <Carousel.Item ><img src="/algebra.jpg" alt="Algebra book spotted in the wild"/>
            <p class="py-5 font-light">Algebra book spotted in the wild.</p>
            </Carousel.Item>
            <Carousel.Item ><img src="/jan-ahmed.jpg" alt="Jan Ahmed Thinking"/>
                <p class="py-5 font-light">Jan Ahmed Thinking (2024).</p>
            </Carousel.Item>
        </Carousel.Content>
        <Carousel.Previous />
        <Carousel.Next />
    </Carousel.Root>
    <div class="flex h-5 my-10 items-center space-x-4 font-light text-gray-500">
        <a href="https://www.linkedin.com/in/johnma02/">LinkedIn</a>
        <Separator orientation="vertical"/>
        <a href="https://github.com/johnma02">GitHub</a>
        <Separator orientation="vertical"/>
        <a href="/Ma_Jonathan.pdf" target="_blank">Resume</a>
        <Separator orientation="vertical"/>
        <a href="mailto:ma.jonathan02@gmail.com">Email</a>
    </div>

</div>
