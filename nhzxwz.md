代发 wailian999

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xoylrqjp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnafxnmd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzavtln.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqjuic.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzbitoc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnetnh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2buppbgnr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhzykvi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2siehfumf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rznjzmas.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mciwexlf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsrlsls.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkttgle.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2givrpvxt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyilfrzf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mucdynmu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcefqvur.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgriked.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayytblfi.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfprnqq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hecimdcr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2opigmagv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2leedximy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2plekqaef.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgblqyic.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tubbwthg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlolerfi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2srddmdtt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wejvifor.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdwyacf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2sedsnuwu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxawndr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwutumkn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2idrzmltz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooshzuqt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrxhuxb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xefipulf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbuiaua.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefkaop.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmskmkx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tblkhwvw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdctmple.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2medqexyd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqgiqsk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dotmfulu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwbwtoi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpvklxn.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhzamxv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmgoklb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgjhrir.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrclhwb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmkuimp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ealhszfj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgonwjsf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2smbqacbg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkrljqb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlymzao.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qblkbzav.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbshihug.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxgeztq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzreuwf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjdkgih.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvtvfse.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjussmo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeychmu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjfedcm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmyuxqe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2myxwolck.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsnqfx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwhhdsc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtzdpsm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqupdks.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwvcsv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqepyor.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvxulos.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2brmdakow.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbqzfxt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmadgdpu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uslfxunc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2curigpms.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqlddlo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2llzrvsrf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvlplop.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqkmmsr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktedgzpn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2njyfakrt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyuitmw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqtnyij.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnikiae.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnegzvv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhyylgf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjyantw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmawavd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2efsirjtu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2becydttj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzlixzs.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afynqmwn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpztdhol.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlopxju.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjbryj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbdigq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfoyqlh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndchtztn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xzytvqot.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xftsberb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcualqg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchroook.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoueztu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sanewdke.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2reacxiti.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2himeeqju.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdolyk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdicpsha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkkxgdf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2avsibcft.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2otrvrtan.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2psengpgy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvutujav.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2hewwxhvw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcphypy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzexije.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2roomgiyw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcxsksk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgfhaeo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfphjis.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vewuksot.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2yozmmttl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhvxqod.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcweryu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaggrie.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cstphphx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2noqrhukq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fespglgh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsbrzkm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkuhnyn.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbfiras.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epgbxvzl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iffzqajh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpcgkem.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsvbtca.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgnlvjm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hnshsarv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhxgfkq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqetuyo.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2huwlxnfd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqlotnb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtakmpo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvobsfsg.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fllowjml.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fersuwua.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpqssgs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvknyviw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mllflpve.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvhdbss.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbpyxmp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2orjncwtn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzukcza.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfjyfrp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmaqkqp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfecxcz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnfysaw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shsucmcx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgiqspk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvkqozs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cewpxzis.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqwvfiw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuvksxv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjphvpps.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrbsztm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmdcjuz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjfykqk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoauphd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzqwuak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtntjfkv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgnqwtv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iuybqltz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oedctytt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmleztcm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyffabgd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmugyddn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sethmrqc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujujcsnp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiihiif.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqywnyyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khsghaex.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhzhobt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fondyjhx.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpffifsa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2sioqvwsh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdgezhn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjsjglx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrznywxw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2srwmrxbz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zatktoly.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bjljruxb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjkzdfm.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uircrcuq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvfohcd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxpoqnx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjruxin.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwjvobn.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlipgcas.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyixjyt.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2iypjsxjq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iggqmgcm.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqbqvti.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjliexdp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndchbomi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybjvgxo.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcoqylg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoibrvm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2glttlmuz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyonnds.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbgxrv.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cykjeedv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyoytkh.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnogujj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwabjwfw.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuftgxn.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqazyky.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvmedgf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2piymrljs.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmohjme.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cithqmrs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyuzoic.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlkuda.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcwdbfu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrmnidf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbidser.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2frbdnjos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmihvif.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2psrwxaxy.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xahnzcjh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjhozgk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wujgkzmc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfogotg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lljkbkno.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbapprde.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfnqkd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjiuxmx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vovubtiv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjssihq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2fkretxcz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2owclxike.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcpwwez.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvatmci.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmotdzo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrukoucc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkuaxv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtltocv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuykqzf.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dufeyhqi.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqadlkd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlslbvsj.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhbxrea.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnfnzbq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbrqcbh.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqzpulk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfcqmwl.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpryekp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srexrpld.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdxqgzp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrltbgn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylgrgpe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pimbjboa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqwlcmc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcxwqha.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhdynmt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyxzkwa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gimsopqh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2bguddykk.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsztame.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbyfvqj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzjmbdw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvstqmmr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsltmoq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2rptsovzt.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyctolq.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2aithqoob.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dugtsiia.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqfyqpj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2moblbiuw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvauelnw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pbahqfqj.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgauigh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoqznne.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyjenad.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrrjxyx.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmhnzrb.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrulmyc.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hejuigzg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2slygglqr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxulhzyb.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2agjrymfj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2apputyrx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucajxj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2nancuyfo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlxpojy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeescyq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbtisfi.html


<!-- 参考信息 -->