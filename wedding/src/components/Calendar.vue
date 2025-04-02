<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 220;"
  >
    <div>
      <h3>오월의<br />세 번째 토요일.</h3>
      <div class="calendar uk-text-center uk-overflow-auto">
        <table>
          <caption>
            <span class="caption">2025. 5</span>
          </caption>
          <colgroup>
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
          </colgroup>
          <thead>
            <tr>
              <th scope="col">일</th>
              <th scope="col">월</th>
              <th scope="col">화</th>
              <th scope="col">수</th>
              <th scope="col">목</th>
              <th scope="col">금</th>
              <th scope="col">토</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="holiday"></td>
              <td></td>
              <td></td>
              <td></td>
              <td>1</td>
              <td>2</td>
              <td>3</td>
            </tr>
            <tr>
              <td class="holiday">4</td>
              <td class="holiday">5</td>
              <td class="holiday">6</td>
              <td>7</td>
              <td>8</td>
              <td>9</td>
              <td>10</td>
            </tr>
            <tr>
              <td class="holiday">11</td>
              <td>12</td>
              <td>13</td>
              <td>14</td>
              <td>15</td>
              <td>16</td>
              <td class="dday">17<div class="circle"></div></td>
            </tr>
            <tr>
              <td class="holiday">18</td>
              <td>19</td>
              <td>20</td>
              <td>21</td>
              <td>22</td>
              <td>23</td>
              <td>24</td>
            </tr>
            <tr>
              <td class="holiday">25</td>
              <td>26</td>
              <td>27</td>
              <td>28</td>
              <td>29</td>
              <td>30</td>
              <td>31</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.calendar {
  width: 100%;
  font-size: 0.8rem;
}

.caption {
  font-weight: 700;
}

.dday {
  position: relative;
}

.circle {
  width: 25px;
  height: 25px;
  border-radius: 51%;
  border: 2px solid rgba(var(--color-calendar-circle), 0.667);
  position: absolute;
  font-weight: 700;
  top: 50%;            /* 셀 높이의 가운데 */
  left: 50%;          /* 셀 오른쪽 끝 */
  transform: translate(-50%, -50%); /* 정확한 위치 맞추기 */
}

.holiday {
  color: var(--color-calendar-holiday);
}

.time {
  display: block;
  position: relative;
  top: 5px;
  font-size: 0.7rem;
  color: rgba(var(--color-text-alpha), 0.667);
  font-weight: 700;
}

table {
  margin-left: auto;
  margin-right: auto;
  color: rgba(var(--color-text-alpha), 0.8);
  padding: 15px;
  border-radius: 50px;
}

th, td {
  padding: 5px;
}
</style>
