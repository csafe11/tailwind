<template>
  <Nav />
<div class="content">
  <div class="columns-2">
    <div class="shadow-lg
    
    
    ">
  <h1>Content</h1>

  <p>
   Lorem, ipsum dolor sit amet consectetur adipisicing elit. Error illum fugit culpa alias. Enim fugit suscipit magni facere praesentium ullam officiis aut illum odit a quam illo amet, magnam repellat asperiores tempora quo harum molestiae voluptatum! Quasi facilis repellat eum corrupti quidem? Expedita repellat ipsum eaque quo. Facilis, iure illo dolores ea, illum reiciendis exercitationem fugiat aspernatur quas labore dolorum assumenda. Aliquam, corrupti recusandae ad optio excepturi ducimus deleniti maxime animi sit error officiis dolor, dolore illo nulla nisi molestias suscipit iste. Ut enim, dolore omnis illum libero modi aut ex quasi necessitatibus soluta voluptatem error deleniti fuga eveniet ullam qui veritatis vero vel quos sit unde adipisci reprehenderit. Consectetur ad modi accusantium corporis rem nam iste quaerat? Rem natus aliquam quae, neque aperiam rerum commodi perspiciatis facilis qui laudantium exercitationem sint praesentium ab corrupti nihil laborum. Consequuntur laborum animi dicta fuga in nesciunt odit inventore quisquam vero, alias optio non facilis facere enim fugiat debitis! Dolor provident eius temporibus ipsum tenetur assumenda et enim eum explicabo. Hic cupiditate consectetur, illum aspernatur accusamus corrupti eius libero! Sint sunt adipisci tempora, rem repellendus repellat velit mollitia minus asperiores eum laudantium dolorum voluptas doloremque voluptatibus sapiente, nihil nesciunt perspiciatis accusantium aut dignissimos maxime optio amet! Voluptates, dolorum illo aspernatur laborum expedita inventore saepe odio, fugiat ad molestias repellat recusandae consequuntur nisi quas corporis veniam ea deserunt at, nobis aperiam numquam! Nam ab consequuntur iusto ullam nulla? Vero quas aut eligendi architecto officiis. Ipsum amet expedita quod vero atque minus quo iusto. Dolore voluptatum sit quasi eveniet amet fugiat laudantium. Eos voluptatum vitae placeat magni velit itaque perferendis error iure totam amet perspiciatis magnam, dolorum quia? Illum officia commodi perferendis provident iusto aut voluptate! Quidem assumenda omnis reiciendis at similique neque ad cupiditate recusandae sequi, repellendus repudiandae beatae sunt earum! Esse quidem soluta ipsam vel sed eius optio laboriosam cum aliquam voluptate voluptatibus tempora inventore mollitia maiores iure, recusandae nulla. Pariatur aliquam dicta doloremque impedit, assumenda ipsam! Quaerat vero adipisci itaque. Nisi exercitationem vitae odio error quam eveniet iusto officia facere, tempora excepturi laudantium consectetur optio aut omnis beatae nesciunt quae eos. Ipsam fugit ullam impedit veritatis tenetur tempore quia ad! Nesciunt quaerat mollitia vero dignissimos pariatur perspiciatis harum, optio, fugiat ut expedita veniam cumque. Rerum nobis laudantium animi officiis, incidunt itaque magni, totam et nostrum repellendus natus sit sapiente est aliquid dolorum laboriosam earum dicta soluta amet! Est eos ducimus mollitia expedita rerum, temporibus ad corrupti repellat voluptatum itaque nostrum iusto explicabo officia quisquam quod, officiis, praesentium consectetur tempora quibusdam! Dicta id consectetur provident, vitae maxime atque ab doloremque, optio porro placeat labore incidunt consequatur est nesciunt dolores minus autem amet! Numquam iste voluptas iusto incidunt natus consectetur deserunt non repellat quidem! Quo repudiandae tempora dignissimos amet, consequatur eaque voluptatum. Exercitationem, quam delectus. Excepturi assumenda earum obcaecati, optio quaerat facere soluta numquam tempore ea mollitia deserunt beatae perferendis adipisci debitis animi delectus quod ullam aspernatur tempora maiores molestiae! Officia corporis recusandae quod porro modi saepe cumque. Id corrupti asperiores vero suscipit doloribus!
  </p>

  <p class="break-after-column">
    Dolor sed viverra ipsum nunc aliquet. Sed sed risus pretium quam vulputate
    dignissim. Tortor aliquam nulla facilisi cras. A erat nam at lectus urna
    duis convallis convallis. Nibh ipsum consequat nisl vel pretium lectus.
    Sagittis aliquam malesuada bibendum arcu vitae elementum. Malesuada bibendum
    arcu vitae elementum curabitur vitae nunc sed velit.
  </p>
    </div>
  <div class="subject animation">
    <img src="https://picsum.photos/id/237/200/300" alt="">
  </div>

<div class="shadow-lg">
  <h1>ELEM</h1>
  <p class="text-red-800">
    Adipiscing enim eu turpis egestas pretium aenean pharetra magna ac. Arcu
    cursus vitae congue mauris rhoncus aenean vel. Sit amet cursus sit amet
    dictum. Augue neque gravida in fermentum et. Gravida rutrum quisque non
    tellus orci ac auctor augue mauris. Risus quis varius quam quisque id diam
    vel quam elementum. Nibh praesent tristique magna sit amet purus gravida
    quis. Duis ultricies lacus sed turpis tincidunt id aliquet. In egestas erat
    imperdiet sed euismod nisi. Eget egestas purus viverra accumsan in nisl nisi
    scelerisque. Netus et malesuada fames ac.
  </p>
<div v-for="adat in data" key="adat.name">
  
 <h1 class="lgblue font-mono">{{ adat.year }}. {{ adat.month }}. {{ adat.day }}.</h1>
</div>
</div>
</div>



</div>
</template>

<script setup lang="ts">

const { data } = await useFetch('/api/bar')
</script>
