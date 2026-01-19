---
permalink: /0.20/nogroup/v1alpha2/clusterBundle/
---

# nogroup.v1alpha2.clusterBundle



## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withInLineCAs(inLineCAs)`](#fn-specwithinlinecas)
  * [`fn withIncludeDefaultCAs(includeDefaultCAs)`](#fn-specwithincludedefaultcas)
  * [`fn withSources(sources)`](#fn-specwithsources)
  * [`fn withSourcesMixin(sources)`](#fn-specwithsourcesmixin)
  * [`obj spec.sources`](#obj-specsources)
    * [`fn withKey(key)`](#fn-specsourceswithkey)
    * [`fn withKind(kind)`](#fn-specsourceswithkind)
    * [`fn withName(name)`](#fn-specsourceswithname)
    * [`obj spec.sources.selector`](#obj-specsourcesselector)
      * [`fn withMatchExpressions(matchExpressions)`](#fn-specsourcesselectorwithmatchexpressions)
      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specsourcesselectorwithmatchexpressionsmixin)
      * [`fn withMatchLabels(matchLabels)`](#fn-specsourcesselectorwithmatchlabels)
      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specsourcesselectorwithmatchlabelsmixin)
      * [`obj spec.sources.selector.matchExpressions`](#obj-specsourcesselectormatchexpressions)
        * [`fn withKey(key)`](#fn-specsourcesselectormatchexpressionswithkey)
        * [`fn withOperator(operator)`](#fn-specsourcesselectormatchexpressionswithoperator)
        * [`fn withValues(values)`](#fn-specsourcesselectormatchexpressionswithvalues)
        * [`fn withValuesMixin(values)`](#fn-specsourcesselectormatchexpressionswithvaluesmixin)
  * [`obj spec.target`](#obj-spectarget)
    * [`obj spec.target.configMap`](#obj-spectargetconfigmap)
      * [`fn withData(data)`](#fn-spectargetconfigmapwithdata)
      * [`fn withDataMixin(data)`](#fn-spectargetconfigmapwithdatamixin)
      * [`obj spec.target.configMap.data`](#obj-spectargetconfigmapdata)
        * [`fn withFormat(format)`](#fn-spectargetconfigmapdatawithformat)
        * [`fn withKey(key)`](#fn-spectargetconfigmapdatawithkey)
        * [`fn withPassword(password)`](#fn-spectargetconfigmapdatawithpassword)
        * [`fn withProfile(profile)`](#fn-spectargetconfigmapdatawithprofile)
      * [`obj spec.target.configMap.metadata`](#obj-spectargetconfigmapmetadata)
        * [`fn withAnnotations(annotations)`](#fn-spectargetconfigmapmetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-spectargetconfigmapmetadatawithannotationsmixin)
        * [`fn withLabels(labels)`](#fn-spectargetconfigmapmetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-spectargetconfigmapmetadatawithlabelsmixin)
    * [`obj spec.target.namespaceSelector`](#obj-spectargetnamespaceselector)
      * [`fn withMatchExpressions(matchExpressions)`](#fn-spectargetnamespaceselectorwithmatchexpressions)
      * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-spectargetnamespaceselectorwithmatchexpressionsmixin)
      * [`fn withMatchLabels(matchLabels)`](#fn-spectargetnamespaceselectorwithmatchlabels)
      * [`fn withMatchLabelsMixin(matchLabels)`](#fn-spectargetnamespaceselectorwithmatchlabelsmixin)
      * [`obj spec.target.namespaceSelector.matchExpressions`](#obj-spectargetnamespaceselectormatchexpressions)
        * [`fn withKey(key)`](#fn-spectargetnamespaceselectormatchexpressionswithkey)
        * [`fn withOperator(operator)`](#fn-spectargetnamespaceselectormatchexpressionswithoperator)
        * [`fn withValues(values)`](#fn-spectargetnamespaceselectormatchexpressionswithvalues)
        * [`fn withValuesMixin(values)`](#fn-spectargetnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.target.secret`](#obj-spectargetsecret)
      * [`fn withData(data)`](#fn-spectargetsecretwithdata)
      * [`fn withDataMixin(data)`](#fn-spectargetsecretwithdatamixin)
      * [`obj spec.target.secret.data`](#obj-spectargetsecretdata)
        * [`fn withFormat(format)`](#fn-spectargetsecretdatawithformat)
        * [`fn withKey(key)`](#fn-spectargetsecretdatawithkey)
        * [`fn withPassword(password)`](#fn-spectargetsecretdatawithpassword)
        * [`fn withProfile(profile)`](#fn-spectargetsecretdatawithprofile)
      * [`obj spec.target.secret.metadata`](#obj-spectargetsecretmetadata)
        * [`fn withAnnotations(annotations)`](#fn-spectargetsecretmetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-spectargetsecretmetadatawithannotationsmixin)
        * [`fn withLabels(labels)`](#fn-spectargetsecretmetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-spectargetsecretmetadatawithlabelsmixin)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of ClusterBundle

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec

"Desired state of the Bundle resource."

### fn spec.withInLineCAs

```ts
withInLineCAs(inLineCAs)
```

"InLine is a simple string to append as the source data."

### fn spec.withIncludeDefaultCAs

```ts
withIncludeDefaultCAs(includeDefaultCAs)
```

"IncludeDefaultCAs, when true, requests the default CA bundle to be used as a source.\nDefault CAs are available if trust-manager was installed via Helm\nor was otherwise set up to include a package-injecting init container by using the\n\"--default-package-location\" flag when starting the trust-manager controller.\nIf default CAs were not configured at start-up, any request to use the default\nCAs will fail.\nThe version of the default CA package which is used for a Bundle is stored in the\ndefaultCAPackageVersion field of the Bundle's status field."

### fn spec.withSources

```ts
withSources(sources)
```

"Sources is a set of references to data whose data will sync to the target."

### fn spec.withSourcesMixin

```ts
withSourcesMixin(sources)
```

"Sources is a set of references to data whose data will sync to the target."

**Note:** This function appends passed data to existing values

## obj spec.sources

"Sources is a set of references to data whose data will sync to the target."

### fn spec.sources.withKey

```ts
withKey(key)
```

"Key(s) of the entry in the object's `data` field to be used.\nWildcards \"*\" in Key matches any sequence characters.\nA Key containing only \"*\" will match all data fields."

### fn spec.sources.withKind

```ts
withKind(kind)
```

"Kind is the kind of the source object."

### fn spec.sources.withName

```ts
withName(name)
```

"Name is the name of the source object in the trust Namespace.\nThis field must be left empty when `selector` is set"

## obj spec.sources.selector

"Selector is the label selector to use to fetch a list of objects. Must not be set\nwhen `Name` is set."

### fn spec.sources.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.sources.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.sources.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.sources.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.sources.selector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.sources.selector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.sources.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.sources.selector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.sources.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.target

"Target is the target location in all namespaces to sync source data to."

## obj spec.target.configMap

"ConfigMap is the target ConfigMap in Namespaces that all Bundle source data will be synced to."

### fn spec.target.configMap.withData

```ts
withData(data)
```

"Data is the specification of the object's `data` field."

### fn spec.target.configMap.withDataMixin

```ts
withDataMixin(data)
```

"Data is the specification of the object's `data` field."

**Note:** This function appends passed data to existing values

## obj spec.target.configMap.data

"Data is the specification of the object's `data` field."

### fn spec.target.configMap.data.withFormat

```ts
withFormat(format)
```

"Format defines the format of the target value.\nThe default format is PEM."

### fn spec.target.configMap.data.withKey

```ts
withKey(key)
```

"Key is the key of the entry in the object's `data` field to be used."

### fn spec.target.configMap.data.withPassword

```ts
withPassword(password)
```

"Password for PKCS12 trust store.\nBy default, no password is used (password-less PKCS#12)."

### fn spec.target.configMap.data.withProfile

```ts
withProfile(profile)
```

"Profile specifies the certificate encryption algorithms and the HMAC algorithm\nused to create the PKCS12 trust store.\n\nIf provided, allowed values are:\n`LegacyRC2`: Deprecated. Not supported by default in OpenSSL 3 or Java 20.\n`LegacyDES`: Less secure algorithm. Use this option for maximal compatibility.\n`Modern2023`: Secure algorithm. Use this option in case you have to always use secure algorithms (e.g. because of company policy).\n\nDefault value is `LegacyDES`."

## obj spec.target.configMap.metadata

"Metadata is an optional set of labels and annotations to be copied to the target."

### fn spec.target.configMap.metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is a key value map to be copied to the target."

### fn spec.target.configMap.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is a key value map to be copied to the target."

**Note:** This function appends passed data to existing values

### fn spec.target.configMap.metadata.withLabels

```ts
withLabels(labels)
```

"Labels is a key value map to be copied to the target."

### fn spec.target.configMap.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Labels is a key value map to be copied to the target."

**Note:** This function appends passed data to existing values

## obj spec.target.namespaceSelector

"NamespaceSelector specifies the namespaces where target resources will be synced."

### fn spec.target.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.target.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.target.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.target.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.target.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.target.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.target.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.target.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.target.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.target.secret

"Secret is the target Secret in Namespaces that all Bundle source data will be synced to.\nUsing Secrets as targets is only supported if enabled at trust-manager startup.\nBy default, trust-manager has no permissions for writing to secrets and can only read secrets in the trust namespace."

### fn spec.target.secret.withData

```ts
withData(data)
```

"Data is the specification of the object's `data` field."

### fn spec.target.secret.withDataMixin

```ts
withDataMixin(data)
```

"Data is the specification of the object's `data` field."

**Note:** This function appends passed data to existing values

## obj spec.target.secret.data

"Data is the specification of the object's `data` field."

### fn spec.target.secret.data.withFormat

```ts
withFormat(format)
```

"Format defines the format of the target value.\nThe default format is PEM."

### fn spec.target.secret.data.withKey

```ts
withKey(key)
```

"Key is the key of the entry in the object's `data` field to be used."

### fn spec.target.secret.data.withPassword

```ts
withPassword(password)
```

"Password for PKCS12 trust store.\nBy default, no password is used (password-less PKCS#12)."

### fn spec.target.secret.data.withProfile

```ts
withProfile(profile)
```

"Profile specifies the certificate encryption algorithms and the HMAC algorithm\nused to create the PKCS12 trust store.\n\nIf provided, allowed values are:\n`LegacyRC2`: Deprecated. Not supported by default in OpenSSL 3 or Java 20.\n`LegacyDES`: Less secure algorithm. Use this option for maximal compatibility.\n`Modern2023`: Secure algorithm. Use this option in case you have to always use secure algorithms (e.g. because of company policy).\n\nDefault value is `LegacyDES`."

## obj spec.target.secret.metadata

"Metadata is an optional set of labels and annotations to be copied to the target."

### fn spec.target.secret.metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is a key value map to be copied to the target."

### fn spec.target.secret.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is a key value map to be copied to the target."

**Note:** This function appends passed data to existing values

### fn spec.target.secret.metadata.withLabels

```ts
withLabels(labels)
```

"Labels is a key value map to be copied to the target."

### fn spec.target.secret.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Labels is a key value map to be copied to the target."

**Note:** This function appends passed data to existing values