# Are you stupid?
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
<button class="yes" 
onClick="(
    function() {
        $('.yes').finish().animate({
            left: '-=30'
        });
        return false;
        }
    )(); 
    return false;">YES
</button>

<button class="no">NO</button>
