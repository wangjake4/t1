代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfypwygi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmgejum.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcdytye.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlsimfp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgpxezp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgpjteu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2efamljcg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2iztdikow.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbxtayq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2irphtmcw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2rulwurqx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zubuqqfz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bpunwreo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmirddqg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowifqmx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaoqkia.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakplth.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xfawhscf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvunwmzs.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2egasxevw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpsbmri.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2psuzncgj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2geuughpm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmsiukp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqawnanq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaasnir.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkbvmpe.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwokfbcd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkmphyb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eserpoej.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqklinw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgiselt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwmkxu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2coqqswkx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmsebe.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wypfmzdq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2smzvwjte.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyadjirj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgjrghf.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzhbrcw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqaeaku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yslddgwl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsoeztj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyxgsrz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjelylyx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhsxicu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yaukkljk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmdeulq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwluxbvh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wahkdijc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxjbkhb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kklrtjrb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xswcacbn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pajsennv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2azrzbwhh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvppscb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbnlsxl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruodozyq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvjldcv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2llxkdqky.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmlbxua.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjsmyym.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyxwasw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajglditj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yicgqogl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrcjbbt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfufgck.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrdbvki.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctistpcl.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnaescr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzslezsn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnvsvok.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ardqqohw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jctjzrwb.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmzbfjv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqoaxar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgqhxwv.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxhiwtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iudyoxfy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2giqwqjer.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2yphpyfjy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjpemjw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrsxixv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzcwgbj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkniwfqk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcffptt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2aslabqdt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dungukwt.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmcylga.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2csduusxt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkhjdfm.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmbibmd.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnpdekq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbedkgg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbphjlsm.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzurbjn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyafgnzf.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvkmuhr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hylroscc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaggtvy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfwrylr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbmslnj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlpxygb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpjndil.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ronevhay.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dskuulxj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyxuihd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlrpoti.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xggliiwv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzihcnol.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2efpvnkrg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dueuvaps.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqtodsn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxuqfio.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkclwjpd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuxjnky.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmszxiv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtaxpgz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aazgthpi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2igbykoue.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnrhrca.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2boypqztl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aunsymyz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nduqvsxe.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zphnynga.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjdztyn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtsvgms.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sodwpxcf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2grdyntrg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2htsjvgwa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pctnrixb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhmnewn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhpctaz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mfazyuqi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ivufwrmv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnyuhem.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmknlfkw.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjurisgz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqsjvhi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prpmhblv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvbycjd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2aisybchf.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2arfomcfd.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lofjcaci.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaitkcix.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2szxgrswc.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2muoigptu.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdlcqdi.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtxcpdm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjttuzq.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhysfah.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2jefqwixv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbpjdig.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkaarrs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wttmpzer.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjrlbit.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2awaemzrb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2evummlzo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2caehhzcj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2noygqdju.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpxkwqb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbsznza.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2lruraiql.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexgeer.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfioqvu.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2acmuljnu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksazgfxw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyrijwm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgecltt.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovceveeo.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2foardvlk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2htgmqimc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2axpphnas.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2awcjtgma.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwabazkf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmxrfth.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzgswhw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjlibfi.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkrracg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2coczqypj.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyqlquc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2giwbzqzg.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zkflaykr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2csskgfge.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybthwwjy.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwiohmu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2agiyrdcm.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owclkqfm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmigabs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piaeogfm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2quhbewnd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbnsjpa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbprvyd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uijrpcgl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajcwisy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvncysb.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2csyqxriw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cofwrqsi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdilosw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzunkrhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkskian.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdsjcim.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhvmjcd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2upokasby.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfzjwmg.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2iywctdrj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqnvghd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvpnsgw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwtgwl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfxpffo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfclrsv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lccfidmb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebturktw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2makxkhui.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxthdcl.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvzdkrz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2vztiuuzw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdcrtn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsbsovt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcimwfvf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqmyspj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cangfzpe.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2plyygvhn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2hykwklof.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxfkvkz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2chydumbx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdwdzve.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytgclnv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbygrjz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxfenqj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyozcgz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbbomcs.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuepyzm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdxaqag.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zezfiqun.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pajgjfql.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgdmtms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iywwsjqj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzemsihl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhlkkgt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjzbwjd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoxixom.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcumnndi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlsuzay.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjcceqx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmssilp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkflqxvv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2boinkbku.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2scrjefiw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaclgvs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2alnphlhs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2kiacszlz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2skdkzeoz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoqptnw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emkiraiz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmskoxca.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hacfksbd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2mmejojyz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuwhazl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mmntwlvz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2eseumtqs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbeggoc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfxhgrn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrmlwxn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhixilc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2sehnobey.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgyrrgz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2omihqtle.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2frzauyzr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmddwfd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xratzdji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjwyqbj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aomebpct.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiigqxtj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkgawoe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kianbjhz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrscwma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtmunnc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozglegop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zldjcnwh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbosipz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzngxcp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbzexfr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzblyhp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzilxuf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuulcqn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qsffdatu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkitozdm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqnefzl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ordosrko.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2huxwsepj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrunppvr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxrorf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oviafrle.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmetbuu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrysotj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfufhmho.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bthnmjsn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtgwsec.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuczhcb.html


<!-- 参考信息 -->