代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdarndk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oujsjtim.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvhkbql.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dugttese.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jntsmyxg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uunsonnn.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvxjbcf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjotrt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmqimvl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdzclct.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flfsdgcn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooygbxzc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiawdbq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xapklmjf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2eujgciqk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lywszjex.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2smosbrie.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwqcoha.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenxqltc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynohdcki.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qulcslar.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrdgmjn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpfogla.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjowgfo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2beldcjmh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fogfmjjx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2umrqkznu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmpajbh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vemwtsjx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzenzvt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnrtxdg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2eajfhtpv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzabgjo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wltgjxgr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gspwjtbo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmoxwis.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpykjwf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqaxygq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqfltfu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvocchx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmpevpk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kegimdcu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjqogbr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eehgyukq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2solxqsec.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzqnvss.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2csnwpbun.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mciguhbn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ranouffw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtazrdt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkcsvvt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cfauihsg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuamtrfj.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yirthihe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ievrrwzk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziruwjzc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2thfdzgzp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqakxbz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvkvsug.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnlpjyf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjhxutg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqdlwgk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2skadgbuo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhwagjx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaqgjqq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdykbmjb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rscpudon.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2imuuinot.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjzxwjh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmgjcgu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqjtone.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxggqksh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbvjssf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2srlrbjih.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaogyfwj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhactaq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuwbvih.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oiexwjof.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqirkqk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkekupcw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zzehkpub.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuzrgfz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbnuyif.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ituwjbjy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dprfxyig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vossuprl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dshlbxha.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzuahnz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvknlpqw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2fftmchml.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwewcykk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tihisjtm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvavfnqi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uufhtifm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2eijgcumt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rymhmxun.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjgrlyl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxretghi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptxmzl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vulfhhad.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sapsuqjx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrcnhhn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2afisocxy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvreitd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axvcjxlj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2culsscor.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgprpdk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlvygxj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2onpoavig.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhalddml.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2lltolcrz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfqtoxi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxecmaoc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eudrbmyp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2coluqykt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfyutak.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lstqrpcv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qspkxmkz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkijkypf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhrpmsy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvciykc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcrafyd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkciany.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2txsnxzlb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsxuzcd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiqpdgg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvubuag.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuenrux.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uchzxugd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdfjkzu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbfeyad.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2imfvqvkw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2irkwvykr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkiltls.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wggyqstk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmgulwg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nieuatbg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lriawdbh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2caxmddjg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhclbpi.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnjoipo.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgybfou.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbnsvyz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxzdafr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxjvwuh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bfumrltz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsotpvz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2esavjhgc.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqevmjpr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2grexgici.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnuxrdh.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrilebs.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2prtdphwz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvokizmu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2samtjxci.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojgtmjb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqacoidx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfarvhb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhtggqw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2owqxfyxp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2govafqzb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiszhdv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpldfhvd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aifrbnjs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmvlwdo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdnxdc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxibbzit.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlfttad.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwfaisz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2emabxwbx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrframo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpfdhjd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vytxnlvp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsrkmpj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodxvwl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwsdfol.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbmmadp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxgyboy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdserkce.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2exgrgwxp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgemvejs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdrollq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrgfjyd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaisojpe.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jilthafj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhjlqyr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sviywkwd.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2umfffrdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrocrcl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eifgjmnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygovvibj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzaskgb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2comqbsbx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sohnelmg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlavryud.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fydffrdj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqqmyqs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfvcvkd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgkakco.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqcudlh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvgpiym.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzdxguv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzbgwbf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyevsdd.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2meynifvh.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2udizdlfz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnhaidu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xclmwigi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjujpldj.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzenxieg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhcsoxe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvtuwjw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnppwxut.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bntfbula.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbohxox.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dunknevt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlkclqx.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qduwjglf.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2crvdyjai.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrihhlsn.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuppwjsp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hphiacbp.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhhylhf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxrcxqi.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoqkmvf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lexvrwmn.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrmnlef.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kjazfuuq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lowotkyg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2dowwfhoh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxolrpow.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeypgkyt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqdbakw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmtvpiu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkdgiaz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoedgebg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lggbjoil.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wapnmnsm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqowrsbr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2esljxnsz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2omrsujza.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwschxcf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqpgvmr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtgloqu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtzupud.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2phvitqdv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhnejjq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2irsqgova.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2veuzvtfe.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2codtxfeg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hclrddfo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjcofak.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2jodmeazg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoitezsw.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yttipumd.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmdatbl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdyardi.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnpelle.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmhacsl.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2njodfixn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsybvgmf.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsbgwtd.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzoxacv.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2delemlnf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uifnaddc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlhgudd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2newyronw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxkwoyf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2swvjdkka.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwvnxxm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yypayily.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2renimuld.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqbygzu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfoekyj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmbpqi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2survqqtb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkduiu.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgvxjhx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jccphxdb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyvknhr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2tixluxlu.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsljqyq.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqligvs.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oytdtxrw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwxhvtk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyjemuk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yixwmqag.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwggbfk.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hyssvjir.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnczbed.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiisktir.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxchewm.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkcsipa.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsgfhch.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcpfuni.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwortaae.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2upydevpy.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgumfaxd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyjotmt.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hlftdiho.html


<!-- 参考信息 -->