# Are you stupid?
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
<button class="yes" 
onClick="(
    function() {
        var d = document.getElementByClass('yes');
        d.style.position = 'absolute';
        d.style.left = (Math.random()*100)+'px';
        d.style.top = (Math.random()*100)+'px';
        return false;
        }
    )(); 
    return false;">YES
</button>

<button class="no">NO</button>
