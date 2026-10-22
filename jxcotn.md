代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbolejqo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dnngbmgk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2owmxzefa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbwbmnw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzejjndf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qofpvdfy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjxyyzm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxietevw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nudzaygm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrrdlim.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2akyggfjf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnlqtfj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlexqgj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2txyxplbb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxfoewv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bijccluk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcxmves.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxgsjtl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmbsato.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zivlwdbj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cizfaylf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2logdkgjd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ercaotpk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnfjuip.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdefbqkn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pokguegp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwpobrc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ninzpilj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwwltli.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfhfgoe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbtrlux.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2agumzxkw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahthixeh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2guxzpuxn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrxmizr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2urlntfox.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hubuhlxp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiiwszv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rncmqmuv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbtpckg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2klabnode.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlqzieh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrhhlar.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntqgdhm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2btetnwda.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oxabbdig.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvwwuki.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuptpfej.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zkayabvs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bflpjxnw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnynainp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvqvzjh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuibhyy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2maquedac.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfemuuag.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lynlqmjk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmpkisg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyvlovx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvphoava.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjwrqex.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcalsjy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vknxsfyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmorrlzb.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkkzynm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zlundvxj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wesohdkd.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqojzaja.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ychxjugl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiylzbkf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxeuhld.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsyxqld.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dswizbrp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrpfqxh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gccjlwgc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhgglov.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqrthzc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2huuesbse.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrkufqu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2salidtnc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwabozkp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpodawx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkutzuz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2itcfzrli.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvelzvju.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2htqvkucx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaetnsic.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvnnlrj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkodbvc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwxhtrz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgociltw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fxakqnhy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykccxkxb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvsurwp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhedjzos.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibufols.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijejeaqf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cddwhtum.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2skaoyujs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvipxqw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wacvmdhs.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmgircl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbdzmlj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpldtsr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmlxndx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydphzmyo.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjybmdt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvdsmxz.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhacyrre.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2worfrsxg.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzdmbwe.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2addlrzgm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyswxyym.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufisfqki.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pqapkhzc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzkmocd.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2acuiwnsz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2udwsyjnh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qckmtmgk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdzxtlo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tieaeeje.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyotswn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztxsxzz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvwpild.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rylnligw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wruigito.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrwiagl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2copagkyb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2txtigepa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkojfuvr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2umewjglv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcssity.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpscirva.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pucuhdmm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2woqkvaca.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjqtzkb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpmaarx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tueguhhi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzfwbsz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzbglnn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nctjukxn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2twhbevuo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rradawjv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unxexhzg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhnjcx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgudskb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoirwnv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nathcnno.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqilcns.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcpnszx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvpdseq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwqceq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvprjpfl.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aioajmmz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqjckuo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfyvvmp.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2riexuaep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uscoerwz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkpxbxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfrxkbf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mecjybth.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2eiicnnua.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmnamxn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjwkbud.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtakuprf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuysppg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2epditzhz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zhilpbnd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2watqpuqn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtfyacv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2biogxuyq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaautpuj.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlouwdxy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mriwzsmn.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfgfzu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gurwinlk.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yncokqdi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfwzgsi.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjewhhs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynybhpze.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vphfwtzj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyujnkmr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2llqcejgv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2veklnfka.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ecavgbgv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2frpnxmtg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpzswyu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzadgcc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjurpvh.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2nciubggq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlflkxoh.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yplbkmua.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gooocmgu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngiclvv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iecfuuzc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhaqnfv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2apsxxkxi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiexprk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2tktmrfgf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2crsitmvt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkegzhjg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfqefam.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjheggkw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfmvxja.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtnfapd.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2avywlnae.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbxiasf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsodsaq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2loghftpz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvxdlcm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbpgdyz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2phiwiryw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjlujwe.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnbeufv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rjupmzij.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ildzdnho.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhecoou.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2darkjjwb.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2htiumugu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxndxo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlsfvuj.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyteszt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyccovno.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2daomfpvr.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2unocutmm.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2iafchoab.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaiopxn.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxvneuc.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfkwkim.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvlydki.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlivopjf.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2akimepyt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hesvxjaz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxymbfx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkhpqcn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2svpnlrmb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrxjlal.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tixmxdcg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmepczob.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2edelgzzv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxswlkg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ponyouvm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxzhtct.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2vawfraul.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2znazxdhi.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoqcubz.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzhsstp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnllgnl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmkudcl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2gmetymbs.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irrxlzno.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcxgsha.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2knexrurf.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2piydosxt.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjygfyqc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bexqtwne.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vsksejog.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hbilwrmw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjpaksr.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzunlqw.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcwjxfp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmlnans.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmctfsrx.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2imnwnrrg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbkmtwo.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwhejgr.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iquyxyna.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2dywihdsu.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgxquqi.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2agtnemfi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphfniwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgptmdq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihnbevx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcczzspk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpqljir.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2fghmjlus.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phroczyq.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bskawcqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmkpadz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wphyglaq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jquehzrf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bphmatwy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvsrpaa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbvzznw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyofosl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbhnwmq.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2rwysjznw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwktcf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrylthh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupgnytm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvkiyxb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2yeidnpcg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qppafhif.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imcxrqof.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdafllvc.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkfywug.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkaryce.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdknrr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzttxwf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjjtdw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqcmrep.html


<!-- 参考信息 -->