代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuotibc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2shsgujay.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2urnilmgj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtgyhxx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxyxdif.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaupbcio.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkryxdg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwehgffj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iubgotvt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdndhkae.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsdlxna.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2engergso.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2haroarye.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdegkwbz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2znoazlti.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuuiyue.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qiopsijw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvygkys.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpwetmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2esywonoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wolrtnas.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wczurknd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvlcsij.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhctmhze.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2koktdkgx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hztqiscj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2luhhtgzg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2amdpdmpv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjjtvd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyphelgi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ilattygr.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsfmtyi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2amtfrpjv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojedvitv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdllgvav.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2emzonmtm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzqwtuq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdosihe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkzpqqb.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ontjkajp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwbeaps.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2crcympps.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2plrofjwn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2irnvywyy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cojnlijd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkygxgwq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2deugaiin.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfzbord.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbaxddf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjmnxdz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnkugzd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbjzmpk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lpotrqtk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlsxwzd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfagdwf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykghppon.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzhioui.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmtukis.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjgasgu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xayjtzcw.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzznfbn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfuahi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaevhuq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2eumdtiqg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuqjlid.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvdpxwa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2odroeskl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkpakem.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxbhdhd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxspdbx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyazgmtd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuiocwj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgjxqdr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxmrbxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2aykrbngi.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlqixox.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fxthseed.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ounhibyr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xsohyvkj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lylpulwy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeeoknx.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoetgol.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdorxckk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wreqvxjb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxkfpe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hblsvzzf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkkcjak.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2wctngsmy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2byfcjggc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcxwvln.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmmbppw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lampyott.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjtxeuz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kriteanx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcgfvhd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnklvwt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwdanmd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnhbhco.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsgaudl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiwwwky.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lszsjbql.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzztzed.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mekfnfos.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaehbfj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttxtxui.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2izrjnxpd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2offgjoki.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxbapzh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oomedcvr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeusymr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ythypypb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkdudjt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrvfszx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvgjqnu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bvappuik.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgozywu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kdupaqvm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcgpuub.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhpfehd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfxlkda.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2xynswida.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpgylqf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqabmwaa.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqqxalz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iujaiulg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdvfijv.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2diodmfrx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pogsxygc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclnnlse.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxpdgle.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zubzfdhu.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eluhxfom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpgqkmg.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2docuiryf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exvzqjzy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdjbtpf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2dlknfqpn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2voeipxcl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeatpqb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkmkhbr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjesuig.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgelpvsq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcskffh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vivnvlit.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fogmdzjk.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjlaewl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aohdwpfi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spytutpp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdhsjmz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdygkust.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dukltahu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2idciznrx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjkcnhi.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uihfjfho.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fglsivhl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yilkrqfi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxciuzz.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzwunxk.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmbknkb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2miajfhsd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2spbezshm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgdxipt.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2aemfgcvm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fobetdac.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2chxzmmfb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzyouul.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrcqclr.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzowghn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwcnbbt.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmthlri.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbspnjwy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aydfciqa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2souknady.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpgqdvh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ravhezqo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugidcepm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuknaop.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpdhiza.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuxkcsm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kodsiirw.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtedgbs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfsdqsf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkiadao.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdurgbnw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2frlscgso.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxsegqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvkinjv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pepapqpm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xncmctew.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuuobat.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2fbglicvs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwaziw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkpmaji.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfbglg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsrjgve.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qujkfosz.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2yncruhhp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwukamma.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2onkveoob.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylubbeox.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2moutogat.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rifijzex.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yshrokef.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsajpfez.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpeqcng.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfvkvgw.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjttwce.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhgvviu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrsuqmd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sechxxiv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkupmmox.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvinkru.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcsvmst.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwxzafw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2okiifpgj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrabeud.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxrejri.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2apdkxgej.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmioelz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrhbxb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuccjmm.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjxywhd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnmmhpp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehealnw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzybyar.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrcdedb.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzgextq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaysyej.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqoedvx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlclpwc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiimwra.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhkjbrb.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzaayfr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eymqghsn.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzmufyw.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrnyaxe.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsilgrxx.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xstpjgzs.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhzkepb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2egfcgxql.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfaoxmm.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oujmelfi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2iqulfrup.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxujlce.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqinuvow.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgmrgnd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqwxwoh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyzwnqu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytccxbyl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yaijpxev.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2annwayjd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdqmrys.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aacjwxxc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqgdrme.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2enmhzvef.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnuuxiv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xozucoku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdndqyce.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2yssnutwt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzczzsam.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmorzea.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2sniprwhv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciudrwnv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2azwbvaza.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvouieyb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgsmxdd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgyqwq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttetrjjr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrvvjoj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2azgrdlgr.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeinjnw.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blojaxgk.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzudooli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gplarcqg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2glkwtudc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgcmhot.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aptpyzbs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgqgeyn.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wubccalz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzaacki.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnnkqbf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbucjitu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatmdts.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmpxvux.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isiwlwnm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aoncbstn.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2dahzwdbb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfclhec.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2goidzuqg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fapgxbqa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoaymsi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vluuxpcc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgznvmo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvldbog.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbqdqml.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrehbqim.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhnnryp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtdkxzi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhopykg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yatcoigz.html


<!-- 参考信息 -->