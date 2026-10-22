代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpupvgn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2whownfjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiszfdom.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvbwxri.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsmmjbo.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2salyibua.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2glfjauwm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vecfxtpn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mseixvqz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsguufl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qktiixzo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaykqbff.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2voaobddj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bojyddzo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2adcfvyat.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khsjshkc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hskbeeob.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2exxhvefm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiubezq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2thsctoux.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvldalh.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2igmcryuj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azchhmbp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhryonyo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjyubgq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vuylmllr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2znlujpsn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjnwzgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtcoaiu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifewdlra.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2maqfoici.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqurgbj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2brirkyyr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtktarh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2smhxbdsh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2okwcwkra.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylafulpi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhgvqtg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyaynwv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2suovswxj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxfdxqa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pagjlebu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqtqcej.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwahhpd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqheugp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fpirkfaq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiehcwz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqxoiwr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tvskabcs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wohkzlfv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjwlzty.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnhqlsu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvqxcpz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xadljvqo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtavhhvh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnstgke.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrcpvum.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeeqvhi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhdaauq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hspjftbn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpgosyh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztywgts.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2drkrpgaf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpndxqr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oprltkza.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qagyxntd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwthtfwv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgysjlj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2twdnxgnm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmfrajs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2efiqwtbt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyfommc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkwikfg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqyauic.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbowsst.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2sprmbsvk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsimuqxs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwnyzna.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjlaxp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcvwupf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaasjnol.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtpkksw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyigahby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2owgbizpw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbuphkr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2apnqigbw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrwkhfp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtqryos.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsrgnqq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rigtfumw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmdrbpn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuzownl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyigjdr.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmazhyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekidpvd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoazvni.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbauhijw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbtvwho.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxpdevc.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2sgejwjsg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tignyhsn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgheyji.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaisxuy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuxdyjb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxvjrn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2royaaotp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncygrpnt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gubheflw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlzuras.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhkcbf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ektribgf.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjbqnry.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2itloylln.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsbdzmj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvifzfbw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mocoiiky.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbzaknr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vckmmmki.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2kgadkohv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvltaxym.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdzvldb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2saedmaob.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjojnne.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyeaini.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgmygsu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuaiysb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gojnwtpt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrsssnd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvmtnry.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgypkrrk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqrghfv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfoygxo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcjkrbm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzvljsv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyjxneb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaclsnz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2isytcuay.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2wozadail.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtgucoy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2omycndmx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqrpywx.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2edenwcgz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjktweqi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbimppqp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ookyplno.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2plzgjskx.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzsvyw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdfpnyx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyytuazb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqyrvuu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgwxwxw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrgpaxn.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdsvrks.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapnwknl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ekenokhs.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wljnfloo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2idzxhpsg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldnagpz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aloblobi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hueuyudf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzvgbvz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2andiughf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2saxserba.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpunewg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdqlhmh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2osbdfrit.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbjyese.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sreukkkr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxoproz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuxbrkl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzycltb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpjcfyp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwschqen.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaitvjz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bddsaxei.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgjpasi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmvvkfk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2joiiducj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2crgfuuxs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrssknm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaqjjhf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxinjra.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yayetlml.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2boocdcsp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkpqfny.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlpeesy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hojzbyrx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdmjcew.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnivlol.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2spjxjejj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfzpjud.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvvbuct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whmewoxh.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fazetdwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abzoyzzp.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2athxhqzj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2euhezhws.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klayyxsa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqccjeig.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwypsxrm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeinrrql.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeanaklo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2coazgjfu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gipgvjqt.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxduql.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nftapkvn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdtyfzi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vigplesv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowjtwmt.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkzrpwh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2blaqphbr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2isiwjtlp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgenpkob.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pauxufhz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqbzdl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwddbuik.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awipdgoe.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxzabta.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhlgiry.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zobnstbp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tprmzymk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2anpiwccm.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhulhtc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbunsqdt.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyljfgt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzysmxpa.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2agnmtrla.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dikjrnhx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cximqawf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hknroyyd.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrljbvr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2enhyzxde.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2phbtneel.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrocqjht.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwxdfsh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2avfckkmw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyvtsin.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aouwuvpv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aplkugtd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqzvrtg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpsuwza.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wexpmxee.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aypzldko.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqspggs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfavplv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2erxllmus.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mztzveag.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijooixei.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mptrjaoo.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvksrdk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmpukhv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrsbouu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglklyva.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2krzoprkj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgjygwt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfwepyo.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvveslr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvgszq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgewkvi.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaslmnkz.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2leeiqgnv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmqixuv.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2emovggiy.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgrfjub.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vadevala.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwsrfoo.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcuicdt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcgzzew.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlncjba.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmdybww.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjvyvyv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkplcfb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2abwttnsi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhzonam.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uofkvhgh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjduvxh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2qaloidaw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2irvqdybx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmuhaau.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2etyynyfr.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lihhprsz.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgrlgbf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2abwlasry.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jivjjjzp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfcytpy.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ketlktku.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2seppfbwz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdarkuey.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eehrvjfk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nejtqtdw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvqoozz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2xtixdqpd.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fdugxgot.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjpjrst.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsldjgqz.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgymvky.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhqwxrm.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hivbwxpf.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2niqtprta.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkahcbq.html


<!-- 参考信息 -->