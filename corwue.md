代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnqcqzj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2apmmxphe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwqefdq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iocrfuwh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2prlcnbng.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wefqljqy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2noulzexd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzpavow.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfwmmem.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rexkuuhg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwizxunk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgncgykl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqautrwl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiwsuuk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvibmwl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qktrsmhf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpfcnqt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pddlahzv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2foouybno.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwskobup.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmpdaqy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2toowqbad.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzppqvk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahisayjt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkelsre.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxtzvxk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwybizn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrwuibi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjyhpkl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuhsgsn.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtysaaep.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrhoqzm.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hozumiop.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbldbef.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2twibwopl.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wuohxajw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2urylvrrp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyjrmwz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfjmhzx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpghwak.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfatvtxx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qowvxsmn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2phgkxawn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vevphkay.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuvqzpw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmibidzi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iakctwtf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2naarmxlx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyapcfqj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkqnhin.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2euhqtudp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzslrgr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfybsmbr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2goldsgrz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2csjdrjkq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cuehdsdq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yrldkyvc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2llrgoyos.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbrphan.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqsqofr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfccsqqj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tabqxwic.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbfcbdo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mndgktva.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2csodljtx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfeapni.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2suiypwhg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gsedwibf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppehjekb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgkzkfr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwzlqbx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2arpywmmk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoelvmx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2xouqsven.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxertty.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hceohxjb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hzswwkay.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnmgchp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnguoazk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eunvwxnr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxiemsh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2zotrawbb.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfwmwwu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmnajit.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qebqumyr.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qomqswxt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2llhmrhhc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgcvtdu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tayktnbl.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wracqdch.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prmmdvay.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekszatxg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzsjnnf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsyxhfz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaejquub.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcbmgxb.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqadbbm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuyhrls.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzmuchm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqesqdw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcsdypa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdjxlzz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2klbkwdjj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkdplsu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuheajbe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2njijnxsn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zujbfwne.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2drjzjwwc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuupjvzm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zizueova.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2stmjmhqi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfypfiy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lechtnxq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kajexfgt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ervfbjqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2btcqqrly.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oksphzmw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmdepbw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bisfrxcr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaxvvnb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjyiayu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrgrzoa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwubkzqe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjbavpe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbakniiw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eholknre.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2watvmrcu.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tovwbvwn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpczujg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuxgfav.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkppwpch.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfkautu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbphuou.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxxvpuz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgqzird.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2reuirdhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhclplnt.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuxlquh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhniqyc.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnjeoxm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpfeduo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkernwe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xboriftc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oomohbpg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmirvyi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynlzii.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2exextjzz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwphrykp.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lurjeikl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2latfoden.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdwauvb.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2umqqhjix.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioppgbup.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrpbdiz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhjavag.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2toukplju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnudxof.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wggevsjj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdgozte.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnmarlu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsaffjr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2itkhydaj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2blhnfngd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgxvama.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzjcidc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqowrku.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyioqnn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbslfdzs.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzndfpy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hegwcdzj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2opxxepit.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2omouojee.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmndxjih.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnrjoxu.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wemgopsy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfynsvy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqitsfa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwofsyov.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaiermg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmabfrca.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcvtfmf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkqjvyx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhyufos.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwkqcqx.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ageexhuu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmgfve.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lovlszzi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjmnzmt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2prhvbsaq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqpowop.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rffwkgyy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sizonrjh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kalqdbjv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqiwzqx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxlghuu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiizuqp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbukkyaz.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lztfvrms.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzprcqan.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nednmmru.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ynptrdiy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhewaru.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxxtbed.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrgmkoz.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdnmjqv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkebhpu.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcrydhi.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvclwspp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfcifiw.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrexxto.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2havzjyts.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmtqqac.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qesyzllf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2txgavany.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwbdzbx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2spnmfzxp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vulwdukd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqgfjzk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2whzzvook.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iozyhmox.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2zcioviju.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeyzlvk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghmgpnc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgvfzoe.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjzumnv.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukfmvat.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pztaozrt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihiava.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2wagpmggv.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vopjeewt.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvvlszy.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aicaibge.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnephol.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sntfrhas.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2crugobjh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiptdfr.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvxapae.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2brxowzei.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfncuotq.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2emeytehk.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzthcvy.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuvqbgf.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2txrprgfs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2satuloes.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nybfwswj.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbogajvy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2bltoznwv.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2frgaffao.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2dazmvhcc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olcfjqwx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzzdrvd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyudnth.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzjusjv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmsdrjg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecettmf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qppstahd.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sjefvzxx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qglihlwj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2olgyamnp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wztcftrp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupnyogn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjukzhbk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2xamuangn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gglbfpnt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpmewpm.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwcehaj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkokelmo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoyeyns.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlzmbag.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbgpncb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2svbiuroa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzxgkza.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yahmlvnn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqyvxal.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvcrvhq.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fctcsuxq.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmijhni.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdxzsfq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpuqifz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdexzwu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozptryao.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjckfaa.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjipkvit.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtwydlj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqydrvn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcimrac.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgflmxqw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apcqwzal.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drwelxhi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2erlfikph.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeiieyb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2hykvjppq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrlybve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxszdomn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnukpskg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2swifnoal.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkwyhnw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnclznmv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcsqyxi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2locwifeq.html


<!-- 参考信息 -->