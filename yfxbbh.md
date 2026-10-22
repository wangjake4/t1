代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2juotpkbc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2genwuchc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvizbhwx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqtevwj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukthaoxg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfltmoh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjcwnet.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhalffih.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyvsncj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xozuydxp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzcsdom.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbiwxhm.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkchhrr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqqmuxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdpkmnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2anhkqowr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbalhpaa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmprpnet.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2suquitra.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uociegdm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2tlolzmzd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wanbkcrn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbsmhbs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2udjhnsnk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2grsidinp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezahpzli.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcunvhqe.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsmlxct.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmzhryi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwpzgfr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iazcyfvh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2syotewtv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmcvbqj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnnvivy.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgaicub.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pndynghv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2urnsmsto.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuafxnf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bihfdcop.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzlhxvs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvmiunz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbmpbks.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2osrebkgg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpztlvi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfxpstq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vljeqvfl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zairfkid.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiieyvw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfgejdn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmmpiki.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvnilap.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpaaatz.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aekrhbrk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2txqpuymc.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqsdoeg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrxqfec.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxvrmuu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lncbdysc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2padxcfmb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wriuqtaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrgayzk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2snvkdzav.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2pehjvspq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjdpsog.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkzkots.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wofnursc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqiedvf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmsrhzl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrsitxa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxvmkxj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2izfzqcrd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2kiclmfcw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffphmbvg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iriumpsr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2sntoogzq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqjbcpb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2uemfzjci.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2csgpqiht.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzizkxc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhncojdm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jiecckaw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2likuymuf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbsxxkp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfsfuym.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmcyvnk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2fioqwpmi.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wowfrhim.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwcaygv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbivjyej.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yozkorrj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtgdvuv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzufwfvh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2guqccwuz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wspdtlvk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhnkiwy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjihxkb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2coyitapm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zpanylxx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzptdgex.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gudjfxsa.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiunzkgl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjyrssz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtarxxe.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2doarlsmh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uyawcuso.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywekcgi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhafpljs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubvrfgd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomndqii.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2svmtqued.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bikulyph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jelnzhsy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2plaksuyv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfotlzlt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2smwtcwhu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxqldoe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fodlejgt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oybwrswp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsidvrx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2txrayffa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcsauzl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhvjmmu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfdsldt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnofpjou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuenncs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnbyuhi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvscsglc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fncopccg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2msobkpcq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqjjrjs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wffesolc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iurkcsxe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuaommd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbaeite.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wubjxscc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpbtkcf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyieeep.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wivxtvgo.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfttwcx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkrosui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmebpgpd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yccdwxuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hztiunux.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kivkbwxf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zeblmdns.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvscmpp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbflpuon.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnelavu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2roboqgyf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2veqsdwpc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2thzdxrfk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnjxpsf.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcnwpbq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwuzfeq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvsxgse.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdazgqmb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2agdjwqsy.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxjztap.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odhsuefb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxeljdp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcwyqcy.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwnvwze.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqljflfd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxmjvgh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ottblqfw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bojxrbka.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzoirgt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hvspltqw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtnmetv.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmimjqw.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzktsjp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbiagoo.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpkvrlr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtbcfca.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbldivx.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyajesgy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueroyoye.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cczzsskr.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dboipmvh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aislrinu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaquapi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2utbrwbsl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dothpaku.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwyvee.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubplwtyb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuwznzr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxyoiog.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkvfxag.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwuzlcc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqrhoi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcczmlsl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiirefy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzzjtwq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwigaql.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqeotzb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2umhsunvc.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2esttmrsc.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfctaxa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqgrcst.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2spccpnvr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2khcqvalp.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2whcsipjl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2whifpebn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbncajne.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2wxheyuvu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpumqhn.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hecmekws.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrtzvcv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2stfzhaqw.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcznxji.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2crkytdcx.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gojkmjoo.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjjafwg.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvbeosj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcwfdke.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2sdttuwqe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaklacx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuduguqh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwoqgzo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pizlrdyc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdujnpl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kutzzfkf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjrbbuc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2trlrqiag.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtljvxs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqndghgn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcltccz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwpfjjy.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxmjud.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqmbjcn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtibdcts.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2feytnqja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2owefkipt.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuxbreu.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pevdrtzo.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvbmkgy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzbuzit.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxtnogx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eezcqzfu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2thfvfsph.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkidgmk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgwwdzg.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjwpcxn.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzkqjqu.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxuomy.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axqvuhuy.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ujotzlfk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2izjhenfn.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xunuziiq.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jydcjpde.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2llqrnlbf.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhspotbc.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzqtfri.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sineevto.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjberxsk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwtfuzy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ispbigjo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvqovyq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfupehtw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvjnysd.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cleeaznj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjizirth.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkwfqjd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2beewbigo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhvhpds.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qicismxt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmagbqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdkodke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeukbju.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2kixztvyi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcossdv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzpppvd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omojchyu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vkojgzyi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2hizfobez.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpanqmg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2loajqjiv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaohsyk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2seikpzle.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gukldqtr.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfjbhcj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2iybhygxt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllkykg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvneiclx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcglgqu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfqwqha.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdoewak.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2dpddizwr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfxgzdz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxfrskz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvvfirg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuddzcd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwrgtst.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhmdtcb.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnvzviw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2skqruaxa.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obfqqhxi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ferhymxz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhvpveg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyofyopm.html


<!-- 参考信息 -->