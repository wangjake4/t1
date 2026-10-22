代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqypjxvn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2klkkdnka.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmxljdl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2waranxpc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwgupoq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjwuoro.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtxdbav.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyysmkfb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkolptmb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2oglntyan.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2igpuqsfq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qupqigfi.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlkwkxt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2peeyater.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbfflsr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvtomti.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwwtcoa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrquknl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxnhipp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujleypay.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kehenswj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmwisgo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rexdikth.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2miblkiac.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkopsrc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opuoafgr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xooamvxd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2syhcdogb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxbmae.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzbagjr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2axnrauhv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfhieiq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2owgfsygi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2btglhgus.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuvucgn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caoillhl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lgophksn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjamcpx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phkbfzub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeosxpt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbwigld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmuhwgj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnulpgc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcmrhie.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2edhnvbzr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbgtrau.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpivopnb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uuflcuqy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqaqbsc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2twoabxgc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaskhzp.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2woexutby.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mllwqnmi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdifauk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfexijm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaeuykd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arfybmry.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqhvgng.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2epezugmx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhuiqqj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2klfnzmxy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wllfmeyr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlguibda.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zoipahid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2geedfnpc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2otauyyfm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyllbxez.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjyuebu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2arinloxs.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ermlbmeu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnhtger.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfskkbdf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmiyyhp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lermouty.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eofwlgxa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeojwfal.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtsieex.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vizuncvj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyknqcn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gucrdind.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2twmbtlnu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeobqpu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjzdbsz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2efjqhqny.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoxhlns.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwwsjzv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqejxmvv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2umagtokl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2idwaqmam.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wandgzrx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kpodyqmf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2chkkgelg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaslrwj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwyldxx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhnqnwy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjlrlig.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqdipul.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrsecoe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvvbtfw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nomieqvb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaomseu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pivxblhh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2riqtutfb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfregsk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwvfnrw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qczyjwzt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzjdbcv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2glcqxcva.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxkvhln.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2amgtoavv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfneizj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkghaif.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2venplwdv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqaynwx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2npkkwqve.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqxdxdf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjoqqfb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvwwsnw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uenbliyy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwojddux.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvvlsif.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiovqcy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxceuxrp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2thcsgglm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvhjfsi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtstgyfk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrrblfk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrssnocj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnvsekt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsxqjda.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2deztbrky.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtdlqy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aiucyhpu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkqdbfl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvteead.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2waobnakr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mherayhh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iilwhrlo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvrqvcz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbaarbn.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvyvkky.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2arcteafs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qthctkrt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhorttxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2onnqrvpa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhhsmrf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxivvgif.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifozxfgb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhascwc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkedvffe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywddzqlb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoshunw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzndgrce.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdczfsqa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwemicfa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lucbkmmo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuecouj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzpqbbi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqrjivl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvttqlrl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2irzopruu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxstytd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btjtucah.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlneeabn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2maghvkig.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrxymlm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrtuqwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tipbswmn.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrebgfp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2prbysgmx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svqouzfw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2baqeovpt.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oojnliyw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgatvjs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbgfduy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmthvdv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaodmua.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2voudlzgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emteepsq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsjxpwc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgdungs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2reeozzee.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggklidyu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wpclznly.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2grknchel.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzxfgeo.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaudjaa.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftwmncg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqkhpni.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbxwmxw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxsynls.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pikttjpi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzztlotf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gduaydiu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcazlpy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eycjtmxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqrwgov.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbbqgqp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnpiwex.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2huntjnph.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2crempaig.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xixkqkcg.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqqgnvn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwhoaem.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmuabri.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcamuvu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2urpxqyhy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vyypuypj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoajuis.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2svodgqjf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwsszwg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexjpszc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwtzksi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdugulb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2useqacbx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqdqddq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uizvxboq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrsgbyx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvplkzpb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnpzprr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2iglmpbyu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2krepqmab.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrjsoil.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jshrbshv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpccipaf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjgyrcq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrnqhrv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfuksk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvamlfn.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2npbdfqtl.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfqecdq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2itodkvff.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmvatsz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkiqeos.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsbqnwa.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2xjauzyay.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwinjdw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfbuonk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlizthr.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvryiejj.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwmexui.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikatoysq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcpwjwt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vasgffyg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qynwskhg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwguxuq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2luytsmdu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkridij.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfuvdyk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqkvfnh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2edffmdgx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srwsncyj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxuwrn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmtccuz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdmjeou.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2omrtgcdo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydygtrdq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnayakve.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjvmuki.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2npzljstw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xmarxwox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbrnsts.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdftyxo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwfvqyj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgryzasq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkfayqg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqntxfag.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgerptj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjtyrnn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwlbyka.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oetmyzsp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2djfvzmws.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvyflad.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdtvnth.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2egphdhtj.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxygqclm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saivvmqd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwdjzoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbxculv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxljjfo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdxmuib.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkeyuuk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdkraqj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgeewts.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tezwxkqy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouckdvuj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkyxpbc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvabqeu.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apnaandc.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmlvtvb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdwbarc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdyctzn.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2abhguocx.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrirssr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfjssoc.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqbadlp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuasynv.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcncthxx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2htknpbub.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqznpwr.html


<!-- 参考信息 -->