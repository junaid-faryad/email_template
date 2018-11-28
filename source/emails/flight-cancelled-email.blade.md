<table class="wrapper w-full bg-grey-light all-font-sans" cellpadding="0" cellspacing="0" lang="{{ $page->language ?? 'en' }}" role="presentation">
  <tr>
    <td class="sm-w-full py-48" align="center">
      <table class="w-600 sm-w-full" cellpadding="0" cellspacing="0" role="presentation">
        <tr>
          <td align="left" class="px-24">
            @include('_partials.header')
            <table class="w-full bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
              <tr>
                  <td><p class="pl-16 purple-color text-2xl font-semibold"> Flight Cancellation Confirmation</p></td>
              </tr>
              <tr>
                  <td><p class="pl-16 text-lg font-semibold mb-0 text-grey-darkest"> Hello John Smith!</p></td>
              </tr>
              <tr>
                  <td><p class="pl-16 pr-16 text-base grey-color"> We have successfully cancelled the following reservation at your request. No Need to call us to confirm. You can see all the details of your cancelled flight below</p></td>
              </tr>
            </table>
            <table class="w-full bg-white confirmation_numbers" cellpadding="0" cellspacing="0" role="presentation">
              <tbody class="grey_wrapper_table">
                <tr>
                  <th COLSPAN=2 class="pl-12">
                    <p class="purple-color text-left text-base font-semibold"> Cancelled Itinerary: San Francisco to London </p>
                  </th>
                </tr>
                <tr>
                  <td>
                    <span class="pl-16 m-0 text-sm font-semibold text-grey-darkest"> Travel Dates</span>
                  </td>
                  <td>
                    <span class="pr-16 m-0 text-sm font-semibold text-grey-darkest"> Fly.me Reference #</span>
                  </td>
                </tr>
                <tr>
                  <td class="pl-16 pt-8">
                    <span class="purple-color m-0 text-base"> Dec 10, 2018 - Dec 14, 2018</span>
                  </td>
                  <td class="pt-8 pr-16">
                    <span class="pr-16 m-0 purple-color m-0 text-base"> 40005673</span>
                  </td>
                </tr>
                <tr>
                  <td class="pl-16 pt-16 text-grey-darkest">
                    <span class="pr-8 m-0 text-sm font-semibold"> You will receive a refund of </span>
                  </td>
                  <td class="pt-16 text-grey-darkest">
                    <span class="pr-16 m-0 text-sm font-semibold"> American Airlines Reference # </span>
                  </td>
                </tr>
                <tr>
                  <td class="pl-16 pt-8 pb-16">
                    <span class="purple-color">$656.00</span>
                  </td>
                  <td class="pt-8 pb-16">
                    <span class="pr-16 m-0 purple-color">5674133</span>
                  </td>
                </tr>
              </tbody>
            </table>
           @include('_partials.centerSection')
            <!-- Your Traverler Started -->
            <table class="w-full bg-white confirmation_numbers pt-32 pb-32" cellpadding="0" cellspacing="0" role="presentation">
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
            <table class="w-full bg-white confirmation_numbers" cellpadding="0" cellspacing="0" role="presentation">
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
                    <span class="m-0 h-14 text-left text-sm grey-color">Total Charges</span>
                  </td>
                  <td> <span class="m-0 h-14 pr-16 text-right text-sm grey-color">$656.00</span></td>
                </tr>
                <tr class="pl-16 mb-16 flex justify-between">
                  <td> <span class="m-0 h-14 font-bold text-left text-sm grey-color">Refund to Original Form of Payments</span></td>
                  <td> <span class="m-0 h-14 pr-16 font-bold text-right text-sm grey-color">$656.00</span> </td>
                </tr>
              </tbody>
            </table>
            <!-- Summary of Charges Ended -->
            <table class="w-full pt-24 bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
              <tr>
                <td class="pl-32">
                  <p class="text-lg font-bold purple-color"> Need to Know</p>
                </td>
              </tr>
              <tr>
                <td class="pl-32 pr-32 grey-color">
                  <p class="m-0 text-left text-lg font-medium all-text-justify leading-20"> $656.00 will be refunded by the Americal Airlines to the original form of Payment within 7-10 business days.</p>
                  <p class="pt-4 text-left text-lg font-medium all-text-justify leading-20"> To refund additional services, such as baggage fees or seat assignments fees, please contact American Airlines directly.</p>
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
                  <p class="text-left text-lg font-medium all-text-justify leading-20"> We are here 24/7. Feel free to email us at <span class="footer_link_color pr-8">support@fly.me</span>   For any questions or concerns, call us 1 (540)328-6206. You can also get answers to top questions in our <span class="footer_link_color"> FAQ's </span></p>
                </td>
              </tr>
            </table>
            <!-- Footer -->
            @include('_partials.footer')
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>