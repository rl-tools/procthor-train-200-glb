Generated with RLtools commit `ae98c8992087883ce25b6c07ec66ad094a8ca858` using `procthor2glb --normalize`.

Conversion command (run from the RLtools checkout after building `procthor2glb`):

```bash
for i in {0..199}; do
    ./build-codex-review/src/rendering/procthor2glb/procthor2glb "$HOME/git/ai2thor-hab/ai2thor-hab/configs/scenes/ProcTHOR"/*/"ProcTHOR-Train-$i.scene_instance.json" --normalize -o "$HOME/git/procthor-train-200-glb/ProcTHOR-Train-$i.glb"
done
```
