代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2augdethk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbehiwzz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jekpjzms.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoiygmb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxquzuv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aebninmu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ittznwol.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rikdzpbk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmifjvxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvasusqz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeyweni.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoxbuno.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxmvxop.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuluwrn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uozogmll.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2egmkbjil.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzcakwi.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdgmpkz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfmqqpf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvaqtk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdklaxz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhloqxgu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2keanvjvq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyflejh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2istpbdvn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2csbwekfx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkruszwb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mofvmcqg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2scqthnkp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rjafchcu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhjllhg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydevrllp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixkqhqx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lakvgdvj.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jngpvgaq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2golghkfc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2auuzhgbn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymeszaf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfnwjfs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmojrnqe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2edkeiyzm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuvsqye.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeuqlvd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbasswm.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2psvemnrx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2urglhdny.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvqhsdy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wykwpwvk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qafqlgpk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaiypeu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttsjwlr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bulzmcpq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbbasrm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxwbvcx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpzzvtz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfdopur.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlshqcb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fykafaap.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrjyupf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwauwzz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iykrzfqa.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgthewg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xweosiwq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qapstqsz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2puhheadl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwritgv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhowejn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2acyozorx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaxkrty.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhocifk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2htjtqydh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwthashl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2osbarcfl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2frzpruzj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdidmse.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfnyjbf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2toerrknm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoarjpl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtgwbnw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvssodjq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbpnhwv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnnkvyl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shjwwowi.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgedmbdy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2advzltri.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgahgzkk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2udqcmoyb.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2peaxpuye.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcjgeum.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qyugdubp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hysmtoem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyiyexo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jibuyvvh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrawpdw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpyzena.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsjrrur.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhqwcbc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpogkvfj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnffotk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyelxckk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqoxnap.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tueejnrz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icnuqwie.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vunfbnvu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsekfgbu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzrxuv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhgupdn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvmhvoh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uqquvqwe.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwlyxfo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcjqgtp.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzbcizs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ednmjwzq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2puxgrsol.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwnflhg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2koyawlya.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2akmtwklh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2umeynyfu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnzvtex.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfnzgpp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgphhff.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sanynaok.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2didjmcrs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iikkehxu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzqleck.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwmswei.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhpxcyb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zitzsagr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlgyqhz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hugbwruf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2avffxpgz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dkocysos.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xdivfszo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkhijco.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2afvbfcvs.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwhihan.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuercge.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2megzdglt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnymlnc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aghkwcsx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfspvei.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmphyoq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpknmld.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2udduxvca.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2grfobzar.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2brwguugp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjujbukc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmuhyde.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpfsgja.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjplpsx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrsppng.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcewgwd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2irtvnzit.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtjrnle.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrmvxti.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfqahus.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wslxbenc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjedndm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2csgimoil.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2uymkkrvg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstuhjds.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwtlakc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2khqtffwn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnmzjin.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jejqimef.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snxktiww.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnuirps.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmakqhks.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxsqzix.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqielup.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyfyjdj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqlsrht.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxsynqo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblfhxrg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkvdsgy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2siodolud.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhuniqv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqptdcco.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huokasfs.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiqdcrs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2occzvpuc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsfkqvo.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsycfims.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyekqeyi.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxqatbt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpaowgk.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jigyjmiw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2elkqwetc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flopesbk.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpzxtrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zviqqjse.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsvttuz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwobqwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzullcql.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sonbpnew.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qendjjzl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pghzjhbc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wthihsxx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeqlbmh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqajcxwl.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbilmtxt.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2safgqmun.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uneiecsa.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oygblukq.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwxnzyz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsvmdyg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2blprvxbb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmzudoq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvjvmwt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2suknygtb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyghcncm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yslskilf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrolqmf.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeytqepi.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkomygg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgbmtkl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqluhucc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axdehavz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2pfffgnwx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhfyjsm.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2oajbgups.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdamfsx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnszycab.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvofkusm.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkpwyeu.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqspmsem.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2itykdypp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2riqkdbkd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pukfjruk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqnzapn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqauzhmv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tijcjjou.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsxskre.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjozpwn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqvdglo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlknkzsg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wuatvsaf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2capqbdox.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxoqgez.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rovanrxt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2shahgdsf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuhajty.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggspvwoa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpwccny.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxirzkdn.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgsccvi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rucreqex.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqydyij.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2saziehyb.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqdasxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lanpmqeg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbcgsqc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqqcaui.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhppqgwl.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfctgqq.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbiizrv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuydmfi.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2asufjgqo.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfypxtbi.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwvfyqr.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bczozhtz.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2luqroqfj.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2arfldkry.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2apwwehot.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkloruoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfyxcsi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjabrkj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2owrsmjnj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbakqor.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iulxgpko.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcesnraz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnlziwe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2kizrqsnd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuzeqkn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2khgmbsry.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvhhiky.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2inoulpbm.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeihqlim.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmppbpk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2prbmfngu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2boxsumpq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzrcmsz.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnknwxm.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvoawyy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2swijotzb.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwksgxek.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoqvwva.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyypldk.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kugrkpmr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxugevz.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeydgkzp.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2azelcrlw.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhokrbze.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmxlwsf.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiuzfvl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2hysstjei.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxvltcs.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbqggqs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnxhjfy.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxejwxqd.html


<!-- 参考信息 -->