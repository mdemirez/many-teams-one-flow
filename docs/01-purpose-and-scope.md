# 1. Problem, Purpose and Scope

**The problem.** A new customer journey needs changes in five systems. One business team owns the journey. Four shared enabler teams own the systems behind it. Each team works in an agile way and delivers its own backlog on time. Yet the journey takes months to reach customers. When it finally does, nobody can say exactly what the service now does.

The problems sit between the teams:

- **Business intent gets lost on the way to the teams.** Nothing links the customer journey to the stories the teams build.

- **Work is split by system, not by value.** Each team builds its part, and nothing is usable until every part is done.

- **Work starts before teams have capacity for it.** Approved epics wait in enabler backlogs, next to requests from other streams.

- **Several business owners compete for the same team,** and nobody decides between them.

- **Integration problems show up late,** close to the release date.

- **A change in one system breaks another team’s interface.**

- **Requirements live in tickets.** A story describes a change, not the service, and it is closed once done.

- **Nobody describes the service end to end.** Behavior that crosses team lines is not written down anywhere.

Team-level methods do not say how teams should work together. Large frameworks add many roles and meetings, and they often still keep requirements in the backlog.

This playbook adds only what multi-team delivery needs: a clear commitment point, limits on work in progress, and stable contracts between teams. It is use-case driven and document-centric. A use case model describes what the service does, and every functional change traces back to it. Work is cut into use case slices, each delivering usable value. Tickets only track changes to the model. A few living documents describe the system as it is built. Everything else is left to the teams.

This playbook describes how multiple independent product teams deliver value together within an enterprise value stream. It is intentionally lightweight. It defines the process, the boards, the policies, and the checkpoints, but not the internal workings of any single activity or team. Anything the playbook does not define is left to the teams.

**Scope.** This playbook covers the **development value stream**: the flow of work from concept to release. It does not cover the operational value stream (the run-time flow from a customer request to its fulfillment). The two are related but distinct; when this document says “value stream” without qualification, it means the development value stream. The term does not refer to value stream mapping or to Value Stream Management tooling. It refers to the flow of work itself. It is designed for value streams of roughly five to six teams that share a system of many components. Work that stays within one team is managed on that team’s board.

**A note on stance.** This is an opinionated document. It does not claim to be the only correct way to run product development at scale, and it is not an implementation of any commercial framework. It combines ideas from flow economics, lean product development, use-case driven development, evolutionary architecture, and team topologies, adapted to an environment of shared enabler teams. Section 2 lists the main influences and the choices that depart from common practice.
