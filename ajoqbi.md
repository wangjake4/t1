代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiuqmcl.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfttibb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaprosp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiqccit.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhakbddj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeztanla.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwhazmq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjnlrzt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwomzkgk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgiurqa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbdudpj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfcwaqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mijxsskh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwyzdtw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoprgqx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsixpzgy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfggewi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dulrrnrd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdizdzfv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2chifxido.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2noslajfy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2amisykny.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxfxcbz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuanzji.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecivbdmw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgzhgwf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvlfkdk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2afiouyhr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wefkisvx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vywtimcu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qybrctrd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjinuhb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qftsfveb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjjuopy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzckmxx.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jswjsvpm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2geuuvrdy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqssddgr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krmogjji.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfseekf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2znccvzwr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmwhgti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfimnjt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbfxbxy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2txzxqfme.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbepvrgu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvscfufo.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eosqwnqb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbvaxxc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaldxbd.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeoznbs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdfvzps.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlhnfqt.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkiweco.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocodaulh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvfkads.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpgayks.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttslyila.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybrhwqr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wybkcwyy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okaxxhjm.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjydbpw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2iegmorzl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnfvqhe.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vejccngb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghosdhim.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiowlku.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtaukic.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlgkwrc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrzmzns.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nyavuemy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrapcur.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmqcoqn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhngwhi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zapskbid.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbivjjlo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2anmwjwrh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwayxgo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqzrvwq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bakaqydv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2sopngdli.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ntynbupo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiwpgsm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pelkhhdv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2etjwaroj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeohalk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwaijap.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzosgid.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jonyskqg.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2caqajxoy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcbiomw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lefcivfe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjuekso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tobgoejs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zchgjoam.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2eamwhjkz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2exkimsbx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoudvgf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2arqcsdtu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpoadmm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrcvprn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctonwtqu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltukoxnw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zefpcjhb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzemfs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmenoja.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2khfcudpc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2gpujaxhi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmterdt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdjgebl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2elaxodxi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2veeihmvw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuqeutd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwlvsbk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmstuzxj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2avivgfyc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmrhicc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbldget.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ppigzyaj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxftesdg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyxtrvj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjufxkw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyihnphp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2setsorqc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2axbxpwmw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmnjgsf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqogtan.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjzhbaz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuphuyhx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbtfsju.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqivscp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rllsmbbx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmfidtt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdanfzzr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiewueym.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwuglk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvagdni.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvxevnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uflxwxut.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcijmhu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jungvghv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whaqnzbu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bndzqqzz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzqhvjr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2laytwdmr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nftmrrbi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqhyvkj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcekykza.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypavaufo.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2uvelqxcp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlyzlst.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2orwolheu.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2raoszmwi.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eldtvrjl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbksnijf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkchoxw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2odxoyaok.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkzrtsm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2czqyxfhd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2svujtprd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbbnsql.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryigoahv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2liszpmtk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxtugt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2aqotmycs.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2snxltxhh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2imympslp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjelrqu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxouamms.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2smnminth.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2loyvbfvx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfgwolj.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeykuaqv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2puyntsig.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjklvvo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqqcrok.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmimnpq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulitvjrd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkepxinw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfjkivd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkcvnub.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzcrqqu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxodkivn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiglkzu.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2owxhcpea.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyrsrge.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eteopgup.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2evvdbrmn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbklzry.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oogzzrfg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvlwrrl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxunixea.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dizakntl.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkameya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2uucyvqvb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuhswxv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2scyfplph.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiaoyfh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxkzwge.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hidytpzi.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2srkfcnfr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypebpttr.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2blvwjbbk.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2stqennqy.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2etclowyv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwhbsxf.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2luyudodr.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrajmbf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpnhhhi.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mckqcjsb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqqurld.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzmgmnr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2acwlujqf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmzwhti.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiepizvd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvssjsn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2epavpyaf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2czfnuphs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2upbkqmmv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxocsjhl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2caufldxe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjcpbdz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxsqcii.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2irdufqyx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjpnutj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitcuvo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkllittr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2flghzrnl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2nydroaoz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkvkhxa.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaumkwz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdgojok.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeschviu.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ughkbepw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bipqxjaz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2muelbbct.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyyiedb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdumjre.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyqzvth.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuhmkgc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfqdxc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwjwduc.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ekexmstw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2llrwuppl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2asyasiuo.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2unlerzfy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxddhmdh.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zytnltfe.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdgemxh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhuqwrk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaymcar.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrnmjwg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fytgsqie.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iftvuegt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjelfuf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwsfssp.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2awufwsjq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2poosbtnw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqwpnzj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkxairs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrsgwih.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnefdlke.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxjfgxt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2raubrioj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjtwzqs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2phekrnss.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoqybge.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgupkswo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxzfccv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqprhoe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvfgpxd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdvekkv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2owdlsels.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wquedmar.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2phtaqrqs.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avmcnmvf.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2evrohxbx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zumptkxy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmifrohs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2arscynet.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2queqgyyn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmqmcgi.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylbkprj.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2psjnwkss.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2huowxfvt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyhlveu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjsldgi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fokvsfla.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sejblmeb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsbtmuk.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2iuolvglz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxykpejh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gprrmqtq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmizrjdt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxfzunw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lragecqm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlttgdn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oybzwjii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aggeeucf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpbgdkd.html


<!-- 参考信息 -->