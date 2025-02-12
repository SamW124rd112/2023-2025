# #[[MAT 1322]]
- ### [[Euler's Method and Applications of DEs]]
- ### [[Sequences]]
- ### [[Series]]
- ### [[The Integral & The Comparison Test]]
- ### [[Remainder Estimate Error Bounds & Limit Comparision Test]]
- ### [[Alternating Series & Absolute/Conditional Convergence]]
- ### [[Ratio & Root Tests & General Strategies for Testing Series]]
- ### [[Power Series]]
- ## Topics Covered:
	- ### Euler Method's
		- **Euler's method** is a method of solving differential equations with the general formula
			- $$x_{n+1} = x_n  + \Delta x$$
			- $$y_{n+1} = y_n  + f(x_n,y_n) \Delta x$$
			- ![image.png](../assets/image_1709779635455_0.png)
	- ### Applications of DEs
		- Newton's Laws of Heating and Cooling
			- $$T(t) = T_s + (T_o - T_s)e^{-kt}$$
				- $T_s$ surrounding temperature
				- $T(t)$ target temperature
				- $T_o$ initial temperature
	- ### Sequences
		- A **sequence** is an ordered list of numbers
			- ![image.png](../assets/image_1709785535482_0.png)
		- A sequence is considered **convergent** of its $\lim_{n \rightarrow \infin}$ is a unique real number
		- #### Limit Laws for Sequences:
			- $$\lim_{n \rightarrow \infin} (a_n + b_n) = \lim_{n \rightarrow \infin} a_n + \lim_{n \rightarrow \infin} b_n$$
			- $$\lim_{n \rightarrow \infin} (a_n - b_n) = \lim_{n \rightarrow \infin} a_n - \lim_{n \rightarrow \infin}$$
			- $$\lim_{n \rightarrow \infin} ca_n = c( \lim_{n \rightarrow \infin} a_n)$$
			- $$\lim_{n \rightarrow \infin} (a_n b_n) = (\lim_{n \rightarrow \infin} a_n) ( \lim_{n \rightarrow \infin} b_n)$$
			- $$\lim_{n \rightarrow \infin}(\frac{a_n}{b_n}) = \frac{\lim_{n \rightarrow \infin} a_n}{\lim_{n \rightarrow \infin} b_n} \text{ provided } \lim_{n \rightarrow \infin} b_n \ne 0$$
			- $$\lim_{n \rightarrow \infin} (a_n)^p = (\lim_{n \rightarrow \infin} a_n)^p \text{ if } p > 0 \text{ and } a_n >0$$
		- #### Squeeze Theorem
			- $$\lim_{n \rightarrow \infin} a_n = L \le \lim_{n \rightarrow \infin} b_n \le L = \lim_{n \rightarrow \infin} c_n \\ \therefore \lim_{n \rightarrow \infin} b_n =L$$
	- ### Series
		- #### Infinite Series
			- A sum is:
				- $$\sum_{n = 1}^\infin a_n = a_1 + a_2 + a_3 + ... + a_i = ?$$
			- Finite sums to term $S_n$ are **partial sums**
			- If a sequence of partial sums converges to a fininite number $L$, then a series is said to **converge** to $L$, written $\sum_{n=1}^\infin a_n = L$
			- If sequence diverges, series diverges
			- ![image.png](../assets/image_1709786461765_0.png)
		- #### Geometric Series
			- A **geometric series** has a first term $a$ and **common ratio** $r$ in the form
				- $$a + ar + ar^2 + ar^3 + ...$$
			- In equation form, it typically needs to be simplified to some:
				- $$\sum x (\frac{a}{b})^n$$
			- $$S_n = \frac{a(1-r^n)}{1-r} \qquad \lim_{n \rightarrow \infin}S = \frac{a}{1-r}$$
			- If $|r| < 1$, then the geometric series $\sum_{n=1}^\infin ar^{n-1}$ is convergent and it converges to $\frac{a}{1-r}$, else if $|r| > 1$. the geometric series is divergent
	- ### Integral and Comparision Tests
		- #### Integral Test
			- $\sum_{n=1}^\infin a_n$ is convergent if and only if $\sum_1^\infin f(x)$ is convergent
			- In $p$ series, $\sum_{n=1}^\infin \frac{1}{n^p} \ dx$,
				- Convergent if $p > 1$
				- Divergent if $p \le 1$
		- #### Comparision Test
			- If $\sum b_n$ is convergent and $a_n \le b_n$ for all $n$, then $\sum a_n$ is convergent
			- If $\sum b_n$ is divergent and $a_n \ge b_n$ for all $n$, then $\sum a_n$ is divergent
	- ### Remainder Estimate Error Bounds
	  collapsed:: true
		- To determine error in estimating the function we use:
			- $$S_n + \int_{n+1}^\infin  f(x) \le S \le S_n + \int_n^\infin f(x) \ dx$$
		- #### Examples:
			- ![image.png](../assets/image_1709845902859_0.png)![image.png](../assets/image_1709845916308_0.png) ![image.png](../assets/image_1709845924972_0.png)
			- ![image.png](../assets/image_1709845891659_0.png)
	- ### Limit Comparision Test
	  collapsed:: true
		- If,
			- $$\lim_{n \rightarrow \infin} \frac{a_n}{b_n} = c$$
			- where $c$ is finite number and $c > 0$ then $\sum a_n$ and $\sum b_n$ either both **converge** or **diverge**
		- Examples:
			- ![image.png](../assets/image_1709846263355_0.png)
			- ![image.png](../assets/image_1709846267940_0.png)
	- ### Alternating series and absolute convergence
	  collapsed:: true
		- An **alternating** series is a series is which consecutive temrs have alternating terms:
			- ![image.png](../assets/image_1709846348445_0.png)
		- If the alternating series $\sum_{n=1}^\infin (-1)^{n-1} b_n = b_1 - b_2 + b_3 - b_4 + b_5 - b_6 + ...$ (where $b_n > 0$ for all $n$) satisfies
			- $b+{n+1} \le b$ for all $n$
			- $\lim_{n \rightarrow \infin} b_n = 0$
		- then the series is convergent
		- #### Estimation Theorem for ALternating Series
			- If all of the conditions above are met, $|R_n| = |S-S_n| \le b_{n+1}$
			- ![image.png](../assets/image_1709846847114_0.png)
		- An alternative series is **absolutely convergent** if the series $\sum |a_n|$ converges
		- An alternating series is **conditonally convergent** if $\sum|a_n|$ is divergent but $\sum a_n$ is convergent
	- ### Ratio and Root tests
		- #### The Ratio Test
			- If $\lim_{n \rightarrow \infin} | \frac{a_{n+1}}{a_n}| = L$ and $L < 1$, then $\sum_{n=1}^\infin a_n$ is ^^absolutely convergent^^
			- If $\lim_{n \rightarrow \infin} | \frac{a_{n+1}}{a_n}| = L$ and $L > 1$, then $\sum_{n=1}^\infin a_n$ is ^^divergent^^
			- If $\lim_{n \rightarrow \infin} | \frac{a_{n+1}}{a_n}| = L$ and $L = 1$, then Ratio Test is ^^inconclusive^^
			- ![image.png](../assets/image_1709847803071_0.png)
		- #### The Root Test
			- If $\lim_{n \rightarrow \infin}  \sqrt[n]{|a_n|}= L < 1$, then $\sum_{n=1}^\infin a_n$ is ^^absolutely convergent^^
			- If $\lim_{n \rightarrow \infin}  \sqrt[n]{|a_n|}=L > 1$, then $\sum_{n=1}^\infin a_n$ is ^^divergent^^
			- If $\lim_{n \rightarrow \infin}  \sqrt[n]{|a_n|}=L = 1$, then Root Test is ^^inconclusive^^
			- ![image.png](../assets/image_1709847925425_0.png)
	- ### Strategies for Testing Series
	  collapsed:: true
		- $$\sum_{m=1}^\infin \frac{m!}{m^m}$$
			- ![Screenshot from 2024-03-06 12-34-50.png](../assets/Screenshot_from_2024-03-06_12-34-50_1709746542018_0.png)
		- $$\sum^\infin (\frac{n}{n+1})^{n^2}$$
			- ![Screenshot from 2024-03-06 12-36-08.png](../assets/Screenshot_from_2024-03-06_12-36-08_1709746781612_0.png)
		- $$\sum^\infin ke^{-k^2}$$
			- ![Screenshot from 2024-03-06 12-40-10.png](../assets/Screenshot_from_2024-03-06_12-40-10_1709746850624_0.png)
		- $$\sum_{n=1}^\infin \frac{(-1)^{n-1} \sin^2(n)}{n^2}$$
			- ![Screenshot from 2024-03-06 12-41-12.png](../assets/Screenshot_from_2024-03-06_12-41-12_1709746894973_0.png)
		-
	- ### Power series
		- A **power series centred** at $x = n$
			- $$\sum_{n=0}^\infin c_n (x-a)^n = c_0 + c_1(x-a) + c_2(x-a)^2 + c_3(x-a)^3 +....$$
		- If the series is centred then, $x= a$
			- $$\sum_{n=0}^\infin c_n (a-a)^n = c_0 + c_1(0) + c_2(0)^2 +.... = c_0$$
		- If the series is centered at $a = 0$, then
			- $$\sum_{n=0}^\infin c_n (x-0)^n = \sum_{n=0}^\infin c_n x^n  c_0 + c_1x + c_2x^2 + c_3x^3 +....$$
			- ![image.png](../assets/image_1709849141167_0.png)
		- #### Radius and Interval of Convergence
			- There are only 3 possiblities for a power series
			- The series converges only when $x = a$
			  logseq.order-list-type:: number
			- The series converges for all $x \in \mathbb{R}$
			  logseq.order-list-type:: number
			- There is a positive number $R$ such that (Radius of convergence)
			  logseq.order-list-type:: number
				- The series converges if $|x-a| < R$
				  logseq.order-list-type:: number
				- The series diverges if $|x-a| > R$
				  logseq.order-list-type:: number
			- ![image.png](../assets/image_1709849260867_0.png){:height 495, :width 688}