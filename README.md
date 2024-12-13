spec = {"backeng": "Mongodb", "frontend": "AngularJS"}

print(spec["backend"])
spec["App"] = "website"
print(spec)
spec.pop("frontend", None)
print(spec)
