代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2alrqbnnh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqfqcvv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaiftrf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yslgfbdd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2efykvoqp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tynahgla.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmzhidw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tahpntld.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoiimgo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkucalcw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuzimfe.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvrwyli.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxlrxpd.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvxdpao.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqsgjre.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2czojywew.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwdkuwe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfofusq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqljlqv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxbudzk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azffctiu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oubikaui.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ripivwke.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhpxugk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2adhzywgc.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmowwvwd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeheadkz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzusgtq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkrwkql.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2decrvizw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbepfgqm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlyeufg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfqoqej.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2braggayx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcchzwrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtdqnit.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btzxdlry.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jefnzwxj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfriougp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnacovp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiptqft.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wcurckrl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkmrcgm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezsanw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvcuqsh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfssgpk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfkiwst.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxowcjdq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbtzanp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fysfltru.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2goixkrih.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sflwwdge.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2agoyvsac.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqomxwbx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vztbrduf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2grlwumlk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rktmtefp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbgzqdv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etkfhdde.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kgixkauc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcjbzoo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2laupvbrg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcqmzvb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozglymq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2drpxjaiw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kogyvnsd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsckaadh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oecjxxfi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yamwlkwj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqomzsmv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrierwnv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogijktxj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2arqtpdpq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkejsba.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxooazve.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2awurwnnd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkuraoq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qloukscr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmtktii.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkneomy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhuovxj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkofqub.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxxaied.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrplhxq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fecglybs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkqqjgl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2juyiutka.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiocawj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbqsyra.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcbjbbd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdhnspx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mxznadmb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghryvbpa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxgycit.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2avunfxny.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qvudvylf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmjabdp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2igwzmivi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2paceuyol.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlzahfh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtbengp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xphdxczx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfpskpl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrohkdn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2akwsgbbs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcmxbkq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2imqufngv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dozcliaq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpsexio.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbhjzsi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2igyamecb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzndien.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drdbqtsx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdyzzk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dynquioz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2myqrjgie.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eudjecsw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjbmdrc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphcnjdy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2barpftbd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jggdmylo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgvxxul.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2whavrdrj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2galcwtre.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwejtkrh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cleridhp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qyanmeox.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2harhpdew.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnselmyi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbulkthi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbajfnu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2osrvpbab.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2pcijeuyv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuhidxt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyphlpvk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtzpnjq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wleausfp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2omhjhehk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdceace.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cliyzlqt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcwdtbv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2mglhdvsg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wyejqzbj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zkafzegq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lobxtpsn.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfketykt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgukhzr.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgyjisc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thtwmaxp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpxabwu.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2diebnbsy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2rekimtah.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgralre.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuzclgr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbufslb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoavqcm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcqjwxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eicxjyjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmodnwz.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihljohit.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2vasljnyu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpgsrxj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yikfzcbv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswgyrez.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyamfseh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2plloowdu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgbqxna.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fimrxqvt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yftlxcjb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2balfhoag.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvrtfyt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2buxagama.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhjqvuk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epcbxbcr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkgewqr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qadbfhic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2limxucwj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtszthr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgjsxpe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2bduaompj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2twfpdbmo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gftrdyws.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvwjgfr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxlqrqc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2umseyfey.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvonemaw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgmkdsb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xlraybtk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsjijrq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkipioag.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcygadl.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mihhtxir.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhkktog.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyftaoo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeviekc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2denyiezj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsehgeb.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lodboxqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frxifznl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nexlbove.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2bwomnzly.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpfxihd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaaomvj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxdpwsw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrcuouo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2njemhzet.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqreetg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eepqbxfq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llkgkjsk.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2owkdnhhf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zssswsre.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nesodwzt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsncuhv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalzfnhy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkacjkoi.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyicrdx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhfksqk.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ujteerit.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2orlubykn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwuyeuc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rclrxwih.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwolfyhb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmtocz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2veieltxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhuvdmy.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizqvegb.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfqoxhl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmywhet.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtyizar.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbbboxg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfvkufz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtnjgji.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rltoylop.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rftstujl.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2icruqpon.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfpdzkq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzntnles.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxmppmi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkqxnpi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrxdwmq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgreatlz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqkmkbe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzholquy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwonsmz.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lycfjkpl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwavxatk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjzzhro.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aruwyrxm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwvduvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmudyrpo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrjieqv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sskjaxzp.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeunygb.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnwmget.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2emxdrabc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlfzjzk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkrkpdk.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2smhfmlpy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2szmvdkpn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lasqemso.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2aemjezro.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2urlngakn.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjkaxat.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2icyngegg.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyqczyp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvmljmz.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvagfoa.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmniph.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2awlxpanu.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxbcbfj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgdtkll.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2mubfueip.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxzfmst.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fidltmrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgbpzaa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2icouwaqr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2siogivuw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oirpbwzm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfudzxtc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2szfoegef.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2uehvsoqf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2azcukkpa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2duhqzdts.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pctpowtl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lthoyspz.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnqtfsy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaektufi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gioebcya.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2aohcfniz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvurhv.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpgswmx.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhbksbw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdhackq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiymzbpu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrinxbrk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqmplvy.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2omkuopvn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpxgbkf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrlzxpe.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcswezog.html


<!-- 参考信息 -->