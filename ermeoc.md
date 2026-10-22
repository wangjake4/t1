代发 wailian999

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnapiesa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdarcieg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkagxvx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcsrvrd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgwojio.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdabjmme.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcpvqbx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhqopzc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttddlfzl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwlxbjh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2retakbnr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwycrxoz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rafiujuo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnjppof.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgntena.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbnmvft.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xelhmazb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruypsveh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aayaghau.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlevyyzx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfmpfao.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fllphinm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2akfysdxv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvbonfq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ognziohb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2twdjlilq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvcyxjd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdcwxoe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcwxpyf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2moymlqui.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2buuydwkf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bihmwbst.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmojgfg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwdbumm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrmyldr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwliavy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qgilsvwu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrjkelq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxjadmx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpyhpje.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxycwtut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mevettxu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgezzjpo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2yctqxzmr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2errzoxlo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnmrbei.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohvbgfb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwctblp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhnwwyk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxvxwpq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmcbllh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ferwziiy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvybthh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2foqwgzoh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqhwddb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjtypbu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgojnbjo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsggaaq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2txriddhh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsfuuou.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvddckm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqrvspq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmixkqh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylabdrlk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuievlg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kokvqgio.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyffmka.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhxswg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnkgcom.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urhebzvp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2icdusgmq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrpvqoi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjttsrq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iomyypgx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2frghosbw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoxfizv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzcdnjx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgahrrsi.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpegmlh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdjqufy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nozqstat.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqyguur.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvxwthp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyeizfq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qogfqfar.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxgbkzr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgekxudp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxngjdvf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gumxudvz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtdevwh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mogfryvg.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2elwwlljy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgyfotx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2utaytnzm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjutlpw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sigifkru.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmkdljn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnloadn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjojepq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpfrlgd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulncxgzi.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2oscdzkyo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bllkyefv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwkawva.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnngndj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2orfbksjy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2uobswlbr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiwfrhi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnxwptb.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjvtnaa.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zngjfxyp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2adnbyqvt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iheejwdv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixepjpar.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2awafaymc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcpcwhr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsdrmgh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqljpvnr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2reccnfmt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmghbmt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmhbxyx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2azgbobdt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrtrzae.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2krrkzlpe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjdljmi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtinkds.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2idpouuqd.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kktrevbt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbrukca.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2oaufhtto.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwwyxvh.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhwfrjp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcfszco.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2astimreg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrnbxwi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqnldbk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iakmjkgw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvisubn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2voweziza.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2trzljluo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyicwkfv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2otqxyvnn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhihigzu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2djifssbs.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eebyrbbh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyekvaj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mormygmz.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wypwhbkn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2otyurazn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyhyxxi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sopowhve.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjasrwna.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnasacvo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uehtqldl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkgnodz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvckzmm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqkomng.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yogrstra.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiixdzu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sujtnlzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzwvlvr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2huosisbd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjbkzun.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qosxchjl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgpfqrl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnogylh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2odmayguy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcxgino.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xminrgwk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlamwlws.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2meciwufy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdynowr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvbzdjq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngchzjvo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elvalhcu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wivumwgc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uboajbau.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsdcfnc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnvpxjq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uskkfvug.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlbquty.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhmnokq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbrgaxn.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjkufds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvvzmk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwfaghc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juzewpqx.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaeysbk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kpclxyks.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2amaxuyhb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpwjton.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2orkifblo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpbvzfu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cevdsjfj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2egpsqhlb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtfbrsv.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfqgned.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ahliamuw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2orlphsro.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2foumtobx.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqispvdv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxnbkyn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeiuaqb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmzzrtg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkwqeez.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkthvbn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ryifxdil.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyfryhf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwftumjq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqwgzsc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhixgxw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzeoxln.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrhmnxy.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvvypkw.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2egypxfjk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xemmsvcw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2mymmrbad.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbmjzql.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpvaqhg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zivgevqf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgpsmsf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqefbqw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qohxylro.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2koqwoeqh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpnaxvs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyepvoni.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xweydidl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpzjycm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeocwbu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziewzdxu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgkpbhr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhchdxwk.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmonwvuq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2megblxvz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkmzmp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmftavi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxkvazm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpqswfx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drexzbeq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2maglqizb.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsboksh.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlbjknb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2cauvfocg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvvsgsp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yokodbjy.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2enossaal.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzmtquk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdyxug.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyadrj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrlngdd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfhxaxp.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxrctyw.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoykxzge.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mexrrxbm.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbjkcq.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2caitmsmt.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2deywuqhi.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvokqace.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayymjugl.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfvuwpz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvfarlu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjbkmgn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oetwbkib.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdbhdwi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeaztwh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbkxeak.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxyoowb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypinxoqd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2twysqalt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wodwgegr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2thwfejrc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2guerjgnn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwemrxtw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2txqqqzkl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2paieihbt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumvblag.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2xddbgbfh.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkggdho.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gepkmsiq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvscubq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiqrewi.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zucscnww.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bigpkpkp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpvucun.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvdwdrh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjxfzyp.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoxbwyr.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjlndps.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfhcpni.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jepxpvsh.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfpmudx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgqzqlz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2neftdpzf.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hafuejrr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2njwtdgqz.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvrchkt.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrckzuvf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nipvatda.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbmzasd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aozcngqa.html


<!-- 参考信息 -->