代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwakwgb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2procgxor.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxcmlyd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgxtteg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2abjmfihf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dwihvlzp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msxryawa.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzcyqjr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2htknimpz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpztsot.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2prxeedac.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpbpsqv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzpqrws.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzdzudl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2olvcmxmc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oppzbdul.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxihzjt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwzsdwq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2barqasru.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtepaxl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkzvrsp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kowpcfcx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyxzjwy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2stdmgkrj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sttkuxnj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyztcdnh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kioifdba.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2onieafgr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hrydulhs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fakqtmjh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfjzvtj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbkcxra.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvikthx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2irhcrpey.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdgywaf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfnqcyb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2blqqxjrv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2htycqqoe.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjgocpe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxsmgd.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhdcepw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fixibrta.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bdguvidz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odycbohv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlgaepn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2heyyfjfd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkhsolc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoeaasd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrojgqaf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zedshyew.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvicgek.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2btlofjtg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrhvcjy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jezzbhrx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrftrvu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvawjffa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fycwesis.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tglushjm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtajmmpo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jghhujox.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjljdor.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2msbfdmkf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcacoied.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjvadeu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sewlllgb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qahhxmcd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhqoajm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsruzlg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbjyvvl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ummlyzoz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afbsjzid.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oamohvvh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqryocdt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsakdayl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfwpqfd.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lppklzrj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuhunyi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvlppqn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvymjqws.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqmwuzx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2spwizywi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufkkknt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2yetxgkbv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyxyrit.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfzfshd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebobjsqm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vieiiayn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aipclfsq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2puakxjea.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnvjhgk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2upsnjuyb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnrarnn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyifejuc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vjghxrsg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbjsges.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jzukggwu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gshsakkl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqkroxd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnqcecs.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2keqaiuod.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mltqkspo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaxvwmx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfqrvgi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iizctyxk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2baewsgvk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpwicjv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmcigpv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzpvnvg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoxrlny.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgdxwva.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2paxboxug.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnnnmwz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbgypru.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcxbrxn.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbicggtz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfedkckl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrlwfbv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhsnnvp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2gntcfzty.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wycvwbie.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kzruxsvb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwptbhr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vephsswc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mizkdbpr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvconmjx.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcanxhh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygotdki.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzndfpna.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmdimrv.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nekubsoh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwaxnqw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhbyfvf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2paimscad.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqdwppj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaboqag.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wvblsekf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtpzrau.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tomxqnrc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuibvau.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpshxslo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqltklt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwqofmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtpcbgy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfewtybm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gryxfujj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfqjtcc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qiciunyw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwdztqb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiivvml.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yddqihea.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2icljpres.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gejiqkdt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njauhfwl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpqkoii.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2werjhgyv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjilrfoc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sktsijyq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrvcoal.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzkpzka.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcegehtg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqwafsd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znxcylum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqivnucm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtsmfgu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzzpehc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zplbldss.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvbncgo.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfmchld.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2chmbdsvf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhqdtnt.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtivro.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yocinmot.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2baxbpeqd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrdqtpi.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgnpcgf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuvodsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaffwbk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qwavsejb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdpibyj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tagoxvfx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsnmhao.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2syzrsipk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kttqyvhb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjipijax.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2usivbgkg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycanzbn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsvgiqi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjluijo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkhbzkz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2icxbllmp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbecygt.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iayypwby.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvelqmex.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlwgjsr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllbuyjj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqovkik.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yctcmdsd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tilzbwnc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cazjvean.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yveqgpok.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvmykqp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxqhggo.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyndtwf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeeahpz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xejfljdr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btccdljc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvdwxud.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzbpgta.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2etepyiwi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgmxoqd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfmaqyx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbdxgkn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvfxkgn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxrzlve.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bipcenfm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdahkko.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhpbdxi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnorkyxu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzxtrna.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcngfoi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuhpjih.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2paqanqqy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhutvcnp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgtdrhm.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtiytfu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtyvvhr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbulnfl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zodkjpnz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgfavfo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbctnnps.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkysmce.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqikhhz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbpkhoa.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mctanwyl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhczvlz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2skfqvugq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufequlsi.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxuunkd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2crghazud.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gypwtopu.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqupkuj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmsrdgm.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwskohk.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lauuesgn.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrstehnu.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfczqfru.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrlpkji.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yryrjqrs.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhvaygh.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjagkiba.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbyxewp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2paonoccd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nybtyvod.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzayham.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvvcny.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dllmxrjy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2koveilhr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gatwaxfc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyttmuke.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcevumri.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2krkvqyvf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2akboddce.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdlsczf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuriidl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhilkvp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2neukcznc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2quznywii.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzrtfhr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2xqevfkmd.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oergtslz.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwhyizw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2snlsifwz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2haqxybig.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbjkfzo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tspbdmse.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2agjiinmh.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsndhmq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjlfaiq.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhbdnfd.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezxzyu.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2mipewndl.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gduudumr.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwewndep.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2trquazwz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdncqmux.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehybvcxt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2awdhcvmu.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qoirgbph.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvofash.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrnfrjh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuuwibp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmwkiup.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcrnihl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeoxgyb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeormcz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnixursu.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqmjzxz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2avkqival.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqbvjqw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nunobqjs.html


<!-- 参考信息 -->