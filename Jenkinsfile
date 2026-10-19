libraryPipeline(component:'voip-patrol',
                dockerfile: 'docker/Dockerfile.libon',
                releaseSlackChannel: '#team-voice',
                githubRepo: 'voip_patrol',
                customVersioning: true
) {
   sh 'git submodule update --init'
}
