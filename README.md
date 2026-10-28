# Marble Run

A 3D design of a marble run. A marble dropped in the top funnel lands on a ridge that sends it
down one of two paths: right, around to the bowl funnel and down a ramp, or left, down a long
four-section track. Both paths end in the plinko box, which drains into the collection cup.

![Marble Run - main view](<Marble Run - main view.png>)

![Marble Run - back-left view](<Marble Run - back-left view.png>)

## Files

- `Marble Run Completed.step` – full assembly, STEP format (as designed)
- `Marble Run Completed.stl` – full assembly as one mesh, for viewing only (don't print this)
- `Marble Run Completed.x_t` – full assembly, Parasolid format
- `Marble Run Parts.step` – the 40 printable parts with fitted joints, STEP format
- `parts/` – one STL per printable part, grouped by assembly step
- `all parts/` – the same 40 STLs in one folder, for loading into a slicer in one go

## Printing

The run is printed as 40 separate parts and glued together. Printed as one piece, the tracks
and funnels would be floating in mid-air and need huge amounts of support.

### Settings

| Setting | Value |
|---|---|
| Material | PLA |
| Nozzle | 0.4 mm |
| Layer height | 0.2 mm (0.12–0.16 mm for the funnels and curved tracks if you want smoother runs) |
| Walls | 3 |
| Infill | 15–20% (the posts are thin enough to print almost solid anyway) |
| Supports | Only where noted below |
| Bed adhesion | Brim on the tall posts |

### Orientation

The STLs are exported in their assembled position. Lay each one on the bed as follows:

| Group | Parts | How to print |
|---|---|---|
| `1_base` | base plate | Flat, sockets facing up. No supports. |
| `2_posts` | 20 posts + the central pole | Standing up, socket end on the bed. Brim on anything over 60 mm. Print several at once, spaced out, so each layer has time to cool. |
| `3_plinko_and_cup` | plinko box, collection cup | Floor on the bed. No supports. |
| `4_funnels` | bowl funnel, start funnel | Wide end up. Supports under the bowl funnel's outlet if your slicer flags it. |
| `5_track` | 9 track sections | Open side of the channel up. Tilted and curved sections need supports under the low end; use tree/organic supports and keep them out of the channel. |
| `6_connectors` | arm, strut, junction ridge, 2 start-funnel legs | Largest flat face down. Small parts: print them with something else so they don't overheat. |

## Bill of materials

The 40 parts are merged into 11 STL files for ordering from [3ding.in](https://3ding.in/) (also in
[BOM.csv](BOM.csv)), plus a strand of decorative beads that serve as the 8 mm marbles. All prints
are FDM/FFF, PLA, white, 20% infill, with the service's standard supports. Prices are in USD at
about ₹96.5 per \$1. 3ding.in charges a minimum of ₹200 (\$2.07) per line, so the unit price for
small parts is that minimum, not the quoted price.

| Part | What it's for | Qty | Unit price (USD) | Vendor | Link | Notes |
|---|---|---|---|---|---|---|
| `base_with_posts.stl` | Base plate with all 20 posts and the central pole | 1 | \$9.37 | 3ding.in | [3ding.in](https://3ding.in/) | 150 x 150 x 146 mm; 174 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Print priced at \$9.37 |
| `bowl_funnel_with_arm_and_strut.stl` | Bowl funnel with its arm and strut | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 68 x 77 x 38 mm; 14 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.75; the \$2.07 minimum per line applies |
| `final_E2_to_cup.stl` | Final track section from E2 into the collection cup | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 19 x 116 x 34 mm; 10 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.53; the \$2.07 minimum per line applies |
| `path1_lower_ramp.stl` | Lower ramp of path 1 | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 56 x 40 x 24 mm; 3 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.31; the \$2.07 minimum per line applies |
| `path2_S2.stl` | Path 2 section S2 | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 19 x 51 x 44 mm; 8 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.41; the \$2.07 minimum per line applies |
| `path2_S3.stl` | Path 2 section S3 | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 91 x 19 x 49 mm; 10 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.54; the \$2.07 minimum per line applies |
| `path2_S4.stl` | Path 2 section S4 | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 19 x 72 x 47 mm; 9 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.48; the \$2.07 minimum per line applies |
| `plinko_with_exit.stl` | Plinko box with its exit track | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 71 x 57 x 27 mm; 15 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.82; the \$2.07 minimum per line applies |
| `start_funnel_with_legs.stl` | Start funnel with its two legs | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 47 x 47 x 25 mm; 4 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.31; the \$2.07 minimum per line applies |
| `top_left_track_with_S1.stl` | Top-left track with path 2 section S1 | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 54 x 14 x 11 mm; 3 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.31; the \$2.07 minimum per line applies |
| `top_right_path.stl` | Top-right path | 1 | \$2.07 | 3ding.in | [3ding.in](https://3ding.in/) | 92 x 66 x 56 mm; 9 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Quoted \$0.51; the \$2.07 minimum per line applies |
| 8mm decorative beads (Paradise Jewellery strands) | The marbles that run down the track | 1 | \$2.58 | Amazon | [amazon.in/dp/B0HJSWZFS9](https://www.amazon.in/dp/B0HJSWZFS9) | Rs 249. Decorative beads sold as strands; used in place of 8mm marbles. Only a few are needed |
| **Total** | | | **\$32.65** | | | |

## Assembly

### How the joints work

- **Posts into the base:** every post has a 2 mm plug on the bottom that fits a socket in the
  base with 0.2 mm clearance. Most posts are the same 6 mm diameter but different heights, so
  use the table below to put each in the right socket.
- **Post tops:** the top of each post is shaped to match the underside of the part it holds up.
  Glue the part onto it.
- **Track ends into notches:** where a track enters the plinko box or the cup, the notch is cut
  to the track's shape plus 0.2 mm, so the track end drops in.
- **Pole top:** the junction ridge, both top tracks and the start-funnel legs sit in pockets in
  the top of the central pole.

Use CA glue (superglue) for PLA. **Dry-fit every joint before gluing.**

### Post positions

Positions are in mm from the centre of the base, using the CAD model's X and Y axes. The central
pole is at 0, 0. Heights include the 2 mm plug.

| Post | X | Y | Height | Holds up |
|---|---|---|---|---|
| `pole_solid_column` (Ø20) | 0 | 0 | 139 | start funnel, junction, both top tracks |
| `post_right_bend` | 50 | -10 | 137 | top-right track bend |
| `post_path2_S1_-46_0` (Ø7) | -46 | 0 | 134 | track S1 |
| `post_path2_S2_-62_6` | -62 | 6 | 106 | track S2 |
| `post_path2_S2_-62_28` | -62 | 28 | 104 | track S2 |
| `post_funnel_2` | -66 | -36 | 77 | bowl funnel |
| `post_funnel_1` | -62 | -66 | 76 | bowl funnel |
| `post_path2_S3_-48_42` | -48 | 42 | 75 | track S3 |
| `post_path2_S3_-15_42` | -15 | 42 | 71 | track S3 |
| `post_path2_S3_2_42` | 2 | 42 | 69 | track S3 |
| `post_lower_ramp` | -25 | -43 | 39 | lower ramp |
| `post_path2_S4_20_26` | 20 | 26 | 39 | track S4 |
| `post_path2_S4_20_2` | 20 | 2 | 36 | track S4 |
| `plinko_leg_1` | -7 | -18 | 34 | plinko box |
| `plinko_leg_2` | 47 | -18 | 32 | plinko box |
| `plinko_leg_3` | -7 | -68 | 27 | plinko box |
| `plinko_leg_4` | 42 | -68 | 26 | plinko box |
| `post_E1` (Ø5) | 52 | -64 | 23 | plinko exit track |
| `post_E2_-45` | 62 | -45 | 6 | final track |
| `post_E2_-12` | 62 | -12 | 4 | final track |
| `post_E2_20` | 62 | 20 | 2 | final track |

The post names follow the track they hold up; the numbers in the name are its rough X and Y.

### Order

Build from the bottom up, so lower parts are easy to reach.

1. **Posts.** Dry-fit all the posts into the base using the table above. Once they're all
   correct, glue them in one at a time and check each stands straight.
2. **Plinko and cup.** Glue the plinko box onto its four legs. Glue the collection cup flat onto
   the base, centred at X 56, Y 48, with its gap facing the final track.
3. **Final tracks.** Seat `final_E2_to_cup` into the cup's notch and onto the three short
   `post_E2` posts; it rests on the base at its low end. Seat `final_E1_plinko_exit` into the
   plinko box's exit notch and onto `post_E1`.
4. **Bowl funnel and lower ramp.** Glue `bowl_funnel` onto its two posts, then glue
   `arm_pole_to_funnel` between the funnel and the pole. Fit `path1_lower_ramp` from under the
   funnel outlet into the plinko notch, resting on `post_lower_ramp`.
5. **Left path.** Working downwards: `path2_S4` into the plinko notch and onto its two posts,
   then `path2_S3`, `path2_S2` and `path2_S1`, each on its posts. Check the marble drops
   cleanly from each section into the next before gluing.
6. **Top junction.** Seat `start_junction_ridge`, `top_left_track` and `top_right_path` into
   the pockets in the top of the pole. `top_left_track` meets `path2_S1`; `top_right_path` rests
   on `post_right_bend` and ends over the bowl funnel. Glue `strut_ramp_to_funnel_rim` between
   the top-right track and the funnel rim.
7. **Start funnel.** Glue the two `start_funnel_leg` pieces into their pockets on the pole top,
   then glue `start_funnel` on top.

Roll a few marbles down each path before the glue fully sets, so you can still nudge a joint.

## Fit

Joints are designed with 0.2 mm clearance per side. Printers vary: if a joint is tight, sand it
lightly; if it's loose, fill the gap with a little extra glue.
