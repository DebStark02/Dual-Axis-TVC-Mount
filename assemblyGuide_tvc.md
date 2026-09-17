# Assembly & Mating Guide

> **Note on Hardware Attachments:** Screw holes, mounting bosses, and fastener locations are **not explicitly modeled** in the current SOLIDWORKS CAD files. For physical fabrication, mounting points must be manually drilled, heat-set, or jerry-rigged using zip ties, adhesives, or custom brackets.

---

## 1. Required Tools & Materials

- Drill bits / Rotary tool (for creating custom screw holes)
- M2 Screws, zip ties, or cyanoacrylate (CA) glue / epoxy
- Needle-nose pliers (for linkage clevis adjustment)
- SOLIDWORKS 2021+ (for virtual assembly reference)

---

## 2. Physical Assembly Steps

### Step 1: Base Frame & Pitch Servo
1. Position the primary **Pitch Servo (TowerPro SG90)** into the base frame cavity.
2. Secure the servo using hot glue, zip ties, or by drilling pilot holes for self-tapping screws.

### Step 2: Outer Gimbal Ring Integration
1. Align the Outer Gimbal Ring inside the Base Frame alignment arms.
2. Insert pivot pins or M2/M3 bolts along the pitch axis to establish the hinge.
3. Attach the pitch pushrod from the Servo Horn to the Outer Gimbal drive arm (jerry-rig attachment points if clevis holes are missing).

### Step 3: Yaw Servo & Inner Motor Mount
1. Fasten the secondary **Yaw Servo** onto the Outer Gimbal Ring platform.
2. Place the Inner Motor Housing into the Outer Gimbal Ring.
3. Pass hinge pins/bolts through the perpendicular yaw axis pivots.
4. Connect the yaw pushrod from the secondary Servo Horn to the Inner Motor Mount.

### Step 4: Motor & Propeller Mount
1. Position the **A2212 Brushless Motor** against the inner housing face.
2. Mark and drill clearance holes manually for the motor's X-mount bolt pattern, then secure with M3 screws.
3. Attach the propeller adapter and propeller to the motor shaft.

---

## 3. SOLIDWORKS Mate Verification Checklist

When opening `Tvector.SLDASM` to inspect the virtual design, verify the following mates are active:

- [ ] **Base to Outer Gimbal:** Concentric mate on pivot pins; limit angle mate for pitch travel.
- [ ] **Outer Gimbal to Inner Mount:** Concentric mate on yaw pivot pins; limit angle mate for yaw travel.
- [ ] **Linkages:** Coincident/Concentric mates on pushrod ends to simulate mechanical movement.