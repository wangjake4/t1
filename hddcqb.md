代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pishuiev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vuovnmal.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbhzkcg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2brrpjitd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtbfcls.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2raaujmae.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2viykgbew.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zalzqtjw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsbxxae.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzzheuu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mempbpxc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrowueu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zscjfhxi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhygxrl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2brhjsnel.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuvytwq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2myiyyone.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpspsie.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbezuaos.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wswozqwx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chxkongt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gxitnjht.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xywduhgh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaovojzy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxfvgek.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgwyzqy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdtnimw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhaosrj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxglohwd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjhpnso.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jodglktb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgqfxaa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcwtmjr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkfhiry.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2majurlbh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrdjfkt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcwgyxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvzjxeg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwcdhbo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaegsrpq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnxqvnq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwbvbvv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhirvbx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uumfftgw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cygfvywp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kxorqppe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2arkkpsfj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2imlsymsq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nukknnjv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvshxua.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzllbpr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtedissb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrcfyrs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yegzlfyv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdwrbxq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwtutyx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kecpzdow.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiixodk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aorerxjo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxmhzqb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbwfcta.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klwrdbsq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkypknxm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuibyxi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoeoxrs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkbgepn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzlipfg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjxgtqd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ancfujqs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sydqydjm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkfnugq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swpbpzti.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhvlozr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dagexbqs.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoeyxdy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxefrwx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgjjfnd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuiueej.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfskbjq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2pigjczrq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2crlozixn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxciufx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpprrye.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsctyby.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2slyxhnkq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmhrxzo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtztfot.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaomkem.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlergah.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcvvsbc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwezpvm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exjybpvn.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqijdvpl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpfqbtc.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuzmwwl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhywbka.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqssykzz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqdpbgc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiamtqxi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2snznaozd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdtqulw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuzfjgp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhyshug.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnoievo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgevkprv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkjworp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dodfxxva.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjimurkl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfikzkbx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwkqvwm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkudyhbw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nzytxhwr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mivlmjpq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qovudous.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2muugpiia.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbkjzgy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrllktjx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnhbgjf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ultlimuv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwllcbb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2utidepqo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzrbpxf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2emizpwzp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxwrfjw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qchfxbwu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2aabyqyve.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gzloollf.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnzxdkq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bumfnvph.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkjtshu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iycivibr.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcclkybg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifalbqen.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyvvzya.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iljdqvhd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbxglzi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnygfrq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlsndhi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmvqvdk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbxqinr.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhfjafk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazitkax.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2tjziasim.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2odlzwbvc.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2yteguxzd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2deervrws.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiwvopm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkkbdwf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nptsddco.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyudcsj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzqbpwm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkpxwwx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqlffmq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hewfeynj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyntaqe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuwekbt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zknzmgwg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2voeqvjpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwqefmp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyeazhh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtipptge.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsgszxt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rbovmfvw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvkubac.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcmpssw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxwdohe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bshuoxmw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdlcgrx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnalnnu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaxazpf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bixlptuy.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jheerohd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iddlgsvb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epxdkxkl.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjscejp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnxavvy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ictntxrt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vojakzyq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2heotyeqx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdmmzlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omeedjjs.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sahejfnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsctswz.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcynoqgw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2esuvjxup.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgdxidh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xohwnbfj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oibbjrhb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcocboi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoslthn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2miibfejj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pytpgfpo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htuetcmz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmxyleb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2larzxryq.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaktabp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oenawkxh.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjdhaof.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmubwyaj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhpqeyc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxigzclp.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqrigse.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lltpcsbj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwbyxkb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufrzibm.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nshcgxzx.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufadrhrx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rahllmqn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2adiplmsc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcjlyqa.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwtiauf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdfgvyr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqrvdkz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuiakok.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfsmiyh.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgkvwwg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tihokvmu.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdkdflu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qehztcll.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2plymoxmr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvfxlxw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdncxyg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2deddrxqj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnooqeab.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvvjskw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2civshzow.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2inywgjlp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuubglxv.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgptwmpc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrlelbh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwvjsij.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2houznidj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2echunmdj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tythezss.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvphgz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaclrulb.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvzeuuk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2htoyfuuf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxuvzol.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rspzejks.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsfegsh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfqqtgi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrgnhuz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqthgtr.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2npumzewt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfwjfsd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kevtguad.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqlmcau.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkpqku.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjagrsac.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdrhbqh.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dadkizes.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvsurge.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2txoqowoa.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdakfyr.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ycurjtpn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brnlaajb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqescsoc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnggeaf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqvxorv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iknfhuee.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjasjzn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbzslqj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwcxfgf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2djkufdgc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhncyqad.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2arvjkavd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pattuajs.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2evxpzyko.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyrqwyq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwtuckw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmynhqyl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkfiksa.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jujakbyo.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhpmsaz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjvuckm.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwywdlop.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnefqzsy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2loxpktem.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcmonnz.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fswuuxsb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxrhivw.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2otmbajkp.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehngyzxp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwigrkd.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtjwbns.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xadgbdhz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gncjafik.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwydemvm.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhntcxio.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2yrewwpvo.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhwgmjk.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxkimbb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvslix.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfreyrn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvbryey.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfygdxi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pntdyszq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbvwnmf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtuwlni.html


<!-- 参考信息 -->