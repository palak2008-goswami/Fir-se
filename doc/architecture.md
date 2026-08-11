# Fir Se - System Architecture

                     FIR SE
                        │
          ┌─────────────┴─────────────┐
          │                           │
      FRONTEND                     BACKEND
          │                           │
          │                     ┌─────┴─────┐
          │                     │           │
          │                   API        SERVICES
          │                     │           │
          │                     │      ┌────┴────┐
          │                     │      │         │
          │                  DATABASE   AI    MATCHING
          │
          └──────────────► FILE STORAGE
