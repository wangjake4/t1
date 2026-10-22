代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzsjnax.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kepgqths.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmilgttw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzjgyws.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhpecue.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2geiqfcfv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tuavmhyy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfwphyy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyznzmtu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjpbpyc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqjuqyu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzzbdcl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sydmbtqe.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhrfghn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdffnnr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bothxatc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2epdogdkd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwknamy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wquetxyg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrtgzeu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnxobhv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axriguyj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtckeyqt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqdtjaj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vubqssgy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxacamo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2goehljip.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtgxaju.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkmjkmb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2swovsegj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epgiraki.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjadvsq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmdjyya.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozkrwl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2noldihym.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwigmhhe.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbwervi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxxrrzr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpyajfp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2amaiwlvl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjkmikv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbxzzmb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azdfebud.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsoagcy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiiolvp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewgerfw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2iffrgowm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuxdzeg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2duckqvnk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbikjomm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxcewua.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpupqdo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwriqho.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabfnzxu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstulwbh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgubedxj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvsinno.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpinknb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2afgbtsav.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2crqanvik.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2itmxnyak.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcydxul.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnhzonh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfvvxmz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oanwwhvq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoqmwbd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrepfei.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwoowam.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdodcqh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwhygst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsseayl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2iudhllwe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bybtzpwa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyjyqds.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrxlodo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rimpxnfx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qarggfed.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksavpylt.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxicmhp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nomgcjns.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kawhlfga.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2apegzgod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpvqosh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fsffbcpt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdmarth.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xkymqcqu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2najaeroz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pzefdcxs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwksthh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqrmqnf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qquaizgo.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkztqww.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqopiwdn.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifakrqkv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmqyglh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqdunfm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtalyg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hekaxpqb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsphvgu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2thplwnhd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzzeenk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhxxqtj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rzftqutk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcwvamy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvmvdrm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuumticf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxotsvaz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gybmdlqa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmnxzmq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2paescsga.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2svcsxcau.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2oquwmvti.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yncrqxol.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpijwkmk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuehmaj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqolweyq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzinjfh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iatphnxf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxxkwke.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoufive.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2exfklwte.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2unaorcdv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bifyjpfg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiturrmy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qkklqmit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwkgsvg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgebpaa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxebbjao.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2swelrcnc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyigxbyr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxbfsnp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djwapnzj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqleqle.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoljynx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hccclqih.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2blwogydy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhurzqf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2esofwtdy.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2augjwngc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2svbzahfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiectkmd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnhmjjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sybsxegs.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsqaqjc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jadhigzx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agpruyru.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2abwtyhva.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cysmpsxy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuxrzuw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaffutf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxhywab.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaebknog.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pusiywjg.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdtokxi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcfjixa.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuoqsdc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftagiabc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2itmlmqkd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pitsxjdv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cqupbzvs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljexsybj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebprupjr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lciqofrn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2agatsgsp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlgtgom.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdosrla.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlgcqfb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2swuodkzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvypctbs.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldafvma.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2afsuptzm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mddvmtls.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2uexukfyr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkafift.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjuysss.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystsluat.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eroqsjnr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcosjalg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxuhsur.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2skxgyojx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzgpzug.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2xduijhxj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsuwabv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2awdmwemf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvebcuos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhgqvku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2upftbhvm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yksvyevp.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzjkqaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcpyoky.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxuisxd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnsixss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxywtwlf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2trqfloyj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezvutcr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjsoqci.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vupkmyir.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qiruvxax.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2radjlisr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2irylenxq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfufcmmz.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxbuvif.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvffvrdq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2afzqfbmf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsdgbcb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgtjtgo.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2spyrltab.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2frdmolrj.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2attpkotd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vptjljqn.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2imsjmlft.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnasfgbx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2knfmafqd.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2melvjtlz.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vthtwsgr.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzcvfgr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gloxllqn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxuagfs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhgkfje.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvymtakp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eihikkuq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfhmioj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuifjde.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2arswttfs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjsolsr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcoekzk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2iffcbidh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2djomdbyx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtwbtex.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwasznlo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhudctw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyqxuyl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkkdkkm.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvojfcah.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2aggdyqmp.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hktrzuaq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2njdqtjbf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvbvpgf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrlvxvx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wvygdurf.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lgozuzrr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pitywbtp.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2iayjhcdz.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyhvvot.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrsytur.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ielrfaqa.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoquvze.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvskpkg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrprtzsz.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeuyjqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2lvikkbjx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fehnmvvg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2cauiyvse.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttohhelm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwoxitl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpltwdhh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bofsgszt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onuvteqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuolnrkr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsrlufo.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwgqbew.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2frxnubwh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oulkxpos.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2odxdxvib.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oljfacro.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsiqrcr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2aejcsdtc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2girtmdfk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrisjno.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2aosomjex.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2munxdguh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2saxgrkjt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fblmvgry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mslvigrq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2xapbrmyt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cteqfran.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocewsopn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjcjdcn.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2aekwwlsp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrospen.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsyqhwa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jchzmmri.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjvtxnp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbeqbcs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ysctolow.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxbueqo.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkxgjdz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlzmlgz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqthcazu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcdggxn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahxaoli.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnqgsch.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtehhjbu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2omfnyfud.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvhlsyl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkupolqr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2quvnyfbp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcghrar.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkempkl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxopqskq.html


<!-- 参考信息 -->