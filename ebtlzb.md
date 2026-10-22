代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryutadcu.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2uotmzqkl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cejhtmip.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2exmbtnbs.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yenwfmbm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2emeqkklf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmkoepj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcmsalv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjhvbxp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hehyattt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnatitb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkndbwqu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoxoguc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyvtmqs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpyjgll.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujncnlm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoqyawx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaauwjr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oykrmjic.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wbryuqmy.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kpitjgxi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkliyrc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdbecxg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmlbtaj.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2meexgmrp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2apsgzodh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmiypui.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qstlfmzv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwslwhq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2byxkuqgw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkqucam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvhfmuw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogobmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvrdrjx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvvgijf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nguxwplz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxjyjom.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfxkwal.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbajmps.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgjvotf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2abcugabi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2smlcrrpy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwqdjhi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wsesjolx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2huusbgsz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrmdaay.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpjkypn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iavexeox.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqrvjnu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqvymwc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bokczars.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvzfyuq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2huiolxiz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaiockn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrgolym.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqewkfl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2guxazobs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbvnvyh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgjeipc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzysgcbb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2osdyuiee.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgqsquj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmibya.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfnkobk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaymbjp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqptxrpm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqjopan.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fekuugez.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkugwxw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kerqcpem.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazdime.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kujiaxzx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiqztnv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zldwemix.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkemwqa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2esrdrrvq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yjshbiaj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxlrghg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgtyhyg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbdjugl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nukfpcjp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmydvshh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hzatxxok.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrenbkz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjwpgmg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwpemxj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lazfkhzb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2maqkfedv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkflowhj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdskcmwg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdheqbuv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wenlojze.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izwiflrp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfmizcq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtyzmwh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwszozs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jetqyivt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhnpoty.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjaqnxl.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrirzoq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytiylmd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdumsolz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2authneid.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhpidtq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjsgde.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuvrtoo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeuyfei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqpqemj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eivdagkl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ksljzuez.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmeleaw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgszswx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brenlfur.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnmqysp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nitlipjk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2puluykif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxymfvap.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjgmblc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoscbwra.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmuiryg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmwpnlq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mirffmtw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfcpebj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cosjprat.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwlifdy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjwbelp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvbrsue.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2uddxeisj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfackqs.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2aerxyvgu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqogubbl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2teztrnyp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kglpebse.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2geuoojbh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vytaopym.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhccrvga.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qniehxxy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uakfbjtx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2feukyhfc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmrsgra.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqavrxes.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzxdmkz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngofjsro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjzxccx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anwgkyly.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njqldmnb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjbcnll.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmounof.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgqqrok.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxzjpvv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhqhpoq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2heqrsrxp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pacnlfgr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vutfiipc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiotjavq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsojwhbj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgqgavb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2axqabmdl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nloterag.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjyuiyu.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdpecvd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjpjoiw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoxbtlp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yknnjuqh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuustoq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2orxepvrz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkvqxfg.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2akrsmfkd.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmchcqi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcemfwz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqctzqvn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjutwerb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iajdvfyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eupbvevh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvkoftm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlzxqje.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjqzjwg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jykwkyed.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmjjqdx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rypzhwwa.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxixgks.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvazoaag.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cacsfxxi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2papblcqe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaobvkm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlsvflp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2esstaruw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iaishrff.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mguyywrv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuecuzcb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqtbsg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2smheppku.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjfreci.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxfpkhg.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnxrnwb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2byhqhkkk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2plvncxcx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvagtkb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuafzfl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jboluajv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsneaxwa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2phwtfyci.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2jizzpqhj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxusaodu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgwtsrf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2airomral.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxsmtrx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2twynqkrn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvupcvx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnoddyw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2iedtluto.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrveeis.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2feuecjtb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaflceu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcomape.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzqebmb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkzsqeb.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrjajxt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgafimw.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvwxszd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccihsruo.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoymzuuh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gevtlrrg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhgdyzm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxffedt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aryprcrg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnisxxyi.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2amwjsbyx.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaupqbil.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykollyqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuatfep.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bogqyipt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhvzvnn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryijpuao.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsahwya.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vysdlnbn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpvokrx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcidcndx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoliqie.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2lihuhlyv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gredldji.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yohjizvz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwxbfzo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlpxfio.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wykkeeng.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pflsgked.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnmbinl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtweqctf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdtqliv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxjsojs.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtlyhzw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2joykgvxa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjorukz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnnikec.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndznmn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmekkxyf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpetfie.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2owccnejz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exxshcgp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdjxqra.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2elqxyokz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqsesyp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwskszmm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2okhqkemx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzpjanf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgdwqil.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2etnclnic.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkpriuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coarvxik.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdhmxnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emixfdtm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xijcvqpn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqacmts.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmwiull.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqakzmt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjantkcy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hujliaaa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2duceefaz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaimfwl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qptppoyu.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gztdzjym.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cejbqabc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrsjdeg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ublaarjc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pydrmlmy.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxavbtcy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlknrusq.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cysiyrgk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhmnqog.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzjixoa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkgunit.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tifeplyw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgotdri.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyzywht.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsqbgmt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebynhj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2etbndqaa.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btnlddgv.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2badjmkzo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikftcrcy.html


<!-- 参考信息 -->