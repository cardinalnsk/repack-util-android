# new.dat.br to img Converter
[Русский README](https://github.com/cardinalnsk/repack-util-android/blob/main/README.md)

This project is a console application written in Java that unpacks an OTA update archive and converts `*.new.dat.br` files into `*.img`.

## Why is it?

This project was created to automate the process of unpacking `*.new.dat.br` files, which are often used in Android development, into `*.img` files. This can be useful for developers who work with Android partitions.

## For whom?

This project is intended for enthusiasts who work with Android partitions.

## How to install or build?

To build and install the project, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/cardinalnsk/repack-util-android
```

2. Navigate to the project directory:
```bash
cd repack-util-android
```

3. Build the project using Maven:
```bash
mvn clean install
```

## How to use it?

To use the application, you will need to enter the following command in the command line:

Running the utility without additional flags:
```bash
java -jar repack-util-android.jar your-ota-update-with-brotli-files.zip

The result will be placed in the ./UnpackFirmware directory.
```

---

Example usage with a flag:
```bash
java -jar repack-util-android.jar your-ota-update-with-brotli-files.zip -o /path/to/output/directory

The result will be placed in the /path/to/output/directory.
```

## Documentation

- [English README](https://github.com/cardinalnsk/repack-util-android/README_EN.md)
- [Русский README](https://github.com/cardinalnsk/repack-util-android/README.md)

---