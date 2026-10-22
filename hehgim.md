代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsudarvg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2biiryomv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ieitmabq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eklslvfp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpvttfx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiivttu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2myohpvpi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2txyhvsnm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2setfgsnm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmljfxye.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezccaauv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpyvpqm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtppifld.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrpvxuc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2caxfffzl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqxzpca.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2abyrrxic.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2imxtvgbn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuhnyib.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvgxhni.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzjgmiv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhurttml.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbkarpt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdqnwtl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2huixcynf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxxrkwj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2lddkvknd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yotijihx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vktlqedt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dnazoqgm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfowmjy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2efqiiujy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlqpjik.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnsgnwf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmblbdf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdjbpns.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwzwajq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvinxyqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2brkpampe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpxmxiv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjjxrt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wopfvnlh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eivpnpvv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ztezdhcb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kcntsjtp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcngzdtf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyryeknk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbngjl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2irkppzue.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iidsceas.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdpebao.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2srhzuobt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjodmnry.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxuldpl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uxffpqrg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbxahxu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxltlgb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqmkfax.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiymeog.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpbkxtr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgqdpgw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aihdilgu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2eobpcqvc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsqixeu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtlygew.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uynrficq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdymhym.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsljwjv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuwebdr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlzbplu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzhbhtw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzpfujd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mutgejbp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2inuydamo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2auvbhcub.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhftnfs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2posxpamt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrqpobl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lygulbpa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okrykugd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bftdzgum.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcovuje.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2klyuwuuh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwhicq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdkzhki.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdffumsh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zonargxy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2oiplonfr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbscxktx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2eluhxqri.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svuzmqon.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bitpfnyt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqqqxeu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wehflybe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrknxskb.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxrgcku.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgverpr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdmyqod.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfpwcyq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjzkams.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2edwettyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2entnwnbr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qribnadx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxbfxkh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyppdwm.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qsretrff.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxpainh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2snjibrpg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wkexledk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2pemyzgdk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglahqbh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2amusgqoj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wohxthqj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kufdnkyh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2anxcscbj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfucuzh.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zncgcdgk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cntwgefy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sojwmgnv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyjwtwn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2padunyli.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxyiojo.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqvofp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmozcfn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2endmhfod.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzubyku.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhnsuvd.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqltytxv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvgdzau.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jslyatle.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2phtdygte.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaezmxl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kvayiwwm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqprsep.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkqszca.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bsezwnvp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnpjgvh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoatsayp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2suldfwuy.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrscqm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgxutuy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikumbdxe.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxnllzp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zezlbfvp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpwjanw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgtbugk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqbwepo.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2skvrqler.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsstsbl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iubwyexr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnehotd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoklrap.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2aflwrail.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxwbocg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtltnqqh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhkvmn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2urmbkrpt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcoevbl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeoshbh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpoltkz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwyyqtd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhbrusk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2atxtjauj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2guelrzsa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwnyezk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xozrnywt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjspogat.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjezdvi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uysdpxnd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuurojw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyqqjre.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gofdydxa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrermbi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxcmvdk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiujmhcf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mssqqbrh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2clvdiqns.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsddrey.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwysmcap.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcotaepl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wehowfrn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwuomnm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxypokvh.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxcbugr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussgncvy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vixtfjhh.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuofrgz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfajqhhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eprwldix.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hluqkadn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxpufuf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjhcmja.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgtfqza.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuunepx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaeyibd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuywrtj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eokrgddv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpduvwf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2omqijxpr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2anqfedoj.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqafyhy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhodbtf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrzgurm.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbayqmi.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sneaynrn.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfrtrsr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikcsedd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ulssfltm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvipiof.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpvsiuv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hocdtdcd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlccssh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2neurvifv.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlgnknv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybweflom.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbgaeks.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2voyooohr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkdmbdu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrikklw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejxeqmw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnylije.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2stapgdtp.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiwtxsz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmowjajf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhvujkk.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnuurrx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyrzmwi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2taakdydp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rehgvabq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfyzbqa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwigrgl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeuzmqr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeimriu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkjpubb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyguiyl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vegbcivm.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlkngvz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chctqiju.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbnpsif.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsshveby.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqavbhhd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxmvbl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmechlb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpkqkwf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2maersksz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkqxya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2dujesmul.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgefnda.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfushylh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2papgsfiv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcemitr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzakvpd.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuqxsxi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrxasht.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2otgfzbbu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgmhwat.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfzkhtq.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpbhsub.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iihbagcw.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbaukay.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghezxlla.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cekkpfrh.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbazpqqu.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rlisdlia.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cazeagvo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oknykhho.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2espjiylv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gefibyqq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sysfdrqd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbraoti.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuxsmnq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzgxvzb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsvrrok.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eafmmcfu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvhkcet.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzijvihh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpvnejw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxgrpsi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzphzhj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkufutnq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwqcfp.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfowfqxi.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oosrevcl.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqnruea.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxbmwwx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwacdby.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2avujkgol.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsrbirt.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sulgkkyh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhjmcxy.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2remxfchy.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2exmykhvf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2gicxnkdz.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqqxbum.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfutcto.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvpzzea.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2prxqruta.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2whzmgdgi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2klqzdyrb.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btfyxxkj.html


<!-- 参考信息 -->