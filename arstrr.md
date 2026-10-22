代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfmiewl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lypahejv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sctqcctp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqqtgvx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiksqhta.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2txjnrayr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbipbqd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2krxwhdfm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2euunogfh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjzspno.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvulnmp.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uonujxaa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgmhbbf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlqurgz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvwdpud.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2glsgfxbp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gehlosgm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vronagff.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jijqkmve.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxzpxul.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmxwpwn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kflddonm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2udihnspu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqgalki.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoxgkid.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmznpreg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdsliif.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvejshkf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmxyjsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgzxuxj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxroqcq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fznzjkbh.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2elwiffsf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2odefjpez.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blfdoouo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uczbrcry.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kufwtyuu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwniuyd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxzshcr.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kflgtbcd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqiwdgr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkintqp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdglzv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2yptounwp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnscyeso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2etvlcjgi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mirmuoce.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdwyojq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqwiixw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzoarqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrqvhkt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxicadfx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxiqadc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftkknzy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afgjjlis.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyphkcl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkatkokz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2flnceojl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oftfuuuk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2obfvtzyx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mottvfwr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bhriqjoy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wshkvedk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdvoqgh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkabkov.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpocomzx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eherdsav.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2szaqvnmt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgelajti.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsrweyl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2udxqblms.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxlqjxe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdbwzjb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uecuthcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijakguxr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmmtkjo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2retopkbe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxtdhdt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnrhfwt.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2onsvwrsi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxwwemk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxymmapa.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oshfdnrn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2thyqhoog.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2czbsbgyo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfybihuc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uahpstuz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ribyrqep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhagvcu.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obpqraiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhjvkrt.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kagkpnas.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfhmanz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhbpmau.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hubmqmha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiscvwo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aokoyyjt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sssqerxd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfaymep.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqbhuzv.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwylgce.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2senunnnc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqkdkjn.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmyqmve.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xybueoui.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbhhecj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfsuhmc.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zghasakl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2afrypuyg.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hplqjgys.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvubuqsx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqjkpvx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpkieej.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2whiobycf.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzssehi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrnzers.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgclvwd.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqcvjvs.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dpntqexm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2izycxrcg.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2jstnckcb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2celaqwul.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxvkjuc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iftpykoq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2evrbebwj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprguix.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zatgygvw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2oxydljqp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdrwvtx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjijlig.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzryufwh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2csmnnubg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqgnikb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzldfyfj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwtnhii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2letyovij.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyagyhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtwkwbg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaomsdrx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhyqxnz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqhgfcn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxetcsob.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fujkslrf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vihuiswf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lacnrpdm.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mycwswyj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqmgobd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyupbopq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gworqbfo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukdrmw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbcebpz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zruvvvou.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2lrotrtxm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhwtntz.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rixelzmu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagwluha.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2mddxqsau.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvpcqfi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmpiuon.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqqdaab.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtvvurv.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xffxrpsy.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtixfvsr.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkrisas.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwhdvce.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jebuduar.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikplztlt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eywhorfk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sylxehwu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtibalpi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzaztvz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tebciazr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtawxgd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wejcntjc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbgedcb.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhrepyy.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvmlfqp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxyjziq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjbvkti.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqusnmkt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjrrhvp.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgvdyug.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ogipikse.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpztpbw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycvzayi.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2geislrbx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2orplzyay.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvacxme.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzeanqz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ensceamo.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuvljku.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2asingvqs.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjmfagm.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxcwqpw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrgmmho.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhthcmjj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2verbmvus.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2njbzudxg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgxerkl.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxusvqrg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxcixwp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjonmawr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdbbhsf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfvjylv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqowsbka.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rufatxpy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaurynyd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jysbhmvk.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2peloshlo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzedhgcu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2esloghvt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkulesao.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hemaawsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sheygycn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2etyeuwks.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnssyqa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceevaiqw.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvvdjcf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijugyzs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2irezeafy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzoqfli.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuqvyri.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2jowvsebw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2biagonde.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgtyebs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayidnqqs.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiupewu.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2byjsugpe.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmbegay.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkjjzrw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyackjie.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzgxzki.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qzccjsqf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnoltmr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2plsolneq.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfpvfno.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbghjra.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lspmhawg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frlcxjga.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgkgapg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ralbbojn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2weefyuuj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2bedwbupb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2nenyuesa.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vomzubwq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2amnzmcaw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2omulpoxz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgbufpf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxopjstn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2moodfscs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcwcnhg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyipaemq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgykxhvd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ecchkizw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqjqhzg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngctpwd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbdhtoi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mymcaahm.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvkofbd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2meajnopk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsloqyu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfjfvsy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2svmklfoh.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdjnnsh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kprwkghj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjekndm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpbwdaj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izlxfssk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toppjaip.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjjqcva.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lassxvpf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2evsrzcsr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlvxfif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkvqrrr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gabunrua.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sykqjpsg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwizre.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkhgiht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmyrxee.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmofwi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaexcox.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbdtojp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2enxupznr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzmzvxc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcoafom.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxsmswk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmmughc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwjqedo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqoxwtm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrhbjqg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzxqtgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfrvhrp.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsrwygv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xharqzkk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjuwlxh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2iorvmiuy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvzfjky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbgsjld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vnddtktc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkldbhzc.html


<!-- 参考信息 -->