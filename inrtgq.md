代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqpddx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkegelp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2scjpwlbm.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyydwum.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ertdttwg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxsoswi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwyudip.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsrqnfl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2eogbzlmf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeasadzr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2upyqrghk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjgqini.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqegexg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2asedcums.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bieaexwg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrgvmha.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnwndjr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrbcjdg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2myaehvws.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yktaasvd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzchowew.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2prcdadcf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpjmakq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2usqmzxxp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuasfgbv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyqrrbz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaeeqak.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnczvpdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshaktbx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhectpse.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2clebwkcz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyznnke.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqfnbfn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhmqaaj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtoralq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwbzzqm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shulntef.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2esjliyqn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qusoyfzc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlwtles.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkgkcyh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxydegtt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2imqjghad.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bokkbanx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vytruvbh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2suyjcgqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2djrkgklh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwqmtyh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqysrni.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjdlpfp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnqxvnp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gasxqvvi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdexccj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpayubl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjrgnej.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cahbcolu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqabpqb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqteykc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxydlkn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwszkbv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cksahtek.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydgqehd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rntbxvnc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukjudmh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2guubkdkp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxwqvos.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2owimolsf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aumnfwnt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmffxdry.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbdpypl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpexeeb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxcxde.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnrevur.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiwrcom.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaqjweh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2auflvtiq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2daalsnoe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwnphjo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmohiotz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqnyiry.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbblxqkr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkzsbou.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qttkrbzs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iooqkbux.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2slbdetrz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfngdbus.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oymlsvzn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eswuarey.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jajacclc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2seleftjk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2prhbyynj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2poyvfhhi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfazftg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2yodlbuim.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqrfvqy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvcuayq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpntopk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvepesfb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2oejdtgnx.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnmnfbo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qytyjbgt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrsbvmp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qivamwlp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hybllczg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfebthtc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ondphyxa.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwzgoet.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywucglit.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2robqywzv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zcybeutw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2isdirttj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbunfcn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2awchsymk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhamykg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtzxpwy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nroyizte.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydublatt.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdenjhd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2grefvrvr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtgopqg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpsojwv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktcokxj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoswjzg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gingrtzy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiytimf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuygewe.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2miypmqpl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2afyiomox.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2cauehxoj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqkubpl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpinucyp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aypvlgri.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqlvxna.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aksxcdvj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2koejucdf.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2opkosjbd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfovfct.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbjbogu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdlccyb.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbcpzvr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgenywg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdowfpmt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzicxrbs.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoolsrid.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfbynvk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkqktay.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvihqow.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjqcxja.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lazzbhzi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2capoxgoj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgmljsb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lihhkqbv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprgnmhh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrahaofe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbqgtlf.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpzqnjh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2efojyvqg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2spaeravp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2macogbyl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgotcsm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjslqnn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vriacplm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jirehyhj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2eihkonza.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsvujaw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpzbskh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjodhncr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnepzqcj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrenktu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmcfnjc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsedciuc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgmlxov.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2icydqxst.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgemvsnj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvwllqi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyzodme.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2butlfxpp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzvhfgj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgbzjjg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcwceol.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbfiezx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiichfk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgphewxq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iptxnbcd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgrtsps.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdkltty.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkussje.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2efuefhol.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2umczzewr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jepvbwst.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvelcnw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnbxbuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrnolga.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xcreoeci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynncfhph.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpavyxbs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2dgucsdxw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qysprnlb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvqfbnn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kendwcif.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjbmteh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfzbosf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2suuwbctf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbctkzb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stscxqsf.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2irmzfarq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzpptkf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucqulkw.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcvnnfg.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqmmlpn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhusnwb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxfrjjf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpisprxo.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuqyojk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cglghbbl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjrcuul.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzipxluq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztfqwpl.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcewalb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzzriio.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gaieauqf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssudgryj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2edqwrvjk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2exnymxbh.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2uosckndr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mntazzrm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjbmnjm.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fteuwjmz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmbosql.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2suzrumwd.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgvjazn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2imhdfysy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hghujmwa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jilbxiac.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnoejub.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqdhroo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2csjpccic.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fimajydp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcsjjsy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtrgfgy.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ooutgccm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icvyipjf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgqncky.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdwxnpx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uidlemhr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpskxft.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgyjlcv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdwxwbj.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbixxbe.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bowvqcoj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2dexnaxex.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuzxzxw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbqzxzx.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhbwqyt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cktrbzws.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nktxjcxz.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkxfcji.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgveckt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cghnzdaf.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlrqsnb.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2grjkcair.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvszhvyg.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2crqvvnxe.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxoswdh.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwiecei.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlfotz.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2soxcohtk.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2xccfmnlh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvwfscy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyvkfha.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhlzulk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vziwnoca.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijitgkvt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzhrilu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jflbbnof.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhtsbes.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2elrfmyqj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyfcyml.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2umrqowmt.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2siofzfxe.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxybfqvz.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbiyrbk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nztmywcf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmtcdoj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2bcybzxoz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twpavbot.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ulploeel.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmnfpmh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiecyqr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrstbgy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bulcrtji.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjbzooa.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uopzkdvm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jztwzhtt.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuezrqg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqthtem.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2celjvfow.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmggtrx.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yugqvzah.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnshbzd.html


<!-- 参考信息 -->