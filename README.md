





اريد تصميم موقع خاص فيني اي ان يمكنني صنع مواقع اكترونيه بشكل احترافي 





Nachgedacht für 8s

ان تكون لغه بلالماني

نعم، تم تحويل تصميم الموقع بالكامل إلى اللغة الألمانية.

إذا أردت، أستطيع الآن أيضًا تعديل التصميم ليكون:

باسمك الشخصي

بألوان تختارها

مع أقسام خاصة بخدماتك

ومناسب لعرض أعمالك كصانع مواقع محترف

اكتب فقط:
اسمك + نوع الستايل الذي تريده
مثال:
“Max Web Studio, modern und luxuriös”


سوي موقع الان بلغه العربي وفي لاخر نضيف لغه المانيه ولاجنبي

تم. صممت الموقع الآن باللغة العربية، وأضفت فيه شكلًا يوضح أنه جاهز لاحقًا لإضافة الألمانية والإنجليزية.

الخطوة التالية الأفضل هي أني أضيف لك:

اسمك أو اسم مشروعك

رقم التواصل أو واتساب

قسم أعمالك السابقة

زر تغيير اللغة بشكل فعلي بين العربية / الألمانية / الإنجليزية

اكتب لي فقط اسم الموقع الذي تريده، وأنا أجهزه داخل التصميم مباشرة.


Personal-web-agency-site-german
عندما يضغط تواصل الان عبر واتس   15213873166


Nachgedacht für 7s
Personal-web-agency-site-german
· typescript
            </div>

            <div className="grid gap-4 sm:grid-cols-2">
              <div className="rounded-3xl border border-white/10 bg-white/5 p-6 shadow-2xl backdrop-blur">
                <div className="text-3xl">🚀</div>
                <h3 className="mt-4 text-xl font-semibold">تنفيذ سريع</h3>
                <p className="mt-2 text-sm leading-6 text-white/65">
                  مواقع حديثة بهوية قوية وانطباع أول احترافي.
                </p>
              </div>
              <div className="rounded-3xl border border-white/10 bg-white/5 p-6 shadow-2xl backdrop-blur">
                <div className="text-3xl">📱</div>
                <h3 className="mt-4 text-xl font-semibold">متجاوب مع كل الأجهزة</h3>
                <p className="mt-2 text-sm leading-6 text-white/65">
                  تصميم مناسب للكمبيوتر والهاتف والتابلت.
                </p>
              </div>
              <div className="rounded-3xl border border-white/10 bg-white/5 p-6 shadow-2xl backdrop-blur sm:col-span-2">
                <div className="text-3xl">🌍</div>
                <h3 className="mt-4 text-xl font-semibold">جاهز للتعدد اللغوي</h3>
                <p className="mt-2 text-sm leading-6 text-white/65">
                  الموقع الآن بالعربية، ويمكن لاحقًا إضافة الألمانية والإنجليزية بسهولة.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section className="mx-auto max-w-7xl px-6 py-20 lg:px-8">
        <div className="max-w-2xl">
          <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-400">الخدمات</p>
          <h2 className="mt-3 text-3xl font-bold sm:text-4xl">كل ما تحتاجه لموقع قوي واحترافي</h2>
        </div>
        <div className="mt-12 grid gap-6 md:grid-cols-2 xl:grid-cols-4">
          {services.map((service) => (
            <div
              key={service.title}
              className="rounded-3xl border border-white/10 bg-white/5 p-6 shadow-xl transition hover:-translate-y-1 hover:bg-white/10"
            >
              <div className="text-3xl">{service.icon}</div>
              <h3 className="mt-4 text-xl font-semibold">{service.title}</h3>
              <p className="mt-3 text-sm leading-6 text-white/65">{service.desc}</p>
            </div>
          ))}
        </div>
      </section>

      <section className="border-y border-white/10 bg-white/5">
        <div className="mx-auto grid max-w-7xl gap-12 px-6 py-20 lg:grid-cols-2 lg:px-8">
          <div>
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-400">المميزات</p>
            <h2 className="mt-3 text-3xl font-bold sm:text-4xl">لماذا هذا الموقع مناسب لك؟</h2>
            <p className="mt-6 text-white/70">
              هذا التصميم مناسب جدًا إذا كنت تريد تقديم نفسك كمصمم أو مطور مواقع بشكل احترافي مع قابلية إضافة لغات أخرى في المستقبل.
            </p>
          </div>
          <div className="grid gap-4 sm:grid-cols-2">
            {features.map((feature) => (
              <div key={feature} className="rounded-2xl border border-white/10 bg-slate-900/70 p-5 text-white/85 shadow-lg">
                {feature}
              </div>
            ))}
          </div>
        </div>
      </section>

      <section className="mx-auto max-w-7xl px-6 py-20 lg:px-8">
        <div className="flex flex-col gap-4 sm:flex-row sm:items-end sm:justify-between">
          <div>
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-400">نماذج</p>
            <h2 className="mt-3 text-3xl font-bold sm:text-4xl">أمثلة لأنواع المواقع الممكنة</h2>
          </div>
        </div>
        <div className="mt-12 grid gap-6 md:grid-cols-3">
          {projects.map((project) => (
            <div key={project.title} className="rounded-3xl border border-white/10 bg-gradient-to-b from-white/8 to-white/3 p-6 shadow-xl">
              <span className="rounded-full border border-cyan-400/30 bg-cyan-400/10 px-3 py-1 text-xs font-medium text-cyan-300">
                {project.type}
              </span>
              <h3 className="mt-5 text-2xl font-semibold">{project.title}</h3>
              <p className="mt-3 text-sm leading-6 text-white/65">{project.desc}</p>
            </div>
          ))}
        </div>
      </section>

      <section className="mx-auto max-w-5xl px-6 pb-20 lg:px-8">
        <div className="rounded-[2rem] border border-cyan-400/20 bg-gradient-to-r from-cyan-400/10 to-indigo-500/10 p-10 text-center shadow-2xl">
          <h2 className="text-3xl font-bold sm:text-4xl">جاهز لموقعك الاحترافي؟</h2>
          <p className="mx-auto mt-4 max-w-2xl text-white/70">
            ابدأ الآن بموقع عصري يمنحك حضورًا قويًا، ومعه إمكانية إضافة اللغة الألمانية والإنجليزية لاحقًا.
          </p>
تم ربط زر تواصل الآن بواتساب على الرقم:
15213873166

وأصبح الزر يفتح واتساب مباشرة عند الضغط عليه.

إذا تريد، أقدر أيضًا أجعل زر "ابدأ مشروعك" في أعلى الصفحة يفتح واتساب أيضًا.



ChatGPT generiert eine Reaktion…
