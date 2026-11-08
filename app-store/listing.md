# Projomia — App Store listing draft

Not entered in App Store Connect. Name availability and trademark clearance are still separate checks.

## Identity

| Field | Value | Limit | Count |
|---|---|---|---|
| Name | Projomia | 30 | 8 |
| Subtitle | AI Work Context & Memory | 30 | 24 |
| Promotional text | Capture the work. Connect the knowledge. Give AI the context to understand your work and solve real problems. Photos, notes, and plans stay on your devices. | 170 | 156 |
| Keywords | construction,photos,notes,drawings,documents,planner,journal,offline | 100 | 68 |
| Price | Free | | |
| Proposed version | 1.0.0 | | |

The Xcode project is still 0.13.7 (80). Set 1.0.0 and a new build number when the distribution archive is made. Do not upload this draft.

Headline, for the website and review notes, not a separate App Store field: Everything about your work.

Core promise: Give AI the context to understand your work and solve real problems.

Philosophy: Capture the work. Connect the knowledge. Build the context. Solve the problem.

## Description

Projomia keeps the record of a project on your iPhone.

Capture photographs into the room you choose. Import still images from Photos. Add notes, drawings, and documents. Use Planner, Journal, and Daily Log for the work as it happens. Browse by project, folder, and date.

Your library stays on the device. There is no Projomia account and no Projomia cloud. If you also use the Mac app, pair the two devices and synchronize directly over your local network. When both sides change the same record, you choose which version to keep.

AI is optional. Connect your own OpenAI API key or ChatGPT account, then confirm what to send. Projomia can include the question, notes, project context, and photographs you select. A suggestion copy is a resized image with location metadata removed. An exact-original send, which the screen identifies, can include location metadata already in the file. The app works fully if you never turn AI on.

Projomia does not use advertising or tracking.

## Screenshot captions

Use captures of the current app after the Projomia name is on screen.

1. Projects — Everything about your work.
2. Camera — Capture the photograph into the room you choose.
3. Photos and notes — Keep the visit with the picture.
4. Drawings and documents — Read the files in the project.
5. Planner — See the work, the areas, and what is waiting.
6. Daily Log — Record the day against that plan.
7. Projomia AI — Send only the context you confirm.
8. Local sync — Pair a Mac and iPhone directly.

## URLs

Intended, not live until published and checked:

- Privacy: https://projomia.com/privacy/
- Support: https://projomia.com/support/

Do not paste these into App Store Connect until HTTPS returns the prepared pages.

## App Review notes

Projomia is free. No sign-in is required. Create a project and use the camera, notes, drawings, documents, Planner, Journal, and Daily Log offline.

AI is optional. It uses the reviewer’s own OpenAI API key or ChatGPT account. Nothing is sent until the reviewer confirms. Suggest-information copies strip location metadata. Exact-original sends can include GPS already stored in the file. Requests use store:false. Projomia has no server.

Background processing indexes on the device and does not upload the library. Local network permission is only for optional direct sync with a paired Mac.

The library folder inside the app’s Files area is named RoomLog. That name is the storage folder, not the product name.
