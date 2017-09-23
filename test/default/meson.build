test_deps = declare_dependency(
	include_directories : [include_directories('../quirks')],
	compile_args : ['-DTEST_SRCDIR="@0@"'.format(meson.current_source_dir())],
	dependencies : [libsodium_dep],
)

'''
test(
	'aead_aes256gcm',
	executable('aead_aes256gcm', 'aead_aes256gcm.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'aead'
)

test(
	'aead_chacha20poly1305',
	executable('aead_chacha20poly1305', 'aead_chacha20poly1305.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'aead'
)

test(
	'aead_xchacha20poly1305',
	executable('aead_xchacha20poly1305', 'aead_xchacha20poly1305.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'aead'
)'''

test(
	'auth',
	executable('auth', 'auth.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'auth'
)

test(
	'auth2',
	executable('auth2', 'auth2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'auth'
)

test(
	'auth3',
	executable('auth3', 'auth3.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'auth'
)

test(
	'auth5',
	executable('auth5', 'auth5.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'auth'
)

test(
	'auth6',
	executable('auth6', 'auth6.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'auth'
)

test(
	'auth7',
	executable('auth7', 'auth7.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'auth'
)

test(
	'box',
	executable('box', 'box.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box2',
	executable('box2', 'box2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box7',
	executable('box7', 'box7.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box8',
	executable('box8', 'box8.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box_easy',
	executable('box_easy', 'box_easy.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box_easy2',
	executable('box_easy2', 'box_easy2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box_seal',
	executable('box_seal', 'box_seal.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

test(
	'box_seed',
	executable('box_seed', 'box_seed.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'box'
)

'''test(
	'chacha20',
	executable('chacha20', 'chacha20.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'chacha20'
)'''

test(
	'codecs',
	executable('codecs', 'codecs.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'codecs'
)

test(
	'core1',
	executable('core1', 'core1.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'core'
)

test(
	'core2',
	executable('core2', 'core2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'core'
)

test(
	'core3',
	executable('core3', 'core3.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'core'
)

test(
	'core4',
	executable('core4', 'core4.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'core'
)

test(
	'core5',
	executable('core5', 'core5.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'core'
)

test(
	'core6',
	executable('core6', 'core6.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'core'
)

test(
	'ed25519_convert',
	executable('ed25519_convert', 'ed25519_convert.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'ed25519_convert'
)

test(
	'generichash',
	executable('generichash', 'generichash.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'generichash'
)

test(
	'generichash2',
	executable('generichash2', 'generichash2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'generichash'
)

test(
	'generichash3',
	executable('generichash3', 'generichash3.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'generichash'
)

test(
	'hash',
	executable('hash', 'hash.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'hash'
)

test(
	'hash3',
	executable('hash3', 'hash3.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'hash'
)

test(
	'kdf',
	executable('kdf', 'kdf.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'kdf'
)

'''test(
	'keygen',
	executable('keygen', 'keygen.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'keygen'
)'''

test(
	'kx',
	executable('kx', 'kx.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'kx'
)

test(
	'metamorphic',
	executable('metamorphic', 'metamorphic.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'metamorphic'
)

test(
	'misuse',
	executable('misuse', 'misuse.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'misuse'
)

test(
	'onetimeauth',
	executable('onetimeauth', 'onetimeauth.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'onetimeauth'
)

test(
	'onetimeauth2',
	executable('onetimeauth2', 'onetimeauth2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'onetimeauth'
)

test(
	'onetimeauth7',
	executable('onetimeauth7', 'onetimeauth7.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'onetimeauth'
)

'''test(
	'pwhash',
	executable('pwhash', 'pwhash.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'pwhash'
)

test(
	'pwhash_argon2id',
	executable('pwhash_argon2id', 'pwhash_argon2id.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'pwhash'
)'''

if not get_option('minimal')
	'''test(
		'pwhash_scrypt',
		executable('pwhash_scrypt', 'pwhash_scrypt.c', build_by_default : false, dependencies : [test_deps]),
		suite : 'pwhash'
	)

	test(
		'pwhash_scrypt_ll',
		executable('pwhash_scrypt_ll', 'pwhash_scrypt_ll.c', build_by_default : false, dependencies : [test_deps]),
		suite : 'pwhash'
	)'''
endif

test(
	'randombytes',
	executable('randombytes', 'randombytes.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'randombytes'
)

test(
	'scalarmult',
	executable('scalarmult', 'scalarmult.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'scalarmult'
)

test(
	'scalarmult2',
	executable('scalarmult2', 'scalarmult2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'scalarmult'
)

test(
	'scalarmult5',
	executable('scalarmult5', 'scalarmult5.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'scalarmult'
)

test(
	'scalarmult6',
	executable('scalarmult6', 'scalarmult6.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'scalarmult'
)

test(
	'scalarmult7',
	executable('scalarmult7', 'scalarmult7.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'scalarmult'
)

test(
	'secretbox',
	executable('secretbox', 'secretbox.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretbox'
)

test(
	'secretbox2',
	executable('secretbox2', 'secretbox2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretbox'
)

test(
	'secretbox7',
	executable('secretbox7', 'secretbox7.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretbox'
)

test(
	'secretbox8',
	executable('secretbox8', 'secretbox8.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretbox'
)

test(
	'secretbox_easy',
	executable('secretbox_easy', 'secretbox_easy.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretbox'
)

test(
	'secretbox_easy2',
	executable('secretbox_easy2', 'secretbox_easy2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretbox'
)

test(
	'secretstream',
	executable('secretstream', 'secretstream.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'secretstream'
)

test(
	'shorthash',
	executable('shorthash', 'shorthash.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'shorthash'
)

test(
	'sign',
	executable('sign', 'sign.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'sign'
)

if not get_option('minimal')
	test(
		'siphashx24',
		executable('siphashx24', 'siphashx24.c', build_by_default : false, dependencies : [test_deps]),
		suite : 'siphashx24'
	)
endif

test(
	'sodium_core',
	executable('sodium_core', 'sodium_core.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'sodium'
)

test(
	'sodium_version',
	executable('sodium_version', 'sodium_version.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'sodium'
)

test(
	'sodium_utils',
	executable('sodium_utils', 'sodium_utils.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'sodium_utils'
)

if not is_emscripten and not is_nativeclient
	test(
		'sodium_utils2',
		executable('sodium_utils2', 'sodium_utils2.c', build_by_default : false, dependencies : [test_deps]),
		suite : 'sodium_utils'
	)

	test(
		'sodium_utils3',
		executable('sodium_utils3', 'sodium_utils3.c', build_by_default : false, dependencies : [test_deps]),
		suite : 'sodium_utils'
	)
endif

test(
	'stream',
	executable('stream', 'stream.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'stream'
)

test(
	'stream2',
	executable('stream2', 'stream2.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'stream'
)

test(
	'stream3',
	executable('stream3', 'stream3.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'stream'
)

test(
	'stream4',
	executable('stream4', 'stream4.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'stream'
)

test(
	'verify1',
	executable('verify1', 'verify1.c', build_by_default : false, dependencies : [test_deps]),
	suite : 'verify'
)

if not get_option('minimal')
	'''test(
		'xchacha20',
		executable('xchacha20', 'xchacha20.c', build_by_default : false, dependencies : [test_deps]),
		suite : 'xchacha20'
	)'''
endif
