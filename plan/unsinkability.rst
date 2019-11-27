.. -*- mode: rst; coding: utf-8 -*-

==============================
Tammy Norie Unsinkability Plan
==============================

:Tag: plan.unsinkability
:Author: Richard Brooksby <rptb1+tammy-norie@pobox.com>
:Date: 2019-11-14
:Readership: author, boat engineers, long distance solo sailors
:Confidentiality: public
:Copyright: `CC BY-NC-SA 4.0`_

.. _CC BY-NC-SA 4.0: http://creativecommons.org/licenses/by-nc-sa/4.0/


1. Introduction
===============

This document explains how and why I intend to make Tammy Norie
unsinkable.

The document uses the conventions of an engineering project at my
company, `Ravenbrook`_ [RB-1998]_.  In particular:

- It uses tagged statements (with dots) as cross-references.

- Comment *about* the document that aren't *part* of it are enclosed
  in square brackets.  These are often notes of things that need
  further work.

I've included a brief explanation of the purpose of each section so
that you can get the idea.

.. _Ravenbrook: https://www.ravenbrook.com/


2. Goals
========

_`.goals`: The goals section explains the purposes of the project.

_`.goal.survival`

  Increase chance of survival in the case of a hull
  breach or other catastrophic failure at sea, especially on long
  distance solo passages.

_`.goal.save-boat`

  Reduce chance of loss of boat and all it contains.

_`.goal.benefits`

  Provide other benefits such as insulation, soundproofing, and padding.


3. Requirements
===============

_`.requirements`: The requirements section defines what would achieve
the `.goals`_ in a measurable way, but does *not* presuppose *how* to
achieve them.  They can be used to evaluate whether a design and
implementation are successful.

_`.req.haven`

  Boat remains a safe haven in the case of a hole in the hull which
  can't be fixed for many days.  [Ref to Adrift for 72 days.]

_`.req.chop`

  If you break the boat into pieces, most of them float and some of
  them are liferafts.

_`.req.suitable`

  Suitable for Tammy Norie [TODO: clarify -- is this just time and
  cost?].

_`.req.preserve`

  Does not permanently change the fundamental nature of Tammy Norie as
  an example of a well-preserved Newbridge Coromandel in near-original
  condition.

_`.req.useful`

  Does not significantly limit Tammy Norie's usefulness as a coastal
  cruiser for friends and family, even while it makes her safer as an
  ocean-going passagemaker.

_`.req.time`

  Can be fitted by me in reasonable time [TODO: clarify].

_`.req.cost`

  Material costs less than GBP 1000.

_`.req.maintainable`

  Maintainable [TODO: clarify].

_`.req.removable`

  Can be removed and replaced with reasonable cost and effort.  [How
  does this compromise bonding?]

_`.req.access`:

  Must not impair access to equipment or fittings.

  _`.req.access.seacocks`

    Must allow inspection and free access to seacocks in a hurry.
    Must allow for seacocks to be plugged in an emergency.

  _`.req.access.wiring`

    Must allow inspection and maintenance of electrical wiring —
    instrument, radio antenna, and lighting.

  _`.req.access.deck-fittings`

    Must allow access to the fasteners of deck fittings in the
    ceiling.

_`.req.safe`

  Must not introduce other hazards: fire, poison, access, etc.

  _`.req.non-flammable`

    The materials most not readily catch fire or burn or produce toxic
    fumes when burning.

  _`.req.non-toxic`

    The materials must be inert and not be toxic, since I will be
    exposed to them a great deal.


4. Design
=========

_`.design`: The design section explains *how* the `.requirements`_ can
be met to achieve the `.goals`_.


4.1. Overview
-------------

_`.design.displace`

  Attach `closed-cell foam`_ to the hull so that over 1 tonne of
  seawater would be dispalced by the air in the foam even if the boat
  is fully submerged, creating an upthrust greater than the weight of
  the boat [RB-2015-06-09]_ [RT-2007]_.

.. _closed-cell foam: https://en.wikipedia.org/wiki/Foam#Solid_foams

  Newbridge claim the Coromandel weighs 2000lbs (908kg) laden
  [Newbridge-1982]_ and so I'm using this as a guide.  The lack of
  precision in the 2000lb figure suggests an error of at least ±10%.
  I intend to measure the actual weight of Tammy Norie
  (`.plan.weighbridge`_).  Tammy has quite a lot of gear aboard in
  preparation for single-handed distance sailing, so there may be a
  surprise and a need for more floatation.  [TODO: Contingency plan.]

_`.design.lining`

  Most of the foam will be stuck [how?] to the interior of the boat as
  a lining, also providing insulation and padding for comfort
  (`.goal.benefits`_).

_`.design.cushions`

  The interior cushions will also be replaced with closed-cell foam
  cushions, so that they cannot take up water.  These will be secured
  to the interior by some means so that they do not detach when the
  boat is flooded [what means?].

_`.design.voids`

  Many accessible unused voids will be filled with foam — particularly
  the `.vol.coamings`_ — but not voids that are needed for drainage or
  access, or voids from which airtight containers can't escape (see
  `.design.containers`_).

_`.design.containers`

  It's not as useful as you might think to fill inaccessible voids
  with closed-cell foam where airtight containers (such as empty
  plastic bottles) will do. As long as they can't escape. Foam is good
  for surfaces.

  Additional precautions include storing as much as possible in
  watertight containers and bags which are half-filled with air.

_`.design.cover`

  The foam will need to be covered with a lining to protect its
  surface and to reflect light, since it is usually matt black.
  Conventional vinyl headlining material is probably the right thing.


4.2. Volumes
------------

_`.vol`: These are the volumes in the boat where closed-cell foam can
be fitted, so that water cannot replace the air and sink the boat.

_`.vol.sides`

  The boat interior sides.  This is the area of the hull that is
  exposed in the boat cabin and forms the "walls".  This could be
  padded quite thickly but it would be nice to keep this fairly thin
  to avoid reducing the living area.

_`.vol.ceiling`

  The boat interior ceiling, mostly comprising the underside of the
  coachroof, but also some of the underside of the foredeck.  This
  will need to be fairly thin to avoid bringing down the ceiling
  height in the accommodation, which is already fairly low.  It must
  also have numerous holes to allow access to the fasteners for deck
  fittings.  It may be possible to make cosmetic plugs for these
  holes.

  The biggest difficulty I anticipate is holding up the ceiling
  lining.  This is a notoriously difficult problem on boats.  Gluing
  tends to be temporary in this context.  My main idea for solving
  this is to epoxy wooden blocks or strips to the ceiling to provide a
  purchase for some sort of screws or other fasteners (see
  `.idea.chesterfield`_).

_`.vol.cushions`

  The existing boat cushions are in good condition even after 36
  years, but they are made of absorbent foam with woven wool covers.
  They would not provide floatation for very long, and in any case
  tend to take up moisture over time.

  Annie Hill warns that closed-cell foam cushions can be uncomfortably
  hard [AH-2015]_.

_`.vol.quarter-berth`

  Although this is part of the cabin it deserves some special
  attention.  The quarter berth runs under the starboard cockpit seat
  and has a wooden bulkhead on the port side adjoining the
  `.vol.under-cockpit`_.  It is a fairly large volume and is my main
  sleeping area.  As such it could be quite thickly lined for both
  comfort and buoyancy.  The berth is also home to clothing and
  equipment bags when I'm not in it.

  [TODO: experiments to see how much space I need for comfortable
  fidgeting while sleeping.]

_`.vol.coamings`

  The Coromandel has high and broad cockpit coamings that are part of
  the deck mould.  On the starboard side, the coaming forms a large
  void above the `.vol.quarter-berth`_.  (It had a clothes hanging
  rail in when I first got Tammy Norie.)  This void is not very
  useful.  On the port side, the coaming forms a large void above the
  `.vol.cockpit-locker`_.  This is a little bit useful if you can
  stack objects in the locker, but would be no great loss to foam.
  The very aft part of the coamings open in to the
  `.vol.engine-locker`_ and the `.vol.quarter-locker`_.

  The coamings have the advantage that foam can be wedged into them
  quite tightly and is unlikely to come loose.  On the other hand,
  they are quite high above the waterline and so will only provide
  floatation when the boat is very submerged.

_`.vol.under-cockpit`

  The Coromandel has a large compartment below the cockpit where an
  internal engine might have been fitted, though I have never come
  across one.  This is extremely useful storage that I use for the
  battery, parts, and tools.  It also contains: two cockpit drain
  seacocks; the hose from the bilge to the bilge pump; the gas alarm;
  the battery shut-off switch and circuit breaker; the electrical
  conduit to the stern.

  A loss of volume in this compartment would be quite hard to bear
  forward, but not so much aft, where the battery is mounted.  This
  part is quite hard to access without crawling, so could not only be
  lined thickly with foam, but could also store containers full of
  air.  It may be possible to form some foam into a mounting for
  various containers, as is done in photographic cases, so that they
  are held firmly.  For example, the tupperware tubs of fasteners,
  electrical parts, etc. could be jammed in effectively.

  _`.vol.under-cockpit.channel`: The bottom of this compartment is a
  channel (with the bilge pump hose in it) that acts as a drain
  forward to the bilge.  It's probably best to leave this exposed.

_`.vol.engine-locker`

  The starboard quarter locker holds the outboard engine, which
  protrudes through a hole in to the water.  The lower part of this
  locker is normally flooded, and much more of it floods when the boat
  is heeling.  The locker also holds the main fuel tank on its forward
  shelf.

  The locker has a lot of unused volume.  The upper parts could be
  lined to at least 100mm without restricting airflow around the
  engine, and possibly much more.  The locker lid could also be lined
  with thin foam.  This has the extra advantage of helping to reduce
  engine noise, especially when cruising with the locker closed.

  Foam could also help to wedge the fuel tank more securely in the
  locker.  When sailing, the locker does flood quite deeply and the
  fuel tank is sometimes afloat.

  Conditions in this locker are quite harsh and the foam's backing
  adhesive may not be enough to hold it in place.  It may be possible
  to epoxy wooden blocks to the bulkheads and screw the foam in place
  using large washers.

_`.vol.quarter-locker`

  The port quarter locker is a large storage volume.  It also holds
  the gas bottle and the body of the bilge pump.  The electrical
  connections from the cabin protrude into this locker through a tight
  hole.  The bottom of the locker accesses a kind of tunnel that
  awkwardly reaches the engine mounting bolts.  This tunnel should not
  be blocked, but could hold removable airtight containers.  In any
  case, it would be very hard to line with foam.

  Currently I use this locked for a 50 litre spare water container,
  the spare fuel tank, the inflatable dinghy, and various flammable
  engine-related materials such as oil and carburettor cleaner, as
  well as spare butane for the soldering iron.  It also houses the
  bilge pump handles, the hand pump, a drain unblocking water jet,
  funnel and tubing, and a few other gas- or fuel- related items.

  Loss of volume here could be a little tricky as the dinghy fits
  quite snugly with the 50 litre spare water.  Some experimentation
  will be required.

  The aft part of this locker joins with part of the `.vol.coamings`_.

_`.vol.cockpit-locker`

  The port-side seat of the cockpit lifts to provide access to a large
  locker that is the equivalent of the quarter berth on the starboard
  side.  This locker also contains the heads seacocks, and the copper
  gas pipe passes through it, attached to the starboard bulkhead.  At
  the forward bottom there is access to a void underneath the heads
  compartment sole.  It also adjoins most of the port
  `.vol.coamings`_.  The locker is used to store a large amount of
  equipment that might be needed while sailing: ropes, bucket, flares,
  kedge anchor, fenders, etc.

  Although this locker often appears full, tidying it always makes it
  half empty, and it could be lined with quite thick foam.  More foam
  might be used to make mountings for various items, so that they
  wedge in tightly.  Access to the seacocks and plumbing must be
  maintained, but in fact could be improved by defending the seacocks
  with foam recesses.  The base of this locker must drain forward
  under the heads compartment sole and in to the main bilge, so it is
  in some sense "inside" the boat.  The drainage channel should remain
  clear.  It may also make sense to stuff spare foam in sheets under
  the heads compartment sole, but there is not a great deal of volume
  there.

_`.vol.interior-lockers`

  The Coromandel has a fibreglass liner that forms most of the
  interior bunks.  There is a void on both sides of the boat beneath
  these bunks, with access through locker lids.  The void joins with
  the area under the forward V-berth, which houses the mast step and a
  large triangular area forward of the mast.

  On Tammy Norie, the starboard void contains the flexible 200 litre
  water tank.  Thie does not actually inflate to contain 200 litres,
  but fills the available space.  Lining the void with foam would
  reduce water capacity.

  The port void is used for food storage.  It is a little awkward to
  reach, and food is contained within sealed tupperware containers
  that are thrust into the void and pulled out as needed.  This void
  could be lined, at the cost of loss of stowage.

  The mast step is a wet area that also houses food storage
  containers.  It is moderately hard to access.  On the starboard
  side, near the mast step, is the through-hull fitting for the log,
  and a seacock for the sink drain.  Both of these could benefit from
  protection by foam recesses.

  The forward triangle locker is also used for food storage.  It is
  quite accessible through a large lid and could be effectively lined.

  It may be difficult and unnecessary to attach the foam very firmly
  to the hull or liner in these voids, since it is very unlikely to
  escape in the case of flooding.  In the case of the mast step, which
  is made of wood that tends to get wet, it is probably best to allow
  air circulation and encourage evapouration as much as possible.
  Certainly it's necessary to inspect the step regularly.

  See also compartmentalization of interior lockers task [ref?].

_`.vol.forward-bulkhead`

  The bulkhead between the cabin and the anchor locker located in the
  bow.

  On Mingming and Mingming 2, Roger Taylor added a second “watertight
  bulkhead” or “collision bulkhead” with foam between it and the
  anchor locker [RT-2007]_.  This could work on Tammy Norie, except it
  would considerably reduce the size of the forward bunks and make it
  much less easy to have guests on board, and so does not satisfy
  `.req.useful`_ or `.req.preserve`_.  [TODO: Ask Roger about this.]

_`.vol.starboard-aft-bulkhead`

  The small bulkhead between the cabin and the cockpit that is
  currently used to mount some equipment.

  [TODO: compromise between current use and foam]

_`.vol.port-aft-bulkhead`

  The small bulkhead between the heads compartment and the cockpit on
  which the compass, log, and depth instruments are mounted.

  [TODO: describe how access to instruments and wiring will be
  retained]

_`.vol.anchor-locker`

  [TODO: consider if it is sensible to use this at all, reference to
  Roger Taylor's collision bulkhead modification]

_`.vol.heads-bulkhead`

  The forward bulkhead of heads is a large blank wall that could
  easily be covered to a depth of 20-30mm.

    
4.3. Dimensions
---------------

_`.dim`: These are the approximate dimensions of the `.vol`_ based on
measurements made on 2019-11-23/25.  The purpose of this table is to
estimate total displacement volume.  In many cases geometrical
approximations have been used (such as averaging the ends of a
trapezium) so this table should not be used to order sections of foam.
[TODO: Link to scans of notes?]  [TODO: Consider the weight of the
foam.]

================================  ==========  ======  =======  ================
Reference                          Areas      Depth   Vol/cm³  Note
================================  ==========  ======  =======  ================
`.vol.anchor-locker`_
`.vol.ceiling`_ forward              45×85cm    30mm    11475  [TODO: windows]
`.vol.ceiling`_ starboard           50×232cm    30mm    38400  [TODO: windows]
`.vol.ceiling`_ port                50×160cm    30mm    24000  [TODO: windows]
`.vol.ceiling`_ top                100×200cm    20mm    26000  inc. hatches
`.vol.ceiling`_ heads top            32×70cm    20mm     4480
`.vol.ceiling`_ heeads port          48×70cm    30mm    10080  minus shelf
`.vol.coamings`_ starboard          36×135cm    20cm    97200  use bottles?
`.vol.coamings`_ port               36×114cm    20cm    82080  use bottles?
`.vol.cockpit-locker`_ hull        107×114cm    30mm    36594
`.vol.cockpit-locker`_ forward       74×40cm    30mm     8880
`.vol.cockpit-locker`_ aft           56×52cm    30mm     8736
`.vol.cockpit-locker`_ starboard    52×114cm    30mm    17784
`.vol.cockpit-locker`_ lid           33×84cm    30mm     8316  tapered volume
`.vol.cushions`_ port f f           36×120cm    10cm    43200
`.vol.cushions`_ port f a            48×70cm    10cm    33600
`.vol.cushions`_ starboard f f      36×120cm    10cm    43200
`.vol.cushions`_ starboard f a       48×70cm    10cm    33600
`.vol.cushions`_ starboard q a      53×110cm    10cm    58300
`.vol.cushions`_ starboard s         55×40cm    10cm    22000
`.vol.cushions`_ starboard q f       66×82cm    10cm    54120
`.vol.cushions`_ infill              53×54cm    10cm    28620
`.vol.engine-locker`_ lid            44×63cm    30mm     8316
`.vol.engine-locker`_ port           40×35cm    30mm     4200
`.vol.engine-locker`_ hull           43×64cm    30mm     8256
`.vol.engine-locker`_ coaming        15×46cm    18cm    13248
`.vol.engine-locker`_ fuel tank      32×17cm    20cm    10880  [#fueltank]
`.vol.engine-locker`_ transom       ¼π×46²cm    30mm     4983  quarter circle
`.vol.forward-bulkhead`_           ½×78×62cm    30mm     7254  triangle
`.vol.heads-bulkhead`_ lower        ¼π×78²cm    30mm    14327  quarter circle
`.vol.heads-bulkhead`_ upper        ¼π×57²cm    30mm     7651  quarter circle
`.vol.interior-lockers`_                                       use containers
`.vol.port-aft-bulkhead`_            58×43cm    30mm     7482
`.vol.quarter-berth`_ hull          50×195cm    30mm    29250
`.vol.quarter-berth`_ ceiling       42×133cm    30mm    16758
`.vol.quarter-berth`_ bulkhead u    32×115cm    30mm    11040
`.vol.quarter-berth`_ bulkhead l    17×115cm   120mm    23460  cuboid recess
`.vol.quarter-berth`_ locker        55×115cm    10mm     6325  eighth spheroid
`.vol.quarter-locker`_ hull          89×86cm    30mm    22962
`.vol.quarter-locker`_ coaming       14×96cm    18cm    24192
`.vol.quarter-locker`_ lid           44×63cm    30mm     8316
`.vol.quarter-locker`_ starboard     36×74cm    30mm     7992
`.vol.quarter-locker`_ transom      ¼π×30²cm    30mm     2119  quarter circle
`.vol.quarter-locker`_ forward      ¼π×80²cm    30mm    15072  quarter circle
`.vol.sides`_ port                  48×205cm    30mm    29520
`.vol.sides`_ starboard             48×214cm    30mm    30816
`.vol.sides`_ heads                  44×98cm    30mm    12936
`.vol.starboard-aft-bulkhead`_       58×43cm    30mm     7482  [#sab]
`.vol.under-cockpit`_ top           37×107cm    30mm    11877
`.vol.under-cockpit`_ starboard     31×107cm    30mm     9951
`.vol.under-cockpit`_ port          31×107cm    30mm     9951
`.vol.under-cockpit`_ hull          37×107cm    30mm    11877  [#vuch]
Total                                                 1069068  ± 10%
================================  ==========  ======  =======  ================

.. [#fueltank] cuboid blocks to wedge in the fuel tank

.. [#sab] The `.vol.starboard-aft-bulkhead`_ may have to be thinner to
          accommodate the equipment mounts, but it's quite a small
          volume anyway.

.. [#vuch] Might be a good idea to leave this exposed.
       
.. (+ 11475 38400 24000 26000 4480 10080 97200 82080 36594 8880 8736
   17784 8316 43200 33600 43200 33600 58300 22000 54120 28620 8316
   4200 8256 13248 10880 4983 7254 14327 7651 12936 7482 29250 16758
   11040 23460 6235 22962 24192 8316 7992 2119 15072 29520 30816 7482
   11877 9951 9951 11877)


Contingency

================================  ==========  ======  =========================
Reference                          Areas      Depth   Volume / cm³
================================  ==========  ======  =========================
`.idea.fixed-cushions`_ liner f     11500cm²    20mm   23000
`.idea.fixed-cushions`_ liner s     136×56cm    20mm   15232
Total                                                  38000 ± 10%
================================  ==========  ======  =========================

.. (+ 23000 15232)


4.4. Ideas
----------

_`.idea.cushion-straps`

  Cushions could perhaps be made with webbing straps that attach to
  pad eyes on the cabin liner.

_`.idea.fixed-cushions`

  What if the cabin liner has a layer of foam glued to the top in
  addition to cushions.  The cushions could be more conventional,
  possibly solving Annie Hill's objection [ref?].

_`.idea.fewer-cushions`

  Since I'm remaking cushions and storing the originals, what cushions
  do I actually need?

_`.idea.chesterfield`

  Some kind of fasteners to tighten the surface lining against the
  foam “stuffing” and so produce an attractive effect like a
  Chesterfield sofa, as well as securing the foam.  The fasteners
  would need to flexible and not have sharp edges, especially on the
  ceiling.  Probably needs prototyping.

  Something like <https://www.ebay.co.uk/itm/UPHOLSTERY-BUTTONS-WIRE-LOOP-BACK-LENGTH-OF-TWINE-12-X-NO45-WHITE-VINYL-COVERED/152515686888?hash=item2382a4b1e8:g:otAAAOSwevlaDG~z>?

_`.idea.pad-eyes`

  How does this interact with the idea of strapping in bags etc. using
  pad eyes attached to the hull in the manner of mini transat racers?

_`.idea.test`

  Test the unsinkability of the boat by attempting to sink the boat.
  This would only be a partial test.

  It would probably be best to do it in clean fresh water, to reduce
  the effort of drying and cleaning up afterwards.  Warm dry weather
  would be good for the same reason.  Sea water is 2-4% denser than
  fresh [#wolfram], so displacing it is more effective, and a test in
  fresh water is more rigorous.

  It would also be sensble to do it somewhere that the boat can be
  recovered in some reasonably cheap way if she does *not* float.  For
  example, somewhere that she'll rest on the bottom with her
  coach-roof at the surface, so that we can deploy air bags to
  re-float her, or somewhere that can be drained or a crane can be
  used.

  In addition to being a test of the design, this would be fun and
  interesting and make for an interesting article, photos, and a
  video!

_`.idea.foam-in-bags`

  This is an excellent idea from Bernie Branfield:

    “I carry a can of builders foam and a couple of heavy duty bags as
    part of my emergency kit. So far I have only used them to make a
    cockpit seat!” — `Facebook comment, 2019-11-26`_

.. _`Facebook comment, 2019-11-26`: https://www.facebook.com/permalink.php?story_fbid=2479882315602365&id=1435460230044584&comment_id=2479999215590675&reply_comment_id=2480072452250018

  This is a great way to generate extra flotation while at sea, and,
  as Bernie points out, for fabricating shaped objects.  I think I
  will add this to my kit as well.

.. [#wolfram] according to Wolfram Alpha


4.5. Suppliers
--------------

_`.supplier.lux`: _`Lux Distribution`
<https://www.carinsulation.co.uk/>, Unit 3 Watling Court, Attleborough
Fields Ind Estate, Nuneaton, Warwickshire, England, CV11 6GX.  Tel:
02477 670370, Mob: 07476 064038.

_`.supplier.veolia`: Veolia Otterbourne, Poles Lane, Otterbourne,
SO21 2EA <https://goo.gl/maps/D8Fi8ZKhJ8ih2SyB7>.  Tel: 01962 764000.


5. Plan
=======

_`.plan`: The plan section contains a list of concrete steps that I
plan to take to implement the design.  Each step should have a fairly
predictable duration.  Note that the plan section does not say when
things will happen (see `.schedule`_).  The plan is only roughly in
order, but all steps are written after steps they require.

_`.plan.plan`

  Initial plan and schedule.

_`.plan.clear-out`

  Clear out enough stuff from the boat to get access to the surfaces
  and volumes.

_`.plan.measure`

  Measure boat for materials and to ensure that there is enough volume
  to `.design.displace`_ enough volume.

_`.plan.battery`

  Make battery compartment using 1m²×30mm foam sample that I already
  have from `.supplier.lux`_ in order to learn about handling the
  foam, its adhesion, etc.  (And of course to mount the battery!)

_`.plan.find-vinyl`

  Find vinyl headlining offcuts in crates I have at home, prior to
  `.plan.try-chesterfield`_.

_`.plan.find-fasteners`

  Investigate suitable fasteners for `.idea.chesterfield`_.

_`.plan.try-chesterfield`

  Experiment with `.idea.chesterfield`_ with foam sample and vinyl on
  backing board.

_`.plan.strip-deck`

  Remove deck fittings to allow core to dry. [Ref details for this
  project.]

_`.plan.order-mats`

  Order first batch of materials.

_`.plan.surface-prep`

  Prepare surfaces according to the experience from `.plan.battery`_.

_`.plan.weighbridge`

  Visit a public weighbridge with the boat on her trailer (all
  equipment laoded) before launch, then again with just the trailer
  after launch, in order to find out the real weight and required
  volume of floatation.  Compare to actual volume and make further
  plans as necessary.  This can't happen until launch in Spring 2020.
  There is a weighbridge at `.supplier.veolia`_.

_`.plan.more`

  Plan further steps.


6. Schedule
===========

_`.schedule`: The schedule describes *when* things from `.plan`_ are
scheduled to occur.  It is subject to continuous change in the light
of what actually occurs (see `.journal`_).

I'm quite limited with scheduling since I am disabled with `ME/CFS`_,
which is not only both physically and mentally debilitating, but
unpredictable.  In many ways this schedule will be an exercise in
managing my effort carefully to see what I can achieve.

.. _`ME/CFS`: https://en.wikipedia.org/wiki/ME/CFS

_`.schedule.2019-11-17` : Planning (at 1TR)

    Initial plan and schedule (`.plan.plan`_).  Allot time to the
    project on my calendar.

_`.schedule.2019-11-24/28` : Design and measurement (at 245)

    1. Clear out boat (`.plan.clear-out`_)
    2. Measure volumes (`.plan.measure`_)
    3. Select initial volumes
    4. Order initial materials (`.plan.order-mats`_)
    5. Make battery compartment (`.plan.battery`_)
    6. Remove deck fittings (`.plan.strip-deck`_)
    7. Order fasteners for chesterfield (`.plan.try-chesterfield`_)

_`.schedule.2019-12-03/06` : (at 1TR)

    [To be decided]

_`.schedule.2019-12-12/17` : (at 245)

    [To be decided]

_`.schedule.2020-02/03` : (at 245)

    1. Weigh and launch (`.plan.weighbridge`_)
    2. Plan to add even more floatation if required [TODO: link to
       contingency plan]


7. Journal
==========

_`.journal`: The journal describes *what* actually occurred and *when*
while implementing the plan.

_`.journal.2019-11-14`

  After refining my big to-do list for the Tammy Norie project, I
  realised that the unsinkability project was too complicated to
  manage with a simple to-do list and decided to write a document.
  That turned into “Tammy Norie Unsinkability Plan” (this document)
  which rapidly grew to a length and level of detail that surprised
  me.  I have been thinking about this project for many years and have
  accumulated a lot of ideas.  On top of that, when I started thinking
  about the volumes inside the boat I realised that there were a lot
  of wrinkles and that writing them up would help a great deal with
  execution and increase the chance of completing the project during
  the winter of 2019/2020.

  As part of a general plan for the winter I constructed a tent around
  Tammy Norie in my parents' driveway using a 10×10m clear tarpaulin
  on a frame jury-rigged from Dad's party gazebo.  This will allow me
  to disgorge the contents of Tammy Norie onto the deck without them
  getting wet during the winter.  It will also help with two other
  projects:

  1. Drying out the hull in preparation for a layer of epoxy to
     prevent osmosis.  [ref?]

  2. Removing the deck fittings, many of which are held in by
     self-tapping screws, and drying out the deck core before
     replacing them using machine screws and nuts, to prevent deck
     core rot.  [ref Pascoe, Mads]


_`.journal.2019-11-24`

  Measured foam volumes and took photographs for `.vol.sides`_, liner,
  `.vol.ceiling`_, `.vol.under-cockpit`_, `.vol.heads-bulkhead`_,
  `.vol.starboard-aft-bulkhead`_, `.vol.port-aft-bulkhead`_,
  `.vol.coamings`_, `.vol.quarter-berth`_, `.vol.forward-bulkhead`_,
  `.vol.cockpit-locker`_.  [TODO: Scan results.]

  Extensive updates to this document including preparation for
  publishing via GitHub so that it can be critiqued by interested
  folks from the `Tammy Norie blog`_, the `JRA forums`_, mailing
  lists, etc.

.. _JRA forums: https://junkrigassociation.org/technical_forum

  At this stage the volumes do not seem to be reaching anywhere near
  my estimate from [RB-2015-06-09]_ so something is wrong and I must
  investigate.  This might just be due to tiredness and `ME/CFS`_
  brain fog.  I will:

  1. Try to rediscover the basis for my estimate.

  2. Re-draw my measurement diagrams more carefully and check my
     current calculations.


_`.journal.2019-11-25`

  Finished measuring volumes (except `.vol.anchor-locker`_, which is
  an unlikey one).  These need writing up in this document, and the
  whole lot need to be gone over more carefully.  I've had a horrible
  thought — did I accidentally make my original esimate using 10cm of
  foam instead of 10mm?


_`.journal.2019-11-26`

  NB writes:

    “I’ve calculated that 10mm of foam on all the surfaces I’ve just
    painted, plus the cushions, add up to about 1m³” suggests that you
    painted nearly 100m². That's a lot. (In comparison: all the walls
    in my living room add up to about 35m².)

  This confirms my suspicions of `.journal.2019-11-26`_ that my
  original esimate was wrong, and that I'll have to find more surfaces
  and voids than I mentioned in [RB-2015-06-09]_.  This is also confirmed
  by the calculations in § `4.3. Dimensions`_.

  I've reached 1m³ by adding the remaining measured volumes and
  thickening the foam on `.vol.ceiling`_.  This demonstrates
  feasibility at least!

  I think `.vol.sides`_ could be thicker instead to avoid reducing
  headroom.

  There are also voids that could be filled with air bottles that are
  not accounted for.  It's probably more efficient to fill the
  coamings with air bottles instead of foam, since they do not need to
  be insulated or padded.  At this stage it's probably worth reviewing
  all the volumes to see what could be replaced by air bottles.

  There is other floatation that is not accounted for: the mast is
  partially filled with bubble-wrap [RB-2015-09-02]_ and the deck is a
  balsa sandwich.  [TODO: Write these up.]

  Published links to this and other plans on GitHub_ and the `Tammy
  Norie blog`_ [RB-2019-11-26]_.

.. _GitHub: https://github.com/rptb1/tammy-norie


_`.journal.2019-11-27`

  Made battery compartment (`.plan.battery`_) but did not stick it in
  place.  Discoveries:

    1. You can draw plans on the paper backing of the foam in pencil.

    2. The foam is easy to cut with scissors.  It can be cut with a
       knife, but even blunt scissors do a better job.

    3. The foam is good at staying in place when it is jammed in by
       its edges.

    4. `.vol.under-cockpit.channel`_ is quite wet and dirty,
       especially forward at the lower end.  It does not drain in to
       the main bilge at its lowest point, and so is accumulating
       water and dirt.  [TODO: Make an action to improve this.]

    5. Working in a 25×30cm dark space where you can't bend your
       elbows is quite challenging.


A. References
=============

.. [AH-2015]
   Commnent on “Redecoration”, from the `Tammy Norie blog`_;
   Annie Hill;
   2015-06-12;
   <https://tammynorie.wordpress.com/2015/06/09/redecoration/#comment-333>.

     “I had the misfortune to spend seven years living on a boat with
     closed-cell foam cushions. I’m naturally well padded, but I have
     to say they were some of the most uncomfortable seats I’ve ever
     had to live with.”

.. [Newbridge-1982]
   Untitled Newbridge Coromandel specification;
   Newbridge Boats Limited;
   1982 (date uncertain);
   <https://corribee.files.wordpress.com/2009/06/20090629_coromandelbrochure_markdeverell2.pdf>.

     “Displacement laden: 2,000lbs (908 kg)”

.. [RB-1998]
   “Rules for all documents”;
   Richard Brooksby;
   Ravenbrook Limited;
   1998-06-03;
   <https://info.ravenbrook.com/rule/generic/>.

.. [RB-2015-06-09]
   “Redecoration”, from the `Tammy Norie blog`_;
   Richard Brooksby;
   2019-06-09;
   <https://tammynorie.wordpress.com/2015/06/09/redecoration/>.
        
     “My goal is to displace over 1m³ of water with foam, providing
     over 1t of buoyancy. That should make Tammy Norie
     unsinkable. I’ve calculated that 10mm of foam on all the surfaces
     I’ve just painted, plus the cushions, add up to about 1m³, and
     that’s not counting the locker interiors or any other voids, so
     it’s quite achievable.”

.. [RB-2015-09-02]
   “Radio mast bubbles”, from the `Tammy Norie blog`_;
   Richard Brooksby;
   2015-09-02;
   <https://tammynorie.wordpress.com/2015/09/02/radio-mast-bubbles/>

     “The top section of the mast weighs about 30kg. A quick
     calculation gave its interior volume as about 40 litres. If it
     were completely sealed, it would float! That was not likely to be
     possible, but I did think about packing it with closed cell foam,
     or air-filled bags. Then I realised I could use bubble wrap.”

.. [RB-2019-11-26]
   “Project documents and unsinkability”, from the `Tammy Norie blog`_;
   Richard Brooksby;
   2019-11-26;
   <https://tammynorie.wordpress.com/2019/11/26/project-documents-and-unsinkability/>

     “I decided to publish them so that other people could benefit
     from seeing the projects develop, and how I approach these kinds
     of engineering problems. I’m also hoping that interested folks
     might have suggestions or spot mistakes before I make them!”

.. [RT-2007]
   “Voyages of a Simple Sailor”;
   Roger Taylor;
   2007.

     “A watertight bulkhead was put in just forward of the forward end
     of the coach-roof.  Apart from the chain locker, the whole area
     forward of the bulkhead was filled tight with closed-cell foam.”
     (§3 ch.2 ¶2)

     “My calculations suggested that by them Mingming had about 150%
     of the floatation required to keep her where one would like to be
     kept — on the surface of the ocean.” (§3 ch.2 ¶3)

.. _Tammy Norie blog: https://tammynorie.wordpress.com/     



B. Document History
===================

==========  ====   ============================================================
2019-11-14  RB_    Brainstormed with Dad.
                   Lots of brain dumping about potential volumes for foam.
2019-11-24  RB_    Added measurements made on 2019-11-23/24.
                   Added new volumes discovered while making measurements.
                   Added introduction and explanation of sections to make
                   document more accessible to people who aren't familiar with
                   the structure.  Expanded plan and schedule.
==========  ====   ============================================================

.. _RB: mailto:rptb1+tammy-norie@pobox.com
