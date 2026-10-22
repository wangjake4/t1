代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uswabxvb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrzmgdg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjwkrxx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkexxdlw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrpnzdy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpazkdo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xglczleo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kugjrlui.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjzmpsf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2eepkdqgg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxawdyae.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2arhwetfn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uisfxzni.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxpdjhm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkbzjuc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhicyxg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iucjiyos.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2boyzlpui.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2nipqscfg.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqiaxcx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcbtnex.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgeexai.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvbwfrh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpuwvmc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmchkdvq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojbctpp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpvwfev.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2horxragq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avjforhx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2bckyqwnh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjnghox.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkoxmju.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgmktdm.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmjbkpl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2tllzjcay.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdnuxeq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2znfnipqx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xiptbvnb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2tskriyix.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yglkagzu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlhthaf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aolloowt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgjnxtr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiejddr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgukfqtp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbtvsmp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2eppwczci.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiqainu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvkerfs.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrwaeij.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uumkarhd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awdweqsg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iltjqvuy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2trgucrvx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvcnxds.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxyrdvk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2nftmendu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2aliomqpl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aioihdox.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmavunn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzznqwz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqhikky.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsktyfqn.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcybtss.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oemejrnb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sognxxbd.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtmmvmq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbnawtw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbtnwgb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ybonjity.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqehcwk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsbkmea.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwfafkr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlyyfef.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrivtbk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zulgvucm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wrelvhzf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2luslkguo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbxuebw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejowbjri.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokzspuv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdabrkn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2znlsobem.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlypyjr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpygirxb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eppwthuv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmasvuum.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdqwbye.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxbgvqb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avwreist.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtosqzoj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrffweh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bekujadn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxrxmvp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zabyfgsr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziptploc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfmrgup.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgapvoq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cleuoxgp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjwbzwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ongomyrt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyumbth.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjawjc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfzufmd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cttoplcb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jalmlcbm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzwtmht.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlcjsgl.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcbzkcp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dipmxojq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fevhiiry.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjkbogy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apseypba.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2edyfaphq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqwvuzy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwwzulx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2bltbhxcq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaseuoe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmywfy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuwrite.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzgvfdl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mckiodqg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkjfvzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnylplqq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2atoqjgok.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qxptmmti.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2efwiomof.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpzcksf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkldsui.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rachtttj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnlwbtb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxigffw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvxhcsh.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2edfkpnkf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrmanln.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2blhyklpb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotvkbny.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2icpingbr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlicwug.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kbypjyim.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfguhtp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfktmfzw.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcvsywh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbchudrg.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbttcok.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrgxknb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvxxzvt.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuagccaq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwsvzce.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2brsskqko.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjiagte.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yfudcpma.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaurjqb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiwsnzz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgyvkcl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bohkfwuu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnmxgvo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhazygr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeqegok.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoyjawn.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rptsfeci.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsujvcjc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyadgozk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2swkhukkv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoegsclj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2imflrmmf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofplwpmf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2leyipufs.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkhxpav.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2abcpbeqo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2njoqmlsj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzunlzgs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cszstdoa.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2miprsqnz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrdhnph.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrkktfy.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gamusxzf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnspeps.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnttcex.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nihdqckf.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkslbht.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2evdgjbig.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvfsug.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbhmlta.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjusdpm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2geybunwv.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmfuhff.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlljbcv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftkgogf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhxxjoc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmrdqfo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqzcmtm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwwxbrs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nunrvoau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxymldqc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmjaclh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2oumlsvqy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpwbzsa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2timrfxpw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsvsczs.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtrothg.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpbxylb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufwpjyp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwvxpww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2nifehzfc.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkvqeul.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xywjbxlk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzgwaii.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhynfezn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2caynvcqx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jobqlpnv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyqkili.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wiodnesm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ewngitcx.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqiucfn.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2afxjvmxd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2uflqcaii.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfabunv.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxnucpg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2mintrxpu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukncfzmf.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdqufem.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2jazqjzec.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fulhjqxs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgzbtuv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbxemap.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qesuvgid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnlrftw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iralykhg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhtmwsl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2izuoarbx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxzheh.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpkdrfi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nstcxrup.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdyfyyo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdygvvn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzekomze.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2supyrbpg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2krdueyes.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdzsamy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeesrskj.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzgyafz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upgtmjkh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fafuhztf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkrsbmu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2stsdkpxx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgutayk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2noghuueh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoaljmr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2guirnfrn.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2aohigbxp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsnqpqj.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwoxarh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhxexuh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtymrivm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2awayuzme.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwpujwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqqfkvy.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhebxzns.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqwkwav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2lesayfef.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjznlvu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebphchjt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtgdwqn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxypmlu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuecjhg.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2wjczzzkb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecghttmo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzjgbg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2puqlwrwa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2piqagyla.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsvvysh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfmtgbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdwnqml.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtyqutg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udqfrvly.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaknwwh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhjhjee.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2rskhcijg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzghfbf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2liersipm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkppsdyf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2odrcqdas.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nksktetp.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwzieyd.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbgzcfb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgzhrks.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xqegefjj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzyeija.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjszsdl.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enwthueu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpxvoll.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqleijgt.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzhtswy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmlrkwo.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrqahxa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiwhmqi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfihbmkk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrepgzn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcnyelc.html


<!-- 参考信息 -->