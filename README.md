# speed-dating-app
Goal: Create a model that predicts if a couple is a match at the end of the night

Dataset: This dataset was compiled by Columbia Business School professors Ray Fisman and Sheena Iyengar for their paper Gender Differences in Mate Selection: Evidence From a Speed Dating Experiment.

This script cleans, does some basic EDA/stat, and creates a model that predicts a match.

Column info:
*wave: speed dating round
*gender: gender of self
*age: age of self
*age_o: age of partner
*d_age: difference in age
*race: race of self
*race_o: race of partner
*samerace: is the pair the same race?
*importance_same_race: how important is it that your partner is the same race?
*importance_same_religion: how important is it that your partner is the same religion?
*field: field of study
*pref_o_attractive: how important does your partner rate being attractive?
*pref_o_sincere: how important does your partner rate being sincere?
*pref_o_intellgence: how important does your partner rate being intelligent?
*pref_o_funny: how important does your partner rate being funny?
*pref_o_ambitious: how important does your partner rate being ambitious?
*pref_o_shared_interets: how important does your partner rate having shared interests?
*attrative_o: rating by partner (about self)-how attractive is your partner?
*sincere_o: rating by partner (about self)-how sincere is your partner?
*intelligence_o: rating by partner (about self)-how intelligent is your partner?
*funny_o: rating by partner (about self)-how funny is your partner?
*ambitious_o: rating by partner (about self)-how ambitious is your partner?
*shared_interests_o: rating by partner (about self)-do you have shared interests?
*attractive_important: how important is it that your partner is attractive?
*sincere_important: how important is it that your partner is sincere?
*intelligence_important: how important is it that your partner is intelligent?
*funny_important: how important is it that your partner is funny?
*ambition_important: how important is it that your partner is ambitious?
*shared_interests_important: how important is it that you have shared interests with your partner?
*attractive: rate yourself-how attractive are you?
*sincere: rate yourself-how sincere are you?
*intelligence: rate yourself-how intelligent are you?
*funny: rate yourself-how funny are you?
*ambition: rate yourself-how ambitious are you?
*attractive_partner: rate your partner-how attractive is your partner?
*sincere_partner: rate your partner-how sincere is your partner?
*intelligence_partner: rate your partner-how intelligent is your partner?
*funny_partner: rate your partner-how funny is your partner?
*ambition_partner: rate your partner-how ambitious is your partner?
*shared_interests_partner: rate your partner-do you have shared interests with your partner?
*sports: scale 1-10-how interested in sports are you?
*tvsports: scale 1-10-how interested in tv sports are you?
*exercise: scale 1-10-how interested in exercise are you?
*dining: scale 1-10-how interested in dining are you?
*museums: scale 1-10-how interested in museums are you?
*art: scale 1-10-how interested in art are you?
*hiking: scale 1-10-how interested in hiking are you?
*gaming: scale 1-10-how interested in gaming are you?
*clubbing: scale 1-10-how interested in clubbing are you?
*reading: scale 1-10-how interested in reading are you?
*tv: scale 1-10-how interested in tv are you?
*theater: scale 1-10-how interested in theater are you?
*movies: scale 1-10-how interested in movies are you?
*concerts: scale 1-10-how interested in concerts are you?
*music: scale 1-10-how interested in music are you?
*shopping:scale 1-10-how interested in shopping are you?
*yoga: scale 1-10-how interested in yoga are you?
*interets_correlate: correlation between yours and your partners interests
*expected_happy_with_sd_people: how happy does you think you will be with the people you meet during this event?
*expected_num_interested_in_me: how many people will be interested in you during this event?
*expected_num_matches: how many matches do you think you will get?
*like: did you like your partner?
*guess_prob_liked: do you think your partner likes you?
*met: have you met your partner before?
*decision: what is your decision at the end of the night about your partner?
*decision_o: what was your partners decision at the end of the night?
*match: was is a match?!
