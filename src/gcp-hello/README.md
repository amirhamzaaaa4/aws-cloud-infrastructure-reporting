# GCP source snapshot

These files were manually transcribed from terminal listings in the GCP report, particularly image 9 and corroborating image 8. No original source files were attached. The listing prints main.py, requirements.txt and app.yaml sequentially; they are separated into their corresponding files here.

- [main.py](main.py): Flask root route. The student identifier was removed from the Hello response; whitespace was normalised.
- [requirements.txt](requirements.txt): Flask 2.3.3 and Gunicorn 21.2.0 as shown.
- [app.yaml](app.yaml): Python 3.12 runtime and Gunicorn main:app entrypoint as shown.

The original deployment succeeded according to screenshots. Portfolio validation checks Python syntax; it does not repeat deployment or certify dependency security. These pins are historical. Review dependencies and current platform requirements before any new deployment.

No AWS Lambda source is included because its screenshots expose fragments only. See [missing artifacts](../../docs/testing.md#missing-artifacts).
