代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqxmqjh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2quvpmuch.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvtfnhe.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcozwxde.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khyahiib.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpjkzeu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhdhple.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsorjao.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpjqbew.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bryumnre.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiuneqz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjqagfb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwssbow.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcivonq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjdkhdo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmmvzev.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnjbsnf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnzbkuq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gflxelgp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwmpvme.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyqkzih.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuizass.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjbemji.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2idzxtwsh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gibovoox.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yipbvgwk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyugfvwp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2beetjvsy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hadoqdjh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgrwyus.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfmqslj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiiiplo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jekgijpr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtortazy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cocjzjjy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzpcphu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgtopjh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhudzom.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcrscpo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2besnjexc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2brbydcly.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnlgshk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hmenkapq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jihiwsxx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpahlpyl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2itwwfmkz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2sphluomg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oegiqfwt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buuawmgg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhxqisi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2syaemojh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuumbevg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfikqlz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnvmrrk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrewkhyp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2guctvgnx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zobixxrt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qazcdipb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aopxeqyy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgdbkk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtltqh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkwvtno.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhookoec.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xppjdhna.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqxknuw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tuetdrpa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smezfpdt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2alqudkdz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zminipum.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjlgpfz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhvbitt.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpcmnxb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbkyzwh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkfqcbk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmrsfcz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nriasqns.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2txtnvpsg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2fclmspqx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nofwntgm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtanlwk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcebhls.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvqkhil.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppehqblo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fevnlboh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ioazwwyq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuryomeb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hiogtuyt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpiaqlt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wenerhme.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaadngf.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuzxrlb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbaxugg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxbsds.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2bsitiztz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tziapiqd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmetzwe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vsepxhyg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxdnmur.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikngawhy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmnjrjw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahckzxgj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvmylvq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcpqnin.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sytjcogq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tiurdmau.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrcxlyw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcdvmyy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpxxexw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmxkrgx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsmvjig.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2dnybsnua.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqzhbfm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpwvvqd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkquhjwo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zocpsjvw.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awefnzov.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2onmsxfmi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqmvlmv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqnpehw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2thbzvsbj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjsreql.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xthxksck.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlriuym.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfdoveh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdinlcnr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpptayl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywitmhx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlcbokk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeatsfl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uebthtaf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdjbjjj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2uavrvjxt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vncpxjew.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zigxvaam.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfznuqez.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrxwauf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2olyqjkij.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2imyamgmy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zwktuoxb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwloyls.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2anqomrkd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhyykpj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsizqlm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrbmpyw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjdubci.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgewxdc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrqilum.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2hcprifya.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhoypqx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wyejbmgr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xathnzzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiafvpl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtjsjsj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyphzcsz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pstagmdm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2scsuykqt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaluuva.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2byeodjot.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xufrfeft.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ullsxcxg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2howhrgws.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iylnkxpo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryelqqbg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llpwwptp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhntwmi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwyuuuo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhyqzib.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmsokud.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnyhnpm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfewaitl.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2csppbzge.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnsxsub.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwxstcy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yucepbud.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkkldvc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcqjvkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbdqlef.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfwwljh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nynqjxyj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyurykj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pwurbkpr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxauopx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvetenku.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystrxpki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2spgxsjep.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nulxdymf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfcynqc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2abxkhsax.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqemvbmu.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qminwcnx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nphcjkia.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhcmajp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owesyueu.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqbyzpz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzudbda.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyynmkv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoaiclp.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pciixlwj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kavqxomy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfioygo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2goxyftnw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnuqtmj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2deneximd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfumcqe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lpniowip.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njbpctab.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmiagoc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoukbpbq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2suradjcd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2grkuqtuo.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2susgakpb.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymebcn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzketeft.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrmewtg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2udxvrshv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jshnekkp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyfrnhu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrsulsy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvkhqry.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2phqocupa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdxdkhe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ashahjac.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpckcjh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjnpuzg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2scdjognz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcixfeot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbxszri.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2roypqxnr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfviwdg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxskhtcd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwfsmco.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgnjrgh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiduzdem.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2crbcilgv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgpedok.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzdkqkj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcigjsn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvrepzy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpvppfh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadyrhxl.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2zguvxohd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2jujafvwa.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwteame.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvvhycz.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlsodly.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrgagrg.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2axmwliwj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2idlzcjoe.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2igrngyoh.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdlnkvi.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfpuftt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyucepf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiytrcz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwuddyr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oegvlszq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gimtmorv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdltgrv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwxwzcq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgyminy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmafcp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwkkfaa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiknblkj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmltstf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wehdgirz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkkttzg.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyjnvon.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2heapgzwa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftiysmq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdyiwct.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oleehuja.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mawvqkuv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovksxjn.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpaynus.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpenwrh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oemdrhqu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmscjvn.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rjccwszy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mpovztpt.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmwdqoi.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2chtsknqf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2unqrqhir.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfodilw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnbrjtp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2nblnyjhk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cynhezdw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyupaoht.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2asdyttgz.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tefzfbvr.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2sllmtznf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naconvwj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shcbthsn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqvgtcu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsjacip.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2obxodboa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnpqsyl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2japdjecc.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ufesaakd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbstlgx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpwiyvc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2euefsdij.html


<!-- 参考信息 -->