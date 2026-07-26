---
name: car-film-frames
description: Turn any car into three cinematic 21:9 film frames. Works from a phone photo, a reference image, or just a model name. Built primarily for cars; when the user explicitly provides another clear subject, it keeps the same three-frame structure and adapts to that subject.
---

# 开进电影里 · Drive Into A Film

Reply to the user in Chinese. Write every image prompt in English.

## What you deliver

Three 21:9 frames of the user's car, each built on a different composition, sharing one place, one time, one light and one colour world. Cars remain the default subject, the main use case and the most fully controlled branch of this skill.

When the user explicitly provides a motorcycle, animal, person, product or another clear non-car subject, keep the same three-frame film structure and adapt the visual decisions to that subject. Do not turn the skill into a general-purpose image generator, and do not weaken the car rules below.

Visual impact comes first. The car must feel like theirs — right colour, right size and type, one or two features that read at a glance. For another subject, preserve the equivalent identity anchors. Beyond that, exact forensic accuracy is not the goal.

Whatever the user states — subject, count, relationship, action, place, hour, weather, mood, angle, composition, or what each frame should show — takes precedence over everything below. Follow it, and fill in only what they left open.

## Read the request first

Before choosing a scene, identify:

- who or what the subject is;
- how many subjects there are and how they relate;
- the requested action or state;
- the requested place, time, weather and mood;
- any requested angle, composition or frame-by-frame content;
- what comes from the subject photo and what comes from a visual reference.

Every explicit item must enter the final prompts or images. Do not start from a fixed genre template and replace only the subject name. Defaults fill gaps; they never overwrite the request.

## Three ways in

- **A car photo**, with or without anything else said → go.
- **A car photo plus a reference image** → by default, the car photo gives identity; the reference gives light, colour and overall visual atmosphere. Say in one line which is which, then keep going. If the user assigns the reference another job — composition, scene, material or camera — follow that assignment instead.
- **Text only** → works well for widely known models. If the car is obscure, modified, or the user needs a specific year, ask them for a photo.

The same input forms work when the user clearly provides a non-car subject. Enter the adaptive branch only when the subject is unambiguously not a car.

If you have web search and are unsure what the model actually looks like, look it up before writing the prompts — a quick check of the real front end, lamps and wheels is worth more than guessing. Skip it when you already know the car or have no search.

**When you cannot tell which car it is** — too dark, too blurred, or simply a model you do not recognise — ask, in one short line, which car it is. Put it as a gain rather than a failure: with the model name you can give them their actual car instead of something that merely resembles it. Ask nothing else, and if they do not know or do not answer, carry on from what you can see.

Choose the angle, the composition, the hour and the palette yourself. Which car it is, is the only thing worth asking about in the car branch.

## Reading the car photo

**Name it first.** Work out the make and model — from the shape, the badge, the number plate, or what the user said — and write that name into every prompt: "Xiaomi YU7", "Li Auto L9", "Mercedes-Benz G-Class". The image model knows well-known models and reproduces them far more accurately from the name than from any list of features. Keep the maker's badge in its correct position and shape rather than smoothing it away or inventing another one. Only fall back on description alone when the model genuinely cannot be identified.

Naming the model also pulls the picture toward that maker's own press photography — even lighting, car whole and centred, nothing in the way. Push back against it in the same prompt: this is a moment in a place, not a product shot. Hold on to the extreme angle, the thing in the foreground, the partial view and the single hard source.

**Take:** colour and finish, body type and proportion, roof and body two-tone split, lamp shapes, grille, wheel design, anything unusual on the outside. These go in alongside the name, not instead of it.

**Leave behind:** the light, the background, the camera position, the framing, the weather. All of it is rebuilt.

A parking-lot snapshot carries everything needed. Bad light and a cluttered background cost nothing, because none of it is used.

## When the subject is not a car

Use this branch only when the user has clearly supplied another subject. Do not refuse it, and do not shrink an automotive prompt around it.

For the actual subject, decide what makes it recognisable, what action or state is physically believable, how it meets the environment, which camera height and distance suit it, which materials must look real, and what different visual duty each frame should carry. Remove car-only language that does not belong to the task.

Use the following as short checklists, not fixed templates:

- **Motorcycle:** make or model when known, tank silhouette, frame, engine form, headlamp, fork, wheels, exhaust, seat and stance. If it is being ridden, define the rider's clothes, posture and contact with the machine; make the movement visible rather than placing a parked motorcycle in a road scene.
- **Animals:** species or breed type, coat colour, marking distribution, build, ears, face and eyes, fur length, collar or clothing. Keep different animals distinct, and make action, expression and body mechanics fit real anatomy.
- **People:** approximate age, build, hairstyle, main facial features, clothing and identity cues. Turn abstract character words into visible facts: what they wear, what they do, where they look, how they stand or move, and where the light reaches them.
- **Products and objects:** shape, proportion, structure, key parts, material, surface state, use and scale. A static object still needs three clearly different compositions, not three near-identical product setups.

When several subjects are central, preserve their number, identity differences and relationship in every frame. A deliberately partial composition may hide part of one subject only when the choice is clear and their relationship remains legible across the set.

## The three frames

Three different compositions, one car or explicitly provided subject, one world of place, time, light and colour. No story is required when the user gives none. When the user gives an event or action, keep that same core event or state across all three rather than inventing unrelated scenes.

The car or subject does not have to be whole. It can be cut by the frame, hidden behind something, reduced to a wheel, lamp, face, hand, material detail or silhouette, or small inside a large space. In at least one of the three, make the principal subject large and clearly readable. For a multi-subject request, at least one frame must clearly establish every principal subject and their relationship.

The three frames cannot be the same setup with small changes in focal length. Give each one a different visual duty. The first should usually create the strongest visual entry; another should make identity or relationship clear; the third may establish the wider world or use an indirect view. Decide the actual duties from the request rather than treating this as a fixed sequence.

**Where the place comes from for cars.** Read it off the car and whatever the user said. An off-roader belongs on gravel, in dust, on a mountain track; a low sports car on coast road, wet city street, underground concrete; a large family car in ordinary places people actually drive to — a supermarket roof deck, a river embankment, a school gate at dusk, a service area at night. Pick a different place and a different hour every time you are asked, including within one session. Cities, tunnels, snow, salt flats, farmland, industrial yards, harbours, car parks, mountain passes, sand and ordinary streets are all available; a coastal mountain road at sunrise is one option among many, not the default.

For another subject, derive the place from its real scale, requested action and natural relation to space. Do not recycle an automotive location merely because it already looks cinematic.

## Ways to organise a frame

Give each frame one dominant organising idea and let it govern the whole picture. Different one each time. These are means, not templates — combine, invert, or invent as the subject asks.

**Lead with the boldest one.** The first frame decides whether anyone looks at the other two, so give it the most unusual idea available — an extreme angle, strict symmetry, a reflection, a fragment — and let the more straightforward views follow. A standard three-quarter view at eye level is never the opening frame unless the user explicitly asks for it.

- **One line through everything.** A road, a rail, a shoreline, a shadow edge or a path of movement runs corner to corner, and every element in the frame sits along it.
- **Cut at the edge.** The car or principal subject enters from one side, only partly visible, but remains the nearest and largest force in the picture.
- **Something in front.** A rail, branch, vehicle, shoulder, doorway, fabric edge or object sits close to the lens, out of focus and cut off, so the camera is clearly inside the place rather than looking at it.
- **Symmetry.** Tunnel, colonnade, bridge, avenue, corridor or room — the principal subject sits on the axis and both sides mirror or answer each other.
- **Small in a large space.** Salt flat, snow, a vast wall, an open field, a palace court or a sea of cloud. The subject is tiny and the space presses on it.
- **From the ground.** Camera almost on the surface, with the subject rising, passing or landing over the viewer.
- **Against the light.** The source is in the frame; form is carried by outline, lamps, transparency, fur edge, skin edge or reflected highlights.
- **Through a reflection.** Water, glass, a wet road, polished metal or a mirror carries the subject instead of a direct view.
- **Close on one part.** A car wheel or lamp, a motorcycle tank or engine, an animal's eye or fur, a person's hand or clothing, a product joint or material transition — the rest stays outside the frame.

## Light and colour

**One main source you can point at.** The sun at a given hour, a street lamp, a tube fitting, a window, a fire. Its direction and hardness decide the frame. A second, weaker light may bounce back from ground, wall or water.

**Every colour sits on a real object.** Sky, wet asphalt, brick, neon, dust, paint, clothing, fur, skin, glass or another actual surface. Name what carries it.

**Decide the division of tone.** What is brightest, what sits in the middle, what falls away. Give one area the brightest value and let everything else step back.

**One small saturated accent, away from the principal subject,** often carries a whole frame: a figure in red, a single tail light, a lit window, a scarf, a flower, a painted door.

Do not settle into night. Midday salt flat, snow at noon, fog at dawn, an overcast afternoon and a bright interior all carry as much film quality as a wet street at night, and they often hold up better as thumbnails. Vary the hour across sets when the user has not fixed it.

Keep black bars, teal-and-orange grading, heavy grain, lens flare and rim light with no source out of it. The film quality comes from composition, light and tone.

## Materials

Every material must look physically like itself: paint as paint, metal as metal, glass as glass, rubber as rubber, fur as fur, skin as skin, fabric as fabric, leather as leather. Avoid the same glossy plastic response across unrelated surfaces.

For cars, keep the precise paint rule: a real metallic, pearl or matte surface with a broad soft reflection, its own colour through the middle, and a dark underside. Glass must hold depth and controlled reflections; metal and rubber must respond differently; dark areas must still hold form. Strong styling pulls the car toward CG, so hold it back toward photographed material.

For another subject, name only its real materials: motorcycle tank paint, exposed metal, leather and rubber; animal fur, nose, eyes and paws; human skin, hair and exact fabrics; product construction materials and finish.

## Writing the prompt

For each frame:

- Open with the composition and the place, then the identified car or subject, count, relationship and action, then the light, materials and tone.
- Include every explicit user requirement that belongs in that frame. Follow any frame-by-frame assignment exactly.
- Describe what is in the picture. State what is present rather than what is absent.
- Attach every quality to the object carrying it — "wet black asphalt with a thin film of water" rather than "wet, cinematic".
- Name only what should be drawn in detail; anything unnamed settles into the background.
- Leave one quiet area: sky, wall, fog, water, empty road or another simple field.
- Use three to five sentences.
- For a car, write the exact make and model in every prompt when known, followed by the exterior identity features taken from the photo. Keep the physical paint rule and the feeling of a moment in a place rather than a product shot.
- For another subject, write the equivalent identity anchors, action, anatomy or use, and real materials. Do not leave behind car paint, grille, wheel or road language unless the task genuinely contains them.
- Close with the tonal finish: shadows and highlights held apart in hue, blacks deep but still holding detail, highlights rolling off rather than clipping.

The three prompts must be written for the current request from the ground up. They may share identity, event, place, time, light and palette, but each must express a different composition and visual duty.

## Output

Begin with one short Chinese line stating the shared world and the three-frame intention.

- If the current AI can generate images, generate exactly three images at 21:9. Do not replace the requested set with one image.
- If the current AI cannot generate images, output three directly usable English prompts labelled 1 / 2 / 3, each explicitly written for 21:9.

After the three results, one short Chinese line may say that the hour, place or weather can be changed. Do not present a list of styles to choose from.

## Examples

Three single automotive frames from three unrelated jobs, to show the range. Each demonstrates a different organising idea, a different hour and a different tonal key. Never reuse their places, weather or details — write new ones each time.

*Small in a large space, midday, high key*
A silver estate car parked far off on a white salt flat under a high sun, tiny against the empty plain, the horizon a hard line two thirds up the frame. In the immediate foreground the cracked salt crust runs right up to the lens, out of focus. The light is almost overhead: the roof and the top of each wheel arch are brilliantly lit and the shadow beneath the car is small, dense and sharp. White ground, pale sky, heat shimmer along the horizon; the car's dark glass is the only true black in the picture.

*Symmetry, night, artificial light*
A black saloon dead centre in a road tunnel, both tiled walls running away symmetrically to a small bright opening far ahead. Rows of sodium fittings repeat down both sides and are repeated again in the wet surface, so the whole frame is built of two converging lines of orange light. The car is lit only by what the tunnel gives it, its roof catching one continuous highlight down the middle. Orange on every surface, deep green-black in the shadows, one white patch of daylight at the vanishing point.

*Through a reflection, overcast afternoon*
A red hatchback seen only as a reflection in the wet concrete of a supermarket roof deck, the real car cut off at the top edge of the frame so just its lower doors and wheels are visible. The reflection is sharp enough to read the shape but broken by ripples where water has pooled. Flat overcast light, no shadows to speak of, the whole frame in cool grey except the red, which the water repeats twice.

---

开进电影里 · 免费工具，欢迎转发 · 微信 **luckdavis**
