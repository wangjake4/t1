代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvdrlni.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkowqrfk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gpikbiob.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdcsjkd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnxdyug.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nveygjqa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqenbdis.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2osllbaam.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdevglg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcwiwqt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqnslui.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbnxwqy.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqmikpz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcmhuie.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nekjtqcs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqkighf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmxggb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvsknpa.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqgfgkx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvptzddi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oojfhqxj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfddsfa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lomhthmf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzedqndz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2feldnqvp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fisporzc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcditzf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghquvflu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrtwciq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2viurviuu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2prnnkcum.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2edicanzz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpnsmbc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcslluvs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrlinmz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdsiskl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxwpxkk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxcdoqb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmnjcst.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfbgshe.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gltaecuf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdtxjvx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrffgfhc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhlquse.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmgyqte.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpcjosl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmatqcvk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2nktxjvyz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxytqyr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjgngna.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sflrapbt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxajkzh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pjatetrb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gsofsnwc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vewnwldo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qswnapcj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzbpvhd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdogwdfe.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwvoyz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjjvdnw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwelbsqc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcgsoqq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgntqqbi.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fonbnlbj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyhamop.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ekodjeus.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvozusf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2poqshiuj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owcrpfiz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2omfukrne.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqevyntx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnihrvvz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcpgcso.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2famifcvq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2exauptox.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmygxqpg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgfzhnk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izhczlvw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuwsbwv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2deamjagk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrgmjft.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrulqgf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdobkibr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2scesaeio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhasesg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bccpokms.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmzlvau.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuvcscj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyyaoar.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwrrqse.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcimcas.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skatcqbq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vbopifsf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnaxalh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpmxlsa.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjoiucj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqptolr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2sojzpqbe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2oggofaib.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hargnbec.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvyelao.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rneeisdz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsszzcl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frprwgsy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhxgtd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpqeaec.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmarvdq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2uuugehzx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfqexjd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbwhbkx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxhfdcp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iogsbglk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icwexcnq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlagkeo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdrinzy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oipjrfxy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plhaaquh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2llydfhyu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqijoarp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbwfiyy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtuanmu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2azdusmtt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdoiwch.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlncqzv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2etekbkwd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uxismqch.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpnitjf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmbrxpk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnidwoo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqokbxpr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dycvcmgg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcxdadt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqhfukr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeyequy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2btkfrakz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlxwyrw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zocoksbf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxeqgda.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lceqcqhd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuyiyiw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnygzb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2btzgtqap.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhdghwt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjzlexc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvareki.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hppbjvwy.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxkpvyr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvyxiwx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aykjawtd.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chpgcibx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmdjew.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpozfafe.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvoigom.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxevovfl.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nirufbkl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2shvjwvew.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihkfrla.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxioxkg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzixqmgq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ehazwlzu.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpxsywk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyrtwik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dmehuyxe.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnxhnhc.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2tccwagnw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eblralme.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hndujzpg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lppmnmyc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoeyehn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2lccdttxn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qsefhcje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2dypjbanz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsogjpr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2znnyxecx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrsrrsn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfenvjoq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdcnxfr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axwffhmj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xywpkctv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgviqwf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmyfnyp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjqkvts.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbblcxr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkpwmdi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cgecfkwr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2taphzhna.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgowpxhn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyrkast.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2khcxwccc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwevwdjg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeymacb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmlsvhm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuqtavp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpxbcm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcvadjl.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fegonxrg.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxqaodd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrlrgor.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jixcomfs.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjczluw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnrkbit.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gyabsdxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwowixb.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqkscpp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsbgkvs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomzjjcx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2klltljlg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2umvvmrki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2orevvqud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rebxgtpb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdnrsgj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioordloh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2csnxacyr.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdlegip.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaugusx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aplrwfxo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pipshbsc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lesmrqsr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxginpr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2plydbvbn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hchvstmk.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpkigva.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnctogy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrtpjcr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrcwlfq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwpgoft.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfajxaz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjqozuw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmxwtc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oulmsejx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2nsytuhkg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlouphf.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzdhwef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrmjunk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrwjsmb.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwjkanb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdmupch.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoidwoq.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruawecvn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzdnvlf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfhshga.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvhmwgv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuisfsz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2terpfqwa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vknltmsa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhijtqxi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdibkdn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uecbgdyr.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzthjyh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsypyacl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iysmadfp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2guctnbiy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuoxylm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqfryun.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrtfjom.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yerdfyxq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uauazhzk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhcevbm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jioowbue.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxygoand.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wttabhwo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbspnydo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogutzurs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxmgien.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmuklbc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2onkdbbmz.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oinfjwto.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2phumjahj.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2odxwydvf.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgikmdx.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeacjjce.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthtskmk.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zchzulfs.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqqfxoj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmtiodj.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2plegvsci.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bochtdce.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeiznfo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wroqxvhw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxrcxvh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnskzbnu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gakxlujt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kblhsqgk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vshnatqn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ksngdiiw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vllrghaf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmwpzwc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvobgwo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlmuoal.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwtovwp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwveqcm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxbtjts.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaciutp.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omgrbjgv.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2omysyhsk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2btjzyytr.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqhlwmd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qklssfry.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxruvka.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ramiosmh.html


<!-- 参考信息 -->