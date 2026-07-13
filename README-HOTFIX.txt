ARCHIPELAGO.MULTICLIENT.NET 6.6.1 PEAKS LARGE-ASYNC COMPATIBILITY HOTFIX

This is an unofficial compatibility hotfix. It is not an official
PeaksOfArchipelago release or an official Archipelago release.

This artifact does not contain the PeaksOfArchipelago mod. It contains a
modified build of the MIT-licensed Archipelago.MultiClient.Net 6.6.1 library,
based on upstream commit:

dda0939d319f6671048f879688c4b2ab5cde40d4

The only functional source change increases the connection/login timeout from
four seconds to 60 seconds. This build is intended to test login behavior in
extremely large Archipelago rooms.

Back up the existing Archipelago.MultiClient.Net.dll before replacing it with
this build.

This build is provided without warranty.
