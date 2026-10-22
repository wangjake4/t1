代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2diofifdu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpuwkhg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwaeqmc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxygahn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inacaotu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizjooms.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrjcshs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfywercd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjqynpi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmseznt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmuvgeh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2clinzpur.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vurwugjc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbxtlvw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juotlyps.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzbuyee.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwvidic.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcxshzl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2clmarvgp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoryqix.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrksdrq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pzilsttj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hynnmsgj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpteorm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuwfhuo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fucxgggr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqphdwhd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifldybmj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnzefsc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsxzddq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxkigkg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fldfwdrn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcokgatv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvitqeq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rskrwazi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzkaect.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmjaoim.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdjgbsh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rupviexl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hacipgan.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrkkgdg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hseenojd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgesvwb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxbntwj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbwcaya.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qavqilzo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2znjcgado.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcgfggp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxicyvnj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpeisps.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpbejvf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkgwukx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnnrjuc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtsohqi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2naodkfso.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvwrhws.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrabbkn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bhweswbb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrzaelt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txeuoweq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpzlatx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkowwij.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqegmnmw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mggxldek.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2irqpirmp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nibepyxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpehfxa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzyqztf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2crijrjzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmlddem.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sagcfeiq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixowvimg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2kjahcvyw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etqzcfxq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tknkyhjq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gboyxfjv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlkoern.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbbbzjs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lokqttdg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jckckdrk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzutclm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuoevea.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgwtuxn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2maozjruc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxuttgq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjakyxfo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaaxyxs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvykkxh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqerfmqi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vddodiid.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cldrtucx.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyujmji.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgukeypw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2fctgumuq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqkript.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyznqvte.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdggewyu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoopbbik.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxfliyh.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2bzipdnse.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfoqjsc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsvsvuy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqsrrer.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eymjyoia.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcodqcph.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulglchsb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jycdrbfd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlsprbi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffgsqe.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqvkzih.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeipgql.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqhiriw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbuwgi.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2imjhjilf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2azezbyng.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsurabh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlonsutf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlcoxkg.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2melciyjx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2geufgcci.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sflfwhgg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbeabhm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaomhak.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2igdqudsv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmeyhsp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2etzcbtdd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfsotek.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlftllxz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nsesiyna.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxeiufu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hglkhnbf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqswqmim.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvehnsi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvihyne.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2glclnvwz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtfudyb.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2efruljan.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdmkdkx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgwovfh.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dwodtozu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqpzxkc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjqiscc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffawlixu.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnpysnr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmizgwp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgugfmjn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2odoyrnmj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nftibfhy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdgbvuh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qoioweri.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsezcoll.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gttkbyyy.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbytpsp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcvwbzq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2efqyspkn.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoqavqu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnrqbkx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrabdls.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2etfpuncs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqzazes.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2agoravdn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiweqmkr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yolhralw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2crkdooxh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2roooiqwp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2umvlhppn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhujrdy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgdaglz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrgaljh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jobvfmqm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtyfuqz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bisqjdui.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfisyhxp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrpdmfu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvuxhht.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdallkoo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kctrwvgu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjcmtm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvocrpvb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscmkrq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2czihnuyi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuqemgt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axsdylzb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mciqgodu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrlxxha.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyttwibl.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwjamwt.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2voszfebk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2soemiyiq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlusjpw.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrdrfnp.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2koegerqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrfilqv.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlrmroo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thfjwtgt.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfcrykk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzctosj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2opitarfe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyifwaf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2whwvdjrx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqudyehb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fokimsya.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfajyxp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pipfrmtw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjsqwye.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhwhbkd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaqprkr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfilzge.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2csrutdnr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2largxqfa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgcqxxz.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vplwvqxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoapqye.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgsqcyd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2agptuhlv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ennnoalq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2idwzstnu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayablow.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdjpdan.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rmabcdot.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpogvec.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yittyrzf.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2zljaryoi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdxbvwq.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2adywrova.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nluitmag.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcftfzt.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eutfdptq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdtstjj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbxieor.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2twzapfss.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ahakwvpq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2noqsmlkt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjipqhch.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykulyndq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsropcir.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhhnvgf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzsrrdy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2amxgfnbn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mynknkam.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkkibds.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2equgmtns.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdbijxj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjdkkth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwffabp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbsaony.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoktzun.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2etluxtxk.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiirnjy.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpmzdet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwiejay.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjjugmt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyetxse.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyppyerf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2avxrpwak.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wakpnlqg.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2anhxosoy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyelqpnc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaxkhjj.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdgjol.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qokorhxk.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mafbilcq.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2licmfejk.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrtpdud.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtuoikl.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbufbggc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwemzbtp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhxcoqh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odxwnsdh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiihdjv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrynuhj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2haszrrbj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqahjxh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjufdakf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaypkqo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2opkyetgs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjxtomg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2adndqyhr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmecaeht.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbxonzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxutffe.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkewulm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfrtcdg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdnsxza.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2apcvmdbg.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdujxxp.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewzmfu.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcatvlh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyakhpr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbudbffx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uztadjkj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rjieblno.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vzprytkg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeacyrg.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmybghdf.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2giwgaplj.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjpyptp.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zflmbrvk.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2upfnqucm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2veiuplht.html


<!-- 参考信息 -->