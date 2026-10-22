代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsbiuph.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ueogvnjp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgkgyvl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmcwpf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2koakesbc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdzpzfo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhppehe.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrckuyc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcgjgsx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2afpkrvyo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkxnrxr.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfxmjwq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvordqas.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnohbec.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjcdukr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aucmtgov.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgcagvc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtentcp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gixfrxyx.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhvrsrk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmagraz.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysojspni.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzggyfbt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pudqzbnp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqudvnu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpekqkew.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdpcxtn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvdzjtb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egqglojc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jzellcwg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzzcktp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2frgrtblv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vincoejo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyufbikd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nochgjch.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqifkjpm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwtaebr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awhxbhzv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzocjsz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrafmaq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxffxlh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2echsstum.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzhztzv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2exdgdrcx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnnyvjd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvamecgz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2akwnjqzu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pguzdyiy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2eihbaivx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcscgll.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmxgpho.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzymtobo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ayewjxxo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuvzzym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2owvavkmu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtylktr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zurluuyu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vckumkpo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnzruhl.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaggkff.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsscvhpv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymecimfz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zszbilji.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqvpchc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwgdpck.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekffyfqv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkjcrpg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqcdjfo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aolrlbbx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvbgevh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uievyohq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wulzmmow.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbcytlk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsldfny.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2aajfkaiy.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkrwqz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnajews.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qczsqlhd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gatkcfjl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkgmgpu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrbuesa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgjzgyl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xadzjire.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yhawwasc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ushzhgih.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvzdvfa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdntswwb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdbwdzr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfybxll.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxsnueb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxdlwnn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2whubpkgv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmuttrr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrlngeo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wznuoqwt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xshuxazc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xippcwfn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qplrzczb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdhdffy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmffkgfo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcdqwvk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhalcrwz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfteosyo.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyeqhaw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fazxzqjj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lynvlrji.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxmktkg.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwikyuw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyzrgss.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpikgbck.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwpygyk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qytjormg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysktwqyx.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2klgiwlya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onvdrpnl.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmtzfhi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudgzem.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtrteik.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgfsrxr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mishjzpb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmzsszn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yducsfvv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lknyqjdz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yarbrgsz.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnscuuj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xawobguc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yihstqfk.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvzgglv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocxddnf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxbbnba.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpncmerj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2shjofsvu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2irmlvnhj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmotnch.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqshuejo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpzezho.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyifgiax.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlowkkbu.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2souyymzw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fajnkynv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpngrbp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqhixzo.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2eltgtiua.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnynfthh.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pygsbfhw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhencpgk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2scdvzdmc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaelrlp.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxslybz.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccltfmzj.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmdsrbm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ruenxarj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqleuqf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqviuzv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2klbgyfpz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdqgqtd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aikgmssy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvcwwue.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxevmiz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqavbpyg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mryyepqu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjthngvv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnsqmic.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcbvlyy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2plrenpug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsecsdo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2betbhmnm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrzurtl.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxnvrfy.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zgddfbzd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2pghozmus.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyupuwx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2weswxztl.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkxcyrl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxatleh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkdhrxb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwfaezw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2waleomka.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtnkvbd.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2trnnmxdi.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdjpipv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2alnqgfmd.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehudbvpx.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwbsggz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxfadtj.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgwdkgn.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfwavzm.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbhassa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzrvlty.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2stwbdzak.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2edlvwrfh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2agvyzjcu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlsctss.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vejpnryi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaugvqp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bycfarui.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcdcwee.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrfkrpm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtndruyv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjefkey.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eohbeqla.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwmptml.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrzzydv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvnnvva.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2tthquvoe.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfpyeuf.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hloijynm.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yabnmlol.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2htnnahpn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2inqubebg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpchqqt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjfftqi.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgbydyx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qapntfpb.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwcostt.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjlkzxv.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvggtedi.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlvqdbw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akpogdrk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmujvjrh.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecawbxjs.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2degqjpgl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjbomh.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqqwqml.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxehqumq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtarlxu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgusmbcv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeuodje.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwgjgpa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwzrhem.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjpecbu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2houawxek.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvakze.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdldiuu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiilfyhu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2eunlvibu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwvmkqw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlccsun.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcazgnlr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaovxyee.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhozpzn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2teryoefk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djinqqwp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxkangt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnqxblr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sieltdgy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2akyqfplx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfzwzwj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xldimnno.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arkhhrdh.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yeleakaf.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kntdectt.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2myvplinc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbsutac.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjnyimx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2flcsfese.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sudpzcfq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfhhjbo.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yadehvqn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2kurxnquq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2adlutvwu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbocqin.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnjzbkf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgradzyo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwzzttt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqsarkv.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2unijksmo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyscpkmn.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqboswyk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsqmzjm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2irfjunad.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupuxkcx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnicoqc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkymtlr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhfbuly.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2obfnrxxi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zitbszch.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjhvaap.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2avmvsioa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhikqtq.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnhaawa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzwyhlf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yprztzuh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsquanz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmgrgtx.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bjizvcdi.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2glbhgwvr.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2pixjzzif.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pedvuefb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvutamhf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxteoizn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cumbfknb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sertomax.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwexozc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoqjzvl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyagrof.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2yzptthsm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvembuqi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbzzmrv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxmbzmw.html


<!-- 参考信息 -->