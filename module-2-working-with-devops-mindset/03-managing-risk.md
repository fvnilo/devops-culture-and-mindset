# Managing Risk with DevOps

## Risk Management Theatre

- Are we just checking the boxes of the process that has been developed
  - "Well, we checked all the boxes! (shrug)"
- It makes us feel good that we think we are doing risk management but we are not

## DevOps Risk Mitigation and Management

- Focus on the process
- Improve delivery performance
- Increase stability, quality and speed

## Compare DevOps to ITIL Best Practices

**ITIL**: Information Technology Infrastructure Library

### ITIL Best Practices

- Change
- Release
- Configuration
- Incident
- Problem
- Knowledge Management

### DevOps Improves Change Management

- What's going on in the environment
- What's changing
- Document it

_Example_: In DevOps, most changes are automated. As long as there is an audit trail of the change and a way to surface the data when needed to understand the change especially when there is a change failure, we are good. Compare to having to fill out paperwork or having another team review the work.

## Risks Associated with Release

There is often a challenge with allowing teams to release their code. It is seen as conflicting with some of ITIL's best practices around having separation of duties.

DevOps release are automated and have audit trails.

## Reducing MTTR

A fast MTTR minimizes the concerns over how the changes are pushed to production.

## Freeze Windows

- a.k.a Restricted change windows
- Limit risk of change during high-potential revenue generating times

### Risks after freeze windows open

- Changes accumulate
- Big batches of changes
- Cause more incidents and issues

#### Example from Nordstrom

- Customer mobile application team invested effort in CI/CD
  - Good track record
  - Low defect count
- Exception granted for the freeze window
  - Responded to customer and business needs
  - More revenue

## Rething Philosophy of Change

- Allow for continual change when teams demontrate a consistent track record
- Invest in team capabilities
- Check track record
- Ensure minimal risk
- Risk management focuses on the **outcome**
