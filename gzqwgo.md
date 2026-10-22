代发 wailian999

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgybjgzg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaalxad.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jftjbevn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuytpgti.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkdozkh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpexifbi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgapdvlm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oildihzm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhsaiyn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpffztqr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtlfocc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2blqmwzri.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2agefywmd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2akugujtq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2awookpsu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnfrffd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpbxjwf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnrxrwj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izokdkru.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhplbgqk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjuaang.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkljlaou.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqqtpbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aejlbszb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdmhplb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbmphwd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnjuohf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kftunoue.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyaegga.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2niqsleir.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdsjbqi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gabjxkgh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfnuslb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoscblg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nekixuxf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxsspqs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cuprepfq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvxievl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooekwezb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oeegqyrf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2udsraqye.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmbtmpu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sectdohm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2latuxwtp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmkmkjn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2axzgdxrv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gicpbwij.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kljayogl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsenerb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2eigpbrgd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2idmolymb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qetohyah.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wojrmltf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzuolhc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yngaaufg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoaibbz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvecgos.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwgyvob.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmswugs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeolfddn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvfbitg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiibcsl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dylssqbc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvokfcof.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbygavw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrokuxul.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2klnavntl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzrpqih.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eygjjuga.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qusxiggl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvommmc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adktxcvr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsqcgis.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmogvaa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecofzdu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2djaztwuf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmsfenu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwydmmz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbijjii.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkpquem.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzlxmy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2metthlpn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfjqwjw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2arqlxjtu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaafzxhl.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2snvtskyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvqocjq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjzjied.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ridtkcyo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwnuonx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rokwejkr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2aiihjzdw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wegckwko.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzngmhpc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sunageyp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwamwal.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvzoklw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgzlxmp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yebkebbb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjvdevf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxplqrie.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsxivij.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2olkpdqtw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhxkoqs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpaqpqb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsyksoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceztbxkb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2glhiajtz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zedlwmxe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nsszwaxu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmuwhdp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mssjxufq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yszjzhdz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjfjcze.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2oojsatki.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhnhxoa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2csnicqti.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sydfsbqc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmumacp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2paqfxbmf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2iainadgc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zavzewyi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrzmocv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmwknvs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrzoxym.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ciekdsky.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfyeley.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoogzho.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmndvgz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaxuxbo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2duowegwf.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ymccljki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdwnnjv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpphnbcd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvfkvv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvyjzor.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszyienb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmixgzsk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyjlsxb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuekemdp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kugpeyiz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2negpmpnp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtecjbao.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdigxir.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqgmynh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdunzpbv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgiweac.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjijgbs.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ompntvba.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ankdhxgb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zteifzbg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppgogtp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjecrmcb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2pulxuiru.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2syjokezg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqhxgmz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2shcxacwl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjnivna.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2udnegvdt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2myuwbady.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlycaxjr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtzyqzy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lawdntbp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmcbqyw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvgnjax.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2alxusrju.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bgasapnt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuhnlco.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bovdlcdv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmzhssn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zovkjokm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgtoyvx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2szytpiow.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycomtxt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndexphnq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nowcqcsn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqagcmi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjwqsfs.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2udixwspt.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yciqsfwz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqcwidw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbrxycn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlvcfux.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbcxkpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trcqfnok.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lcumaeuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wohoivqf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrgcnwt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxfbtwi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqzsjok.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxddksy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzpqhqj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2etkxztsv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmfnxvg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2wogxaqfc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjbbjsx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vecktsey.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjdinur.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaoodry.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dypegzyw.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dugicfwp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2povghezy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtvpbys.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgnojxx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kojncdzj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sozecolp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2apohjqlh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zorpqtbv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lurfpgmn.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwttnqol.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uymilnke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2okvohefn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2actmdffu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmocxbe.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2jygyjokp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjlbjcw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2tudmzaer.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivqlomu.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqztvmfj.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2anbtnnwa.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2unpqujhr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2piwnxafq.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2makrnyju.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gjowujqw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjntgmdu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2favtwtij.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgyhdyc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjghxlj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fagiqhdx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2irhhexnd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhrgdjg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyuuxxi.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxugahd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkorboq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sykbrssb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiumywlc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnedetu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzqlgwp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfjzikl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbfqplf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgavlfqg.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwivoya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2twvfqrfo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyzepdt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxwzgkl.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hilgfakr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkposkdt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlypvzw.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2rbalnywj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewyzkgg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdwcons.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfwzxuw.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2fissjdwd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwernrl.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoxpdxp.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcovkebq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmivvmx.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2blamqazi.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhntdce.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2newuovqh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bofmxywp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyrcrza.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtthxpog.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrjjiye.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmkkfqv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpdjaaj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghylkbqe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sghclklk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2urqpcflt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbjpqhw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyedwwxe.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnxqbws.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaegyue.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrgbbl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tceefqaf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkydjljm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqjkpox.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2giupjajq.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnmoqhu.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlkphgc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2urqjpnwx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpmujhx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbafepos.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxxbjgu.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gzezcjpl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvttzs.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2conexgnj.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjpebkj.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoplntyb.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmpanrj.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfwahpk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmllwoq.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2srisdbyj.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kezuwtdi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ingtjxkd.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbdxqli.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2raosvwmm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxskidia.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfezamcn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pndinesw.html


<!-- 参考信息 -->