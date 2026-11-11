# PlanetCannon Fabric 1.21.11 port - STATUS (checkpoint, NOT yet compilable)

DONE: build.gradle/gradle.properties/workflow, fabric.mod.json, assets+data (1.21.11 format),
      PlanetCannonMod, Config (json), ModRegistry, ModNetwork, AlienShip (partial, earlier session)
TODO (from 1.20.1 bytecode, no source): PlanetCannonItem, CosmicBoltEntity, OrbitalStrikeEntity,
      PlanetPath, client: ClientFx, CinematicCamera, CockpitScene, OrbitalStrikeRenderer, Olympus,
      VoxelZeus, Vox, FxDraw, FxRenderTypes (render pipeline rewritten in 1.21.5+), ExplosionFx,
      EarthUplift, ChargeFx, CosmicBoltRenderer, CannonModeScreen, Dialogue, AlienAnim, client entrypoint
Unverified guesses: loom/fabric-api versions in gradle.properties - adjust if the build complains.
