# Garagem

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
class DrumKitTestDrive {
	public static void main (String[] args) { 
		DrumKit d = new DrumKit();
		d.playSnare();
		d.snare = false;

		if (d.snare == true) {
			d.playSnare();
		}

		d.playTopHat();
	}
}
```