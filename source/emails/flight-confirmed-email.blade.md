<table class="wrapper w-full bg-grey-light all-font-sans" cellpadding="0" cellspacing="0" lang="{{ $page->language ?? 'en' }}" role="presentation">
  <tr>
    <td class="sm-w-full py-48" align="center">
      <table class="w-600 sm-w-full" cellpadding="0" cellspacing="0" role="presentation">
        <tr>
          <td align="left" class="px-24">
            @include('_partials.header')
            <table class="w-full bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
            	<tr>
            		<td class="pl-16 all-py-8">
	            		<h1 class="purple-color"> Flight Confirmed!</h1>
	            	</td>
            	</tr>
            	<tr>
            		<td class="pl-16 text-grey-darkest">
	            		<p class="m-0 text-left text-sm font-semibold"> Congratulations John Smith! </p>
	            	</td>
            	</tr>
            	<tr>
            		<td class="pl-16 pt-16">
	            		<span class="purple-color text-base font-semibold"> Thank you for Booking with Fly.me </span>
	            	</td>
	            	<td class="pr-16 pt-16 grey-color">
	            		<span> Your San Francisco - London Round</span>
	            	</td>
	            </tr>
	            <tr>
	            	<td class="pb-20 pl-16 pt-4 grey-color">
	            		<span> trip flight is Confirmed </span>
	            	</td>
            	</tr>
            </table>
            <table class="w-full pb-24 bg-white confirmation_numbers" cellpadding="0" cellspacing="0" role="presentation">
              <tbody class="grey_wrapper_table">
                <tr>
                  <th COLSPAN=2 class="pl-12">
                    <p class="purple-color text-left text-base font-semibold"> Confirmation Numbers </p>
                  </th>
                </tr>
                <tr>
                  <td>
                    <span class="pl-16 m-0 text-sm font-semibold text-grey-darkest"> American Airlines Reference # </span>
                  </td>
                  <td>
                    <span class="pr-16 m-0 text-sm font-semibold text-grey-darkest"> Other Airline Reference #</span>
                  </td>
                </tr>
                <tr>
                  <td class="pl-16 pt-8">
                    <span class="purple-color m-0 text-base"> 5674133</span>
                  </td>
                  <td class="pt-8 pr-16">
                    <span class="pr-16 m-0 purple-color m-0 text-base"> XXXXXX </span>
                  </td>
                </tr>
                <tr>
                  <td class="pl-16 pt-16 text-grey-darkest">
                    <span class="pr-8 m-0 text-sm font-semibold"> Fly.me Reference #</span>
                  </td>
                </tr>
                <tr>
                  <td class="pl-16 pt-8 pb-16">
                    <span class="purple-color">40005673</span>
                  </td>
                </tr>
              </tbody>
            </table>
            <table class="w-full bg-white" cellpadding="0" cellspacing="0" role="presentation">
              <tr>
                <th class="bg-blue all-hover-bg-blue-dark rounded-full" style="mso-padding-alt: 7px 64px 14px;">
                  <a href="#" class="text-white inline-block text-base leading-full py-14 px-48 no-underline">Find Hotels</a>
                </th>
                <th class="bg-white all-hover-bg-white border-2 border-blue rounded-full" style="mso-padding-alt: 7px 64px 14px;">
                  <a href="#" class="text-blue inline-block text-base leading-full py-14 px-48 no-underline">View Itinerary</a>
                </th>
              </tr>
            </table>
            <!-- Buttons Ended -->
            @include('_partials.centerSection')
            <!-- Your Traverler Started -->
            <table class="w-full bg-white confirmation_numbers pt-32" cellpadding="0" cellspacing="0" role="presentation">
              <tbody class="grey_wrapper_table">
                <tr>
                  <td class="pt-12 pl-16 h-20 text-left text-xl purple-color"> Your Travelers </td>
                </tr>
                <tr>
                  <td class="pt-12 pl-16 grey-color"> <span>John Tobias Smith Jr.</span></td>
                </tr>
                <tr>
                  <td class="pt-12 pb-16 pl-16 grey-color"> <span>Allie Smith</span> </td>
                </tr>
              </tbody>
            </table>
            <!-- Your Traverler Ended -->
            <!-- Summary of Charges Started -->
            <table class="w-full bg-white confirmation_numbers pt-32" cellpadding="0" cellspacing="0" role="presentation">
              <tbody class="grey_wrapper_table">
                <tr>
                  <td class="pt-12 pb-12 pl-16 m-0 leading-20 h-20 text-left text-xl purple-color"> Summary of Charges </td>
                </tr>
                <tr class="flex justify-between">
                  <td>
                    <span class="pl-16 m-0 h-14 text-left text-sm grey-color">Base Fare</span>
                  </td>
                  <td>
                    <span class="m-0 pr-16 h-14 text-right text-sm grey-color">$548.00</span>
                  </td>
                </tr>
                <tr class="pl-16 flex justify-between">
                  <td>
                    <span class="m-0 h-14 text-left text-sm grey-color">Taxes & Fees</span>
                  </td>
                  <td>
                    <span class="m-0 h-14 pr-16 text-right text-sm grey-color">$108.00</span>
                  </td>
                </tr>
                <tr class="pl-16 flex justify-between pt-20">
                  <td>
                    <span class="m-0 h-14 text-left text-sm font-bold grey-color">Total Charges</span>
                  </td>
                  <td> <span class="m-0 h-14 pr-16 text-right font-bold text-sm grey-color">$656.000</span></td>
                </tr>
                <tr class="pl-16 mb-16 flex justify-between">
                  <td> <span class="m-0 h-14 font-bold text-left text-sm grey-color">Balance Due</span></td>
                  <td> <span class="m-0 h-14 pr-16 font-bold text-right text-sm grey-color">$0.00</span> </td>
                </tr>
              </tbody>
            </table>
            <!-- Summary of Charges Ended -->
            <table class="w-full pt-24 bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
            	<tr>
            		<td class="pl-32 m-0">
	            		<p class="text-lg font-bold purple-color mb-0"> Need to Know</p>
	            	</td>
            	</tr>
            	<tr>
            		<td class="pl-32 pr-32 grey-color">
	            		<p class="text-left text-base all-text-justify leading-20"> General Checkin Instructions.. have you id ready for security, etc. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam lobortis vel neque ac finibus. Ut mi ante, aliquam quis porttitor eget.</p>
	            	</td>
            	</tr>
            </table>
            <table class="w-full pt-12 bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
            	<tr>
            		<td class="pl-32 m-0">
	            		<p class="text-lg font-bold purple-color mb-0"> Airline Regulations</p>
	            	</td>
            	</tr>
            	<tr>
            		<td class="pl-32 pr-32 grey-color">
	            		<p class="text-left text-base all-text-justify leading-20"> General Airline Regulation Information.. Security screeing times, no boarding passes issued 30 minutes before flight times, etc etc. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse facilisis aliquet elit, nec egestas lacus vestibulum id.</p>
	            	</td>
            	</tr>
            </table>
            <table class="w-full pb-20 bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
              <tr>
                <td class="pl-32">
                  <p class="purple-color text-lg font-bold mb-0"> Need Help? </p>
                </td>
              </tr>
              <tr>
                <td class="pl-32 pr-32 grey-color">
                  <p class="text-left text-base all-text-justify leading-20"> We are here to 24/7. Feel free to email us at <span class="footer_link_color pr-8">support@fly.me</span> For any questions or concerns, call us 1 (540)328-6206. You can also get answers to top questions in our <span class="footer_link_color"> FAQ's </span></p>
                </td>
              </tr>
            </table>
            <!-- Footer Started -->
            @include('_partials.footer')
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>