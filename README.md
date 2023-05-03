# Hi, hope you enjoy the code.
<p>Actually, I solved the problem in four different ways, and the only way I can determine if one of them is actually better than another needs math, and actually, I'm not going to go through this for the sake of math but for looking for the advantage and disengage of them!</p>
<ul>
  <li>
    <p>Solution 1 (my faword one)</p>
    <span>
      back to the school, the first algrithms i designed was this to solve this perticuler proplem, and i was very happy of since i thought i could better then my firents solution in which most of them solved using arrays. 
      so i'm going to assume the size of input is (N) so the function "fiboForward" will need n opeation on then to solve and 
      then we got O(N) if the input is gretter than 2 but if not then it will only that constant time O(1)
    </span>
  </li>
  </li>
  <p>Solution 2</p>
  <span>
    it is a little bit easy, but first I'm going to assume we have n the size of the input, and then we will do recursion to solve them, and each recursion it does two recursive calls n-1, n-2, how many numbers of operation will happen let's see, in the first one we will not do any recursion so to number of operation will 0 but the second when I become 1 then we will 2 and when it's 2 we will do 4 so on.

so we can conclude that in each recursive call, we did 
0 = 2^0, 1 = 2^1 so we say to get the number of operations in a specific level we need to 2^i + c which is some constant operation,
to get the total number of operations we need
to Sumption from i= 0 to n 2^i + c when can be rewritten as 2^n +c.

but it also has the advantage that we don't require memory here and this is the only advantage of it!
  <span>
    </li>
  </ul>
