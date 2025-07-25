This is the data from Functional Ecology's double-blind peer review trial, extracted on 15 September 2022. The trial is ongoing as of the time this was extracted so future datasets will be slightly larger and may fill some of the missing cells (e.g., for papers still under review at the time the dataset was extracted). 

The dataset contains personally identifying information that cannot be shared. This dataset on Dryad thus excludes information on an author's home country, including their country name, HDI and TOEFL scores. We do include HDI category because the sample sizes are large in each category and so this is inadequate to de-anonymize the dataset. Additional details can be provided with permission of the British Ecological Society and IRB approvals from the relevant oversight institutions. 

Because the research paper focuses on first authors, the data provided here included just one row per paper with author details only for the first author. If we provide additional authors in the dataset we would need to delete all of the biographic data because the combination of author details from multiple authors would likely allow author groups to be de-anonymized. We decided that the dataset would be most useful if we provide as much detail as possible on first authors (the focus of the paper), rather than including coauthors at the expense of less detail per author.

ManuscriptID = Manuscript number. This is a dummy variable not related to the original manuscript number. 

Treatment = Whether a paper was reviewed Single Blind or Double Blind.

Year = Submission year.

AuthorGender = Author gender, based on author given name using genderize.io. f = female; m = male. 

NumberReviewsCompleted = Number of reviews submitted by reviewers.

ReviewScore_Mean = Mean of the submitted reviews. A low score is a less positive review. 

PaperReviewed = Whether a manuscript was sent for review or not. 1 = yes, 0 = no. Empty cells are papers that were still under consideration by editors at the time the data was extracted. 

RevisionInvited = Whether a revision was invited or not. 1 = yes, 0 = no. Empty cells are papers that were still under review at the time the data was extracted. 

ResubInvited = Whether a resubmission (a paper that is rejected but invited for resubmission) was invited or not. 1 = yes, 0 = no. Empty cells are papers that were still under review at the time the data was extracted. 

AuthorHDICat = Whether the first author's home country was categorized as having an HDI that is Very High or Other (below Very High).

AuthorEnglish = When the first author's home country has English as a first or official language (Yes) or not (No).

RevOrResubInvited = Whether an author was invited to submit a revision or resubmission, of reviewed papers. 1 = yes, 0 = no. An empty cell is a paper that was either not sent for review or has not yet had a decision made. This column can be recreated from other columns. 