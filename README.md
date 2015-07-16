# golang.org
## To solve the problem that someone can not acess to golang.org but have demand for “golang.org/x/net/html”  
  
When you use goquery or other package, you may occur the problem "cannot find package "golang.org/x/net/html". You can use the following two methods to solve this problem.    
method 1:
<pre><code>go get golang.org/x/net/html</code></pre>
  
method 2:   
Step 1:
<pre><code>cd $GOPATH</code></pre>  
Step 2:
<pre><code>cd golang.org</code></pre>
if your GOPATH doesn't have /golang.org, you need run ``mkdir golang.org`` first  
Step 3:
<pre><code>git clone https://github.com/yufeizyf/golang.org.git</code></pre> 
