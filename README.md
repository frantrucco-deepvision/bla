# Run examples

## What is this?

This is a script that runs a number of examples of the main program
with different switches.


## Prerequisites

First we need to download the test files. These test files include:
- A directory containing a camara_info.json file and a set of depth and rgb images.
- A test.bag file.

To download these files, simply run:

```
wget https://s3-us-west-2.amazonaws.com/dv-shepherdai/test_files -o test_files
```

Also remember to rebuild the docker image!


## Running the examples

To run the examples simply run:

```
./run_examples.sh <frontend_server_ip> <config_file> <tb_config_file> <attributes_file> <input_path>
```

Where:

- `<frontend_server_ip>` is the frontend server ip.
- `<config_file>` is the path of the configuration file.
- `<tb_config_file>` is the path of the thingsboard configuration file.
- `<attributes_file>` is the path of the attributes file.
- `<input_path>` is the path of the downloaded files.

