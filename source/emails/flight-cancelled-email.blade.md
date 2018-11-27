<table class="wrapper w-full bg-grey-light all-font-sans" cellpadding="0" cellspacing="0" lang="{{ $page->language ?? 'en' }}" role="presentation">
  <tr>
    <td class="sm-w-full py-48" align="center">
      <table class="w-600 sm-w-full" cellpadding="0" cellspacing="0" role="presentation">
        <tr>
          <td align="left" class="px-24">
            <table class="w-full bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
              <tr>
                <td class="px-4 all-py-8 bg-header bg-header-gradient">
                  <img align="left" src="./img/h-logo.png" width="100" alt="">
                </td>
              </tr>
            </table>
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
            <table class="w-full pb-24 bg-white confirmation_numbers" cellpadding="0" cellspacing="0" role="presentation">
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
            <!--Flight Details Started -->
            <table class="w-full bg-white confirmation_numbers pb-32 pt-24" cellpadding="0" cellspacing="0" role="presentation">
              <tbody class="grey_wrapper_table">
                <tr>
                  <td class="px-8 py-16">
                    <table class="w-full">
                      <thead>
                        <tr class="flex justify-left">
                          <td>
                            <p class="m-0 pt-2 text-base text-left purple-color">Depart</p>
                            <div>
                              <span class="text-5xl">10</span>
                              <span class="text-sm grey-color">December</span>
                              <br>
                              <span class="text-sm">Monday</span>
                              <div class="flex flex-col pt-8 pb-8">
                                <span class="line-wrapper">
                                  <span class="line"></span>
                                </span>
                              </div>
                              <span class="text-xs font-semibold">Arriving Tue, Dec 11</span>
                            </div>
                          </td>
                          <td class="pl-16">
                            <p class="m-0 pt-2 font-semibold text-left text-base purple-color">San Francisco</p>
                          </td>
                          <td class="m-0"><img src="img/next-arrow-24.png" alt=""></td>
                          <td> <p class="m-0 pt-2 font-semibold text-base purple-color">London</p></td>
                        </tr>
                      </thead>
                    </table>
                    <table class="w-full departure-details" cellpadding="0" cellspacing="0" role="presentation">
                        <thead>
                          <tr>
                            <th>
                                <div class="text-left">
                                  <span><img src="img/airplane-7-16.png"  width='13' alt=""> </span>
                                  <span class="m-0 pl-8 text-lg text-left font-normail grey-color">Departure</span>
                                </div>
                              </div>
                            </th>
                          </tr>
                        </thead>
                        <tbody class="w-600">
                          <tr>
                            <td>
                              <span class="text-base font-semibold purple-color">San Francisco - 6:00am - Flight AA5764 </span>
                            </td>
                            <td>
                              <span><img src="img/cancel.png" width='10' alt=""> </span>
                              <span class="text-sm grey-color">Seat Selection</span>
                            </td>
                          </tr>
                          <tr>
                            <td>
                              <span class="text-xs font-semibold custom-dark-grey">Mon, Dec 10, 2018 -1h 0m </span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/check-mark.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Carry-on bag</span>
                            </td>
                          </tr>
                          <tr>
                            <td class="pt-8">
                              <span class="text-xs font-normal grey-color">San Francisco Intl. (SFO) to Los Angeles Intl. (LAX) </span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/dollar-sign.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Checked Bag</span>
                            </td>
                          </tr>
                          <tr>
                            <td class="pt-4">
                              <span class="text-xs font-normal grey-color">Economy / Coach (E)</span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/cancel.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Cancellations</span>
                            </td>
                          </tr>
                          <tr>
                            <td class="pt-4">
                              <span class="text-xs font-normal grey-color">Boeign 717 </span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/cancel.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Changes</span>
                            </td>
                          </tr>
                          <tr >
                            <td class="pt-8">
                              <span class="text-sm font-bold custom-dark-grey">Los Angeles - 07:00am </span>
                            </td>
                            <td>
                              <span><img src="img/check-mark.png" width='10' alt=""> </span>
                              <span class="text-sm grey-color">Personal Item</span>
                            </td>
                            <tr>
                              <td class="text-left pt-8"><span class="text-base font-semibold purple-color">56m Layover at LAX</span>
                                <span class="pl-8"><img src="img/exclamation-24.png" width="20" alt=""></span>
                                <span class="text-sm text-grey-darkest">Short Layover</span></td>
                              <td><span class="text-xs font-semibold grey-color"> Carry On </span></td>
                            </tr>
                            <tr>
                              <td class="mt-8"><span class="text-base font-semibold custom-dark-grey">Los Angeles - 8:56am flight AA3356</span></td>
                                <td class="m-0"><span class="text-xs grey-color"> Free </span></td>
                            </tr>
                            <tr>
                              <td><span class="text-xs font-semibold custom-dark-grey">Mon, Dec 10, 2018 -15h 22m </span></td>
                              <td class="pt-8"><span class="text-xs font-semibold grey-color"> 1st Checked Bag </span></td>
                            </tr>
                            <tr>
                              <td class="pt-8">
                              <span class="text-xs font-normal grey-color">Los Angeles Intl. (LAX) to London Heathrow Intl. (LHR) </span>
                            </td>
                              <td><span class="text-xs grey-color"> $30.00 up to 23 Kg</span></td>
                            </tr>
                            <tr>
                              <td class="pt-4"><span class="text-xs font-normal grey-color">Economy / Coach (E)</span></td>
                              <td class="pt-8"><span class="text-xs font-semibold grey-color"> 2nd Checked Bag </span></td>
                            </tr>
                            <tr>
                              <td class="pt-4"><span class="text-xs font-normal grey-color">Boeign 717 </span></td>
                              <td><span class="text-xs grey-color"> $40.00 up to 23 Kg</span></td>
                            </tr>
                            <tr>
                              <td class="text-left pt-8"><span class="text-base font-semibold purple-color">London - 10:08am</span>
                            </tr>
                            <tr>
                              <td><span class="text-xs font-semibold custom-dark-grey">Tue, Dec 11, 2018</span></td>
                            </tr>
                          </tr>
                        </tbody>
                    </table>
                  </td>
                </tr>
              </tbody>
            </table>
            <!-- Ended Flight Details -->
            <!-- Return Fligh Section -->
            <table class="w-full bg-white confirmation_numbers pt-16" cellpadding="0" cellspacing="0" role="presentation">
              <tbody class="grey_wrapper_table">
                <tr>
                  <td class="px-8 py-16">
                    <table class="w-full">
                      <thead>
                        <tr class="flex justify-left">
                          <td>
                            <p class="m-0 pt-2 text-base text-left purple-color">Return</p>
                            <div>
                              <span class="text-5xl">14</span>
                              <span class="text-sm">December</span>
                              <br>
                              <span class="text-sm">Friday</span>
                              <div class="flex flex-col pt-8 pb-8">
                                <span class="line-wrapper">
                                  <span class="line"></span>
                                </span>
                              </div>
                              <span class="text-xs font-semibold">Arriving Sat, Dec 15</span>
                            </div>
                          </td>
                          <td class="pl-16">
                            <p class="m-0 pt-2 font-semibold text-left text-base purple-color">London</p>
                          </td>
                          <td class="m-0"><img src="img/next-arrow-24.png" alt=""></td>
                          <td> <p class="m-0 pt-2 font-semibold text-base purple-color">San Francisco</p></td>
                        </tr>
                      </thead>
                    </table>
                    <table class="w-full departure-details" cellpadding="0" cellspacing="0" role="presentation">
                        <thead>
                          <tr>
                            <th>
                                <div class="text-left">
                                  <span><img src="img/airplane-7-16.png"  width='13' alt=""> </span>
                                  <span class="m-0 pl-8 text-lg text-left font-normail grey-color">Departure</span>
                                </div>
                              </div>
                            </th>
                          </tr>
                        </thead>
                        <tbody class="w-600">
                          <tr>
                            <td>
                              <span class="text-base font-semibold purple-color">London - 8:45am - Flight AA5562 </span>
                            </td>
                            <td>
                              <span><img src="img/cancel.png" width='10' alt=""> </span>
                              <span class="text-sm grey-color">Seat Selection</span>
                            </td>
                          </tr>
                          <tr>
                            <td>
                              <span class="text-xs font-semibold grey-color">Fri, Dec 14, 2018 -14h 0m </span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/check-mark.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Carry-on bag</span>
                            </td>
                          </tr>
                          <tr>
                            <td class="pt-8">
                              <span class="text-xs font-normal grey-color">London Heathrow Intl. (LHR) to San Francisco Intl. (SFO) </span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/dollar-sign.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Checked Bag</span>
                            </td>
                          </tr>
                          <tr>
                            <td class="pt-4">
                              <span class="text-xs font-normal grey-color">Economy / Coach (E)</span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/cancel.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Cancellations</span>
                            </td>
                          </tr>
                          <tr>
                            <td class="pt-4">
                              <span class="text-xs font-normal grey-color">Boeign 717 </span>
                            </td>
                            <td>
                              <span class="text-right"><img src="img/cancel.png" width='10' alt=""> </span>
                              <span class="text-sm text-right grey-color">Changes</span>
                            </td>
                          </tr>
                          <tr >
                            <td class="pt-8">
                              <span class="text-base font-bold purple-color">San Francisco - 12:00am </span>
                            </td>
                            <td>
                              <span><img src="img/check-mark.png" width='10' alt=""> </span>
                              <span class="text-sm grey-color">Personal Item</span>
                            </td>
                            <tr>
                              <td>
                              <span class="text-xs font-semibold grey-color">Fri, Dec 14, 2018 -14h 0m </span>
                              </td>
                            </tr>
                            <tr>
                              <td class="text-right"><span class="text-xs font-semibold grey-color"> Carry On </span></td>
                            </tr>
                            <tr>
                              <td class="text-right"><span class="text-xs grey-color"> Free </span></td>
                            </tr>
                            <tr>
                              <td class="pt-8 text-right"><span class="text-xs font-semibold grey-color"> 1st Checked Bag </span></td>
                            </tr>
                            <tr>
                              <td class="text-right"><span class="text-xs grey-color"> $30.00 up to 23 Kg</span></td>
                            </tr>
                            <tr>
                              <td class="pt-8 text-right"><span class="text-xs font-semibold grey-color"> 2nd Checked Bag </span></td>
                            </tr>
                            <tr>
                              <td class="text-right"><span class="text-xs grey-color"> $40.00 up to 23 Kg</span></td>
                            </tr>
                          </tr>
                        </tbody>
                    </table>
                  </td>
                </tr>
              </tbody>
            </table>
            <!-- Ended Flight Details -->
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
                <td class="px-24">
                  <p class="text-lg font-bold purple-color"> Need to Know</p>
                </td>
              </tr>
              <tr>
                <td class="pl-24 pr-24 grey-color">
                  <p class="m-0 text-left text-base all-text-justify"> $656.00 will be refunded by the Americal Airlines to the original form of Payment with 7-10 business days.</p>
                  <p class="pt-8 text-left text-base all-text-justify"> To refund additional services,  such as baggage fees or seat assignments fees, please American Airlines directly.</p>
                </td>
              </tr>
            </table>
            <table class="w-full pb-20 bg-white rounded-sm shadow" cellpadding="0" cellspacing="0" role="presentation">
              <tr>
                <td class="pl-24">
                  <p class="purple-color text-lg font-bold mb-0"> Need Help? </p>
                </td>
              </tr>
              <tr>
                <td class="pl-24 pr-24 grey-color">
                  <p class="text-left text-base all-text-justify"> We are here to 24/7. Feel free to email us at <span class="footer_link_color">support@fly.me</span> For any questions or concerns, call us 1 (540)328-6206. You can also get answers to top questions in our <span class="footer_link_color"> FAQ's </span></p>
                </td>
              </tr>
            </table>
            <!-- Footer Started -->
            <table class="w-full bgFooter" cellpadding="0" cellspacing="0" role="presentation">
              <tr class="h-40"><td>&zwnj;</td></tr>
              <tr class="h-47">
                <td>
                  <img class="block h-64 mx-auto" src="img/f-logo.png" alt="">
                </td>
              </tr>
              <tr class="h-40"><td>&zwnj;</td></tr>
              <tr class="flex justify-center">
                <td class="text-xs text-grey-dark">
                  <div class="icon-wrapper m-4 mt-0 mb-0">
                    <div class="rounded-full w-40 h-40 footer-rounded-icon">
                      <img class="footer_icon_bg mx-auto footer_icon_color" src="img/w-fb-24.png" alt="">
                    </div>
                  </div>
                  <div class="icon-wrapper m-4 mt-0 mb-0">
                    <div class="rounded-full w-40 h-40 footer-rounded-icon">
                      <img class="footer_icon_bg mx-auto footer_icon_color" src="img/w-insta-24.png" alt="">
                    </div>
                  </div>
                  <div class="icon-wrapper m-4 mt-0 mb-0">
                    <div class="rounded-full w-40 h-40 footer-rounded-icon">
                      <img class="footer_icon_bg mx-auto footer_icon_color" src="img/w-in-24.png" alt="">
                    </div>
                  </div>
                </td>
              </tr>
              <tr class="h-48"><td>&zwnj;</td></tr>
              <tr class="h-56 w-256">
                <td class="px-40">
                  <div align="center">
                    <a href="#" class="px-10 h-24 no-underline footer_link_color">About</a>
                    <a href="#" class="px-10 h-24 no-underline footer_link_color" >FAQs</a>
                    <a href="#" class="px-10 h-24 no-underline footer_link_color">Help</a>
                    <a href="#" class="px-10 h-24 no-underline footer_link_color">Terms of Service</a>
                  </div>
                </td>
              </tr>
              <tr class="h-48"><td>&zwnj;</td></tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>