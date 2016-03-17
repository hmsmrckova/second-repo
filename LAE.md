---
author:
- |
    Takumin Wang 100131\
    Hana Marie Smrckova 537009
title: Law and Economics written assignment
...

Tort Liability
==============

(a) First-best precaution: Social Planer’s Cost Minimization is
    $$x^*=\arg\min_x c_I+h=x+h(x,\upsilon)=\arg\min_x x+10\upsilon{e^{-x}}$$*where
    $c_I$ represents costs of precaution for the injurer.*
    $$FOC: 1 -p10\upsilon{e^{-x}}=0$$ $$x^*=ln10p\upsilon=ln5p$$

(b) Standard of due care under a simple negligence rule should be set at
    $x^*=ln5p$. If the standard is set on the socially optimal level,
    the injurer is motivated to undertake this precaution in order to
    avoid liability. $$C_I=\begin{cases}
            x+h(x,v)p & ,x<x^* \\
            x & ,x\geq x^*
            \end{cases}$$ $$x^*=\arg\min C_I$$

(c) If there are two types of injurers with different probability of
    accident $0<p_l<1/5<p_h<1$, the efficient levels of care
    $x_t\in\{l,h\}$ are $x^*=ln5p_t$.
    $$\min_{x_h, x_l} E(c_I+h)=E(x_t+h(x_t,\upsilon))=1/2[x_h+h(x_h,\upsilon)]+1/2{x_l+h(x_l,\upsilon)}$$
    $$FOC: x^*_t=ln5p_t , t \in \{l,h\}$$

(d) Strict liability do this work and force injurer to internalize the
    social costs. In other words, by setting the strict liability rule,
    the cost function of injurer becomes identical to the social
    cost function. Thus, strict liability solves the problem of public
    unobservability of injurer’s type since injurer who knows her type
    privately minimize (social) costs.\
    Each type of an injurer solves:
    $$\min_{x{_t}} c_I+h=x_t+h(x_t,\upsilon)$$
    $$FOC: x^*_t=ln5p_t \textit{ (FB)}$$

(e) Efficiency requires that all types of victims greater than
    $\bar{\upsilon}=\frac{2c}{5(p_he^{-x_h^*}+p_le^{-x_l^*})}$ take
    precautionary measure. We know that the following inequality must
    hold if precaution of victim is efficient in order to minimize
    social costs:[^1]
    $$\frac{1}{2}[p_h\frac{1}{2}h(\upsilon,x_h)]+\frac{1}{2}[p_l\frac{1}{2}h(\upsilon,x_l)]+c\leq\frac{1}{2}[p_hh(\upsilon,x_h)]+\frac{1}{2}[p_lh(\upsilon,x_l)]$$
    $$c\leq\frac{1}{4}p_h10\upsilon{e^{-x_h}}+\frac{1}{4}p_l10\upsilon{e^{-x_l}}$$
    $$\upsilon\geq\frac{2c}{5(p_he^{-x_h^*}+p_le^{-x_l^*})}\equiv\bar{\upsilon}$$
    $$\therefore m^*= \begin{cases}
                0 &, \upsilon<\bar{\upsilon} \\
                1 &, \upsilon\geq \bar{\upsilon}
              \end{cases}.$$ Given the threshold derived above, the
    social planer’s cost minimization is as follows:
    $$\arg\min_{x_h,x_l}W=E[x_hh'(x_h, \upsilon,m)p_h+mc]+E[x_lh'(x_l, \upsilon,m)p_l+mc]$$
    $$= \frac{1}{2}[x_h+p_h[prob(\upsilon\geq\bar{\upsilon})\frac{1}{2}10E[\upsilon|\upsilon\geq\bar{\upsilon}]e^{-x_h}]+ p_h[prob(\upsilon\leq\bar{\upsilon})]10E[\upsilon|\upsilon\leq\bar{\upsilon}]e^{-x_h}]$$
    $$+\frac{1}{2}[x_l+p_l[prob(\upsilon\geq\bar{\upsilon})\frac{1}{2}10E[\upsilon|\upsilon\geq\bar{\upsilon}]e^{-x_l}]+ p_l[prob(\upsilon\leq\bar{\upsilon})]10E[\upsilon|\upsilon\leq\bar{\upsilon}]e^{-x_l}]+c-\bar{\upsilon}c$$
    $$=p_h\frac{1}{2}((\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_h})+p_l\frac{1}{2}((\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_l})+\frac{1}{2}(x_h+x_l)-c\bar{\upsilon}+c$$
    Thus we have the first-order conditions for maximization of social
    welfare:
    $$FOC_{x_h}:-\frac{1}{2}p_h((\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_h^*})+\frac{1}{2}=0$$
    $$FOC_{x_l}:-\frac{1}{2}p_l((\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_l^*})+\frac{1}{2}=0$$

(f) Neither strict liability rule with contributory negligence nor
    standard negligence rule can implement the first-best levels of care
    $x_t^*$ and $m=1$ for $v\geq\bar{\upsilon}$. In the strict liability
    rule with contributory negligence, it is not possible to design a
    standard of due precaution of victims that brings efficient level
    of precaution. Victims do not take optimal level of precaution since
    their type is not observable and they can pretend to be of the low
    $\upsilon$ types in case the rule is to take precaution if
    $\bar{\upsilon}\leq\upsilon$. If the standard due care for all
    victims is set to invest ($m=1$), at least some types of victims
    will take inefficient precaution in order to avoid liability. In
    standard negligence rule, high risk injurer is motivated to imitate
    low risk injurer and thus take lower than optimal level of care.

(g) The total liablity of participants to an accident equals to the
    total harm done if $D_v+D_I=1$ (*where $D_I,D_v$ are the proportions
    of total harm borne by the injurer and victim, respectively.*) In
    order to achieve first-best we set $D_v=1$ and $D_I=0$ if
    $x\geq{x_h^*}$and $D_v=1-\bar{D},D_I=\bar{D_I}$ if $x<{x_h*}$. The
    intuition for this is that if the court would observe higher level
    of prevention than is the optimal due care for high type, then it is
    certain that the level of care was high enough for both types (in
    fact excessive care for the low type). On the other hand, we design
    a damage $\bar{D_I}$ such that the low type still would like to pay
    but that the high type would rather take higher precaution since the
    expected damage payment exceeds the saving cost on precaution.
    Therefore, the question of interest is how to set the $\bar{D_I}$ in
    order to force injurers to reveal their type (it is not profitable
    for high type to pretend to be low type and – at the same time – low
    type is not forced to take higher than optimal level of care). We
    need to find $\bar{D_I}$ such that high type wants to set $x_h^*$
    and low type wants to set $x_l^*$:

    \(i) high type wants to reveal himself:
    $${x_h^*}\leq{x}+D_Ih'(x_l^*,\upsilon,m)p_h$$
    $${x_h^*}\leq{x_l^*}+D_I[\{(1-\bar{\upsilon})5\frac{1+\bar{\upsilon}}{2}+\bar{\upsilon}10\frac{\bar{\upsilon}}{2}\}e^{-x_l^*}]p_h$$
    $${x_h^*}\leq{x_l^*}+D_I(\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_l^*}p_h$$
    Note that when the injurer is liable to $\bar{D_I}$ time the total harm,
    it is always optimal for her to set $x_l^*$, so condition (i) is
    sufficient for high type to reveal himself.\
    (ii) low type does not want to pretend to be high
    $${x_l^*}+D_Ih'(x_l,\upsilon,m)p_l\leq{x_h^*}$$
    $${x_l^*}+D_I(\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_l}p_l\leq{x_h^*}$$ (iii)
    low type prefers $x_l^*$ to $x$
    $${x_l^*}+D_Ih'(x_l,\upsilon,m)p_l\leq{x}+D_Ih'(x,\upsilon,m)p_l$$ Note
    that (iii) is redundant, above conditions can be reduced to:
    $$\frac{x_h^*-x^*_l}{(\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x^*_l}p_h}\leq{\bar{D_I}}\leq\frac{x_h^*-x_l^*}{(\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x_l^*}p_l}$$
    This condition is always satisfied since $p_h>p_l$, so such $\bar{D_I}$
    always exists.\
    In sum, the high type of injurers set $x_h^*$ to exempt from liability
    of damage, and the low type chooses $x_l^*$ to save costs and bears risk
    of being liable to $\bar(D_I)$ time the harm. Knowing this, the higher
    type of victims $\upsilon\geq\bar{\upsilon}$ thus take precaution
    according to the argument in (e), so we can implement the first best
    level of care.\
    \
    The liability rule involve negative damages if
    $\bar{D_I}\geq1\Leftrightarrow{\bar{D_v}\leq0}$. The condition for
    negative damages is as follows:
    $$\frac{x_h^*-x_l^*}{(\frac{5}{2}+\frac{5}{2}\bar{\upsilon^2})e^{-x^*_l}p_h}\geq1.$$
    In this case, victims obtain higher compensation than is the harm
    she suffered. Intuitively, when the risk of harming is sufficiently low,
    negative damages serve to discourage the high type injurer from
    pretending to be low type since he would face punitive damages. Low type
    is willing to bear punitive damages to reveal himself because she bears
    lower risk than high type and would rather save some precaution cost.
    Under this liability rule, victims know that each type of injurers will
    take optimal precaution of high type, so type
    $\upsilon\geq\bar{\upsilon}$ is willing to undertake precaution.

(h) To reveal all the specific details of the case is costly. For
    example, in some cases it is more efficient to set the liability
    rule that makes injurers internalize social costs and give the
    optimal outcome in expectation rather than to determine for instance
    the standard of due care on the case-to-case basis, which may be
    costly to evaluate. To illustrate, it is more efficient to set an
    uniform speed limit on the roads rather than set individual speed
    limit based on the driving skills of each driver. In fact, the limit
    should be set on the level when marginal social loss from
    opportunity time costs of more skilled drivers is equal to marginal
    saving on revealing individual driving skills in case of
    accident occurrence.

    Furthermore, from question (g) we see that even if the courts do not
    observe types but only precaution level, the court still can
    decouple damage from harm and design a direct mechanism to elicit
    information (truthful revelation) and thus provide right incentives.

Marginal Deterrence
===================

Denote $a_o$ such that type $t_o$ choose $a_o$ in the optimal punishment
scheme. First, can social planner implement optimal $a_o^*$ such that to
$b'(a_o^*)=h'(a_o^*)$? The answer is “No”, because monitoring comes at
costs, and it could be socially well off to allow for some harmful
activity to save the monitoring cost. Since $c_p=0$, we have $p(a)=1$,
$e(a)=\mu{f(a)}$ and the social welfare function is:
$$W=t_0b(a_o)-h(a_o)-\mu{c_m}$$ To implement $a_o$ such that any
${a}>a_0$ is deterred, $t_0$ chooses $a_0$ that maximizes her individual
utility $u(a)=t_0b(a)-e(a)$. Therefore, for any ${a}>a_0$, we have
$$t_0b(a)-e(a)\leq{t_0b(a_0)}-e(a_0).$$ Note that since we do not deter
$a\leq{a_0}$, we can set $f(a)=0$ for all ${a}{\leq}{a_0}$ and thus
$\Rightarrow{e(a_0)=0}$. Hence, we can set $e(a)$ at minimum
$t_0b(a)-t_0b(a_0)$ to minimize monitoring cost.\
Taking $a\rightarrow\infty$ and setting highest sanction to highest
harm, we have
$$\mu{w}=\lim_{a\rightarrow\infty}e(a)=t_0\bar{b}-t_0b(a_0)$$ Thus
following condition must hold for $t_0$ to choose less harmful acts:
$$w\geq\mu{w}=t_0\bar{b}-t_0b(a_0)$$ $$t_0b(a_0)\geq{t_0\bar{b}}-w$$ If
equation (2) is not satisfied, then no deterrence schedules can be
implemented. We substitute equation (1) in social welfare function and
$\frac{v}{w}$ as a Lagrange multiplier on the constraint:
$$\max{t_0}b(a_0)-h(a_0)-\frac{c_M}{w}(t_0\bar{b}-t_0b(a_0))$$
$$\textit{s.t. }w\geq{t_0}\bar{b}-t_0b(a_0)$$
$$FOC:[t_0+\frac{c_M+v}{w}]b'(a_0)=h'(a_0)$$ Since $c_M>0$ $v\geq0$,
$a_0\geq{a_0^*}$. If $v>0$ then monitoring cost is at its maximum
$\mu=1$. For $v=0$ then $\mu<1$. Only when
$\frac{w}{C_M}\rightarrow\infty$ can $a_0=a_0^*$ be achieved.\
To summarize, the optimal sanction scheme is: $$f(a)=\begin{cases}
        t_0b(a)-t_0b(a_0) & ,a>a_0 \\
        0 & ,a\leq{a_0} 
        \end{cases}$$ ,where $a_0$ is characterized by (3) and $\mu$ is
characterized by (1).

Litigation
==========

Osborne,(1999): Who should be worried about asymmetric information in
litigation?

#### Research Question:

Is litigation process characterized by asymmetric information or by
random optimism of the litigants? Who suffers by asymmetric information?

#### Relevance:

It tries to resolve the question that is important for the optimal
setting of the litigation rules.

#### Method:

Empirical analysis. The econometric model based on cross-sectional data
examines how the final award to the plaintiff from the litigation is
determined by the attorney’s estimate of the maximum the client should
have taken to settle the case.

#### Answer:

Asymmetric information are present. Defendants are significantly better
in estimation of the outcome. This seems to be especially the case for
the plaintiffs who pay their attorneys contingency fee. The possible
explanation is that under contingency fee, attorney is motivated to
acquire lower than optimal evidence.

#### Evluation:

We see the approach of this paper rather superficial. Problem of this
analysis arises even in the dataset. The crucial explanatory variable is
supposed to catch *ex ante* estimations of the attorney who are,
however, asked to give this estimate after the case is resolved and the
outcome is known. Thus, the estimates can be severely affected by
hindsight bias. Moreover, the author does not discuss the possible
endogeneity that is likely to be present in the model. The most
important objection is that there is no theoretical framework in this
paper that fits its methodology. In particular, the author refers to the
paper written by Waldfogel (1998) who also asked whether asymmetric
information or random optimism (divergent expectations) characterizes
litigation process. Unlikely to Osbourne, however, Waldfogel use the
probability of win as a proxy. We do not think that to be optimistic
about the winning probability is the same as to be optimistic about the
amount awarded. Thus, it would be valuable if the author formulates the
theoretical framework more precisely and if he explains why his approach
is supposed to deliver more reliable results than Wladfogel’s. Moreover,
the sample size is quite small in comparison to Wladfogel’s.

[^1]: Note that it is possible to obtain the same result by minimizing
    social costs: $$\arg\min_{m}E[x_t+h'(x_t,\upsilon,m)p_t+mc]$$
