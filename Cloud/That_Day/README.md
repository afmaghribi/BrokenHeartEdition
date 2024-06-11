# That Day

by Lychnobyte

---

## Flag

```
TCP1P{4nd_c3l3br4t3_y0ur_h4pp13st_d4ys_th3r3_:')}
```

## Description
But perhaps you hate a thing and it's good for you And perhaps you love a thing and it's bad for you :')

`http://foryou.lychnobyte.my.id`

## Difficulty
Tingkat kesulitan soal: easy-medium

## Hints
> Intentionally left empty

## Tags
Kubernetes, Kubelet, Anonymous Auth

## Deployment
Already deployed in my own vps, no need to run! This is just for a note
- Scp `sites` to vps and move to `/var/www/sites`
- Deploy `microk8s` using guide
- Deploy all chall manifest in `deploy_sites.yaml`
  ```
  microk8s kubectl create -f deploy_sites.yaml
  ```

## Notes
