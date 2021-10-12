<style>

#sbtbacktotop{

background: url(//1.bp.blogspot.com/-CH03QlSNpBY/UnCY1gMhmXI/AAAAAAAACaM/qZaVYNrP0-s/s1600/back-to-top-sprite-30224d9b.png) 0 0 no-repeat;

height: 130px;

width: 72px;

padding:5px;

position:fixed;

bottom: 5px;

right: 5px;

cursor:pointer;

transition:none;

    z-index:15;

}

  #sbtbacktotop:hover{

    background:url(//1.bp.blogspot.com/-CH03QlSNpBY/UnCY1gMhmXI/AAAAAAAACaM/qZaVYNrP0-s/s1600/back-to-top-sprite-30224d9b.png)no-repeat;

background-position: 0 -142px;

}

</style>


<script type='text/javascript'>

//<![CDATA[

$(window).scroll(function(){if($(this).scrollTop()>100)

{$("#sbtbacktotop").removeAttr("href");$("#sbtbacktotop").stop().animate(

{bottom:"0"},{duration:100,queue:false})}

else{$("#sbtbacktotop").stop().animate({bottom:"30000"},

{duration:8000,queue:false})}});$(function()

{$("#sbtbacktotop").click(function()

{$("html, body").animate({scrollTop:0},"slow");

return false})});

//]]>

</script>

<!-- Code provided to you by sbt -->

<a href='#' id='sbtbacktotop'></a>
