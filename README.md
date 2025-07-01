# Multi-Tenancy-Cloud-Data-with-Shared-Privacy-Preserving-Trusted-Keyword-Search
Description:
cloud service models intrinsically cater to multiple tenants. In current multi-tenancy model,
cloud service providers isolate data within a single tenant boundary with no or minimum
cross-tenant interaction. With the booming of cloud applications, allowing a user to search
across tenants is crucial to utilize stored data more effectively. However, conducting such a
search operation is inherently risky, primarily due to privacy concerns. Moreover, existing
schemes typically focus on a single tenant and are not well suited to extend support to a
multi-tenancy cloud, where each tenant operates independently. In this article, to address the
above issue, we provide a privacy preserving, verifiable, accountable, and parallelizable
solution for “privacy-preserving keyword search problem” among multiple independent data
owners. We consider a scenario in which each tenant is a data owner and a user’s goal is to
efficiently search for granted documents that contain the target keyword among all the data
owners. We first propose a verifiable yet accountable keyword searchable encryption
(VAKSE) scheme through symmetric bilinear mapping. For verifiability, a message
authentication code (MAC) is computed for each associated piece of data. To maintain a
consistent size of MAC, the computed MACs undergo an exclusive OR operation. For
accountability, we propose a keyword-based accountable token mechanism where the client’s
identity is seamlessly embedded without compromising privacy. Furthermore, we introduce
the parallel VAKSE scheme, in which the inverted index is partitioned into small segments
and all of them can be processed synchronously. We also conduct formal security analysis
and comprehensive experiments to demonstrate the data privacy preservation and efficiency
of the proposed schemes, respectively.
