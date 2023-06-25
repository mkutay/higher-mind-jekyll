# rabin karp

$h(s) = p^0 \times s[0] + p^1 \times s[1] + ... + p^{n - 1} \times s[n - 1]$

$h(s[0...i])$

$h(s[0...i + 1]) = h(s[0...i]) + p^i + s[i + 1]$

$h(s) =? \space h(t[j...j + m - 1])$