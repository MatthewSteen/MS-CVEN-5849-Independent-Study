# Abstract

https://www.elsevier.com/journals/renewable-and-sustainable-energy-reviews/1364-0321/guide-for-authors

# 1. Introduction

Electrification trend vs. other fuels

How the grid works - supply, demand

How do GEBs fit in to recent trends, needs

# Methods and materials - Literature review

[Grid-interactive Efficient Buildings Technical Report Series: Overview of Research Challenges and Gaps](https://www1.eere.energy.gov/buildings/pdfs/75470.pdf)

## Demand-Side Management

The DOE defines the following DSM strategies for buildings that can be implemented to manage load on the grid.

1. Efficiency 
2. Load Shed  
3. Load Shift
4. Modulate
5. Generate

Efficiency is a reduction in energy use while providing the same or improved level of energy service(s). Graphically, efficiency is represented by a y-axis shift downward. Load shed is the ability of a building to reduce electricity use during a short period, which typically occurs during times of peak demand or emergencies and on short notice. Load shift is the ability to change the timing of electricity use, which is graphically represented by flattening the load curve. Modulation is the ability to balance real power supply with demand or the ability to balance reactive power draw with supply...
Generation is the ability to produce electricity for consumption on-site or to dispatch electricity to the grid in response to a signal from the grid operator. For the purposes of GEBs, the DOE identifies load shed, load shift, and modulation as demand flexibility strategies.

## Grid Services

Grid services provide value through avoided electricity system costs by supporting the generation, transmission, or distribution of electricity. The potential value of a DER can be quantified by estimating the avoided cost of acquiring the next least expensive energy resource that provides comparable grid services. Examples of current mature demand-side resources are energy efficiency and demand response. 

### Energy Efficiency

Energy efficiency improves grid reliability by decreasing peak demand and reducing strain on the T&D system. By reducing load, energy efficiency improves reliability on the supply side by increasing the system's reserve margin by offsetting generation that would otherwise be needed. Energy Efficiency also improves T&D reliability by increasing available capacity in both low-voltage and high-voltage systems. To defer costly T&D upgrades, some utilities have used geographically-targeted energy efficiency programs to reduce strain.

From the demand-side perspective, the value that demand reduction from energy efficiency provides is a function of the amount, timing, and location of the savings. From the supply-side perspective, the value of energy efficiency is a function of the system's characteristics such as the peak demand timing (seasonal, diurnal, etc.), load factor, and reserve margin. For example, load reductions that occur during times of peak demand are more valuable than reductions that occur during off-peak times. From the T&D perspective, an important energy efficiency benefit is reduced marginal line losses, which are higher during times of peak demand due to resistive losses that scale non-linearly (i.e. with the square of current according to Joule's first law). These marginal losses must be covered by a utility's generating reserve, which makes on-peak energy efficiency more valuable.  

### Demand Response

In contrast to energy efficiency, which focusses on reducing energy consumption, demand response focusses on reducing peak power requirements through the timing of energy use. Demand response is also the most common form of demand flexibility currently in use in commercial and residential buildings. From the perspective of building owners, demand response can provide reduced utility costs by avoiding high peak demand charges and providing incentives for reducing demand during peak periods. From the perspective of the grid, demand response can provide increased reliability by reducing operating costs and deferring or avoiding capital upgrade costs. 

Demand response can be classified into two types, dispatchable and nondispatchable, depending on who initiates the response to a peak demand event. Dispatchable demand response is initiated by the utility, grid operator, or third-party aggregator to directly control building systems to reduce demand during a peak event. Nondispatchable demand response is initiated at the building in response to price signals. 

## Grid Services Potential

TODO

## Grid-Interactive Efficient Buildings

### Characteristics

The DOE defines a GEB as "an energy efficient building that uses smart technologies and on-site DERs to provide demand flexibility while co-optimizing for energy cost, grid services, and occupant needs and preferences, in a continuous and integrated way". DOE characterizes GEBs further as having four general characteristics.

1. Efficient
2. Connected
3. Smart
4. Flexible

First, GEBs reduce demand on the grid by using less energy through efficiency. Second, they are connected allowing two-way communication with the grid by sending and receiving signals to respond to time-dependent needs. Third, GEBs are smart by using sensors and controls that allow the co-optimization of cost functions from the perspective of the building owner, occupants, and grid through the use of analytics. Finally, they are flexible allowing loads to be shaped dynamically. These characteristics are facilitated by capabilities at the component level and system level where individual components can monitor and send information about their status and receive control commands to shed, shift, or modulate loads from the building's control system.

### Operational Strategies

TODO

## Technologies

Technologies that are suitable for GEBs are organized below by design discipline. Alternatively, these could be organized based on commonalities (if any) in the literature review.

### Architectural

[Grid-interactive Efficient Buildings Technical Report Series: Windows and Opaque Envelope](https://www1.eere.energy.gov/buildings/pdfs/75387.pdf)

Architectural technologies that are suitable for GEBs include systems that separate the outdoor environment from the conditioned indoor environment (collectively the building envelope). These systems can be divided into the opaque envelope (floors, roofs, walls) and windows, and further categorized as having static, dynamic, or both properties that provide grid services through demand-side management strategies. Architectural technologies affect cooling, heating, and lighting energy end uses by decreasing assembly thermal transmittance (U-factor), decreasing or increasing solar heat gain through windows, or by allowing or blocking visible light to interior spaces.  

#### Static Systems

Static building envelope systems do not have dynamic or time-varying properties relying instead on inherent high performance properties that manage heat transfer, thermal bridging, and air flow (infiltration) through the system assembly. These properties can be a result of a single system component that contributes to the assembly's overall performance, such as a layer of insulation with high thermal resistance (R-value), or the result of multiple system components, such as reduced thermal bridging and air flow. Because static envelope systems do not dynamic properties they are primarily an energy efficiency DSM strategy, although they can passively shift load by delaying peak cooling and heating loads compared to lower performing systems.   

ADD EXAMPLES, CONSIDER INCLUDING RESILIENCY TERMS (PASSIVE SURVIVABILITY ETC)

#### Dynamic Systems

Window Systems

* Dynamic Glazing
* Automated Attachments
* Photovoltaic Glazing

Dynamic building envelope systems have properties that can be actively modified to decrease or increase their performance to achieve desired DSM strategies and grid services. Currently available dynamic envelope technologies include dynamic glazing and automated attachments. 

Dynamic glazing technologies include electrochromic glazing and thermochromic glazing that change tint (solar heat gain coefficient, SHGC) allowing more or less solar radiation into the building. Electrochromic glazing has more than one tint state (SHGC) compared to non-dynamic glazing, that can be changed by applying electric voltage to an electrochromic layer. Thermochromic glazing passively responds to temperature to change its SHGC. 

Automated attachments include exterior and interior devices that open or close to allow or block solar radiation into the building. Examples include interior devices such as blinds and shades, and exterior devices such as awnings or shutters. 

Photovoltaic glazing generates electricity the same way that traditional photovoltaic modules do, but are semi-transparent or transparent allowing some portion of visible light to pass through. Thus, PV glazing acts as part of an electricity generating system and a window system.

Opaque Systems

* Tunable Thermal Conductivity Materials
* Thermally Anisotropic Systems
* Thermal Storage
* Moisture Storage and Extraction
* Variable Radiative Technologies
* Building-Integrated Photovoltaics

Tunable thermal conductivity materials have thermophysical properties that can be dynamically adjusted to produce a desired thermal performance. For example, during cooling periods these materials would have high thermal transmittance (low R-value) when the outdoor temperature is lower than the indoor temperature to precool the building effectively acting like night flushing without the need for mechanical ventilation. Conversely, in the heating season these materials would have low thermal transmittance (high R-value) to minimize heat loss to the outdoors.

Thermally anisotropic systems include components and assemblies with areas of high and low thermal conductivity that allows heat to be routed through the envelope to a heat sink such as a plumbing loop.

Thermal storage materials have variable heat capacity properties that allow them to release or store heat. They behave similarly to passive thermal mass, such as strategically adding materials with high heat capacity, but with less volume and weight. Phase change materials (PCMs) are a type of thermal storage material that passively charge and discharge. PCMs are currently available but are not widely used in buildings.

Moisture storage and extraction...

Variable radiative technologies include materials that can reject heat during the daytime or even in direct sun. Cool roofs are a well established strategy to reduce cooling loads in warm/hot climates that are not appropriate for colder climates because they do not decrease energy use. These strategies are currently passive, but if they could be dynamically controlled to change their radiative heat transfer properties they could provide additional grid services through expanded DSM functions.

Building-integrated photovoltaics, although part of a building's electrical system, refer to PV integrated into the opaque portions of the envelope. For example, wall cladding or roof shingles. 

### Electrical



### Mechanical



### Plumbing



# Results

Categorize measures and technologies that are suitable for GEBs.

* Bassed on design discipline
  * Architectural
  * Electrical
  * Mechanical
  * Plumbing
* Based on literature review

# Discussion

TODO

# Conclusions

TODO