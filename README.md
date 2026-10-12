# Vexo Client access

## Add someone
1. Open [allowed-uuids.txt](allowed-uuids.txt).
2. Click the pencil / Edit file button.
3. Add their Minecraft UUID on a new line.
4. Click Commit changes, then Commit changes again.

## Remove someone
Delete their UUID line and commit the change. The client checks at startup and every five minutes. GitHub updates may take a little time to reach everyone.

## If someone is locked
They can use Copy My UUID on the Vexo access screen and send that UUID to you. Add it here, then they can click Retry. An empty list approves nobody.

Only the UUID list is public; this repository contains no client source or passwords. This is basic launcher-UUID access control, not protection against modified launchers or patched JARs. New sessions require an internet connection; already-approved sessions tolerate short connection outages.
