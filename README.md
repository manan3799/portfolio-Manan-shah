import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Portfolio() {
  return (
    <main className="p-6 md:p-12 max-w-4xl mx-auto space-y-10">
      {/* Home Section */}
      <section className="text-center">
        <h1 className="text-4xl font-bold mb-2">Manan Shah</h1>
        <p className="text-lg text-gray-600">Business Professional | Product & Manufacturing Expert</p>
        <img
          src="https://via.placeholder.com/150"
          alt="Profile Placeholder"
          className="w-40 h-40 mx-auto rounded-full mt-4"
        />
      </section>

      {/* About Section */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">About Me</h2>
        <p>
          I am a dedicated professional with experience in business operations, product handling, and manufacturing
          processes. I bring efficiency, structure, and passion into every team I join.
        </p>
      </section>

      {/* Experience Section */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">Work Experience</h2>
        <Card>
          <CardContent className="p-4">
            <h3 className="text-lg font-bold">Various Roles in Manufacturing & Production</h3>
            <p className="text-sm text-gray-600">Poland | Ongoing</p>
            <p>
              Hands-on experience in production lines, process improvements, quality checks, and packaging. Collaborated
              across departments for efficient production delivery.
            </p>
          </CardContent>
        </Card>
      </section>

      {/* Education Section */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">Education</h2>
        <Card>
          <CardContent className="p-4">
            <h3 className="text-lg font-bold">Bachelor’s Degree</h3>
            <p className="text-sm text-gray-600">India</p>
            <p>Specialized in technical and operational studies with practical applications.</p>
          </CardContent>
        </Card>
      </section>

      {/* Skills Section */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">Skills</h2>
        <ul className="list-disc pl-6 space-y-1">
          <li>Manufacturing & Product Handling</li>
          <li>Team Collaboration</li>
          <li>Packaging and Quality Control</li>
          <li>Problem-Solving</li>
        </ul>
      </section>

      {/* Contact Section */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">Contact</h2>
        <p>Email: <a href="mailto:your-email@example.com" className="text-blue-600">your-email@example.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/manan-shah-4398a3137" className="text-blue-600">Manan Shah</a></p>
      </section>
    </main>
  );
}
