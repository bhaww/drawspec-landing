# drawspec-landingexport default function LandingPage() {
  return (
    <div className="min-h-screen bg-white text-slate-800">
      <header className="p-6 shadow-md flex justify-between items-center">
        <h1 className="text-2xl font-bold">DrawSpec.AI</h1>
        <button className="bg-green-500 text-white px-4 py-2 rounded-xl shadow-md">Join Waitlist</button>
      </header>

      <main className="p-10 space-y-16">
        {/* Hero */}
        <section className="text-center space-y-4">
          <h2 className="text-4xl font-bold">From Drawings to Proposals in Minutes</h2>
          <p className="text-xl max-w-xl mx-auto">
            AI-powered automation for Security, AV, and Communications integrators.
            Instantly generate SOWs, BOMs, RFIs, and proposals from plans and specs.
          </p>
          <button className="bg-blue-600 text-white px-6 py-3 rounded-xl shadow-lg">Get Early Access</button>
        </section>

        {/* How It Works */}
        <section className="text-center">
          <h3 className="text-3xl font-semibold mb-6">How It Works</h3>
          <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div className="p-6 shadow rounded-2xl">
              <h4 className="text-xl font-bold mb-2">1. Upload Documents</h4>
              <p>Upload PDFs, specs, and construction drawings.</p>
            </div>
            <div className="p-6 shadow rounded-2xl">
              <h4 className="text-xl font-bold mb-2">2. AI Analysis</h4>
              <p>Our AI extracts scope, materials, and missing details.</p>
            </div>
            <div className="p-6 shadow rounded-2xl">
              <h4 className="text-xl font-bold mb-2">3. Export Proposals</h4>
              <p>Download ready-to-send SOWs, BOMs, RFIs, and quotes.</p>
            </div>
          </div>
        </section>

        {/* Testimonials */}
        <section className="text-center">
          <h3 className="text-2xl font-bold mb-4">What Our Industry Experts Say</h3>
          <p className="text-lg italic">"This is a game changer for preconstruction workflows."</p>
        </section>
      </main>

      <footer className="text-center py-6 bg-slate-100 text-slate-600">
        <p>&copy; {new Date().getFullYear()} DrawSpec.AI. All rights reserved.</p>
      </footer>
    </div>
  );
}
