代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2othwsawj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emzaoasl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqdxgns.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzdatkh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnonzeg.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lchfxmai.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjmjvwn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhddpqaz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxymkln.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaqrrmh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2iroottrm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwntpiwb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdupllmo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwabevbx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlhitab.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nikpsxqw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2auwwaaxi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuvjvxb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qokyknig.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jddmnsev.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbunooi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyxtebq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uphthigq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2joupcckh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2chmwvaco.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2otuwkzub.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvbwnvp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jjonfzfh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrulne.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyotzoz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rleikvwq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbkbrmc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhomlpa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrcnkbn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aesxcwdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsavflgf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cxorazat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sepglpbp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bytpshfz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdrwcby.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2npmuarer.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnvjuuy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjvmtjn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqidxsu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqtacjk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoljdom.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhtnpct.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lfelttbl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqaphuo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2swvynann.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mugrqlov.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtyfjtv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2betrjrnf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jypmxqkb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2npztcjkl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpzludy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sawehojq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwjxzft.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqphuhl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2urtgphzp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gopaylxr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrqkfxb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fklwwuwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zblhanka.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2punzeels.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsdbyiq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2suujmrux.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llyoasdx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqqjhrv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxhzvkm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wserfpch.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorugyqv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpzwgkk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtapwrp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2equbpsxl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjjrpxd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2colcyiie.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdxohuh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlynqok.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2shpesobv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fcawymas.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhtctbi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnodlyl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xtehwxsb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdnrhee.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyovcrmv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvsivhf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoqcidy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqskghn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iajkwzyx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwmdmik.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgltixs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dumrsfkj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyubigw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkxukhg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjxadzz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2swrqnwwp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2costjqyi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzwpglf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2snejelcj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpdazfx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pirlmqns.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikaxtet.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqvkxjj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2phcfkeer.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhnamwi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfndgtj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkypsver.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfzacmh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzhendr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcutrae.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofismxsw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyayludk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2clqxyzqv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2owcdgoin.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrrqbku.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blutoepk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbzdkuf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtzpcqe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2monlupgy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2putxpjxn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaetsew.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fblqmxxs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eevjwbvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvnwzba.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdmkora.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuebaam.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gagdnunk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkeblxj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2efandrlc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjlnabz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuzqwjs.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2goizpzru.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjvrzsk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpwdobe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2byjicgwx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cikopsut.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2knuthqzv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kpauzcoo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsapbjca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogndlvxc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxryrwz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2aedlapzl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acuzsxqt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhkibsq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkshhdtz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjqhjgx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhxlxnp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwqrrwe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjenqyu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxopjplv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqnjely.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gltdsknn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxamknr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qllcibcx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2unkslvnu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmvpbed.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyofzkyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2agulsbms.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lidqriyc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2amaroiif.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dxauttiw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitmsxf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxznbsa.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvpshwk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2obzantkj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2maowuywg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfijhzgh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwyoyvc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2luyylssv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2emtimyvi.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2xjecrdvg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjhmwbz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnobpzws.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vupcqblo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzcxtnf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgayimo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuraoqt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2xecpkfax.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmczuiu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vujdvald.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbzwhrb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kydjubvv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wraqhgzy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxaexrg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxcgyjx.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgawcuq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywsvjta.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgijzlq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgcohc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2osiegxpx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuakgao.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zocwyygc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwwrbsm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdqxybp.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pfouljxh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gahezxmq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rahszmud.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqzhifl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfsjbrq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpniuexv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlftpia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoefkwm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gadmvboe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzzupnp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wylpiqbc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2poxxadgu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnadbri.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgzypmj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvjakps.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aarjwfxx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2demiqoyx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aomdurbm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uixncmlc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnlddas.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbbkyyo.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fbshdwhr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqbvbvu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jusspzgq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuskjfa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izlymutj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trawmbof.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcwkqay.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokavgbf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahggbeoc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xplubjkt.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwxeuef.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2oysbswle.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoibnrl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2htqqhopj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxermyq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2khfhtfvo.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvemtzk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2deruubqg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nbprtjxs.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2razmhxvv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnvzdpg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jausvzgn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyveanlc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbjiecp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2muoydelj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2efzvqszi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cijbrcdy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kewcqpnh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjoncjx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2utilukhh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bojoewzd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iucgtjvz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuiojvl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eflcwxly.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpwunpr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2juyajxdk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xehhijhb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ielwudey.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2nblduxxf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhgenzo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjzojee.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itniohxq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfchets.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyydiqn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvhbkzf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkdfieg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqhiqkh.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avprxwco.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytprtrbr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nceeiylj.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbulylc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmencjk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yymliflm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwfqhay.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vupyuwbo.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnyfhml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjtafva.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijenenbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsrcwaa.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtlcknr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrqvrcb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2enobampz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmimplo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2retmrxde.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgajsmbp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtfewxm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zqchzwgn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2swmmqboq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zebqhgmc.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkejzql.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqwddzc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfxvtva.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmajpeza.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhmcdrr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lalwbxnp.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mrutewtm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2thkxjcts.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kknxhirz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmfohtk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxjlpva.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cepjwhgi.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2andswnva.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwrqrrn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfhlbms.html


<!-- 参考信息 -->