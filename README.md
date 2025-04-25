# cs6035-project-cryptography-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6035-project-cryptography-fall-23-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113167&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6035 Project Cryptography Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h2>Project Files</h2>
<h4><strong><span style="color: #0000ff;"><a style="color: #0000ff;" href="https://www.ankitcodinghub.com/product/cs6035-cryptography-fall24-solved/">Fall 2024 Solution LINK</a></span></strong></h4>
You can download <a href="https://drive.google.com/file/d/1qHXrBeJZL73Ezen2ol2F-03RCR5aYKKJ">a zip file with all necessary project files here</a>.

Goals of the Project For Students

<ul>
<li>Will get an introduction to both symmetric and asymmetric cryptographic systems</li>
<li>Will gain an understanding of how these systems are implemented through examples</li>
<li>Will exploit systems that have certain vulnerabilities</li>
<li>Will have the opportunity to engage in discussion about advanced topics in cryptography</li>
</ul>
<h2>Information</h2>
There is no required VM for this project. All that is required is a Python development environment. Make certain that you are using Python 3. To check your version of Python, open a command prompt and run the command:

python –version. (You may need to use the python3 command instead.)

For the established algorithms that you may find it necessary to use, you are allowed to reference and implement pseudocode with citation (a comment in your code will suffice)<strong>.</strong> What is Pseudocode? <a href="https://en.wikipedia.org/wiki/Pseudocode">https://en.wikipedia.org/wiki/Pseudocode</a>

<strong><u>UNDER NO CIRCUMSTANCES</u></strong> should you copy/paste code into the project. Doing so is an honor code violation (not to mention a real world security concern) and will result in a zero (refer to the <a href="https://docs.google.com/document/d/1EIR__l5eJ3hufG4tQN5kMvuSf2ZesHXmBN8bF-cj9Mg">syllabus</a> for more information).

The Final Deliverable

You will complete the provided Python file <strong>project_cryptography.py</strong> and submit it to the autograder in Gradescope.

<h2>Open Discussions</h2>
For each task we have provided prompts for further discussions. There will be threads created in Ed where students can discuss these topics. Participation is optional and will not be graded.

Task Vigenere Ciphers )

The Vigenere cipher is an example of a symmetric key cryptographic algorithm. In such a system, a single key is used to both encrypt and decrypt messages (this is what makes it symmetric). The first step for both encryption and decryption is to build a Vignere square like the one pictured below. In each row of the Vigenere square, the letters of the alphabet are shifted to the left by one. The second step is to extend the key to match the length of the cipher/message by repeating it, taking care to remove any spaces or punctuation from the original message. For example, if our message is <strong>GEORGIA</strong> and our key is <strong>TECH</strong> we would end up with a key <strong>TECHTEC</strong>.

&nbsp;

<strong>To encrypt a message,</strong> we lookup each letter of the message as a row, and find its intersection with the column whose label contains the corresponding letter from the key. Using our <strong>GEORGIA</strong>/<strong>TECH</strong> example, the intersection of the first letter of the message <strong>G</strong> with the first letter of the key <strong>T</strong> is <strong>Z</strong>. Going letter-by-letter in this manner we build our cipher until we get <strong>ZIQYZMC</strong>.

&nbsp;

<strong>To decrypt a cipher,</strong> we start with the first letter of the key and traverse that row until we reach the corresponding letter from the cipher. The label of this column is our decrypted letter. Using our same&nbsp; <strong>GEORGIA</strong>/<strong>TECH</strong> example, to decrypt the cipher we would start with the first letter of our key <strong>T</strong> and traverse that row until we reached the first letter of the cipher <strong>Z</strong>. The label of this column is <strong>G</strong> – the first letter in our message.

<em>Vigenere Square [source: Wikipedia]</em>

&nbsp;

Armed with this information, the first two parts of this task will ask you to write the necessary code to handle the encryption and decryption functionality for a Vigenere cipher system.

&nbsp;

For the third and final part, you will attempt to crack a Vigenere cipher using a dictionary attack. Ordinary words can make convenient keys because they are easy to remember, but this practice is far from secure. For this task, you are given a cipher and a list of some of the most common words in the English language. One of those words was used as the key to encrypt the cipher, and your job is to write the code to figure out which one it is. For simplicity, you can assume that all words in the original message are also chosen from the provided list of dictionary words.

&nbsp;

<table>
<tbody>
<tr>
<td width="680">def vigenere_decrypt_cipher(c: str, keyword: str) -&gt; str:

# TODO: Write the necessary code to get the message (m) from the cipher ©

# using the keyword

m = ‘’

return m

&nbsp;

def vigenere_encrypt_message(m: str, keyword: str) -&gt; str:

# TODO: Write the necessary code to create a Vigenere cipher (c) of the

# message (m) using the provided keyword

c = ‘’

return c

&nbsp;

def vigenere_dictionary_attack(c: str) -&gt; str:

# TODO: Write the necessary code to get the message (m) from the cipher (c)

m = ‘’

return m
</td>
</tr>
</tbody>
</table>
&nbsp;

Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

The Vigenere cipher improves upon the ancient Caesar cipher. Mathematically speaking, how much more complexity does it add and how does it accomplish this? What are some ways that one could add more complexity/security to the Vigenere cipher system?&nbsp; <a href="https://edstem.org/us/courses/38326/discussion/3208574">See Discussion Question 1 thread.</a>

<h2>Task RSA Warmup (10 points)</h2>
&nbsp;

Now that we’ve reviewed a&nbsp; symmetric key cryptographic algorithm, we can move on to the world of&nbsp; asymmetric key cryptography. RSA is perhaps the best known example of asymmetric cryptography. In RSA, the public key is a pair of integers , and the private key is an integer .

&nbsp;

To encrypt integer m with public key , we use the formula .

To decrypt cipher integer c with private key d, we use the formula .

&nbsp;

In this task you will write the code to perform the encryption and decryption steps for the RSA cryptographic algorithm. Finally, you will write the code necessary to calculate the private key <strong>d</strong> when given the factors of the public key <strong>N</strong> (i.e. <strong>p</strong> and <strong>q</strong>).

&nbsp;

<table>
<tbody>
<tr>
<td width="680">def rsa_decrypt_cipher(n: int, d: int, c: int) -&gt; int:

# TODO: Write the necessary code to get the message (m) from the cipher (c)

m = 0

return m

&nbsp;

def rsa_encrypt_message(m: int, e: int, n: int) -&gt; int:

# TODO: Write the necessary code to get the cipher (c) from the message (m)

c = 0

return c

&nbsp;

def rsa_calculate_private_key(e: int, p: int, q: int) -&gt; int:

# TODO: Write the necessary code to get the private key d from

# the public exponent e and the factors p and q

d = 0

return d
</td>
</tr>
</tbody>
</table>
&nbsp;

Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

Did you try to decrypt a cipher by using a line of Python code something like this: m = c ** d % n? Did it work? (Hint: It did not.) Why not? After all, the math is correct. <a href="https://edstem.org/us/courses/38326/discussion/3208573">See Discussion Question 2 thread.</a>

<h2>Task RSA Factor A 64-Bit Key (10 points)</h2>
&nbsp;

Modern day RSA keys are sufficiently large that it is impossible for attackers to traverse the entire key space with limited resources. But in this task, you’re given a unique set of RSA public keys with a relatively small key size (<strong>64 bits</strong>).

&nbsp;

Your goal is to get the factors (p and q) of each key. <strong>You can use whatever methodology you want.</strong> Your only deliverable is a formatted json file containing p and q. To get your unique set of keys, you must update the task.py file located in the task folder with your 9-digit GT ID, and then run it. Find the section below in the provided <strong>task_factor_64_bit_key.py</strong> file:

&nbsp;

<table>
<tbody>
<tr>
<td width="680">&nbsp; ##############################################

# Change this to your 9-digit Georgia Tech ID!

STUDENT_ID = ‘123456789’

##############################################
</td>
</tr>
</tbody>
</table>
&nbsp;

Running the command “python task_factor_64_bit_key.py” should output your assigned keys. Once you’ve calculated your p and q values, enter them into the function stub for this task. <strong>NOTE:</strong> <strong>It doesn’t matter which value you specify as p and which value you specify as q.</strong>

&nbsp;

<table>
<tbody>
<tr>
<td width="680">def rsa_factor_64_bit_key() -&gt; typing.Dict[str, typing.Dict[str, int]]:

return {

‘test_1’: {

‘p’: 0,

‘q’: 1

},

‘test_2’: {

‘p’: 0,

‘q’: 1

},

‘test_3’: {

‘p’: 0,

‘q’: 1

},

‘test_4’: {

‘p’: 0,

‘q’: 1

},

‘test_5’: {

‘p’: 0,

‘q’: 1

}

}
</td>
</tr>
</tbody>
</table>
<h3></h3>
Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

If 64-bit keys aren’t safe, then what size is appropriate?&nbsp; Is there a trade-off between size and performance? <a href="https://edstem.org/us/courses/38326/discussion/3208567">See Discussion Question 3 thread.</a>

<h2>Task RSA Weak Key Attack (15 Points)</h2>
&nbsp;

Read the paper “Mining Your Ps and Qs: Detection of Widespread Weak Keys in Network Devices”, which can be found at: <a href="https://factorable.net/weakkeys12.extended.pdf">https://factorable.net/weakkeys12.extended.pdf</a>. The essay is essential to understanding this task. Do not skip it, do not skim it, read the whole of it.

&nbsp;

You are given a unique RSA public key, but the RNG (random number generator) used in the key generation suffers from a vulnerability described in the paper above. In addition, you are given a list of public keys that were generated by the same RNG on the same system. Your goal is to write the code to get the unique private key (d) from your given public key (N, e) using only this provided information.

&nbsp;

<table>
<tbody>
<tr>
<td width="680">def rsa_weak_key_attack(given_public_key_N: int, given_public_key_e: int, public_key_list: typing.List[int]) -&gt; int:

# TODO: Write the necessary code to retrieve the private key d from the given public

# key (N, e) using only the list of public keys generated using the same flawed RNG

d = 0

return d
</td>
</tr>
</tbody>
</table>
&nbsp;

Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

Have you ever heard the saying, “Never roll your own crypto?” What are some ways (besides this particular attack – we don’t want you to give too much away) that doing so can cause unintended problems? Can you point to any specific examples or known exploits?&nbsp; <a href="https://edstem.org/us/courses/38326/discussion/3208572">See Discussion Question 4 thread.</a>

<h2>Task RSA Broadcast Attack (15 Points)</h2>
&nbsp;

A message was encrypted with three different 1,024-bit RSA public keys (N_1, N_2, and N_3), resulting in three different ciphers (c_1, c_2, and c_3). All of them have the same public exponent .

&nbsp;

You are given the three pairs of public keys and associated ciphers. Your job is to write the code to recover the original message.

&nbsp;

<table>
<tbody>
<tr>
<td width="680">def rsa_broadcast_attack(N_1: int, c_1: int, N_2: int, c_2: int, N_3: int, c_3: int) -&gt; int:

# TODO: Write the necessary code to retrieve the decrypted message (m) using three different

# ciphers (c_1, c_2, and c_3) created using three different public key N’s (N_1, N_2, and N_3)

m = 0

return m
</td>
</tr>
</tbody>
</table>
&nbsp;

Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

In addition to the low public exponent being used, this attack is possible because a textbook implementation of RSA is being used. In the real world, there are common mitigating tactics used. What are some examples? Why else are they important? <a href="https://edstem.org/us/courses/38326/discussion/3208577">See Discussion Question 5 thread.</a>

&nbsp;

<h2>Task RSA Parity Oracle Attack (15 Points)</h2>
&nbsp;

By now you have seen that RSA treats messages and ciphers as ordinary integers. This means that you can perform arbitrary math with them. And in certain situations a resourceful hacker can use this to his or her advantage. This task demonstrates one of those situations.

&nbsp;

Along with an encrypted message (c), you are given a special function that you can call – a parity oracle. This function will accept any integer value that you send to it and decrypt it with the private key corresponding to the public key that was used to encrypt the given cipher (c). The return value of the function will indicate whether this decrypted value is even (true) or odd (false). Armed with this function and a little modular arithmetic, it is possible to crack the encrypted message. Your goal is to write the code necessary to decrypt the original message (m) from the given cipher (c).

&nbsp;

<table>
<tbody>
<tr>
<td width="680">def rsa_parity_oracle_attack(c: int, N: int, e: int, oracle: Callable[[int], bool]) -&gt; str:

# TODO: Write the necessary code to get the plaintext message from the cipher (c) using

# the public key (N, e) and an oracle function – oracle(chosen_c) that will give you

# the parity of the decrypted value of a chosen cipher (chosen_c) value using the hidden private key (d)

m = 42

&nbsp;

# Transform the integer value of the message into a human readable form

message = bytes.fromhex(hex(int(m_int)).rstrip(‘L’)[2:]).decode(‘utf-8’)

return message
</td>
</tr>
</tbody>
</table>
&nbsp;

Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

This task is a simplified example, but can you see how some potentially useful information may be inadvertently leaked by something (i.e. a protocol)? Can you find any examples? <a href="https://edstem.org/us/courses/38326/discussion/3208581">See Discussion Question 6 thread.</a>

<h2>BONUS: Task Affine Ciphers (+2 points)</h2>
&nbsp;

The affine cipher is a kind of monoalphabetic substitution cipher. In this case, the substitution rule is determined by a simple mathematical formula that relates each letter to its corresponding numerical value. This formula ensures that every letter is encrypted to a unique letter, and can be decrypted back to its original form. Because the affine cipher follows this rule for its substitution, it shares the same vulnerabilities as other substitution ciphers.

&nbsp;

To encrypt a message using the given keyset(a, b) involves the following steps:

&nbsp;

<ol>
<li>Determine the size of the alphabet (m). In most cases, the size of the alphabet is 26 for English letters a to z. However, it could be different if you are using a self-defined alphabet, or adding some special characters.</li>
<li>Map each letter in the alphabet to its corresponding value. Typically, ‘a’ is mapped to 0, ‘b’ to 1, and so on, resulting in a range of integers from 0 to m-1.In some cases, the mapping could start from 1, creating a range from 1 to m.</li>
<li>Select a pair of keys (a, b) to be used in the encryption process. The key ‘a’ must be coprime with the size of the alphabet ‘m’, meaning that their greatest common divisor is 1.</li>
<li>For each letter in the plaintext message, find its corresponding integer value x using table 1.</li>
<li>Apply the affine cipher encryption formula below to compute the encrypted integer value.</li>
</ol>
&nbsp;

&nbsp;

<ol>
<li>Use the calculated integer value to find the letter for the cipher in the alphabet table.</li>
<li>Repeat each letter in the plain text until you get the full cipher text.</li>
</ol>
&nbsp;

To decrypt a cipher using the given keyset(a, b) one reverses the encryption process::

&nbsp;

<ol>
<li>Determine the m, size of the alphabet.</li>
<li>Map each letter in the cipher text to the integer value in the table.</li>
<li>Calculate the multiplicative inverse of ‘a’ modulo ‘m’</li>
<li>Using the decryption formula, get the value for the decrypted letter.</li>
<li>Find the decrypted value corresponding to the letter in the alphabet table.</li>
</ol>
&nbsp;

Decrypt a message by determining the keyset by yourself.

&nbsp;

Decrypt a message by identifying the keyset independently. In this task, the keyset (a, b) is not provided, and you must determine it yourself. Return the plaintext message’s SHA-256 hash for submission. In real-world scenarios, it is highly likely that you won’t know the keyset. If you are aware that the message has been encrypted using the affine cipher, you need to devise a method to obtain the keyset and then decrypt the message.

&nbsp;

<strong>Notes:</strong>

The alphabet in this task will be 29 characters – lowercase a to z, space, comma and period.

The index of a is 0, b is 1…and space is 26, comma is 27, period is 28.

&nbsp;

<table width="606">
<tbody>
<tr>
<td width="100">a</td>
<td width="100">0</td>
<td width="101">k</td>
<td width="102">10</td>
<td width="101">u</td>
<td width="102">20</td>
</tr>
<tr>
<td width="100">b</td>
<td width="100">1</td>
<td width="101">l</td>
<td width="102">11</td>
<td width="101">v</td>
<td width="102">21</td>
</tr>
<tr>
<td width="100">c</td>
<td width="100">2</td>
<td width="101">m</td>
<td width="102">12</td>
<td width="101">w</td>
<td width="102">22</td>
</tr>
<tr>
<td width="100">d</td>
<td width="100">3</td>
<td width="101">n</td>
<td width="102">13</td>
<td width="101">x</td>
<td width="102">23</td>
</tr>
<tr>
<td width="100">e</td>
<td width="100">4</td>
<td width="101">o</td>
<td width="102">14</td>
<td width="101">y</td>
<td width="102">24</td>
</tr>
<tr>
<td width="100">f</td>
<td width="100">5</td>
<td width="101">p</td>
<td width="102">15</td>
<td width="101">z</td>
<td width="102">25</td>
</tr>
<tr>
<td width="100">g</td>
<td width="100">6</td>
<td width="101">q</td>
<td width="102">16</td>
<td width="101"></td>
<td width="102">26</td>
</tr>
<tr>
<td width="100">h</td>
<td width="100">7</td>
<td width="101">r</td>
<td width="102">17</td>
<td width="101">,</td>
<td width="102">27</td>
</tr>
<tr>
<td width="100">i</td>
<td width="100">8</td>
<td width="101">s</td>
<td width="102">18</td>
<td width="101">.</td>
<td width="102">28</td>
</tr>
<tr>
<td width="100">j</td>
<td width="100">9</td>
<td width="101">t</td>
<td width="102">19</td>
<td width="101"></td>
<td width="102"></td>
</tr>
</tbody>
</table>
&nbsp;

Table 1: Index value for each letter.&nbsp; The alphabet size m is 29 as seen in the table.

&nbsp;

<strong>Example:</strong>

To encrypt “hello world.” using keyset (a=2, b=3),&nbsp; the alphabeta is the same as Table 1.

<table width="624">
<tbody>
<tr>
<td width="93"></td>
<td width="36">h</td>
<td width="33">e</td>
<td width="43">l</td>
<td width="35">l</td>
<td width="48">o</td>
<td width="48"></td>
<td width="48">w</td>
<td width="48">o</td>
<td width="48">r</td>
<td width="48">l</td>
<td width="48">d</td>
<td width="48">.</td>
</tr>
<tr>
<td width="93">index</td>
<td width="36">7</td>
<td width="33">4</td>
<td width="43">11</td>
<td width="35">11</td>
<td width="48">14</td>
<td width="48">26</td>
<td width="48">22</td>
<td width="48">14</td>
<td width="48">17</td>
<td width="48">11</td>
<td width="48">3</td>
<td width="48">28</td>
</tr>
<tr>
<td width="93">(ax+b)%29</td>
<td width="36">17</td>
<td width="33">11</td>
<td width="43">25</td>
<td width="35">25</td>
<td width="48">2</td>
<td width="48">26</td>
<td width="48">18</td>
<td width="48">2</td>
<td width="48">8</td>
<td width="48">25</td>
<td width="48">9</td>
<td width="48">1</td>
</tr>
<tr>
<td width="93">Encrypted</td>
<td width="36">r</td>
<td width="33">l</td>
<td width="43">z</td>
<td width="35">z</td>
<td width="48">c</td>
<td width="48"></td>
<td width="48">s</td>
<td width="48">c</td>
<td width="48">i</td>
<td width="48">z</td>
<td width="48">j</td>
<td width="48">b</td>
</tr>
</tbody>
</table>
&nbsp;

The ciphertext is “rlzzc scizjb”

&nbsp;

Useful resources:

Affine cipher Wikipedia:&nbsp; https://en.wikipedia.org/wiki/Affine_cipher

&nbsp;

&nbsp;

Submission Details

&nbsp;

You will write your code in the specified function stubs found in the provided <strong>project_cryptography.py</strong> file. When ready, submit this file to the <strong>Project Cryptography </strong>autograder in Gradescope.

&nbsp;

Open Discussion

&nbsp;

What are some ways that one could add more complexity/security to the Affine cipher system?&nbsp; What are the vulnerabilities? <a href="https://edstem.org/us/courses/38326/discussion/3208587">See Discussion Question 7 thread.</a>

<h2>Important Notes:</h2>
&nbsp;

All necessary starter code and unit tests for each task is located in the corresponding folder in the provided zip file.

&nbsp;

You may import any python packages that are part of the standard library. Some useful ones are already imported for you, and additional ones are not strictly necessary.

&nbsp;

For each task you are also given a unit test file (it starts with test_)to help you develop and test your code. We encourage you to read up on Python unit tests, but in general, the syntax should resemble either:

&nbsp;

python -m unittest test_task_rsa_encrypt_message

&nbsp;

or:

&nbsp;

python test_task_rsa_encrypt_message.py

&nbsp;

However, keep in mind that passing the unit test(s) does NOT guarantee that your code will pass the autograder!

&nbsp;

<strong>The autograder will timeout after 10 minutes.</strong> If your implementation is timing out, then there is very likely something wrong with your implementation. It is possible to solve each task in a few seconds. We encourage you to test locally to avoid unnecessary submissions.

&nbsp;

Gradescope can get very busy and even potentially unavailable near submission deadlines. <strong>Please do not wait until the last minute to make your submissions to the autograder. Submit early and often. <u>There will be no late submissions accepted, as per the syllabus.</u></strong>

<strong><u>&nbsp;</u></strong>

&nbsp;

&nbsp;

<h3>Good luck!</h3>
