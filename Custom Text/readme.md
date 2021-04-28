## Custom Text
if you use https://www.keybr.com/, you can go to settings, advanced from the practice page in order to add your own custom text. I am essentially trying to reduce use of keys which are going to change.

I made my own using an unscrambler and randomly shuffling words. You can use those in [Custom Text folder](/Custom Text)

Still would recommend going to https://monkeytype.com/ to write out actual passages of word which you will use while transitioning.

### Considerations
#### Letters that always stay the same:
Q, W, A, U, I, L, V, 
, . / [ ] ' \

I don't usually include punctuation in my training, though I might for the last one which changes semicolon position.

####  For each stage of TarmakDH mod (ANSI)
Which letters after this change will be in same position as final layout. 

##### Tarmak-DH (ANSI) (1a): N, E, K

So should train on words with Q, W, A, U, I, L, V, N, E, K 

QWAULIVNEK
##### Tarmak-DH (ANSI) (1b): M, H

So should train on words with Q, W, A, U, I, L, V, N, E, K, M, H 

QWAULIVNEKMH

##### Tarmak-DH (ANSI) (2a): X, C, Z,
This is with z mod, so ZXCB change places but only XCZ are in final positions

So should train on words with Q, W, A, U, I, L, V, N, E, K, M, H, X, C, Z

QWAULIVNEKMHXCZ

Due to 12 character limit of unscramble, I essentially did 2 scrambles of
- WAULINEMHXCZ
- QAUIVNEKHXCZ

Removed by lowest [letter frequency](https://www3.nd.edu/~busiforc/handouts/cryptography/letterfrequencies.html): 
- Q, V, K, 
- W, M, L

##### Tarmak-DH (ANSI) (2b): F, B, T

So should train on words with Q, W, A, U, I, L, V, N, E, K, M, H, X, C, Z, F, B, T

QWAULIVNEKMHXCZFBT

1. Based on my keybr learning progress and also that I rarely use QW remove: I N L A & QW

uvekmhxczfbt →  first set of words (very small number generated)

2. Remove by letter frequency Q, V, K, W, L

AUINEMHXCZFBT  → second set of words (much more)

3. added in common words and ngrams


##### Tarmak-DH (ANSI) (3): R, S, D

So should train on words with Q, W, A, U, I, L, V, N, E, K, M, H, X, C, Z, F, B, T, R, S, D

QWAULIVNEKMHXCZFBTRSD

letters to avoid are P J Y O ; L U I 

I want to focus on: RSD for thir change
But also to keep working on HMTFKCZXB

These are 12 letters
RSDHMTFKCZXB

We should add AE as most common vowels so break it up
- RSDTFCZBAE
- RSDHMKCXAE

I only kept unique words then shuffled
##### Tarmak-DH (ANSI) (4): P, J, Y, O, ;

So should train on words with Q, W, A, U, I, L, V, N, E, K, M, H, X, C, Z, F, B, T, R, S, D, P, J, Y, O, ;

QWAULIVNEKMHXCZFBTRSDPJYO;

##### Colemak-DHm (ANSI) z-mod: L, U, I
Basically should just train on full text but might want to do ; coz it has moved along with : (shift ;)

So should train on words with Q, W, A, U, I, L, V, N, E, K, M, H, X, C, Z, F, B, T, R, S, D, P, J, Y, O, ;

QWAULIVNEKMHXCZFBTRSDPJYO;:


### How I generate custom text based on letters
![Custom Text Generation](https://github.com/Caffa/Tarmak-DH-Mac/blob/0f47647d9dad8076ac6f08cd6b277c80474a408f/My%20gifs/output_optimized.gif)
1. Generate text using [unscrambler](http://www.allscrabblewords.com/unscramble/qwaulivnek)
2. Shuffle words using [random shuffler](https://onlinerandomtools.com/shuffle-words)


Also put in [top n-grams](http://norvig.com/mayzner.html) and top words
