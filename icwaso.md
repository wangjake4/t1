代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wserfdwn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2frdoawdk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfwnolu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yunuiiae.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaytecam.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyusxrmq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccseyxbq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2svwyflfi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfwnhli.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dydqpdwb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bupylhbr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjddet.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pohfgwfi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxgdnkv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaekpdkd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdyzldb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnelgzr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stafckgl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbuueng.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfcwax.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvtzqvv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcernxq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2drywqzzw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogololgc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckyfph.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xhothilt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyqmdfm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2riuleesw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjovncty.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnewwlr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qreqfumt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjznwgu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eokfhbdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwwnrfr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aakasdoj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pppzhhrd.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjvlqhv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmucrii.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nodhwilj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2eylliatl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xgejbcck.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2thctkrds.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvynrjml.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tdihxzzc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfxekoc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2nldmvrop.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwbvppf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oykkovzb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2byieznrh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewxfkv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxsjaoy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzccdzz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tudiueoj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchzpfho.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkisvsdb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wobfskmn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhqpaxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nesgovnk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlazoblr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2riznhccf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbgtysd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2seprijov.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdsgwcv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwqrhoy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjvrsld.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hooepuly.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjevclfn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lozprxms.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpzbpnl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oefsyyzt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcawiyyp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlglgjr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkjcnxp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsuthrv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sltmgjrr.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2goiwnwaz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrtpxop.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmxhufv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeupwdz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2buumrilb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfmvztj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvylboct.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rychwdzq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkbyaqz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2klxssfnd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzojlkqc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwdrzlh.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhuiena.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkdeidq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlmayqx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nngzrqad.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkydatp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggctcvsc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdtrhfy.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hweosikb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvapuwa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2afbrzuvj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hucrxyti.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjyqtsk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsjmjyh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgfqyvg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsrqjwu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaasngq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjthiszj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dydjtywe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2efzqnale.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2thsaqvmr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqvzefi.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcpesuj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2icvobfgx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vacrtopm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2exilpnim.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2elkroyla.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmwvika.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qextnvge.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwailkn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2klxmdbgc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgvatep.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzerapv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtnppej.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gogvnvui.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2leuhhrjy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2edrubckm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjvepox.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2arqlnjkg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2upjtdejc.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2npiavtwo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xiccrykl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2exfzohfz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyczsqh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmrofkj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwzpqcd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyixrsg.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2quecsihs.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipebfcvy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgceojmi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbzehue.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2icxnjezs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgilnyf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdmbgwi.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjmuzxu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbtbqjg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmgpdu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiacddzd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2cobozmrd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzdcdbr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwgrtpi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jifdrynr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvdzcac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2slslwvar.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xambcfvn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvjdzxi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afjnsxgq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luxnvrnf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwydfmk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpbxljz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrllvjz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjdywqn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xozkyvxb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsomyqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjaybwg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvurrgh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrleerx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfbhhrt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ftabresj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafroeqo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwpwmro.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphfnspq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxfdvzx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzqgdcp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2virnqbgn.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrbpyvl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjhusrs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuyutzu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfpwtww.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtraeszl.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2brbbcsln.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vntehudp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbaghvl.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozipftmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdplblx.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwhfts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evoebedc.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzwcjmv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtqbxni.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoxjouo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhpznvo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bclbaasp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcidgdto.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mswuxnzw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2owgmwlnf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjuktmw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2waygkgxo.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tvriipvb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkckvsi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvsluml.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqulvtow.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfysepg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmkewcz.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zynhbzpb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2agfejnuw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rinxvzsb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2okqabvjk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpawiggy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpltzam.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqoagfq.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvbyfcu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzaortb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uleuljix.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cybnhhyp.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2juyfonmr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fitmpyov.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bskantjm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvraaxy.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlnsrcv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrfhajl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzinxsi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eijcxaaf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgdegyt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhqfbap.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcdbiaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2daxvdikn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrukayq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfbecue.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjtohhk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxiqiqv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyjtotn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwszpulq.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzltgeo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpznkipt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idjwubmc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lryvbrle.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsfwnwf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2raqvghbe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqcgpnd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyspifpy.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqefyuz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnsqdyv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhopsyv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfufldg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpetucmr.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2urmhkxlk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuamloc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvnplwf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuqjlrf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2plnevufg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnijwrg.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezknlpzk.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnlhdvd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyeuaws.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpclekih.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvfyziy.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nantnuap.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwtvnxn.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisonxie.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwajqpm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2surdiooq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2herffopj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwiurfu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvrnatb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiijzze.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hshpfxos.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbeszoi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqymlfbe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2wzordgqp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeoljpu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbroqeve.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2govkknun.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2njpcbmux.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkgplcn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2feszbdnb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctyjjyr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2tltxjexp.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gacaaxms.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zifrybjr.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oohzpzrk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtibkbbu.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2atstiiiz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vivlkfuo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwadkiu.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeexdzn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjblupgt.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhwuvzm.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fytswuwt.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfgxdoo.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvexuaq.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aicarhdq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2scbdtrpl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zudxixda.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqehqkar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2idatpdff.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzptrea.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaqppuo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onwnlugo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnwaoki.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaqnzyy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvvczfi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkhcrsc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmsbwxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvgwrjg.html


<!-- 参考信息 -->