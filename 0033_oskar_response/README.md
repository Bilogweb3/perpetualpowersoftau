See `oskarth_attestation.md` in this directory for Oskar Thorén's signed attestation.

Hash of the [`challenge`](https://ppot.blob.core.windows.net/public/challenge_0033) file for verification:

```
    daa7c3b5 570966a7 1180db03 c0d76def
    00395cb6 95c90736 d9c7c240 8bc76b33
    bda8ee88 f495b77d 1927a94d 37e67726
    89e7cb8a 1796c863 5c1153fc 6d6b6f42
```

`response` was based on the hash:

```
    daa7c3b5 570966a7 1180db03 c0d76def
    00395cb6 95c90736 d9c7c240 8bc76b33
    bda8ee88 f495b77d 1927a94d 37e67726
    89e7cb8a 1796c863 5c1153fc 6d6b6f42
```

Hash of the [`response`](https://ppot.blob.core.windows.net/public/response_0033_oskar) file for verification:

```
    cd052845 3b0cca20 3956bb23 333473be
    c12c14a8 cb7102ef e437f8d4 07f23463
    6e77e1e7 d44c4176 608ad290 a2d83f48
    78ccb222 c1e7c60b f5a8ab38 542ce634
```

Blake2b hash of the `new_challenge` file for participant #34:

```
    5e4226c9 b037c98d 6207ee8f 8056c651
    d3686215 74dcf7ac 67cf6908 43dc8072
    4f8c8f62 7d3a0e33 4d82934e 24d17e89
    300c767f 91c03ca2 13742e0d 25c6ac09
```

The above `new_challenge` file: https://ppot.blob.core.windows.net/public/challenge_0034

Oskar Thorén's attestation:
***

## Attestation to response 0033

*Date*: Fri Apr 24 2020 - Sat Apr 25 2020
*Name*: Oskar Thoren (oskarth)
*Location*: Taipei, Taiwan
*Device*: Personal Lenovo Carbon X1 with Fedora 29
*Commit Hash*: bf852c168676a7afc5dd17b47ff9b8f394aeab8a
*Challenge URL*: https://ppothk.blob.core.windows.net/public/challenge\_0033

*Challenge*:

```
`challenge` file contains decompressed points and has a hash:
	daa7c3b5 570966a7 1180db03 c0d76def
	00395cb6 95c90736 d9c7c240 8bc76b33
	bda8ee88 f495b77d 1927a94d 37e67726
	89e7cb8a 1796c863 5c1153fc 6d6b6f42
`challenge` file claims (!!! Must not be blindly trusted) that it was based on the original contribution with a hash:
	527fe68c 16219d86 018de364 fc5701b1
	44fc5b68 eb063c9a 8c4e8405 b35f4561
	b55363df 6d9adf82 8792c7b1 92a595b4
	4aadbea7 cdef918a 11bfe65a 89c9e4a3
Computing and writing your contribution, this could take a while...
```

*Response*:

```
The BLAKE2b hash of `./response` is:
	cd052845 3b0cca20 3956bb23 333473be
	c12c14a8 cb7102ef e437f8d4 07f23463
	6e77e1e7 d44c4176 608ad290 a2d83f48
	78ccb222 c1e7c60b f5a8ab38 542ce634
```

*Time taken*:

Not recorded.

*Entropy Sources*:

- ~1mb of live Wide-band WebSDR recording converted to base64 (using http://websdr.ewi.utwente.nl:8901/).

- Interspersed with random key smashing.

*Side channel defenses*:

No specific precautions taken, but performed in isolated home office.

*Postprocessing*:

Rebooting the machine.
