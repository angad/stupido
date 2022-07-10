# Are you stupid?
<!--<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>-->
<script type="text/javascript">
    function moveit() {
        const width  = window.innerWidth || document.documentElement.clientWidth ||
        document.body.clientWidth;
        const height = window.innerHeight|| document.documentElement.clientHeight||
        document.body.clientHeight;
        var d = document.getElementById('no');
        d.style.position = 'absolute';
        d.style.left = (Math.random()*width)+'px';
        d.style.top = (Math.random()*height)+'px';
        return false;
    }
</script>
<button id="yes">YES</button>
<button id="no" onmouseover="moveit()" ontouchstart="moveit()">
NO
</button>
