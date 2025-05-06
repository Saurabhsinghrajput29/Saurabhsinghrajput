<main className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
    <Card className="bg-zinc-900 rounded-2xl shadow-md">
      <CardContent className="p-6">
        <h2 className="text-2xl font-semibold mb-2">About Me</h2>
        <p className="text-gray-400">
          I'm a passionate developer with a love for sleek design and functional code. I blend creativity and logic to craft beautiful digital experiences.
        </p>
      </CardContent>
    </Card>

    <Card className="bg-zinc-900 rounded-2xl shadow-md">
      <CardContent className="p-6">
        <h2 className="text-2xl font-semibold mb-2">Projects</h2>
        <ul className="text-gray-400 list-disc list-inside">
          <li>Project One – A minimalist portfolio site</li>
          <li>Project Two – Dark-themed blog platform</li>
          <li>Project Three – Custom CMS for creatives</li>
        </ul>
      </CardContent>
    </Card>

    <Card className="bg-zinc-900 rounded-2xl shadow-md">
      <CardContent className="p-6">
        <h2 className="text-2xl font-semibold mb-2">Contact</h2>
        <p className="text-gray-400 mb-4">
          Let's collaborate or just say hi!
        </p>
        <Button className="bg-white text-black font-medium hover:bg-gray-200">
          Email Me
        </Button>
      </CardContent>
    </Card>
  </main>

  <footer className="text-center mt-10 text-gray-500 text-sm">
    © {new Date().getFullYear()} Your Name. All rights reserved.
  </footer>
</div>

); }

