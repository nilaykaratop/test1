<script context="module">
	import * as Base from '../components/base.js';
	import { get } from 'svelte/store';
	import { _, isLocaleLoaded } from '../locals/i18n';
</script>

<script>
	import * as UI from '../components/UI';
	let width = 0;
	$: if ($isLocaleLoaded) {
	}
</script>
<UI.Page>

 <UI.Section>
	<UI.Headline
	  title={'OUR SOLUTIONS ARE SOMETHING GOOD FOR YOU TEST'}
	  description={"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages."}
    />
    <UI.Block>
        <UI.Card
		 image={''}
		 title={'SUBMIT YOUR REQUEST'}
		 text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
		/>
		<UI.Card
		 image={''}
		 title={'TALK TO CONSULTANT'}
		 text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	   />
	    <UI.Card
	     image={''}
	     title={'TRAVEL TO TURKEY'}
	     text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	  />
    </UI.Block>
 </UI.Section>
 <UI.Section>
	<UI.Headline 
    	title={'DO YOUR MEDICAL THINGS ON THE MIDDLE OF THE WORLD, TURKEY'}
	    description={"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages."}
	/>
	<!-- //İMG GELECEK -->
 </UI.Section>
 <UI.Section>
	<UI.Headline 
    	title={'OUR HIGH QUALITY SERVICES'}
	    description={"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages."}
	/>
	<UI.Block>
        <UI.Card
		 image={''}
		 title={'FUE HAIR TRANSPLANT'}
		 text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
		/>
		<UI.Card
		 image={''}
	     title={'FUE HAIR TRANSPLANT'}
		 text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	   />
	   <UI.Card
	     image={''}
	     title={'FUE HAIR TRANSPLANT'}
	     text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	    />
	    <UI.Card
	     image={''}
	     title={'FUE HAIR TRANSPLANT'}
	     text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	    />
	    <UI.Card
	     image={''}
	     title={'FUE HAIR TRANSPLANT'}
	     text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	    />
	    <UI.Card
	     image={''}
	     title={'FUE HAIR TRANSPLANT'}
	     text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
        />
        <UI.Card
         image={''}
         title={'FUE HAIR TRANSPLANT'}
         text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
        />
        <UI.Card
         image={''}
         title={'FUE HAIR TRANSPLANT'}
         text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
        />
    </UI.Block>
 </UI.Section> 
 <UI.Section>
	<UI.Headline 
	title={'FREQUINCY ASKED QUESTIONS'}
	description={"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages."}
    />
   <!-- //tab ve accordion menu gelecek// -->
 </UI.Section>
    <UI.Section>
	  <UI.Headline 
     	title={'LATES BLOG POSTS'}
	    description={"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages."}
	  />
	 <UI.Block>
	 	 <UI.Card
		  image={''}
		  title={'SAPPHIRE FUE HAIR TRANSPLANT'}
		  text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	     />
	    <UI.Card
		  image={''}
		  title={'SAPPHIRE FUE HAIR TRANSPLANT'}
		  text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	    />
	    <UI.Card
		  image={''}
		  title={'SAPPHIRE FUE HAIR TRANSPLANT'}
		  text={'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry’s.'}
	    />
     </UI.Block>
    </UI.Section>
</UI.Page>