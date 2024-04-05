#pragma GCC optimize("O3")<br>
#pragma GCC optimize("Ofast", "inline", "ffast-math", "unroll-loops", "no-stack-protector")<br>
#pragma GCC target("sse,sse2,sse3,ssse3,sse4,popcnt,abm,mmx,avx,avx2,tune=native", "f16c")<br>

static const auto optimizer = []()<br>
{ <br>
    std::ios_base::sync_with_stdio(false); <br>
    std::cin.tie(nullptr); <br>
    std::cout.tie(nullptr); <br>
    return 'c'; <br>
}();<br>

Solution(){<br>
    optimizer;<br>
}<br>
