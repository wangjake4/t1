代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2myamerex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtqswda.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwknpjhi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyqajzn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hafxuarx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpsgjbg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxixwrl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjzzrik.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dzegogtu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qifgpehn.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsxuqnl.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2spnsojmj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2glasdpad.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcrkxze.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2jzitphyk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2oavxohbz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uouhkfzx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkuoggb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqyibsx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlkobmz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qetwvcvr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpyzriv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfostrk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dozqvqhn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrovxhv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvhqem.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oteuobge.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvidolti.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyefzxp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmjipti.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtmdssl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxolqhzx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxldbadv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ubesingz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2phfoicks.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbrvtmf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xeffmyud.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhykktdz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2udzplspp.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdncbuny.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqvlagu.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjsiuhl.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrlwgnc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzkuqlz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2stzmmetk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tavlkyuc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2axukhbpz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2pueuxcmt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjakwnyl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuzbrom.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2khnqzlqh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuspqjm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2edyhlaoq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaowfnci.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxaesli.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpiatsx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnnwztr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sanfvxxi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkfdpfs.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jwljsasc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkuxdah.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrbzvpb.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojolvamj.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2orpepxwz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhlrwsf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcjftwg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yucaleji.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mswellzz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfpqaio.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvotybug.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qalijkkh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkzllli.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdzryfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uddmhbok.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpjlvos.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmnjcic.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2irmuzthh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2muqelcfc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2emihuvws.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmbfhif.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qepfoqba.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvmwmig.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmirjdpb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgsjmqo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgsgfcd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphvzjfy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpryjon.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoarlyz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmwtsil.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hduzpqhf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hajbsmfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjgswae.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaayzfh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2facglqdm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jygnmnjb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzhyxxt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbupqeg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlphphq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2suswynye.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtdedpd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jkimxdoe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2roongstd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rngptjxl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcaztky.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jftovlew.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqpdlnm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxirnme.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcfcdhe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2josxiyoz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bopmufcc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaqqyux.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgrndbw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2elfijvnl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpcrycc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuabyqys.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcesxup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsxqvjm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xssugfbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnebgfb.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqzzsha.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoleqhv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvsokxf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mumvlfcb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oggikojz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjprpd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngiegoo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vckssejh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiugmzvt.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glitbcrr.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uadfvvvq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjsgeh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyexqje.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmoqrlr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbeiotg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfpzvva.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjpclvr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgxlvjt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxitdvy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kygzhnir.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2edyviyew.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuufljah.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglidmev.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvryojw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2onyxlfcs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrycyqcq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2emgjvdnt.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2arwcynnt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqydnnu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxqgijo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmendrz.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhozuur.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpzdbzn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyrgxzi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnegxnd.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eboqgddp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yhksrlwz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxjasnl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjhjavz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfgysap.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2srlxhacc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2erecofea.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2swwfhcyw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoutvar.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbactkz.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqatwgdf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqqpfnr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cagyirpf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2asdfjyrd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2awrclmlb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcomdlu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwbqocg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2naaorubh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfevuni.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tlztqusd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqdbhfh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnbaioj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2adsbebal.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2izovalvu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lprghqaj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlczixpy.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2sznfkwnu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tekvdefh.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrjpxkm.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvalxhh.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2crlfgkkg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxonyusi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcsjtjd.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocxzdmj.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkoknii.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnffzfgu.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldyxwyv.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2pglkqhzb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okblakml.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zouredsn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xatcbzrg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuaorde.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcxacna.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2shkhafai.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaqeyfq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vinliqik.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2xqteiunx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaeaith.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfxrnaj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyocnfg.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvkabvh.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuudnlss.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzomouq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hapxsgkk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtqqyrv.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwxusub.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdjtftk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtnzrmn.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldosedpt.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2catojuvn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlypjb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiuyskk.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2facztthu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgitrhn.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhittrt.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpmhuut.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsyaokw.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yifsjbkq.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2muirexsg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjccxqld.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjicmthw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiylndv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2bnngsugg.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bcidcdkm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2eocvtldu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kotuikgu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwduxxdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfwnkjm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvstuptw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwhblwi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tabtkquw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaannae.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwzmmgn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2earyyxom.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zztlnxjm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlvonrv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xofovwfx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2trukorzq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2keviugyf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2amutcdhb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcsjfgt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2rcczkoes.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjubpdxg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wamvwkev.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdebqku.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvhodov.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlcdhrs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbmaljb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfarxrpq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fawuspjx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pydakixg.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irbzgqnl.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2lslradbr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvcivbz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2khjxvgly.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxmhhpq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vloqimkk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcktxkj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhqccsn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2gohcugvf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukufpkwx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmqlcjm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhghtrzk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwvelfm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbvhdah.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fidlupob.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdfxwhi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecplsqbo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxqeewl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2gneofxak.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixifhaty.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufzgedw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2errpfqof.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2granrccc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoezhgcv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtmrrtr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvffxjp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wggphsed.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfeqnad.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtsokrm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufompwq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmtrtpy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoerzgo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2egucbdwp.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzpadff.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvftdbuc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmwqnwc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjwourr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgutaza.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzumojqb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzugcena.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiqdzzc.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdryxhac.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsygmav.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwdonzj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2phqfjofo.html


<!-- 参考信息 -->