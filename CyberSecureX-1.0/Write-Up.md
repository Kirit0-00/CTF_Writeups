
# Web

## Challenge Name : The Acme Corp

The flags are in segmented format :

The first part was found in client side html code :  
```html
<!-- build artifact:
       [1/5]=S3GM
       (note to self: admin panel moved, TODO remove robots entries)
  -->
```

The Second part was in style.css :
```css
/* build note:
   [2/5]=3NT_
*/
```

The third part was in app.js :
```text
build scratchpad:
   The release engineer left fragments here but reversed to be "compact":
   ]'3/5[' = ]'3R0F'[  // reversed Correct : F0R3
  */
```

The fourth part was in robots.txt :
```note
audit note:
# [4/5]=NS1C
```

The fifth part was in .htaccess :
```
#[5/5]=S
```
Final Flag : `flag{S3GM3NT_F0R3NS1CS}` **S was missing in the part**

# Crypto

## Shadows in the Wall 

We got a hex encoded text :
`2E2525233E233C3C31201E203D0C3D2F2D0B232C3D39`

First decode this from hex
Then from description we take first letter of each sentence then formed the key for **XOR**
which is `HIDDENINPLAINSIGHT`

flag : `flag{mural_is_the_key}`

## x^2+y^2=5 

This is a jsfive code 
```js
[$$=[+[]]]+[$$[++[[]][+[]]]=+[]]+[$$=[$$+[]][+[]][++[[]][+[]]]]+[$$$=[$[[[]+[][+[]]][+[]][++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+[[]+[][+[]]][+[]][++[++[[]][+[]]][+[]]]]+[]][+[]]]+[$$$$=[$[[[]+[][+[]]][+[]][++[++[[]][+[]]][+[]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+[[]+[][+[]]][+[]][++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[++[++[++[[]][+[]]][+[]]][+[]]]+$$$[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[[]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]][[[]+[][+[]]][+[]][++[++[[]][+[]]][+[]]]+$$$[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+[[]+[][+[]]][+[]][++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]]]][+[]][+[]]]+[$$$$$=$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[++[[]][+[]]]+$$$[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[+[]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]]]+[$$$$[$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[+[]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[++[++[++[[]][+[]]][+[]]][+[]]]+$$$[++[[]][+[]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+$$$[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]][$$$[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[++[[]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]]][[[]+[][+[]]][+[]][++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[+[]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]]]+=$$$$[$$$$$][+[]]+[[]+[][+[]]][+[]][++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[[]][+[]]][+[]]][+[]]]+$$$[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$$[$$$$$][++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$$[$$$$$][++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[[]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$[$$$[++[++[++[[]][+[]]][+[]]][+[]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[[]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[[]][+[]]]+$$$[++[++[++[[]][+[]]][+[]]][+[]]]+$$$[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]][[[]+[][+[]]][+[]][++[[]][+[]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+[[]+[][+[]]][+[]][++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[[]][+[]]][+[]]]+[+[]]]]+$$$[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[++[[]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[[]][+[]]][+[]]]+[+[]]]]+$$$[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[[]+[][+[]]][+[]][++[++[[]][+[]]][+[]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]]+$$$[+[[++[[]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]]+[[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+[+[]]]][+[]]+$$+[+[[++[++[++[[]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[++[++[[]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[++[++[++[[]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[++[[]][+[]]][+[]]]+[++[++[++[[]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[+[]]]][+[]]+$$+[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+[++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[+[]]+[+[]]]][+[]]+$$+[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[[]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[[]][+[]]]+[++[++[[]][+[]]][+[]]]+[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[[]][+[]]][+[]]][+[]]]+[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]]][+[]]+$$+[+[[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]]+[++[[]][+[]]]]][+[]]][+[]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[+[]]]]+$$$[+[[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]]+[+[]]]]+$$$$[$$$$$][++[++[++[++[++[++[++[++[[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+$$$$[$$$$$][+[[++[[]][+[]]]+[++[[]][+[]]]+[+[]]]]]
```

on putting this on this website : https://aem1k.com/five/

We got the flag : `flag{You_are_a_1337_d3c0d3r}`

## Secret Message

I attempted to implement RSA encryption with small values for simplicity. Can you help me decrypt the ciphertext? The parameters are: n=3233 e=17 c=1306 Find the original plaintext message. Submit your answer in the format: Solve this
The above was the description that it is a RSA challenge.. I gave chatgpt to write a script for to extract the correct number from above values:
```python
# RSA decryption example

# Given parameters
n = 3233
e = 17
c = 1306

# Step 1: Factor n = p * q
p = 61
q = 53

# Step 2: Compute phi(n)
phi = (p - 1) * (q - 1)

# Step 3: Compute modular inverse of e mod phi(n)
def mod_inverse(a, m):
    # Extended Euclidean Algorithm
    t, new_t = 0, 1
    r, new_r = m, a
    while new_r != 0:
        quotient = r // new_r
        t, new_t = new_t, t - quotient * new_t
        r, new_r = new_r, r - quotient * new_r
    if r > 1:
        raise ValueError("No inverse exists")
    if t < 0:
        t += m
    return t

d = mod_inverse(e, phi)

# Step 4: Decrypt ciphertext
m = pow(c, d, n)

print("Decryption exponent d:", d)
print("Plaintext message m:", m)

## Plain Text: 1337
```
flag : `flag{1337}`

## Factor's

From factor.db I found the p and q 
In dcode.fr/rsa site I put all the values 

```
n = 408579146706567976063586763758203051093687666875502812646277701560732347095463873824829467529879836457478436098685606552992513164224712398195503564207485938278827523972139196070431397049700119503436522251010430918143933255323117421712000644324381094600257291929523792609421325002527067471808992410166917641057703562860663026873111322556414272297111644069436801401012920448661637616392792337964865050210799542881102709109912849797010633838067759525247734892916438373776477679080154595973530904808231
e = 65537
c = 321032879323205327725702473173186126139806349977995355851770555368773987337788381305330715691451675233822332788148678876695658947721063822106013968982141117811060606096601702756749928977440152428256556701812213214485306880463012248237572289090239204812320882132872241252415408250039824898913320655846342475805127699401297961693171893817378737598710752083615027737006555198517143730812880793088207442754977911029461994184058346013879033290267049619197891732832973720711195278508885239645327100743130


p = 15485863
q = 263840088670917452946333545478352127416914166730974445948719617086068982461916312849228659410121241843272432475145625757 500575308088875898098480894611741004217089821840822946755005773362259577979888187213725467491313808765661376070363014734 357640316590852761599094472558243169917315597762816959190564269902851202779503255987007705881523305657745462196113601677 479009675113787095763660567278662393597444843430993224406744340208742005940410339262025789415089695962293981599655815213 26643115137
```

Then I got the flag : `flag{kiet_sh0uld'v3_t4k3n_b1gg3r_pr1m3s_xd}`

## Math 

I was trying to implement RSA encryption again. I learnt my lesson from last time, so I'm not just using simple numbers... Can you help me recover the message? Here's what I used: n = 12407072677633161347 e = 65537 c = 6680131599371095691

Again I tried in factor.db and tried to factorise and n and got p

`p=3078160451`

Then while in dcode.fr/rsa it was giving some random number : 727361
After trying to understand it I tried to divide then into pair(1 byte) which hex values give me : rsa (got from cyberchef.io)

FLAG: `flag{rsa}`
## clean_secrets 

Using this script from AI I decrypt the flag as only first some parts are flag and then padding was there 
```python
# RSA signature verification and ASCII character output

e = 65537
n = 29272211185791337470601459865547915572705405074737448165554838548593414777186862322360266396503949588399211978684110028692178124348659022347925865586858857745046980867426705555580364865219468822048313765397195531031542876514446065112877624125765279978999006068867591708338040814923453793785950485219534236427095229380429852683155646321025259419045010795522308637833753510147498752683522318021290578396732008492148002481783070584916418311934016850189529538209785082364073383572848357382062832206142447578010522255643508500605964292519075059674070329541053216687386862501985569949181471733055512716848634213404812305467
sign = 28823527877009404391788009303283758068711379074425201137344940811998934078583167587041482766136924878930695190381296276633373217706755888004430290379533125655122691697171011539214176791406923545245432013886712782232147882041317072208170830413141936709786452545173666025140566880221801368817252874213105392976532941665834879566180285905133499823156214691343651581978074424317672823183441938255275518500290759593740726421853728061784549242702675311865773009409195146565935528082068227978113561192763132802645856604678491872926128999509590907870281571659146454537850484613719932986098559922816859832679101469594354477869

# Step 1: RSA public operation (decode signature)
decoded = pow(sign, e, n)

# Step 2: Convert to bytes
decoded_bytes = decoded.to_bytes((decoded.bit_length() + 7) // 8, 'big')

# Step 3: Print each byte as integer and character (if printable)
for b in decoded_bytes:
    if 32 <= b <= 126:  # printable ASCII range
        print(f"{b} -> '{chr(b)}'")
    else:
        print(f"{b} -> (non-printable)")
'''
102 -> 'f'
108 -> 'l'
97 -> 'a'
103 -> 'g'
123 -> '{'
105 -> 'i'
109 -> 'm'
95 -> '_'
115 -> 's'
101 -> 'e'
97 -> 'a'
114 -> 'r'
99 -> 'c'
104 -> 'h'
105 -> 'i'
110 -> 'n'
103 -> 'g'
95 -> '_'
102 -> 'f'
111 -> 'o'
114 -> 'r'
95 -> '_'
97 -> 'a'
95 -> '_'
110 -> 'n'
101 -> 'e'
119 -> 'w'
95 -> '_'
104 -> 'h'
97 -> 'a'
115 -> 's'
104 -> 'h'
105 -> 'i'
110 -> 'n'
103 -> 'g'
95 -> '_'
102 -> 'f'
117 -> 'u'
110 -> 'n'
99 -> 'c'
116 -> 't'
105 -> 'i'
111 -> 'o'
110 -> 'n'
125 -> '}'

'''
```

flag:  `flag{im_searching_for_a_new_hashing_function}`

# Forensics 

## Echoes in the Deep

We are given a .zip file but when playing with `aplay` it was hinting for morse code

So change the extension from .zip to .wav and in any morse code decoder put it:

flag: `flag{s1gn4ls_fr0m_th3_d33p}`

## Fractured Truth 

We are given a bunch of parts of a qr code...

We have to manually place it in correct order and scan to get the flag..

After a lot of trial and error I found the correct combination...

flag: `flag{puzzl3d_qr_c0mpl3t3`

## Capture 1 

We are given a pcapng file....

While exploring all protocols in **ICMP** protocol I found something dot,space,dash...

So I extracted all the packets
```bash
──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ tshark -r cap1.pcapng -Y "icmp" -T fields -e data | xxd -r -p 

␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567dotdotdashdotspacedotdashdotdotspacedotdashspacedashdashdotspacespacespacedashspacedotdot␦1234567␦1234567dotdashdashspacedotdashdotdotspacedotdotdotdashdashspacedashdashdotspacedotdashdotspacedotdotdotdotdashspacedashdashspacespacespacedotdotdashdotspacedashspacedotdashdashspacespace␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567␦1234567      
```

Then replacing with the corresponding symbols we got :
` ..-. .-.. .- --. - ...-- .-.. ...-- --. .-. ....- -- ..-. - .--`

Flag : FLAGT3L3GR4MFTW                    `flag{t3l3gr4m_ftw}`

## Capture 2

I opened the file.pcapng with wireshark and analysed every protocols TCP,UDP,QUIC,ICMPv6... but got nothing..

Then while filtering I found something wrong with **ARP** packets, a huge number of arp packets are originating from same source.

![](Pasted%20image%2020250905161909.png)

So using Tshark I extracted all ARP packets 

```bash
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ tshark -r file.pcapng -Y arp -T fields -e arp.src.proto_ipv4 \
  | awk -F. '{print $4}' \
  | while read n; do printf "\\$(printf '%03o' $n)"; done
echo

�	�	�	�	�	�	�	�	hahatryagainbaby�	��	�	�	�	�	flag{addr3ss_res0lv3d_bu7_n0t_issues}�	---> Got the flag

```

# Misc

## Plug and Play

Here we are given a windows2000 ova file... and told that there is shady driver its IOCTL handler leaks secrets if you poke it the right way.

So after opening the VM file I search for a tool WinObj which allows us to view drivers as objects in windows...

In that I found a driver named as leakydrv...

Every drive has its own `.sys`(System file), So I search for it and found it...

And on doing `strings` we got this flag...

![](Pasted%20image%2020250905161910.jpg)

## OG

After downloading the file I searched in ChatGPT , it gave me this tool : https://ncviewer.com/?utm_source=chatgpt.com

![](Pasted%20image%2020250905215338.png)

The string was `W9gt5z7h`  After searching a lot I found out that this was a pastebin endpoint..

In that another gcode was there 
![](Pasted%20image%2020250905220234.png)

FLAG : `flag{G_m4n_h3he}`

## The Archivist's Riddle 

```bash
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ cat pass.txt    
0h9bJv1@T
r8N$!zK2p
7eY&wQ3xL
5dU*aM4cA
l6F#bG5iZ
83hfb^pl0
@dj13e890
kdow#pdo8

                                                                                                                                                                            
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ cat riddel.txt 
I have cities, but no houses.
I have mountains, but no trees.
I have water, but no fish.
I contain the essence of all, yet reveal none.

What am I?

My final word is a key, but it unlocks no lock.
                                                                                                                                                                            
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ strings encrypted.bin| grep flag
this_is_not_the_real_flag_or_password
                                                                                                                                                                            
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ file challange.zip                                                                                                   
challange.zip: POSIX shell script executable (binary data)

```

I found that the zip file is POSIX shell script..

Using strings I got this:
```bash
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ strings challenge| grep flag 
?@@@	@@@@@@@ @@(@@this_is_not_the_real_flag_or_passwordAuthentication successful. The key to the next step is not here.Authentication failed. The key you seek is elsewhere.Enter the secret key: 
?@@@	@@@@@@@ @@(@@this_is_not_the_real_flag_or_passwordAuthentication successful. The key to the next step is not here.Authentication failed. The key you seek is elsewhere.Enter the secret key: 
echo "flag{executing...'b
?@@@	@@@@@@@ @@(@@this_is_not_the_real_flag_or_passwordAuthentication successful. The key to the next step is not here.Authentication failed. The key you seek is elsewhere.Enter the secret key: 
this_is_not_the_real_flag_or_passwordAuthentication
```

Then we contacted OC about what or where is the other part of the flag : 

So they provided us with the full flag:
`flag{executing_the_truth}`

## Web_access

In this we are given web_access zip file which was password protected....
I got to know that the password is a pangram :
So I searched internet which are famous pangrams it gave me this : `thequickbrownfoxjumpsoverthelazydog`

Then I got a web_access.log file in which find sql injection was going on... using SUBSTRING which contains the flag:
```bash
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ less web_access.log | grep -i substring
192.168.0.92 - - [10/02/2024:01:32:28 +0000] "GET /search?id=1' OR SUBSTRING((SELECT f),1,1)='f' --  HTTP/2" 200 894 "-" "Safari/537.36"
192.168.0.198 - - [09/04/2024:02:29:55 +0000] "GET /search?id=1' OR SUBSTRING((SELECT l),1,1)='l' --  HTTP/2" 403 4945 "-" "Chrome/91.0"
192.168.0.61 - - [27/06/2024:16:37:05 +0000] "GET /search?id=1' OR SUBSTRING((SELECT a),1,1)='a' --  HTTP/1.1" 500 1274 "http://test.com" "Safari/537.36"
192.168.0.88 - - [09/01/2024:23:01:49 +0000] "GET /search?id=1' OR SUBSTRING((SELECT g),1,1)='g' --  HTTP/2" 404 3747 "http://test.com" "Mozilla/5.0"
192.168.0.172 - - [14/02/2024:02:19:58 +0000] "GET /search?id=1' OR SUBSTRING((SELECT {),1,1)='{' --  HTTP/1.1" 500 4438 "http://test.com" "Safari/537.36"
192.168.0.97 - - [08/03/2024:12:02:23 +0000] "GET /search?id=1' OR SUBSTRING((SELECT s),1,1)='s' --  HTTP/2" 403 4226 "http://test.com" "Chrome/91.0"
192.168.0.78 - - [19/04/2024:05:04:51 +0000] "POST /search?id=1' OR SUBSTRING((SELECT q),1,1)='q' --  HTTP/1.1" 403 2959 "http://test.com" "Mozilla/5.0"
192.168.0.58 - - [05/04/2024:06:16:35 +0000] "GET /search?id=1' OR SUBSTRING((SELECT l),1,1)='l' --  HTTP/1.1" 200 1225 "http://test.com" "Mozilla/5.0"
192.168.0.34 - - [18/04/2024:04:31:29 +0000] "POST /search?id=1' OR SUBSTRING((SELECT _),1,1)='_' --  HTTP/2" 200 1803 "http://test.com" "Chrome/91.0"
192.168.0.37 - - [15/12/2024:17:32:47 +0000] "GET /search?id=1' OR SUBSTRING((SELECT i),1,1)='i' --  HTTP/1.1" 500 3193 "http://example.com" "Mozilla/5.0"
192.168.0.244 - - [27/02/2024:19:30:23 +0000] "GET /search?id=1' OR SUBSTRING((SELECT n),1,1)='n' --  HTTP/2" 500 4301 "-" "Safari/537.36"
192.168.0.141 - - [28/10/2024:03:57:13 +0000] "POST /search?id=1' OR SUBSTRING((SELECT j),1,1)='j' --  HTTP/2" 500 3596 "http://test.com" "Safari/537.36"
192.168.0.189 - - [14/11/2024:14:42:26 +0000] "POST /search?id=1' OR SUBSTRING((SELECT e),1,1)='e' --  HTTP/1.1" 200 340 "http://test.com" "Mozilla/5.0"
192.168.0.49 - - [17/08/2024:20:31:58 +0000] "GET /search?id=1' OR SUBSTRING((SELECT c),1,1)='c' --  HTTP/2" 200 792 "-" "Chrome/91.0"
192.168.0.48 - - [05/04/2024:16:22:20 +0000] "POST /search?id=1' OR SUBSTRING((SELECT t),1,1)='t' --  HTTP/2" 500 3490 "-" "Safari/537.36"
192.168.0.229 - - [19/05/2024:14:18:57 +0000] "POST /search?id=1' OR SUBSTRING((SELECT i),1,1)='i' --  HTTP/1.1" 200 2023 "http://example.com" "Safari/537.36"
192.168.0.120 - - [14/05/2024:06:08:46 +0000] "GET /search?id=1' OR SUBSTRING((SELECT 0),1,1)='0' --  HTTP/1.1" 500 3977 "-" "Mozilla/5.0"
192.168.0.73 - - [13/05/2024:16:56:30 +0000] "GET /search?id=1' OR SUBSTRING((SELECT n),1,1)='n' --  HTTP/2" 200 1491 "-" "Chrome/91.0"
192.168.0.104 - - [08/01/2024:11:23:36 +0000] "GET /search?id=1' OR SUBSTRING((SELECT _),1,1)='_' --  HTTP/2" 404 256 "http://example.com" "Chrome/91.0"
192.168.0.16 - - [16/05/2024:09:58:15 +0000] "POST /search?id=1' OR SUBSTRING((SELECT a),1,1)='a' --  HTTP/1.1" 403 1323 "http://test.com" "Chrome/91.0"
192.168.0.125 - - [17/01/2024:21:37:43 +0000] "POST /search?id=1' OR SUBSTRING((SELECT t),1,1)='t' --  HTTP/1.1" 404 3895 "-" "Safari/537.36"
192.168.0.179 - - [28/06/2024:07:43:49 +0000] "GET /search?id=1' OR SUBSTRING((SELECT t),1,1)='t' --  HTTP/2" 500 2308 "http://test.com" "Mozilla/5.0"
192.168.0.172 - - [07/07/2024:10:06:35 +0000] "POST /search?id=1' OR SUBSTRING((SELECT a),1,1)='a' --  HTTP/1.1" 404 379 "http://example.com" "Mozilla/5.0"
192.168.0.65 - - [16/11/2024:17:46:12 +0000] "POST /search?id=1' OR SUBSTRING((SELECT c),1,1)='c' --  HTTP/1.1" 404 1013 "http://example.com" "Safari/537.36"
192.168.0.139 - - [02/08/2024:00:50:50 +0000] "GET /search?id=1' OR SUBSTRING((SELECT k),1,1)='k' --  HTTP/1.1" 404 4126 "http://test.com" "Safari/537.36"
192.168.0.190 - - [28/04/2024:09:28:59 +0000] "GET /search?id=1' OR SUBSTRING((SELECT }),1,1)='}' --  HTTP/2" 404 2570 "http://test.com" "Chrome/91.0"
```
FLAG : `flag{sql_injecti0n_attack}`

## EXCELient

In this we are provided with an excel file `user.xlsx` that hints that there are hidden sheets present 

Then there was a sheet named as FLAG

Then I asked to Chatgpt how unhide the sheets then I got to know that with right clicking on any sheet we can unhide the sheets...

Then I unhide all the sheets and got fragments of flag : `FLAG{SHEET_425`

But in Calc 2 formula was not working I did it manually : formula : `=CHAR(INDEX(A2:A100,8))&CHAR(INDEX(A2:A100,2))&CHAR(INDEX(A2:A100,3))&CHAR(INDEX(A2:A100,4))&CHAR(INDEX(A2:A100,5))&CHAR(INDEX(A2:A100,3))&CHAR(INDEX(A2:A100,6))&CHAR(INDEX(A2:A100,7))`

Then the string I got is broken but I guessed it should be _SORCERY_ from other parts..

So the flag is `flag{sheet_sorcery_425}`

# OSINT

## Three_day_invasion (200 Points)

Pretty simple, just reverse search the image, you will get it in X(formerly
twitter)

![Screenshot_2025-09-05_17_23_35.png](6c185b9f-5a53-4ba8-ad8b-3146faaabe37.png)

Flag: flag{jembobineuse}

## Lost in Dusts (300 Points)

Reverse search on google, it’s sandwedges in Ghaziabad

![Screenshot_2025-09-05_17_26_56.png](82f969de-a065-4096-a83d-2eb9a8ae1b3f.png)

Pretty classic, went to google map reviews, sorted by newest and found the
flag in recent review

Flag: flag{rusted_lotus_47}

## Just Search It Writeup

so today we are going to discuss about the CTF  OSINT challenge of just search it (points - 200) organized by cybersecure

At First we got this webp file showing a bunch of people attending a session and if we carefully look in the bottom left we can see the sign says something like __con. 

1. First i copy pasted the code in the screen in github but no luck
2. second when i tried to read the code there a [file.rs](http://file.rs) mentioned and i search it and i get to know it is a rust program  

 
![challenge.png](challenge.png)


### The Rust Code

```
error[E0308]: mismatched types
  --> file.rs:3:9
   |
3  |   foo(&x);
   |   ^^^^ expected usize, found u32
   |
   = note: expected type `&usize`
              found type `&u32`
error: aborting due to previous error
```

if we look carefully there a speaker discussing this rust code with an audience ..the poster where the speaker is cropped but we can identify its a Con as in defcon nullcon conferences .. i started searching for every type of conf and started searching their stage image no luck finding any match but i searched for RUSTCON and just a bit of guess regarding the A in the image i went with “RUSTCON ASIA” and yeh same to same stage images 

  

![Screenshot_2025-09-05_17_01_09.png](6bc0f6b9-48c5-41fc-84ea-e58355ae225f.png)

# Youtube Video 0f RUSTCON 2019

![Screenshot_2025-09-05_17_03_25.png](178aef95-b4f1-4ecd-9f4c-0470f490d66c.png)

Got to Know the speaker is Nick cameron and he has a github profile….

![Screenshot_2025-09-05_17_05_25.png](7bde344d-6a90-4143-88a0-3de0b7bc3166.png)

after that i just searched “flag{” and found the flag pushed in issues 

![Screenshot_2025-09-05_17_07_06.png](989da22e-37a2-4e38-856c-6cd19bdddaf0.png)

*flag*{f0und_th3_s0urc3_l1k3_a_b0ss}

## Trained Few

While searching for this I went to kiet_edu instagram profile, there I saw two batches about cybersecure-x training : (ExploitEdge BootCamp)

First one has 96 students and second one has 65...

So flag is : `flag{161}`

## BUMBLLEBEE-2

I was there in the previous ctf, So I knew about the OS that `ethical_buddy` has made which had name as the challenge.

So I went to his github repo , where I saw recent commit which was only 16h ago... So when I viewed that commit I found the flag...

https://github.com/ethical-buddy/ethical-buddy/commit/350bc5b37a79c1acbd9803b0d52139fc5cd17ed7

`flag{Y3S_1_U5E_4i_to_hack}`

## Brainrot

In this I break the strings into two parts "c2hhcmQtMg== "  and "_4db3b07f-23d8-4322-a4bd-484628587a0f" 

The first string when I searched in google I got a grok publicly shared chat and when I opened it and looked in its url I find that the another string was its chat id...

So I changed the id to the given id and got two base64 encoded strings:
`ZmxhZ3tPU0lOVF9odW50ZXJzX2ZpbmRfd2hhdCdzX2hpZGRlbl81ZjlhMWN9Cg==`
This one was the flag...
flag : `flag{OSINT_hunters_find_what's_hidden_5f9a1c}`

# Steganography

## Layers of Silence (200 Points)

Another classic challenge, from hints in challenge description, I knew it would
be LSB, so I used zsteg. Found encrypted text

![Screenshot_2025-09-05_17_31_25.png](1fd9eafc-c2a1-47a5-8636-ce217df1a29f.png)

it was Base 58, so converted

![Screenshot_2025-09-05_17_32_52.png](3783caea-b3a5-4cf0-8bbe-9cd5b5238792.png)

Flag: flag{STEREO_SECRET}

## Hidden Whispers

We got a wall.jpg file...  As the challenge is stego and file is .jpg so it will be solved by _steghide_

But we do not know the passphrase, but we can bruteforce it by using tool `stegcracker`

```bash
──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ stegcracker wall.jpg /usr/share/wordlists/rockyou.txt   
StegCracker 2.1.0 - (https://github.com/Paradoxis/StegCracker)
Copyright (c) 2025 - Luke Paris (Paradoxis)

StegCracker has been retired following the release of StegSeek, which 
will blast through the rockyou.txt wordlist within 1.9 second as opposed 
to StegCracker which takes ~5 hours.

StegSeek can be found at: https://github.com/RickdeJager/stegseek

Counting lines in wordlist..
Attacking file 'wall.jpg' with wordlist '/usr/share/wordlists/rockyou.txt'..
Successfully cracked file with password: 123456
Tried 1 passwords
Your file has been written to: wall.jpg.out

```
FLAG: `flag{E4SY_ST3G_UNL0CK3D}`

## Nom Nom Nom

Some memories hide between the lines. Check the margins.

In `exiftool` I found this :
```bash
┌──(kirit0_㉿m4ch1n3)-[~/CTF/cybersecure2.0]
└─$ exiftool old_photo.jpg                                                 
ExifTool Version Number         : 13.25
File Name                       : old_photo.jpg
Directory                       : .
File Size                       : 86 kB
File Modification Date/Time     : 2025:08:29 23:24:05+05:30
File Access Date/Time           : 2025:09:05 21:13:03+05:30
File Inode Change Date/Time     : 2025:09:05 21:12:56+05:30
File Permissions                : -rw-r--r--
File Type                       : JPEG
File Type Extension             : jpg
MIME Type                       : image/jpeg
JFIF Version                    : 1.01
Profile CMM Type                : Little CMS
Profile Version                 : 2.1.0
Profile Class                   : Display Device Profile
Color Space Data                : RGB
Profile Connection Space        : XYZ
Profile Date Time               : 2012:01:25 03:41:57
Profile File Signature          : acsp
Primary Platform                : Apple Computer Inc.
CMM Flags                       : Not Embedded, Independent
Device Manufacturer             : 
Device Model                    : 
Device Attributes               : Reflective, Glossy, Positive, Color
Rendering Intent                : Perceptual
Connection Space Illuminant     : 0.9642 1 0.82491
Profile Creator                 : Little CMS
Profile ID                      : 0
Profile Description             : c2
Profile Copyright               : FB
Media White Point               : 0.9642 1 0.82491
Media Black Point               : 0.01205 0.0125 0.01031
Red Matrix Column               : 0.43607 0.22249 0.01392
Green Matrix Column             : 0.38515 0.71687 0.09708
Blue Matrix Column              : 0.14307 0.06061 0.7141
Red Tone Reproduction Curve     : (Binary data 64 bytes, use -b option to extract)
Green Tone Reproduction Curve   : (Binary data 64 bytes, use -b option to extract)
Blue Tone Reproduction Curve    : (Binary data 64 bytes, use -b option to extract)
Current IPTC Digest             : 05a9a5f0e096c9c20a73d2fe6f7e7a1d
Copyright Notice                : Grafner | Dreamstime.com
Application Record Version      : 4
XMP Toolkit                     : Image::ExifTool 11.88
Licensor URL                    : https://www.dreamstime.com
Web Statement                   : https://www.dreamstime.com/about-stock-image-licenses
Exif Byte Order                 : Big-endian (Motorola, MM)
X Resolution                    : 72
Y Resolution                    : 72
Resolution Unit                 : inches
Y Cb Cr Positioning             : Centered
Copyright                       : Grafner | Dreamstime.com
Exif Version                    : 0232
Components Configuration        : Y, Cb, Cr, -
User Comment                    : Rk1ZU01MQ0FOQjVXWTJKRU9aU0hZNVJFTk5XRUU9PT0=
Flashpix Version                : 0100
Color Space                     : Uncalibrated
Image Width                     : 800
Image Height                    : 534
Encoding Process                : Progressive DCT, Huffman coding
Bits Per Sample                 : 8
Color Components                : 3
Y Cb Cr Sub Sampling            : YCbCr4:2:0 (2 2)
Image Size                      : 800x534
Megapixels                      : 0.427

```

Using CyberChef's Magic tool first it decode to Base64 then to Base32 
After that I tried various decoding methods, in which I got the flag in ROT47 Bruteforce
```
Amount = 56: ci^dxBUFC\P>VP\EFz
Amount = 57: dj_eyCVGD]Q?WQ]FG{
Amount = 58: ek`fzDWHE^R@XR^GH|
Amount = 59: flag{EXIF_SAYS_HI}
Amount = 60: gmbh|FYJG`TBZT`IJ~
Amount = 61: hnci}GZKHaUC[UaJK!
Amount = 62: iodj~H[LIbVD\VbKL"
```
FLAG: `flag{EXIF_SAYS_HI}`

## Sanity Check

From hint I got to know that its present in voice chat `general`

`flag{entered_th3_m3tr4x}`
![](Pasted%20image%2020250905230220.png)
