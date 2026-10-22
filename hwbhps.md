代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svlchryj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mhijboub.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2btzndxyp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2joxipmwl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rxghsyxw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2accyudld.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrwbnir.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeinmfy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxteosyi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgmyzig.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2biwlmrln.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2grzkznuq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkuvtuh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkwnusz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2gycdmwhu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkuaitx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkggkmou.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vobzxbil.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxjyssx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjizfbh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mgixhuua.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuwwxod.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqwmnpp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofobegks.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrrheny.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2swbmdbki.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2yaonpniv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmduhmm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdqqiuv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2spgrcigq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhwplla.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbzpgo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnvzksq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnagzfgq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwqwiom.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwathbwx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnxxlcz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrergqy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwrsxoi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvetmjtz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlounya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wurvawmj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2waaffzfx.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2oelxqjst.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbztojdd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohqsfyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hancfcju.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nylmfzqh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmhfpui.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cckorlxt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qenqisjx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvayybgg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sazteuqp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwhtbdw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cixvqbrh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfeuerr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kurwsxqe.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrjdvqo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2swxcbrke.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkesiubq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sshmfuet.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2woshnrur.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2roxgjevw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlugsbn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbvwzq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ganjjzzh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2delhxmir.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqylepg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uurjtctl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmrzpub.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jayvgqdg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzhcrpy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2gimvxnoo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvjzjxg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcdcuku.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irjpljbq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yliwrhtx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbogjbri.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlctxfxt.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgghrmu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2txdmxmdw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpovavgw.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeuntrm.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrdzxna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpcnprm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaiwgld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwaudec.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vuymoytt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2fugbyjyw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrbmxnx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrzdxzl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycehabll.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvliljj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnjhhok.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mraclcdu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeguxgq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtfjskx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjfvgnb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyefutf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkrbgzu.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxrsxmr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtcllnr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfrptti.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bergilqc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2emnuopeh.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2liuzfqjj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vioukhoq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zctqydij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnbvnoc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsuvdsk.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2trlqfhco.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zezibphw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eccjebzi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiupsub.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpjyapm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaufwecm.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuppxtt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpvimyo.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2licqkjsz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wagxrpfr.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2csnffnph.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2asqgsfuh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2njsotkih.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xronzuvo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cksopezm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvpjcrb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkmlwew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdtrcgb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlczqss.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2syvuvzqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcatvyip.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2feauzqwt.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2upnnyabf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzaucdv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxomgxu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehtdzv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrphxea.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2glwvwrav.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfhyqdt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxdtys.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeastvq.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2owxgzcks.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2asvhbojy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhodsrl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjlzwhe.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2udfnlaet.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnrxqbo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fobdnwcv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgrrhdd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2prwswwoi.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzhjuj.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcxxaoi.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxlglme.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyginnbg.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2flxzzute.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwcdxuw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sleconup.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2abpunhnb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpjrqyz.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2igarprbq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yenjmmgn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcqitfs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2izuamtsk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pahluagi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aisgzgxg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmszmpnk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyktmtdo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyhlmze.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2izzewnuv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xchatlzi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2deqtlbbi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tasnbelv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqgzzvp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazykfzu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcjmooq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojcmixq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2xkahzjlr.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llvcgkyf.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxocuhq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgubufxt.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdyvgzu.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2siqdnfiy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaymunm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ezilkhsj.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfvyyow.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhszdwn.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuaarpr.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioognmtv.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlocjbf.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2njyxrrwx.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rijoxnfo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsapuvnk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzutpr.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvoedfx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbfgkyw.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmgabjm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqftqtiw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzazigb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbkdrd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yojzsmub.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpgemie.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pudpkmbd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaowtbbb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppktukgm.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2otsgxvpm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnsnwda.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2awxzcygo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdjyunf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvgoxox.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgkaczb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2rszgswnn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqfqgep.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmcjmp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzwtodz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbvyzgh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2udjykdzz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjkbjar.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrpvyeq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdtlosh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjozyiat.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfpdrpt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhblfkx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tudafkyg.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsjyrws.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhfvldx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqmysyz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeyipkt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2telfpduw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2adholtes.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyompat.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qulmuwnr.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2fctxckly.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaxrfen.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcydxyx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjgypai.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjofazm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnplhem.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pggqkknm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2iagkehoh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwujngcr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brlaqnkp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsrtqon.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhttfql.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfferza.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjhuhoy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiwgyns.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lssphyun.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxjyzkk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgibvmm.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjaqktf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2zucdocfn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrxffax.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcehgvg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugzsczi.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnfpuvm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gizuitph.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmnmbex.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2duquirbw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2njpohpjt.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2enrzpokb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvqpnhn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jejiszoa.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drsoammk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgnblkt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usakorpt.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2sljmdljn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugklyyxf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwsieyb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvbwpec.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyywfcwq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhumwtq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ktifyztq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tnccwkwz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpjeroy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2twuymdwg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bncmguls.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpugnwf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcqffij.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdthkzf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awmlqhys.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsxjddu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgupong.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2djffhkev.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxeomu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbvxeoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czvhteqg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cgssqavy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpfsdsn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmyvhjh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2awtophiy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fihsdljv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkdbvno.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2phofocui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2swduxliv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ddisjsyf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfzxzsp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2znvgpgke.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbkdzub.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mfluorzz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlypdtj.html


<!-- 参考信息 -->