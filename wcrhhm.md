代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxizxnvj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apyygroz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqxdjsd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2veehgkry.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtckdzcy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2skjnprgv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtfzdll.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmhimwr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhqdequ.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmrvdsf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqmrhce.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvtayhu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrutkhrj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmexwhha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgfcjcn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bisvykjs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bihwgqqy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2aegubqmj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2miwiqfhk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aflnxixi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkvmoio.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2shbhsmod.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsrmdpz.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fezxxmpl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wphnkaca.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjkrgfc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxgsazk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvrqozl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvlpzdg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyjfhgs.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpceymvq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qglzayhq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcubmvm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtsudjw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpgpfng.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tseuvccn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbqykge.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzvrsuq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2idgbzipd.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fupzwviz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbgrrop.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2asqlwjdr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2weucszfz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeqnvwp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrousecg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqxqhdq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2aelvlimf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2smzglkhv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zryhbdql.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2svjjswen.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxutnmo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqmjtri.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2cughrddx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcotrsnb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdssmhr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wraocstb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjaptuo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtsvjni.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyifirpa.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lklpstcl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxosgqt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2floajosn.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uaksvitw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlubufa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsszjts.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkynyuv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzihnhdk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdhiqgf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjudsoai.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttjohxn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceookzko.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqculmi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgxatnk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjjkrsi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfovswh.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2yyluafqn.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeqfhtp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pevybgzo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dcioraho.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyzvjhv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jblxwryy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrcekqj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqtnhmy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwcuryt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnzdvzc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtqmgji.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnbwoiz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qynersfq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhmzom.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaiasib.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkbsonm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwvmpcu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruymfqwh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekltjre.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzrcxle.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvojolgz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xycynpkj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2chcjwski.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjagkcy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpewumxs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xggqlsyn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2olulperv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aztcyyzf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2djizywfe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvnsrfs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kizaycpo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrklzup.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2elrhugvj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgbtzfy.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsqpsek.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2clakdgdd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hptddbix.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yatzboee.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cblgwgzt.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzufbtvx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjhmqfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxysevp.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mufmzdrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewewaqyk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vllucsla.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2iptsadjx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2idylyygg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2htelbdxc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyjroex.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2srljbeac.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwxywsc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mcowzzjo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2quhozurz.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgpwadf.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuiiqdp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njswzfsi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfosjrm.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2parzorfs.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dziegmtl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkerute.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fixjtvku.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzpkylf.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiyicyy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbsslya.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qotkyxwc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfxdgbr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaguynzv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmomwqlz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2adgconmy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iugywuhd.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmibrzl.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2rpplsijg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgadjevx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fggbbmpr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjnkrnd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzazhrv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfndfbz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2drqqkcak.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zryyujrx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpxzcpg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bctylqhm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaxigie.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdthykvr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iomqljbn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2huyanyfo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lifwxrbn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvseelbf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoqpiou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2drgiemxy.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2owzrqhed.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwmmxoz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2azchicwc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlrnbf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwebcyub.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtxckty.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaeoztj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fctjtcoe.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rigslmrm.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rruqxgxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgmmcw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpvizqv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xudwgkea.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkpgsvh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qytqzdkm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttamfohh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2utmrnvao.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmnhrxc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeivppn.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2irqslzfr.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnysuzuy.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2srpvgytx.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwdjtmo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2soblxbxx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwcunif.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyniskaj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbixufw.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rrexacxa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxtajbb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyjjanu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2takwgnoa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrhudef.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdmddfs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjjczwt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2olorwxtg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdvwwzs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjzfqyv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2utdpxbgz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2phmbugfy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyneekz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiczdqww.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlpgjyc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuqnvae.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtdkxhj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2btabeetz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iauyfhtw.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoriytq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxgtmgw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlylnyoq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcswbxz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmnuoeh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tzywccks.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvvajpr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbplbuo.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhgilcc.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2axjnubxz.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjihkjx.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xabyhkfj.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtkknvr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjwyqaz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixkvihj.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtnrzdn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2swdyccvd.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iubwxasd.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyvandm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxwvnzi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujamqjnv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khvickma.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbifqbng.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpwcpry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzcbtui.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmryxck.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsmrkxh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuqpeqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgtarbl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfebsra.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2enqfuwne.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjzwwum.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtfdyty.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhymshot.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuujvil.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzgazrf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgcizid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbidhox.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chyplhzv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2npvvcwjh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2meetrmgj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djbexgiy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pflievpj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htnjqkoh.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2djxyfhna.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqznkhtd.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkbpxas.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpomvdvv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2beadyfmo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekasdabv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2krgamkvk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iszisxzf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtberohe.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmadvpq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbvqnvm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrljvucc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jugycomk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmuvhdr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixuaduo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaqucrs.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hiltzuud.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jntogmve.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebccrkqu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2sygdbvxk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhgepjv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihseieip.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvwukla.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazilyky.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzchwnkq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtxdrrz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsemjgl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfabfbs.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fllbcovd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkbhosb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhyypba.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiudksd.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hshngkyp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoosshpq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2gczgkaoq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcufwaq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fksbheha.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpdywkv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyuemzp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jebwxfmg.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhmjdlb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzuoiqa.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxvcxwd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zklfulqq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhzunlr.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2asnlxhaj.html


<!-- 参考信息 -->