# {endstation or TLA}-workflows

> Replace all instances of {endstation or TLA} with the name of the endstation
> or the **lower-case** three-letter acronym of the beamline, if an endstation
> name does not apply. Finally, delete all instructions -- lines that start with
> `>`

> Choose one of the following descriptions; delete the other.

For beamlines with endstations: "Repository of workflows for the {endstation}
endstation of the {TLA} beamline."

For beamlines without endstations: "Repository of workflows for the {TLA}
beamline."

To configure running a workflow for CI, update test_run.py with the UID of a
test workflow run, and set the GitHub repo secret TEST_TILED_API_KEY to the
Tiled API key value used for these tests.
