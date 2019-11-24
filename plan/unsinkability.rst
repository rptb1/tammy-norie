.. -*- coding: utf-8 -*-

==============================
Tammy Norie Unsinkability Plan
==============================

:Author: Richard Brooksby <rptb1+tammy-norie@pobox.com>
:Date: 2019-11-14
:Copyright: `CC BY-NC-SA 4.0`_
:Tag: plan.unsinkability

.. _CC BY-NC-SA 4.0: http://creativecommons.org/licenses/by-nc-sa/4.0/


1. Introduction
===============

This document explains how and why I intend to make Tammy Norie unsinkable.

The document uses the conventions of an engineering project at my
company, `Ravenbrook`_.  In particular:

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

  Suitable for Tammy Norie.

_`.req.time`

  Can be fitted by me in reasonable time [clarify].

_`.req.cost`

  Material costs less than GBP 1000.

_`.req.maintainable`

  Maintainable.

_`.req.removable`

  Can be removed and replaced with reasonable cost and effort.

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

_`.design.displace`: Use closed-cell foam to displace over 1 tonne
[why?] of seawater, making the boat bouyant even if totally submerged
[RB2015]_ [RT2007]_.  [What is the margin of error?]

Most of the foam will be stuck [how?] to the interior of the boat as a
lining, also providing insulation and padding for comfort
(`.goal.benefits`_).

The interior cushions will also be replaced with closed-cell foam
cushions, so that they cannot take up water.  These will be secured to
the interior by some means so that they do not detach when the boat is
flooded [what means?].

Many accessible unused voids will be filled with foam — particularly
the `.vol.coamings`_ — but not voids that are needed for drainage or
access.

Additional precautions include storing as much as possible in
watertight containers and bags which are half-filled with air.

The foam will need to be covered with a lining to protect its surface
and to reflect light, since it is usually matt black.  Conventional
vinyl headlining material is probably the right thing.


Volumes
-------

These are the volumes within the boat where air can be replaced by foam.

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
  hard [AH2015]_.

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

  The bottom of this compartment is a channel (with the bilge pump hose
  in it) that acts as a drain forward to the bilge.  It's probably
  best to leave this exposed.

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
  the spare fuel tank, the inflatable dinghy, and various
  flammable engine-related materials such as oil and carburettor cleaner,
  as well as spare butane for the soldering iron.  It also houses the
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

  It may be difficult and unnecessary to attach the foam very firmly to the hull
  or liner in these voids, since it is very unlikely to escape in the
  case of flooding.  In the case of the mast step, which is made of
  wood that tends to get wet, it is probably best to allow air
  circulation and encourage evapouration as much as possible.
  Certainly it's necessary to inspect the step regularly.

  See also compartmentalization of interior lockers task [ref?].

_`.vol.forward-bulkhead`

  The bulkhead between the cabin and the anchor locker located in the
  bow.

  [TODO: description and analysis, reference to Roger Taylor's
  collision bulkhead modification]

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

    
Dimensions
----------

These are approximate dimensions based on measurements made on
2019-11-23/24.  [Link to scans of notes?]

================================  =========  ======  =========================
Reference                         Areas      Depth   Volume / cm³
================================  =========  ======  =========================
`.vol.anchor-locker`_
`.vol.ceiling`_ forward             45×85cm    10mm    3825
`.vol.ceiling`_ starboard          50×232cm    10mm   11600
`.vol.ceiling`_ port               50×160cm    10mm    8000
`.vol.ceiling`_ top               100×200cm    10mm   13000 (minus hatches)
`.vol.coamings`_
`.vol.cockpit-locker`_
`.vol.cushions`_                              100mm
`.vol.engine-locker`_
`.vol.forward-bulkhead`_
`.vol.interior-lockers`_
`.vol.port-aft-bulkhead`_
`.vol.quarter-berth`_
`.vol.quarter-locker`_
`.vol.sides`_ port                48×205cm     20mm   19680
`.vol.sides`_ starboard           48×214cm     20mm   20554
`.vol.starboard-aft-bulkhead`_
`.vol.under-cockpit`_
`.idea.fixed-cushions`_ liner f   11500cm2     20mm   23000
`.idea.fixed-cushions`_ liner s   136×56cm     20mm   15232
Total                                                114891
================================  =========  ======  =========================


Notes
-----

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
  This would only be a partial test.  It would probably be best to do
  it in clean fresh water, to reduce the effort of drying and cleaning
  up afterwards.  Warm dry weather would be good for the same reason.
  Salt water is 2.7% denser than fresh, so displacing it is more
  effective, and a test in fresh water is more rigorous.  It would
  also be sensble to do it somewhere that the boat can be recovered in
  some reasonably cheap way if she does *not* float.  For example,
  somewhere that she'll rest on the bottom with her coach-roof at the
  surface, so that we can deploy air bags to re-float her, or
  somewhere that can be drained or a crane can be used.  In addition
  to being a test of the design, this would be fun and interesting and
  make for an interesting article, photos, and a video!


Suppliers
---------

_`.supplier.lux`: _`Lux Distribution` <https://www.carinsulation.co.uk/>, Unit 3 Watling
Court, Attleborough Fields Ind Estate, Nuneaton, Warwickshire,
England, CV11 6GX.  Tel: 02477 670370, Mob: 07476 064038.


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

2019-11-17 : Planning (at 1TR)

    Initial plan and schedule (`.plan.plan`_).  Allot time to the
    project on my calendar.

2019-11-24/28 : Design and measurement (at 245)

    1. Clear out boat (`.plan.clear-out`_)
    2. Measure volumes (`.plan.measure`_)
    3. Select initial volumes
    4. Order initial materials (`.plan.order-mats`_)


7. Journal
==========

_`.journal`: The journal describes *what* actually occurred and *when*
while implementing the plan.

2019-11-14

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


2019-11-24

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


A. References
=============

.. [RT2007] “Voyages of a Simple Sailor”; Roger Taylor; 2007.

     “A watertight bulkhead was put in just forward of the forward end
     of the coach-roof.  Apart from the chain locker, the whole area
     forward of the bulkhead was filled tight with closed-cell foam.”
     (Section 3 chapter 2 paragraph 2)

     “My calculations suggested that by them Mingming had about 150%
     of the floatation required to keep her where one would like to be
     kept — on the surface of the ocean.” (Section 3 chapter 2
     paragraph 3)

.. [AH2015] Commnent on “Redecoration”, from the `Tammy Norie blog`_;
   Annie Hill; 2015-06-12;
   <https://tammynorie.wordpress.com/2015/06/09/redecoration/#comment-333>.

     “I had the misfortune to spend seven years living on a boat with
     closed-cell foam cushions. I’m naturally well padded, but I have
     to say they were some of the most uncomfortable seats I’ve ever
     had to live with.”

.. [RB2015] “Redecoration”, from the `Tammy Norie blog`_; Richard
   Brooksby; 2019-06-09;
   <https://tammynorie.wordpress.com/2015/06/09/redecoration/>.
        
     “My goal is to displace over 1m³ of water with foam, providing
     over 1t of buoyancy. That should make Tammy Norie
     unsinkable. I’ve calculated that 10mm of foam on all the surfaces
     I’ve just painted, plus the cushions, add up to about 1m³, and
     that’s not counting the locker interiors or any other voids, so
     it’s quite achievable.”

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
                   the structure.
==========  ====   ============================================================

.. _RB: mailto:rptb1+tammy-norie@pobox.com
