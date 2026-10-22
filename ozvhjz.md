代发 wailian999

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mfevkagi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2axafptib.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2myghvqlf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpiwxjy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aanrastb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tevjolpy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yukefqka.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzjoofq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkszobbd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2arzwivbf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uqebhmxn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmicshhh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkwqype.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvsojas.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2szoujpqe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvynqze.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xplirxfi.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpdeeii.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqfnyso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyrkkb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhufrpaw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvmypat.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2riuvwcys.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2butuzjoa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bchibpay.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdadvqj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2soplzlhk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2necfadma.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsvrhuw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghtakgp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaxlypg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzrkejx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrnxlhe.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhffnmqm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqqzryv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xukcsjav.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xplecydc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2perwjbws.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyismygi.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2juudotaw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaezkfm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjftajee.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lqktjvmn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvwkbpb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smmaxaxy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vegrknpt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptetvcrm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epkyagdd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxeromp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkqrwgt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuilcgcq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wixccrfu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2swiofpfs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgkgyfn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlnukgz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aahgmafy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fofwdzeg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iosjymtp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2anrpvbkd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2myfkgoyq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plqnyzej.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2denbotss.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgjgppo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtunvo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2avdcjvfh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwnzmil.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgktrszt.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbvlfvk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpovgpiz.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbyfylt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrekycc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chaaagwc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlmnfcx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpkkoom.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzykztn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtbpxzq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxykafi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbacayv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2yudsvazw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwgllpa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhyttjz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrofjzh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohvintq.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xclnojuy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yglwyyfa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vliuwmlz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vubmcpvv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2aznpjohk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2upqldehf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmobpltk.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxentgql.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bbywqibk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbqpxoc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dviwahdv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqpzfjz.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzeysve.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2paeuovqv.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuplzko.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyrcmoh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoqrubs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acrnuwht.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbskzzk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltahpcyz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruslvrzi.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqsqgjp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjbhggw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bppmoczs.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpbszwq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wniwpcqg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnzthju.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2czkvjmib.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iosjhrlf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwrvjvd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2emydfysz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrhaaji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhavqkp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2betzxpmz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2haxggzrp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyumeece.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlhuijh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sicqqpux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lviqvian.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pthhrmwi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cicgerpt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbadnvwl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtctghi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbyotlk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoomwqa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ywndqctl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzkepur.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfiqwbe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpjvdvc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceewskdc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aplaldvi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnqgrsq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2piaxsnma.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuvhmnt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjsqhwz.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocibcyow.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgtxazj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwdmthg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnfwcay.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdtmijx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lycrhqcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrtnent.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2giixvktf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjhflem.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzupqbsn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2yekyapke.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjnfjsu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjytvpai.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhergbnx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2npklwwqm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2enxjxxjp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lgidrofs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjiybbo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiihovj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ioodsxfo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwdfmqv.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2agohwpjy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nksvwcad.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpkjgvk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yriqbzfo.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kazionhf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwalxqki.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2seokwxav.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyngtlr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dahmtirq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvjdebj.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqobexra.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2peluqalq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkfzohj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nocvgkif.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odywrfvh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2xaroagxt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcjosfg.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrbkija.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2luheadnj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmjhsvu.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkatvxqh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvjopjv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjbdwpz.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jprcziuu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mrostwfq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwzzsmy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiwheas.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsmlaqe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2phjmsrjh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2odnudsfz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2htsyhwvx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdjivff.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzszzfg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dipuoqqn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgzibaq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2spmqotba.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwsqqnu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2deinzypn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2neqeelfi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnifaldg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwgdsky.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2irmbskkk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfenepi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2bokgjnjx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmeynsq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrjfdyl.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmgfui.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2abkvjood.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbkfzou.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xeatfnvt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2omaqqfip.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnzzwzc.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtlpotk.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbgtnko.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpduzdm.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2szysztbe.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqaazqc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vekowiht.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uirnyykc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogejoth.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2fibynmgd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgywrapu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sopjkbzz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhikcj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2agxnzzqd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbqkrcg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzcrvpv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jllepvhn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqelaqjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcaeojm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuujeog.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzckbjg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvprprx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eonyzupi.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hefshoip.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxotatiz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdmohym.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrxnbup.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dchdphqn.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bisowxfl.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dakcsnim.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agtmoyto.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzjlnfs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvefpuyw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfnttev.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrujomx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrpyogz.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbokkzb.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2phvvwuje.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgvsiuw.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpesjnwz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxnatvl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttprheqk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dijyvjbl.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrvydsx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdkkgqx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tokncfws.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsraegsr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcbuupy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvdnbcv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anwmnfbo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oprgiqhj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxmjhmw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhljrih.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wamaoxxo.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtognosq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2woamrzww.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrydgrs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2minzsiib.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnzrnco.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmqydfk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgckzkon.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kguqzzek.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsurqmyx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2bksqavbn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tenryuhe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbglsyeb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpwrggv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2esaboaht.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfwsjnj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmfrwds.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpizqpup.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqbreid.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhunts.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuinjup.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2dycbpuaq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2vljdfdff.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccixorut.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgunfaq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsmbjbe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvwedjv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdnqwwn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2muywvkty.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnkqubu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxzlgsv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpzaish.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hieusvwc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndlfyai.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jysrfbrq.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2naocvlrw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2riwpjxzx.html


<!-- 参考信息 -->