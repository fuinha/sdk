# The Things Uno Library

The Things Uno Library for Arduino has been renamed to The Things Network Arduino Library, moved to its own repository at [TheThingsNetwork/arduino-library](https://github.com/TheThingsNetwork/arduino-library) and can now also be installed and updated via the Arduino IDE Library Manager.

Be aware that you will have to updated your sketches and replace:

```c
#include <TheThingsUno.h>
TheThingsUno ttu;
```

With:

```c
#include <TheThingsNetwork.h>
TheThingsNetwork ttu
```

For aesthetics, you might want to replace `ttu` with `ttn` throughout your sketches as well.