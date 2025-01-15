# Backstage is not your platform - PlatformEngineering.org (Humanitec) Webinar

*Notes AI-generated from a combination of the YouTube transcript and my previous notes*

## Key Message

- Backstage is a good frontend for platforms but should be treated as just that - a frontend
- A platform is the sum of all different components that platform engineers put together
- The goal is to create golden paths that lower cognitive load for all user personas

## Current State of Platform Engineering

- Around 60% of platform engineering initiatives are using Backstage
- Internal assessment shows 500-600 platform engineering initiatives last year
- Estimated to have tripled this year to 1,500-2,000 initiatives
- Humanitec is starting a new platform engineering initiative with 500+ developers every three days

## Platform Engineering is tough, but game changing

[Netflix's case study](https://www.youtube.com/watch?v=36FcxlPerdQ)

In 2022: Started building unified engineering experience platform
In 2023: Revealed that "the view and assess experience provides value but on its own is not yet compelling enough to pull users in away from existing habits and routines"
**Key learning**: Focus should be on meeting developers where they are rather than changing their habits

# Common Platform Problems

- Adoption rates aren't high enough
- Maintenance becomes difficult
- Too much functionality packed into frontend layer
- "Infrastructure Tetris" - continuous resource creation without lifecycle management

## Platform Design Principles
1. Multi-player Game
   - Must serve multiple personas: developers, infrastructure teams, operations, security, product managers, executives
   - Can't optimize for one group at expense of others
   - Security teams often underrepresented in platform discussions

2. Two Key Value Drivers
   - Automation
   - Standardization

3. Interface Choice
   - Don't force all users into one interface
   - Provide multiple options: UI (Backstage), CLI, API, code-based methods
   - Meet users where they are

## Implementation Approaches

### Backend Options
1. Pipeline-based backends
   - Good for smaller setups (20-50 developers)
   - Familiar technology (GitHub Actions, Jenkins)
   - Harder to scale due to linear/start-stop logic
   - Requires more human resources to maintain at scale

2. Graph-based backends (Platform Orchestrators)
   - Better for larger scale operations
   - More sophisticated automation
   - Better lifecycle management
   - Multiple options available (both open source and commercial)

## Platform Team Composition
- Need diverse profiles:
  - Platform product owner (doubles chances of success at 12 months)
  - Infrastructure/Kubernetes experts
  - Developer experience representatives
  - Experience level should match organization scale
- Team size shouldn't scale linearly with developer count

## Success Factors
- Start smaller than imagined
- Build MVP in 4-8 weeks
- Choose right first team (not the most advanced)
- Focus on showing concrete ROI
- Consider total cost of ownership (including maintenance)
- Create pull rather than push adoption
- Focus on building something 10x better than current solutions
- Focus on [Pareto efficiency](https://en.wikipedia.org/wiki/Pareto_efficiency) - where an outcome is better in every way
