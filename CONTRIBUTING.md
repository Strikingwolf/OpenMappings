# Contributing

1. Clone this repo somewhere.
2. Create and launch a Vanilla MC 1.10.2 instance.
3. Download the OML fork of [Enigma](http://modmuss50.me:8080/job/OpenModLoader/job/Enigma/)
4. Open Enigma.
5. Click `File -> Open Jar...` and select the 1.10.2 MC jar from the appropriate location for your launcher.
6. Click `File -> Open Mappings...` and select the `OpenMappings/` folder in this repo where you cloned it on your computer.
7. Deobfuscate.
8. Profit.

# Style guidelines

- Interface names should _not_ be prefixed with I.
- Use the simplest accurate form of the name. `hardness`, not `blockHardness`.
- Follow the official [Java naming conventions](http://www.oracle.com/technetwork/java/codeconventions-135099.html).
- If a naming pattern has been established, i.e. using Block as a prefix for block classes, please follow it. Consistency makes the mapping far easier to work with.
- Do not copy existing mapping projects, unless you can verify that said mappings are available under a license compatible to ours. This means that you cannot copy MCP.
