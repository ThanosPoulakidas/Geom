# GEOM
Geom is a variable and static sans typeface designed by Thanos Poulakidas.


## Basic Information
Geom, is a contemporary geometric sans serif typeface. It has 7 weights. This typeface is intended for display purposes but it works just as well in small texts. Even though the geometric typefaces look more dynamic in relation with other typefaces, Geom has gone one step further by having an even more additional dynamic characteristics on some of its characters. The typeface is a variable font which includes a Latin and Greek character set.


**Variable Axes**

Geom has the following axes:

- Weight (wght) - 300 to 900. (Default 300) Controls the darkness of the composed text. 


**Language Support**
<details>
<summary>Expand</summary>
<p>
Latin: English
<p>
Greek: Monotonic Modern Greek.
<p>
</details>  

## Building the fonts

### Step 1: Install Requirements

Set up a virtual environment in the root directory:

```
virtualenv -p python3 venv
```

Activate the virtual environment with:

```
source venv/bin/activate
```

Install requirements with:

```
pip install -U -r requirements.txt
```

### Step 2: Build the fonts

**Building the fonts**

The scripts for building the fonts are in the `/sources/` folder.

To build the variable font run:

```
cd sources
sh build_vf.sh
```

To build the static ttfs run:

```
cd sources
sh build_statics.sh
```

To build the variable font and the static ttfs run:

```
cd sources
sh build_all.sh
```  

If you want to build otf's do so through Glyphs using the source Glyphs file. 


```

## ChangeLog

This is version 1.000. No changes to report. 

## License

Geom is licensed under the SIL Open Font License v1.1 (<http://scripts.sil.org/OFL>).

To view the copyright and specific terms and conditions please refer to [OFL.txt](https://github.com/ThanosPoulakidas/Geom/blob/main/OFL.txt)
