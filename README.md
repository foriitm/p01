# GitHub Austin Developer Analysis

- Leveraged GitHub's REST API with Python to extract comprehensive data on Austin-based developers (100+ followers), capturing 11 profile metrics and 9 repository attributes including stars, languages, and project features across their repositories using pandas and requests libraries.

- The programming language with the highest average number of stars per repository is Fennel, with an average of 2,446 stars. A language I had never heard of before.

- Developers seeking to maximize their GitHub influence should focus on creating public repositories, as each additional repository correlates with 3.824 more followers, and consider enabling project features since 97.7% of repositories have both wikis and projects enabled.

## Detailed Findings

### Data Collection Process

- Utilized GitHub's REST API with authenticated requests
- Collected data from users with 100+ followers in Austin
- Scraped detailed metrics including:
  - User profiles (followers, following, repos, etc.)
  - Repository details (stars, languages, wiki status)
  - Temporal data (creation dates, activity patterns)

### Key Statistical Insights

1. **Repository Impact**

   - Strong correlation (0.621) between public repos and followers
   - Each public repository correlates with 3.824 additional followers
   - High correlation (0.977) between wiki and project features

2. **Technology Landscape**

   - JavaScript is the most prevalent programming language
   - Most common licenses: mit, apache-2.0, gpl-3.0
   - Project and wiki features typically enabled together

3. **User Behavior Patterns**
   - Bio length shows positive correlation with follower count
   - Weekend repository creation patterns identified
   - Public repository count predicts follower growth

### Recommendations for Developers

1. Create more public repositories
2. Enable both wiki and project features
3. Maintain detailed bio descriptions
4. Consider weekend contributions
5. Keep repository metadata complete and updated
