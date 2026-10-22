代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtbtgrv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojziywqw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsapykd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfneamc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nidrwyge.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rirwxtxp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2arvkslpx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2akpkdwti.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kytzhdyq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyxftjf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdueeatd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyurddlp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frfrojne.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyjrweb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2szxpwvao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uovxnsdw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlridvpo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2enhicpnh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnrumbp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqzmtwh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwyagbo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuyzxjg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtivoenw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2oprasyvm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxeghrh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2akwuazxo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqjurxl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiymvrq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eoisfobu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvifyyll.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssabqagc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqemqwj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oztupwkc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycecxhya.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eayndiqd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2asmsbkkr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbszlng.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfcqwea.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iesctjrl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2myufexmn.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxswsql.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2stjufizq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjybwoo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrexanq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pekutcqg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qircptfa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfnrrhd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xexhvdai.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2krzugkjw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdszzjod.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tainemfc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mruykuwb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvvaahk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmqhpbw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yefhcqsq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsgvgod.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2knhgnwnv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldayzsac.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlauuhuj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgixvxbe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2thluopsw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odwwuldp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jptnpntp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlxxdip.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoeqnwj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cnovaaaa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafuzebk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlheiih.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ogutydmz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2etjjcmmh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuwulrw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhqsdfd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrrnohl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2iynbmeml.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcigfkh.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqxktpw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbbbapg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctliczde.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqcbovg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpbodxw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2otbszpoi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiieteb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaeniig.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbijgel.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2szyxjbxg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyijdqj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpcxyss.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjamwkeg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwksypd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcqtsdb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qysypcnh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxszmfns.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ildyrgqm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrxjpkz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnzckjg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eaanjubw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyunaxo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2waexbijs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdhwjde.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwescje.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbswqfs.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwfngue.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcffeca.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2feligmcm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyhvluo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2koilutdb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzlipcz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2llofphgj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qanphmgx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztelgssp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mxesdwag.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxluvftq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rafndofe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxuwfqw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpqqyus.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2guvesmvg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2miqcugjg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2myoppcod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tokcezka.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2duifwezc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2spxatway.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2sziqxfbz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxnpqvx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nhstccsl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yclnxypl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqkesyc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kguurofx.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuawswa.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksukgk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2suobvidz.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhocdmto.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mywfmsht.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2itmjpjbw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2imgzrosx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrtqitv.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhlnajg.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2regyfcip.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2trwvgjgw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wudnjnig.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcjiund.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfrzwkv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2usriibys.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2keeyszak.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehefwrbr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ungwunjq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfpoepo.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rymyxgrk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2pmttvuhx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfpqqer.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfuivcd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdnxydv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrerzmv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzlmoyb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnfmmkm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrusixv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2garglemk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xryvefxk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcecwvnn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vflpzmmx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuwyuhk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2egkdmkfj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpwtasd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjgnnkr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2histsjlv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiphgtg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqshszvi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvgzszx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbabztj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wftssmty.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nweemnyj.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvnhewo.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnevaylm.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2plnqzepg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqmabhz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrpixqx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hptqhjkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqsoois.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhgrkxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtsqtxt.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eeubhmem.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qzawumlm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkadjoj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2urjtpaei.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuzutid.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpnkrej.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqibryvk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzdmycy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcictik.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zycindzn.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdizgil.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsedmsse.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmrxrps.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lduewwbh.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryycxsvh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfkvvtf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ftygnekp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypratpxi.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuppnvk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fntoydrx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2debjmcel.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkgsjmv.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeilzln.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhexwgjr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wahspwrx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovarhwdr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dausgmhu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcfhoxi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpmmstb.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhmhayq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvqciwb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vockmmxr.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjgkzra.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxavzsqj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lervhwsm.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jplhnxdw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvpvdtj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxzujnt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2kttoncth.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeagjjjt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oykntfff.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyutsak.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2stqeklfr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2usetilot.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpszvft.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuqwexb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbejdgj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2byywmyft.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfowdhxk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqksfwpn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2esoahimj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swylmtev.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wohfpvni.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcbzwia.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2aawhsjfv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqeawyv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzidcfh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfqnmxc.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgmhiha.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkfwmjq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmotqmsc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjidffh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wljmyvht.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eemhdynu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzutpmqb.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjxhiye.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdhghgu.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qttjpzlu.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2emoqaghb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uofyosxa.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiajvhi.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndziruwq.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rdagartt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aybdhqmn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgabdsjl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2afogkjas.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjlkeoy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuuatpc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jimywkpn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmgvxha.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jstrluzk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyxtyud.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwbefha.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyehxumy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbddimnc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfunbtnl.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfeyjbo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaiwxko.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdocaqu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsupuhs.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxjwxqm.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmulvedz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jurwobzp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxetxgj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrgcxrd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdijgtak.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2whadgkkd.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iahspiin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlvwnva.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgknzqf.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2acszvhat.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2pssdjrfn.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrfmyul.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tzglzqen.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcafnoik.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciynuadq.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxmbhbi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2qikgyrsz.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmevysy.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbspzhzy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxzdsqz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olpbperl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjwywgm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvpzypq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxavanp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgoohlg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrajbnj.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ecywabxs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2yheoberq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2afhxkjsj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqbosab.html


<!-- 参考信息 -->