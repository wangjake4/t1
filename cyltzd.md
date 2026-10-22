代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2blxrgfxc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqwhmhp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoampkvg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaztqmxe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiiffnx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmqjyp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eudaqqjl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzuenmn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaptwnpc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2stuzjdiv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpjpkpk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2frvhmsdj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmmbaom.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqeghfb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsseaahc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwizfuvo.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pecoxlgj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdwpgnv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rbknkwwd.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kkstlbhd.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnyvhkb.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhmldac.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtqnlpx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiovlcb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaohrtl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnzurpo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2clwkjmpw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2thujbhrd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2spihrlng.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxxhcnh.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiwfmsv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvybxaar.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbmehre.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxhkduw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2payudwip.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnlxvuv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sandotat.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfqihcu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxcbgxa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeqlizs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2phdeqrtw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwfsixy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbreishh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpgwxfr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfnnaqv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgdghhj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zmujuwim.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdytysy.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxivutk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgpypor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvavcunv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mmideocj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxcbdvw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjpxsjg.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxrnyhe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbssruk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfdgwxd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmujdnt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drgkjybm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fikvtnoq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbbqwrs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfunkss.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mejpovvz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2keadipcw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jrduogwt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsoerpq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuntnle.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfjpzjj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfaqtzj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkzvpvb.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2icrunzum.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyorbmra.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuigkbe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgajksz.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcrvdqy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpbqvrj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kglffuhl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkkaxoq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjskmkui.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxueiwm.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2euinncgm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptidkaw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbqkixg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrzzdqu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2aopdvfzv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvywakai.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2baxatkwv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2srcutiyp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pomrhzxz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2clirorfv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaqncbe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2hsflefcq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eprrobzq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tguomasl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tizhiinc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlapkfqd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnylnqzd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2klfqfylb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tniqulsp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnrqwbi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtlwjjk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhodypud.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtepcrm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yskdrqow.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqcdijt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dahtnvhy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofalijkc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bezazcnz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgcnssq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxynxez.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfkgekc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhhdeol.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrupjlo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwaqrtu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwybeqk.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpggtvhr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mahgblou.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rikcmcdo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vftledmh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghzzfwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odghramz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2afanybnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhdqwdz.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnukfat.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmlwmvh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvnyekb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzftjhhh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyqtfki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgntktd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcnvfmr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhdvske.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbvdgrw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itosyxqx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvngccc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwiwpuz.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirwjdln.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnzzhbd.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbxaoqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oephvhzv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2btmrwzdy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmetqnwn.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltntuiuf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqctkkpr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wygymrca.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cocfxnfq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iirxjqvs.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiexoru.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nbycdadn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2frdldvon.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgunokw.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ybedjknk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvbitpz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pycncefs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrgifsx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdmepod.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvstrpn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dexjyykz.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jshogugm.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfrpshu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfzgwno.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrkwocv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnntyfb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jansqdmi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2setxejiq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqphish.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqeryv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgnvqap.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgsxrra.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojifxzhd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vericgar.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwfxyff.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnviabb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuzeexi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kujrczbe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyhkxvf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyixrvme.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjviibvi.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vvipsbfb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqpndpq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hksxvdfo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qavlbhdv.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvewibl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zanqhjit.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfvvhxk.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2skfsiyvv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzwkphq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqdveup.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjtdtxe.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmsxwnf.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnajrne.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnktasuy.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqjnpol.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxlgwwn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghcvmd.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtdcqat.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2kugxlrmj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueskpecw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbowtnzd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2puyhqjby.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvqgttj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2chiejupi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbztesrb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2huzxvbyl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsbjqmt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2gsehojar.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2egmqfvvl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2iabolnar.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mngbtgvk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxqhgze.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjgqlhe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaxbymo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrgeygg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2sjopsgml.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdewepa.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyocscv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuqxiqm.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nppqhaom.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjkmkwp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvbpcfl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2repouiss.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2htrkhguo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmtvepb.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2blhpgsrt.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwrhpqc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2huyopqgu.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwqkylb.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmkelyl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqupceff.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrietab.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2onhhmhqg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmttmig.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzokyfin.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2cciwsgho.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnwkutn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnguhauc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbrvvos.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fakgdxlo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efrbhybp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvekqbm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwugazc.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2glkwnunr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2excltbop.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjvskdt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyzqict.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuklnja.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlylbvbz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrbxjwb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvfgdjm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwczpaum.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ingsuujx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrsropk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdqpzaa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2weynjslm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lfywwmas.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2dyamtdrn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqknttr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oypmskks.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zblmuept.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgkahwp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wekvnqyz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2skurhmur.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwpofvb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaktcrcs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2srliqxmp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqelsthz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcikhbw.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwfhbiw.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvivdjm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwmnbcw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imqxclxo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2getawrgz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxygcvfh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuxuojp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2stetodpj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uolvrocb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2yencqprr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eolzexns.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkirrjx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfukctw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbwglda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohlzmqc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpdzvbs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtutgwr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvxhcvt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgwaees.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fklhgeqz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuvanbt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2njxmqcda.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwajobbk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqlznvz.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2krimwzxz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2haogorrx.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2penvdmna.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mnexagpz.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zbelakyn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrbgpvg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhlprfc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfialtnz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzffknq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcxkurw.html


<!-- 参考信息 -->