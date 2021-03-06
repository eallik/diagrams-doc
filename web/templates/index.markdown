---
title: About diagrams
---
 <p class="lead" style="text-align: center; font-size: 3rem">
<b>diagrams</b> is a <em>powerful</em>, <em>flexible</em>, <em>declarative</em> domain-specific language
for creating vector graphics, using the
[Haskell programming language](http://haskell.org/).
 </p>
 <br>
 <div class="row">

 <div class="col-md-4">
 <div class="panel panel-default lead-panel" onclick="window.location='doc/quickstart.html';">
 <div class="panel-body">
 <p class="lead text-center" style="font-weight:bold; font-size:24px">Get started</p>
 <p class="text-center">
Read the [quick start tutorial](doc/quickstart.html) or the [user manual](doc/manual.html).
 </p>
 </div>
 </div>
 </div>

 <div class="col-md-4">
 <div class="panel panel-default lead-panel" onclick="window.location='gallery.html';">
 <div class="panel-body">
 <p class="lead text-center" style="font-weight:bold; font-size:24px">Get excited</p>
 <p class="text-center">
 Check out the [gallery](/gallery.html) for example images and
 code.
 </p>
 </div>
 </div>
 </div>

 <div class="col-md-4">
 <div class="panel panel-default lead-panel" onclick="window.location='http://webchat.freenode.net/?channels=diagrams';">
 <div class="panel-body">
 <p class="lead text-center" style="font-weight:bold; font-size:24px">Get connected</p>
 <p class="text-center">
Drop by the [`#diagrams` IRC channel](http://webchat.freenode.net/?channels=diagrams)
with questions, or post them to the
[mailing list](http://groups.google.com/group/diagrams-discuss).
 </p>
 </div>
 </div>
 </div>

 </div>

 <!--
 <form method="get" action="http://paste.hskll.org">
 <p class="lead text-center">
 Impatient? &nbsp;&nbsp; <button type="submit" value="clickable button" class="btn btn-primary btn-lg">Try diagrams in your browser!</button>
 </p>
 </form>
 -->

 <div class="row">
 <div class="col-md-8 col-md-offset-2">
News
----

 $for(news)$
 $partial("templates/newsitem.html")$
 $endfor$
 </div>
 </div>

 <hr />

 <p class="small text-center">
 Built with [hakyll](http://jaspervdj.be/hakyll/), [pandoc](http://johnmacfarlane.net/pandoc/), and, of course, diagrams.
 </p>
