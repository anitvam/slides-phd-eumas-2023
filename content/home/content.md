+++
weight = 10
+++

# We searched for popular AOP languages

* **PYPL** PopularitY of Programming Language [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://pypl.github.io/PYPL.html)

* **TIOBE** [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://www.tiobe.com/tiobe-index/)

* **Stackoverflow developer survey** [<i class="fa-solid fa-arrow-up-right-from-square fa-xs"></i>](https://survey.stackoverflow.co/2023/#most-popular-technologies-language-prof)

<br>
<br>
<br>

{{% fragment %}}

# No one at all &#129335; 

{{% /fragment %}}

---

# Why?

We identified 4 possible reasons

---

# 1. Learning curve vs ergonomics
<br>
<br>

{{< multicol >}}{{< col >}}

<h4> AOP Libraries </h4>
<br>

<div>
<i class="fa-solid fa-check" style="color: green;"></i>
Gentle learning curve
</div>

<div>
<i class="fa-solid fa-check" style="color: green;"></i>
Large community
</div>

<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Poor ergonomicity
</div>

{{< /col >}}{{< col >}}

<h4> Custom Languages </h4>
<br>

{{< tick >}}
High ergonomicity
{{< /tick >}}

{{< cross >}}
Steep learning curve
{{< /cross >}}

<div>
<i class="fa-solid fa-xmark" style="color: red;"></i>
Small community
</div>

{{< /col >}}{{< /multicol >}}

<!-- {{% fragment %}}
**AOP libraries** provide low ergonomics:
<br>
non-experienced users find difficulties to describe AOP entities
{{% /fragment %}}

{{% fragment %}}
vs
{{% /fragment %}}

{{% fragment %}}
**Custom Languages** have a steeper learning curve,
<br>
due to the custom syntax
{{% /fragment %}} -->

---

# 2. Tooling
#### (IDE, code suggestion, syntax highlighter, ...)
<br>
<br>

{{< multicol >}}{{< col >}}

<h4> AOP Libraries </h4>
<br>

Come with a large set of well-known **development tools** and **utilities libraries** built for the mainstream language in which they rely on

{{< /col >}}{{< col >}}

<h4> Custom Languages </h4>
<br>

Needs to **implement** all the tooling required to support programmers, which is a time-valuable task

{{< /col >}}{{< /multicol >}}

---

# 3. Middleware/Runtime requirements
<br>

The majority of BDI AOP libraries rely on specific runtimes, e.g. **JVM**, **Python interpreter**, ...

<br> 

But BDI AOP systems could be designed to run on a large variety of devices, 
<br>
from **web** to **wearable**-oriented applications 

---

# 4. Concurrency model
<br>

Current BDI AOP languages offer limited configuration over the **execution** of an agent system.

<br>

We believe that a BDI model definition should be completely agnostic of the underlying concurrency model, which should be **pluggable**.

---

# Jakta
## <u>Ja</u>son-like <u>K</u>o<u>t</u>lin <u>A</u>gents

Internal DSL implemented in Kotlin

* Native tools maintained by the community
* Multi-paradigm support
* Gentler learning curve, leveraging a mainstream language
* Good ergonomy

<br>
<br>

{{% fragment %}}

{{< figure src="images/qr-code.svg" width="20%" >}}
[github.com/jakta-bdi/jakta-examples](https://github.com/jakta-bdi/jakta-examples)

{{% /fragment %}}
