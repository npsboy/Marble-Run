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
- `grouped parts/` – the 11 STLs to print (see [Bill of materials](#bill-of-materials))
- `grouped parts.3mf` – the same 11 parts in one file, for uploading to a print service
- `Marble Run Grouped Parts.step` – the 11 parts, STEP format
- `BOM.csv` – the bill of materials below, as a spreadsheet
- `parts/`, `all parts/`, `all parts.3mf`, `all parts.zip`, `Marble Run Parts.step` – the same
  design split into 40 separate parts (see [Printing 40 separate parts](#printing-40-separate-parts))

## Bill of materials

The run is printed as 11 parts, ordered from [3ding.in](https://3ding.in/) (also in
[BOM.csv](BOM.csv)), plus a strand of decorative beads that serve as the 8 mm marbles. All prints
are FDM/FFF, PLA, white, 20% infill, with the service's standard supports. Prices are in USD at
about ₹96.5 per \$1. 3ding.in charges a minimum of ₹200 (\$2.07) per line, so the unit price for
small parts is that minimum, not the quoted price.

The run takes **8 mm balls**: the channels are 9 mm wide. Standard 16 mm toy marbles won't fit.

| Part | What it's for | Qty | Unit price (USD) | Vendor | Link | Notes |
|---|---|---|---|---|---|---|
| `base_with_posts.stl` | Base plate with all the posts, plinko legs and central pole, plus the collection cup and junction ridge | 1 | \$9.37 | 3ding.in | [3ding.in](https://3ding.in/) | 150 x 150 x 146 mm; 174 cm3. FDM/FFF PLA White; Stand supports; 20% infill. Print priced at \$9.37 |
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

You'll also need CA glue (superglue) and some fine sandpaper.

## Printing

These settings are for printing the parts yourself. If you order from a print service, pick
the same material and infill and let them handle orientation and supports.

### Settings

| Setting | Value |
|---|---|
| Material | PLA |
| Nozzle | 0.4 mm |
| Layer height | 0.2 mm (0.12–0.16 mm for the funnels and curved tracks if you want smoother runs) |
| Walls | 3 |
| Infill | 20% (the posts are thin enough to print almost solid anyway) |
| Supports | Only where noted below |
| Bed adhesion | Brim on `base_with_posts` |

### Orientation

The STLs are exported in their assembled position, which is also how they print best:

| Part | How to print |
|---|---|
| `base_with_posts` | Flat on the bed, posts pointing up. Needs a bed of at least 150 x 150 mm and 146 mm of height. Slow down for the top of the posts, where they're thin and tall. Supports only if your slicer flags the junction ridge on top of the pole. |
| `plinko_with_exit` | Floor down. The exit chute hangs about 2 mm below the floor, so the floor needs supports too. |
| `bowl_funnel_with_arm_and_strut` | Wide end up. Supports under the funnel, arm and strut. |
| `start_funnel_with_legs` | Legs on the bed. Supports under the funnel bowl. |
| Track sections (6 parts) | Open side of the channel up. Supports under the sloping and curved sections; use tree/organic supports and keep them out of the channel, since anything left inside will stop the marble. |

## Assembly

### What goes where

The base comes with every post already in place, so assembly is mostly setting the other ten
parts onto their posts:

- **Post tops** are shaped to match the underside of the part they hold up. Glue the part onto
  them.
- **Track ends** slot into notches in the plinko box and the collection cup. Each notch is the
  shape of the track end plus 0.2 mm, so the track drops straight in.
- **The top of the central pole** has pockets for the two top tracks and the start funnel's legs.
  The junction ridge between the two top tracks is already part of the pole.

Use CA glue. **Dry-fit every part before gluing**, then glue them in this order, from the bottom
up, so the lower parts are easy to reach.

### Order

1. **Plinko box.** Set `plinko_with_exit` on the four short plinko legs, with the exit chute
   resting on the short post beside it, and glue.
2. **Final track.** Seat `final_E2_to_cup` into the collection cup's notch and onto the three
   very short posts; its low end rests on the base. It catches the marble from the plinko's
   exit chute.
3. **Bowl funnel.** Set `bowl_funnel_with_arm_and_strut` on its two posts, with the end of the
   arm against the central pole, and glue. The strut sticks up from the funnel rim; it supports
   the top-right track later.
4. **Lower ramp.** Fit `path1_lower_ramp` from under the bowl funnel's outlet into the plinko
   box's notch, resting on its post.
5. **Left path.** `path2_S4` goes into the other plinko notch and onto its two posts. Then add
   `path2_S3` and `path2_S2`, each on its posts. Check the marble drops cleanly from each
   section into the next before gluing.
6. **Top tracks.** Seat `top_left_track_with_S1` into its pocket in the pole top, with the S1
   end on its post so it feeds into `path2_S2`. Seat `top_right_path` into the other pocket, resting on
   the tall post at its bend and on the top of the strut, and glue.
7. **Start funnel.** Push the legs of `start_funnel_with_legs` into the two remaining pockets in
   the pole top and glue.

Roll a few marbles down each path before the glue fully sets, so you can still nudge a joint.
The ridge under the start funnel sends marbles either way, so drop a few to test both paths.

### Fit

Joints are designed with 0.2 mm clearance per side. Printers vary: if a joint is tight, sand it
lightly; if it's loose, fill the gap with a little extra glue.

## Printing 40 separate parts

If your printer can't fit the 146 mm tall base, or you want to be able to reprint single posts,
the same design is also split into 40 parts in `parts/` (grouped into folders by assembly step)
and `all parts/` (one folder). It costs more to order this way, since each part has its own
minimum charge.

The extra steps compared to the grouped build:

- **Posts into the base.** Each post has a 2 mm plug on the bottom that fits a socket in the
  base. Most posts are the same 6 mm diameter but different heights, so use the table below to
  put each in the right socket. Dry-fit them all, then glue them one at a time and check each
  stands straight. Print the posts standing up, with a brim on anything over 60 mm.
- **Collection cup.** Glue it flat onto the base, centred at X 56, Y 48, with its gap facing the
  final track.
- **Small pieces.** Glue `arm_pole_to_funnel` and `strut_ramp_to_funnel_rim` to the bowl funnel,
  `path2_S1` to `top_left_track`, `final_E1_plinko_exit` into the plinko's exit notch, and the two
  `start_funnel_leg` pieces to `start_funnel`. Seat `start_junction_ridge` into its pocket in the
  pole top before the top tracks.

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
