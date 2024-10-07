# @datastax/astra-db-ts@1.5.0

## Overview

This isn't the bug free source code for @datastax/astra-db-ts, but the distribution which has already fixed.

## Fixed Errors

The following errors are fixed:

* node_modules/@datastax/astra-db-ts/dist/astra-db-ts.d.ts:3181:49 - error TS2552: Cannot find name 'HTTPClientOptions'. Did you mean 'FetchHttpClientOptions'?

3181 declare interface DataAPIHttpClientOpts extends HttpClientOptions {

* node_modules/@datastax/astra-db-ts/dist/astra-db-ts.d.ts:3182:15 - error TS2304: Cannot find name 'KeyspaceRef'.

3182 keyspace: KeyspaceRef;

* node_modules/@datastax/astra-db-ts/dist/astra-db-ts.d.ts:5198:30 - error TS2304: Cannot find name 'DataAPIRequestInfo'.

5198 emitCommandStarted(info: DataAPIRequestInfo): void;

* node_modules/@datastax/astra-db-ts/dist/astra-db-ts.d.ts:5199:29 - error TS2304: Cannot find name 'DataAPIRequestInfo'.

5199 emitCommandFailed(info: DataAPIRequetInfo, error: Error, started: number): void;

* node_modules/@datastax/astra-db-ts/dist/astra-db-ts.d.ts:5200:29 - error TS2304: Cannot find name 'DataAPIRequestInfo'.

5200 emitCommandSucceeded(info: DataAPIRequestInfo, resp: RawDataAPIResponse, warnings: string[], started: number): void;

* node_modules/@datastax/astra-db-ts/dist/astra-db-ts.d.ts:5205:49 - error TS2304: Cannot find name 'WithNullableKeySpace'.

5205 declare interface ExecuteCommandOptions extends WitNullableKeyspace {

## USAGE

Replace your @datastax/astra-db-ts installed via npm with this distribution.