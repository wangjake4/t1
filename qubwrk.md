代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkugqo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xetsjdvl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyuurzu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2okuzdbrw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymqxxwc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggzfbcu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpvcvux.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2klvgnwdy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wgedydzr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkbowsa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfksodg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzxivnw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avksfcfl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvapeffb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nttclkcn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdzfcnv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrrvhkw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmaqvvi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnqpnfh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkozhlkr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2turcauvm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2alpbfrkf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjunmhh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnyszi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbettfz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpjnnop.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzupehy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2edtilrzn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoknqml.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ryylybpt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzxryev.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuerxjl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqsinbu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwbuzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2btvqdsms.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijueuwjm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgczmnn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uthmavte.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2evifnhaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2duezooii.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblqmxeh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmjvxgl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoxlxat.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcxwlok.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlrosgy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbouuhk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbmfueg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdddaevl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvmcldn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2odwvrxym.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnagsdg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuhship.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgmzqob.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgdwfoy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xshsnjqo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2izttasvz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyzthwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zetsjgku.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmzjcpi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgziicvw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchsidt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pydirtne.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjsssyw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vxavoieg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2efxxctmt.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrhqnxq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cscqdgek.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgmrgvt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2msxsgpmx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxnygmi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2byvrmfwu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvykulwu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejgrwnq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoxaafq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtlfjtj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbsfmow.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvarlhji.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwclpqfk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2joulcqov.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfivroo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbhdbgz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqccgqie.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrihodi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrvyxyj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ighslbpn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdhjwy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjikeuwg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpbpigy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmeoshq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2alhzyccp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uypgmspc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2anlgerxj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tocjdrok.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vesycnrx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fomxvoej.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ygikfafb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiyuyeb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrsvhtq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoedsli.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rrconaug.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2krmbpxdn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxauljd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2buwcxczc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwhwkeg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oinazsna.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqpxysa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbpxght.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqgurcc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jfezqwit.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwflwpry.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqutmgri.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqszxom.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtosqfea.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrubjebs.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2obcusvtl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2czlnmmgb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2opogdxxu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xeleepxn.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2whgrfgls.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwlttmj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xmydfgcp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzcxdbc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrxndxc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwaqtqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyutswlk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwcsxzs.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2lihahtdi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdyquwc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2djqperet.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhrxydt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfijubmb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrnpxy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2idzctzby.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsjpkof.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzafoet.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjegqie.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vrphanfu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbwlnxx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwbywad.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhshbqil.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrgviui.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxjkaxr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfxojtr.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdjwfiq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2wupgplvh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbzaquc.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpnehwx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hyleyznd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2srtoucbs.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmkzkfb.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eucoeavf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtipgbew.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eitqkehb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2plborkom.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zltsdrvq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2spepkrzw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeisgmi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hskungrn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqogpucu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2srblqynl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxpwtde.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhtsuoo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rascuzvy.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmnlzrk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ouunuixw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkemrkt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdilaxk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyozuwop.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nucqhoro.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2lclptrgk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vygexexi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2upefihgc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyadnbh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcpjfel.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgsfdw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izjqxsjx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphmbvyk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sckvyajd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2caemdbxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2utmpudwx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlksxlhc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gblzewls.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2sujstxrg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjglqfgq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvckull.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdntkdij.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrcrjat.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgzisfv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2cljcnslm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwijbpb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhorlxmp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krszlfqu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxekhxs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaaipzr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxsadiz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqoxzly.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2npqocygh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbewsbeo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzwihhs.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgnmfdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqfvokj.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yskjclnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elggfbff.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeyaqei.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xudsjbwy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fggjpwqm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zidicmmi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfbodmu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wktznjsw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmkdntm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbgadob.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeffxwe.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwijdlm.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrkvukm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bacgyvcs.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjtpwgh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpkmtgf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhmddqh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vafgwkcl.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ypygdbwc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwmezvl.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvoyuqc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtmczzm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsclgpa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvrkhjj.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cutvsqhl.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbduplms.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwwaxvl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdybyvkq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phzjsyvn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2owoxeogi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnxumgv.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzbknzl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqfbfjo.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuoakqz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2abjwbvkn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeypqlev.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyfngye.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfwgwao.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnvukau.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkckistz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcspboyo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwfsefo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxguxwgu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2isjtcluj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2deeauhjc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmyfbxl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgqhfbw.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsycicit.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apaftzgv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2odsaiqbw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fadbluev.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxwnhka.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqdoaag.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vouqhzpn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zviqtzav.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbntskro.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtrswcf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2zqupnykm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2njeblxbv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxuzhjz.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewohjqmf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfueenzz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2stizdxbg.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhfbimj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiehmya.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wrudncrk.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnoxnke.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvrbxyt.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxdvzcg.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjpmdtx.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqwgeph.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuabedhd.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2csxgbcsl.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvhgwta.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2swqpuuom.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmekkiy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2clbnurrr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cteneuwu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhglnqgx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwejfvth.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wthldsmm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfxxtej.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aztepqpa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaexbjk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyjabey.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsltayk.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mksbqjwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfkzyab.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2oomjkukk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetqmpoj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zztkkyrv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2txegrojt.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbiieir.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcuckkj.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxzwffz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgtgykx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sojxncvq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyktoocu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcjhcvy.html


<!-- 参考信息 -->