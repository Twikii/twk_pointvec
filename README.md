# TwK-PointVec

**Note: This is a resource for script developers, it is not anything you should put in your gamemode.**

PointVec is a simple utiliy for bulk collection of coordinates.

## Installation

Simply add the `twk_pointvec` folder to your resources folder and `start twk_pointvec`.

## Usage

Start PointDev using the `/pointvec` command. Once running, stand where you would like to collect a `vector3` coordinate and press `E`. You will see a confirmation chat message.

When you are done collecting points, use the `/pointvec` command again, and the list of coordinates you collected will be saved in the `files` folder of the resource.

### Notes

* Coordinates are rounded to the hundredths place. This can be changed relatively easily.
* 1.0 meter is automatically subtracted from the `z` coordinate. Once again, this can be changed relatively easily.

## Support

No support is offered for this resource.

## License

TwK-PointVec is licensed under the MIT license. See [LICENSE.md](LICENSE.md) for more details.