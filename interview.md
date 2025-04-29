# Interview
## Personal Interview
Q: Introduction\
A: My name is Sourav Mahato. I'm from Jharkhand.\
I did my B.Tech. in Mechanical Engineering from National Institute of Technology, Jamshedpur.\
After that I joined Deloitte USI as an Analyst & I'm still working there.\
My hobbies including Football, Video Games & watching Nature Documentaries.

Q: Why do you want to join IISc?\
A: I want to work on what I personally consider to be the biggest challenge that our generation have to solve - Climate Change.
- Climate Policy: I'm interested in it becuz, I don't think we lack the technolgy to stop Climate Change, what we lack is an effective communication with Gov. I don't think politicians even understand when we say something like - "We need to stop the Global Avg Temp from rising more than 1.5 degrees from that of pre-industrial levels.\
I also want to explore Academia.\
I have already tried Corporate life.
- Some things I liked & some didn't.

Liked:
- I learned basics of Linux which is a very good personal skill addition
- I used Python in some practical scenarios for automation. Ex: Automating metadata ingestion, automated metadata lineage creation.

Didn't liked:
- Work life balance was very messed up. I login at around 9:30 AM but the logoff time completely depends on when the American clients have scheduled the meeting in the evening.
- I have very little control over what I have to learn, it's almost forced onto me by the company or the market.

Q: What did you do in N.I.T. Jamshedpur?\
A: I was interested in Maths, Mechanics, Programming, Fluid Mechanics & ML. I was not very interested in the core subjects of Mechanical like IC Engines, Design, CAD, etc.\
I enjoyed sports a lot. I was the captain of NIT Jamshedpur Football team.

Q: Hobbies?\
A: Football, Video Games, currently trying to learn how they work underneat the hood.

## Fluid Mechanics
**Fluid:** In scientific terms, a fluid is defined as any substance that flows or deforms under applied shear stress.\
**Viscosity:** It is the property of a fluid that obstructs the flow of the fluid.\
**Laminar** v **Turbulent** v **Transition** flow\
Streamline v Streakline v Pathline\
Boundary Layer\
Linear Strain Rate\
Why do we study boundry layer in 2D?

### Classification of Fluid
DPRT → Dilatant, Pseudo Plastic, Rheopectic, Thixotropic

#### Shear Stress v Rate of Shear Strain (Shear Rate)
**Viscosity:** Slope of the curve.

Newtonian: Air, water, diesel.\
**Bingham:** Toothpaste, Gel, Cream, Mud\
**Dilatant:** (Shear thickening fluid) Viscosity increases with increase in rate of shear strain. Ex: Honey, Sugar sol, Cornstarch.\
**Pseudo Plastic:** (Shear thinning) Viscosity decreases with increase in rate of shear strain. Ex: Paint, Blood, Milk.\
**Rheopectic:** (Time-dependent shear thickening) Time-dependent increase in viscosity; the longer the fluid undergoes shearing force, the higher its viscosity. Ex: Gypsum Paste\
**Thixotropic:** (Time-dependent shear thinning) Certain gels or fluids, that are thick under static conditions, will flow (become thinner, less viscous) over time when shaken.

#### Surface Tension
**Def:** It is the tendency of liquid surfaces at rest to shrink into the minimum surface area possible.

### Pressure Measurement
#### Liquid
1. Simple manometer
    1. Piezometer
    2. U-tube manometer
    3. Single column manometer
    4. Inclined manometer
2. Differential manometer
    1. Inverted manometer
    2. Multi U-tube manometer

#### Non-liquid
1. Bourdon tube
2. Diaphragm guage
3. Bellow type

#### Barometer
It gives gauge pressure but since vapour pressure of _Hg_ is negligible infront of atmospheric pressure, it is nearly equal to absolute pressure.

Q: Why do we use Mercury (_Hg_) in barometer?\
A: Becuz of:
- High specific wt.
- Low vapour pressure.
- Imiscible with other fluids.

Q: Why boiled food remains uncooked in Mountaneous region?\
A: Food cooks becuz of Thermal Energy & not becuz of Pressure Energy. If phase change starts happening at say 90 degree C, the food will never reach temperature above 90 degree C.

### Cavitation (aka Pitting)
**Def:** In fluid mechanics & engineering normally is the phenomenon in which the static pressure of a liquid reduces to below the liquid's vapor pressure, leading to the formation of small vapor-filled cavities in the liquid.

### Hydrostatics
**Center of Pressure:** It is the point through which the Pressure Force acts.

### Buoyancy
**Center of Buoyancy:** Geometric Center / Centroid of the submerged port.

#### Metacenter
The point at which a vertical line through the heeled centre of buoyancy crosses the line through the original, vertical centre of buoyancy is the metacentre. The metacentre remains directly above the centre of buoyancy by definition.

**Metacentric Height (GM):** It is calculated as the distance between the centre of gravity of a ship & its metacentre.

| M & G orientation | Stability |
|--|--|
| M above G | Stable |
| M below G | Unstable |
| M & G coincides | Neutral Eqm |

## Fluid Dynamics
- Navier Strokes Eq.
- Euler's Eq (Linear Momentum Conservation) (by neglecting Viscous Forces)
- Bernoulli's Eq (Conservation of Energy) (by integrating Euler's Eq)

### Bernoulli's Eq
Assumptions of Bernoulli's eq:
1. **Steady Flow:** Properties don't change with respect to time.
2. **Incompressible Flow:**
    - Incompressible fluid will always have an incompressible flow.
    - Compressible fluid is considered to have an incompressible flow if `viscosity < 0.32`.
3. **Non-viscous Flow / Invicid Flow**
4. **Irrotational Flow**. Only valid along the steamline in **Rotational Flow**.

## Mechanics
Newton's Laws

## Heat Transfer
**Thermodynamics:** I am not sure, but everything related to understanding heat transfer mechanisms (conduction, convection, radiation, latent heat), the ideal gas law, hydrostatic balance, the first law of thermodynamics, etc. Be thorough in those basic concepts and fundamental equations

## Data Science
