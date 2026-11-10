# Injection Molding Cushion Variation: Why Stability Beats Size

## The target value is not the process

A process sheet that says 4.0 mm often turns a process outcome into a supposed setpoint. When the displayed value moves, a technician may adjust shot size, decompression, or hold pressure until it returns to the target. The screen looks better, but the underlying leak, viscosity shift, or positioning problem may still be developing.

Cushion is the melt remaining in front of the screw at a defined point in the cycle, usually at the end of hold. It is shaped by shot size, melt density, check-ring sealing, barrel temperature, material condition, and screw-position control. The number is therefore evidence of how the process behaved, not a complete description of process health.

That is why [injection molding cushion variation](https://nhyscrews.com/blog/injection-molding-cushion-variation) belongs on a process-health dashboard, not only on a setup sheet. A stable cushion at a slightly unconventional value can produce better parts than a nominal cushion that swings from shot to shot.

Consider two simplified runs using the same machine and the same measurement point:

- Run A records 3.9, 4.0, 4.1, 4.0, and 3.9 mm.
- Run B records 2.8, 5.2, 3.0, 5.0, and 3.9 mm.

Both runs have nearly the same average cushion. Run A has a 0.2 mm range; Run B has a 2.4 mm range. If the part depends on consistent packing, the average conceals the important difference. Run B is forcing the screw, melt pad, and cavity to experience a different pressure-transfer condition on nearly every cycle.

The operating question should not be whether the cushion touched the target. It should be whether the machine created the same usable pressure-transfer condition repeatedly.

## Why stability controls pressure transfer

During hold, the screw presses against the melt pad in front of its tip. That pad acts as the hydraulic link between the injection unit and the plastic in the cavity. The screw can continue applying force only while enough molten material remains for that force to move through the nozzle, runner, gate, and part.

A cushion that approaches zero creates an obvious failure mode. The screw bottoms out, and the hold-pressure command can remain on the controller without transmitting meaningful additional pressure into the cavity. Thick sections may show sink marks, part weight can fall, and dimensions can shift as the molded plastic cools with insufficient packing.

A larger cushion is not automatically safer. An excessive melt pad can absorb part of the applied pressure through melt compression before the force reaches the cavity. It can also increase residence time, which matters for heat-sensitive materials. The useful target is a validated cushion with enough margin to prevent bottoming, but not so much that compressibility or residence time becomes a new source of variation.

The more subtle problem is a cushion that changes while remaining above zero. A lower residual cushion generally means the screw traveled farther forward, but that movement does not prove that more useful material entered the cavity. Melt may have leaked backward across a worn check ring, compressed differently because of a viscosity change, or responded differently because the machine overran the intended position. The same displayed cushion value can result from different physical conditions, and the same average value can hide very different cycle histories.

Stability matters because it makes those conditions repeatable. When the cushion remains within a narrow band, the machine begins each hold phase with a similar melt reservoir and screw position. That does not guarantee a good part, but it removes one major source of uncertainty from the pressure path.

## Remove false variation before setting limits

Cushion variation cannot be analyzed until the measurement itself is consistent. Machine manufacturers do not all define cushion in the same way. One controller may report the screw's farthest-forward position during fill. Another may report screw position at the end of hold. A third may display both values under different labels.

Those readings are not interchangeable. After the machine transfers from fill to hold, cavity pressure can push against the screw and cause it to move backward. The end-of-fill position and end-of-hold position may therefore differ substantially even when the process is stable.

For packing control, end-of-hold cushion is usually the more informative value because it describes the melt pad remaining after the phase responsible for packing the part. The exact machine convention still needs to be documented. A position number is not meaningful until the reference point, sign direction, and sampling moment are known.

A reliable control plan should specify:

- The controller field used for cushion measurement.
- Whether the reading is taken at maximum forward position or end of hold.
- The screw-position reference and direction of travel.
- The cycle stage at which the value is captured.
- The resolution and repeatability of the position sensor.
- The hold pressure, hold time, shot size, and decompression settings used during the baseline run.

Without those definitions, a change in displayed cushion may be a measurement change rather than a molding change. Comparing a fill-end reading from one machine with an end-of-hold reading from another can create a false benchmark. Even on one press, a controller update or data-collection change can appear as a process shift if the capture point is not preserved.

## The shape of the variation is more useful than one alarm

An isolated cushion value rarely identifies a root cause. A trend containing hundreds of cycles provides far more information. The pattern of movement helps distinguish a progressive mechanical problem from a material change, thermal drift, or intermittent control issue.

### A narrow, stable band

A tight band around a consistent mean indicates that the machine, material, and process settings are interacting repeatably. The mean still needs to be validated against part requirements, but there is little evidence of a developing cushion problem.

A stable value is not a reason to stop monitoring. It is the baseline against which later widening, step changes, or drift can be recognized.

### A gradual drift with a widening band

A slow change over days or weeks often points toward progressive wear or thermal degradation. A check ring may be seating less consistently. Screw flights and the barrel bore may be developing additional clearance. A heater band or thermocouple may be losing control even though the setpoint remains unchanged.

The combination matters. A slowly moving mean with a slowly expanding shot-to-shot range is more concerning than a one-time shift in average. It suggests that the process is losing repeatability, not merely operating at a new but stable center.

### A sudden step change

A step change that begins after a resin-lot switch, regrind adjustment, dryer interruption, maintenance event, or parameter edit should be investigated as a change-point. Material viscosity, moisture, back pressure, decompression, and actual melt temperature can all change without an obvious change to the nominal process sheet.

A sudden shift after a material change does not justify pulling the screw immediately. It does justify isolating the material and comparing moisture, melt-flow data, regrind percentage, and recovery behavior before changing several machine settings at once.

### Alternating high and low readings

An alternating pattern often indicates an intermittent condition rather than a simple setpoint error. Possible contributors include inconsistent check-ring seating, unstable feeding, fluctuating moisture, intermittent nozzle leakage, or a control response that overshoots and corrects on successive cycles.

The direction of cushion movement is not a diagnosis by itself. The same downward trend can have different causes depending on how the machine defines position and whether shot size, recovery, and hold behavior changed at the same time.

### Values approaching zero

A cushion that repeatedly approaches zero is an immediate process risk, even if parts still pass visual inspection. The machine is losing the reserve required to maintain pressure during hold. A small additional viscosity shift, temperature change, or mechanical leak can push the screw into bottoming and create an abrupt quality failure.

## Connect cushion data to the part, not just the controller

Cushion is a machine-side signal. It becomes a quality-control variable only when its movement is compared with the part's critical responses.

A practical baseline begins after the barrel, mold, and hydraulic or servo system have reached operating temperature. Capture at least 30 to 50 consecutive cycles under stable conditions, and record more than cushion alone:

- End-of-hold cushion for every cycle.
- Part weight by cavity when possible.
- Critical dimensions or functional measurements.
- Cavity pressure, if sensors are available.
- Actual barrel-zone temperatures rather than only setpoints.
- Recovery time, back pressure, decompression, and material lot.
- Dryer condition and moisture results for hygroscopic resins.

The relationships between those signals are often more revealing than the cushion trend itself.

If cushion variation rises while part weight and a critical dimension move with it, cushion is likely part of the quality mechanism. If cushion varies but the part remains unchanged across the validated operating range, the process may be less sensitive than expected, or the position signal may contain measurement noise. If cushion remains stable while part weight changes, the investigation should move toward feeding, cavity balance, material density, temperature, or weighing practice rather than forcing cushion back to a nominal value.

Generic limits can provide a starting point but should not become release criteria by default. A tolerance of plus or minus 0.05 inch, approximately plus or minus 1.3 mm, is often used as a broad training reference. A 0.5 mm change may be important for a medical housing or optical component while having no visible effect on a noncritical container. The acceptable band belongs to the part's critical dimensions, weight, mechanical performance, and regulatory requirements.

A design of experiments can establish that relationship more reliably than inherited rules. Within a safe, non-bottoming range, run deliberately low, nominal, and high cushion conditions while holding other variables as constant as practical. Measure part weight, critical dimensions, warpage, sink, and mechanical performance. The result is not just a target number; it is a map showing how much cushion movement the part can tolerate before a critical response changes.

The commonly cited 3 to 6 mm starting range has the same limitation. Four millimeters on a 25 mm screw does not represent the same melt volume as four millimeters on a 60 mm screw. More importantly, a starting size says nothing about shot-to-shot repeatability. A cushion target should be established inside a validated operating window, not adopted as a universal acceptance rule.

## A production example: restoring the average without restoring the process

Imagine a 50 mm screw molding an ABS housing with a validated cushion near 4.0 mm. During a stable run, the reading stays between 3.8 and 4.2 mm, and part weight remains between 21.00 and 21.08 g.

Several weeks later, the average cushion falls to approximately 3.2 mm, with individual shots ranging from 2.8 to 3.7 mm. Part weight begins moving between 20.70 and 21.25 g, and sink marks appear intermittently near a thick rib. The first response is to add shot size until the average cushion returns to 4.0 mm.

That adjustment may restore the center of the display while leaving the variation intact. The machine could now produce readings from 3.0 to 5.1 mm, with the same weight scatter and intermittent sink. The target has been corrected numerically, but pressure transfer has not been made repeatable.

At that point, a check-ring repeatability test, nozzle inspection, and screw-to-barrel wear evaluation become more valuable than another parameter change. If the mechanical assembly passes inspection, material moisture, actual melt temperature, back pressure, and hydraulic or servo positioning should be compared with the original baseline. The cushion trend has narrowed the search; it has not named the failed component.

The opposite case is equally important. If cushion variation begins exactly when a new nylon lot enters production and recovery time changes with it, material condition may be the primary cause. Replacing a check ring in that situation would consume time and money without addressing the source of the viscosity shift.

## Build the control plan around repeatability

A robust cushion control plan treats the mean and the variation as separate signals.

1. **Set the measurement definition.** Use the same end-of-fill or end-of-hold point every cycle and document it in the process record.
2. **Establish a stable baseline.** Collect cushion and part data only after the machine reaches thermal and mechanical operating conditions.
3. **Track the center and the spread.** A mean chart can remain flat while the shot-to-shot range doubles, so monitor moving range or another measure of short-term variation as well as the average.
4. **Tie limits to critical quality attributes.** Use the cushion range that preserves part weight, dimensions, appearance, and performance rather than a generic number copied from another machine.
5. **Use warning limits before reject limits.** A widening warning trend should prompt verification of material, temperature, settings, and mechanical sealing before the process produces nonconforming parts.
6. **Change one controlled variable at a time.** Increasing shot size or hold pressure can move the cushion display without fixing a leaking check ring, unstable material, or faulty position response.
7. **Reconfirm after correction.** A repair or parameter change is not successful until cushion spread and part responses remain stable over a representative production run.

Some thin-wall processes intentionally run with minimal cushion, while precision processes may use a larger reserve to protect long packing stages. The same principle applies in both cases: the chosen condition must remain repeatable and must preserve the required cavity-pressure history.

## The operating rule

Cushion size answers whether a melt reserve exists at one point in the cycle. Cushion stability answers whether the injection unit can repeat the pressure-transfer condition that made the part.

> A target is a location on the screen. A stable cushion is evidence that the machine, melt, and process are working together.

The best target is therefore not the number that looks most familiar or matches a generic guideline. It is the center of a validated window with enough margin to prevent bottoming, little enough melt compression to transfer pressure efficiently, and a narrow enough variation band to protect the part's critical requirements. When the average looks correct but the spread is widening, the process is already providing a warning. Treating that warning as a maintenance and process-control signal is far more effective than repeatedly forcing the display back to target.

## Related Articles

- [Injection Molding Cushion Variation: From Silent Drift To ...](https://nhyscrews.com/blog/injection-molding-cushion-variation)
- [Your Injection Molding Cushion Is Drifting — Here's Why](https://nhyscrews.com/blog/injection-molding-cushion)
- [Injection Molding Screw Tip: How Hidden Wear Triggers ...](https://nhyscrews.com/blog/injection-molding-screw-tip)
- [Screw Tip Assembly Worn Out? Spot Failures Before They ...](https://nhyscrews.com/blog/screw-tip-assembly)
- [Stop Chasing Injection Molding Flash: Fix the Cause, Not ...](https://nhyscrews.com/blog/injection-molding-flash)
- [Inside the Injection Molding Barrel and Screw: What Others Skip](https://www.nhyscrews.com/blog/injection-molding-barrel-and-screw)
- [Sink Marks Injection Molding: Fix the Dent Before You Cut Steel](https://nhyscrews.com/blog/sink-marks-injection-molding)
- [Why Your Injection Molding Back Pressure Is Costing You Parts](https://nhyscrews.com/blog/injection-molding-back-pressure)
- [Your Injection Molding Shot Size Calculation Is Missing Melt ...](https://www.nhyscrews.com/blog/injection-molding-shot-size-calculation)
- [Check Ring Failing? Spot The Warning Signs Before Your ...](https://www.nhyscrews.com/blog/check-ring)