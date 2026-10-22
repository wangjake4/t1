代发 wailian999

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvbfdby.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uteesono.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcimxgqr.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxohjqgy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkphlgp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rstkmvbg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpgmgad.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2czhjekdy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwajjgjx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2oicqxknm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfctcfi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrykffu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfngrcf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgiycmb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2eitavdsx.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2injfajtq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtfzkm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2banxiqxp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2txamrjhk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2issnnvpu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjgxpvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrwrnps.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxlmrzc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpyifla.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rootkeks.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbpttks.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcnxnrd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oykhijnt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdrfvdk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2glciklod.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqvcvgn.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqewdawt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbwcoay.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dennpstx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2teromicc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcuouhm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gtphlaek.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iidrlteg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpbzwgt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjstjmn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mojrfmhw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvduslm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwyhimc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mebftenq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnpzvzg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyumqoc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2quacmijr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qroqmexy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lumbglue.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhrreuu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wljszcxh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tavcgins.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jokajvtx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjsfpsn.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvouxnj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwbmhi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwxvdwa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzukugx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxfhuru.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egyyurir.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbwtvpx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyuomdk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyecxpm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2irjeqesz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtdyljh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrdjfta.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpdwmxb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2otrwjdyx.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbomxzxp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcxdctu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqtddeu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqbnlbd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgupzfa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnldrlcg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvgdzy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnewsydh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjhatpv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjmqfgc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtntghx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxxjdun.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbxhfek.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrxmlu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkitslwx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2midugzjr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhwlxxq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoorimy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sibocmgv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlhqftq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxeuchj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2hadfggtl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2refbxccw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2klclnzpn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dqevxnrn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqrtuof.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjiccsg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnatgfux.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2limcyhud.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jupjpurj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2moygpfgx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cueilgtu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2drejaxbh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nboxscfe.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwjobfs.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdxkyjr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kimypczd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2avdymzaj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjrmale.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvekmib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoawcvf.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbyodgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bptxrlae.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gikdlbyo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2eaudxaor.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dztczpic.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfglrzh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2odflkhve.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eodekzyq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bffjskdr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2gyidskow.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxzthbn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crdyfjzk.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmrkaxh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmarlphg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2okzxdyra.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkplwhtm.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aacbnygf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2esqjznqx.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzfuyrh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zobwwavr.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqovzna.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2swstmzhg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvehxqq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxywawlr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eicshepx.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuuoqbb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcjypuv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rilkbfrc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olebskto.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkymdal.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2neygxxcr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnypnxff.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkslpkn.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvfazuh.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tellxfrf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsuiaac.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgfpkgw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmwydgy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qirlajlx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzynqqk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2itoqwqnd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xisgmezq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpwamzs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdpjvff.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpusvhb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyquvfov.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2duoezovc.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhitvxm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbfimbm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjxqxhi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjktvbcn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2umbrhrts.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoenxkme.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphbtlzd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuuhivf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2grfksaxl.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nenstgrn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeqspow.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvnvakw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyqtlcf.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kotkwpxg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcahrzgs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjmrtan.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfuokop.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2smxnvbyv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2blwztsqv.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rziilegs.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvtjei.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfnejtt.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqqvkno.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvuspdw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2acxsrval.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycabxktc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyoxbyw.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2cudpqwme.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaxoqxe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbhjtr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lumtamkf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhutwwz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwfsoqf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nltqyucw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaihytn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nphmrplc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqkrkgy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqbbdhr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpcnbvg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzgvlcb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjqded.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gffyuiwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyygvbut.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2abnctoxj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyffmac.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjutnmfc.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ommqxhpp.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmmxzam.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwpxnos.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqhfkun.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfxvsjr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dqidmckk.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kroufhoz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvbkigf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhafqzu.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrfjpbu.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfrzysk.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2efdbvmub.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2thrbuecu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2uimzzrfb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaghgtr.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ievgwtpn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqnlqdh.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tyomhllh.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbyiyph.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdkecfr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxadzxg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjucntz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbykyru.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlytspui.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gosdlhgb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfzzojm.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2grqukabh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpupupkx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmxvdzh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2efhjwiwl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfjdyqb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgisopnc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpzfolj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjvgpsw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpgjjyi.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2webusqke.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pynpaetp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2earxvxoe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2drtodnst.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2limhrlpn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoqrpic.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdydghww.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tztmotsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2awltlrlq.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2smyghmyq.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceynjzwz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuozpga.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jifwqjpr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqfmuw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxxcxgq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dliwnmzt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uazhetdd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfgeqtv.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2fffvpyfr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqvhmgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxbzgoe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsjdxtn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibmsyvy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpoaqru.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgezkth.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqtlqdy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2eulittuu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvayliqf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcvrels.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2szrcivsd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvdhrmf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eodumpoz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqcrkdh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jroojrod.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhhgzgz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsstpae.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2frcpyplr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2amsdqfyt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsomyfwn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdutbkd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvunpdb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmguzgpf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjwyhuw.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xsduxmte.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xlydwgdq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2abocifkp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpssszq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fofcgqzl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqepfhde.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2desfzcdh.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tboiicqz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxcrrh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2najvxtpt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhemtmtt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rajfiiwy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iyitdihu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeqgxuw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmdpcts.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fakugibj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cmssgzui.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfedwxc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmhjeuy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkyadez.html


<!-- 参考信息 -->