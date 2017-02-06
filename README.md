# ExampleCode
1. Get Current ListView</br>
                    int first = mListView.getFirstVisiblePosition();</br>
                    View c =  mListView.getChildAt(0);</br>
                    int top = c == null?0:c.getTop();</br>
                    int addition = (data!=null) ? data.size():0;</br>
                    mAdapter = new HouseOpinionListViewAdapter(HouseGeneralOpinionFragment.this, response.body(), false);</br>
                    mAdapter.notifyDataSetChanged();</br>
                    mListView.setAdapter(mAdapter);</br>
                    mListView.setSelectionFromTop(first,top);</br>
            
