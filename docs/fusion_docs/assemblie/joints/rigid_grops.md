# 강체 그룹
**강체 그룹**은 Fusion 360에서 선택한 구성요소의 상대적 위치를 잠그는 조립품 관계입니다. 구성요소를 캔버스에서 이동하거나 접합을 적용하면 구성요소가 단일 객체로 처리됩니다.

기본적으로 조립품의 구성요소는 Fusion 360에서 유연하므로 접합과 같은 조립품 관계 간에 정의할 때까지 자유롭게 이동할 수 있습니다. 구성요소의 각 복제는 다른 복제와 독립적으로 유연합니다.

**강체 그룹**을 사용하여 다음을 수행합니다.

* 서로 상대적으로 여러 구성요소의 위치를 제 위치에 고정합니다.
* 삽입된 부분조립품에 있는 모든 구성요소의 상대 위치를 신속하게 잠가 조립품에서 동작을 정의하는 접합을 작성할 때 구성요소가 모두 함께 이동하도록 합니다.
* 각 강체 접합을 두 구성요소 간에만 적용할 수 있는 개별 강체 접합의 수를 최소화합니다.

<details>
<summary>구성요소의 강체 그룹 작성</summary>
<div markdown="1">       

구성요소의 강체 그룹 작성
==============

**강체 그룹** 명령을 사용하여 Fusion 360의 디자인에서 선택한 구성요소 세트의 상대 위치를 잠그는 방법에 대해 알아봅니다.

1.  **디자인** 도구막대에서 **조립 > 강체 그룹** ![강체 그룹 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/rigid-group.png)을 선택합니다.
    
    **강체 그룹** 대화상자가 표시됩니다.
    
2.  캔버스 또는 **브라우저**에서 두 개 이상의 구성요소를 선택합니다.
    
3.  선택 사항: **하위 구성요소 포함**을 선택하여 선택한 구성요소 내에 내포된 모든 하위 구성요소를 포함합니다.
    
4.  **확인**을 클릭합니다.
    

구성요소는 서로 상대적인 위치에 고정됩니다. **강체 그룹** 피쳐가 **타임라인**에 표시됩니다. 접합을 이동하거나 구성요소 중 하나에 적용하면 모든 구성요소가 캔버스에서 함께 이동합니다.

강체 그룹 편집
--------

1.  **타임라인**에서 **강체 그룹** ![강체 그룹 아이콘](https://help.autodesk.com/cloudhelp/KOR/Fusion-Assemble/images/icon/asm/rigid-group.png) 피쳐를 마우스 오른쪽 버튼으로 클릭합니다.
    
2.  **강체 그룹 편집**을 선택합니다.
    
    **강체 그룹 편집** 대화상자가 표시됩니다.
    
3.  선택 세트에서 구성요소를 추가하거나 제거합니다.
    
4.  **확인**을 클릭합니다.
    

선택한 구성요소가 **강체 그룹**에 추가됩니다. 선택해제한 구성요소가 **강체 그룹**에서 제거됩니다.

팁
-

*   모든 구성요소 또는 부분조립품이 서로 상대적인 고정된 위치를 유지해야 하는 경우 구성요소나 부분조립품을 디자인에 삽입한 후 **강체 그룹**을 사용합니다.
*   세 개 이상의 구성요소 사이에 상대 동작이 없는 경우 각 쌍 사이에 강체 접합을 만드는 대신 **강체 그룹**을 사용합니다. 이렇게 하면 **타임라인**에서 계산할 피쳐 수를 줄일 수 있습니다.
*   부분조립품을 그대로 유지하려면 **하위 구성요소 포함**을 선택합니다.
*   각 복제는 기본적으로 독립적으로 유연하므로 부분조립품의 각 복제에 대해 **강체 그룹**을 작성합니다.
*   **타임라인**에서 **강체 그룹** 피쳐를 편집하여 구성요소를 추가하거나 제거합니다.
*   **강체 그룹**의 구성요소 사이에 **접합**을 추가하여 횡단구성요소 간의 동작을 정의하면 전체 그룹이 함께 이동됩니다.

</div>
</details>

