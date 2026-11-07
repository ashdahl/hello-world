# NYC Provider Candidates — remaining cleanup (71 rows)

Database: https://app.notion.com/p/2b1bec2ca2704df6a9b1ec3554b80de1 (data source collection://c66c99c9-8efb-48b8-bc04-766bb52df570)

## Instructions for the assistant executing this

For each row below, update the page properties exactly as listed (use the Notion `update-page` tool with command `update_properties`). Rows are identified by Notion page ID.

Rules that apply to every row:
- **Notes**: delete the line that starts with `Address:` and the line that starts with `EDS directory listing:`. Keep everything else. If a row lists "Other locations", append a final line `Other locations: ...` with that text.
- **Address** is a Place property. Set all four fields: `place:Address:name`, `place:Address:address` (both = the address string below), `place:Address:latitude`, `place:Address:longitude` (numbers below).
- **Telehealth-only providers**: name and address are both the literal text `Telehealth only`; still set the lat/long given.
- Only change Specialty, Website, Practice, Name when a value is listed. `Website: (clear)` means set it to empty.
- Do not touch Phone, Status, Priority, IV Therapy, Est. Cost.

## Rows

### Callie Pederson  (page `3fed6b2867f48105918ecc3264b7b05c`)
- Name: Callie Pederson
- Address: Telehealth only  (lat 40.7381, long -73.9847)
- Neighborhood: Telehealth only (NY)
- Source: https://www.ehlers-danlos.com/directory/callie-pederson/
- Specialty: PCP
- Notes: remove the Address / EDS-directory-link lines

### Chaim Mandelbaum, MD  (page `3fed6b2867f481f39c5bf3ca8398a937`)
- Name: Chaim Mandelbaum, MD
- Address: 75 Maiden Lane, Suite 1206, New York, NY 10038  (lat 40.7069, long -74.007)
- Neighborhood: Financial District
- Source: https://www.ehlers-danlos.com/directory/chaim-mandelbaum/
- Specialty: Pain
- Notes: remove the Address / EDS-directory-link lines

### Charles Popkin, MD  (page `3fed6b2867f481028c4eee593c31a013`)
- Name: Charles Popkin, MD
- Address: 622 W 168th St, 11th Fl, New York, NY 10032  (lat 40.8412, long -73.9414)
- Neighborhood: Washington Heights (Columbia; also Tarrytown)
- Source: https://www.ehlers-danlos.com/directory/charles-popkin/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: CUMC Tarrytown, 155 White Plains Rd, Tarrytown, NY 10591`

### Christina Nguyen, CGC  (page `3fed6b2867f481e4a6c9c4b59db982be`)
- Name: Christina Nguyen, CGC
- Address: Telehealth only  (lat 40.465, long -80.065)
- Neighborhood: Telehealth only (home office Pittsburgh, PA)
- Source: https://www.ehlers-danlos.com/directory/christina-nguyen/
- Notes: remove the Address / EDS-directory-link lines

### Chris Nadler, PhD, LP  (page `3fed6b2867f481fc8e49eb4df25d5118`)
- Name: Chris Nadler, PhD, LP
- Address: 220 5th Ave, 11th Fl, New York, NY 10001  (lat 40.7441, long -73.9878)
- Neighborhood: NoMad
- Source: https://www.ehlers-danlos.com/directory/chris-nadler/
- Notes: remove the Address / EDS-directory-link lines

### Cristina Bateman, PT, DPT, RYT-200  (page `3fed6b2867f481f09a66f052d59e007e`)
- Name: Cristina Bateman, PT, DPT, RYT-200
- Address: 310 W 72nd St #1G, New York, NY 10023  (lat 40.7793, long -73.9838)
- Neighborhood: Upper West Side (also Upper East Side)
- Source: https://www.ehlers-danlos.com/directory/cristina-bateman/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 241 E 86th St #2B, New York, NY 10028`

### Cristina Sabbadin, PT, DPT  (page `3fed6b2867f4811fb059fb197abda0ba`)
- Name: Cristina Sabbadin, PT, DPT
- Address: 129 W 29th St, 2nd Fl, New York, NY 10001  (lat 40.7474, long -73.991)
- Neighborhood: Chelsea / NoMad
- Source: https://www.ehlers-danlos.com/directory/cristina-sabbadin/
- Notes: remove the Address / EDS-directory-link lines

### Deborah Barbiere, Psy.D., L.Ac  (page `3fed6b2867f481308fddffa353da3910`)
- Name: Deborah Barbiere, Psy.D., L.Ac
- Address: 16 Madison Square West, 11th Fl, New York, NY 10010  (lat 40.7419, long -73.9892)
- Neighborhood: Flatiron
- Source: https://www.ehlers-danlos.com/directory/deborah-barbiere/
- Specialty: Acupuncture
- Notes: remove the Address / EDS-directory-link lines

### Daniel Shapiro, PT, DPT  (page `3fed6b2867f481b7bb71e9e0b21d2cca`)
- Name: Daniel Shapiro, PT, DPT
- Address: 213 W 35th St, Suite 603, New York, NY 10001  (lat 40.7523, long -73.9906)
- Neighborhood: Garment District / Midtown South
- Source: https://www.ehlers-danlos.com/directory/daniel-shapiro/
- Notes: remove the Address / EDS-directory-link lines

### Diana Kumar, MD  (page `3fed6b2867f481f6aee4e365dcdde612`)
- Name: Diana Kumar, MD
- Address: Telehealth only  (lat 40.799, long -73.968)
- Neighborhood: Telehealth only
- Source: https://www.ehlers-danlos.com/directory/diana-kumar/
- Practice: EDS Connective
- Notes: remove the Address / EDS-directory-link lines

### Diane Richmond, PT, DPT, CFMT  (page `3fed6b2867f481f288b1c562d1b2d4df`)
- Name: Diane Richmond, PT, DPT, CFMT
- Address: Rye Brook, NY 10573  (lat 41.019, long -73.683)
- Neighborhood: Rye Brook (Westchester)
- Source: https://www.ehlers-danlos.com/directory/diane-richmond/
- Website: (clear)
- Practice: Richmond Health
- Notes: remove the Address / EDS-directory-link lines

### Dorothy Regan  (page `3fed6b2867f481a8941df6c61feb3b8c`)
- Name: Dorothy Regan
- Address: 534 River Ave, Pelham, NY 10803  (lat 40.91, long -73.808)
- Neighborhood: Pelham (Westchester)
- Source: https://www.ehlers-danlos.com/directory/dorothy-regan/
- Website: (clear)
- Specialty: Personal Training
- Notes: remove the Address / EDS-directory-link lines

### Dr. Laurel Steinberg, Ph.D.  (page `3fed6b2867f481cda5a2f3162220a948`)
- Name: Dr. Laurel Steinberg, Ph.D.
- Address: 442 Fifth Ave, Suite 1080, New York, NY 10018  (lat 40.7524, long -73.982)
- Neighborhood: Midtown (Bryant Park); phone/Zoom sessions
- Source: https://www.ehlers-danlos.com/directory/dr-laurel-steinberg/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: Center for Relationship Repair, 17 Capi Lane, Port Washington, NY 11050`

### Dr. Lloyd Becker  (page `3fed6b2867f4810287bcfc1ece7da5ee`)
- Name: Dr. Lloyd Becker
- Address: 80 Maiden Lane, Ste 702, New York, NY 10038  (lat 40.7073, long -74.0068)
- Neighborhood: Financial District
- Source: https://www.ehlers-danlos.com/directory/dr-lloyd-becker/
- Notes: remove the Address / EDS-directory-link lines

### Dr. Rani Gandham, MD  (page `3fed6b2867f481fab292e29ed0d3e17e`)
- Name: Dr. Rani Gandham, MD
- Address: 1220 New Scotland Rd, Suite 303, Slingerlands, NY 12159  (lat 42.642, long -73.86)
- Neighborhood: Slingerlands (Albany area)
- Source: https://www.ehlers-danlos.com/directory/dr-rani-gandham/
- Notes: remove the Address / EDS-directory-link lines

### Eleanor Griffith, MS, CGC  (page `3fed6b2867f4813c9145ea87653de253`)
- Name: Eleanor Griffith, MS, CGC
- Address: Telehealth only  (lat 40.7165, long -73.9575)
- Neighborhood: Telehealth only (mailing address Williamsburg, Brooklyn)
- Source: https://www.ehlers-danlos.com/directory/eleanor-griffith/
- Notes: remove the Address / EDS-directory-link lines

### Elena DiRusso, DO  (page `3fed6b2867f48199a741d5ca4a7a913c`)
- Name: Elena DiRusso, DO
- Address: 55 Livingston Ave, Dobbs Ferry, NY 10522  (lat 41.014, long -73.872)
- Neighborhood: Dobbs Ferry (Westchester)
- Source: https://www.ehlers-danlos.com/directory/elena-dirusso/
- Specialty: Osteopath
- Notes: remove the Address / EDS-directory-link lines

### Elizabeth Arnold Cells, PT, DPT, CFMT, CSCS  (page `3fed6b2867f481fdb8c6fa41f9b85cdd`)
- Name: Elizabeth Arnold Cells, PT, DPT, CFMT, CSCS
- Address: 27 Chadwick Rd, White Plains, NY 10604  (lat 41.04, long -73.75)
- Neighborhood: White Plains (Westchester)
- Source: https://www.ehlers-danlos.com/directory/elizabeth-arnold-cells/
- Website: (clear)
- Notes: remove the Address / EDS-directory-link lines

### Elliot Cecil, DO  (page `3fed6b2867f481278208c60c8ae7eaf2`)
- Name: Elliot Cecil, DO
- Address: 50 W 97th St, Suite 1-J, New York, NY 10025  (lat 40.7923, long -73.9665)
- Neighborhood: Upper West Side (also Midtown East)
- Source: https://www.ehlers-danlos.com/directory/elliot-cecil/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: Healthy, Wealthy, and Wise, 280 Madison Ave, Suite 905, New York, NY 10016`

### Elliot McCullough, LCSW  (page `3fed6b2867f48192ba75c178fa30db61`)
- Name: Elliot McCullough, LCSW
- Address: 110 Lafayette St, Room 501, New York, NY 10013  (lat 40.7183, long -74.0005)
- Neighborhood: Chinatown / Tribeca
- Source: https://www.ehlers-danlos.com/directory/elliot-mccullough/
- Notes: remove the Address / EDS-directory-link lines

### Emily Gayeski-Freedman, PT, DPT, OCS  (page `3fed6b2867f4815c9864f9a30bf7244a`)
- Name: Emily Gayeski-Freedman, PT, DPT, OCS
- Address: 244-250 W 54th St, Suite 805, New York, NY 10019  (lat 40.7645, long -73.9835)
- Neighborhood: Midtown West (also Flatiron)
- Source: https://www.ehlers-danlos.com/directory/emily-gayeski-freedman/
- Practice: SerendiPT
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 7 W 22nd St, 8th Fl, New York, NY 10010`

### Emma Raccaro, PT, DPT  (page `3fed6b2867f481979188c154800bb2f3`)
- Name: Emma Raccaro, PT, DPT
- Address: 310 W 72nd St, Suite 1G, New York, NY 10023  (lat 40.7793, long -73.9838)
- Neighborhood: Upper West Side
- Source: https://www.ehlers-danlos.com/directory/emma-raccaro/
- Website: https://www.zionpt.com/
- Notes: remove the Address / EDS-directory-link lines

### Erika Moran, PT, DPT  (page `3fed6b2867f481db9b14d6c3af975d5f`)
- Name: Erika Moran, PT, DPT
- Address: 310 W 72nd St, Suite 1G, New York, NY 10023  (lat 40.7793, long -73.9838)
- Neighborhood: Upper West Side
- Source: https://www.ehlers-danlos.com/directory/erika-moran/
- Notes: remove the Address / EDS-directory-link lines

### Fiona Malamen, LMT, CSC I  (page `3fed6b2867f4814c8967cb8b52c51e75`)
- Name: Fiona Malamen, LMT, CSC I
- Address: 315 Madison Ave, Suite 1200, New York, NY 10017  (lat 40.7527, long -73.979)
- Neighborhood: Midtown East (Grand Central)
- Source: https://www.ehlers-danlos.com/directory/fiona-malamen/
- Notes: remove the Address / EDS-directory-link lines

### Ezgi Irmakkesen, PT, DPT  (page `3fed6b2867f481759c12c6247264321f`)
- Name: Ezgi Irmakkesen, PT, DPT
- Address: 275 4th Ave, Brooklyn, NY 11215  (lat 40.6755, long -73.9843)
- Neighborhood: Park Slope / Gowanus, Brooklyn
- Source: https://www.ehlers-danlos.com/directory/ezgi-irmakkesen/
- Notes: remove the Address / EDS-directory-link lines

### Gene Shenker, DPT  (page `3fed6b2867f481989771ee1d0f78a001`)
- Name: Gene Shenker, DPT
- Address: 247 3rd Ave, B2, New York, NY 10010  (lat 40.737, long -73.9843)
- Neighborhood: Gramercy
- Source: https://www.ehlers-danlos.com/directory/gene-shenker/
- Specialty: Physical Therapy
- Practice: Gramercy Physical Therapy / RehabStride
- Notes: remove the Address / EDS-directory-link lines

### Haley Shepherd, PT, DPT  (page `3fed6b2867f481d08cf3d3114c7a2ba5`)
- Name: Haley Shepherd, PT, DPT
- Address: 32 Union Square East, Suite 402, New York, NY 10003  (lat 40.7357, long -73.989)
- Neighborhood: Union Square
- Source: https://www.ehlers-danlos.com/directory/haley-shepherd/
- Notes: remove the Address / EDS-directory-link lines

### Jason Siefferman, MD  (page `3fed6b2867f48146a874e5833590ebb4`)
- Name: Jason Siefferman, MD
- Address: 2 Fifth Ave, Suite 7, New York, NY 10011  (lat 40.7322, long -73.9966)
- Neighborhood: Greenwich Village
- Source: https://www.ehlers-danlos.com/directory/jason-siefferman/
- Notes: remove the Address / EDS-directory-link lines

### Jacquelyn Jaronczyk, PT, DPT, PRPC  (page `3fed6b2867f4814fb878e965cd286d92`)
- Name: Jacquelyn Jaronczyk, PT, DPT, PRPC
- Address: 171 S Wellwood Ave, Unit B, Lindenhurst, NY 11757  (lat 40.685, long -73.374)
- Neighborhood: Lindenhurst, Long Island (also Somers, CT)
- Source: https://www.ehlers-danlos.com/directory/jacquelyn-jaronczyk/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 24 Battle St, Suite 1A, Somers, CT 06071`

### Jena Blackwood, PT, DPT  (page `3fed6b2867f481c798e1c4854f5c6f7d`)
- Address: 32 Union Square East, Suite 1217, New York, NY 10003  (lat 40.7357, long -73.989)
- Neighborhood: Union Square
- Source: https://www.ehlers-danlos.com/directory/jena-blackwood/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 2902 Garfield Ave S, Minneapolis, MN 55408`

### Jeni Horvat, ND, BCAMP, CR, ME, CI  (page `3fed6b2867f48175bba2eb5c43566866`)
- Name: Jeni Horvat, ND, BCAMP, CR, ME, CI
- Address: Telehealth only  (lat 35.5917, long -92.4604)
- Neighborhood: Telehealth only (based in Arkansas)
- Source: https://www.ehlers-danlos.com/directory/jeni-horvat/
- Notes: remove the Address / EDS-directory-link lines

### Jenna Cangiano  (page `3fed6b2867f4811f89a9e7c2a05c6f3b`)
- Name: Jenna Cangiano
- Address: 134 W 29th St, Suite 606, New York, NY 10001  (lat 40.7472, long -73.9916)
- Neighborhood: Chelsea / NoMad
- Source: https://www.ehlers-danlos.com/directory/jenna-cangiano/
- Notes: remove the Address / EDS-directory-link lines

### Jennifer Tang, M.D.  (page `3fed6b2867f4817d92bbc2442cff7069`)
- Name: Jennifer Tang, M.D.
- Address: Telehealth only  (lat 40.7585, long -73.9675)
- Neighborhood: Telehealth only (NY = consulting; primary care for CA patients only)
- Source: https://www.ehlers-danlos.com/directory/jennifer-tang/
- Specialty: PCP
- Notes: remove the Address / EDS-directory-link lines

### Jennifer Wolfe, LCSW-R  (page `3fed6b2867f481f8bf75e040ead00f0f`)
- Name: Jennifer Wolfe, LCSW-R
- Address: Telehealth only  (lat 42.444, long -76.5019)
- Neighborhood: Telehealth only (NY & MA; based in Ithaca)
- Source: https://www.ehlers-danlos.com/directory/jennifer-wolfe/
- Notes: remove the Address / EDS-directory-link lines

### Joanna Streitman, OTR/L  (page `3fed6b2867f48121a21cde9332621dac`)
- Name: Joanna Streitman, OTR/L
- Address: 5 E 102nd St, New York, NY 10029  (lat 40.7905, long -73.952)
- Neighborhood: East Harlem (Mount Sinai)
- Source: https://www.ehlers-danlos.com/directory/joanna-streitman/
- Specialty: Occupational Therapy
- Notes: remove the Address / EDS-directory-link lines

### Joy Hyunjeong Jang, PT, PhD, WCS, CLT  (page `3fed6b2867f4815886bac96805add1ee`)
- Name: Joy Hyunjeong Jang, PT, PhD, WCS, CLT
- Address: 275 4th Ave, Brooklyn, NY 11215  (lat 40.6755, long -73.9843)
- Neighborhood: Park Slope / Gowanus, Brooklyn (also Koreatown)
- Source: https://www.ehlers-danlos.com/directory/joy-hyunjeong-jang/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: CHA Physical Therapy, 16 W 32nd St #2A/#1007, New York, NY 10001`

### Julia Delzingaro, MS, OTR/L  (page `3fed6b2867f48115897eed8ce058686c`)
- Name: Julia Delzingaro, MS, OTR/L
- Address: 529 E 6th St #1B-4B, New York, NY 10009  (lat 40.7245, long -73.982)
- Neighborhood: East Village / Alphabet City
- Source: https://www.ehlers-danlos.com/directory/julia-delzingaro/
- Website: (clear)
- Specialty: Occupational Therapy
- Notes: remove the Address / EDS-directory-link lines

### Kathryn Bacigalupo, PT, DPT, GTS  (page `3fed6b2867f481f2aa54fd626ab4bb82`)
- Name: Kathryn Bacigalupo, PT, DPT, GTS
- Address: 1615 Northern Blvd, Suite 202, Manhasset, NY 11030  (lat 40.792, long -73.69)
- Neighborhood: Manhasset, Long Island
- Source: https://www.ehlers-danlos.com/directory/kathryn-bacigalupo/
- Notes: remove the Address / EDS-directory-link lines

### Kelsey Conger, MS, PMC  (page `3fed6b2867f48150b7b0fcc382403d27`)
- Name: Kelsey Conger, MS, PMC
- Address: Telehealth only  (lat 41.927, long -74.02)
- Neighborhood: Telehealth only (based in Kingston, NY)
- Source: https://www.ehlers-danlos.com/directory/kelsey-conger/
- Notes: remove the Address / EDS-directory-link lines

### Kendel Lipe, PT, DPT  (page `3fed6b2867f4810cb3eee6fb27130781`)
- Name: Kendel Lipe, PT, DPT
- Address: Telehealth only  (lat 40.585, long -73.95)
- Neighborhood: Telehealth only (based in Austin, TX)
- Source: https://www.ehlers-danlos.com/directory/kendel-lipe/
- Notes: remove the Address / EDS-directory-link lines

### Kristen Freeland, PT, DPT  (page `3fed6b2867f4818ab4e2eb9f5215e568`)
- Name: Kristen Freeland, PT, DPT
- Address: 275 4th Ave, Brooklyn, NY 11215  (lat 40.6755, long -73.9843)
- Neighborhood: Park Slope / Gowanus, Brooklyn
- Source: https://www.ehlers-danlos.com/directory/kristen-freeland/
- Notes: remove the Address / EDS-directory-link lines

### Lev Kalika, DC, RMSK  (page `3fed6b2867f481c48a03dd406220bb89`)
- Name: Lev Kalika, DC, RMSK
- Address: 11 W 25th St, 5th Fl, New York, NY 10010  (lat 40.7437, long -73.99)
- Neighborhood: NoMad / Flatiron
- Source: https://www.ehlers-danlos.com/directory/lev-kalika/
- Notes: remove the Address / EDS-directory-link lines

### Madeline (Maddie) Connolly, PT, DPT  (page `3fed6b2867f481949c38f9b7b051e7a6`)
- Name: Madeline (Maddie) Connolly, PT, DPT
- Address: 151 W 19th St, 2nd Fl, New York, NY 10011  (lat 40.7409, long -73.996)
- Neighborhood: Chelsea
- Source: https://www.ehlers-danlos.com/directory/madeline-maddie-connolly/
- Notes: remove the Address / EDS-directory-link lines

### Louis Ezrick, MSPT  (page `3fed6b2867f4819a9247c1f6342a11ca`)
- Name: Louis Ezrick, MSPT
- Address: 3319 Ave N, Brooklyn, NY 11234  (lat 40.617, long -73.934)
- Neighborhood: Marine Park, Brooklyn (also Mill Basin, Park Slope, Gravesend, Midwood)
- Source: https://www.ehlers-danlos.com/directory/louis-ezrick/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 6161 Strickland Ave (Mill Basin); 550 5th Ave (Park Slope); 372 Avenue U, Ste 1A (Gravesend); 945 Kings Highway (Midwood)`

### Madison Caloss, PT, DPT, CSCS  (page `3fed6b2867f48111ba3fe97e89187e0b`)
- Name: Madison Caloss, PT, DPT, CSCS
- Address: 241 E 86th St, Ste 2, New York, NY 10028  (lat 40.7786, long -73.9527)
- Neighborhood: Upper East Side / Yorkville
- Source: https://www.ehlers-danlos.com/directory/madison-caloss/
- Website: https://www.zionpt.com/
- Notes: remove the Address / EDS-directory-link lines

### Maria Rodriguez Contreras, MD  (page `3fed6b2867f4813f8ceced8fdda43f06`)
- Name: Maria Rodriguez Contreras, MD
- Address: Telehealth only  (lat 41.704, long -73.929)
- Neighborhood: Telehealth only (NY listing: Poughkeepsie)
- Source: https://www.ehlers-danlos.com/directory/maria-rodriguez-contreras/
- Notes: remove the Address / EDS-directory-link lines

### Masumi Kishimoto, AT, AmSAT, ACAT  (page `3fed6b2867f481c49142c420b50f43c5`)
- Name: Masumi Kishimoto, AT, AmSAT, ACAT
- Address: 315 Madison Ave, Suite 1200, New York, NY 10017  (lat 40.7527, long -73.979)
- Neighborhood: Midtown East (Grand Central)
- Source: https://www.ehlers-danlos.com/directory/masumi-kishimoto/
- Notes: remove the Address / EDS-directory-link lines

### Megan Trinkle-Knotts, MS, CGC  (page `3fed6b2867f48160a07ecc657e41f654`)
- Name: Megan Trinkle-Knotts, MS, CGC
- Address: Telehealth only  (lat 40.747, long -73.86)
- Neighborhood: Telehealth only
- Source: https://www.ehlers-danlos.com/directory/megan-trinkle-knotts/
- Notes: remove the Address / EDS-directory-link lines

### Megan Lothian, LCSW  (page `3fed6b2867f481d2ab1be85435435fe8`)
- Name: Megan Lothian, LCSW
- Address: 113 University Pl, New York, NY 10003  (lat 40.7338, long -73.9925)
- Neighborhood: Greenwich Village / Union Square
- Source: https://www.ehlers-danlos.com/directory/megan-lothian/
- Specialty: LCSW
- Notes: remove the Address / EDS-directory-link lines

### Megan Wise, PT, DPT, CSCS, NCPT  (page `3fed6b2867f4810f8624da9888a1fbb3`)
- Name: Megan Wise, PT, DPT, CSCS, NCPT
- Address: 32 Union Square East, Suite 402, New York, NY 10003  (lat 40.7357, long -73.989)
- Neighborhood: Union Square
- Source: https://www.ehlers-danlos.com/directory/megan-wise/
- Notes: remove the Address / EDS-directory-link lines

### Megan Young, PT, DPT  (page `3fed6b2867f481e39fdccfeea31706bb`)
- Name: Megan Young, PT, DPT
- Address: 211 E 43rd St #1101, New York, NY 10017  (lat 40.751, long -73.9728)
- Neighborhood: Midtown East (Grand Central)
- Source: https://www.ehlers-danlos.com/directory/megan-young/
- Notes: remove the Address / EDS-directory-link lines

### Melanie Carminati , PT, DPT, GTS, NCPT  (page `3fed6b2867f481c2a78ce071df4a2eaa`)
- Name: Melanie Carminati , PT, DPT, GTS, NCPT
- Address: 295 4th Ave, Brooklyn, NY 11215  (lat 40.675, long -73.984)
- Neighborhood: Park Slope / Gowanus, Brooklyn (also Midtown)
- Source: https://www.ehlers-danlos.com/directory/melanie-carminati/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 2 W 46th St, Suite 403, New York, NY 10036`

### Miho Urisaka, PT, DPT, OCS, CSC I  (page `3fed6b2867f4817ba605d1373141fabb`)
- Address: 315 Madison Ave, Suite 1200, New York, NY 10017  (lat 40.7527, long -73.979)
- Neighborhood: Midtown East (Grand Central); also Rye Brook
- Source: https://www.ehlers-danlos.com/directory/miho-urisaka/
- Notes: remove the Address / EDS-directory-link lines; append `Other locations: 34 Rye Ridge Plaza, Rye Brook, NY 10573`

### Morgan Roberts, MS, RDN, LDN  (page `3fed6b2867f481b7bd10ecb2e2fc7e58`)
- Name: Morgan Roberts, MS, RDN, LDN
- Address: 250 E 40th St, New York, NY 10016  (lat 40.7487, long -73.9735)
- Neighborhood: Murray Hill
- Source: https://www.ehlers-danlos.com/directory/morgan-roberts/
- Notes: remove the Address / EDS-directory-link lines

### Myranda Oettel, PT, DPT  (page `3fed6b2867f48161b25ccbc7f3f1719e`)
- Address: 5 E 98th St, SB-Rm 18, New York, NY 10029  (lat 40.7889, long -73.9532)
- Neighborhood: East Harlem (Mount Sinai)
- Source: https://www.ehlers-danlos.com/directory/myranda-oettel/
- Website: https://www.coresinai.org/
- Practice: Mount Sinai CoRE
- Notes: remove the Address / EDS-directory-link lines

### Natalie Trubin, PT, DPT, PCES  (page `3fed6b2867f48134b7daed3664341b65`)
- Address: Telehealth only  (lat 40.7445, long -73.9843)
- Neighborhood: Telehealth only (Spear, NoMad)
- Source: https://www.ehlers-danlos.com/directory/natalie-trubin/
- Specialty: Physical Therapy, Pelvic Floor PT
- Notes: remove the Address / EDS-directory-link lines

### Noha Elsadek, PT, DPT, PRCP, ISST-Schro  (page `3fed6b2867f481398869d5fe6f409b18`)
- Name: Noha Elsadek, PT, DPT, PRCP, ISST-Schro
- Address: 275 4th Ave, Brooklyn, NY 11215  (lat 40.6755, long -73.9843)
- Neighborhood: Park Slope / Gowanus, Brooklyn
- Source: https://www.ehlers-danlos.com/directory/noha-elsadek/
- Notes: remove the Address / EDS-directory-link lines

### Rehabologym Corp, PT, OT, SLP  (page `3fed6b2867f481318ff0f04c2e6785ce`)
- Neighborhood: Tarrytown (Westchester); telehealth available
- Notes: remove the Address / EDS-directory-link lines

### Rachel Harlich, LCSW  (page `3fed6b2867f48135b004e3f85af2e66c`)
- Address: Telehealth only  (lat 40.693, long -73.991)
- Neighborhood: Telehealth only (NY)
- Source: https://www.ehlers-danlos.com/directory/rachel-harlich/
- Notes: remove the Address / EDS-directory-link lines

### Shane Rutkowski, L. Ac. , Dipl. Ac  (page `3fed6b2867f481b6b4aaeb53bf9ea350`)
- Name: Shane Rutkowski, L. Ac. , Dipl. Ac
- Address: 32 Union Square East, Suite 612, New York, NY 10003  (lat 40.7357, long -73.989)
- Source: https://www.ehlers-danlos.com/directory/shane-rutkowski/
- Notes: remove the Address / EDS-directory-link lines

### Staci Hoover, LCSW  (page `3fed6b2867f4817588c5d9fd2222295c`)
- Address: Telehealth only  (lat 41.7004, long -73.921)
- Neighborhood: Telehealth only (NY & VT)
- Practice: Secure Self Care
- Notes: remove the Address / EDS-directory-link lines

### Stephanie Bostic, PhD, RD  (page `3fed6b2867f4814697bafc453227797d`)
- Name: Stephanie Bostic, PhD, RD
- Address: 35 Front St, Binghamton, NY 13905  (lat 42.099, long -75.918)
- Neighborhood: Binghamton; telehealth available
- Source: https://www.ehlers-danlos.com/directory/stephanie-bostic/
- Website: (clear)
- Notes: remove the Address / EDS-directory-link lines

### Sueanne Baddour, DNP, APRN, FNP  (page `3fed6b2867f48112b896de3aca08ae4e`)
- Name: Sueanne Baddour, DNP, APRN, FNP
- Address: Telehealth only  (lat 44.4759, long -73.2121)
- Neighborhood: Telehealth only
- Source: https://www.ehlers-danlos.com/directory/sueanne-baddour/
- Specialty: Diagnostics
- Practice: Well-Being Hypermobility & EDS Care
- Notes: remove the Address / EDS-directory-link lines

### Taden Gery, PT, DPT  (page `3fed6b2867f481368e55c0edb5194d04`)
- Address: 310 W 72nd St, Suite 1G, New York, NY 10023  (lat 40.7793, long -73.9838)
- Neighborhood: Upper West Side
- Notes: remove the Address / EDS-directory-link lines

### Tiana Pallister, MS, CGC  (page `3fed6b2867f481c0920cec024a2285d4`)
- Name: Tiana Pallister, MS, CGC
- Address: Telehealth only  (lat 45.677, long -111.0429)
- Neighborhood: Telehealth only
- Source: https://www.ehlers-danlos.com/directory/tiana-pallister/
- Practice: Pallister Genetics
- Notes: remove the Address / EDS-directory-link lines

### Valerie Rogers, PT, DPT  (page `3fed6b2867f4814fb711db8cc1d9dbbd`)
- Address: 5 E 98th St, New York, NY 10029  (lat 40.7889, long -73.9532)
- Neighborhood: East Harlem (Mount Sinai)
- Source: https://www.ehlers-danlos.com/directory/valerie-rogers/
- Practice: Mount Sinai CoRE (Cohen Center for Recovery from Complex Chronic Illness)
- Notes: remove the Address / EDS-directory-link lines

### Victor Volle, MD  (page `3fed6b2867f48143abe3d541ec4506c6`)
- Name: Victor Volle, MD
- Address: Telehealth only  (lat 40.799, long -73.968)
- Neighborhood: Telehealth only
- Source: https://www.ehlers-danlos.com/directory/victor-volle/
- Practice: EDS Connective
- Notes: remove the Address / EDS-directory-link lines

### Vikas Gupta, MD, MPH  (page `3fed6b2867f4818383e9e7d5a4979bc9`)
- Address: 325 5th Ave, New York, NY 10016  (lat 40.7474, long -73.985)
- Neighborhood: Midtown South / Koreatown
- Source: https://www.ehlers-danlos.com/directory/vikas-gupta/
- Notes: remove the Address / EDS-directory-link lines

### Yaniv Larish, MD  (page `3fed6b2867f4815c9067eabdfa18c37c`)
- Name: Yaniv Larish, MD
- Address: 5 E 83rd St, New York, NY 10028  (lat 40.7779, long -73.9602)
- Neighborhood: Upper East Side
- Source: https://www.ehlers-danlos.com/directory/yaniv-larish/
- Notes: remove the Address / EDS-directory-link lines

### Yael Cohn, PT, DPT  (page `3fed6b2867f481e9b1d2e4748eecc4ab`)
- Address: 241 E 86th St, Suite 2B, New York, NY 10028  (lat 40.7786, long -73.9527)
- Neighborhood: Upper East Side / Yorkville
- Source: https://www.ehlers-danlos.com/directory/yael-cohn/
- Notes: remove the Address / EDS-directory-link lines

### Yuri Brosgol, MD  (page `3fed6b2867f48111bb57c108374ecf64`)
- Address: 11 W 25th St, 5th Fl, New York, NY 10010  (lat 40.7437, long -73.99)
- Neighborhood: NoMad / Flatiron
- Notes: remove the Address / EDS-directory-link lines
