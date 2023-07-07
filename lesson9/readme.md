 Emmet abbrevations used as shortcuts to generate full code eithout effort
 
 ////////////////////    use > for making parent and child 

 p>p>p
 <p>
        <p>
            <p></p>
        </p>
    </p>



p>img
<p><img src="" alt=""></p>



p>h1
 <p>
    <h1></h1>
 </p>


p>lorem100
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis velit error a labore iusto debitis dolores consequatur quas minima pariatur mollitia cumque quos officia autem voluptas tempora illo, alias qui eos dolor, perferendis praesentium libero beatae. Neque, quaerat accusamus sint laboriosam asperiores totam omnis ut eligendi debitis! Perferendis fuga harum modi nesciunt temporibus? Impedit, ipsam a ducimus sunt dolore cupiditate esse, veritatis dignissimos laudantium aut iste quia, delectus harum nobis similique voluptate in minus odio autem nisi laboriosam qui et fugiat nam? Repellendus quasi sed nam. Nulla officia aperiam blanditiis ut iure fugit nemo atque perferendis aliquam explicabo. Harum, dolores?</p>
paragraph of 100 words


////////////////////    use * for number of times

table>(tr>td*3)
<table>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </table>



   table>(tr>td*3)*4
    <table>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </table>



  ol>li*3
 <ol>
          <li></li>
          <li></li>
          <li></li>
        </ol>


////////////////////    use + for making different tags (sibling)

 article+section
 <article></article>
 <section></section>


 p{this is my first paragraph}
  <p>this is my first paragraph</p>


////////////////////    use {} for writting content in your tag

 h1{this is my first paragraph}
  <h1>this is my first paragraph</h1>

  article{this is my first paragraph}
  <article>this is my first paragraph</article>


////////////////////    use # for id

p#para1
<p id="para1"></p>

article#article1
<article id="article1"></article>



////////////////////    use . for class  

p.para
<p class="para"></p>

article.dog
<article class="dog"></article>


section>p*3
<section>
        <p></p>
        <p></p>
        <p></p>
    </section>

section>p+p+p
 <section>
        <p></p>
        <p></p>
        <p></p>
    </section>


ol>(li>p>a)*7
     <ol>
        <li>
          <p><a href=""></a></p>
        </li>
        <li>
          <p><a href=""></a></p>
        </li>
        <li>
          <p><a href=""></a></p>
        </li>
        <li>
          <p><a href=""></a></p>
        </li>
        <li>
          <p><a href=""></a></p>
        </li>
        <li>
          <p><a href=""></a></p>
        </li>
        <li>
          <p><a href=""></a></p>
        </li>
      </ol>




























