## OS: MS Windows 11

```sh
 curl.exe https://repo.anaconda.com/miniconda/Miniconda3-py312_26.1.1-1-Windows-x86_64.exe --output .\Miniconda3.exe
.\Miniconda3.exe

> Follow onscreen interation

```

## Open terminal

Press [Window] key, and start typing `anaconda prompt`; and on seeing `Anaconda Prompt (App)`. click on `Open` to launch it. 

```sh
conda create -n osdag-env osdag::osdag -c conda-forge -c geompy

#  environment location: D:\Programs\MiniConda\envs\osdag-env


Channel "defaults" has the following notices:
  [info] -- Tue Jun  9 00:00:00 2026
  PyTorch 2.12 with CUDA support is now available to install with your current channel (Anaconda Main). Learn more: htts


(base) D:\IIT_OSD>
```

## launching Osdag

## Open terminal

Press [Window] key, and start typing `anaconda prompt`; and on seeing `Anaconda Prompt (App)`. click on `Open` to launch it. 

```sh
conda activate osdag-env
osdag
```

## Deactivate environment

```sh
conda deactivate
```
