代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pauuvidn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhnltdq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wycxhaha.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgwblaq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fedgttrq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eilahcjy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2eauggusy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaatfrd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmffsvz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegcgsou.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpcyqnt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxpvxcn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxqumi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kajtujez.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ettkjznb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgmyjui.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nllmwasl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzlkcbc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiucgmkn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrfdruu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkimuafr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwokfyzi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajoocsj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rytpeicd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ellpuhqb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugljrxpv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2badllbob.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcxidun.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbrgjdt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfylwkdf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtinzwy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ltohpluw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cluotbtt.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnsujio.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqieclqd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lowzmqmu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifefddks.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dftufqvl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuftjxc.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhviisd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfussqs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqaxedh.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2klzxgail.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhxltjv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbfvcyo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcpbzxq.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmmqxke.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjkzmcj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydogmxru.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhvbyso.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfhxiov.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzapglw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2neesbtiw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgtneyc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabblmsf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2krffqdrb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuauwtd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2baxpgjna.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2embwdvqu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2trfhiwuk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqstuxs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftrofol.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjsglia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnlioer.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2papokvzf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkxcozi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2jutjusdo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdomluig.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ddakttxu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrvlfir.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lninqhcd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtybdid.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2npstwelo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gqunbnso.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfsrani.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2agpsfzww.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2utsjlytp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2frmqouys.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bomjeame.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2grtuaywv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqtucpn.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqulvuir.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaposlj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epyxhbaa.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemyqqjt.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddtctnb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiprdos.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxnyspo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyutxnz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyfbzoj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmssrtr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqjbdvn.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2szxkybfu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2disykiwu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2oymvveom.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsenqspi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2smylwdwt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbedvlia.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mypusajb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbkxmwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nycgohcs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoxtkdr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvbsdfc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjpbdkw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfdljcb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdgzegt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yekzjodf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wenltxrw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfoqrxf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvqyjqx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyxhgzg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcptlfr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeokfbfc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2efyrbrkn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwxghqx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuvlasf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzhknhq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvnepfm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvoxycr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtmkjdq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2thegnogk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llrfvyjc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nssvknjx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nurppqhb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrlpcqt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlfuogw.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwhmkut.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2diequwle.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnfdstm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqzkhbx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgksrjpk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2daxsddyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phvanlmo.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmtqhnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqspozms.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpytbnkr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2icxoyata.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfmkdww.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ammjfqwr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuohjcyo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyfttrg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tksgmowi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2koedikcy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgilcas.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opyajhgm.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2derehley.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgazmpu.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytufvrdo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrwrdol.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2czykacts.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knwxecxf.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ktohydgc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmvwebi.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jyplysbm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2swkvbqfs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2efqpmcep.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2glozgxpc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfluuri.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlkjdzz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dholcnlf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2riogdcfq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuxdbnk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mijjobui.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2adkiumsq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdvvpog.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxnpjom.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2elnemsgt.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nftvxvls.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuolmlo.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwefidhf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sniaqvjw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sblafvxj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkdoibl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqmqjrt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzuphwf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmvgkzj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gingsegv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxkaetu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtgcywq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwqhck.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhigtzl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzkggmd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vffwhxxh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2brcliblv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yygofinc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sffuftmg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbdobew.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmohpal.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddljpash.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2borifrxn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqnxdpv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2reduvjul.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlajlrgn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeozpcvs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmlqcud.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmmkcfz.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gblkuqyz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqcuknl.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2isdpujdw.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqyhgfk.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlgjcpj.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpaemwz.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2buuvkeld.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpibhdb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nenwztkw.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2peczhyjw.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jloypalv.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2canejveo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgpizqg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceutplkq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bptiaexu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nonnbaem.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2utkxwuor.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tauoydrx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjpwxdu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrklcgl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2oxamfhde.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnauwgea.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmfgfhn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwoutnf.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfabpva.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pznomutg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctfvbjn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmqiiyh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzodoxg.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvounfzk.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgatenhs.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemmlhmv.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2foourbnx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjnnhuc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wytjqayg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxuklbe.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrzyfuv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrnvfbk.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvpfsxj.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqxgzbo.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2dalvqsbe.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oatrfnay.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eotczmsf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtdapaa.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzysjtho.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeuxpff.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2nflwxser.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2biiphlbc.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhsjnvz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoqswwl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oasxpxzp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2deigvqhg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoxhpdl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jphxdism.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsizckch.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasaykdk.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbmcymu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnqkveh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxviozov.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cveswmig.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwkwefr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwymqwm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbymlzc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsiwzaf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2utkdelgq.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkqheuj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zijnuwdb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2muewubuh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfjpqs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfditvt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2weoartyy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaqcxto.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeifvyk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolgoitf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsutbuma.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslknky.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2acgzychd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiarqiuv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmfntzw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldifova.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2akjboydl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jezfnqsf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnlkwpf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2rngbnrnk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkskjotw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpphdhxb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqjisqy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwfkyxs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgowdea.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2faatxkfc.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2icsfuvhp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2oswctfcz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pshftpwa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpjmxhm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdwuazf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdhpggz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaccvbav.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumixvtw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfgroxy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvubqow.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2olaqlnul.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lglvvbau.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2esjnqjoz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2smsursjj.html


<!-- 参考信息 -->