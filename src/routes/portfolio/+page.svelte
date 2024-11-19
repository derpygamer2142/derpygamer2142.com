<script>
    import "$lib/listStyles.css"
    import SoupCat from "$lib/images/soup-cat.gif"
    import Raytracer3 from "$lib/images/raytracer 3 morrowind.png"
    import Meowy from "$lib/images/meowy.svg"
    import GitHub from "$lib/images/github.png"
    import GPUSB3 from "$lib/images/gpusb3 thumbnail.png"
</script>

<h2>Portfolio</h2>

<p class="ignoreP">this page is for employers and people curious about stuff i do to show what i know</p>


<div class="list">

    <div class="item">
        <img src={Raytracer3} alt="Raytraced scene" width=300 height=168.75>
        <h3>3D stuff</h3>
        <p>I know a bit about 3d graphics, enough to make semi basic projects and explain it to people who know nothing, but currently not enough to implement complex algorithms. See <a href="/3d">the 3d page</a>.</p>
    </div>

    <div class="item">
        <a href="https://extensions.derpygamer2142.com/docs/gpusb3"><img src={GPUSB3} alt="GPU.SB3 thumbnail" width=300 height=168.75></a>
        <h3>WebGPU</h3>
        <p>I made a Turbowarp extension that compiles scratch code to WGSL, and lets you use compute shaders.</p>
    </div>

    <div class="item">
        <img src={Meowy} alt="The meower logo" width=300 height=300>
        <h3>Meower</h3>
        <p>I helped on the frontend of the <a href="https://meower.org">Meower</a> example client until the project got abandoned.</p>
    </div>

    <div class="item">
        <a href="https://github.com/derpygamer2142?page=1&tab=repositories"><img src={GitHub} alt="A link to my github" width=300 height=300></a>
        <h3>Misc web dev stuff</h3>
        <p>I have done a bunch of miscellaneous web development stuff such as websites, tech demos, and more. Check my github.</p>
    </div>

    <div class="item">
        <img src={SoupCat} alt="Soup cat" width=300 height=300>
        <h3>School newspaper</h3>
        <p>I'm the head programmer for my school newspaper, not saying the name because this site is public but i will specify if asked.</p>
    </div>

</div>

<style>
    p:not(.ignoreP) {
        max-width: 15vw;
        margin: auto;
    }
</style>