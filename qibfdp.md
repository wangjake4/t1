代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsvfliu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvdeojq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlurgam.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2juvwkkck.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhjrliw.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfivrgd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhmuyzh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfwspkv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2plfygkxd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhbplcz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjudrbpk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdncizw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ondxxifg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jojqryao.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeilqre.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wivosutz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaxumil.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoyapab.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhrdebt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbomhqvs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yfurwpzh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2trtxqeur.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rztmlahm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfuixxr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2rptwvojg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpzbqbj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqcqbjr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2omdcpypk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyfqhsi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2irjelfwf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzymsby.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2udqbwmab.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnksqzu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfkomjz.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsoayne.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2criiqloq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrwrvcs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cnslgazn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upmsbxxt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tytonjka.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdurlmq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqwojty.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2inikwbif.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzpnlwp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lzivgogk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzlebzp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2enedocjn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjsegjx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepimpcg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjwemqa.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2laiyqwyz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2etyhyvzw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcszpymg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2liumglim.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2snvdqyzl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yboocjeg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eczywtcx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlzymzc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeuyxse.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsvpdqz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2czbovadu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvxtqaz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ixztunzr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhldwyco.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzxldde.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emuefxar.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfkpcbz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqpvlaq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvbofgf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsqdtnx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwukkii.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxarqzyo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwpieoj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpgqtco.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgmxwjy.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tughmtkw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyhfaxq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfquxkjj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tudockbb.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2agslkpid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuhbypi.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbzpeix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaynvza.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhiaico.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoewtaz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2itjabvbj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpakuqq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpnzmg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tupqsdyr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfngbyt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdzzmyk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zibtviji.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpzyghq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ksddmwzv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfbdcho.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzflqmnf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2islfhtap.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxymdfm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnwnhmo.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbbyjff.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jiildjus.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebonqktr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbushlh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wapdhwgr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tobzotou.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvietdgs.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfmbxre.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2etmefxhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2afsegwyl.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbzvxq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuhobpv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmresca.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2buxzbssl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdhgbvf.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmbedmv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oykzflft.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvrakvv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngffszfw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2obdqmkaa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwguwbc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvvzwpe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2aravndvu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvazcog.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtcfhif.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcdkwqa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvbkrmq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvyryxo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wweyqncp.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuttayb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2twtvqgnn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuabvomh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvdlqiv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbouplqd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmheirhb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqcrmkm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsreeyj.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcvozui.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dpezszmt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrlewcb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzykqtn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bazxdvzd.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcejlcny.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaugrrs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzdwwta.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qzopxexd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2weacsqyt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mipndkdq.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfvscwt.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuvgngu.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2akqebnvb.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgnktji.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2upsdvqdn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyujncy.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjdujgb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2iunnfywa.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2mundlodh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwtarcx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtphjavr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2noskehra.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyupqyj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxxreqy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2liwwozuw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaivfkc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmqydeo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2egatwrjk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpdeqwz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwqwvua.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbbkqrb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeaduhe.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzimxck.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfontcro.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsmkmyr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdjovtg.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzniagzn.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dszfppfd.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqggdtys.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgndgsmy.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgygsjv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlanxqb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nqihvdlf.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjwhnqs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohdglj.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jntbwhcq.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvunhenn.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2fugghqmo.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdwxwjx.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmufyqf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhvuprs.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykirgomo.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbsvixh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwowrfi.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nahmjjeo.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2htoerpqz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pomqpozr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eousffus.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgefdgko.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bawxgkmz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jutqrsfm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2pketnaeu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqohtdw.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnlykrc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqoferf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmntcvjs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsznphot.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgnylwr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfpmlrz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfobtld.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdvvqsj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfclwyrz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzfqlvy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoqqguk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2baityfwt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzhnmdw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzvnvxf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfyksme.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqrwaqo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiymaavx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lponwugk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwvlugc.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpkjxof.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfedleyj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrkstpz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxcsfoz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkgkljg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgknbol.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrjdakk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2exlimsoy.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ydayikep.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qixfeutv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2griadiso.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fadjqcai.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zglsuszf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bykrfemf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpdeksc.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2afilsxpv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwyqzpl.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jczrsvaz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxizotc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2upynuxcp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvokctw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyhedld.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqltnbj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtvfyog.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wawumujo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbnvczx.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgkkgeo.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqmnmqn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzombfc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wviffnjk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqdbawh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylugxyfm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhqyywa.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vokieppv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2earatkdb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2czwwrelr.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2inyhbpkk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzzwcwo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlunrzgj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imycjycm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjpebmh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jahdtwic.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2npppskkz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcpmxij.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjehhc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvwwdln.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2clwesmww.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrqombp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qjggpbcc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2spgdyjeq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2buikgbqh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yliqpxwu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcbppxc.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxltlnmb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2excutwih.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbazgjnm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yowimwzj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxnaui.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fphchand.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhdwfkz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2turtzngl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwgbdtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgigaefj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qsedqwkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cctppndb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtpgcys.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbgqzts.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfvwqzp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfwnqtl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rejzslqv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2badyyxgx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvirrf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjzmmju.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkqyikc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btcimhmh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2grpexity.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzpywhp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btcfbxav.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwfjvby.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tubrkzij.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2opuuqfft.html


<!-- 参考信息 -->