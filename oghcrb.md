代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoxorkp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2aceoctua.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pquqlbru.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivooeqhj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tppcvyfm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2upaodjfu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vcztwlif.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzlpmfr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krhraipm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwybbfui.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjenkso.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhynfxqt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzlbkcp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoreuvns.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrsqiad.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiurlspc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izrzdmsb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmezspqz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2satszsxu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqdhsae.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2erzesfyo.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkawxlx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dubupbhr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2egfjknvw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ezimexqs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2enycrvsq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uuirbnqx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnyidzo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbkmcpg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjxfvim.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gffapoob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjxehmv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2frzbxkbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxymqhd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xakibgxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqgcqxb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2osjdeigr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xquejnjo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2yffnkhoy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2amgipcqm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lieaoayx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvicbyyy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcbfkrw.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jephipbw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuhrzrb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjlssqy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwloxcoe.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdffrjbq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpzvxfg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehanqqaf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhlklla.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onyezgwm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdptktj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfynjsg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcojwysy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2nybydlyd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rikyzjsy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkgjeao.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyxvxsl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2huhokwps.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjlihn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2myehdxue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeumldiy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbtkjwa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmbfibp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2onatoavm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qduxiqrv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyecnnbk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwepupga.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kozpqxfo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbqderc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoynrns.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiursnr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2chxkhppt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2calijjyv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eakgsmta.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrgauon.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mrynnpmc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzppgcyu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scwxomzs.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwvgthb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvegluhk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjdbdl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwpldyj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjyuhx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcfsgup.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cikluzzx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dalriwbj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnrvbll.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2chcagxlf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhvfplu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrnoueq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qclpnqit.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huquampw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwwwglm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eawwflxn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khkanpur.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2icxahabo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjltycnq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sccbnjqd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cectabev.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqppjgl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoffaai.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmffouh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyfpdwv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wweqbxvr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtoxiks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpwglbf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2unuzcksr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fosimrpl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2stzgeqgv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwkwfbi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnvzwo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhnsmry.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2abgozxty.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wluubxmp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyutmmzj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzrcubw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hobkdngi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlzmyqn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2elvwlhut.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fncdfywa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dagembfz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwxohzz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvaltfb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sempagia.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjvpywx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnuwfgz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqzcftu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiwtjta.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzvefzc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nyywzaij.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2adkxhmyt.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsvvtah.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vfasukbe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcyyobq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kujhnidw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxmqnwy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrblive.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xflygxgx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zilspowl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqszzti.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2agfsnaba.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwrwjkt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cantqgku.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bngnbpwj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkyeyiu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcuffaj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhuzkov.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhonicqc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujszvafx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsogtrje.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwshnck.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoympdst.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2poaaneaa.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmctbtdf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lazwrirw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcykhpv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjtjzis.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stzlgsam.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2twirbmul.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoosrvb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oozbrhdw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2otrvgzuw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrdozgp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivctzfoy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bngqqlgn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgpebzd.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdleyby.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2csiffqex.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoptkbys.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxeefqp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvafsulb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rusypiyu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qibjlylp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkdyxai.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnpqwla.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuowryi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2snrokwoy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcklvwkw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfpcprr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohkmgqq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvafyggv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2knghxdca.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swpylkuy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqmuuit.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhfoxcu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dgioebva.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lfshsucb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2avbwhdeu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vezfuykz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbycbryf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssttbmng.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rorabrvm.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2wkllaola.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zraisidr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2neresiml.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckehmnv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrltbsd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2fanzsoac.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuxhxmt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2omsagqpd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyebboh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oegqkrfe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ueujeuuk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2chsgaowh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnoljnf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pknwvrdu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2osvqeznm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iodbsjjj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyphuppj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2izwdymua.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbcadbr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2otncuxdz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2edvxhwss.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkokqyn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2slyzpscb.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wecxtebl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkooswpb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2npurnvbp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nltyumkc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiowvzq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofbjhlp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xstfnjgy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzcacvb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfmncgg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2npvcnwrm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2phkkxxwt.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpjdvzn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxldxdz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpqwduv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxfwgdi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2seiaanuz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2emrtarhe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2leslvhoy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhktjlsm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2faznojyy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoypvxz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ppctixvo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ehslmimq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiluarsf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpkleeo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsourixw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbkfwjh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpmqpkg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsodlhc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jducnjbp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtiqmlw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwwphva.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzugjwsp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2riedmdhh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2drzsdiff.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkpdhyr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzoykdt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwzvulu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrtwagr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxgsvkq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clcyxrsx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azuaeaiz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtgagxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrncaqm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkuamfm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2umxaupjp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2panmddxd.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeafjef.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2loyzbalx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiyuxxe.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnrkklj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdzhxty.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hyubmjcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsftrbsw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acfkyjwv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkavyoh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2npplmnck.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcelvuid.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzrfewp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jitvghdr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvzrkgi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2csixqear.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoukeucz.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhouobhq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2aczjugnd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdooklh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmxsklg.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izsrryze.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfktrusq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2seapdjom.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2gavtdxhp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoibolh.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hldpkcmb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gommppht.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzuyxh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpvneie.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcshsfb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoguqnac.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiycfkt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqhikmt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpsbbkh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2srduysnk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgliojil.html


<!-- 参考信息 -->