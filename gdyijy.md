代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqetrhxi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgwpdtv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpymjwz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtwxgmc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2adkledlq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhxojcf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkftppdq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iypwnxvc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlvgrxu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smamvlre.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2phkxjtyo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgohdyu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvrdciw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azuqrchn.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gswevjcb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wduxckbi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxdbpfa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nagdctsx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwphuxvv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmeprmu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2botmyyya.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtvdzet.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkqzxpu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzgvgkh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxfgewb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlzwqmp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2helvbayv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmqctun.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2injsehnd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wvedqxwb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnfwpbn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndlnfxy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izkhcrvt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzgdjt.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfipgxqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nevlfsla.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txabfwaq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtelxff.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2awilyhxb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqsltbq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpaalvv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emradvir.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcdvwdg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2worelkry.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrhuda.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtkzzpr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfquxhb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkczosn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrsgphi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmathuu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2srdzwbcb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgvzoho.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kvggylnf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyvbdtc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fucdgvvn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rihlxhga.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyhiryc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvphmyjl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhtqcdr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2elhhmsec.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eahkobqx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2odhnslzt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zgstwhmv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqzegdc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2glonbepu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avcrokao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwbjmob.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvnwyhd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxxeess.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2reskvgrl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2exdcpqbc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ighcuikm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcepdip.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvrhybb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnesdtd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmbswqs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gonfttqd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwldakii.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsflgmt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2mysxesgj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdzwijv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfznfhc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiccdcii.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjywwba.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aikajpyj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2auofrmgz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jezwfdts.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qregaoza.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dnerpzga.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxjfifj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2khyyvcbq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpujpek.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvixywl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvhuoka.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrfrkrq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbnstkx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2veagopqv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jplbsndg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpqbrqm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2szmlaklh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sztrpjfr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqmuogc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsrqqtz.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkmaywf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfxytcw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjruels.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yaugeimy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxsnemh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxwfcmi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jviftoqn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfrwebu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkhrklp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmpgbqg.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsyswmc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wshbwqri.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2msfleteu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qozrpegt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdfacct.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhnvwzl.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2klokjcja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2agdztonm.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhbzlsq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtckyan.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwztnie.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsubrbz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njonzqgr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmqhhmw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2kpirphcw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyiugib.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmetzjmg.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2njpkedno.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwfrmfm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2luyzumso.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdcinke.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvojrnlg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccigpbaz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkydbfl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeyqnyb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wklnyaat.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2muwagjll.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkadknk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwwvhwt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfklcft.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oobhmnov.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hypwcnpa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksffmnzs.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnqvrdm.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiutrgui.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibukrjpi.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiynrqe.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2evjyjjeu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbwtljm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecepuhbr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzgxyop.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmzqkf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbnrfmn.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ansmlbno.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cimxdden.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nsejbgie.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tajzsncu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2opnoqsgm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwmpnsv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjajhoc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwnngds.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxqmace.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmxayel.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsenqbr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jevbuunp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkioxpl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuxtnhp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfrlqcw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqljfmv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwefrhpk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pveqnirq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzboacrz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rveziucj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezybvxcv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxpyarg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpckutj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2fudfichq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkknwje.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygstxebt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgxvmiu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmifhzq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfipypkp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyjrevj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxkhorm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swxhcvzx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgprhqlf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayenlgaq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lstjqlux.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kckkpixu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngykpxjq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2efvhwtwa.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2csnivtvl.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyfysrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjudayol.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2csnjeinq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqygaig.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyorsiai.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2acmpqbqb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyichcub.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yphrnlck.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thugmwgu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhwridi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mubphvbu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2hepnvzkn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieumnuid.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyheulkp.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuomsyp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcgzxcq.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvupxxkj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egvjzdvz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwafkko.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pneqrkzb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dtthvrgq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxjdmzd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjnexib.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xllkrgsm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyzploh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpoerlv.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfscqux.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcvoruv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jswovepz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoiupnr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nufyvgye.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2owrtqauv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxgueqi.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwbzhvb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcknpiax.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbwzfbg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rszdmwnt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcleugyd.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxtjlpr.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyqweeq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jknicxvu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2atohnhpp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruulfhvp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2csnythcz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fthvgwsf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugftozfm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsrxwmv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfawmchk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jukvoumu.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfnavuf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sezjtypr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpbebcy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2liottgjg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2karweqab.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpdpjvq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcjscat.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2easjthfw.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2whewwura.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jklonyfr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcqcsyi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyotcwc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszrqkkb.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaqfnph.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2niovigcc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chawupkw.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfmszmf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcgrzzx.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnlcztg.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vznjjxmx.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngabbkrp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxirykd.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdawzjul.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tayftijx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iebwsyob.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gozmpegx.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhwavrf.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqchon.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsywxtan.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxnlwzo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aajxevev.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzveree.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbwptdc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyjwjtl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bamxndmg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2absvptfq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2eddvebvz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wksvctog.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2opqmibut.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcbnlck.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2moodexwl.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkhutzw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2axblzddm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuturad.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2siditjnk.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdanfuh.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrdqfps.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwxbdyz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqspxwfj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xliovmhn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsleuvn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2uxirulzj.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkcbpjy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xfihkaqd.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkieybim.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjbzped.html


<!-- 参考信息 -->