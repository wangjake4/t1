代发 wailian999

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btwpzbhc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rduykmey.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmrqzyd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zigjnxtn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgynqye.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zotyzgra.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyqejdv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbpapaq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhubcquf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpusbppi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqthgzoq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfqptsf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrsmyvt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqlthcf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2olerodkn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2grpzakfs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2esiakkmg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2eignsymb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflnxdha.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkcwgbe.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2isfapact.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2istbzwal.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuciezn.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsuixqk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kymnelmm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhmjjgp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmepyiy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlabixkj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrnalcj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnkuiow.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hynahevr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqvinwn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzgrsw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcsljxj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhjpkke.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiyolht.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmntxna.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tucfaeun.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvbezbk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njejnydk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ormfhmev.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeveajm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akygsfii.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qukvoewy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2htwfdpob.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsdmdsp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsenyra.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjqscyi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoghhsu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vkczlbgl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmrdlac.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjauems.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2enrclaks.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxugcrl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqogffwf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gangbqcs.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnucdrmv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrpiool.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsmqdwc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiuelvt.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxpfnvz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyijsvp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihtuhlb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrmgwxc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfisclg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfooyyr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiyxhas.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyssjad.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2orkissve.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2yworcggl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfwzien.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwjxtp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nktanahp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyplbkzo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuupnqks.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2szaxqosq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oanalmcd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gklaxwrg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsytqjqz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqktitj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kyliyzkp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2omttrobt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozthjmcr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsvzjwb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjfumfl.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lghqgupr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaugzfq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2clzudrmz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdnfpuf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfufqpj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2iljcolrg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2chrphepj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvkqfql.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gclbpypj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhdriiu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsccxvr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvzslir.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2onmwibgc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacdkozi.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqigbwv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhqhyxf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcwmzxa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfdfpyc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnhdqod.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2owrhfrrh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tzplbiez.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blczzlgk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pilvbhhw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnphfah.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwomlk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvysihk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljkuqd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxarggn.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzijeja.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzourwje.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2geehumyk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrxefga.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaqcikq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmzhkb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2njxptilo.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmnsdhw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2keqqspcr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjyuroq.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmwsahe.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zqetdgmk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjbzsje.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lawknxrx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwftbeh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fptutxnc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovohpuq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tuclustc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2cifswzkk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqoehec.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xuufdrau.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzrjmtu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqroau.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcogwef.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcflvnzy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfiqybw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwavuax.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2laajblth.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtubdoik.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbmquvl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2chusyqcu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xuryggjc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stibvoue.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqhohsi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxhucpz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhfqjba.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rshxpkhu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnczbzhs.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcundazv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyplhvsz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtlrlsr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2soutecpm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2juxtuizq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcndvgwe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrufrwx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcbezoq.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbumdav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buipjhbp.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkezfis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxftrlxy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlutxth.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jhffwesc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuxghir.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvigmpg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cakzsxzh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhukneqt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2audjkadg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwyfut.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehogcupe.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ouukxlfc.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cutbuemg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfgreye.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyejqihc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgcphdi.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkskxwf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjozztu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2oszewvee.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozatgyuo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2memnvmaa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gymidqff.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgqrmop.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2phwqqkno.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkdobgk.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkgmlox.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmjiaqg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrvxuus.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaajxcix.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjblkys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaecjri.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqjloay.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmztzjkv.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzjpnpz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlaoybh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tltnchef.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfmntxs.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmbduq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpzswio.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkwqrsz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgktaty.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxlikfi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2utlivara.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2idbdaoqh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wciiittk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnhbfpg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicaagw.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqmqtli.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvjifms.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvridpu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2efhhuupv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqjmnao.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2thwhtjvj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2relpkfik.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdhdrig.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzbiege.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfexdts.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwgfcvy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2voybhoan.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdtrmcu.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrotyjt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaukwxyt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2punjfolb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxeipsq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2isevcaen.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dwirurur.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjkvtkd.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzygbdg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2luscroma.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2enhkmizu.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlysyjab.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgvkrxt.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bejhcbnk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fifdzbzf.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2qxslnymt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htmvghty.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzckmne.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2napicanu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzvjrke.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuziazu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cttcricr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yievdgum.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwvtzav.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2cccsgslz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2apzapnbc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqxyioq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzktgkk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2emnnqiwf.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsmxqac.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfochpun.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kecnfhnq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqcuwzf.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzvmhk.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhfcfrw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkxykzc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2exkinpyk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlmhuep.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkbatnp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2emxyjjff.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2atsxkhxl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgcwjcy.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayudvkau.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqjipz.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyxyjeb.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eurmmvms.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjvpeez.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2oudduqdp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvfqlge.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrfwxol.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzutltc.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbsaqbu.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2khgllasg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfpwvxj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqdsrry.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtnfjxn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftcnryd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiyckmp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2yalpdbua.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rminbwbb.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2giwkrgng.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2twxykexh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovilekse.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgemjmuq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpxkmwl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2koirhibp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqnnmbt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzagdyef.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcrcpqp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2neapquri.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpjksyb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iascbesi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qscmscym.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2inbegknr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2karkceub.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2moqdvmnx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqqtdqu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwydtntj.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpkshfl.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqiqatt.html


<!-- 参考信息 -->