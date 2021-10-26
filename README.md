# test3
url = 'https://api.patentsview.org/patents/query?q={"assignee_organization":"harvard university"}'
r=requests.get(url)
json = r.json()  # Convert response to JSON format
