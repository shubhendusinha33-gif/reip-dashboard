# REIQ by Shubhendu

REIQ is the next-generation entry point for the Retail Expansion Intelligence product.

## V1
- Existing REIP production files remain unchanged.
- REIQ gets a separate `/reiq/` entry point.
- REIQ Core reuses the existing dashboard baseline rather than duplicating or modifying production logic.
- Satellite Intelligence, Development & Growth, and Network Intelligence are staged as separate product modules.

## Security
- No API key, token, credential, password, service-account JSON, or secret is stored in this folder.
- Google API keys remain browser-side only, consistent with the current application's local-storage approach.
- Never commit secrets to this public repository.

## Next build
Connect approved satellite/imagery and development data sources through a server-side proxy when credentials or proprietary processing are required.