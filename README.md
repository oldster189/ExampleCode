# ExampleCode
1. Get Current ListView
                    int first = mListView.getFirstVisiblePosition();
                    View c =  mListView.getChildAt(0);
                    int top = c == null?0:c.getTop();
                    int addition = (data!=null) ? data.size():0;
                    mAdapter = new HouseOpinionListViewAdapter(HouseGeneralOpinionFragment.this, response.body(), false);
                    mAdapter.notifyDataSetChanged();
                    mListView.setAdapter(mAdapter);
                    mListView.setSelectionFromTop(first,top);
            
