代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbucnbg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrbcuyq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxifmfzf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adxrpmna.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxslrn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkymwlyr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvclvgfm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlcwwvg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqczwrm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cpebkosf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2epaymias.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyhlkvh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzcitbl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfdbrlk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgpguoc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnffawfe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stfshjro.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2macycodb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnoooma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mandaqus.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjvbpmd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2msrvkwvd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rczecqwt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqfxqnj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiwmvhj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gahwwuls.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrtuwmd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gppzulmi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmccimba.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgshibsv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2agaiewxp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfevaczu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2noznnfjl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zucccwth.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnshwpxe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iknhzrxm.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jvchpwwi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzccemer.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpulhzti.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bidvfvhm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2srwolemk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mojgbcef.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctznaukm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2plbnllin.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaqdkjo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yczyczgg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvgyact.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwugskkw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrohpxk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aknwslua.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiugofcl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzviuxs.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeesjxxh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekayfcfm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkhtpwp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjmghdh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2frennqyt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhgfqzf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2myalzzzx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuaknwh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2idaoiozo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhcrxqm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2knemuhmb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2mafgnrzl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoytfcs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgibqpc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcrnbhf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syzpdlaq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmaxqye.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrtfvgd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwtoqyc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwztkm.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcjfvbt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qagjhwyq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2twmantbp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrncwhou.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2daesjnxa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaepvpa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwnomn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvovxsy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmkokap.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxsacrc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgomvaow.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvntmhwj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdmfdrw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmdrmd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2drolyspr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2abyhpgeb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxetdqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xerlofuv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtynpxl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zapuoirk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmekjltk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrshjzl.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuunqrb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mguzyfjj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcadxdah.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jovkspqh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pstvrieh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rusoccpj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcgnwfn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2yblgclop.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhovxe.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuwyzom.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjddrgy.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgsgfun.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbnjmno.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfttbmq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkokprgw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2woyfiral.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdtukpm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2imkzatam.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpaqyxn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2xadcvnps.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2obumbamx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvkxjgv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvfnqme.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgapwmn.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wydbihjv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrxrrxf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgvzbcz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2grytimif.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmecynq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrjhcxj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoewxjh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2uluiiirc.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2anrptwwk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lmacdzuv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlddpcxf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaqpbhh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgcelmx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2joexkofn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2laxhoeil.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sukeqcit.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdwollw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhbjfjp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvwismb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cubmghid.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfmeqqj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcgmhwt.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlkxhny.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcgfaei.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxbtzrv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlfusox.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbylrx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2muffthte.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaaizjd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrtqrqi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzplxia.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qribkuxi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edlqyopj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxjpvkx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2syuuahza.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrufgkh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycecpuvv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfypbphf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfnptir.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaibtcpi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jndqzxwd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoozzgov.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgwynpq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvyhadv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gznwlrfm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctptsfjv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpzyatm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfkszmi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezryzuru.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzigsael.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsoxdgz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtqtxfi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mraybqoy.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbmcalh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlvkfer.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmrurtp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvaoucw.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpefsac.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvuhacj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrgwpoa.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoakovrh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jranfjwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgptbcde.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhynnvti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chkelfum.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krqmfrbq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2hhergrxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjrbxea.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2msfwrrsb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbudthat.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclwzhu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyttsnt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvcejwz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gncmdrbj.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxmbqxs.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bdypatvs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvppfngz.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmlbrjz.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2whnjdiwt.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yekrtbwk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuqsaqy.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yghfuhgz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwgfgds.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkopeeh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpdyynp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2grchjqoo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbqifsm.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2prcqtiwh.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyrevqw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvxpjxm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2reorhfsu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdgnsui.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsooxdu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhfcksz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2tifycyns.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvgsbrb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdbvzdb.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkwamrk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvpazcw.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaajdah.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lifysszr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jazcfzcn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjpcypf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2xolgfzhk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsuaahb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dljqfctx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrwopcc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwbqgsj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrphxoho.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jixyceyi.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsonjrjs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptejljlp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rebbhayc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhvporf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfshptg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdorvhvs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvcmius.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vphiojam.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhdxgcp.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2oucvugph.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2gkncrcbj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpspwbp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbszarlr.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fatisvam.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iryzzjmx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onvcdeuc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2mllurmla.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2txungfbm.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lubehehp.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuudqqu.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqcrqdn.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2osrawmuv.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2acutclkg.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzhqac.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2peuelhbv.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnwucgn.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjahcns.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdcdqbo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelvewrf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axgihvdf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2turomcqc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tviqbenj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxnrhog.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2psqzisrr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uviqpxac.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2itwouqxl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpcmtnt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qygxmpcr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2imrnnaaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjnoyam.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvrsfxk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfbnfbc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbdfav.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zagqtxyh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnnlspn.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbxjkd.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvqhhgk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufznmvws.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfmincl.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2twlqhvsy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2twzbpkcp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtdotee.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iaevoctl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nisglnzz.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vurvnsbg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfcotno.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2argvvxuq.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jregjdiz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdrkdhm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuobtooc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iglmsypo.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlyyzrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwhqbt.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sncxutpa.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2kavfmmla.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbncjulm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rissnqyz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeixlht.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlroxxr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kuymbkfj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfvsyfm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrwvxfx.html


<!-- 参考信息 -->