<template>
  <div class="mt-5">
    <div class="pb-5 text-xl font-light font-inter text-slate-500/90">
      Projects
    </div>
    <div class="grid grid-cols-1 gap-4">
      <div class="flex flex-col">
        <div class="flex justify-between text-sm font-inter">
          <div class="flex flex-row items-baseline">
            <a
              class="font-medium border-b border-dashed cursor-pointer font-inter text-slate-800 border-slate-500/90"
              href="https://lairvox.vercel.app"
              target="_blank"
            >
              Lairvox: Hang-out Community App<span class="hidden sm:inline"
                >,</span
              >
            </a>
            <p class="hidden ml-1 text-sm font-normal text-slate-700 sm:inline">
              Indie Project
            </p>
          </div>
          <h4 class="text-xs font-medium font-inter text-slate-500/90">
            Sep 2026
          </h4>
        </div>
        <p class="mt-2 text-sm font-normal font-inter text-slate-700">
          A Discord Clone Application built with Next to learning how to create
          an end-to-end fullstack and real-time, all with servers, channels,
          video calls, audio calls, editing and deleting messages as well as
          member roles.
        </p>
        <p
          class="inline-block mt-2 text-sm font-medium font-inter text-slate-700"
        >
          Skills:
          <span class="inline-block font-normal text-slate-700">
            Next JS
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            Prisma
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            WebSocket
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            PostgreSQL
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            LiveKit
          </span>
        </p>
      </div>
      <div class="flex flex-col">
        <div class="flex justify-between text-sm font-inter">
          <div class="flex flex-row items-baseline">
            <a
              class="font-medium border-b border-dashed cursor-pointer font-inter text-slate-800 border-slate-500/90"
              href="https://rizzra.my.id"
              target="_blank"
            >
              Personal Homelab Server Infra<span class="hidden sm:inline"
                >,</span
              >
            </a>
            <p class="hidden ml-1 text-sm font-normal text-slate-700 sm:inline">
              Indie Project
            </p>
          </div>
          <h4 class="text-xs font-medium font-inter text-slate-500/90">
            Dec 2025
          </h4>
        </div>
        <p class="mt-2 text-sm font-normal font-inter text-slate-700">
          Designed and deployed a production-grade homelab on a repurposed
          ThinkPad X240, running Proxmox VE as the hypervisor managing multiple
          LXC containers. Used Portainer for container management and deployed a
          custom AI agent (Hermes) with browser access and Telegram bot
          integration. Configured Cloudflare Tunnel for secure public access
          over a custom domain without exposing the server IP, and implemented
          Tailscale VPN for remote management.
        </p>
        <p
          class="inline-block mt-2 text-sm font-medium font-inter text-slate-700"
        >
          Skills:
          <span class="inline-block font-normal text-slate-700">
            Proxmox VE
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            Portainer
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            Docker
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            CloudFlare Tunnel
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            TailScale
          </span>
        </p>
      </div>
      <div class="flex flex-col">
        <div class="flex justify-between text-sm font-inter">
          <div class="flex flex-row items-baseline">
            <a
              class="font-medium border-b border-dashed cursor-pointer font-inter text-slate-800 border-slate-500/90"
              href="https://github.com/rizzra26/kyora-store"
              target="_blank"
            >
              Kyora Store: All Your Gaming Needs<span class="hidden sm:inline"
                >,</span
              >
            </a>
            <p class="hidden ml-1 text-sm font-normal text-slate-700 sm:inline">
              Indie Project
            </p>
          </div>
          <h4 class="text-xs font-medium font-inter text-slate-500/90">
            Sep 2023
          </h4>
        </div>
        <p class="mt-2 text-sm font-normal font-inter text-slate-700">
          Kyora Store is a modern game top-up platform built with Next.js and
          structured using Atomic Design. Its UI components are developed and
          documented in Storybook, resulting in a consistent, reusable, and
          scalable front end for a fast and smooth top-up experience.
        </p>
        <p
          class="inline-block mt-2 text-sm font-medium font-inter text-slate-700"
        >
          Skills:
          <span class="inline-block font-normal text-slate-700">
            TypeScript
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            StoryBook
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            Next
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            Express
            <img src="~/assets/icons/dot.svg" class="inline w-5" />
            MongoDB
          </span>
        </p>
      </div>
    </div>
    <hr class="mt-5" />
  </div>
</template>
