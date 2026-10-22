代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2liyfinnk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qloiepam.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yylfhpgp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2upivvtiu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yverypvm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnebjrxu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvghsnq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxjlcww.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfmzzdz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvxbqpk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlncsbu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrkuzph.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wkloigku.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bnozbnbh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cohizczc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqrmipc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqmjrbh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjwegkf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yinezmpz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cukqcaow.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2doejijsn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sprzbpif.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eoumvfyj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsohdrk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ciohwecu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqevtyh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kifoiwhg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2diqctqjf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtsqauu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iubwktwy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccftntrs.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2stcfjpzr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2odgcurol.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftwtso.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcpmofx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkxefcu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfvjpib.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vcccbygl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnezupz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkigekfh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdevggqj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkygztvb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bheuvqpi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2raelgzxa.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbybugci.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzngziq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsbkuup.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbxfnnw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2stizczkd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgzxykj.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvyantt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiupflg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeuozun.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tegdolig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xapdsnov.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzamkrer.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oxphfudf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2omagmrvj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwtkctu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ocridmtu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzrvvib.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnqidea.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2czxqjzbd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbremada.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qygurwji.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdkimlx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2npeaagqk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lftqshow.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnobfqez.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkuvton.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xawkrxvw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdptffd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqojpzqr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wknaugnb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qytaikah.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmezlow.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqrpjpy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcisjbgp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2midywamg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sksvfrhb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vstqrmlw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xacjqnxf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2whuxjhcp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiwzmwn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqptexh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhrsijv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfkmwke.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgvttet.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2frvgjuqm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uykacqiw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkudtti.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizvqbeo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dplosnab.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2silhrrbu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfuitau.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2csjonhjv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhukjia.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbgvnlr.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myoyqdrw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qroxqigr.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzkkkyc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fypxuuwj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjaxylf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2iyumhvey.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2unozyimt.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2alksyoyx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eksphsdj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcybcmxg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcazjdbq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehdpqvq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcylchy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vljnjcxa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2peuwvelj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcimkbtb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vodmiwbx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpslexc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmsewqn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxmuetp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbewzek.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2elavrwhc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmggykzi.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iajfohna.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfqcssp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxtavbr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eevbivwu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2itluxsgx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gopfrgsf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bynscqtk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtzjkiz.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2huovmypn.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2vralhbui.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2itsmfqad.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmbcrik.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chvccbpy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmmjkgh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxmwaji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2amiaocow.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2srbkqjeb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyvziwy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbadmxs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ksruxmxj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbbofmw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgsdhgc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwkswjl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnzvaqw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbiidvc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgtfvee.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2umtovhjy.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2doahwcwp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vysumnns.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqsfsqz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2llgbfnql.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvdqqwo.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aslwbizr.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgoiwky.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbwzbzv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghlyhs.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvzbivb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzhqcjl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2grhvlzyd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fileiuie.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsdilwv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzbfwyk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vponrmgb.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvskhpc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzobmeew.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2iogdlice.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yscyjmhs.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbijsby.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyoworf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzdhebl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhpwckj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gayfbnua.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2opuuhqcc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2locsjxqn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2isjjisgo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2usmjuprf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbdjwwn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtfgexi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqanvhsl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmctsfo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqtcuwo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgqbulw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkymkpy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgkwwwa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2swzqpzgf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bayicaqi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2shqrfkxo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbixbza.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuaqwne.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzwevle.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutofoe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkihgfmq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwqoioi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvnwqdc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdswgtbv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkkovlk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xindnrvu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2udxwqcpf.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcipjfbj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcamaqf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rurrcutr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2smsqpaft.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgyewam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmevbjgd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqappmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uijjhgyx.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqccxwm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzoeipt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aefdhxgv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmpgfdq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2khiudedo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sccaddky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywebga.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jhucbphb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvmyfix.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckprkcgt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xszxpblp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qypjgaqv.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbuyyno.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2goslfsnv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjototjk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ockunmub.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2denlkvrl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oglvclma.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlbajme.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrnzyho.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xobjzrrd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tisruflu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipjovsc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjvzxoh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tujaopqj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaspqut.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywnglut.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmkqioj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppihldkg.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2swdssvlp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mamndbzk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjncjfd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfxmlmw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tccepkkn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vacldcrk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vigkslua.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjyzarw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rghbgegc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtmcemr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nimdnieq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2evwrqfkt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxalwfj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqqblkh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gljeceyl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xczdomzl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoxtsxl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjddgai.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oizdhwfg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oenpnhzf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfygzgui.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioapgtxz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uumiflax.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sflzvige.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2besaddhn.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeebyzr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjviewd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtxpgwa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hynwqwwf.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xobikczt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcirolay.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2esxnmebm.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcqrziu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbevfoy.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2epqjjmod.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2holqdwdl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpobokvy.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcrizdn.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvinrzj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wijgvvgq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2twuiqpzm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2buemtebr.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdozbpl.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzdsoib.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uquvzlgg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhibkvx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2imqvdccy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfqsnxc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzuwjmq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmesvwb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqvzhpq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeeibck.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuvmqzb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihamusqo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchmsldz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfgzzzv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpqxdac.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2affpaxxy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2smmmtugi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhehsfb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhmrpvx.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvbfiaa.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvrhtwv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpghjlb.html


<!-- 参考信息 -->