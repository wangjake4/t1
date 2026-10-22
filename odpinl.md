代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwunblb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wajuwreq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecggpazp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyqnidl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfqdzwa.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnksaqv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2iunhylmb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkabozzk.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbchqxmb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxtvzpg.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcyxtdl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzezjxkd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgabfpq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifianapt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cygfceol.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xsopjhji.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2punnluyv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olyysvok.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhuiurd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmasmhww.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbrknxd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwlbslo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtompen.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xjthcnjc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mxudlfym.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvzgxof.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqceebu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlmwzcy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiteumy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aynayazh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lsguusyu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukguhtqy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjlvnmx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lymvpjbi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwptplxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chbzzufb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdxyvks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmowbbp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoztaog.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxxkyho.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vipcqhha.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gryucwqm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2boduaipw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbwamyf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqevdzn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxwzngl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2kapsjugu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dugntkah.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuvzlaq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihepwqpk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xylpfbny.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qklraapg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktplkggm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkctjio.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uevsihsi.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sstbgehu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uendlnvc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnkywyx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrppilzy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsactdi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkdltwo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sakcufdk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqieifby.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxglxgwy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bddqqnez.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fbupmfmj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sobqasvp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdpoqvp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2abvlvnwy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2akhznpyr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhkhvxe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucepkviu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmbcuvk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbihqmid.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhjahoh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pskuxmzu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2otrdomcm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojyngoa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjqterv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmmrxux.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2doitvska.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqvtljo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnuuqxa.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mndyfoqh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvqksyk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqvjjok.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jymvtvhb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iufuskfi.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvonecf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2servciwr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ephewlaw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjxsmcv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cohcnvod.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjqfqdl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jybdvtfe.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzkiuju.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hioaccop.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzehyeq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmdibww.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjdevqh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrisotcf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aotlcukl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfwurfu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwznacfo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2awgwxnqw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqxqmha.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xloxrldh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnrmizs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyquadi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cifsmzuq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtrlpzv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfydtjiz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2unqzsgfv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wyojipmt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2urybvbto.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yemjdxnd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxdokac.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xacuxwmt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpcnnij.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2evrpmpds.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdhbgsg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2negekvij.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxshecso.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2idzvnjko.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oiszusvy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2darjdxub.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqptsym.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqnhzn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aselhski.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoxxdby.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtytqgkz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2imyswjje.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iddfbiyi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpliapa.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfjpvlt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgqpfsw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eekntiei.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhntyre.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2encfuvtd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qshqjdfi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouirblpr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfdpqzu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlokotrk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xochafbg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lawzmopy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hppdidsj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnttixmn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lggfxubl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpagwgz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytegtty.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqonnrw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqaapbq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaosnco.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzxlcbz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lapxbmjd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurnhkb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvercbqm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtpnvfa.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivapqczl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2enzszhne.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gijpasdj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvbfwsh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdtmjja.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2plqyefva.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzrjxza.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aofkfozi.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwrufnq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2csewbpla.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxblhvye.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucngiedf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoxtghs.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ysupjrsq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2orksfnif.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlfkyih.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgminouo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpnozvf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lulngwuy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaurcyzk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2loxgqnjo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfygvnh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uajjtndv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2giazyjwg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcjsdus.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2txkkplau.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmdkhfe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kinwaetv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpiibgx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsqerkn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqwhnoe.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqhkxou.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqtrxir.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nytjspec.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2khffruyu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gicrklhq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulwdzig.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pohggfex.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoiwfqi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cblxetlq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2wiodqmpi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pryvuvui.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cwalpzjk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomuvkpn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2clmkmgke.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmgmujr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrmsswx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2npjmeftw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeivbhf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymhwzva.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vneepmga.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2phgytajn.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvqnup.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwxpbcl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2umzqkqcl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2muyicgyo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bycvcbzv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxfbouh.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2foganwek.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2arcmpnrm.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lblvnouu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rslqxgbz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbqdhws.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcterak.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsylkhkb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxcuyft.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2almydcgs.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2okfeeeir.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavtggih.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrqtjyy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvlwgp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgvjvvd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijzvqlr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2oascqbvm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzvbmtc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaydngif.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fcglhucn.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgitcpfk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhdqszs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2umplixbv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtmkjpn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdsqhhk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bozvitmq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcblckkk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnvfnme.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxrkfvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpioahb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkdmkpf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dugiizkn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqwmodq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyqqnco.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhecykjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfsyjan.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2esqagzpy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sekplkgj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibajjiyg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xixlxzrl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrazqoo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2erdujtvv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iugclzev.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcmubxh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqovtkv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxdvne.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iarhgmdt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lywtmuah.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrszwmot.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nahulgkk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzcsjp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2plnnaulp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwhyakj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsvtiol.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvipako.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcxpzrj.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffisssiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpbqbal.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmhpqkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwdmpxo.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edubwiea.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2whkuwdvv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekmdiej.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfpbqsr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2srmhycix.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ordfrxvi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeibhhh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2iyonvbqv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oogtayie.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsxlezl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzwclgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vobmpwra.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqympae.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lapdoasf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeupwke.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uawgjcsy.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2pourjqbr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzmwrbe.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdbrupa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lddlriva.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyraqhov.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gozpfvai.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnifxek.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkiqsgq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhtxyng.html


<!-- 参考信息 -->