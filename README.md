# Political Stories

This repository contains notebooks and scripts for exploring political news articles, detecting anecdotes, and performing stance analysis.

## Data Setup

Large dataset files are intentionally **not versioned** in this repo.

1. Download the data files from:
   https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Furldefense.com%2Fv3%2F__https%3A%2F%2Fdrive.google.com%2Fdrive%2Ffolders%2F1hWNlk5Vz4e_vkgwzM0ra8UKiQl4QJIYC%3Fusp%3Ddrive_link__%3B!!GIqKXF0_-xZi!q58ASnc33r1zI5OHCywebAtzqODr3LsD3ERkL9yBIZtpFPxgZLdz3VWlgxviti-SxDOpBT7sBmdealZBn0x5eq5ufYhSHcsXZId3eVHSFbpL%24&data=05%7C02%7Cmshokri%40gradcenter.cuny.edu%7C16922ed8980c464db84b08de906c2386%7C0b678335d50a41d3b15230149d930cfa%7C0%7C0%7C639106991302179875%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=EX5WHfIQJFsi77%2Bj%2FOQvKeyw0ibmJtFTZlOMZ4BuvsM%3D&reserved=0
2. Move the downloaded data files into the `news_data/` folder in this project.

## Repository Structure

- `news_data/` contains input data files (ignored in git; folder kept for structure).
- `anecdote_outputs/` contains generated outputs (ignored in git; folder kept for structure).
- `news_data_anecdote_analysis.ipynb` contains the main analysis workflow.

## Notes

- `sambanova_api_key.txt` is ignored and must not be committed.
- `.DS_Store` is ignored.
