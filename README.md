export default function GazaKitchenWebsite() { return ( <div className="min-h-screen bg-black text-white font-sans"> {/* Hero Section */} <section className="text-center py-16 px-6 bg-gradient-to-b from-orange-600 to-black"> <h1 className="text-5xl font-bold mb-4">Gaza Kitchen</h1> <p className="text-lg text-gray-200 max-w-2xl mx-auto"> Delicious local food in Freedom Park 🍗🔥 </p> <button className="mt-6 bg-white text-black px-6 py-3 rounded-2xl font-semibold shadow-lg hover:scale-105 transition"> Order on WhatsApp </button> </section>

{/* About */}
  <section className="py-12 px-6 max-w-5xl mx-auto">
    <h2 className="text-3xl font-bold mb-4 text-orange-400">About Us</h2>
    <p className="text-gray-300 leading-7">
      Gaza Kitchen helps people enjoy tasty meals at affordable prices. 
      We serve fresh food daily and focus on quality, fast service, and customer satisfaction.
    </p>
  </section>

  {/* Menu */}
  <section className="py-12 px-6 bg-zinc-900">
    <h2 className="text-3xl font-bold text-center mb-10 text-orange-400">Popular Meals</h2>

    <div className="grid md:grid-cols-3 gap-6 max-w-6xl mx-auto">
      <div className="bg-black rounded-2xl p-6 shadow-lg border border-zinc-800">
        <h3 className="text-2xl font-semibold mb-2">Quarter Chicken</h3>
        <p className="text-gray-400 mb-4">Served with chips and salad.</p>
        <p className="text-orange-400 font-bold text-xl">R45</p>
      </div>

      <div className="bg-black rounded-2xl p-6 shadow-lg border border-zinc-800">
        <h3 className="text-2xl font-semibold mb-2">Burger Special</h3>
        <p className="text-gray-400 mb-4">Beef burger with fries and drink.</p>
        <p className="text-orange-400 font-bold text-xl">R60</p>
      </div>

      <div className="bg-black rounded-2xl p-6 shadow-lg border border-zinc-800">
        <h3 className="text-2xl font-semibold mb-2">Full Kota</h3>
        <p className="text-gray-400 mb-4">Loaded kota with sauces and chips.</p>
        <p className="text-orange-400 font-bold text-xl">R50</p>
      </div>
    </div>
  </section>

  {/* Contact */}
  <section className="py-12 px-6 max-w-5xl mx-auto text-center">
    <h2 className="text-3xl font-bold mb-4 text-orange-400">Contact</h2>
    <p className="text-gray-300 mb-3">📍 Freedom Park, Pretoria</p>
    <p className="text-gray-300 mb-6">📞 +27 XX XXX XXXX</p>

    <button className="bg-orange-500 hover:bg-orange-600 px-8 py-3 rounded-2xl font-bold shadow-lg transition">
      Contact on WhatsApp
    </button>
  </section>

  {/* Footer */}
  <footer className="text-center py-6 border-t border-zinc-800 text-gray-500">
    © 2026 Gaza Kitchen. Built with passion 🔥
  </footer>
</div>

) }
