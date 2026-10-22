代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmqhzbu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pemvkmdm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2untroimy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfmefkv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fubwuuih.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmltetiz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sspnqtiq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzatqyu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhvuzyt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrsvsoi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oriwhhma.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirzheww.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rxibuuxv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbcfrae.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2knqmwurc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wszcnqfl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvyasec.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omthadoo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2anatghme.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwququpy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzgbgfr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxhgrjw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvleumjb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvuudyb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dylgqutr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wooxaybn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmujoxrj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoghdcz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpraxok.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjldfqk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yosjvcym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvykcyvq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjwbecd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwphhry.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2degfeede.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2akxmnupz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uprwkhzt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xxitrqst.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfixntu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzonxhdv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhybpin.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwwqjrp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2irxwldnc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkrbytw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqinhbw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfygual.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqketkcv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zyflqptv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eafroock.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvdnebx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoefvpv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2szpybtio.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lltbkeyg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2amuuhjsa.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqahtgxy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gudifwtf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2htsknrwm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlfdkfx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlbkpup.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicrsrkr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiucxbi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrvxkpo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkaovka.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uomzeswr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hghokiky.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqwilyh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdoziaz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhivbasj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dosefaka.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bigibtqp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmzljln.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eujsbwix.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2irtkxyds.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2absypgyo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqibjlxm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwygpiu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rilqlmvm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodpzgxh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptbxqp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvivxghm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkgxipn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2znfckzvj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkxxcua.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhbotyl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlaakkc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdwrgul.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvzdsbc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvtlflb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgqhlax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmqskhk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkqagog.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dccumtlk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiehlev.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2frjmtyho.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgipguld.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdqmvxi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjrywnx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbflqrwg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rexhrvaa.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ldztqljx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyabbaz.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfutsbls.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzglqto.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubooajwt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzwruou.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatelaja.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrmhwds.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bagthikn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsirwyr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2axelsguf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnecqdzi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeqmrae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qptoynwl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2uedfaafg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkjmslq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqjvqlr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtahvnnk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqeprma.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjfdyvs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hncvclca.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzrxkrq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eclmnqye.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhhwjax.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wcymmpwr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnqyyrc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2okcjifwa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmuicwq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpzreey.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuokdvn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgctxxhw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyijqkqy.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaoagwv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uooforpv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2whhnpteg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjgjgbz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2otkjukav.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2taumeapf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzqjmin.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2epwqqwcl.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpkmjkq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2birwsdxm.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2laedrqal.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nifpreuk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trevrybt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdoofke.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmlsmiy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihachheb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgjgjxk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzbrtnp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgaxmps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjslhigt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtmvzpl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2topynrrv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ignuajaq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtmuxwg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlagapu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2whfbglpf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuotcgzy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwoqmxo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaxjgdi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2friasstc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2whduqweu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbypqbd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwymthc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaesdplw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrarpym.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdyxrsb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wukyynyh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoiemof.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwjounl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkqrhao.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjlhdhv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2smhplkbg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozelxoql.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2izegczxc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbykstg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bousyvfo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2meymnjxs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxczpa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqtqlbg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2aowwoaqi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfcfchs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvydtxi.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tidejpae.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtjkadc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uforiugc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gexxwyvx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dquojmja.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzbyrxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ponuuuhp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwnwmiq.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkcltdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhcnxdb.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jloadiut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcexniw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnjiffw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2srgkzrny.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofabljyj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmybswpa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2topapweg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjciipq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqbdhfy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2vsetqnab.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwfmyss.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oelpxted.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqshxk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeedjzo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eupctbuy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhhaolc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdmxcmn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kivhjszr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cfskxmah.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrskapjp.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsumjkec.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlaupiq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoupnad.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdahquu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2faysmqtm.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzjzqvp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2saoeascx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgbwbek.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxhxqid.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoiqkai.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrlnuyy.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2udderfdd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfefevz.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2txjhxnqv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjzzxsq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tttuotyi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzxjqjw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jajguonw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jfekolyr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rocdirpj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2szmrceiq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ickmiakx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgukhfak.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyppvkj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxhnvqv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pearuwra.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyythvh.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnshebw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppbrpnx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2haupfrpl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iepjslin.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuofgsdf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqheaygw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbdjcgu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmkvvru.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgbaptm.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnuudiw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ftckhzlc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2odapebtq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2igjbubbu.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdwiicg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbpisjj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2plpztoel.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2smmzaaqo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvgflft.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tikcvjwt.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkettzd.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyjksqu.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpwmliq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwyrjqj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkadedpk.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jluvpdqc.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpglggv.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2whlkldzz.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnxppkn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2recosjdj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchtxmuv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xojwugxs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbksrth.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbewgate.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2knfopmpk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fygytirz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yitwgxvr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2oypczuks.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkbpirt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2lplmujwo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jijcuqxh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsgxirr.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlwniwa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjyykwe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthjrihf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxntofgx.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sqekfnot.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfosbbn.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axwaaqwu.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqierfhs.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lihhifbj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfhfxuy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2bymmhokp.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ekegtrjl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtlwxgg.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfebbncm.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhpwzmn.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdxgfex.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqapbug.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axtdcsle.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2qymxdinn.html


<!-- 参考信息 -->