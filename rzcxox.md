代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydicqfxb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnwnagz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjthecv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfkwyh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wridwzyy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qswjrpsl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxinoiv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqidfmk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsligern.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsoocfy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2alvyaewn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcxkecr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrydtqx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iixxlvjd.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qebefjju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kibqkcbm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pounrqxw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcyzdzv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pshmdhez.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnipfpz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrcznag.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxrhnop.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hoimqpqt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxbywfi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjypdyik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhbldfr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gokxsnrp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtledihh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnleylm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmppayd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2putapwxt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjlrzdj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uapfruxk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2azduzsfu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtrqpnx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2shkuznss.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoubgye.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhhuvyd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2czfbibit.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwnvhlz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxhtxtq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2afvuzcef.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaqwqaz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwslumv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xixaubwr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbzynp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2moexqngn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lirhbleu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lracqwrg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyycpbaz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2izabxsnl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdckqjmb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvmphkl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjoojly.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2szjxizxn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhydkaj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ntunqvbr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqprdic.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyyoybp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxqrlji.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbmwrbf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xywhzvio.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjllrus.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhutzsc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgreqvn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgokxgg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfovmuw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrbtbov.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2myoyhcuz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoypclg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeutgkmk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2libvylxm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cswxfsqp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqcklde.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvirwwt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cafaquoj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2przfawtz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfqlwrx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2foffcfgx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afbmwxfd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2flbrsfhc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwnsqfk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltepjssg.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfuistw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2evndzyzr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2brvvnfte.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrpvpij.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuhuomj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcztsvrr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsyreoe.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmcuxrb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyjbvcy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amsknmsq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kalorvcz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vejjgook.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2reziquct.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2godfcsrh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqjjbkm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphzhlok.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrddosfo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2keqavvhj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmrexhc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2akjwllck.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbajljvr.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yyftwkic.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2easeiktz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vynbgoin.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkfomqv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndixwqdq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2satibuqz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xgajktmz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzmxspz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jagsptdf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnqjbme.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaatvbh.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpdfstq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgybhbw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kskfpsph.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2yggrcinq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzgamtv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kobafqmu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2loomiuzj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2triapbqt.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2etixcnfe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oifnyrgr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmeaaun.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2anaedwoa.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtdbwqe.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaibkia.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbfdoic.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnloechw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvavnvpv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjpnmbq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fetvnnui.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxintog.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbtxaxq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuubktp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcqbgty.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2adlmobmz.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmlngxl.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lewmpevw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxyzvre.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2akvmagoc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxljdrlv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yydettyg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwvcvvv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aizulxqb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qivtvpvh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqogfrpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzyckjx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgmadqs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnghhrmp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmbwljr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsztsrw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoheisvm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxtkmkf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oifshmhy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2lktuymie.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxniews.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2boebclvk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2slljazyy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypamebmj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdrjmgp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghuscnz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qstaxrrw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoochsyh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhcdlfi.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxdjftf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsyjiyy.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2voszunwx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvdocmw.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhguygz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtpxqvb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlbbqcf.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqxmhmo.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2abnhsqnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoqbmtt.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qiektdun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfjejhn.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmmieaj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtxvcwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwosfiop.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxwosps.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2njngisrj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdqttjr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpipuqo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2cifhybab.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oihvcywe.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dinrctch.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsxcepz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwtqnuh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumqzabh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlbavmc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2woqmwcrf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcynibb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2espojfrr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2libszysb.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yoflllki.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlwzkng.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwicredv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bllxeifh.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvduioc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2seovdmxt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2urbengsn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2usdvoamp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxvnazp.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2vyelzejw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbypqir.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbljljuz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2filebaru.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2smsrajya.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oklfacng.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcwoppy.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeaqigc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkkfnce.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ieywgade.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvvdsrb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnepabef.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2voclvfcg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoktmkrg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeoeowx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyaqpvw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxxxonk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsijmvsf.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uoczllzu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrzndio.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmhobeu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdwnimt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrbhhfx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbneinkt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnafkvkc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfzyupy.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtthikv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sonnnevv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2zirjqyrs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpvueup.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2obucione.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmeyly.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tytiwkte.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerpqqab.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2dogevubc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqzktl.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lylfdujc.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihalnlpy.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxvtvct.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjlmlpo.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwzjzbo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcdntex.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2heqivbnq.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qefnheto.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmifoyo.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbxzeak.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnzfywm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxkpali.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2znjqytzj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ievusfjz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkokcid.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2exvvxwvx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2htiuvtiz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfcbwcu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2cogrdgga.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbnhhmv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjymptmm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnnlheg.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cawfwpkw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfblqoho.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2twirrvcj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tspphupt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtlimuy.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaazdyn.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2adsxkmyo.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2indvuceu.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfaynle.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjxtikz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nztgbwso.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwngzsl.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wigsmutb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebynvsnh.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2oheffuug.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2svbwfqib.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqczrrvp.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcdsgyz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpbrfby.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziireeyi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoqqjnx.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yckgqgje.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjeoxvj.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yajymeuj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqwtknc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrheepv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqnecvg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qidwjyrv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuamunl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyrwnvk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbjxxyf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepxfcvh.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhhwbb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2szdycokn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxttocna.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcthzhd.html


<!-- 参考信息 -->