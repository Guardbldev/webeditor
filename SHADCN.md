    # shadcn-style UI (manual setup notes)

This project includes small, local shadcn-style primitives in `components/ui/` (Button, Card).

To add the full shadcn/ui stack you'll typically:

1. Install shadcn tooling (optional) and dependencies:
   ```bash
   npm install @radix-ui/react-dialog @radix-ui/react-tabs clsx class-variance-authority
   ```
2. Optionally run the shadcn generator and copy components into `components/ui/`.

The project already contains simple Button and Card primitives you can extend.
