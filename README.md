# avsar-opportunity-finder
# Avsar

**One place for the internships, scholarships and government schemes you actually qualify for.**

Built by Team Black Moon for the TinyFish Hackathon (Round 1: idea submission).

*Avsar* means "opportunity" in Hindi.

## The problem

A lot of students miss good opportunities, and it's usually not because they aren't good enough. Internships, scholarships and government schemes are spread over dozens of websites. Each one has its own layout, its own long eligibility rules, and a deadline that is easy to miss. By the time a student hears about something, the last date has often passed.

## What Avsar does

1. The student fills in a short profile once: course, year, skills, state, category and a rough family income range.
2. TinyFish web agents open real career pages, internship portals, scholarship sites and official government portals, and read the live listings.
3. For every listing, the agents pull out the eligibility, the deadline, the documents needed and the official apply link.
4. An AI model compares each listing with the student's profile and explains in simple words why they qualify, or what is missing.
5. The student sees one dashboard: what to apply for this week, what to check, and which documents to keep ready.

Avsar only finds and explains. The student always applies on the official site, and every result links back to its source.

## Why TinyFish

These sites don't share a common API, they change often, and many hide details behind filters and forms. A web agent can open them the way a person would, every time a student searches, so the results stay fresh.

## Planned architecture

Student profile -> TinyFish agents -> AI model (matching and explanation) -> Dashboard -> Official site

Planned stack: a simple web front end, a Python or Node backend, the TinyFish API and an AI model API.

## Current status

Round 1 is an idea submission. This repo holds the plan and a clickable prototype page (`index.html`) that uses sample data only. No real listings are shown yet.

## Roadmap

- [ ] Profile form and saved profile
- [ ] TinyFish agent for internship pages
- [ ] TinyFish agent for scholarship and government portals
- [ ] AI matching and "why you qualify" explanation
- [ ] Deadline sorting and document checklist
- [ ] Hindi and regional language support
- [ ] Deadline alerts

## Team

Team Black Moon: add names and roles here.

## Disclaimer

Avsar is a research helper. Always confirm details and apply on the official website.
