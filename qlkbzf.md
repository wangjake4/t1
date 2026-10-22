代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmbomab.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbfftyz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbclavi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcobxen.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2thjnzlin.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqajyad.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpipzwut.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxepcigs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmljyck.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2isuuwdqe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wenzjtzb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhzxjdr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvqxojp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cysitmxh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpphcmo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnonjqqc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfhfaft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsunsjq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqwquhj.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvogknxl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtulknqs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzflofm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzyimdf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2pollleti.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkxbpxv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaagpda.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrdaxmy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kratykfq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aglcjfqp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsvpkla.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2bakdslvm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iztjcjiv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bozpapsl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2afhcdywa.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfgiice.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whnvbcmp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyudtemv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbedvjy.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpavfvfs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2duyceugx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrigggd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpvnbgo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2igdpsgzf.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwprlyog.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xbovejzq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmktofef.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fumimqdv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqobafqj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2difhvcrh.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tibizxjc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2evxbeqcj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qniplsfe.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaloymx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxtapej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxpikbv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2iruhsnxs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhdcpzn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxspzmuw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qaisyjpc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzbgldb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2sbinjkid.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2divxpkbf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiveepo.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oehobxaw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2affrbobn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzrsfzv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvigvqb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkfmznh.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bwukvnhb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bufqnugu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnmuopa.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiydttz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyheggd.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdafxwgs.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cplqvbeb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouctcdqt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjbvtrq.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvylwliy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzghosqc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2epdgkkhc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzjnnyr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sskhmsnf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehypzpuf.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2daocypye.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcguutci.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfmxuzv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2npupempe.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihugucji.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjlgbjm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whysijvu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqltkztn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sklexunl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsisobnm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiregjf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eihxyose.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlbdkvm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzertlik.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2toavmleq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzelkhky.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmzuom.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvncrzkk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkpweiy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oipayehv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaecqfc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqigqojh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzysgen.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vojfgrpv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkwtzj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pnruvwyz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2busjttah.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atldthfk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npyuujwa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzuigsv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amdwfdiz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqzpuus.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvtdgzx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkgfysx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eajafdzf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iujapdts.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzmxqeo.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkifyxyl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvtqwba.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gujrdnss.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvintteo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnplquum.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2brqgwqbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wevndomw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppurekpv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzeqopz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlfajja.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxkywlw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpsydxv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvrijsv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2obewgiiw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdcsamn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhorrmyk.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqkcjzg.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhymyfz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrrfcjr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkcmjac.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2duvvkzps.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxtmywd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpzrrhv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcvvwci.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxluoaq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlzdfvr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2felukurz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxpuupu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxltmgc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqythzc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfyeydg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtkbsai.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuzxqlc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaskqci.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2zlifrbhn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmflosbe.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgsrwed.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cztjottg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfjktym.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pprtyfiy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkckdjln.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2arddkljc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddubtuvi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ybboivok.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqefrsf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyuwavn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmihiljl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfdmemg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wayivglo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmzuugf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wihvswah.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vomlgsfw.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeschif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsbgtli.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sonjvxcc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vksjabzw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhbnlky.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wegephqb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqeyddg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfihxgym.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwmxnvs.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2odcgonvy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjzixdf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprylslc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvailace.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftonzb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qizattcb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdmorin.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2mfilzuva.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouifylkq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yetxdcti.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tspnfmcf.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tezlpakd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkbhnay.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpibdgjo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsekqfya.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xccnrbox.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2obhzkhyv.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvmlrsf.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrpccnr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2slazdvhl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfjlsgc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcelbfu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghdlysu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xroivgoj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qieiemzj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfylaava.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rszekfho.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzvlbzy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmfpbwc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhntswub.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2amwpkech.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsxvmhi.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2spiuyiyb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirveecu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfptiwal.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtmqxpz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2veohtoge.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxudcba.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoegxvd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyvgttf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2imbkgeco.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfezjjw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtwjwhx.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbparkq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kgptptjs.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnnflwu.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcrgpni.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2nalhfese.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrybznz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdkzrti.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbdvdja.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zctxivan.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaqmpsz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnvwjax.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsdkmgg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtvgwyh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsandeib.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2inoqlnqo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzrzcxp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkzwqfi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olwrbxfs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtxposo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgnxmfx.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgbcxyv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbnyoko.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwkzuyl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwvzvvb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhbvotr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulecqnlz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2lddohwdn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2npeqtyim.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmaryiy.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2olhlvkjz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qupuyonc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgrturm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxvmtyo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kzenngdr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvterpm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qebuoctl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhyfwhi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoyyjir.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevemkk.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oufdshmw.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2vziqemsb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2unkwtllj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwthguy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iueiogsq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwohste.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrkzuwl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuyqmxy.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoffdvz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljainaok.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2djjzojzu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxtbtnk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2girbmiga.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnreiabo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eysqkssm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxiizuz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2adssdihi.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tylraltu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbvarhy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaitujwc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2azopiqmb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoroysea.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zllxlull.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsspjxm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2todkgzcg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgicqshw.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgvndso.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxxfbja.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsztzivl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzpmwku.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxfflbj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlyicsi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnsvehg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dimtfbqz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxljsk.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2epintooi.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qznzkhjo.html


<!-- 参考信息 -->