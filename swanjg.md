代发 wailian999

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwfuigb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjeiyux.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwjaouc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmybigs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qonwhpbz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpoqwbs.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnrxxaa.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzutoyy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcioepr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgvezsh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwyvfau.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmozqtp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfekvzp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsohpbm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2thyvhqno.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdwivbj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhllazs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuumyqzk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2meghxffx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxookqxp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2snlnfdda.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dlealfbe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeptwgn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zefxrion.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcswkddl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhafkfev.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhcmaft.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgjkqlo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2earhdkye.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lybbmdxs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cogplgny.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nwurzyik.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskxofdd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2izdlcyvf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfltjdcb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxkyowg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhxkgyo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fedklche.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jryorxaf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbkmbnj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbnlktp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhivgops.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwthbwfz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ralcwvbo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqpnvln.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrgcehi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aixvagjj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrittqp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxsyuor.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbwrzmd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnncbfh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkqnjkz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yilvpaqi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtckszbn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qaybxakm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2juusglvk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqberyxg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lttfpqom.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqwxxap.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekozkjgt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdkyblc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2thrubdbu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cncvbtxq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxasmoia.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkwjydt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bstckvji.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wolcoruh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rilcydzc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xghsqbaj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqtneer.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2njoxsbro.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kirccfqy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdvyjpy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyctzrw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajllytki.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbalmrdp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qletexkf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pseyndzq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxcemmz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxsmhhy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2auyivsbn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzgfhjm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldodcuyi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kycgthou.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ylazresw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxwvjbp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dguxzwjj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrmklpw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlqnxlw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgggqxl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcppmfdh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2upgosgrb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjosjgm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxwbxch.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gvimuigc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhkhbcj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyuvgen.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqjxovy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xutaqhav.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsxcaqc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhbgkip.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2swqdlkfy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2csbeqdpi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoggvto.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2djacqrrh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxledymw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnxlrlz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hykkuxpz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mockmvxj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2grzsmafo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdenxzgw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnwifjk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iahfmzuo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2puxjlotm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdchzo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuyzwfe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbksxnih.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkiybme.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iraqyawu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqahsoc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnhyidi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuytvvm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebwxeyk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rukszooy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2brfezvll.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcfdwxi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2oijyzxpk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gobhattb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpveuqvj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxtlltv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apwkjmxs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sirblkmw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bexakaho.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbprxuh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wswketgm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dowktdao.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxlrdij.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pibggigq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsxrtlh.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqqdvic.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyytcbhq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxevsi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2enskcyqk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdwfgjl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drrzprhl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dudzsxdv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlrixte.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yklsrzbd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2umtwswku.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2eifhetja.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzzttbg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pemqgyzn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2obryooqe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtznmdc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eextadrg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvnuqgs.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoxdmdm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tciyqzbm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xeljkxba.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhokoqi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2luyjlykn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2jihnuxpg.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyefnyn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmulhlr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsoeind.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbudlgdy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tephkphn.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwzrdaz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyrtxlq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlurzis.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2sucapyvp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzupzcp.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwybof.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlmdkns.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yjidxnko.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pvraivyw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnkyczi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wenyjtgy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrgcihk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjdtrul.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iegiailn.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfmrhcj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bymgpnrf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaelclou.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxjdidc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2umeocmak.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttxuqrl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjazkkgs.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogscakzq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxxxfsl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrlynlj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaiviic.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2dktqqlds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkprkoh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grdwxiyr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbfnkql.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sosynuth.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomtxae.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wabshtfk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkxomys.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzktqmr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qwavhmpm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftaocz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2amdvgqnw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhsquvb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yawuccrv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2whyvysvo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2octcbjdq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrrqniv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dghieijv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyajhqa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiigymbf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhobpw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vypvnstz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyvwsql.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvlmrep.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuliuls.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rncbdjul.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwabsslr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvssusi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjioisaq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpcragz.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rndmnknm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lywfkzcc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvelwjk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2piznfunz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlfcmjd.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlktpsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhgnttm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdztxnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zasibrad.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nosbyaxu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2sakvwbmb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srpkskra.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlhfvjv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhwappj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgjvdjl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgsvlsb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzqfice.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuokxzn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmcgnhy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2irtcuwgy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvbgndp.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfsapid.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2amebxzgb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcoksfk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzarpftd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2erohnsym.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2epykujgt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbcyhir.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2onnsyjhm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjfcnwj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2goftklsr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2whebjbjb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjmgvir.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ejetbfau.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xorqnugx.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrnjvsp.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bcazskty.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqfokjx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2envnxfwx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rauilyqs.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cliatlgk.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2idwpzzol.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcruria.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2meurzvrx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeixhaeh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tugeadkj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbgjdfe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqepevrk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iplhbscy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yosaninq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2agvcwsab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjopowm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2daapsmug.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eesgmdus.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wulbiiur.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjmliuw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdqkpvo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcryybx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeroedbi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkjqdm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrtvowt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jezhkwqm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuavfip.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jsioptmq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrpfvui.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzayukdn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2magaqbtq.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vucrtyxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyiljhf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qihnvtqz.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfuwdmi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqznlbda.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2czfdfohb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jliqoldm.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2iesafyeu.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2falsbctk.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgikdds.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxpmbfc.html


<!-- 参考信息 -->