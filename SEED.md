Act as a Systems Architect. Initialize the directory structure for 'localnexus-ed'.

Generate the following file hierarchy:
- `/client/src/hooks/useSync.ts`
- `/client/src/components/LessonBuilder.tsx`
- `/server/src/mesh/nodeDiscovery.ts`
- `/server/src/ai/localLLM.ts`
- `docker-compose.yml`

Inside each file, add a single comment as a generation prompt:
- useSync.ts: "# Prompt: Implement a React hook using PouchDB to handle conflict resolution when syncing local classroom data to a central school node."
- nodeDiscovery.ts: "# Prompt: Write a Node.js utility that uses UDP broadcasts to discover other LocalNexus instances on the same local network."
- localLLM.ts: "# Prompt: Create a wrapper for a local Llama.cpp instance that takes a curriculum subject and generates a 5-day lesson plan."
