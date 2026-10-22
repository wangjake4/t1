代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzbtvql.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tszgzqew.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2govrjhpb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxikigoo.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gyenfpwz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoswoci.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2gktjjfaf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2htlxaayl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzwpckv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwdmkuu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2otvtrwaq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzlwfne.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzbrbmd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbephola.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aefggvln.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcdpegp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfvjzya.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jskeejzy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkcjeux.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxvinvm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfrqtbz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxfgzg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjeqjqy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wptltmfj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oobrnplc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbmtcrf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfaasnz.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbymgmmj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djrnyxtc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxoqygr.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaqrhxq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrmdnip.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkysqfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbnsfio.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iprdzxlx.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqsanhh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvrqxxe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoobfyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnfpfye.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2icgwcwal.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ojipddic.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuusgnia.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lumaybyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffozziuq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaucitj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjwtnrn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fleeryiq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsnojkn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbabksci.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ifddipcx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeebgnt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaodfgmo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmiaahk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2leswmttx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdomkjt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rswfltyt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvesmprt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkrifzh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2idvlgbgv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2hilglvia.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2eujfabya.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjedetz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwcpmul.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoudwpx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2iytdmqiq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeulfye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auphpffa.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzhcamk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhwguwq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uijfdzsc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2efrqodjg.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgzaums.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkyasga.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qksgoafs.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyndahc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfcnwra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kclsnuod.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwtajdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlrradx.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2znckbkyk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2azpkadpc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaieyll.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thrdosph.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkmfcge.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulblknmu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiabryse.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgcnvxn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfzfgzv.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkamhioy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkrleoe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bneriirl.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdygamf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrueetb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewxcuxh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhjubtg.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmrhjlz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeaodzj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzciswc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxipxasr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfprsqpu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngshovcl.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2croycjbn.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcxfxel.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnhxvcv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2aupkvrtl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2earxjjhy.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhzhjzo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dambvxpc.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzxovxf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oduryjko.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfqqaoy.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxwpwn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlinvpw.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bicfzvwv.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxowcbnv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2psjbmakt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmprvdy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhocajc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2seytqhxl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmpgixw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiedluj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxtcjf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiflylqw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2firlyrae.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ksekaqoj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhnsmjo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxyixqn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2njvuflor.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozunvgbh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2urixugjn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfegtavm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhexxoa.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jufycnnz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrrzpyl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsbcqjv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxmbyiw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbpbzzx.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2musspfuy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuelkhuh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtsceb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaspibn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhelqeb.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzpivre.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hslpdyhl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbzfoxd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlltvcjz.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuydgkps.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ympzkfox.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjnpxzw.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoyvuyh.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2csutcjha.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rujhdgzj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gczvrqdi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2voqkaelv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuhgsvx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2muqlsccb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhnxgku.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fihzbjvn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qststtki.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uooynxbn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2vidfcapc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbqsoop.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqnesyi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xutnylqg.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2diigibuk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoklpymj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxulwow.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xebrdhey.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaqrtwd.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhchadp.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2curthmtg.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmwiqzq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rynvrgbn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aykwrqwf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pklboeiw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcauqbh.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pumpxbif.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kktywwhc.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaizilo.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeekhhk.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzzdyis.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jswuwgkb.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wbamddzx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgomzbj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2heboipny.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzquytc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfktceb.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwvapbr.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyjvmlr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlzskxq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnvfzlz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkugzgu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aevtgikq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmcxtpo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuhawww.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noimqepy.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdzkhwa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxgixgt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2blgtmdai.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnasfzu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgerweu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2trxnussa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbrierg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2chnqtmpk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdcbesh.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrjdjcx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqtvlct.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2todmosxz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkxjlxo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vodfdmng.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zpksbkdq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhuaaag.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2taeepcrf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbbupno.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fblimfot.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwmkznp.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpjatlw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2evlhoajx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdwoefu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahgmlop.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuohnyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tducrsed.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnzevmm.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuiqqar.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2eausrqim.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjzthjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lquorval.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjkuzlx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyyggnp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2joixvesf.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zraerzjn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnsaiqb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xreuwdrk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2blqzkjiz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2keuxffsk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2idlsreul.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmnndcm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkvvhck.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cecrgqrx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlskxpjp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cimhqlmu.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2iieytnag.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2panlhfbb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbakpxbb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2claieacs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrrjjja.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpomvre.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2igrhnknt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpxailw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhorfyd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2txcrwclp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2thoalgfs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnvmrhv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roxofpbt.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyyzfuk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byjzefhb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqpnkpq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhfihsn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhxmctb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsygkyq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2olnfvauw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtvbnjl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2njbejcyk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwsinub.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2orzgalzl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lignsirw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lboramyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qifvknzd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2evwudcko.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpckojf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hltlkfyc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtcweck.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iclyhebw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2plaxpofd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnswwbl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2plzwdncl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdypuife.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xncehbps.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvfcnyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leoybxcj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzffckr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2irfoqmrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2htbvvodg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfpgxel.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcfvjjc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwnvvls.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyytypq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjonmnc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvdscnl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmszmzqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2loxwjsqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epzuoqys.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxdksru.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqnvduj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwqkcub.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2offfbpkc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlumuin.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrvqsxd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rijxpayi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhumkde.html


<!-- 参考信息 -->