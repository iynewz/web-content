---
id: install-pymilvus.md
label: Install PyMilvus
related_key: SDK
order: 0
group: install-pymilvus.md
summary: Learn how to install the Python SDK of Milvus.
---

# Install Milvus SDK

This topic describes how to install Milvus SDK for Milvus.

Current version of Milvus supports SDKs in Python, Node.js, GO, and Java.

<div class="tab-wrapper"><a href="install-pymilvus.md" class='active '>Install PyMilvus</a><a href="install-node.md" class=''>Install Node.js SDK</a><a href="install-go.md" class=''>Install GO SDK</a><a href="install-java.md" class=''>Install Java SDK</a></div>

## Requirement

Python 3 (3.7.1 or later) is required.


## Install PyMilvus via pip

PyMilvus is available in [Python Package Index](https://pypi.org/project/pymilvus/).

<div class="alert note">
It is recommended to install a PyMilvus version that matches the version of the Milvus server you installed. For more information, see <a href="release_notes.md">Release Notes</a>.
</div>

```
$ python3 -m pip install pymilvus==2.0.1
```

## Verify installation

If PyMilvus is correctly installed, no exception will be raised when you run the following command.

```
$ python3 -c "from pymilvus import Collection"
```



## What's next

Having installed PyMilvus, you can:

- Learn the basic operations of Milvus:
  - [Connect to Milvus server](manage_connection.md)
  - [Conduct a vector search](search.md)
  - [Conduct a hybrid search](hybridsearch.md)

- Explore [PyMilvus API reference](/api-reference/pymilvus/v2.0.1/tutorial.html)
