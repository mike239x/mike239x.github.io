<script language="javascript" type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.0/p5.min.js"></script>
<script language="javascript" type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.0/addons/p5.dom.min.js"></script>
<!-- <script src="../libs/p5.sound.min.js"></script> -->

<!-- MathJax for fancy math formulas -->
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML"></script>
<script type="text/x-mathjax-config">MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});</script>

# H3 or something

Hello World!

[github pages](https://pages.github.com/)

<p style = 'background-color: #ff0000'> my eyes!</p>

<script type="text/javascript">
new p5(function (p) {
    var r = 40;
    function thing() {
        p.beginShape();
        p.vertex(0,0);
        p.vertex(r,0);
        p.vertex(r*0.3,r*0.6);
        p.vertex(r*0.7,r*1.2);
        p.vertex(r*0.3,r*1.8);
        p.vertex(r*0.7,r*2.4);
        p.vertex(0,r*3);
        p.endShape(p.CLOSE);
    }
    p.setup = function() {
        p.createCanvas(20+3*r,20+3*r);
        p.fill(255);
        p.stroke(0);
        p.translate(10,10);
        thing();
        p.translate(r,0);
        thing();
        p.translate(r,0);
        thing();
        p.translate(-r,3*r);
        p.rotate(p.PI);
        thing();
        p.translate(-r,0);
        thing();
        p.translate(-r,0);
        thing();
    }
    p.draw = function(){};
},'task1');
</script>

More text, this time with a formula: $\Omega \in \mathbb{R}$.
