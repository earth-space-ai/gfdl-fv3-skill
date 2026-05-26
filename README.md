# GFDL FV3 Skill

Progressive-disclosure skill for the [GFDL Finite-Volume Cubed-Sphere](https://github.com/NOAA-GFDL/GFDL_atmos_cubed_sphere) atmospheric dynamical core (FV3), used in GFS, UFS, AM4, CM4, ESM4, SHiELD, and SPEAR.

> **Skill author:** Koutian Wu (ktwu01@gmail.com)
> **Skill version:** 0.1.0-scaffold

> ⚠️ **Disclaimer — please read before using this skill.**
> This skill is **not a gold-standard reference**. It is a helper that lowers
> the barrier for new users to **get their hands dirty** with the model. AI
> agents (and the humans drafting this material) make mistakes; commands, file
> paths, namelist options, and physics explanations here can be wrong,
> incomplete, or out of date. **Always cross-check with the official model
> documentation, the source code, and a human expert before trusting any
> output for research, publication, or operational use.**

## What This Is

A guide to the FV3 dycore: cubed-sphere grid, finite-volume numerics, vertical Lagrangian remapping, GFDL Microphysics, and how FV3 is embedded in host atmospheric models.

## Status

Scaffold. Repo layout, numerics overview, and citation requirements verified against the cloned 202411 release. Operational depth (specific stable parameter ranges, instability symptoms) being filled in.

## Related skills in this org

- [fms-skill](https://github.com/earth-space-ai/fms-skill)
- [mom6-skill](https://github.com/earth-space-ai/mom6-skill)

## Acknowledgments

**Gold-standard references for FV3** (use these to cross-check anything in this skill):
- NOAA-GFDL/GFDL_atmos_cubed_sphere repository: https://github.com/NOAA-GFDL/GFDL_atmos_cubed_sphere
- In-repo documentation under `docs/` (build with Sphinx locally for the latest)
- NOAA-GFDL organization (FV3 hosts: UFS, GFS, SHiELD, AM4, CM4): https://github.com/NOAA-GFDL

This scaffold exists only because of the work of other people, and any value
it has is borrowed from theirs.

- **NOAA-GFDL** for developing the FV3 finite-volume cubed-sphere dynamical
  core
  ([NOAA-GFDL/GFDL_atmos_cubed_sphere](https://github.com/NOAA-GFDL/GFDL_atmos_cubed_sphere))
  and GFDL Microphysics, and for releasing the dycore under terms that allow
  use in GFS, UFS, AM4, CM4, ESM4, SHiELD, and SPEAR.
- The **GFS / UFS communities at NOAA-EMC, EPIC, and partner centers** for
  the operational use that drives FV3 development.
- **Zesen Huang** for [laps-skill](https://github.com/huangzesen/laps-skill),
  the progressive-disclosure layout this repo borrows.

Any errors, oversimplifications, or out-of-date claims in this skill are the
skill author's responsibility, not the upstream community's. This is a
scaffold; operational depth is being filled in iteratively.

## License

MIT (skill content). FV3 source is governed by its own license; see https://github.com/NOAA-GFDL/GFDL_atmos_cubed_sphere/blob/main/LICENSE.md.
