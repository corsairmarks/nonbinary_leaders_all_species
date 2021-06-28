# Overview

This is a submod for [Gender Nonbinary Leaders](https://steamcommunity.com/sharedfiles/filedetails/?id=2528614880) that activates for every species the chance for leaders to reconsider their gender identity.

# Changes

Overwrites one trigger from the main mod, which results in leaders of every species potentially reconsidering their gender identity upon spawning.

## Compatibility

Same as the main mod.

### Dependencies

In order for this mod to fully function, you **must** install and use [Gender Nonbinary Leaders](https://steamcommunity.com/sharedfiles/filedetails/?id=2528614880).

## Known Issues

Because this mod overrides an effect from the main mod, expect to see one line in error.log like this:

```
[13:55:38][game_singleobjectdatabase.h:147]: Object with key: should_roll_to_reconsider_gender_identity already exists
```

## Changelog

* 1.0.0-alpha1 1.0.0-alpha1 Alpha version: non-gendered species do consider changing their gender identity, but the game does not allow giving their leaders a gender even through `create_saved_leader`

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/nonbinary_leaders_all_species)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.