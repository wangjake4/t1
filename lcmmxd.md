代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aekckpwx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdkmsjx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bplxfrch.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rykwlhxb.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbeepnn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2itbggvhj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkbbucl.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjesvld.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjydfjh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tijacynj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjespm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvkivhc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nckjmlts.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhkviag.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fslxcsmp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2raepmsec.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zckgtofp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvoehfs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpnrvrq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnkieim.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cknvmftq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2efisjplb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wyibybge.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnzpnsk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgdsaml.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyfgpji.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nombxntd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2proupmcr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axewwxzb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbdxyuw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2eobygrkg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2usdevapl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmezqga.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2skqtxmhp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgbsjye.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzrfecm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fioiyhls.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rimdcynx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bldsczlm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sayqleeg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2myzhmgzo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivdelht.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqfkvt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqbzuvw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaeipqj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnbilms.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoxpgka.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrarzei.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rftkrwxk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxilxjl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbsdspq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2irbftexq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeosjrx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpgepwm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyccoxaq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvnpmsr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsdildz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2askdswof.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fjemsqgj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hakpfprh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbaycxb.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbuudtg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyfevjg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2izzdypng.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clacthcd.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epkcmghx.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkvvruy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2crlgmufe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisxmwbt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjdrrdd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlejnypg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bruailgv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzjdndb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoqbgwf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkrqjpu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wycqckzk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpwbnix.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnzwago.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxmmexf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdsvwgf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2urquvceg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmsgikd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgnshwg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2quixpcya.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wogrdibx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qazmnlck.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkvralc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yczaymto.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcztyuor.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tthnwpvc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvcnpnx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmiiiix.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmsyctx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2upeetlzi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2tcopxeqr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ermauscc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2islaruzg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzvbtdv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjfwdz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjftnhxu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jivfojxn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhxujnb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inzvscon.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phillkfg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxfedic.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxroxoso.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2trderath.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyrqsdv.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2emgpmizk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqpoggg.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hynbwthe.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmsmpxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzintyk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxknxyzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxfyhgl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2duwbvhrd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbvpfzn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrowalu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuklhqbf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2asfvywux.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzipqgq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyexhzb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxslud.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvhfjgs.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2isulnycv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqsvat.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgsdykf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2encihalc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqmdflc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkxlkxv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpezlmr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqmgpwm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzfhdth.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkyhrgd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuxujrf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxlivfj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fesmybnp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2whyfggny.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gieyhqjc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrwuihe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2axqssqlt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkbztkf.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2yiragqpa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdnmfay.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkohxnjz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmsobfr.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhcocos.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdurxlui.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dizmiuby.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlyffpl.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdouaks.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wrojhkka.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyofemm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mebbjwwm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkpjjta.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpztiu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmianbxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zceevthh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbckion.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvysegj.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsflrza.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjoqqmw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewofacyi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsvykse.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2beyodjru.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhqjimr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yidgbjhw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaftyspc.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xogcutvx.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fricbjla.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdgokaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxwfgqw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qclepeej.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxiezrc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkunrwtx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcvfxrs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xtexymjm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2onizwndi.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kytznknm.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2futdfwya.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdmhcrv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yldurcay.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwxrbre.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2scyiibkt.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kureekve.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2epwendfe.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuleieqp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2drlypiac.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbdfkax.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2maynfrdg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrxgtpa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlunrnnk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2piijnqyb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzobeqs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtehpyam.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjesfzox.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtzvlmo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsuwtnz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2apjomzdj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2npyfdxez.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfokrcf.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwkggfn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmobwinn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uduyrdrq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2vbitystl.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdklxchx.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvmmmwq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixelowc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujggruns.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylonxpgq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfwvych.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzgrpnm.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fflcgepq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wbazpixm.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2suwwlyvp.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkvgzfw.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2yizjsjio.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vlatosdn.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmernncj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvghsob.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsokkum.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hykkuyic.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2xchnthlt.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxiuhfu.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzvccuc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvjwdqr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccozmqkk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekigaquk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wurkdykf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsxakpp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmbkuvx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usfapipn.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmxtzke.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2swmgqqaf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbsllrx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2udrboxyx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdgotqu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrquzav.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2goxsrqvl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2whccofvd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyclhcr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyagdtz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnsbolu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoyphfo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhpyoll.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpvbbzc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2pntajleo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbyhwac.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbbvqvw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyudwhi.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jodxnocx.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alyaoejw.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwilgsq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaboyee.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbgpzkg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqglpvmq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbumzld.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxpkibw.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzemvkai.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpfkmlr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaniugm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsoaxsx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogioqrat.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nttekjkq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcekjas.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cowbaxqb.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjubryf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqwlqdc.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dijcccdr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2clbodahh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2idpfdfyo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqndjguh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzehwbji.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwdisdd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexfentn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phhijnmu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsqjavn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvdgnuz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyflywt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wudfnqac.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhscikca.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbbpsxm.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hooaictt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cacbjduk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnvmstg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2vscnhasb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2shxiwkcc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dvowhrlt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtklgbd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gobmnvpx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecblampk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxswjcoo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2petjtpvg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzsylqz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrtddoz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzswecr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmngpgx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2joupjcbw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nyglahue.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fzogqvrq.html


<!-- 参考信息 -->