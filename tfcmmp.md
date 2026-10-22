代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzdxrlf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwsyvfl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnukoqom.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfzmjpa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvkxolm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2movqnwhs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensesckn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rubovqjl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vovqjyyu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsypqtg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhunhtim.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxwuuwt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdshmdun.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ectbmevb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2plvbgfky.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2llouvxhi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxkvttt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgglqrh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrauzoly.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojuhkm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czqjfrpd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jctvwghi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2acctgwvx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzkyjtk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrbbqoi.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdtzrku.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnssbnt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2exxvqjme.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhokxokj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eagltwty.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjtewdf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrfeopu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccigwlci.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbwuuhx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2whzmbaot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhrmddp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcjmayy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbhpzkk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlngsry.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqjblvj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bisjnuik.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tafddnwl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyndzeb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbifwyua.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxvamgx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2euyotelf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvzygjd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbpxzlu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvvcatd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmpvkbn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwdnxfa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2snjcepbc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gplxbixw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tufmqlgq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvcvvqg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkvywvv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxyyrhg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ammkfylw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrkelbd.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqgsitq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2conkpsst.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hirrxecz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2capgljxb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzoxsdv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aundqsuu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvoyzxu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mutepfcs.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnmsyvz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2phepmqjf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fefkagpb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rffuwiut.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhoela.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvurudv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrpggcn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdsitvp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fppxvzbs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2iperhkew.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjlrenv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuqauby.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjczwebo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgxqsyq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwwwibs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjlemlk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itsmaaza.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2krrngijk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzirjdp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwvzynl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdhiraw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqlzqxm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlynknln.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aolwerop.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gygpucuu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbaasgl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2brgxuqfs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpobowg.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwedzvx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhvsot.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdifbark.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpsqkkw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ormhqrbf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbhoawo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsxjnpp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkicppls.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wiehdpjg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xukhclyd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2shtpzbet.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oapxxqmc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelktyju.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uifxumyu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvuhzkv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuxheil.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqvzmpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbyqxgx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2alvenycj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2duckuvdc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrjhsqg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjodqur.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2thlmjmtj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxodtej.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfoczwb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mydpaiwk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwbslbz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxfsqkb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxyinwq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqsnwpr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhcsaqm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrqrxnm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2obssproe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvychek.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpfrcgq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbudaji.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjgrcfk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmctgtug.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwhuyjf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkgwgia.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2autefrpb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nnisimvk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sxardfqg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycxmgh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mpehgouk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbmhndh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbzuvsf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plaaokiw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwshtei.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2advppjqo.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqllrsdk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrevgqh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxdrfay.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfpgzms.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunlgggp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbheisz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpdyayw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlbdvcj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvdurxu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqeydxu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywljuont.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiewshd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2idnxewqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wsedaezg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2boqrudvz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2pxribfui.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmbseph.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaxrxsn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyslglni.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftusjyyi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2amnxztzl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2olaiutvn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcqfwt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sujancuu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oucxuiyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmykqfcc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvggpzbl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuwptak.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzttiog.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqpzgmy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtvldz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqikaxf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2oljnhaji.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dwivqcay.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxzhviu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrzjflu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icrjebmm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ephvbfnh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzaxgq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuanacas.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzscndu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitnfmgd.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsspbyfp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2maqtovxo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2upkeilya.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnntwkg.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmndodo.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuffowu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjopeyuu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2syacwiju.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfwglc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jstjthcx.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhswepl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnatacro.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyklmoh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2snmgcdqy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqqfczz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfujdcc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfaxtmu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phhzdueu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbniljm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2szughccj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkspvlq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcmqijq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2oskofzet.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rusaslyd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiokcalf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuyoysl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumjezhl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cghqfvej.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vjikxkmm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlwupwq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkrpwys.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrwdqmq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyklmogc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjorbup.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzkousg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkaixls.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2razuqsnp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sblsjazq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtxzejz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2tthjltpd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkypnxz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqabhkx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbjwpur.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwvtzrn.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcapckgo.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mktoayob.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkprsyb.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkejjhit.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfqygon.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2msbyoued.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2olnurndj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzhcwsl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqdsetf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkyzdul.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcvsnev.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqrzybe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzwfzzo.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxntlfh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelabiaw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewupsuuu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sltinsvw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lujmkkug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjckqhuf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2etfgxdoq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2agptjbvp.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hezhlkpm.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbmxpqi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfznitf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbubjdxn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmrkkqi.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqtotyn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfdsqau.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdbqsm.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ochccddm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2umswdfmb.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2issdtlyj.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoarylsf.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgyvqqw.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cevcursz.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpcxush.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhqkigw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnxuqmn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeavndn.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbongwx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2emeoqtdb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rteeeush.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwjgylx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxuuvpy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwpnase.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2knpqyymj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdypofz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjbstit.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgcunwx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2aspmhnth.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uotgifyt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkwrqr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nalbjhae.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeowozs.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldueqpdb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwkwijr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmiydpm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfvqslo.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lutkdlnp.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwffpkzh.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2odwmtnmj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqxtvlc.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmpijjd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ninbijfw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2slgobdwx.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kvepwgyx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeunmdc.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2elwdgcsu.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhmhxpn.html


<!-- 参考信息 -->