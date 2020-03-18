# The St. Petersburg Paradox

*First published Tue Jul 30, 2019*

The St. Petersburg paradox was introduced by Nicolaus Bernoulli in 1713. It continues to be a reliable source for new puzzles and insights in decision theory.

The standard version of the St. Petersburg paradox is derived from the St. Petersburg game, which is played as follows: A fair coin is flipped until it comes up heads the first time. At that point the player wins $\$2^n$ where n is the number of times the coin was flipped. How much should one be willing to pay for playing this game? Decision theorists advise us to apply the principle of maximizing expected value. According to this principle, the value of an uncertain prospect is the sum total obtained by multiplying the value of each possible outcome with its probability and then adding up all the terms (see the entry on normative theories of rational choice: expected utility). In the St. Petersburg game the monetary values of the outcomes and their probabilities are easy to determine. If the coin lands heads on the first flip you win $2, if it lands heads on the second flip you win $4, and if this happens on the third flip you win $8, and so on. The probabilities of the outcomes are $\frac{1}{2}$, $\frac{1}{4}$, $\frac{1}{8}, \ldots$. Therefore, the expected monetary value of the St. Petersburg game is

$
	\begin{aligned}
	\frac{1}{2}\cdot 2 + \frac{1}{4}\cdot 4 + \frac{1}{8}\cdot 8 + \cdots
	&=& 1+1+1+ \cdots \\
	&=& \sum_{n=1}^{\infty} \left(\frac{1}{2}\right)^n \cdot 2^n \\
	&=& \infty.
	\end{aligned}
$

(Some would say that the sum approaches infinity, not that it is infinite. We will discuss this distinction in Section 2.)

The “paradox” consists in the fact that our best theory of rational choice seems to entail that it would be rational to pay any finite fee for a single opportunity to play the St. Petersburg game, even though it is almost certain that the player will win a very modest amount. The probability is \$\frac{1}{2}$ that the player wins no more than $2, and $\frac{3}{4}$ that he or she wins no more than $4.

In a strict logical sense, the St. Petersburg paradox is not a paradox because no formal contradiction is derived. However, to claim that a rational agent should pay millions, or even billions, for playing this game seems absurd. So it seems that we, at the very least, have a counterexample to the principle of maximizing expected value. If rationality forces us to liquidate all our assets for a single opportunity to play the St. Petersburg game, then it seems unappealing to be rational.