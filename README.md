static sitemap files


What I know about sitemaps that may be valuable

1. multiple sub-sitemaps can contain the same URL's and it does not hurt the performance. 
    For example, you can have the full_sitemap.xml contain all URL's on the site and have the learn_sitemap.xml contain a subset of those same URL's
    
2. I included both the raw XML files as well as .gzip versions created by running the gzip <file> command 
      https://developers.google.com/search/docs/advanced/sitemaps/large-sitemaps - This guide was where I learned you can compress the files in the sitemap index
      I believe the actual sitemap index is not supposed to be compressed though and be in raw .xml format
      
3. the file sitemap.xml is the sitemap index then the full site sitemap is in full_sitemap.xml

4. I used this https://freesitemapgenerator.com/ to create the video sitemap which grabbed the 4 vimeo embedded videos on our site and formatted them according
    to this guide - https://developers.google.com/search/docs/advanced/sitemaps/video-sitemaps
    
5. I used this tool https://www.screamingfrog.co.uk/ from Emily to create the image sitemap 
    formatted according to this guide https://developers.google.com/search/docs/advanced/sitemaps/image-sitemaps
    
6. I formatted all the news enteries on the acretrader site according to this format - https://developers.google.com/search/docs/advanced/sitemaps/news-sitemap
    
   
----------------------------------------------------------------------------------------------------------------
Descriptions behind each sitemap file in sitemap index

    http://www.acretrader.com/full_sitemap.xml.gz - The full sitemap, containing every 200 code URL that is relevent to the site

    http://www.acretrader.com/video_sitemap.xml.gz - The sitemap containing only special formatted video enteries for the embeddeed vimeo videos on the site
 
    http://www.acretrader.com/resources_sitemap.xml.gz - All URL's from the resources tab on the acretrader site

    http://www.acretrader.com/news_sitemap.xml.gz - All URL's from the news section, formatted according to google news sitemap guidelines

    http://www.acretrader.com/learn_sitemap.xml.gz - all enteries from learn section of site, formatted as normal sitemap enteries

    http://www.acretrader.com/information_sitemap.xml.gz - This sitemap was a category I created to put things in such as the FAQ, PDF files hosted on the site,
                                                            and about-us type pages
                                                            
    http://www.acretrader.com/images_sitemap.xml.gz - Screaming frog generated image sitemap

    http://www.acretrader.com/farms_sitemap.xml.gz - All farm URL's currently live on the site as well as the https://www.acretrader.com/explore page

    http://www.acretrader.com/affiliate_sitemap.xml.gz - I ran screaming frog on https://affiliate.acretrader.com to include those URL's in the sitemap,
                                                          this may not be necessary but I wanted to be thorough
                                                          
   Ask me if you have any confusion!
   -Kyle
