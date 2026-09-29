# GitOps Operating Model

Production changes are made through Git. Argo CD continuously reconciles desired state. Emergency changes made directly with kubectl are temporary and should be reconciled back into Git.
