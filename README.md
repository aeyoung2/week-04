# week-04

 1. Merge Node
 
  - Merge : 여러 이미지를 레이어링 할 때 사용 되는 노드, 이 노드를 사용할 때 원하는 결과를 위해 적절하게 이미지의 픽셀 값을 계산 해 줄 합성 알고리즘을 골라야 한다.
  
    - Operation : 이미지에 merge 노드를 적용할 때 사용 할 합성 알고리즘들을 고를 수 있다
    
![137613619-f8ae0505-4b8e-4022-893e-b3836bddf61e](https://user-images.githubusercontent.com/90597842/146678038-148dca8b-bec7-46ce-8d9b-eada0cb00cdb.png)    
![137613551-5ddfa123-6644-46eb-8eff-4abe72662e69](https://user-images.githubusercontent.com/90597842/146678040-a9b1eb5f-96fb-41df-86f1-7a90f230f578.png)
![137613600-3a8dff54-70c3-4a51-a19e-ae81d7d89c35](https://user-images.githubusercontent.com/90597842/146678042-82838821-049f-441a-8389-bd689209c351.png)
![137613606-13c5bf4a-3dc1-491d-a9ba-f20f8def4781](https://user-images.githubusercontent.com/90597842/146678043-4d4e6e97-3f04-426b-97c3-69db5e0c0116.png)
![137613610-b991dbb1-75db-4a4e-b66b-473fedae5e59](https://user-images.githubusercontent.com/90597842/146678044-69590019-1914-464f-9068-d3489ba2f9e0.png)
![137613614-05ea3deb-0dc0-442e-80ce-9eebdc1ddfa1](https://user-images.githubusercontent.com/90597842/146678045-12d23f8c-5aad-4767-b9c4-8acaa13a5d5b.png)
![137613615-ff1c421a-2561-4e51-bc23-cadd7d7409a8](https://user-images.githubusercontent.com/90597842/146678046-493a422a-cd88-4cb0-ba8c-cb22af81fc50.png)
![137613617-fb9b4fc3-755d-41c9-aed0-110f92509d2c](https://user-images.githubusercontent.com/90597842/146678047-9cba3f4e-cbd8-41a7-8d18-95b1c225c606.png)

(https://learn.foundry.com/nuke/content/comp_environment/merging/merge_operations.html)


 2. Rotoscoping
 
  - Rotoscoping : 가장 오래 된 애니메이션 기법 중 하나. 
                  카메라로 촬영 된 영상을 바탕으로 몇 개의 프레임을 추출하여 덧 그리고 이를 애니메이션 키 프레임으로 사용하는 기법
                  누크에서는 Roto노드를 사용해 트래킹 할 영역을 지정하고 그 부분을 알파값으로 추출해 낼 수 있다.
                  가능하다면 keying을 통해 매트를 추출 하는 것이 간편하지만 사용하려는 영상이 크로마키를 사용할 수 없을 경우 일일이 손으로
                  roto를 따며 작업 해 주어야 한다.
                  
                 ![rotoscoping-techniques-nuke-687-v1](https://user-images.githubusercontent.com/90597842/146677765-8074d92a-f4f4-4849-ade8-062c9209c339.jpg)

                 
  
  
  (https://www.pluralsight.com/blog/film-games/understanding-rotoscoping-process-every-vfx-artist-know)
                  
