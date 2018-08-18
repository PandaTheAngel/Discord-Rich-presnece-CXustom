# Discord-Rich-presnece-CXustom

    static void UpdatePresence()
    {
        DiscordRichPresence discordPresence;
        memset(&discordPresence, 0, sizeof(discordPresence));
        discordPresence.state = "Studying";
        discordPresence.details = "Listening To Music";
        discordPresence.startTimestamp = 1507665886;
        discordPresence.endTimestamp = 1507665886;
        discordPresence.largeImageKey = "studyingasset2";
        discordPresence.largeImageText = "Studying";
        discordPresence.smallImageKey = "spotifylogo5x112";
        discordPresence.smallImageText = "Spotify";
        discordPresence.partyId = "ae488379-351d-4a4f-ad32-2b9b01c91657";
        discordPresence.partySize = 1;
        discordPresence.partyMax = 1;
        discordPresence.spectateSecret = "MTIzNDV8MTIzNDV8MTMyNDU0";
        discordPresence.joinSecret = "MTI4NzM0OjFpMmhuZToxMjMxMjM= ";
        Discord_UpdatePresence(&discordPresence);
    }
