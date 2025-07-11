# MeshEchoTuner

MeshEchoTuner helps test service meshes or microservice topologies by sending configurable echo requests and simulating latency, jitter, and loss.

## Features
- Run echo servers and clients with delay injection.
- Simulate latency and packet loss.
- Tune traffic behavior via config.
- Ideal for Istio, Linkerd, or service graph prototypes.

## Usage
```bash
git clone https://github.com/your-org/MeshEchoTuner.git
cd MeshEchoTuner
python meshecho/server.py &
python meshecho/client.py --host 127.0.0.1 --port 9000
