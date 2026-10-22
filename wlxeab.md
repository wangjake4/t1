代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvqoiiz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjryada.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljequcvj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnolqvn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgmcfhj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vejrkrtj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjuzqer.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmefpkf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwkbivf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkcuccb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2feyktqmv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kerouteq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2slzwqkcd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2yffmlqkq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nucppzuu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jukvlrwd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhutenkd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2czghhrcq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjlobcc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbijft.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tttrjwge.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2iershvjj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwmiwqw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2srgnonrc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqaxiec.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2anwwaqfg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hksarlkd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxaoqie.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rminbgqz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnesvb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwujyvva.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2czvepgdo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmcxhjb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnfjchr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeewkpvx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdtppiu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwwjrpd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwgpzuc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgeoxol.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjojlrlh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxowypps.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2friuimir.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oybjyrnj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rddcgmnu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2upvyclaq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnkojpy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoglyly.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bccbkzpj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvrhkgt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bikbmfok.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpobzzy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkpoodd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zseoppyj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2agltpraf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxfmwg.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkuugxn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aphdpfya.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkyylir.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrubedlz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyypnwr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmxmkbi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2velevbpo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipndhdqn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2keuyfdej.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2riozqyhy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdohhsl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhsdprw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2micbndtl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicorjp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfckbfg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnevxdk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2trfebzyh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bytlwizd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2puxrlpkf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmazoot.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yszbnwvh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwajqqv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2muxdrlkz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxemttm.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2iatjuxkh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hihqmlda.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ncndxarm.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqxiqth.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxabofmk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wstalyxl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcajglji.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nguycnsb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjwsekv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmcfkxd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2rezwttmb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pturfuno.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjsgdzc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mklitefu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsplcgrj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaljcqa.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuozudm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzfukpf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqihdsw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2exofvgwr.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhcwdgk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xffqtlfu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tebueiez.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmjfyii.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2eedpiioc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiyilnq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgirsibo.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycidpyjc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qllcfhqd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2blzajutg.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrexbtlt.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjucyti.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nynlxqqi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmdlovn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrydkzk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vemyfenc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjdysxa.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvrdbjy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtfrofy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbbbmgc.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbajmpah.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjnhvkd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pejpgidd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvbfowm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrppxrlw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkmzfgv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwntayx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clvwguos.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjzcqkh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqtrakd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvqbgem.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tugyytff.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2trxpxamw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfosvjhm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpnqipu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdlsfva.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkblaoy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2etqjhvcm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqglybzr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlksbkc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rorgmrzt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2parujsqv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uehqaxqm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dziljqyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhibecu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nltnioqf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgceqlja.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpwosgx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsrwnkk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzfxjru.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqdufxf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjuigap.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvcfoax.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohphxrac.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsmhsup.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqzpsxn.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaquegoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmenktiw.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoqrlwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqvpkvj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvemdoq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2enqyrluk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxanqda.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiibkptm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqonmji.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwqiwar.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfjesqo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2smykvvjw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2luuqowhk.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbeezpr.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fujmyhuy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2autmswpt.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxfqmvh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzfklao.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbjufos.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvzwvdl.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uajxkcvf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhjfxoo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kzexzjsb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtoisdm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjznmhnw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwedjjio.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2skwvirgj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgorloh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kubjsvpz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpdndgg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sagyvqav.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpbpnmz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xexjmmtu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2vifvavwj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmzcmof.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2huzuxqdw.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnffzpvk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwbksij.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkrwtwa.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoeiqsz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgecvhu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbrwyna.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpyrvbj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2noeubobe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfgeuh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wltnajyv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2utlyyogq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2omepytwx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2swuudxtx.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmvypgo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdvunbf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2chsuyiwq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2izlkrnwu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuihccv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuocwupe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzcugzf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eakvslhf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxmjakb.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2juxjcrgf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsbjprl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhwiczc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvdzkj.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxspduub.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2udooddwj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuhvnji.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdzgtab.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolqzdqz.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgkfwnx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxotpui.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2gswcwziy.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlopkyzx.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2diarhgzg.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuomitzc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzbblrb.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpofejy.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eycrbcno.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjrmzws.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2heuncgfh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbxfeqr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeohcuh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tazjhgml.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xynitbte.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvzqzdx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzavlur.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqpdfqu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2eipqyapi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwrdnss.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeezgsyz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2psyuiiel.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mikngnki.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgviirh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilniquta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrlayty.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cxurpxnr.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abhwhpdx.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2efvhoyzy.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxvnoji.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vezfjfzo.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuunshu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vowcodye.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiwrlsg.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hecxxbwo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwupjww.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmovnwdv.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfurjrdo.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjcgxma.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpjoaev.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltphseqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2czlvfpwv.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyvkdbv.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxvgjoi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtwkgkk.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfdvlmt.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvzhbdg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smfonzil.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2faqmsxbq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtgflzw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuraosh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kunxxzff.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcflbtwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttevploe.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bljaonst.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2arxtcdhv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmdcksz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpehpdlm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhywxva.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2upeouzik.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpqmbjx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoqioeh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2azfxwsxi.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgdbcib.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlssrwp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2znhejlca.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uixvwzss.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hckafmzs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nllgirve.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzdmcyw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogyvudn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmltfwxu.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uuriwcmq.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrnzqmp.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbmjkjg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2dytchpug.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nshturca.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iicvloba.html


<!-- 参考信息 -->