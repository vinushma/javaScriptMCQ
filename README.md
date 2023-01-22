# javaScriptMCQ - EPAM

# Question 1
<pre class="highlight plaintext">
let x = [1,2,3,4];
let y = x.map(x => x*2);

console.log(x);
console.log(y);</pre>
<div>
 # Output <pre>10
[ 1, 2, 3, 4 ]
[ 2, 4, 6, 8 ]
</pre></div>

# Question 2
<pre class="highlight plaintext">
for(var i=0;i<3;i++){
  var log = function(){
    console.log(i);
  }
  setTimeout(log, 100);
}
</pre>
<div>
 # Output <pre>
3
3
3
</pre></div>
<pre>
# Question 3 - what is output of expression '0 || null'  
console.log(0 || null);
if(0 || null){
  console.log('if');
}else{
   console.log('im in else');
}
</pre>
<div>
 # Output <pre>
im in else
null

</pre></div>
<pre>
# Question 4 - what is output of expression  '0 && null'
console.log(0 || null);
if(0 && null){
  console.log('if');
}else{
   console.log('im in else');
}
</pre>
<div>
 # Output <pre>
im in else
0

</pre></div>
<pre>
# Question 5 
var arr1 = "john".split('');
var arr2 = arr1.reverse();
var arr3 = "jones".split('');
arr2.push(arr3);
console.log(arr1.length);
console.log(arr1.slice(-1))
</pre>
<div>
 # Output <pre>
5
[ [ 'j', 'o', 'n', 'e', 's' ] ]
</pre></div>
# Question 6 
var foo = [];
for(var i=0;i<10;i++){
  (function(){
    var y=i;
    foo[i] = function(){
      return y;
    };
    
  })()
  
}
console.log(foo[2]());
</pre>
<div>
 # Output <pre>
2
</pre>
