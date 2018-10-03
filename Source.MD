# Input
* clipRate
* unusedClips
* factoryLevel
* availableMatter
* acquiredMatter
* wire
* harvesterLevel
* wireDroneLevel
* wenn availableMatter = 0 and totalMatter = foundMatter -> done
* probeCost
* probeLaunchLevel
* probeDescendents
* probesLostHaz
* probesLostDrift
* probesLostCombat
* probeCount
* driftersKilled
* drifterCount
* swarmGifts
* processors
* memory
* operations
* maxOps = memory * 1000
* swarmSize = harvesterLevel + wireDroneLevel
* giftCountdown
* qChip0
* qChip1
* qChip2
* qChip3
* qChip4
* qChip5
* qChip6
* qChip7
* qChip8
* qChip9
* stratPickerElement.value
* yomi
* tourneyCost
* honor
* probeTrustUsedDisplay
* probeTrustDisplay
* maxTrustDisplay
* probeSpeed
* probeNav
* probeRep
* probeHaz
* probeFac
* probeHarv
* probeWire
* probeCombat
* probeTrustCost
* maxTrustCost
* unsoldClips = get unsold paper clips
* funds = get Available Funds

# Output

* Button:Make Paperclip - buyWire();
* Button:lower - lowerPrice();
* Button:raise - raisePrice();
* Button:marketing - buyAds();
* Button:Wire - buyWire(); 
* Button:AutoClippers - makeClipper(); 
* Button:Processors - addProc();
* Button:Memory - addMem();
* Button-Quantum:Compute - qComp();
* Button-Strategic:AutoTourney - toggleAutoTourney();
* Button-Strategic:New Tournament - newTourney();
* Button-Strategic:Run - runTourney();
* Button-ProductionMW:Solar Farm - makeFarm(1);
* Button-ProductionMW:+10 - makeFarm(10);
* Button-ProductionMW:+100 - makeFarm(100);
* Button-ProductionMW:Disassemble All - farmReboot();
* Button-StorageMW:Battery Tower - makeBattery(1);
* Button-StorageMW:+10 - makeBattery(10);
* Button-StorageMW:+100 - makeBattery(100);
* Button-StorageMW:Disassemble All - batteryReboot();
* Button-WireProduction HarvesterDrone:Harvester Drone - makeHarvester(1);
* Button-WireProduction HarvesterDrone:+10 - makeHarvester(10);
* Button-WireProduction HarvesterDrone:+100 - makeHarvester(100);
* Button-WireProduction HarvesterDrone:+1k - makeHarvester(1000);
* Button-WireProduction WireDrone:Wire Drone - makeWireDrone(1);
* Button-WireProduction WireDrone:+10 - makeWireDrone(10);
* Button-WireProduction WireDrone:+100 - makeWireDrone(100);
* Button-WireProduction WireDrone:+1k - makeWireDrone(1000);
* Button-WireProduction WireDrone:Disassemble All - wireDroneReboot();
* Button-Manufacturing:Clip Factory - makeFactory();
* Button-Manufacturing:Disassemble All - factoryReboot();

