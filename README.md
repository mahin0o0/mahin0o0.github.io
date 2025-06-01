// Mahin Rahman's Personal Website (One-page Glass Style)

import React from "react";
import { FaFacebook, FaInstagram, FaTiktok, FaThreads, FaYoutube, FaWhatsapp, FaEnvelope } from "react-icons/fa6";
import { Card } from "@/components/ui/card";

export default function MahinWebsite() {
  return (
    <main className="min-h-screen bg-gradient-to-br from-[#e0f7fa] to-[#ffffff] p-4 text-gray-800 font-sans">
      {/* Header */}
      <header className="text-center mb-10">
        <h1 className="text-4xl font-bold tracking-widest text-blue-900 drop-shadow-md">INFORMATION WEBSITE</h1>
        <h2 className="text-5xl mt-4 font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-blue-500 to-cyan-600">Mahin Rahman</h2>
      </header>

      {/* Content Section */}
      <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
        {/* Left Side - Social Info */}
        <div className="space-y-4">
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaEnvelope className="text-xl text-blue-700" />
            <a href="mailto:mahinrahman13140@gmail.com" className="text-lg font-medium">Email</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaWhatsapp className="text-xl text-green-600" />
            <a href="https://wa.me/8801770756964" className="text-lg font-medium">WhatsApp</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaFacebook className="text-xl text-blue-800" />
            <a href="https://www.facebook.com/mahin.rahman.757258" className="text-lg font-medium">Facebook Profile</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaFacebook className="text-xl text-blue-800" />
            <a href="https://www.facebook.com/mahin0o" className="text-lg font-medium">Facebook Page</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaInstagram className="text-xl text-pink-500" />
            <a href="https://www.instagram.com/mahin0o0" className="text-lg font-medium">Instagram</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaTiktok className="text-xl text-black" />
            <a href="https://www.tiktok.com/@mahin0o0" className="text-lg font-medium">TikTok</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaThreads className="text-xl text-black" />
            <a href="https://www.threads.net/@mahin0o0" className="text-lg font-medium">Threads</a>
          </Card>
          <Card className="flex items-center gap-4 p-4 bg-white/50 backdrop-blur-md shadow-xl rounded-2xl">
            <FaYoutube className="text-xl text-red-600" />
            <a href="https://www.youtube.com/@Mahin.0o0" className="text-lg font-medium">YouTube</a>
          </Card>
        </div>

        {/* Right Side - Bio */}
        <div className="bg-white/60 backdrop-blur-md p-6 shadow-xl rounded-2xl text-lg leading-relaxed">
          <h3 className="text-2xl font-semibold mb-4">About Mahin Rahman</h3>
          <p>Hello! I'm <strong>Mahin Rahman</strong>, a passionate and dedicated student of <strong>Computer Science and Technology</strong> at <strong>Headway Engineering Institute, Sylhet</strong>. With a strong enthusiasm for learning and creating, I thrive in the world of technology, innovation, and digital expression.</p>
          <br />
          <p>I believe in turning ideas into impact—whether it's through building modern digital identities, exploring social platforms, or mastering the skills that drive the future. My journey is guided by curiosity, purpose, and the ambition to constantly improve myself and contribute to the digital age.</p>
          <br />
          <p>I am active across various social media platforms, where I share my thoughts, creations, and connect with the world. My website serves as the central hub for all my personal and social presence—styled with simplicity, clarity, and a touch of elegance.</p>
          <br />
          <blockquote className="italic text-blue-600 mt-4 border-l-4 border-blue-400 pl-4">“The future belongs to those who build it.”</blockquote>
        </div>
      </div>
    </main>
  );
}
