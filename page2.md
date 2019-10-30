<h1> page 2 </h1>
<a href="https://georginah2.github.io/SML5202GH/"> Index page </a> <br>
<a href="https://georginah2.github.io/SML5202GH/page3.html"> Page 3 </a>



<h2> Here is a random name called </h2>
<button class="button" onclick="makeSentence()">Generate a sentence </button>
<p id="demo2"> </p>

<body>
  
<script>

function makeSentence() {
var person = {
names: [ "Brian", "Betty", "Fiona", "Freddy", "Mini" ],
verbs: ["walks", "runs", "eats", "drinks"],
adverbs: ["slowly", "quickly" ]
};

var i;
var text= "";
for (i = 0; i < person.names.length; i++) {

name = person.names[i];
verb = person.verbs[Math.floor(Math.random() * person.verbs.length)];
adv = person.adverbs[Math.floor(Math.random() * person.adverbs.length)];

text += name + " " + verb + " " +adv +"<br>";

document.getElementById("demo2").innerHTML = text;
}
}

</script>


</body>
