---
layout : post
title: AutoHotkey配置
---

    F3::
    send #^{left}
    return

    F4::
    send #^{right}
    return

    F7::
    send !{tab}
    return

    F8::
    send #1Sleep, 500{F5} !{tab}
    return

    !h::
    send {left}
    return

    !l::
    send {right}
    return

    !j::
    send {down}
    return

    !k::
    send {up}
    return

    F2::
    send dd
    return
