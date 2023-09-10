# 787-10 (Flight Simulator 2020 Checklist + FMC/CDU Instructions)

## Initialization | Preflight

### POWER (CTRL-7, Column 2, Center)
   - [ ] **ELECTRICAL** - Battery Switch to ON Position *(CTRL-7, Column 1, Center)*
   - [x] HYDRAULIC - Ensure C1 ELEC and C2 ELEC pump selectors are Off (default)
   - [x] HYDRAULIC - Ensure L ELEC and R ELEC pump selectors are Off (default)
   - [ ] **ELECTRICAL** - External Power (if AVAIL) for FWD-L/FWD-R/AFTEXT (CTRL-7, Column 1, Center)

### PREFLIGHT (CTRL-7 / CTRL-8)
   - [ ] **IRS** - [Inertial Reference System](https://skybrary.aero/articles/inertial-reference-system-irs) (IRS) selectors to ON Position (LEFT/RIGHT) (CTRL-8, Column 1, Center)
   - [x] PRIMARY FLIGHT COMPUTERS - Primary Flight Computers Disconnect switch should be closed (default) (CTRL-7, Column 1, Center)
   - [x] ELECTRICAL - IFE/PASS SEATS power switch to ON position (default)  (CTRL-7, Column 1, Center)
   - [x] ELECTRICAL - CABIN/UTILITY to ON position (default) (CTRL-7, Column 1, Center)
   - [x] ELECTRICAL - APU GEN switches (L/R) to ON position (default) (CTRL-7, Column 1, Center)
   - [x] ELECTRICAL - Generator control switches to ON position (default) (GEN CTRL L1/L2/R1/R2) (CTRL-7, Column 1, Center)
   - [ ] **ELECTRICAL** - APU to START (then release it to ON)  (CTRL-7, Column 1, Center)
   - [x] WIPERS - Windshield WIPER selectors to OFF position (default) (CTRL-7, Column 1/4, Bottom)
   - [ ] **FD DOOR POWER** - Turn to ON position (CTRL-8, Column 2, Top)
   - [x] EMER LIGHTS - Close Guard (default) (ARMED by default)(CTRL-8, Column 2, Top)
   - [ ] **WINDOW HEAT** - Turn Primary heat switches to ON (Primary SIDE-L/FWD-L/FWD-R/SIDE-R) (CTRL-7, Column 2, Center)
   - [x] HYDRAULIC - Primary ENG switches to ON (default) (L ENG/R ENG) (CTRL-7, Column 2, Center)
   - [x] HYDRAULIC - Ensure ELEC C1/C2 are OFF (default) (CTRL-7, Column 2, Center)
   - [x] HYDRAULIC - Ensure DEMAND L/R ELEC are OFF (default) (CTRL-7, Column 2, Center)
   - [ ] **PASS SIGNS** - Turn Seatbelts selector to ON  (CTRL-7, Column 2, Bottom)
   - [x] FUEL - Fuel pumps should be in OFF position (default) (CTRL-7, Column 3, Center)
   - [ ] **ANTI-ICE** - Turn WING/ENGINE-L/ENGINE-R to AUTO position (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn NAV lights switch to ON position (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn LOGO lights switch to ON or OFF as required(CTRL-7, Column 3, Bottom)4
   - [ ] **AIR CONDITIONING** - Turn Packs switches (L PACK/R PACK) to AUTO  (CTRL-7, Column 4, Center)
   - [ ] **AIR CONDITIONING** - Turn on RECIRC UPPER, and FANS LOWER if necessary (CTRL-7, Column 4, Center)
   - [x] AIR CONDITIONING - Ensure TRIM AIR switches are on (default) (TRIM-L/TRIM-R)(CTRL-7, Column 4, Center)

### PREFLIGHT (CTRL-2)
   - [ ] **NAVIGATION** - Flight Director (F/D) switch to ON
   - [ ] **NAVIGATION** - Auto Throttle (A/T ARM) switch to ARM (Top Switches)
   - [x] NAVIGATION - Ensure Autopilot (A/P) Disengage bar is UP (default)
   - [x] NAVIGATION - BANK LIMIT selector to Auto (default)
   - [x] LANDING GEAR - Landing Gear Lever to DOWN position (default) (CTRL-2, Center, Down)
   - [ ] **AUTOBRAKE** - Turn Autobrakes Selector to RTO position (CTRL-2, Center, Down)
   - [x] PARKING BRAKE - Ensure Parking Brake is in SET position (default) (CTRL-4, Left)
   - [x] SPEEDBRAKE - Ensure Speedbrake lever is DOWN (top knotch) (CTRL-4, Middle-Left)
   - [x] FLAPS - Ensure Flaps lever is UP (default) (CTRL-4, Middle-Right)]
   - [x] FUEL CONTROL - Ensure L/R fuel control switches are in CUTOFF position (default) (CTRL-4, Center, Down)
   - [x] TRANSPONDER MODE - Ensure the TCAS/ATC selector switch is in STBY position (default) (CTRL-5, Center, Middle)
   
### FLIGHT MANAGEMENT COMPUTER (FMC) / CONTROL DIPSLAY UNIT (CDU) PROGRAMMING (CTRL-3) (If required)
   - [ ] **POS INIT** - Set your initial position (bottom right corner of the CDU/FMC)
        - [ ] **REF AIRPORT** - Enter [ICAO](https://en.wikipedia.org/wiki/Lists_of_airports_by_IATA_and_ICAO_code) code for originating airport (ICAO - i.e. KSEA)
        - [ ] **ROUTE** - Press the ROUTE button (bottom right corner of the CDU/FMC)
   - [ ] **RTE 1** - Press RTE button to select initial route information
        - [ ] **ORIGIN** - Enter [ICAO](https://en.wikipedia.org/wiki/Lists_of_airports_by_IATA_and_ICAO_code) code for originating airport (ICAO - i.e. KSEA), press ORIGIN button
        - [ ] **RUNWAY** - Enter Runway designation (i.e. RW16L), press RUNWAY button
        - [ ] **DEST** - Enter destination airport (ICAO) code, press DEST button
        - [ ] **FLT NO** - Enter Flight Number (i.e. AS612 -- Alaska Airlines Flight 612), press FLT NO button
        - [ ] **ACTIVATE** - Activate the route (RTE 1)
        - [ ] **EXEC** - Press EXEC button to execute the change
        - [ ] **NEXT PAGE** - Press NEXT PAGE to advance to the routes and add your VIA/AIRWAYS and TO/WAYPOINTS
   - [ ] **ACT RTE 1** - Press RTE button to select initial route information (i.e. DCT RYANN, J92 OAL, DCT TQILA)
        - [ ] **VIA** - Enter Jetways if you have them (i.e. J92), if not skip and they will be "DIRECT"
        - [ ] **TO** - Enter Waypoints if you have them (i.e. RYANN)
        - [ ] **REPEAT** - Continue repeating VIA/TO entries until done
        - [ ] **EXEC** - Press EXEC button to execute the change
        - [ ] **PERF INIT** - Press PERF INIT button (bottom right corner of the CDU/FMC)
   - [ ] **PERF INIT**
        - [ ] **ZFW** - Press the Zero Fuel Weight (ZFW) button twice to copy the value to the scratchpad and paste it in
        - [ ] **RESERVES** - Enter in the amount of fuel you want to reserve (i.e. 10.8)
        - [ ] **CRZ ALT** - Enter in the Cruise Altitude (i.e. 350)
        - [ ] **COST INDEX** - Enter in the Cost Index (i.e. 100)
        - [ ] **EXEC** - Press EXEC button to execute the change
        - [ ] **THRUST LIM** - Press THRUST LIM button (bottom right corner of the CDU/FMC)
   - [ ] **THRUST LIM** - 
        - [ ] **SEL/OAT** - Unless you want to limit your thrust, you can enter the same temperature as the outside air temperature (OAT)
        - [ ] **TO** - Unless you want to limit your thrust, you can keep the already selected "< TO value"
        - [ ] **CLB** - Unless you want to limit your thrust, you can keep the already selected "< CLB value"
        - [ ] **EXEC** - Press EXEC button to execute (if you made any changes)
        - [ ] **TAKEOFF** - Press TAKEOFF button (bottom right corner of the CDU/FMC)
   - [ ] **TAKEOFF**
        - [ ] **FLAPS** - Choose your FLAP setting (5 is typical)
        - [ ] **THRUST** - This should have been set on the previous page, but you can set it here if youy want
        - [ ] **CG** - Click the Center of Gravity (CG) button twice to copy the value to the scratchpad and paste it in
        - [ ] **V1** - The REF value should be calculated for you, click the button to copy the REF value
        - [ ] **VR** - The REF value should be calculated for you, click the button to copy the REF value
        - [ ] **V2** - The REF value should be calculated for you, click the button to copy the REF value
        - [ ] **NAVIGATION** - Take the value of V2, and copy it into the IAS speed setting (CTRL-2)
   - [ ] **DEP ARR** - Press DEP ARR button to select Departures/Arrival Procedures
        - [ ] **SIDS**
            - [ ] Select an appropriate [Standard Instrument Departure](https://en.wikipedia.org/wiki/Standard_instrument_departure) (if required) (i.e. SUMMA2)
            - [ ] Select an appropriate Transition (if required) (i.e. LKV)
        - [ ] **EXEC** - Press EXEC button to execute the change
   - [ ] **DEP ARR** - Press DEP ARR button again to show DEP/ARR INDEX
        - [ ] **ARR** - Press ARR button 
        - [ ] **STARS** - Choose an appropriate Standard Terminal Arrival Route (STAR) (if required) (i.e. COKTL3)
        - [ ] **TRANS** - Choose an appropriate Transition (if required) (i.e. TQILA)
        - [ ] **APPROACHES** - Choose an appropriate Approach (if known) (i.e. ILS 26L)
        - [ ] **TRANS** - Choose an appropriate Transition (if known) (i.e. TQILA)
        - [ ] **EXEC** - Press EXEC button to execute the change
   - [ ] **LEGS** - RTE Data - Build out the Route (RTE 1)
        - [ ] **DISCONTINUITY** - Erase route discontinuity if you have one
             - [ ] Select a leg from your route after the one you want to delete
             - [ ] This copies the name to the scratchpad
             - [ ] Paste it on the one before it to erase it
        - [ ] **EXEC** - Press EXEC button to execute the change
        - [ ] **REVIEW** - Review the route
            - [ ] **NAVIGATION** - Set the Navigation Display (ND) (CTRL-2) if needed
            - [ ] **NAVIGATION** - Set the Navigation Display (ND) Range by turning the ND Range knob (CTRL-2) if desired
            - [ ] **NAVIGATION DISPLAY** - On the touch display, switch to **PLAN** mode
            - [ ] **CDU/FMC - LEGS** - Press the PREV PAGE/NEXT PAGE to step through your plan

### BEFORE STARTING ENGINE (CTRL-7)
   - [ ] **ATC** - Contact ATC and Request Clearance for IFR
        - [ ] Set initial altitude (CTRL-2)
        - [ ] Set XPDR to ATC Squawk code (CTRL-5)
   - [ ] **HYDRAULIC** - Turn ELEC C1/C2 pump selectors to AUTO  (CTRL-7, Column 2, Center)
   - [ ] **HYDRAULIC** - Turn  DEMAND L/R ELEC pump selectors to AUTO (CTRL-7, Column 2, Center)
   - [ ] **FUEL** - Toggle PUMPS to ON position (L PUMPS-FWD/AFT CENTER PUMPS-L/R & R PUMPS-FWD/AFT) (CTRL-7, Column 3, Center)
   - [ ] **LIGHTS** Turn BEACON lights switch to ON position (CTRL-7, Column 3, Bottom)
   - [ ] **TRANSPONDER MODE** - Ensure the TCAS/ATC selector switch is in XPDR position (default) (CTRL-5, Center, Middle)

### STARTING ENGINE (CTRL-8)
   - [ ] **FUEL CONTROL** Flip LEFT SWITCH to RUN position - (CTRL-4, Center, Bottom)
   - [ ] **FUEL CONTROL** Flip RIGHT SWITCH to RUN position - (CTRL-4, Center, Bottom)
   - [ ] **ENGINE** - Turn RIGHT Engine Start/Ignition switch to START (CTRL-8, Column 3, Center)
   - [ ] **EICAS** - Monitor for Engine Start/Running in [Engine-indicating and crew-alerting system](https://en.wikipedia.org/wiki/Engine-indicating_and_crew-alerting_system) (CTRL-3 EICAS) display
   - [ ] **ENGINE** - Turn LEFT Engine Start/Ignition switch to START (CTRL-8, Column 3, Center)
   - [ ] **EICAS** - Monitor for Engine Start/Running in [Engine-indicating and crew-alerting system](https://en.wikipedia.org/wiki/Engine-indicating_and_crew-alerting_system) (CTRL-3 EICAS) display

### BEFORE TAXI
   - [ ] **ELECTRICAL** - APU to OFF (CTRL-7, Column 1, Center)
   - [ ] **FLAPS** - Set as appropriate for take off (CTRL-4)
   - [ ] **LIGHTS** Turn RUNWAY TURNOFF L/R ON (down position) (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn TAXI lights ON (down position) (CTRL-7, Column 3, Bottom)

### TAXI
   - [ ] **ATC** - Contact Ground Control (ATC) for taxi clearance
   - [ ] **PARKING BRAKE** - Ensure Parking Brake is in OFF position (CTRL-4, Left)
   - [ ] **STEERING** - Use your rudder pedals to steer the aircraft following ATC instructions
   - [ ] **PARKING BRAKE** - Ensure Parking Brake is in ON position (CTRL-4, Left) -- if required

### BEFORE TAKE OFF
   - [ ] **LIGHTS** Turn STROBE lights ON (down position) (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn LANDING lights L/NOSE/R to ON position (down) (CTRL-7, Column 2, Bottom)
   - [ ] **TRANSPONDER MODE** - Ensure the TCAS/ATC selector switch is in TA/RA position (default) (CTRL-5, Center, Middle)
   - [ ] **NAVIGATION** - Confirm initial Altitude (ALT) (CTRL-2)
   - [ ] **EICAS** - Set TRIM value from pre-flight information (CTRL-2)

### ALIGN WITH RUNWAY FOR DEPARTURE (CTRL-2)
   - [ ] **NAVIGATION** - Confirm initial Altitude (ALT) 
   - [ ] **NAVIGATION** - Setting Heading Mode (HDG) - Click
   - [ ] **NAVIGATION** - Enable LNAV and VNAV - This can be done later (when you enable VNAV, it should enable Auto/Throttle (A/T) automatically)

### TAKE OFF
   - [ ] **PARKING BRAKE** - Ensure Parking Brake is in OFF position (CTRL-4, Left)
   - [ ] **POWER LEVER** - Press TO/GA button in front of power levers (CTRL-1, swivel hard to right and press surface in front of levers)
   - [ ] **NAVIGATION** - Engage Auto-Pilot

### AFTER TAKE OFF
   - [ ] **FLIGHT** - Wait for positive rate of climb
   - [ ] **LANDING GEAR** - Landing Gear Lever to UP position (default) (CTRL-2, Center, Down)
   - [ ] **FLAPS** - Set to up position (no flaps) (C+TRL-4)

### CLIMB
   - [ ] **FLIGHT** - Wait for 10,000 feet elevation
   - [ ] **LIGHTS** Turn TAXI lights OFF (up position) (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn LANDING lights L/NOSE/R to OFF position (up position) (CTRL-7, Column 2, Bottom)

### CRUISING
   - [ ] **PASS SIGNS** - Turn Seatbelts selector to OFF  (CTRL-7, Column 2, Bottom)


### FLIGHT MANAGEMENT COMPUTER (FMC) PREPARE FOR TOP OF DESCENT (If Required) (CTRL-3)
   - [ ] **NAVIGATION** - Set Altutude to your ILS/VNAF capture altitude - Do NOT initiate a Flight Level Change
   - [ ] **INIT REF - INDEX - APPROACH** - Switch to the Approach Ref Page
        - [ ] **FLAPS** - Choose FLAP setting you prefer (i.e. Flap 30, VREF 139KT)
        - [ ] **FLAP/SPEED** - Transfer your FLAP setting to your preferred value

### DESCENT
   - [ ] **NAVIGATION** - Push Cancel/Recall (CANC/RCL) Switch (CTRL-2, Left)
   - [ ] **AUTOBRAKE** - Set Autobrakes as appropriate (CTRL-2, Center, Down)
   - [ ] **PASS SIGNS** - Turn Seatbelts selector to ON  (CTRL-7, Column 2, Bottom)

### APPROACH
   - [ ] **NAVIGATION** - Enable Approach Mode (APP) (CTRL-2) to allow capture of Glide Slope/Path - (CTRL-2)
   - [ ] **NAVIGATION** - Set Minimums (Turn Leftmost Knob to Radio, and dial in correct minimum value) - (CTRL-2)
   - [ ] **LIGHTS** At 10,000 feet turn LANDING lights L/NOSE/R to ON (down position) (CTRL-7, Column 2, Bottom)
   - [ ] **LIGHTS** Turn TAXI lights ON (down position) (CTRL-7, Column 3, Bottom)

 ### LANDING
   - [ ] **FLAPS** - Set to 20 degrees (or as required) (CTRL-4)
   - [ ] **SPD MODE** - Slowly start bring your Indicated Air Speed (IAS) down to your landing speed (CTRL-2)
   - [ ] **SPEEDBRAKE** - Ensure Speedbrake lever is ARMED (Second knotch from top) (CTRL-4, Middle-Left)
   - [ ] **AUTOBRAKE** - Set Autobrakes as appropriate (CTRL-2, Center, Down)
   - [ ] **FLAPS** - Set to 30 degrees for landing (or as required) (C+TRL-4)
   - [ ] **LANDING GEAR** - Landing Gear Lever to DOWN position (default) (CTRL-2, Center, Down)

### RUNWAY CLEAR
   - [ ] **ELECTRICAL** - APU to START (then release it to ON)  (CTRL-7, Column 1, Center)
   - [ ] **LIGHTS** Turn LANDING lights L/NOSE/R to OFF (up position) (CTRL-7, Column 2, Bottom)
   - [ ] **LIGHTS** Turn STROBE lights OFF (up position) (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn TAXI lights ON (down position) (CTRL-7, Column 3, Bottom)
   - [ ] **AUTOBRAKE** - Set Autobrakes to OFF (CTRL-2, Center, Down)
   - [ ] **FLAPS** - Set Flaps lever to UP (default) (CTRL-4, Middle-Right)]
   - [ ] **TRANSPONDER MODE** - Ensure the TCAS/ATC selector switch is in XPDR position (default) (CTRL-5, Center, Middle)

### SHUTDOWN
   - [ ] **PARKING BRAKE** - Ensure Parking Brake is in SET position (CTRL-4, Left)
   - [ ] **ELECTRICAL** - External Power (if AVAIL) for FWD-L/FWD-R/AFTEXT (CTRL-7, Column 1, Center)
   - [ ] **FUEL CONTROL** Flip LEFT/RIGHT SWITCH to CUTOFF position - (CTRL-4, Center, Bottom)
   - [ ] **PASS SIGNS** - Turn Seatbelts selector to OFF  (CTRL-7, Column 2, Bottom)
   - [ ] **HYDRAULIC** - Turn ELEC C1/C2 to OFF (CTRL-7, Column 2, Center)
   - [ ] **HYDRAULIC** - Turn DEMAND L/R ELEC to OFF (CTRL-7, Column 2, Center)
   - [ ] **FUEL** - Toggle PUMPS to OFF position (L PUMPS-FWD&AFT/C PUMPS-L&R/R PUMPS-FWD&AFT) (CTRL-7, Column 3, Center)
   - [ ] **LIGHTS** Turn BEACON lights switch to OFF position (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn TAXI lights OFF (up position) (CTRL-7, Column 3, Bottom)
   - [ ] **LIGHTS** Turn RUNWAY TURNOFF L/R OFF (up position) (CTRL-7, Column 3, Bottom)
   - [ ] **NAVIGATION** - Flight Director (F/D) switch to OFF (CTRL-2)
   - [ ] **TRANSPONDER MODE** - Ensure the TCAS/ATC selector switch is in STBY position (CTRL-5, Center, Middle)

### SECURE
   - [ ] **ELECTRICAL** - External Power to OFF position (if ON) for FWD-L/FWD-R/AFTEXT (CTRL-7, Column 1, Center)
   - [ ] **IRS** - IRS selectors to OFF Position (LEFT/RIGHT) (CTRL-8, Column 1, Center)
   - [ ] **FD DOOR POWER** - Turn to OFF position (CTRL-8, Column 2, Top)
   - [ ] **EMER LIGHTS** - Open Guard, Turn OFF, Close Guard (CTRL-8, Column 2, Top)
   - [ ] **AIR CONDITIONING** - Turn Packs switches (L PACK/R PACK) to OFF  (CTRL-7, Column 4, Center)
   - [ ] **AIR CONDITIONING** - Turn RECIRC FANS LOWER to OFF (CTRL-7, Column 4, Center)
   - [ ] **HUDS*** - Stow the Heads Up Display if you have been using them
   - [ ] **ELECTRICAL** - APU to OFF (CTRL-7, Column 1, Center)
   - [ ] **ELECTRICAL** - Battery Switch to OFF Position *(CTRL-7, Column 1, Center)*
