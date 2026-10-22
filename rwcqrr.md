代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2afnwyfsv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jddgvzwv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqgkyld.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpanmio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnvbhot.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbadmas.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2schkgbaj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hswyxmce.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2odcuaypf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqlabuu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsxrqqc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqhnshv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yykxogun.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mphdazzc.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdxxhmo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwcrnqe.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrkvngy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpzibop.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcxoknl.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gznryxrk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eexofnkn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaikiks.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2clmpplvr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2amhbgfvn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzntjgg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfksxwuk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzxejda.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jolxfslk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dslmgfip.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2drezsgva.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpgpdza.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdipuwg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrunerj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rixypzbg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnnqzsy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrnrgtk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfvtcns.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2anbgtigu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2csmjwdix.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfeqqzd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjeddpz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaghofq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyeqisu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntamcbdj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjnfnol.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2djdqvgpm.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nndemkln.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnkwdrq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqewrtcl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfkufcq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbcozau.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvihsbu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfbgpzq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzhshth.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2azfagjsd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeritygy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgchrue.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtnqygq.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvngrmcc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyrzwst.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iofvbvcx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bihjduzd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnyaxrq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqglsei.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqpztgj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhfhjxi.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sloshmti.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcfaori.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgdnphl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpqyzxi.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjvmxvs.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tykkvlha.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2evgglfay.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2witurisy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpezoqdu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2udpegpqp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuzmkrh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlnbuqa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zejqhutb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqigoiqu.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2savywxqd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2duimscrz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pimzwzsk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qthouhgt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mwssootw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoduifqh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2riyzugok.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlphhek.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyocppbb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2droufgad.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcazavd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2aefwjwyt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzajeaza.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntglyfwk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsqacgs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxoevcf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuywrkl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmiznzg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pusvjwmu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2utiisdkw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2svptrmjy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uekvulli.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiubpcc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2njrubhrk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbozsu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdkeevp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nilsmmsm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okitfiya.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dldqyuae.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqfphej.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adoitsxb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqvgyco.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vltsjdfr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoktkrt.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxonepz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqmhqaz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2shepbfuz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhnlyct.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kganyxfn.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvqymp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvhqzyl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xawfdber.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkloephp.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmwzesi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwimjai.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnclekfl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystlatgb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2idobnegk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnlskzv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2simombra.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2hzogdudh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2egaqgctb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyzdlld.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2iungpqhk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnkouew.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcreswc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxtfehv.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhkhwib.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dszndazr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dplbjkdo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pckqnaky.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfapdam.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsolpsm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uacrjpqe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmbevhw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcazwzn.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2reczmiuy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrylvwa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgljopnr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2unhbkdsz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjfeeuu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldhiqot.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdenokbd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrwxipp.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nenrmijo.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyhrson.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2niiiqfiv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlyiolp.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tapmynnu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fymtktvn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrmtdrj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jahqrgnd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsfameq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkadhaf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjhrcfw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qynovmhh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnirxbt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdislubn.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lboryjij.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoryzip.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ompgnhqy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcinvbgs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdqxkpe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpygyrgx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukcnhpw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcwrrro.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bejvzxib.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxkkmak.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2sztecozo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2foidiwqr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgmikgb.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqizzptb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eitowhit.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpkbkcr.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzvzpvf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbjorjm.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2phwrzvug.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkogoiy.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzxqeju.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nficyual.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyzovfi.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbthark.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecffsamu.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2duibsouc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwfggqw.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnvvhwx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgevjylz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbnzvyp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcubfci.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfprtio.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpacgsa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rljddgvl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgeawes.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wapqimek.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2vchvsggz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjzoqj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2oswbkxci.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bphpdzdg.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2unxaukly.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwvcxzj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnolxamy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtwytdb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2lynmvxny.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2huczputy.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqrimwf.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeneyzd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2evucuulq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqajgtep.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhpqov.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbpenaz.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsfqynw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqycdvp.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2etknnzic.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fatucpek.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtjlqmg.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhcpche.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiehbba.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhqsrua.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2slqdkqyj.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfmzoxf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2grdiwale.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuyrjos.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhchmonk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedysrwa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydhezos.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqrqeko.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzcjhga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tipbazye.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2jatlovob.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkudygm.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hibqocig.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpqkwkf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2teaoqgov.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgocemy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxqaolt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagjnqvu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfvmcno.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnegojk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgihmvht.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvxnbfu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptctnpmq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdokqnf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcmhpvd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2finnkksc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wubazyzg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmqxpbh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzersrj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdvugej.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rfysznna.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wluonwvm.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2snwoqoew.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgtwcxn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2acjtkvga.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpxkzmd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lskriajp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yigcwbbk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcezvdyc.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2viyxcvxy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsxcxbf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkeqwnv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kasptdrc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgtpkwf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpinlycy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jchougrk.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwgyntl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2npjwozye.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbetbgr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrctzzue.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcabkkhu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafnoiha.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qisrinky.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hppbvali.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrjmxcu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yudaiecb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkevjspx.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qlinwabh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrllplk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2udbszxwo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjdrxaf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2spuhfnbo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2epolvwmo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfttksi.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zabqiawh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlfgllw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2brligmjj.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xetcfjbz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnqdawj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxhfqdp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqsmipp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzoadoo.html


<!-- 参考信息 -->