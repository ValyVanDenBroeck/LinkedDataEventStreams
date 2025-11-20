# The Linked Data Event Streams specification <img align="right" src="/semic-icon-small.png" />

A Linked Data Event Stream is a collection of immutable objects (such as version objects, sensor observations or archived representation). Each object is described in RDF.

The objective of a Linked Data Event Stream is to allow consumers to replicate all of its items and to stay in sync when items are added.

The HTML specification can be accessed from [here](https://w3id.org/ldes/specification).

An example JSON-LD context can be accessed from [here](https://w3id.org/ldes/context). It includes the JSON labels we recommend to use in JSON-LD documents. This document may however change over time and does not come with any waranties cfr. uptime. When building for a production environment, do thus not use this URL as an external context.

This specification uses [TREE](https://w3id.org/tree/specification) for its collection and fragmentation features, which in its turn is compatible to other specifications such as Activity Streams, DCAT-AP, LDP or Shape Trees.

If you are new to the concept of Linked Data Event Stream or Linked Data, [this short training](https://academy.europa.eu/courses/publishing-data-with-linked-data-event-streams-why-and-how) introduces the main concepts.

<details>      
  <summary><b>Working Sessions</b></summary>
  </br>
<table>  
    <tbody>  
        <tr>  
            <td>  
                <p><strong>Title</strong></p>  
            </td>  
            <td>  
                <p><strong>Date</strong></p>  
            </td>  
        </tr> 
        <tr>  
            <td>  
                <p><u><a href="https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/event/ldes-working-group-onboarding-session">Onboarding Session</a></u></p>  
            </td>  
            <td>  
                <p>30/04/2025</p>  
            </td> 
        </tr>
        <tr>  
              <td>  
                  <p><u><a href="https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/event/ldes-working-group-1">Working Session 1</a></u></p>  
              </td>  
              <td>
                <p>07/05/2025</p>
              </td> 
        </tr> 
        <tr>  
            <td>  
                <p><u><a href="https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/event/ldes-working-group-2">Working Session 2</a></u></p>  
            </td>  
            <td>  
                <p>12/06/2025</p>  
            </td>   
          </tr> 
       <tr>  
            <td>  
                <p><u><a href="https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/event/ldes-working-group-3">Working Session 3</a></u></p>  
            </td>  
            <td>  
                <p>03/07/2025</p>  
            </td>   
          </tr>
       <tr>  
            <td>  
                <p><u><a href="https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/event/ldes-working-group-4">Working Session 4</a></u></p>  
            </td>  
            <td>  
                <p>11/09/2025</p>  
            </td>   
          </tr>
       <tr>  
            <td>  
                <p><u><a href="https://interoperable-europe.ec.europa.eu/collection/semic-support-centre/event/ldes-working-group-5">Working Session 5</a></u></p>  
            </td>  
            <td>  
                <p>25/09/2025</p>  
            </td>   
          </tr>
    </tbody>  
</table>   
</details>

<details>      
  <summary><b>Pilots</b></summary>
  </br>
<table>  
    <tbody>  
        <tr>  
            <td>  
                <p><strong>Name</strong></p>  
            </td>  
            <td>  
                <p><strong>Description</strong></p>  
            </td>  
            <td>  
                <p><strong>Status</strong></p>  
            </td>  
        </tr> 
        <tr>  
            <td>  
                <p><u><a href="https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/era-dcat-ap-feed">European Railway Agency</a></u></p>  
            </td>  
            <td>  
                <p>This proof-of-concept RDF-Connect pipeline is designed to generate a DCAT-AP feed from the EU Railway Agency's DCAT-AP metadata. 
The GitLab CI/CD pipeline retrieves DCAT-AP data from ERA servers every six hours, detects changes, and updates the LDES feed. This feed is accessible via GitLab Pages, providing up-to-date metadata distribution for the EU Railway domain.</p>  
            </td>  
            <td>  
                <p>Ongoing</p>  
            </td>  
        </tr>
        <tr>  
              <td>  
                  <p><u><a href="https://semiceu.github.io/LDES-implementation-reports/cultural-heritage-feeds/">Cultural Heritage Data Space</a></u></p>  
              </td>  
              <td>With cultural heritage event streams we propose that cultural heritage data providers publish an event source API that can help to replicate their source datasets about cultural heritage entities towards a harvester, and keep the data on the harvester side in-sync in the way that is intended by the provider. </td>  
              <td>  
                  <p>Completed in 2025</p>  
              </td>  
        </tr> 
        <tr>  
            <td>  
                <p><u><a href="https://data.rijksmuseum.nl/docs/ldes/">Rijksmuseum</a></u></p>  
            </td>  
            <td>  
                <p>Rijksmuseum offers an LDES API to share metadata about its collection objects and bibliographic resources. Each LDES page is formatted as JSON-LD and contains complete metadata of one or more resources and/or information to navigate the available metadata.</p>  
            </td>  
            <td>  
                <p>Completed in ???</p>  
            </td> 
          </tr>  
    </tbody>  
</table>   
</details>

## Build the spec

Install [bikeshed](https://tabatkins.github.io/bikeshed/) and then run `bikeshed watch eventstreams.bs`

## Contributions

 * [Create an issue](https://github.com/SEMICeu/LinkedDataEventStreams/issues/new/choose) first
 * Gather community input, either by asking input from the editors via email, either via the github issue, either via the [Matrix chat channel](https://matrix.to/#/#ldes:chat.semantic.works)
 * Open a pull request extending the specification

## Changelog

 * 2023-04-28 - Point in Time retention policy has been added
 * 2022-07-01 - tree:ViewDescription was introduced as a concept

## Acknowledgements

This work is financed by the [Interoperable Europe (SEMIC) programme](https://joinup.ec.europa.eu/interoperable-europe) of the European Commission
 
