# LIB_LLMIN: the inbox

Everything for Claude (or Spark) to read and act on comes in here, in a folder named after
the project it is for. One inbox for all projects, outside every git repo, so nothing here is
ever tracked and no project needs input folders or ignore rules.

| Folder | For |
|---|---|
| `LIB_GAMES/` | game ideas and designs |
| `LIB_XTJSON/` | `.livecode` stacks to harvest and analyse |
| `LIB_MOCAP/` | new captures: MoCapAnything `*_skeleton.glb` (+ BVH), or `.bvh` (read by `LIB_MOCAP/tools/mocap_lib.py`) |
| `LIB_PUBLIC/` | texts for the public pages |
| `xtalk_py/toCorpus/` | loose LiveCode scripts for the corpus (Spark's drafts in `_spark/`, `xtalk_py/tools/spark_catalogue.py`) |
| `xtalk_py/fromXJSON/` | XTJSON harvests of stacks to take apart into the corpus |

Any other project: make a folder with its name.

**The rule:** once Claude has read something and acted on it, it MOVES to
`../LIB_LLMOUT/Read/<same folder>/`. What is left here is still waiting.
