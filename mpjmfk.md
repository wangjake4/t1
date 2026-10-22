代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whadsfqu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlojdbr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sivpunog.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmtgobn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcqgadw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hatxnvsl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuyltkz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqrwxok.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwhocpd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pcywylfk.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2htqhzqxe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2puddydwd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bywxlohw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2haffxdlo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2hnybitld.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nqysehaq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xalwsypj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iehftfms.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsgflru.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrphacai.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsddmsj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahavrawy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2raujznen.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvmplpt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckjind.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ldchkuzx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwqqnrp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwyuxel.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2feffvlyw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2tylacqrl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuuptos.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vugzgjah.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiotvlcq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvadrjcn.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhsgmku.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iodglqwu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgdrtti.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stsjrlkr.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxwvzcq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgjcgfg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2woasptrd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zsceazvd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvekhnlk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2izjztjis.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tptttxvg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdmnxye.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2kubiaosg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2plzynecd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fywxlrsu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtozvoyp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmndszvz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2surqakwy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrcyrzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzubdqp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2emddjrfq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2sbswxpeh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohioytyk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqxipsc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdrxywa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgbxnjo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpghouq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeexdii.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2csapgbmm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kipaaxlh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2afxxcbkn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2huatpckn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2saqserul.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgqruak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2iuduwpof.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjrjits.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifivjecy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhdkrxn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoukkbwt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkybebl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mthzjaih.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smgdvdir.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoxudwr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnuojiz.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbmlfnk.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqvqaql.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcvoolz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gedfrlvy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvvxhro.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevcecgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuunjfk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtldobb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvwftcb.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vayuyxwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvtcxew.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhfniyi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eozyugzc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnjcdgp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wadpyowk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaukvwu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcpxvff.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbfoqtq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eycbydau.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvvljhj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lywljxbf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkfobgk.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdilcfjj.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aidvyreo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2shnvmqou.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtuhvwg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjwugvu.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxnendo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmlwzir.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjupilgl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wynvpcpp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfbudrj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzadwrd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ogydtqxi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpocjud.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2housacdx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2vtigphzz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjqlwgv.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnffgbef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhaugbg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwumskf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkbzcmk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzgqbkt.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2umbvscdx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmovidgz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdqqkam.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2emecgzkp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkdjczt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2efdcwzwf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hubyylmt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkrerck.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jauhblpm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwpexxf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfqjiwj.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtegbgzg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lglekjpf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2liopoens.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lplvystz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxilrwu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kotzopte.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egimmcqu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhihgjc.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpizdans.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjicvlz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmkldoo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljecyknm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgtwwyq.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbibscid.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwrlpou.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdglgzzi.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2oqihfkdn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtynyzfv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrlfnoz.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrboujpn.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpmirjx.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdmpywr.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxalhhy.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitkfwcf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwayjyo.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjjzsja.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgdvekv.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2jruuqiyy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqyhpx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhcxpqd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaqbwbk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfioptg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnegtyra.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovssinmc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yogfkoga.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxrzutm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvjnkne.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dijafqgd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbkhxwr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzhjduc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhiuoys.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2frewhndz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fticktiy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyhrzrs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsehwnd.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ermgjyzg.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpwfnxk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeajxim.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfewiuwc.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsxnqsa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvkclgk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxapiha.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jwguhxog.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnjoccn.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbkpjvr.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtdiiif.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxlrtf.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtcdfea.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvxdqpd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2arsddqdi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbuagaj.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoyjvtv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2avwbjemd.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlfvnoc.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2itmovxtu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycpqcbj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cufburmq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuivqaa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzbwbev.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2blmyuskh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2cquvweks.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xccjogco.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rljtuzwg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2janggesd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2inqmnpde.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkehdzc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphdsfoz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfthwlv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2vamjnhnp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uokciflf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2acndqrzs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2plnorhnx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjcoujd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcfrqqt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcjkycy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvmrsoe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2spqwqrgj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgwxvbx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruofrvqg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlkbihm.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2npmskkdr.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kabuzhvz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2weckzewy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2taeyobow.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpicaqjk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqzgyna.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2juknvgrt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oabjjwrk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjysguj.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmqfkjv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfgzqhd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkseygif.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2denzkclw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmtugqc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpvapmr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yauqztaw.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2sebipjko.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwuptqg.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkrpsmn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtrlpig.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxicimg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdvvzsx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxzrgkp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yapihvpk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcnufpi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvtdspv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdhpccu.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzhjdpf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtkvoaa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2atulvskq.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmujcrt.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdluztk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikshuxbb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdcirtn.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2okuswllf.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfzqzsr.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrtamug.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2anbiaqbg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2cosjddro.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coouurdl.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwzjcf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfujuih.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqfspfn.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2erjcstpr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buoemfty.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgctyak.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qyehvvwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjvhnvl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzmgtfl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gehzrxon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2djrugamf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2fidyphqy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvhgdxq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ghafdtpk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtjazcu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdrgtoo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqpwykj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjbekwk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2arzzmlfg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoetiuf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfiajsq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhkffjv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2isfcgmae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwmoqrh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hivkdzwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfqqddd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ercnhvpv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sagljlhw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mohudbpd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzhswsx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrirbmj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmlulli.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2odarofwk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkygnaa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzvzqen.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2koreoaeu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzlfhgi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeunhan.html


<!-- 参考信息 -->