# Enterprise-Gamer-Vault-
Enterprise Gamer Vault

A self-contained, single-file HTML toolkit for building and running your own tabletop / campaign game system: card forge, quest map builder, 3D dice designer, a code vault for saving your own game logic snippets, a music player for the table, and an encrypted local save file for all of it.

Everything lives in one .html file. No server, no build step, no external accounts. Open it in a browser and it runs.

Features
Vault lock — real AES-256-GCM encryption with a PBKDF2-derived key from your own passphrase, protecting a single save file kept in your browser's local storage.
Card Forge — design and "mint" custom game cards (title, lore, traits, cost), gallery view, JSON export.
Quest Maps — click-to-build node maps with main/side quests, intervals, and connecting paths; drag to reposition, double-click to mark complete, right-click to delete.
Dice Designer — a genuine 3D CSS cube you can relabel face-by-face, plus quick randomizers for d4–d100.
Code Vault — multiple named code boxes with a lock/unlock (view-only vs. editable) toggle, commit history per box, restore-from-history, and a sandboxed run preview for HTML/JS snippets.
Templates — reusable text/JSON blocks (NPC sheets, side-quest formats, etc.) you can drop into a new code box.
In-game currency — coins and keys mint as you play; a "credit code" generator produces a cosmetic code tied to your balance for use inside your own game.
Fractal transitions — a live-rendered Mandelbrot zoom plays between tabs as a visual flourish.
Honest limits — please read before building on this
Coins, keys, and credit codes are fictional, in-game currency only. They are not money, cannot be cashed out, are not tied to any market (crypto, stock, prediction market, or otherwise), and nothing in this file talks to a bank, exchange, or the internet. If you want real payments or redemption, that needs actual licensed financial and legal infrastructure — a browser file can't provide that safely, and I'd steer clear of any tool that claims otherwise.
The encryption is real but scoped: it protects the local save file in your own browser. It is not a transaction-verification system, and there's no "verify by passphrase instead of hashing" trick that makes a currency system secure — that's not how any of this works. If you build a real points/rewards system later, standard practices (a real backend, real auth, real ledger) are what get you there safely.
No password recovery exists. Losing your passphrase means losing that vault's save file.
License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0).

In short: you're free to use, modify, and distribute this software. If you run a modified version of it as a network service that other people interact with, the AGPL requires you to make your modified source available to those users. See the full license text below for the exact terms.

Enterprise Gamer Vault
Copyright (C) 2026 Joseph La Follette

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.

The full AGPL-3.0 license text is available at: https://www.gnu.org/licenses/agpl-3.0.txt

