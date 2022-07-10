# Are you stupid?
<script type="text/javascript">
    function moveit() {
        const width  = window.innerWidth ||
        document.documentElement.clientWidth ||
        document.body.clientWidth;
        const height = window.innerHeight ||
        document.documentElement.clientHeight||
        document.body.clientHeight;
        var d = document.getElementById('no');
        d.style.position = 'absolute';
        d.style.left = (Math.random()*width-50)+'px';
        d.style.top = (Math.random()*height-50)+'px';
        return false;
    }
</script>
<button id="yes">YES</button>
<button id="no" onmouseover="moveit()" ontouchstart="moveit()">
NO
</button>
