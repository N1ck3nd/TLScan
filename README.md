# TLScan

TLScan is a TLS scanner designed to enumerate TLS/SSL protocol versions and cipher suite support. It provides color highlighting by using the [ciphersuite.info](https://ciphersuite.info/) API for easy identification of supported protocols and cipher suites.

## Installation

```bash
git clone https://github.com/N1ck3nd/TLScan.git
cd TLScan
python3 -m venv venv
pip3 install -r requirements.txt
```

## Usage

To use TLScan, simply run the script and provide the target hostname or IP address as a parameter.

```bash
python3 TLScan3.py <target>
```

## Compatibility

TLScan is only compatible with Python 3.

## License

TLScan is licensed under the [MIT License](https://github.com/ThreatLabsNL/TLScan/blob/master/License.txt).

## Acknowledgements

TLScan was originally developed by [ThreatLabsNL](https://github.com/ThreatLabsNL/TLScan). 
