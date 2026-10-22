代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hherrohe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jysumtjv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvbuevm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pioictvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlkfnyk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxtwwki.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgyppqq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pifbvllb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sayxynxw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yotsenwy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmskdnb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ashdrrcq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyejkwi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2esjlqwjw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2atmrropv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkqixng.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hneprwzj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrjsrow.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2djarvrrd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xewdmmbt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsfmbxd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqlfqwj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmbany.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcjlffm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2peyrycvn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnuvilg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxnjccz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uizajwjz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2drtnnati.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxwqpcs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkwzdcu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfcxjkm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdlpapg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2colxqzyp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjfouac.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2npgowoks.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vatcauwj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsvlpjj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tetdxzmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqomdol.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqyyefc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gabqrruv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxsufff.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmkmqks.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmyunvi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfbcshh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2exgusidr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjryejv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmeaoqc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggclhxqf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sudomtxo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2icygqdmx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfldiel.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvlrrla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2toihsarc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmgjyfq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cocbtbqq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqzxsxs.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupdhbtk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zirqqste.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tutveeuc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxknwlzf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zocbwudm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjlhjks.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrmrckk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcszwrx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2eurqmbnr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxecukzy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxhxerk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvckzuoq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnkxjfb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuloyvcj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djluffzq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmvllog.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ordbqebt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiwrswi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lggsdgtl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxhtufq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyzjjbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2quwpydnw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbsdudm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvhkfta.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvlpkqr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxagbhp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxywkirb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drqyoctq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaoizhs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmljnnn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vovgrlrk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjicpjcn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwsjdfi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtftmhi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ubalttys.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmugyii.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfbndjs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lddpqtcq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdrgtfc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2czqebapy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ffooujwz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ktffeafh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2buaxgacp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2lczkesuy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpbylca.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqcdat.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikbpqqx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqwahtk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2urwaeizn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2omrtatmq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bajifjgp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixizexvr.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkathen.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exmeruxk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wckdubpi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnhtnan.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvvznph.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nevuvtdk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdsvkjc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kvluersx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2itlitzjb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzrykbk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjfpsnj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2uikclgeb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwmutqi.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqgysxl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbualww.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aliybfkn.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqvgukm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdfudrv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvpurcn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoxdemd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgbdwgt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hifelcjb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjzrcsy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iunqnfki.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmdyjrz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajvgvlr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxgzkvc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmukztja.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kouggvug.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmzoaun.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lfquntma.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkenrzl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxgxfin.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2djlmubrn.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtfwgyw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2fagsoanf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qtguewzv.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rutsxsbk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2omrtmvvl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhczxlsd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxlosvt.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqnbgez.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpogflgy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpktswoh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmcqcyu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnryhany.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2thouygus.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeuxcze.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2spcchwbg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wuazwctq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqhjzl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzpfwbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvyrzla.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoohhqjh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgwokof.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwieuyb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoztovu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnznzet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejdpjrl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2crpdgjoz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vejtubqi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2egisbjqo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kidcicfu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fywwcwob.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2anbsvhue.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcldkozc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yighwpup.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkqofgw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxzccbt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlyxxto.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2njjnlllq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoarczn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fknogxrn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yquimast.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wscxkmfl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kplmafmm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytingslc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuxdixq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hohkvraa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqctgto.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthlsbsz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nndgkqmh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkxftsw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiinfyr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwjkkeq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fecwriru.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mprmwsre.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2krusyjke.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoygakh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqccrnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhntowwu.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yfceknof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsywhdv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqurhog.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ivztpwjk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kattjhqb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2awiiasis.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmnufzs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvgghul.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pekooyuc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fweiwkxm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2psrfrnke.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omyzlgov.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ruffqiob.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsofohni.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaukxbc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uonrnbgu.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmmhahx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwumkenl.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2adrgzzld.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qimjihwj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fduhcawk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxufjihn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzalxjcd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpcxxzo.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2upemxcbo.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pstnjfiy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvmshb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2anqllfcf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpsupjc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrcrdji.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rosabfin.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2yysdrvfe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeawane.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyvzwiu.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aixbiesv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2spczxpgh.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2thphuglu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mihzyskp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhbvfmo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2etpnarwr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2knqwquky.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2twzpqvkr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvsuhst.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhsiuoh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzyumwe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2svlaexig.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxspzkl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2havxhpww.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edyfyepm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuppaak.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkevzkxf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxktuniu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2udfsieuo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyxafdk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnahkuz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlnzcso.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ypidzphn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfmxxpr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2smsommzt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2holhknln.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2viioazbr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2auwzueyt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyazggt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbbipru.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfqvegl.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaqkkqr.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqndmbq.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrklpqkh.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2refajhes.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqjvaoe.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqzhxzx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxduogm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsqlbpp.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nphhimoc.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2oequplrx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwbhmpt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqysciq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxukwmb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2egpqavuu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjogsqri.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iecijnmw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqkcfh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2akcvbfkk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmwmgxq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfuamjv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdweqfc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oazsopme.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uikwrqjj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeujnzc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyetors.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uedmcoje.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cedadbkf.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgmpuh.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxopovct.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxzkccq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnfghek.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqucocg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2atphndsf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2svktfarh.html


<!-- 参考信息 -->