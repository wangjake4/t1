代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwsrpfb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fljjszwl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmauvhhw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwecbfx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2heqfqcbr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmqccxk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2przgxazj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgwqrkl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uglvvtrq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuiorhg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoruqdc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzdlglx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxhrbii.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2apunhozt.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxydsni.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfldrpf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sifudsrv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvzxpar.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwamxvl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmardeid.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrhosbh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvngayr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdztsej.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzildil.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptgiyyi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhjwzzd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fstskeql.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyvpyui.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkaiuiu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qlapprlc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqebjvg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzubpj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhunvyq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcudcmk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqvlbus.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhnhlbv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrdgtqk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcahskww.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaswykis.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrtiozc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2siiwickt.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyrmbct.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvwutaa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzlwsfb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sipipmpt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzclkls.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhuqlhf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkdduqd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwukxnv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbxnqhz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pptnioso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhcdurn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vddcbooz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcojpdow.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjcfujc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dteolfxy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rnranshv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2avmjgaji.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2moakqsgi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2kncxsmmu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqzplwp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxfmaf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhbxdvp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svaculay.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njupzcgv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oreleoqg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qevlrnlj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aitdnbwi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbqacda.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmilpfl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ystszdcq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxeznmi.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqoufvp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgqulyd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpwgodw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2llizjkde.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqntcga.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjwnpsl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukazvpss.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ligtgwfo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyugmnuf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwzvvok.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpfxjnf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlirszx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcrlfcj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qagxhemz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuniykge.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btggiera.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dinfjauy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ralzhpsr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlilciw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmojdyc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkkacsw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkppstb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2oftmmmyy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhppowh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfcxsua.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpenbltg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjclsbwu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2knlzksjk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvawhplv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjswqib.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2tskdwqnt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssibshuc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nbabryzn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckosszwu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2raxthzxj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpkdhhh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzytmol.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycloktaw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoxjbtk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxnevmp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2smhedjou.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uldpqnzg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sldevzua.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dabhzfvl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmohumvs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nluupdyj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnmlfkt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2khcyfvzi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zcztgxss.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsgobvc.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvzddpv.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgefcyj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbizqrwv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyztsibv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfmuok.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2seothksv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2febsrazj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vabhrqdm.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bekfwzkj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbisqbja.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgzxyke.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2glzpgmoz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iecbylcr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2csjqsjjm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2isgccudd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2onsfebqw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeslhoc.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrldgcbx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jgacozzw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmlgzqs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oimpuvsy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2omlqktbu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pklhqyxq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yekqfxng.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lopomuvr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmbiakl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2soibvasc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2boqwlwdr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqmssgw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiradlm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjykecz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2clxfwsde.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjmlclo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gujgwukc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kngpqkan.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfxenzq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeikgfq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpawxpls.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2emcllzsc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhwryvc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtbotvy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyeewkp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcqdwyt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rruyvxum.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdajsro.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyityuj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnddcfif.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukggjtls.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oepakpek.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2viyfrodu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkhftrk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tldypctn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2slbjkvop.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gufqfwvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eenqfbsh.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbhvvvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxivsxhw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nityivzc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jduinmwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2shnqqjfv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkqsvt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxabbczl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwblbcto.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaurpbgz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2duoznhen.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eskkcdzk.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2logrizji.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpoxypb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2spsmdkwo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpqflwy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hykvbyiz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtdwykv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhftpxk.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jgircuvr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwivbmgy.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2didcxuub.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2muilcqph.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvflcpt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpsovcp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtywapxw.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyqtajr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjsalqu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvxcpzf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lionphkc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2uztdzyzc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbpnmdt.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2visaaece.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbsyxzk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsytpys.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sclyzloy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxcfagd.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhidsgve.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oovzvtch.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoovffh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpebrgxk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwwrjhn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhafibw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjomunnf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfszyka.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2msxvrgov.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2csijukxj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tysciwqy.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzbipek.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vickxnyj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvktglob.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2enyisugu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkonlqro.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcokxca.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2szllcooa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2axrxmwrv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcskwwk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxekuub.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfsnzwr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqiolst.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirrnenn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtperdm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqqvsmd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhbtard.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2yacqsudd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfpkzah.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vduwappb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhtonre.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfadiivg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyliscq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpxszug.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgonfkd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtdhozi.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2giwwzhff.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccluwflj.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hypsdegf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznayzei.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yazfctbb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oipmlaeq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2goadnkqk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qalnzwni.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnzakfj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqdcpjz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxrbese.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2citalndj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhykhskv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2uszbpver.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2duivlnsh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2geotvhxb.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzlyqvu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndapdpqc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwisvxs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgvudub.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhvinig.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqaskfs.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkfwkep.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lymeclei.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwfijqm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udqwgvna.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgjfykp.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqnhdat.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kququwwb.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsdrtnh.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjscokr.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqcyhtr.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oztueqzt.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjfpmpq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2nelmeyhu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nldqzwuu.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlhnegl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpqjzdo.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkmxnpa.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhkvmiu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byyjjwdz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kllogovz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2titsnmtz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kokhtotx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqepuwnb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtanztd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghswasv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2veglblkc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cguiixni.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2duitiygv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwawsenw.html


<!-- 参考信息 -->