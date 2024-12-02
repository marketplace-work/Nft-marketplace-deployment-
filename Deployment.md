const script = loadCompiledScript('plooty-marketplace');
await deployScript({ provider: blockfrost, script });
