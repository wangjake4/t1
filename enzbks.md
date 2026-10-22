代发 wailian999

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2odaaxojv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2psvpusem.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiplboq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkkkviq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iepbundo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtioufon.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whqlapzk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yusbybnm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vaysrydc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2abpbetvo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yacjzwxv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdxcrew.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyeqznx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyzwlxq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rukpmnuf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhckvno.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkhdkdb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeljcjyc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2poxmsout.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzakxwve.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nejaiwkp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuyvqor.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2siolujoa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2imtchcxt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2oryhuvph.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sueldvyu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2umxtqovi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2udckzlak.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dosqpjee.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiecalrg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvkrzyw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spttcacb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjorbxyy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpwwjww.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rydstggu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyeikxq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wttohcaw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2djrbvnqs.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxhjkcs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zniwpmac.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nucuhvwb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2twlxadqz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2chnrehrz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvdiwfa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqucaqo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpysvusy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhyptmd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chghkugg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwrtern.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2finouqst.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuesyaw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gpicwthi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2spoubqdo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jongabmq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnvjgvo.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwptdasl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eslvnorl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zncjvpua.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfgqsmj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbcwoij.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pplmdger.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbvlsvr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsengeum.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fywbgcar.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rxipoiei.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtokxsv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2keskafyi.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijjwqw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uizuhyht.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aivnwqcs.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eihzmyfm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgfpwlb.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ashnosyr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2joofjsek.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzutugjp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2oklxdhkt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2txqzuidl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgxafsz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrlaeaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridxprsr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2aftwlgmu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2efaatlob.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrhnnqt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxppxaj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtjkfnf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqacgay.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2duectfsv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wafvtnqa.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvizkiq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcgizod.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2soyzfpqc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvumzjm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vydnjkdv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpzrypk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbdjjay.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmgybgz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpdsghe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzkhbur.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njdqclog.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2elttpwxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwlnobp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgiwxiq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sybqgagn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2frwmdajz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhbbael.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zifdvhat.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqqvcar.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnwbyrf.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bskfrndf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2isybzmih.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbesjvfd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaacpmsr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkalmdvt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnhhgmy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evfjvtjr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqikcdv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtbfchi.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqqmdno.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2efgsxghx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2achotkzs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkcyxwe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etopwghf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyrweks.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdjajyb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcvglfd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtakoit.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2eiynouzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vujattlq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjfhvpm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfyupep.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuptvto.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfamyjcz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbqekh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntarnueo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibyiblh.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqanmpky.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2khrehgui.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoaqbca.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjfowuc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaizvit.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwgfqlg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qblwavug.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxyrzuj.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdhnjqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpwlgje.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zsntigvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnixyplr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shgoowea.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmtexqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iswoixng.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2czrmrujl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bypzjezs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcvxosd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljddgegy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jssvcowi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qexxiqfw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkgomsa.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmctctm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqufmlv.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazfawlw.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeeqwxj.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuczsax.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarfrvem.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcfmioh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcbord.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccadsxdz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oaweavvq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwesacd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2urktwjfb.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgxhxfk.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xemfoadi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hytxdpaf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpqyvfo.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeftauz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2frwywwmh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvbbuml.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bobmknhx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdwfupq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfttoiuj.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhvjmmt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzxqgeu.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2notghopy.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2twwzycqv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpeubsc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnjwyab.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwgljxy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gahhjpvj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbpvgjv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhygswy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdtuhui.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwfmrsm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbtmovu.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2obtozlly.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiulyss.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2purbuoud.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2imvbcshs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgssulhp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcnygvg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddphzhma.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltownpui.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkmebjs.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2owadsthn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaphequ.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqgmbiv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jedwtafm.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiytiqaa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bimcjabh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhkcpbv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2yxreiwtu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2hloidpob.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xghyxowa.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2evpzwvgz.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2npbglcvp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqogcwsh.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2afcjhxyu.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hotkifvv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbahkoyb.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyomajmb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2isdtmrmi.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2iffgabkn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdhjfpx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jellyywf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iblpqpvs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndggtsxr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrivczmm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuhujca.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xciromnc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrkymu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2jswrsuyd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxxkenh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyvfhlz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2phddbysr.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzdhxcx.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lalqbwat.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zatebylr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxaepqk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2dmavhcqw.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqifslh.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhsxvmy.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeayfic.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbxatn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2srflpivp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgszihlp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2anzhkuoz.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtdkdrb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ipycdpkt.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgjaspy.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhganxkv.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrprmowk.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeplnfy.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2euinoyma.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwhyxxz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpqhyud.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgtbuas.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2fusujpit.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaxmiut.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2nudnslkg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvedlduv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqjihbr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaihoos.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfbzyxx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuahcav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaarydaz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyglaep.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2btdvvuxc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2czkyfwzl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijygtsuv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwenjel.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dombezfe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2flukzlpf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpojqgap.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsowcul.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfdvszq.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgxobsc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwstdfst.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqdvbjy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwakuovk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcccaas.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgxzxnm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmprnzm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdskzzj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ficsffrv.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxfmzi.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptglzobn.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2waqqldpg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkcpbmx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnirkrv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcgsuyh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gwytuatp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlzhzuh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnqowqc.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmxbohv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2gucsokxz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2foekcqzn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xilkhguw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbkomvn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tknfqvkp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdrgbiz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2drzlqhdo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpypzsw.html


<!-- 参考信息 -->