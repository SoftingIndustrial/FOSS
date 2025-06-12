{
  "bomFormat" : "CycloneDX",
  "specVersion" : "1.5",
  "serialNumber" : "urn:uuid:0776dd6e-33e4-4425-a1e2-0521cadd53a1",
  "version" : 1,
  "metadata" : {
    "timestamp" : "2025-01-22T07:12:40Z",
    "tools" : [
      {
        "vendor" : "OWASP",
        "name" : "Dependency-Track",
        "version" : "4.11.5"
      }
    ],
    "component" : {
      "type" : "framework",
      "bom-ref" : "3192c0f6-0885-4627-b9ff-9f5351c16778",
      "name" : "OPC UA C++ SDK",
      "version" : "6.60"
    }
  },
  "components" : [
    {
      "type" : "library",
      "bom-ref" : "6873f35f-4969-4222-9f47-dc6afa339dce",
      "author" : "jsoncpp contributors",
      "group" : "Open Source Software",
      "name" : "jsoncpp",
      "version" : "1.9.5",
      "licenses" : [
        {
          "license" : {
            "id" : "MIT"
          }
        }
      ],
      "copyright" : "Baptiste Lepilleur <blep@users.sourceforge.net> Aaron Jacobs <aaronjjacobs@gmail.com> Aaron Jacobs <jacobsa@google.com> Adam Boseley <ABoseley@agjunction.com> Adam Boseley <adam.boseley@gmail.com> Aleksandr Derbenev <13alexac@gmail.com> Alexander Gazarov <DrMetallius@users.noreply.github.com> Alexander V. Brezgin <abrezgin@appliedtech.ru> Alexandr Brezgin <albrezgin@mail.ru> Alexey Kruchinin <alexey@mopals.com> Anton Indrawan <anton.indrawan@gmail.com> Baptiste Jonglez <git@bitsofnetworks.org> Baptiste Lepilleur <baptiste.lepilleur@gmail.com> Baruch Siach <baruch@tkos.co.il> Ben Boeckel <mathstuf@gmail.com> Benjamin Knecht <bknecht@logitech.com> Bernd Kuhls <bernd.kuhls@t-online.de> Billy Donahue <billydonahue@google.com> Braden McDorman <bmcdorman@gmail.com> Brandon Myers <bmyers1788@gmail.com> Brendan Drew <brendan.drew@daqri.com> chason <cxchao802@gmail.com> chenguoping <chenguopingdota@163.com> Chris Gilling <cgilling@iparadigms.com> Christopher Dawes <christopher.dawes.1981@googlemail.com> Christophe...",
      "purl" : "pkg:github/open-source-parsers/jsoncpp",
      "externalReferences" : [
        {
          "type" : "distribution",
          "url" : "https://github.com/open-source-parsers/jsoncpp"
        }
      ]
    },
    {
      "type" : "library",
      "bom-ref" : "f7dca7b4-7976-4edd-b705-13e682d73c47",
      "author" : "libxml contributors",
      "group" : "libxml2 contributors",
      "name" : "libxml2",
      "version" : "2.11.9",
      "description" : "https://gitlab.gnome.org/GNOME/libxml2/-/wikis/home",
      "licenses" : [
        {
          "license" : {
            "id" : "MIT"
          }
        }
      ],
      "copyright" : "Copyright (C) 1998-2012 Daniel Veillard. All Rights Reserved. Contributors:Bjorn Reese, William Brack, Igor Zlatkovic for the Windows port, Aleksey Sanin, Nick Wellnhofer",
      "externalReferences" : [
        {
          "type" : "distribution",
          "url" : "https://gitlab.gnome.org/GNOME/libxml2"
        }
      ]
    },
    {
      "type" : "framework",
      "bom-ref" : "ef551cae-e2b5-4e90-be7f-11711cd1bb83",
      "group" : "OPC Foundation",
      "name" : "OPC Ansi C Stack",
      "version" : "1.03.341",
      "licenses" : [
        {
          "license" : {
            "name" : "Reciprocal Community License 1.0"
          }
        }
      ],
      "copyright" : "Copyright (C) 2008,2009 OPC Foundation, Inc., All Rights Reserved."
    },
    {
      "type" : "framework",
      "bom-ref" : "002b7e78-cb2e-4fd6-ad05-b5f8f0bd21e2",
      "author" : "OpenSSL Corp.",
      "group" : "OpenSSL Corp.",
      "name" : "OpenSSL",
      "version" : "3.0.15",
      "licenses" : [
        {
          "license" : {
            "id" : "Apache-2.0"
          }
        }
      ],
      "copyright" : "Copyright (c) 1998-2024 The OpenSSL Project Authors Copyright (c) 1995-1998 Eric A. Young, Tim J. Hudson All rights reserved.",
      "purl" : "pkg:github/openssl/openssl",
      "externalReferences" : [
        {
          "type" : "distribution",
          "url" : "https://github.com/openssl/openssl"
        }
      ]
    },
    {
      "type" : "library",
      "bom-ref" : "9d431353-882d-4b79-9dd5-2fba2349187a",
      "author" : "eclipse-paho",
      "group" : "eclipe-paho",
      "name" : "paho.mqtt.c",
      "version" : "1.4",
      "licenses" : [
        {
          "license" : {
            "id" : "EPL-2.0"
          }
        }
      ],
      "copyright" : "Copyright © Eclipse Foundation",
      "purl" : "pkg:github/eclipse-paho/paho.mqtt.cpp",
      "externalReferences" : [
        {
          "type" : "distribution",
          "url" : "https://github.com/eclipse-paho/paho.mqtt.c"
        }
      ]
    }
  ],
  "dependencies" : [
    {
      "ref" : "3192c0f6-0885-4627-b9ff-9f5351c16778",
      "dependsOn" : [ ]
    },
    {
      "ref" : "6873f35f-4969-4222-9f47-dc6afa339dce",
      "dependsOn" : [ ]
    },
    {
      "ref" : "f7dca7b4-7976-4edd-b705-13e682d73c47",
      "dependsOn" : [ ]
    },
    {
      "ref" : "ef551cae-e2b5-4e90-be7f-11711cd1bb83",
      "dependsOn" : [ ]
    },
    {
      "ref" : "002b7e78-cb2e-4fd6-ad05-b5f8f0bd21e2",
      "dependsOn" : [ ]
    },
    {
      "ref" : "9d431353-882d-4b79-9dd5-2fba2349187a",
      "dependsOn" : [ ]
    }
  ]
}