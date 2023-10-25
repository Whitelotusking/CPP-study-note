---


---

<h1 id="野指针"><span class="prefix"></span><span class="content">野指针</span><span class="suffix"></span></h1>
<ul>
<li>delete释放内存或者用free释放内存的时候，只是释放了指针指向的内存，但实际上指针内存并没有被释放，这时候指针所指向的位置就是非法内存，若不改变指针的值或者赋值为nullptr就会变为野指针</li>
<li>定义指针时如果不给指针赋值为nullptr或者合法内存单元那么指针也会变为野指针</li>
<li>当指针指向了栈空间单元时，这时候指针在栈空间被释放之后也会变为野指针。</li>
</ul>

