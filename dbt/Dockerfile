FROM ghcr.io/dbt-labs/dbt-bigquery:1.4.1
WORKDIR /dbt
COPY . ./

# TODO
ENV GCP_PROJECT=yelposphere2

ENV DBT_DATASET=yelp_dbt
ENV PORT=8080

ENTRYPOINT ["python", "invoke.py"]