## Explosive Sequential Tree Notation

### Prologue
The **Explosive Sequential Tree Notation** or abbreviated as **ESTN** is a *sequential array* based notation devised by the wikia user **Lucian Seaborgis** using **Copy Notation** and other notations.

---

### Definition
#### Episode I
The **Sequence Function** creates a *Sequence*:
`Seq(n, m, q, r) = r[n[m](q times)]`
It uses 4 variables which end up making a **Copy Notation** *Sequence*.
Here is an example: `Seq(3, 3, 3, 3) = 3[3](3 times)` which is equal to `3[3[3[3]]]` which in **Copy Notation** is equal to `3[[3]]`, which is approximated to `3⋅10^10^10`.

---

You can add a subscript as an argument:
`Seq(n, m, q, r)ₖ = r[n[m](q[k] times)]`
Now uses 5 variables. The *k* variable makes a copy operation on *q*.
More variables mean more iterations on the variable *q*:
`Seq(n, m, q, r, x, y)ₖ = r[n[m](q[k[x[y]]] times)]`

---

#### Episode II
The **Sequence Tree Function** makes *Iterations Arrays* of **Sequence Functions**:
`trs(a, b)ₙ = Seq(Seq(Seq(Seq(Seq(Seq(... n iterations on a, b, a, b, ... n)ₙ`
Here's an example: `trs(2, 2)₂ = Seq(Seq(2, 2, 2, 2))₂` which is less than `3⋅10^10^10`.

Finally, the **Explosive Sequence Tree Function** uses the **Infra Notation** and the **Dimensional Phi Notation**:
`xs(a, b)ₙ = trs(|<a, b>)ϕₙ = Seq(Seq(Seq(... n iterations on |<a, b, a, b, ... n)ϕₙ` where `ϕₙ = ϕ(γ(n)1a)[n]` in **Dimensional Phi Notation**. So this makes an unimaginable amount of iterations on *n* itself. 
So, here is an example of deconstructing it: 
```
[
\boxed{
xs(3,3)phi3 = \underbrace{
Seq(Seq(Seq(\dots Seq(|<3,3>|,\ |<3,3>|,\ |<3,3>|,\ |<3,3>|)\dots )))
}*{\varphi(\gamma(3)1 3)[3]\ \text{iterations}}
}
]
```

---

### Estimated Growth Speed (Not exact)
The ***XS function*** (***Explosive Sequence Tree Function***) is estimated to be in `ƒψ_Ω(ε_{Ω^ω^2}` because of the **Dimensional Phi Notation**.

---

### See also
> 1. https://googology.fandom.com/wiki/User_blog:Someone_who_owns_a_fish/Dimensional_Phi_Notation_%26_Beyond#
> 2. https://integralview.wordpress.com/2020/12/08/basic-infra-notation/
> 3. https://googology.fandom.com/wiki/Fast-growing_hierarchy
> 4. https://googology.fandom.com/wiki/Copy_notation
> 5. https://googology.fandom.com/wiki/Array
> 6. https://googology.fandom.com/wiki/Ordinal_collapsing_function
