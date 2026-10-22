代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdxpfdy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywtjkx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yexpkdbq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2weslbsoq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mitpvinv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfpetzj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chxnrdvn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxjkhqy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2meomxuqb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2tukkxmgy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2utambbpc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cgluyyzc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2diskxmni.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzysktd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2daigspfz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgphfndq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvwexic.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtsxozj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mrksmaii.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mekiiwze.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsqjuzs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xghiusqt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsflruu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vuppwnve.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxaxeow.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqekqqba.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkugnxs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcztqdeo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbmkueg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhcgqz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpopzwp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2edukvzfv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wehkybne.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nncepdic.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuirduc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhjbecw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jdodlqty.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcepbjp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsxyleb.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dimdeslj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwemluh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnekujb.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wecjocfb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dddblhqz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epbqyoym.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxybiopk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zroqokwz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrmaiks.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hacqkqwr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2seavelwz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhguxsb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiyssja.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tufuwuth.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdeymle.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2prayvtky.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmpnssn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnwdvfk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlnezyq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtiuzpp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouucbona.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdhhfg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2lllgmktx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zefpisdk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnoylsn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxctcwgd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrltsprr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uerjkafb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmtayyg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2foskpsuh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2apizpubi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2exubscpy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixmxixi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnocswa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2sujgjddv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2btrerxud.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2diiqmxci.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnrmooh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqamfjr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjuxokz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxxsynm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgokrmh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tklvilsb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uublndvg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nydyoqxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvjorld.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbxyoad.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfthomgz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvonaaxi.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbefibc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2galeuocc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiqztdg.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmfuhwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvfryg.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xykbuoqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjkugtl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gyydvxti.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2lesesowy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2muhwyqfz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jedkmhll.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzepzwir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrusggjm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2laihbguv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ifenuilh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fivqyqbn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lulqptcw.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fzobrzia.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fljsdlmz.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2viimvtjx.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcjtrkv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdbawvh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2alvoeiyp.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiymbqh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhkjjf.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjlgavc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzkptdl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkhuhaj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2izxknkrw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqphdqnq.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpikhfz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pylyttim.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2prwciuqo.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwpecbv.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2meufizso.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkaujlw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2gibryxtb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2acxljpav.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpuxsvq.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfswspqq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jddfevlj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2imdkomok.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvrdsoy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zqollhkk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgamdhm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrgsldi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qejoffeo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvlqbmi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwkbtni.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mexskdox.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lityrwcq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhnqbkv.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxaxwco.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgajxti.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cztsefic.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjyukch.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tesavdfw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeyweqj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvmpvah.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2adfnwuzb.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2esteicvt.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2esmfblcf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdtiyzc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uphjqccd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvmgswy.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjnvtlu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2etvbdnlv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zppcgyms.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtzxyb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2baafpmyr.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2thvlrygx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqvfjpw.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwztobev.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrobsgw.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaeifnl.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrkasgc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndubwqma.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dphdsqfv.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnaguxg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlgqvcd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2loukfsvc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyojzgly.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2abzjaogo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufunkxyj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuafxuj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2arxwrjhm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmdjihc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcsdsk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxtiyre.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqzilrs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2bejscoyg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yotflcue.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdptjjvc.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2muldwbrj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2unqlqqih.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2merbnbpv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwxwvxl.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlblvik.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jljkbtvl.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrhzqnw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lckcrcmi.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2paqtczru.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwpbzpr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhelkfk.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jbowegrn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yarnelnf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqpcswi.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcomslk.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfezhiu.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhieuftz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwmmsli.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2iywaacvb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzasmko.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmhkjac.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmwfpzt.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swtyzdua.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqavienh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjyipzh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdsruzu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzdjpxy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yegdczyr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvxwoov.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzliamk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joqopacv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ogghsalu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcirann.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoqwfsp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2punvhxht.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmakumoe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiomewrb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2uynjvxvl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwgmbit.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2knwmewll.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2izgcyrpd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggznnhxl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xobarlay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbzfzjv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qcswyzdc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfkralb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqjnawx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dctkxgdw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2poxvatbd.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qeepesry.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rakxggbi.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzikktj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdqjodw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ragazxem.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbfeads.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lilisnqk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2izenuvax.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycviykll.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2dxesvqbw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvvjcrp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwakrzo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tynvoxbi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptahbkvj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstdkyev.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnnetot.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2giakrfej.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2snjctpnr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iddypodz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2esmndctj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2msohgcpn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkrvumn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qldgbvmp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmmjqla.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyzujmh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwvszsj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2boqdycmf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2amdvuqep.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcvjhhz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpinegmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oikmgpig.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2alghvlyb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wivydzqx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqonqij.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhtvqfv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nizeakzf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vnajhgvy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2rvothokr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2niefpcij.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caxscrxj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zghlbajj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpslvifh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oschydxt.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2efqsxflo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btleldcb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxqezun.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2uohxmfpx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwyrdgk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqjfggz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2svnmmxps.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnimzhl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tkigeaon.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpudfpt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgsgizo.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upoisflf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiltexvo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kncvobgf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dgadiejp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fykzbuvg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2saedbwyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mquscsmq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwcvqmh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehczwtnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emdceexc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrenowa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iltwojjb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uuamzvej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2baqkmxcn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2unariyee.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsqsqxp.html


<!-- 参考信息 -->