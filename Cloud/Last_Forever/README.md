# Last Forever

by Lychnobyte

---

## Flag

```
TCP1P{jus7_l1k3_wh4t_1_s4id_y0u_4lw4ys_r3m4in5_h3r3_f0r3v3r_:')}
```

## Description
I have erased all my memories of you. But, why are you still in the deepest part of my heart? :')

`http://forever.lychnobyte.my.id`

## Difficulty
Tingkat kesulitan soal: easy-medium

## Hints
> Intentionally left empty

## Tags
Aws S3, Bucket versioning

## Deployment
Already deployed in my own cloud, no need to run! This is just for a note
- Install terraform or open tofu
- Go to `deploy` directory to create s3 bucket
    ```
    tofu init
    tofu apply -auto-approve
    ```
- Go to `script` directory to upload versioned flag file:
    ```
    chmod +x unggahhati.sh
    ./unggahhati.sh
    ```

## Notes
- Still need to manually set all `myheart.txt` versions as public accessible