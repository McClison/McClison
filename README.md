import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";

export default function Home() {
  return (
    <div className="p-4 max-w-5xl mx-auto space-y-8">
      <header className="text-center space-y-2">
        <h1 className="text-4xl font-bold">Integrare inteligentă în Germania</h1>
        <p className="text-lg text-gray-600">
          Consultanță, ghiduri și servicii pentru un nou început fără stres.
        </p>
        <Button className="mt-2">Vezi cum te pot ajuta</Button>
      </header>

      <section className="grid grid-cols-1 md:grid-cols-2 gap-6">
        <Card>
          <CardContent className="space-y-2 p-4">
            <h2 className="text-xl font-semibold">💶 Finanțe</h2>
            <p>
              Deschidere de cont, alegerea celei mai bune asigurări, administrare eficientă a bugetului.
            </p>
            <Button variant="outline">Află mai multe</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2 p-4">
            <h2 className="text-xl font-semibold">📝 Traduceri</h2>
            <p>
              Traduceri autorizate pentru documente oficiale. Colaborăm cu profesioniști în domeniu.
            </p>
            <Button variant="outline">Vezi oferte</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2 p-4">
            <h2 className="text-xl font-semibold">🧾 Taxe</h2>
            <p>
              Declarații fiscale, clase de impozitare, optimizare fiscală pentru cetățeni străini.
            </p>
            <Button variant="outline">Detalii utile</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2 p-4">
            <h2 className="text-xl font-semibold">💳 Credite</h2>
            <p>
              Ghiduri și suport pentru credite personale, rate, istoricul SCHUFA și alternative sigure.
            </p>
            <Button variant="outline">Învață cum</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2 p-4">
            <h2 className="text-xl font-semibold">👷 Angajare</h2>
            <p>
              Găsirea unui job, redactarea CV-ului, scrisori de intenție și colaborare cu firme de recrutare.
            </p>
            <Button variant="outline">Aplică eficient</Button>
          </CardContent>
        </Card>
      </section>

      <section className="bg-gray-100 rounded-2xl p-6">
        <h2 className="text-2xl font-bold mb-4">📞 Contactează-mă</h2>
        <p className="mb-2">Ai nevoie de ajutor personalizat? Scrie-mi direct.</p>
        <form className="space-y-4 max-w-xl">
          <Input placeholder="Numele tău" />
          <Input placeholder="Email" type="email" />
          <Input placeholder="Ce problemă ai?" />
          <Button type="submit">Trimite</Button>
        </form>
      </section>
    </div>
  );
}
