代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbpkatv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dolmndqe.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zckpsncz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pflmmzys.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2culpibbx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enqbafoz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bydumiwv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2avmwnoox.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkremopp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyxiqfq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udaqnrhu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emgtjsmf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwclcyu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnthpqan.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2iptyiomy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbyiffr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfhaoye.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2resbldnl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkipaxd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2drnbwspo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpowasm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pdybscie.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaamcvgz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpqawwx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dovcmjyy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smpufbnq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjyyjjm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2anvoaizt.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrakjwc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qrczyhgy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgpegwl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjeycxq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chazhgyr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ekglifvg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxipzuj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkorvsso.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2icernyzc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atkloxxc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fambhwqr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyfajny.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jglxgpbo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaoflur.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kywowrwz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpcmcuq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vuofxlab.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjzqjsd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wayjqptt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwifwxs.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhevhuva.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfudhpn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqybyzlp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqswwpl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbgsxty.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqhxqwk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pacugzpd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpxmjos.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueujmkei.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmenipl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcyamaw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqydkho.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvabgpv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdadwzwo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwvcbeb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eehajaqn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmvsjho.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2instaawn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpccnlar.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbxuhuw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2tcifpijh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2asckzzuc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnziyqcf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwbdldm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2snjvpwwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2okebovct.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2budzvwlc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsepcchs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2imtwcrjq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwdfluu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2voxxrxve.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2erywlihg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrchdfe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqbxdue.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sigsakcg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzextbm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2abbrmrny.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2umqtgluo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfzqxdk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwnfkyt.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsxfedi.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzosthhl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjeqaeb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkwkvxs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrqkmca.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmznylx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2davleudr.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqunxwd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbvxrzd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiukzqje.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2udvphofi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjvqiq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2seqfeixt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlosxvf.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhzpqmz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iytljgwm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxpaahv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2txvpszho.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2huucurlu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2loobqjql.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbebrzv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfrlrhf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2krtgpsau.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pghtvqub.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2riunfipj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2svpswqpj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnyediq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdcuoeu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uddaigir.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epzpztvi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrvtype.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xybmlvzb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2btlxutmf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaqxzdq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ipebaqmz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcciokzl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gaveejeu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagjblx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2accffvkw.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbaheaz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqcewm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnncwmk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxvsrry.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2krzfpejz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmcijnu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhmbuqt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ggumkela.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oaodrhqn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2prcmxoxt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzapwwy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgloglyp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uusgmygs.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoopaej.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfyammf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtonkei.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkrekgi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbmiybi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrhrvan.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxflnlag.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjshaqj.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrvhuoj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfljayu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzuxuh.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fopdflhq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zxilhlvg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2loyjwmdd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wruommxq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwlffys.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjrkrwj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zywjgabl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgxwzqi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2pcufkams.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2blvbyokg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwnuekd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaamcllw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qttjvtla.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjesjpe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpspsvu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkspjqs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2msiukxrf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgroree.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkhscgm.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqubvkl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2erygacou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeeoeuz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnlptrq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2slsashah.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlldguk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsqzqmi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pztdkatq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpfbyiu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mozcsisj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2icutkehn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoprkve.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fggexuhu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxntcgw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgvmuxd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhlcthp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2txyhelhs.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2voibdpig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjefosid.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxznvzug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrrcxsq.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yshyxmub.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjbucwh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2erejwann.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2teevtcfz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlctagq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2osplmvor.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzkzcjo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeseyya.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnllyms.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqmpfma.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdxurhw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwalujd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvynahru.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axqnuzxx.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfsvkyz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2biturqhk.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2aowtzjes.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucucxbwn.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybskasjy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhflbxoo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmysfoco.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqcaosu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqmztaj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mewlsxne.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2poceqmyc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yykayidh.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssinzcz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoybvyc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpekzeh.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfmnuzn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqtxbtr.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgapehhr.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2clouylrg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdaejkl.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxjcfao.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gantvuar.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrfanvb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnizelrl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2lklnjdcb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbziuds.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlukgrtt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2txmvposz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkiezvy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlivqeby.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqtvjke.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgohras.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpthvcd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdbwotv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgbrmpu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tragecvu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldzqjdy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paditavw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvnuoka.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhggctce.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoqsurr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdefeic.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqxrzec.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nweuguro.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxxpqii.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjhzvhn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnawhauo.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxpypns.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzauirpj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2laqwwbpf.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsywymt.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2smdvdbyn.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwbkgbq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzetdec.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dernrlym.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgboyzt.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrhahfc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdqslez.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifcmux.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkpxrgg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhugzbgo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzsjaio.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvcjkzv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2btyqqcil.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbiifhc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aptlsdfc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjufdyb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2qczehyly.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzuodvv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgrtptm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtigftl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrnhshl.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yimdewao.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcjxqod.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbukofsq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgylryu.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnbeeku.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqwevik.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymoctd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aszvzqff.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2osmocixr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycilqyrq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzkzvqf.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeqoqqj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2lwermkcp.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2urgqjfhn.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkluiba.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2aiipgzkw.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtgdmxe.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoeasxq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2icnjvxqj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmzbael.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgbweor.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfjyckx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2blwcyvxv.html


<!-- 参考信息 -->