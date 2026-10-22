代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2velfcklq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyyxhcz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaqqoyy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtbnqpm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjbvsjf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzspnkb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmnwxlq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2futbyedn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2urggazuo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvhoqkv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wntfnuah.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lathajvd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2gfugfqvd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcqxvgm.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqalawu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2adsxapjv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhglnehc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjmrvx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmgtxxe.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdigakzg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuszrja.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chsgnjzu.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnloedj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2wajutppb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfkzqqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoayzwk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqliblw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lufeihpc.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nufzjjlf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcltvdns.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkpztgl.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2czccsgbq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rqastdmp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bibgngup.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kufkuuja.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqqxayk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdynicxb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqwrqqn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoaxuaj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nkamhvdy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hetbfmkv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fulwpsml.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgkplbj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixovqqti.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrvijpo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkuilwg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozlbcb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ninqfayn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdezljm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzyaysp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ryemxncr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2deocsqbg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmqjzjr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwmqcsd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cplckibi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imjyezfv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2inhhjnfi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxykaflj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuigfhn.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfvonhg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2brmgekly.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnttndp.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vowdwjrr.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhywcpk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkatelyh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aemrgzvw.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gssktite.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2penrdmny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmniigim.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2azkxohwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itlsedtq.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwruqq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhfbuxh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiamutrg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaysonm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevtrhrz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqvoaw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eriewtqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuoiemc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdfaknp.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhoznpa.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2eejkvehz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2woxiptot.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujvzcgv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqksbjgb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlgqwlw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkxvvba.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiiqtej.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkimfecm.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifthyezi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xiknkeoo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjabeqrn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2urslupoa.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrvszxl.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsskyxbx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tiljtuqd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2envzjaet.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mixgavzj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2pybzupjr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrwokid.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xucqugxz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zreywcpv.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmffubc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2reuuxjtg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkpnfhb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvxndjg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2givpjbjf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgqzrgq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgbauoz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqdssin.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgoufxc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbhmtlw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxasmpb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcydsey.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2psyjxtcy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aatxtgmh.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtipsrw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfagfiix.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqivlwls.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhruknp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcchlifg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjirqkc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cchiusfe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2evzusvlh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zogucnnj.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrknvxq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2mfetllob.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkyzcri.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wymcdrth.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtesekql.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlvnexe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iolslyeu.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qollnwsj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnejruqq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rnipersa.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2therfhbs.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2exigneyo.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyewfooh.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2stxrwuvc.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaquwrc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuahyvhq.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuetyod.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pytrplyx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjutspx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zipciyff.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztisdydd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptwprd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzapuogw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrbtrqe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvapsrql.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwtomkc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzdrfrt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2deaskpkt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyopmwa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2xctllrvh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqozbeky.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwfqzlk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjemvbi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtwehhv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykbeoaj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfbbnuq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrysinm.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2viomcapq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrbpaph.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfyhhwg.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tozyveku.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cabtijhy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcekxdq.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nixaebif.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcxzuin.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2twtmabwb.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2izaqcmrq.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2odjbskbb.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfqadqv.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoxcqfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2jorgrxze.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2glciccxc.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptynmf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeizzyg.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrcwqlr.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbdpdh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtznlls.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klzdpyhk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbittzvj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbklzfs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcltbzv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrnrgsf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxhtylv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhbebrl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vecbbjqb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2moeisbcb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2phutxnic.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbgulin.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbqzksk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvnahpo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxacmgc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2powlctqf.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrrdygy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2syjsyeer.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpujmqol.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcudjrfd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzqjsff.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zypxqsmv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvibwwmr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grweqcuc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxztjgxl.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbwsbqj.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumzplvu.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbjhenh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkymfiv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqaboyi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnunoxp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eglqqyad.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwcwzdq.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mymlsxxq.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwnwtkd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2aytdxgfz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sloiayxm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cflwyfil.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njlhidfl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sazpniwg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyipoggm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2qpysmmnr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwtixzp.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcpvvag.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgkavbd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2owomqyvo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrmtyle.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgrwmnm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cftxmpgv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgosuikd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xydiueki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhsmona.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfxwcmq.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiqksyq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2phstmdkv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziohnhjq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqdqxxl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwyonmz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwibbahj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2miuoiaaw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2yvewiikc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmgqeea.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2uamxfmkn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbzkuxe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyjklpa.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ialeflkd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aetjfehu.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxavmitm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qeplenvo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phblujax.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdovrrh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2scoztimm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuzowpx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyyasbs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtaggnl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfcglvr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkmprwa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kbglxbqf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnenfio.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxcsuyy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oarhjcji.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvqxqtl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqehclqt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jsadgeej.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwjohzt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2eahweyop.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2edelrbjk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkhdzzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfztdgkl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fucavhni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnvpglu.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjofezod.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksguckrs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2reqefzir.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2alewikah.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gntyzqnl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfilcqw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxcpmhe.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2foruxwct.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aovbvzfr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzayrtyj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rclseliq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplqklzg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thclimcn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drhqioku.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfqgavj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxirsgbl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfbhlid.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvvdsal.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdzdvdz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsucoweg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtllbwzt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoleojz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2njhaovma.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxazbsph.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamyqnd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqscwaw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvejxkmg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qobxbmqv.html


<!-- 参考信息 -->