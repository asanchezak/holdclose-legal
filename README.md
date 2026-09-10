# HoldClose — legal pages

The published Privacy Policy and Terms of Service for the **HoldClose** iOS app.

- https://asanchezak.github.io/holdclose-legal/privacy-policy.html
- https://asanchezak.github.io/holdclose-legal/terms.html

## Do not edit these files by hand

They are generated from the app's own `LegalDocument.swift` by
`scripts/generate-legal-html.sh` in the app repository, and pushed here by
`scripts/publish-legal.sh`. A test in the app (`LegalHTMLTests`) fails if the
generated pages fall behind the documents the app displays, which is what stops
the published policy from drifting away from the one users actually see.

To change the policy: edit `LegalDocument.swift` in the app, run the publish
script, and ship an app build with the same wording.
