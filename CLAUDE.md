# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This repository contains 3D model assets for a Weapons Mod for Space Engineers, using Blender (.blend) files for modeling and FBX files for game import.

## Commands
- **Open Blender File**: `blender /path/to/file.blend`
- **Export FBX**: From Blender, use File > Export > FBX (.fbx) with proper Space Engineers settings
- **Import FBX to Space Engineers**: Use the Space Engineers ModSDK to import models
- **Test Mod**: Run Space Engineers with mods enabled to test in-game

## Asset Guidelines
- **Organization**: 
  - Place WIP models in `/assets/roughdraft/`
  - Place completed models in `/assets/modelsdone/`
  - Place unused models in `/assets/scraps/`
  - Place export-ready FBX files in `/assets/fbxfolder/`
- **Naming Convention**: Use descriptive lowercase names (e.g. `railturret.blend`)
- **Scale**: Space Engineers uses meters - 1 Blender unit = 1 meter in-game
- **LOD**: Consider creating Level of Detail models for performance
- **Collision**: Create simplified collision meshes for physics interactions
- **Textures**: Use PBR materials compatible with Space Engineers