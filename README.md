## ms-progressbar

Redesign of the mdn_progressbar by Medinaa#7364, this redesign has been done by Molina#6922

It is strictly forbidden to steal this script either by changing the name or removing the authors' names.

MS-SCRIPTS: https://discord.gg/BCrFN5QDZu


## Preview:

![image](https://user-images.githubusercontent.com/113800789/230503525-05f346f6-8bbd-414f-901e-da3cd7a4a2f1.png)


## How to install ms-progressbar?

The installation of this textui is very simple, here is a step-by-step explanation:

1. In the file en_extended/client/functions.lua replace line 82 to line 84 with this:

function ESX.Progressbar(message, length, Options)
    exports["esx_progressbar"]:Progressbar(message, length, Options)
end

## How to add ms-progressbar to any script?

``exports['ms-progressbar']:Progress(message, time, color)``

``TriggerEvent('ms-progressbar:progress', message, time, color)``
