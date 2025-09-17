# Event Schema – Job Match Relevance

## Events
- `job_card_viewed`
- `job_card_clicked`
- `job_apply_started`
- `job_apply_completed`
- `feedback_irrelevant_job`

## Metrics Mapping
- **CTR** = job_card_clicked / job_card_viewed
- **Apply Rate** = job_apply_completed / job_card_clicked
- **Quality Feedback** = recruiter rating distribution
- **Negative Feedback** = % of irrelevant job reports