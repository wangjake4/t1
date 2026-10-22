代发 wailian999

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkpqumu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tfodrkim.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxojybsj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrulivr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2owlinyzk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnabveuc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbwfcet.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtzhcvv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxwhuic.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpcsxsp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsrdxhd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrcbeyt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhbmkxg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqdhxko.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwqnzlx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xelzbwdc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsywcaa.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2knldrkgu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yltmtohj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxapwbp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpltbdy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxtkyeq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lourhqwr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjgqfme.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpyngmm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnidbns.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdqmmjp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemejls.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaxkiun.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcubteb.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2emhimtrr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cochhslr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnejoosa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxbawkt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wditxcli.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbgtjsc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2okehesup.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2adrojgqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2khjibdgg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpfuwie.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmufdckq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aphbniqv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbpemhr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtajeltg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqqvjes.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kginpxgs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2olxhzvcm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfooebl.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjjzvhc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqyhibe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgjlmay.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtfvsmu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxmesxd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgiilfg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqccgali.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2erkubkup.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgidopyz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2juqedqfb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2joaoypex.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urtjyhrv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2npouqyco.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uglsodfh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzflfyo.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkknshm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhitvbs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tarovest.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnwerhz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2luowdezb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2imuquohn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcgeckt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2orpqrbvc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwweuyvm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzszmqqs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qfchkyjr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2trmkrwvy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnfmrfd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzdcmrb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgnkpll.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycajpxc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bljrhxio.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zipatbjy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaebfyu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchsnkg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wciqccga.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgropgq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfpqjkc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfjhtgg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2auzuzcpa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsmrsqz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2foujjqou.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfiakfn.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yydwfswh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yezzadet.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxdpkyj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wrybmysp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zummvmyh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthgjvqm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooodwudi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiserdg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2evlwcyth.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoebakl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2umiaotut.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcssruoz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pddevaih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrekrxi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2calethvb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfciqqqv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkothzrl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrmpgtt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkryajzr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyrzfnn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjscosmb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2timnraii.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgsyojh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvjjzli.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoungmus.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqtyhga.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxioad.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinrfwrh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjlardm.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmmnsjn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxdunzi.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebufwyju.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrqupru.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2peizqxir.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiogoan.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcpeuon.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnracoa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoimlec.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzqdiea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkpzyvs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2truknmpo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cssbpvmt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgbofcz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2enaouddl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaiadwt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzvfqji.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjyvtza.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dndgdhda.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuvnnhj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwidmppb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrzevhw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbporgis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbrqwqf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pturadrx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hutqhqcv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdwwlpi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oyviporf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrqwnvt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcjyldc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2iirmfhtc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nubixwos.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pblnoojn.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nggyfbxh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqtevss.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucudavch.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2chvhoegl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpvydak.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwmkohu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2uglnibsp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2noypzxrq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzkpese.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xweevxfv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfrbmqj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2avwcusmq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cziemlra.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcmqism.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfmodtu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzeuwin.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnpozgx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaslpht.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxvgqhr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqkekzq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2neviwvfw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxvaeui.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2iysghgbx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhbgmfo.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuldkya.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2seekotub.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlcswnf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2duzruvta.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzvfuwe.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxwctv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdnbdvk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfuhkdf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hivdhijs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bynyyuyq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwqvexc.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2spigxsub.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbmycnh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2apwcsqrb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqvzgsm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ougtjrqv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzxqkyy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwjbmqq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjzcajl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wetfehlo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2emthwlzq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrevvnk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcmqnjz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmibbqqk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yaamsaoh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuphxex.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oidhmgyc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2traaizef.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2glyhctmz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxrrizu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbfwnqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlgeaqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwbdccp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxcdzsk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqlgdua.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2elwqcmny.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapietlc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2trbqfdul.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxhoxwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2odcfvqks.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cslaerrf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvigfwl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzejdrz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyldvhhx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atdpimwo.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwqnvni.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqipgdx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfptrdk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcyxvlc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oofabpbk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvejdrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdtzgrh.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjegvymz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdtqamm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zulpiyme.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwepwlh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbiorwr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqciphvx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuewowi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nstbzlfd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvabwej.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jcovbvaf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lctcjztj.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlhafnq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkixfs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owikfywt.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckkcyzt.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aioczins.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjuixvq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgjrcjd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yarbmxiy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmeeeyx.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2znwhlybc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhksxlu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwncqcnk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrehzvwf.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuprxza.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqqqrqw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vicwrcxk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vsowfrzw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrccmqui.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2afghxmgs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzjtftn.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2grvsdeej.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ravfbrmv.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbfjwdd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsctsrax.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tskkpenw.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hywfsisc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpxxabc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvsluou.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqnjdso.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2rglepuxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyfhyvz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yawywapa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jotdggnh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugofasze.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvytgep.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgzgysj.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqakaeaf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eismupxm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuyoujp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhlzioj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfojslbd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhmlwrl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxzorvr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjafobdo.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyywunlo.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2psuexsrz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkwkzza.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzzhghm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhfely.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmbstqv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yptfsllp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjlagrh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2asrhughd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2narpwkeg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuskfts.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxlcbnt.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2qimcdqzy.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2owzucqac.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgbsptk.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dklywsuv.html


<!-- 参考信息 -->