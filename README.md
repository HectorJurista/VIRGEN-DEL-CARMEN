# VIRGEN-DEL-CARMEN
TITLE
import React, { useState } from 'react';

export default function VirgenDelCarmen() {
  const [isModalOpen, setIsModalOpen] = useState(false);

  return (
    <div className="bg-gray-100 min-h-screen flex flex-col items-center justify-center p-8">
      <h1 className="text-3xl font-bold text-indigo-700 mb-8">Virgen del Carmen</h1>

      <div className="bg-white rounded-lg shadow-md p-6 w-96">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6d/Nuestra_Se%C3%B1ora_del_Carmen_de_la_Sierra_de_Granada.jpg/800px-Nuestra_Se%C3%B1ora_del_Carmen_de_la_Sierra_de_Granada.jpg" alt="Virgen del Carmen" className="w-full rounded-lg mb-4" /> {/* Replace with actual image */}
        <p className="text-gray-700 mb-4">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nec enim velit.  Donec ut est in elit bibendum ultricies.
        </p>
        <button
          onClick={() => setIsModalOpen(true)}
          className="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-2 px-4 rounded-lg"
        >
          Learn More
        </button>
      </div>
