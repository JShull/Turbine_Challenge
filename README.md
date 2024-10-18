# Augmented Reality Turbine Challenge

* ![Turbine Image](/Media/TurbineFront.jpg)
* ![Turbine Front Render](/Media/TurbineRenderFront.png)
* ![Turbine Back Render](/Media/TurbineRenderBack.png)
* [Video of the pieces](/Media/Turbine_Model_Parts.mp4)
* [Video of the AR Development side](/Media/Turbine_AR_Dev_2024-10-18.mp4)


## The Concept

This is a simple externally modelled turbine designed around off-shore wind turbines and it's intention is to be designed privately and to be released to the public. If you're looking for more complicated one that actually has the ability to store energy please use another model! This original design was intentionally restricted to easier 3D printing on print bed sizes like the [Prusa MK4](https://www.prusa3d.com/product/original-prusa-mk4s-3d-printer-5/). The model's main purpose is for ease of use and to accompany a school lesson plan and/or activity. That information won't be hosted on this site but will have linked information for those interested in that. The information in this repository is solely around releasing the design and accompanying media. All of that being said, the turbine is designed in a way to be extended with other options (attach a gear to the horizontal axel...) but for the time being a simple print that has some mechanical pieces for classroom discussion and/or a classroom build with the intention of other material to accompany it.

## Augmented Reality and 3D Printing

This build is a smaller piece into a larger hands-on activity that others I work with are putting together. We as a group help coordinate and build various activities to support local state and community interests and needs. At the moment (10-18-2024) we are building the AR iOS application designed for Apple iPads that will accompany this 3D print - that should be done by end of 2024 and hopefully go through the University process to get it on the store front sometime in Q1 2025. In the meantime, this 3D print can be used as a simple way to introduce wind turbines and things like blade angle and the major components. As that process is more finalized links will be provided and this repository will be updated.

### Bill of Materials

* Larger Print
  * Mechanical Parts List
    * Bearings: Quantity 4: [14mm x 5mm x 5mm Bearings](https://www.amazon.com/gp/product/B07FDTC4BX/ref=ppx_yo_dt_b_asin_title_o00_s02?ie=UTF8&psc=1)
    * Magnets: Quantity 3 or 6: Turbine | Turbine & Base Plate[12mmx3mm Magnets](https://www.amazon.com/gp/product/B09Q8L2KYD/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
    * Main Vertical Axel and Horizontal Axel: Quantity 2 [m5 120mm Bolt](https://www.amazon.com/dp/B0DFLT9VLY)
    * Main Blade Assembly: Quantity 3: Used for connecting the blades to the assembly [m5 40mm Bolts](https://www.amazon.com/dp/B0CSWBV7XH)
    * Hex Nuts: Quantity 6 or 8: they come with most of the M5 kits you buy
  * 3D Printed Parts List
    * Nose Cone Cover
    * Blade Assembly Cone
    * Housing
    * Turbine Blade(s) - 3 of them
    * Housing Knob
    * Bottom Lower Tube
    * Upper Lower Tube
    * Base Plate
    * AR Marker Plate

### Assembly

**Scaling Notes** Currently (10-18-2024) there are two STL files that need to be scaled 167% before printing them. These are clearly named in the [Geometry folder](/Geometry/).
**Notes** Overall there are two general ways to combine the sections and depending upon the need you could opt out of the base plate. The base plate helps widen the base so if you wanted to have the turbine free stand (not magnet base). You can also use it magnetically. I kept the base plate separate from the other lower tube because the original tube and the lower tube were sized for the m3 configuration and then scaled up in the slicer.

* There are two ways to build the main housing/blade setup:
  * 1: approach: use a hex nut on the assembly cone before you put in the cone bearing thus locking the center 120mm bolt to spin with the nose cone, blade assembly, and housing knob - this spins 'okay' and could then be used later to attach a gear instead of the housing knob.
  * 2: approach: don't use the hex nut on assembly cone, use spacers and/or an additional hex nut between bearings to have the 120mm bolt free spin - this spins 'better' but at the cost of the housing knob no longer moving.

* Housing
  * Uses 2 bearings on either side of the main housing, they should squeeze in with a pair of pliers.
  * Drop in your vertical 100 or 120mm bolt before adding the assembly cone to the front
* Blade Assembly Cone
  * Each blade has to be put on one by one to get the m5 bolt head clear of the center main horizontal axis/axel 120mm bolt placement
  * Use the 40-50mm m5 bolt and drop in the hex nut on the blade slot.
* Housing Knob
  * Three ways to configure hex nuts: but you mainly use the interior center slot and one of the ends
  * Smooth rounded over edge goes into the Housing but it could be flipped for whatever reason.
* Bringing everything together
  * **Make sure you have the vertical 100 or 120mm bolt in the housing before you attach the nose**
    * Use the hex nut on the under side of the vertical opening on the housing to tighten this top vertical axis/axel into position.
  * Depending upon if you want to have the bolt/horizontal axis/axel attached to the nose depends upon if you use the recessed hex nut on the backside of the assembly cone
    * Either configuration will have you then take the blade assembly cone and all blades on, slide the 120mm bolt through the front blade assembly and out the rear - you'd attach the hex nut before you then apply the bearing or you will just pop the bearing in without the hex nut tightened.
    * This axis/axel should go all the way through both housing bearings and come out the rear housing bearing
  * Configure the housing knob with the hex nuts to tighten it to the bolt or just to keep the nose cone from sliding out the front - depending upon how you configured the main horizontal axis/axel.
    * if you decided to use the front nose cone hex nut, then for the housing knob you might consider using an additional the front hex nut to make a clamp between it and the middle hex nut, there's an extra 10-15mm on the bolt for just this use case.
      * This then has the housing knob clamped to the bolt but not rubbing the housing back - consider also using some washers between the rear housing bearing and the housing knob
  * At this point the entire top assembly should be good with that vertical axis/axel ready to be attached to the base
  * Base assembly
    * Mainly glue or free form attached.
    * Put in the magnets on the lower tube
    * Slide in the upper tube into the lower tube
    * On the upper tube, there is an opening for a bearing to be squeezed into place
  * You should be able to just align the vertical axis into the lower tube bearing and have the top fit onto the base
