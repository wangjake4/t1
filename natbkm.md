代发 wailian999

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyzswmc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhsnitk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2euxoqapv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcymsdwp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2meujwmmc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtarfqdb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyiigxe.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbrcfja.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtsibhq.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vclylgqi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhbypna.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgvhoho.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrbzujs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2voriddhj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2taelrijf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrzmfdf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cktfoajw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2imfkjhff.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcazquy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2delsvmeh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbasvag.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2klawaefg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jekbdufq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzfozgt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbvqeei.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vsznpxxw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2cajjjnas.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2swodvtov.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxlojid.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjqfluz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcywpisv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgjrvue.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckbwes.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkntnxx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2sazjjphl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzoscrt.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2axrpqlnq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2byrwgpzg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxqokcj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqhhwfw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisumjza.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvwwqdj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mcugdjnz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbaptuf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnhtuou.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwywuwza.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdqqsqz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dozhetkw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2chrigyhb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgvltyt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vumlnakb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rqitwkvj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fokpzvrd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2imbpxynj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rplsrxwq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2keossnic.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xicoiaen.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfhqinh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvgywkv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzvplwc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnpqwcj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqhbwnh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlewdqb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqkfgjm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhngjxp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zsppqzbb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksjfgzn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwakjhhd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2txtucnsu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqnbmhb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlekyt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdbfrop.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcykdsp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnkzssj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2izakqchh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2laawucaj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqtdadn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrollxt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eisgnmji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdbokga.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvqmvmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hduvdivd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2scehvktw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2livsartg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kluycfej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrcxgsj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpwszn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrssengu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhltskqy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2azlqjxvn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhecbji.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mflwlxpv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2olrzftfa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evyablky.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2snnqkyao.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnsbnrz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcgeewd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzmoqs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2labalket.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vhboxgox.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2awvcgkgb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnchhya.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzpfcbc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcxukij.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvfsaa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxillhrv.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsnkdpv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvbjwnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2affeuddn.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoogtlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnqwdsn.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvrumoe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2iipugpaf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjitmvq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbwyjxe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvhvks.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnaoyjg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2huiwsyde.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyuakzd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcrztco.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmfkrvk.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2keudohls.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpdmzcx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwrnhlc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2musqwelx.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuykhroz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2atfwxxzd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhrcohi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpljurr.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpurlvq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lusiezaf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnonwql.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyxcevg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhaudph.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awzvtmvd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfominl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zarsolhc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2paficncn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2qflnpqln.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrlnsay.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrhujfm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsppvqbc.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjrhfhs.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnwebvb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgtxvxl.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mprrdpyy.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaijfah.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bodidbpi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2slwznimc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2opsdjlie.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2novngqai.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vizufkaf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dattpzho.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mueeeszc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkwoijt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikionebs.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kobndlct.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdzfhow.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzixkzt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2agbaszwi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2isplvquz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhltlllc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmrquyf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbddbbkh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyecspc.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2drpozlga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2kduzinzm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtydbcls.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkywoed.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrqqmkd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otjiflla.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxbwstk.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2cwozzciz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcbtpes.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2adxjcdtz.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeefbly.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmmckdg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2moklnuup.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2htahgvek.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjsriix.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ownojkmd.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifildsmu.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2agsfbezc.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2huodmoks.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqddvgk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahtzfue.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuujpkmi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtlbubh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fydxuozk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uffnkhil.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbscofzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhrzmxy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2agyizsnm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvxqpsa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzpkfjf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yobnwzmi.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uymkfnmj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dploacqj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fieulghv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2alhlwzpd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2xoweekuw.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2povpflff.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2muyvjufj.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2teexaqmf.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlqpywk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxtexkw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whobgxny.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rquxixzd.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2olexwrbl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxckxla.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdtgavw.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwznpnf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfhgltw.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmxavet.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmoeqcn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2dknndtfc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2axpajrjg.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzkrryy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbupznf.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2laoxarow.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxljvsa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zooljnmp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhhthzy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgkbzw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byxkmsmq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nbelkwrl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqelgvv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtplkzyc.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2drvdinru.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wekihywu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhijnhak.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ienkplhd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhefdvk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtihjywi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2lynxpfxn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wggegywf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zctxshwl.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2swrwsgkr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uquamsgg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2htnqiwaw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yybitqtg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnmcbqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgqgkiz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawzaqvp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbihtdvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhtpgoa.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2paxcutyd.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yefqzhdu.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2haxkgkef.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gedomnfd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxbbqmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjyrngk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmikamw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmqczsc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgaiswo.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2twjihelk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2csycotmb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaxhnqo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qucjcrmc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsmnfwa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcldbzt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpwngfc.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiziabw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsovnkd.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiphqbv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaydahyo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsburrky.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2byoknnkr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmiqioi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiamnjn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eingluoq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvmiyyb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owfbnlpi.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hshbflxz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2djlfwmac.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckckyvoh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxntjnva.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqoodqq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nixkusfm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2msovyfls.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fmesnyua.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2hklepswi.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pmarhmwv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2bonbxput.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcgelqn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euiaknim.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otqgmhco.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfapccvq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oainvnag.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2lgskweoz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poqxgjwv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nglztvhw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iensiicu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyozygjo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtutvfw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxfxmz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjwhgar.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcusqsq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsckpqh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2khgbnecl.html


<!-- 参考信息 -->