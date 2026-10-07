# Tudo Bem — option 4 staging

The solo Tudo Bem game (the world runs in the browser, no server, progress saved in this browser only) with the **option-4 avatar**
(auburn bob, freckles, striped tee) as the player. This repository is staging only. It is not [playtudobem.com](https://playtudobem.com)
and it is not the `tudo-bem` Fly app.

- Game: https://jonnyschipper.github.io/tudo-bem-opt4-staging/
- Compare with the current players: add `?hires=0` to the URL
- The earlier walk-only preview: https://jonnyschipper.github.io/tudo-bem-opt4-staging/walk-preview/

`site/` is a build of `JonnySchipper/tudo-bem` branch `claude/avatar-walk-prototype-cblz0f`:

    VITE_LOCAL_WORLD=1 VITE_BASE=/tudo-bem-opt4-staging/ pnpm --filter @tudobem/client build   # then copy apps/client/dist to site/
