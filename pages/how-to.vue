<template>
  <section class="faq">
    <div class="container">
      <div class="faq-banner">
        <img src="/SU.png" alt="" />
      </div>
      <div class="section-header">КАК СТАТЬ УЧАСТНИКОМ СТРИМФЕСТА 2021</div>
      <div class="faq-items">
        <button
          @click="toggleAccordion(1)"
          :class="{ 'faq-item-active': accordionIds.includes(1) }"
          class="faq-item"
        >
          <img class="faq-item__img-1" src="/star_ico.png" />
          Что дает статус участника фестиваля?
        </button>
        <div
          :class="{ visible: accordionIds.includes(1) }"
          class="faq-item__inner"
        >
          <p>
            Каждый участник получает возможность продавать именные билеты на
            фестиваль и получать за это деньги: в этом году это 500 рублей
            донатом с каждого проданного билета.
          </p>
          <p>
            Популярным стримерам и подкастерам, заинтересованным в общении с
            публикой, на фестивале предоставляются оборудованные стрим-позиции
            для выхода в эфир и комфортного интерактива с&nbsp;аудиторией в зале
            (в том числе в звукоизолированных зонах).
          </p>
          <p>
            Каждого участника мы представляем коммерческим партнерам фестиваля,
            которые могут предложить ему специальные активности на Стримфесте
            2021 за дополнительное вознаграждение.
          </p>
        </div>
        <button
          @click="toggleAccordion(2)"
          :class="{ 'faq-item-active': accordionIds.includes(2) }"
          class="faq-item"
        >
          <img class="faq-item__img-1" src="/star_ico.png" />
          Я стример или подкастер, как мне стать участником фестиваля?
        </button>
        <div
          :class="{ visible: accordionIds.includes(2) }"
          class="faq-item__inner"
        >
          <p>
            Проверьте, соответствуете ли вы критериям участия (о них ниже), и
            напишите
            <a href="https://vk.com/mikhail_lisetskiy" class="link"
              >организаторам в VK</a
            >
            или на&nbsp;<a href="mailto:mike@streamfest.ru" class="link"
              >mike@streamfest.ru</a
            >.
          </p>
          <p>
            При формировании списка участников Стримфеста 2021 мы исходим из
            следующих принципов:
          </p>
          <ul>
            <li>
              <p>
                <b>Паритетность:</b> игровые стримы значительно популярнее
                других эфирных направлений, поэтому критерии участия для
                геймеров и не-геймеров разнятся. Если за последний год больше
                половины эфирного времени стримера была посвящена видеоиграм, то
                с точки зрения Стримфеста это игровой стример.
              </p>
            </li>
            <li>
              <p>
                <b>Разнообразие:</b> мы стремимся, чтобы на фестивале были
                представлены основные стримерские платформы и тематики. Важное
                следствие: если у нас получится переизбыток регистраций
                стримеров какого-либо эфирного направления, регистрация новых
                участников в данной тематике стримов будет закрыта. То же
                касается и стрим-платформ в целом. Регистрируйтесь заранее!
              </p>
            </li>
            <li>
              <p>
                <b>Инициатива на стороне стримеров:</b> Стримфест НЕ практикует
                активное приглашение участников. Даже&nbsp;самые популярные
                стримеры не должны дожидаться формального «приглашения на
                Стримфест». При этом мы активно принимаем заявки и отвечаем
                очень быстро.
              </p>
            </li>
            <li>
              <p>
                <b>Регулярность и опытность:</b> стрим-канал заявителя должен
                существовать дольше 6 месяцев, а стримы на нем должны проходить
                не реже 3 раз в неделю. Это общее требование для всех
                заявителей.
              </p>
            </li>
            <li>
              <p>
                <b>Отсутствие накруток:</b> заявитель не должен применять ботов
                для улучшения своей статистики. Мы&nbsp;выявляем «накрутчиков» с
                помощью различных web-сервисов и ручного контент-анализа, а
                также оцениваем спорных кандидатов совместно с менеджерами
                стрим-платформ и аналитиками сервиса
                <a href="https://streamscharts.com/" class="link"
                  >Streams Charts</a
                >. Если участник использует ботов и это доказано, это может
                стать основанием для исключения из списка уже
                зарегистрированного участника.
              </p>
            </li>
            <li>
              <p>
                <b>Закрытый список платформ:</b> в этом году участниками
                фестиваля могут стать стримеры следующих платформ: Twitch.tv,
                YouTube, TikTok, VK, OK, WASD, Goodgame, Instagram. Заявитель
                должен выбрать один канал, с которым он заявляется на Стримфест.
                Показатели каналов с разных платформ не суммируются.
              </p>
            </li>
            <li>
              <p>
                <b>Специальные гости:</b> организаторы оставляют за собой право
                аккредитовать участниками фестиваля несколько специальных гостей
                Стримфеста, не обязательно соответствующих общим требованиям.
              </p>
            </li>
          </ul>
        </div>
        <button
          @click="toggleAccordion(3)"
          :class="{ 'faq-item-active': accordionIds.includes(3) }"
          class="faq-item"
        >
          <img class="faq-item__img-2" src="/twitch_ico.png" />
          Условия регистрации стримеров Twitch.tv
        </button>
        <div
          :class="{ visible: accordionIds.includes(3) }"
          class="faq-item__inner"
        >
          <p>
            Вы можете стать участником Стримфеста, продавать именные билеты и
            получать с них доход, если на момент подачи заявки.
          </p>
          <p>Для стримеров <b>игровой</b> тематики:</p>
          <ul>
            <li>
              <p>
                На вашем канале больше 20 000 фолловеров, а средний онлайн ваших
                стримов за последний год превышает 100 человек (по данным
                независимого сервиса
                <a href="https://sullygnome.com/" class="link">SullyGnome</a>).
              </p>
            </li>
            <li>
              <p>
                На вашем канале больше 12 000 фолловеров, а средний онлайн ваших
                стримов за последний год превышает 250 человек (по данным
                независимого сервиса
                <a href="https://sullygnome.com/" class="link">SullyGnome</a>).
              </p>
            </li>
          </ul>
          <p>
            Для стримеров <b>разговорной</b> тематики (IRL, Just Chatting,
            ASMR):
          </p>
          <ul>
            <li>
              <p>
                На вашем канале больше 12 000 фолловеров, а средний онлайн ваших
                стримов за последний год превышает 80 человек (по данным
                независимого сервиса
                <a href="https://sullygnome.com/" class="link">SullyGnome</a>).
              </p>
            </li>
            <li>
              <p>
                На вашем канале больше 8000 фолловеров, а средний онлайн ваших
                стримов за последний год превышает 200 человек (по данным
                независимого сервиса
                <a href="https://sullygnome.com/" class="link">SullyGnome</a>).
              </p>
            </li>
          </ul>
          <p>
            Для стримеров <b>творческой</b> тематики (музыкальные стримы,
            рисование, крафт, фитнес, шахматы и т.д.):
          </p>
          <ul>
            <li>
              <p>
                На вашем канале больше 3000 фолловеров, а средний онлайн ваших
                стримов за последний год превышает 30 человек (по данным
                независимого сервиса
                <a href="https://sullygnome.com/" class="link">SullyGnome</a>).
              </p>
            </li>
          </ul>
        </div>
        <button
          @click="toggleAccordion(4)"
          :class="{ 'faq-item-active': accordionIds.includes(4) }"
          class="faq-item"
        >
          <img class="faq-item__img-2" src="/youtube_ico.png" />
          Условия регистрации стримеров YouTube
        </button>
        <div
          :class="{ visible: accordionIds.includes(4) }"
          class="faq-item__inner"
        >
          <p>
            Ключевое условие: ваш канал на YouTube должен использоваться в
            первую очередь для стримов, а не для выкладки записанных видео, и
            позиционироваться таковым на аудиторию. Если у вас на канале нет
            записей стримов в открытом доступе, это может стать основанием для
            отказа в регистрации.
          </p>
          <p>
            Вы можете стать участником Стримфеста, продавать именные билеты и
            получать с них доход, если на момент подачи заявки:
          </p>
          <p>Для стримеров <b>игровой</b> тематики:</p>
          <ul>
            <li>
              <p>
                На вашем канале больше 50 000 подписчиков, а среднее количество
                просмотров канала за последний месяц — от 1700 человек в эфирный
                день (по данным независимого сервиса
                <a href="https://socialblade.com/" class="link">Socialblade</a>)
              </p>
            </li>
          </ul>
          <p>
            Для стримеров <b>разговорной</b> тематики (IRL, Just Chatting,
            ASMR):
          </p>
          <ul>
            <li>
              <p>
                На вашем канале больше 35 000 подписчиков, а среднее количество
                просмотров канала за последний месяц — от 1200 человек в эфирный
                день (по данным независимого сервиса
                <a href="https://socialblade.com/" class="link">Socialblade</a
                >).
              </p>
            </li>
          </ul>
          <p>
            Для стримеров <b>творческой</b> тематики (музыкальные стримы,
            рисование, крафт, фитнес, шахматы и т.д.):
          </p>
          <ul>
            <li>
              <p>
                На вашем канале больше 20 000 подписчиков, а среднее количество
                просмотров канала за последний месяц — от 600 человек в эфирный
                день (по данным независимого сервиса
                <a href="https://socialblade.com/" class="link">Socialblade</a
                >).
              </p>
            </li>
          </ul>
        </div>
        <button
          @click="toggleAccordion(5)"
          :class="{ 'faq-item-active': accordionIds.includes(5) }"
          class="faq-item"
        >
          <img class="faq-item__img-3" src="/tiktok_ico.png" />
          Условия регистрации стримеров TikTok
        </button>
        <div
          :class="{ visible: accordionIds.includes(5) }"
          class="faq-item__inner"
        >
          <p>
            Регистрация происходит по согласованию с менеджерами платформы
            <a href="https://www.tiktok.com/ru-RU/" class="link">TikTok</a>.
          </p>

          <p>
            Организаторы Стримфеста совместно с TikTok отберут из числа
            заявителей до 20 самых популярных стримеров.
          </p>
        </div>
        <button
          @click="toggleAccordion(6)"
          :class="{ 'faq-item-active': accordionIds.includes(6) }"
          class="faq-item"
        >
          <img class="faq-item__img-4" src="/vk_ico.png" />
          Условия регистрации стримеров VK
        </button>
        <div
          :class="{ visible: accordionIds.includes(6) }"
          class="faq-item__inner"
        >
          <p>
            Регистрация происходит по согласованию с менеджерами платформы
            <a href="https://vk.com/" class="link">VK</a>.
          </p>
          <p>
            Организаторы Стримфеста совместно с VK отберут из числа заявителей
            до 30 самых популярных стримеров и подкастеров.
          </p>
        </div>
        <button
          @click="toggleAccordion(7)"
          :class="{ 'faq-item-active': accordionIds.includes(7) }"
          class="faq-item"
        >
          <img class="faq-item__img-5" src="/OK_ico.png" />
          Условия регистрации стримеров OK
        </button>
        <div
          :class="{ visible: accordionIds.includes(7) }"
          class="faq-item__inner"
        >
          <p>
            Регистрация происходит по согласованию с менеджерами платформы
            <a href="https://ok.ru/" class="link">OK</a>.
          </p>
          <p>
            Организаторы Стримфеста совместно с OK отберут из числа заявителей
            до 20 самых популярных стримеров.
          </p>
        </div>
        <button
          @click="toggleAccordion(8)"
          :class="{ 'faq-item-active': accordionIds.includes(8) }"
          class="faq-item"
        >
          <img class="faq-item__img-2" src="/wasd_ico.png" />
          Условия регистрации стримеров WASD
        </button>
        <div
          :class="{ visible: accordionIds.includes(8) }"
          class="faq-item__inner"
        >
          <p>
            Регистрация происходит по согласованию с менеджерами платформы
            <a href="https://wasd.tv/" class="link">WASD</a>.
          </p>
          <p>
            Организаторы Стримфеста совместно с WASD отберут из числа заявителей
            до 20 самых популярных стримеров.
          </p>
        </div>
        <button
          @click="toggleAccordion(9)"
          :class="{ 'faq-item-active': accordionIds.includes(9) }"
          class="faq-item"
        >
          <img class="faq-item__img-6" src="/gg_ico.png" />
          Условия регистрации стримеров Goodgame
        </button>
        <div
          :class="{ visible: accordionIds.includes(9) }"
          class="faq-item__inner"
        >
          <p>
            Регистрация происходит на основе внутреннего
            <a href="https://goodgame.ru/channels/rating/premiums" class="link"
              >рейтинга популярности Goodgame.ru</a
            >.
          </p>
          <p>
            Вы можете стать участником Стримфеста, продавать именные билеты и
            получать с них доход, если на момент подачи заявки:
          </p>
          <p>Для стримеров <b>игровой</b> тематики:</p>
          <ul>
            <li>
              <p>
                Вы входите в топ-20 рейтинга популярности.
              </p>
            </li>
          </ul>
          <p>
            Для стримеров <b>разговорной</b> тематики (IRL, Just Chatting,
            ASMR):
          </p>
          <ul>
            <li><p>вы входите в топ-30 рейтинга популярности.</p></li>
          </ul>
          <p>
            Для стримеров <b>творческой</b> тематики (музыкальные стримы,
            рисование, крафт, фитнес, шахматы и т.д.):
          </p>
          <ul>
            <li><p>вы входите в топ-60 рейтинга популярности.</p></li>
          </ul>
        </div>
        <button
          @click="toggleAccordion(10)"
          :class="{ 'faq-item-active': accordionIds.includes(10) }"
          class="faq-item"
        >
          <img class="faq-item__img-2" src="/insta_ico.png" />
          Условия регистрации стримеров Instagram
        </button>
        <div
          :class="{ visible: accordionIds.includes(10) }"
          class="faq-item__inner"
        >
          <p>
            Ключевое условие: на вашем канале в Instagram должен регулярно
            выходить live-контент, востребованный вашей аудиторией.
          </p>
          <p>
            Регистрация участников происходит на основе контент-анализа
            аккаунтов: организаторы Стримфеста отберут до 20 самых популярных
            стримеров в Instagram из числа поданных заявок
          </p>
        </div>
        <button
          @click="toggleAccordion(11)"
          :class="{ 'faq-item-active': accordionIds.includes(11) }"
          class="faq-item"
        >
          <img class="faq-item__img-1" src="/mic_ico.png" />
          Я веду интересный подкаст, как мне стать участником фестиваля?
        </button>
        <div
          :class="{ visible: accordionIds.includes(11) }"
          class="faq-item__inner"
        >
          <p>
            <a href="mailto:mike@streamfest.ru" class="link">Напишите нам!</a> В
            этом году мы впервые приглашаем на фестиваль не только стримеров, но
            и подкастеров. Лучшие подкаст-команды смогут вживую встретиться с
            преданной аудиторией, провести конкурсы и записать новые выпуски
            своих шоу с участием публики и при техническом содействии
            Стримфеста.
          </p>
          <p>
            Организаторы Стримфеста отберут в участники до 25 самых популярных
            подкаст-проектов из числа поданных заявок. Все остальные заявители
            получат бесплатные билеты на оба дня фестиваля.
            Подкастеры,&nbsp;вливайтесь в Стримфест!
          </p>
        </div>
        <div class="faq-item-last">
          <h3 class="faq-item">У меня остались вопросы!</h3>
          <p>
            Прекрасно, задайте их личным сообщением в нашей
            <a href="https://vk.com/streamfest" class="link">группе VK.</a>
          </p>
        </div>
      </div>
    </div>
    <Subscribe />
  </section>
</template>

<script>
import Subscribe from "@/components/Subscribe";

export default {
  components: {
    Subscribe
  },
  scrollToTop: true,
  data() {
    return {
      accordionIds: [1, 2]
    };
  },
  methods: {
    toggleAccordion(id) {
      this.accordionIds = this.accordionIds.includes(id)
        ? this.accordionIds.filter(_id => _id != id)
        : [...this.accordionIds, id];
    }
  }
};
</script>
