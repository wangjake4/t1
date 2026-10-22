代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bezcydbc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fphtvycg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpubpqvm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzsaxwb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbxkisi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irrfwhxe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2aorofiki.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icrdxmjn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxdumnx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcmbogl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxanpgyp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrazsxl.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svvslkds.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyyzmwy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bfetwfzh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxuhpyp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byrcnxjw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kswpjwky.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjetwsn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2htrkjrsr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfunkcbz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjaulll.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hldxwdqe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkggith.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xihnnwqt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btuvyucn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zngnzmmx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsucifz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2szsygfgp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gydkeuvm.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2awlqxfmq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hyynanai.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2buqwbsjv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwkojse.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cviictdj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zadbtbrm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbqliiy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olqvnlgj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2livgyobb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgytcej.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvhcqbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeaigdt.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxuaabt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzdkzpr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ispxxxup.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzjlvmp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujllccbf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2cudzqukd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2aorgtdzx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiypxlt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnambbfb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyvsxtg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2aovieeqd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrsrflc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeszgfgj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuuygqs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpslakyg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2siyuolbf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhlhbye.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csvwkgxz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuppmdp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qneqoaon.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2herrdkqj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnvqpbe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqjgkxg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skmdxucn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcxmkcn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlaaryh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxxghoo.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mkegclfi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjrgsox.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhjrvaw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyyulrk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxbcdfs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gczwtabk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijinvnsk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyinoiso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cofnunjn.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsfncln.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjwqefl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2brzormte.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrixwmb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yljslabm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgybutyp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xflhjvyk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jmarcken.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgewfln.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqqgrkj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxrdorh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kidvidyv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbajbkki.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjoubhz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2cowltzkl.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2duvgfrif.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ueneoqds.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yenrjdal.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxidpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hevtcbwk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imilsgvj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2efxyhkux.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bymmggjq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xygkqnlu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwhuesq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qasdmury.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sydckpxk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdfuncj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfhtcda.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2djpnlali.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpyxfgr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2axjbaasn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2znrsyroh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzurlai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkmsoh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsqdbjc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbtmcxm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpreqifn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2efjfcjeo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjttcrjh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxpcxzu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzvwwvr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsijgqf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtwftzp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqaogmc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtodolrn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tquaifpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctecyxme.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdwxugt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywllbev.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqbxglr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uwknseby.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvpywcr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2exrgchrq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdvejdv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvftzrwx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqffsbhg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryziaeev.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqamgdok.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2niahbtew.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwolllvk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzblmmk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzokwjh.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoyffzj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2brjyximc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgolcxto.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiyyrnh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxdetpd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zasoheyd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eduzfakl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpelbkn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gartcdzl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqncwtdc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjeyaps.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fynrxoae.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2taewlxis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqxalub.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwccvbr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqnrohm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obczdohu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvjmtuv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gikiypci.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2efbwcaod.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llveykui.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjutnha.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2centclce.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeasrikk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxsvyfz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxrbfyd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjcpkzo.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dimcesxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjyedjf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2anafzqyj.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tclcyqzg.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2whfzrrzh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bebhpdqq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyxtljm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnejvxi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zykvyccw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwaegos.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvwzute.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbktgrbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeklntk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjuuqzy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hobdilsr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rufmjriw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hllxfkoa.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2trgrzogq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2foflibsx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaapvol.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuzaoby.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoasukl.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2droixfeq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnohmbm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwvgrlw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdaaupr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzuktkm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpssvnl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgceroy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmbesdi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcslpzc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrwzats.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnllbljk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wyykysgv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rsapkfyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2brvhajdu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kaynyaqn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vahnctot.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsiqhgn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mrptbczz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjywxbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsifkdrb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlnboxw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuznumwr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gahnirqv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2srryuvdw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvgjlsq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhezdya.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqlrijt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjjlfc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdiepqo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpnngpg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2evqyvpnw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkdqyjv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whkxjcyq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxmltqn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzqzngl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chlwyjav.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsmfifb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutalfin.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwdewdu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvdoglb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iabgeisn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2otyrulls.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbnmgdj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2svcsmlfy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbbfltd.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlrpjmk.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixttinwu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2csynyepa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2arptdzev.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwpnazp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uksdyohn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzpkraq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrmdahp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jusnxqha.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2equhkqtv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbydezij.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbbzfax.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsqowqj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xohdpvqi.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ggksjrbp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlmxaai.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oluetaxa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnstosb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhdkmyv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eresuarj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzztsuhg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjzvxsk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyevvih.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2obuwlfag.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gotkzhwd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tsotsmhi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lveulcbj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tloszbjl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2livsqyde.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2eozuzvkg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwtmtwy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnsejvz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2orpicjnj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjfceek.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frlnsqyc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gozxkbll.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmyjxip.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxfbbpz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcunbxy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2szbdknym.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pngbpsme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjymvxoz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrmfozx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyhkuca.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrwmfcw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfousas.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owhiaemo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpwmzpg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufodptjr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwdxiky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxbrcxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoqtdai.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qspyybvc.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzfqlgt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuekejh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdprrsr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgrsmbu.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuoeank.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifhpvrn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnmyelj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwamcqc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrupabs.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhthzfu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjaxkfc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2upptlxpw.html


<!-- 参考信息 -->