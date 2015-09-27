# Carbon apps

## Installation

```
$ git clone https://github.com/benoist/carbon-apps.git
$ crystal build libs/carbon/command -o ./carbon
```

## Usage
```
./carbon app <app_name> <app_dir>

cd <app_name>
shards install

crystal server.cr
```
