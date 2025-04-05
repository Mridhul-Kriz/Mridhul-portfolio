import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Github, Mail } from "lucide-react";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-100 p-6">
      <div className="max-w-5xl mx-auto">
        <header className="text-center mb-10">
          <h1 className="text-4xl font-bold mb-2">Mridhul Krishna KM</h1>
          <p className="text-lg text-gray-700">Business Development Executive & Marketing Specialist</p>
          <div className="flex justify-center gap-4 mt-4">
            <a href="mailto:mridhulkriz1999@gmail.com">
              <Button variant="outline"><Mail className="mr-2 h-4 w-4" />Email</Button>
            </a>
            <a href="https://github.com/your-github" target="_blank" rel="noopener noreferrer">
              <Button variant="outline"><Github className="mr-2 h-4 w-4" />GitHub</Button>
            </a>
          </div>
        </header>
        <section className="grid grid-cols-1 md:grid-cols-2 gap-6">
          <Card>
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold mb-2">About Me</h2>
              <p>
                Goal-oriented sales and marketing professional with a strong foundation in ERP, CRM, digital marketing, and customer relations. I bring hands-on experience in business development, lead generation, campaign management, and team coordination.
              </p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold mb-2">Skills</h2>
              <ul className="list-disc list-inside">
                <li>Marketing Strategies & Business Development</li>
                <li>CRM & ERP Tools (Odoo, etc.)</li>
                <li>Social Media Marketing & SEO</li>
                <li>Customer Relations & Team Management</li>
                <li>HR Operations & Project Coordination</li>
              </ul>
            </CardContent>
          </Card>
          <Card className="md:col-span-2">
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold mb-2">Professional Experience</h2>
              <ul className="list-disc list-inside">
                <li>Zinfog Codelabs – Business Development & Marketing Specialist</li>
                <li>M. Krishna Food Products – Operations Support</li>
                <li>WOBA E-Commerce Pvt Ltd – Customer Support & Marketing</li>
                <li>Hedge Equities – HR & Customer Engagement Intern</li>
                <li>Fortis Hospital – Sales & Marketing Intern</li>
              </ul>
            </CardContent>
          </Card>
          <Card className="md:col-span-2">
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold mb-2">Projects & Certifications</h2>
              <ul className="list-disc list-inside">
                <li>Service Quality Study at Hedge Equities</li>
                <li>BTL Awareness Program Effectiveness at Fortis Hospital</li>
                <li>Digital Marketing Course & Front Office Certification</li>
                <li>Advanced MS, Google, AI Tools Workshop</li>
              </ul>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold mb-2">Education</h2>
              <ul className="list-disc list-inside">
                <li>MBA – Marketing & HR, Chinmaya Institute of Technology (2024)</li>
                <li>B.Com – Finance, PVS Arts and Science College (2022)</li>
                <li>Diploma – Electrical, Govt ITI Malikkadavu (2019)</li>
              </ul>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold mb-2">Contact</h2>
              <p>
                Based in Calicut, Kerala, India<br />
                Email: mridhulkriz1999@gmail.com<br />
                Phone: +91 8138856631
              </p>
            </CardContent>
          </Card>
        </section>
      </div>
    </div>
  );
}
