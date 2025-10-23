# access-om3-experiments

### Branch name conventions
Branches in this repository use the following naming convention:
```
<GH-user-name>-<dev/test>-<YYYYMMDD>-<number>
```
where:
- `<GH-user-name>` is the GitHub user name of the person running the experiment
- `<dev/test>` is the type of experiment, where:
    - `dev` refers to experiments which are anticipated to make their way into the final model, e.g. spin-up simulations
    - `test` refers experiments used for testing different features or model changes, e.g. a parameter perturbation experiment
- `<YYYYMMDD>` is the date that the experiment started running.
- `<number>` is used to distinguish experiments run on the same date.

For example, `Chrisb13-test-20250305-3` would refer to the third "test" experiment run by @chrisb13 on 2025/03/05.
