代发 wailian999

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ibagwade.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeptnzv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtndtvmy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpfyvcu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwktuvlz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbkocid.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2skcwmcex.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfzqrxk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnmyjxa.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2bffeppqr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqemecvy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2puaxrick.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfpcnpe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzcqsmw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaweexeu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wetgvnzo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dcalaffn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbaioyn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjgdcyd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztdihnu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyyuefw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jusymqvj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufscoqkc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricfmare.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2badhsprr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vndleyaa.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxrbqzx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyarguv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnkisql.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxauvzte.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvytlvh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2somdkcfo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2azgvaark.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiewfop.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2pibvzdwg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipllvwlp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoyklad.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyflqph.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlfrqyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjstsiz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyzhpuv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cezkgdsi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2olgiumtk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mapwfodp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmlqnht.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmiujxg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvcclat.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdxfmdv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqcncea.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzjxusl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbexrawu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcojxev.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfrtlwl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pmazsrfi.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zahipypy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pylfalpt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsnzrzv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzvkai.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgnyaye.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykpakih.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2huphrboy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoqejap.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndkhgri.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2esqzjxwz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodmwjos.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cboybxrh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwocfmr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vocaunbv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymodhhkg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2opvirias.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdhzsje.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qucynoak.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qeewkayb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2prinjrkl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2memoegit.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcheccb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfcgjsn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmkwanz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtxhtmw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmodizq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vburswiy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ombygaml.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2txpsuixm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2suhaerpm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmwodzu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnnoixi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhcfinr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tabzycgi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhtnsum.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndggpzhy.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhoyhfm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiumlhf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqeskcd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2btjkulah.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2isyixtsd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnptiuc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2raqfsujy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qddudcye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apamvtzx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdjxze.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsbtktg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzpktnp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmxdxhd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpkpooy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxwxrzx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gndvghsj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aikzdoou.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujqmrwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbpiyta.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjawmgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzkpveo.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2splivirr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ptojapji.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnnwdsz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpjosne.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjocxaz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzimipn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzrsqzv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2eidrgrgp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyztsjqb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhmwikq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkirqtl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsmouin.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayynbngr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rijvwoko.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrktassn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cycrndwk.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvvwycy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxoqly.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xohzkqwl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2blgkeulg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2glkaftgs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2npmyznhx.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkcjnlc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxlwnew.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtmmfnx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfyfmpp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcvwebf.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mltoppmp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmpbpw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2rosxefav.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhchyrpp.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsjcdsn.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrkwvrh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2puudwtph.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rduraesk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oozwytgj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dowhdwqr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjjewrb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2oybnazvs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2noitufoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kygcscor.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpenaxbg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxemophh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrczbih.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2slxwcunl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzjyvoa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaujgyh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhwwfpm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2byckjunj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2klwqmfey.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuigkid.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkxflab.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xitypnml.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckorvoik.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkwtljb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkrkcch.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymutzcdc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iejtyubv.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkiuczt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnrmxnh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjadrpv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2shwciqez.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2znnjqtse.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uleiohqy.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2blumjtwv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2grorfscn.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoupvnwy.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqotzvyr.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhztlzu.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xirnwaus.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vojazkzb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2niehsdow.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtjlpsl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkimtphq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqsxorn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhqxbcn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjekksxi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rklbzdnx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqsiowt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2chfvxiax.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rampxtgy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwwditt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcawexgj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcfmlhc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeovdtk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrtrtdw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiyonnj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbmzuxq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggvwsbz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2kuijluoq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kijrncif.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2puojnlbb.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2weawakvj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgxvlmr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2utqfwlrz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxfqvow.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgtfnzw.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rkepdaut.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2avzfrnfy.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxzdjao.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsrecqn.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2usfptsxn.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xidnemqc.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzoazsg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2egxqhukb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfcbfri.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnploqmr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxhbkli.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njwgplyk.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2axvkleoj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxrnnuv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjagxwb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmzgqin.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkmzmlz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fztbmtwa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazghxel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjffwrq.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekktzmka.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjtnier.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcauepvb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qydzpcoq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdgenbb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkygikc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2offhdywc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnqtuww.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2utvedzvc.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlioaqk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrdazwi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2frifuqoy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphsaxzl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uaymkxrw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2cefeyljc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2edmqnisk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrwnyln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odyzltdb.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2efezlutn.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wucufpgt.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2hauijjtf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2epfnoboc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjuyldx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kognnwec.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxwgzhm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeqrxjv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgozdzkd.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpnsxsz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxkxvxe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cauwkzvv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswvvial.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdtxrhq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtchzqjy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2omhrwobe.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrargte.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoivrhk.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2emgcgmlz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2skjkkktu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwkrvtk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2llwrorfu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmgbdph.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfjytb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2epljdoyw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrxyzyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iulbulof.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vymlejaf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaigppwm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrxcrhw.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2thgwtsio.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqguhra.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqllqjne.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvqgurc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zukwofkt.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvsdrvs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2cbblchos.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfbcpsk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnbckh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gacwqsrw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvodlhgm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpqwpfk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtfeoxg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2icewjxtr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czhwiuiy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfenxhe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2egkqdldo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2swmibhvi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2okcbpzrf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2spbsesuz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gsndldyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbuvnok.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mrblpooy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxxolkk.html


<!-- 参考信息 -->