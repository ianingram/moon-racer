# Moon Racer — ideas, parked

Ideas we've agreed are worth doing, but not yet. The game comes first: the
canyon run, the lane and the landing need real flying on real hands before
anything here is built. Anyone picking this up (a person or a new chat):
read this, then the Moon Racer skill, then the files.

---

## On the water

The craft are caravels: they can sail as well as fly. Landing on water is
**optional** — a third way to travel in a run, beside the deck and the jump.

- **Setting down:** ease down slowly over open water and the craft settles
  on the surface; fast is a hard splash (costs speed, like debris).
- **On the water:** engines drive it like a boat. Slower than flying, but
  drinking at full rate the whole time and no heat from speed — a place to
  refuel and cool down.
- **Downstream** the current carries you, cheap on fuel. **Upstream** you
  fight it — slow and costly, but the way back to a missed gate or a
  better jump point.
- **Taking off:** open the throttle and climb to the deck. A flood-and-jump
  from the water itself is the strongest launch.
- A few optional gates at water level where the gorge is narrowest.

What it opens up later:

- Every coast and river as a route; harbours to rest and refuel.
- Ocean crossings: sail to save fuel, lift off near the far coast.
- Water starts and finishes (the Nile at Giza; a lake instead of a runway).
- Upstream runs as their own challenge.
- Weather on the water — swell, storms, calm — for the sea routes.

## The copilot

- **True AI answers.** The copilot answers questions from the manual now.
  Real conversation (the Claude API, aware of your fuel, heat and position)
  needs a small relay to hold the key — e.g. a Cloudflare Worker — because
  GitHub Pages is static. *Only after the game is bug-free.*

## Players

- **Quick run:** just the canyon, one click from the home page, playable
  before reading a word — for the few-moments player.
- **Ghost of your best run:** replay your best line as a ghost craft (the
  pathfinder already proves a craft can fly a recorded line). Later, other
  people's times.
- **Touch controls** for phones and tablets — the biggest single job; the
  game can't be played on touch at all yet.
- **Bend governor** (discussed, not built): eases the engine back just
  enough before a bend too tight for your speed; visible (GOVERNED), on by
  default, switchable off for racers. Or the lighter version: show the safe
  speed for the next bend and let the copilot call it.

## The world

- **Landing plateaus several hundred miles from each site**, where the
  pyramid is erected and its beacon lit. Flattest high ground found in the
  real elevation data around Hells Canyon (within 400 km):
  - Grande Ronde Valley, Oregon (La Grande) — ~820 m, 95 km W
  - Baker Valley, Oregon — ~1,020 m, 97 km SW
  - Long Valley, Idaho (McCall–Cascade) — ~1,480 m, 74 km E
  - Treasure Valley, Idaho (Boise) — ~750 m, 180 km S
  - Columbia Plateau, Washington — ~700 m, 250–290 km N
- **Leg two:** Hells Canyon → Devils Tower, Wyoming (~900 km) — short
  enough that the low road over the Rockies competes with the lane.
- **The other megalithic sites:** Stonehenge, Teotihuacan, Devils Tower,
  Angkor Wat, Göbekli Tepe, Easter Island, Machu Picchu, Chichén Itzá,
  Baalbek, Newgrange, Carnac, Puma Punku, Great Zimbabwe, Borobudur, Uluru.
- **The other routes** on the start screen (By Water, the Northwest Passage,
  the Low Road) — "not built yet". They are what builds out the **mid-air
  layer**: cloud, weather and coastlines to fly through.
- **Humidity map:** bake NASA's global water-vapour data into one small
  image, so fuel from the air depends on where you really are (humidity
  rising across coastlines, low over deserts).
- **Route balance:** make the lane pay at its ends (a bigger fuel cost to
  climb out, harsher re-entry heat) so short legs favour the low road and
  only long legs pay for the lane.
- **Align the lane's end** with the run's entry point exactly.

## Later still

- **The planets:** each with its landing zone on a plateau. Open question:
  Jupiter and Saturn have no surface — a platform at the cloud tops, or
  land on a moon (Europa, Ganymede, Titan)?
- **Ian's calendar function** (drafted, not yet shared): set dates and
  calendar events and surf the solar system — Moon Racer's sky already
  computes any date.
- **The cockpit console** (`console.html` is the mockup): build it live into
  the canyon and the lane — ORBIT globe, FLIGHT readings, SEA LEVEL plan
  and profile.
- **The 3D globe** could get the console globe's axis, pole labels and
  Arctic/Antarctic Circles, so the two match.
- **A dark start map** with the same coastlines as the dark globe.
- **Every guide as probe vapour:** the line to water, the line to the
  landing field and the jump arcs could all come from the probe's vapour
  rather than drawn lines.
