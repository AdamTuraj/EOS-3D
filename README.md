<center><h1>EOS 3D</h1>

**A cheap cantilever 3D printer with full self calibration capabilities.**

This printer was made for the [Hackclub](http://hackclub.com) "Infill" event.

</center>

## Goal

- $300 (USD) budget
- Klipper compatibility
- No calibration printing is required
- 180x180mm build space
- Cantilever structure
- CFD-optimized part cooling
- Safety considerations:
  - Must not pose a fire hazard
  - Must not cause harm to the user
- ~~[PicoMMU](https://github.com/lhndo/LH-Stinger/tree/main/User_Mods/MMU/Stinger%20Pico%20MMU%20-%20%40LH) compatibility~~

## The Result

After a complete redesign, flaws from early part choices created major issues in the final build. These challenges taught me valuable lessons for future projects, especially regarding keeping structures stiff, following good design practices to avoid pitfalls, and approaching wiring more thoughtfully.

As of writing this README, the printer is about 80% complete but still far below my minimum standards. The main reasons are:

- Wiring: In V1, I cut the wires too short (even for that build they were barely long enough). With V2, they simply couldn’t reach.
- Rigidity: The Z and X axes weren’t stiff enough. This was the biggest issue—I underestimated the limitations of ASA and couldn’t reinforce it enough to minimize flex.
- X-axis rods: These should have been slightly longer to give the XZ mount more gripping surface.
- Lack of time: With university starting in a few days, I do not have enough time to finish it.

It was painful to call this project off, but it has been an invaluable learning experience. From V1 to V2, I made many improvements (and some regressions) to the design. The toolhead was by far the biggest success. With a larger budget, I’d rebuild the machine entirely from the ground up; however, that will be for the future

Below are images of the printer:
EOS V2:
![EOS V2](https://cdn.hackclub.com/019cd879-6193-7095-8d03-0c47acdee47c/image.png)

EOS V1:
![EOS V1](https://cdn.hackclub.com/019c5ace-4b53-79be-ad22-a5185651ff31/fd126409a3874a5b7fc16f55c6bd4d3ca9707a52_screenshot_2025-02-24_at_10.16.00___pm.png)
