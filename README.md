# Cunningham-chain-locator
A simple HTML calculator that identifies where a given prime number appears within a Cunningham chain.

A Cunningham chain consists of prime numbers such that for each prime p, except the last, 2*p* + 1 is also prime (and is thus a Sophie Germain prime). Or, for each prime *p*, except the first, (*p* − 1)/2 is also prime (and is thus a safe prime). A prime that is neither a Sophie Germain prime nor a safe prime trivially forms a Cunningham chain of length 1. Chains of length 2 or greater are more interesting, in my opinion.

The On-Line Encyclopedia of Integer Sequences (OEIS) is a very valuable reference, and it contains many useful entries pertaining to Cunningham chains. But this page, being specifically about Cunningham chains, can offer a little more interactivity by letting users enter prime numbers and see if those prime numbers appear in a chain of length 2 or greater.

Furthermore, the page should report the chain regardless of whether the entered prime appears at the beginning, the end or somewhere in between.
