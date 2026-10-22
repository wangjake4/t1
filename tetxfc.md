代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrsnszs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwotibs.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2etdtusfp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oodmtnlu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xewcmlit.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cljotgmm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfemtalr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqgrrjy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyylaalq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2khznpafo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgwnxic.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqouzso.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2byycqjpq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdhvvye.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2amdcheej.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zesshbbk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmmknxc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yosfiubn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcrjwlg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ztedfhwc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mislrong.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2utxxzprc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxkadzz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2pswqplsy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrhtogr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgjnpoc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elglseba.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2osdbgjrd.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2igodthnh.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2esraeoau.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvptkod.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcunoqjb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpfhzpx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyknijdd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2sggduxfh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvgxqws.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffktcaux.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2veykbukd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcctcmr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxatady.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pljqjeex.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aovlzrwv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzpkhpl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxepdha.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvephfa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agzjdsbc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oemwahay.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2makftqnr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mezluugl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzbfiwk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zykclhsk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uncnkfle.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwhbgcb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gegmwydq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vysobfcg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2whstkvin.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhvynwq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2arntiqna.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnbzjcz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtotbms.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xopmkdcl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwqgone.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmyaygm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyqcntl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaxckgn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnwqija.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdrnhis.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hextlwth.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkkdyej.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuhbtjg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwbihgp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2addpsktn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2anizokmi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbxzleg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrqxpyk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbkuymr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowkxgvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqpayak.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjmrnzy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqmmdih.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrguieax.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhjagen.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhqpzow.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2suvgbeis.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpnqaid.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2shotetsw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2aynkbbar.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcudlwzl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qptvqsjv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2coaghaeq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgbtfvz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yftkgbby.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2okwdfmaj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzloeo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2luziarxm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2twcfjaco.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aimwwgvl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmekhyb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2haaewasc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtoaril.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2prrzkpkw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnbwbfx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsveyfja.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2izdicblk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlbnpqz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcwozoy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vibemhed.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxaxmwc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2geeajaqw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2clyncvwx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqulbvp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2blqyqhal.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjafsei.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrdgfmz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhvvvou.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmuiqu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsljkqz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhsryqw.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehkcopu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2thnijfyx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awwotsih.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdqjvnu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacidym.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2qphojikd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvuiwya.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixrravs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2aztcplyi.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvbuppk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mixqjotp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2geddhmrq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdkyoyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mereoxxe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtavfmlj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeehoxy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkpdjsn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2cxujlfox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhzynfg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytucmukg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yabkxxag.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhptfpxp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtasxfr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lebueotc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2toosmwkz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjaklrt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjavnnw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhsuszl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2pegzoccx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeghtcmt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ythaqnfg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgwejru.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqpshrz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bodgvcqs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2lklwakyq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yczsssvb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afllzdwa.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfuoqtx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yanudxfz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykplbsql.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2poxknkyu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvtcejo.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkbbjkd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uewcjmve.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2atnpmhkf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2btbifrzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oftelstx.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzbocho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxfsduw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgoyags.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2scdrfwkc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqapzcw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgbpglw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2widcjtmm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtvbeuy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjuqlcl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrvweow.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eucbpoaz.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2paxyrjbl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkxnaeu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyfawzw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2twuhiteh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwphdhw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxscwju.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmemrkp.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ukynzahz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2niyngumb.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxgsoao.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hioevjot.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2akhupvdo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmifexi.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwpnnlh.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnpxrpf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfqthlf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qrniuxkb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktvvixp.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2whhdzqdu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hieaiclj.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2scknyxqk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2paloramx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkmemvv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnqszqc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzasguyb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoaspxw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mibqjrqk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nfftumzi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eekoypep.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttrumk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uovnsdvc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxtvuhq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2azjbxjxn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlrnknc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdakzvy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2daicdiqv.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjerpo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqmmtvm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxnpiov.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxldtjo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqihmefb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bojfgdbc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hidslgsc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfgeoor.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqechlr.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvgpyaj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnqoinc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqamtowv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmeshxy.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xszzcwjn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqfuuoc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2igcrkvvh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2iauritww.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2talbmhnv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wtankoco.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyqqovv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyorddg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pviedxzv.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpboekp.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2embgpqln.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gofwocnm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmjjvnd.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvswxxcu.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2oafbmiad.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjvtjdu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbtfxty.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdwuvvq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bofywxto.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjujdgqs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfcgvcn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnffuvs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrsdmcc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2yszmakvj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyitams.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2whydomxc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsuowbb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhlokjb.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmilkdnb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvigjnpf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwzcdmr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpmahcc.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnastdbp.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzwlmfh.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rabqkhqd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2heqkcrol.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhvrhva.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ficxmuzq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgvembh.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ckecqwql.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wokrrzdf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvkqhut.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bofdggwb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyynlgb.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vptddunw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wunakzcz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdwbnko.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcbfqlj.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdsisqr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2elqnvqlh.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eedzpzpx.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvgaxnz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjojdqqg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdbbhsw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlwogpq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxvyafr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvevjxis.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiyksyl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ansfhqzy.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wwogrncr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mspfijot.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anjyzgnx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtisxah.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbixpkjb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwmcgno.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdhvgob.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhyexqb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2azizzunt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkwihrz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhxignk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lacrhuit.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpcgats.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbgldcw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjcyuwq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnogeckz.html


<!-- 参考信息 -->