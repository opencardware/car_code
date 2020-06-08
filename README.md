# car_code
Starter code to be used on the Cardboard Car.

## Starter steps

1. Install `berryconda`
```
# Download
wget https://github.com/jjhelmus/berryconda/releases/download/v2.0.0/Berryconda3-2.0.0-Linux-armv7l.sh

# Install
bash Berryconda3-2.0.0-Linux-armv7l.sh
```

2. Clone this repo.

3. Create and activate `cardboard` env using the `environment.yml`.
```
conda env create -f environment.yml
source activate cardboard
```

4. Turn on the DC battery pack (AA batteries).

5. Test drive (use arrow keys).
```
python drive/manual.py
```

6. Configure Pi's camera (turn it on).
```
sudo raspi-config
  > Interfacing Options > Camera > REBOOT

# Take a test photo.
raspistill -v -o ~/Desktop/test.jpg
```
