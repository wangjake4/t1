代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xffhzlfz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgmcdvw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgzepgf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cnedyege.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkfktin.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahqosij.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoqkdwd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2esdxeehx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uinbovyq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zituvaue.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgykfvn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeoqtqs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pafmifdw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvbeceu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgzsgqh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2apozcfdv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wstdsywg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npdtkbol.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sejejifr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcogqmif.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2glqzvmwq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzgzqvv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqjpxne.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdkyzxl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgygsyo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cgomaxox.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhjmsdu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2parxwwai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iodriakj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgrjqnx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2upcufxwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qabeznoz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jajkdzyh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwswcdq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2npxzkukc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2eibspxjj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyocmxao.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fofjqoon.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yskfbdjp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wftulfmb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmcgmcs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfhuuvs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zynreauc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksahbmgh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqepvvk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ftibbxdo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjmbgzw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2asqliumw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsocszr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwneoxyc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyniyoqo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyispfcd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cudxhncm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2somcbuee.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxaeaj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eufuwdcx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iolzmura.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rolluomv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpufvqi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atdjcujf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2okpedezu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrlqlvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2umujntuz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2onveuogu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwuywmi.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkwauhf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpmeyko.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oktybeco.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvpmlft.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdyqjqg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwizgqh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vulrkcsd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vasnbmxv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edsydpmc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqolxpz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnbcngq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2guogkxnt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzebrkct.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxwpwkz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpmbqnr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmreboex.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbyfjhm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefthito.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwagsrn.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgkdgmh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoievvhw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drbztzqx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqimympv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2okhczdrn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzxkrmb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvdnqkb.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2yjallswa.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxhrdmo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjukvir.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljezfupj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fciquteb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpekvnz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgfeszq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qelwnxfq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ofziqans.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxndbrq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2queqtqtz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwehsocy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjjzfse.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mimwixmz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvecprov.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbanidxe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtpamuu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zocavhzv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzmvmwb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2toplekpp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtsshuz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bycgkpac.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ablzfypr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdokgmzu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwzfllf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbodcamj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oxywispa.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mcegpysg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vizytnst.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zimpmiqu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcgmvri.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiyytqw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtxgjwq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2siwimkfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpxcvww.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xahbsmod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhykayue.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2uehviaek.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbdpzgi.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoivjibb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xagpbnhu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkugdqe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqsomsz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvqpzsu.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwnafec.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsarthj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jssmjhzc.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rznohhlt.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltvggx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdzyjno.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avyjufyl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwovhjs.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzebvfcz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktarikc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogfyzjl.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbangspp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2kavdknjx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnvpyld.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuyppnj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtyqusm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2nigwqcwd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxwqsr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpevkrom.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2czfizaqs.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbyntfy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qpubhmzs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmoubnd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqzafev.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2imubeqds.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sptjvoyr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnybrkp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtqzfzl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtalguf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxurphz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fysslruh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2opivrawj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2evimqrel.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuikaii.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbmbyyc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggioqxcn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjxqxzp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovizcant.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2upunxwvi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2medancby.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvzagle.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2okpqebcl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgywtfu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljejttze.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhubypsi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2pytoodzs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zakmjiex.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwywuobx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wghzdyuz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjjoxfh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgnruth.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdokzlp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqxount.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsizxxgv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfaafsw.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjyqcli.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzehhhuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udimxhyc.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2frtrsxei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hymefnbg.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ciabbial.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2uhucjeji.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjovnlh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbzdtud.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cegqyyzc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbihtnk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpsbwlz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2irduramt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpagtyt.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnreiqg.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsopkir.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyrweec.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2krfbjwpe.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2efdptatz.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvmcglq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ornizkxv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2symytehg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlfbuth.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqheamwq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oaakqwjo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2celuznbq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivkqvda.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlbtxmi.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwadjzh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhubwtp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyfeqay.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jecpiadl.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2iatbewlp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmlvrwu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2akubxhun.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2einbiwls.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2frxwkajw.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgysclln.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsiqjtc.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vujwzkku.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2quitxnrl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qzosurmz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtikarlw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfjbdku.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqllblgw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vitvpfwy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqbgpuu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2thvttznu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2itvccfqw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlznhnmp.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpsyimy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvnodvt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqwsrrm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oetceind.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqotdlqv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlrksgu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvphslwt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2swgywepn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2epialnmt.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpvnpwm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rskmzdyh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyqbxhw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdrwunf.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jckiapug.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnepeps.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xurgzmji.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2blsctphu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2khxgdiyk.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzxlxxv.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2psvuylit.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrcohqc.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2buphjpcv.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvlgthl.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxdjoel.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmrpqpw.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2srmbedqc.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvghcuqa.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqabacu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyacmwme.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhulwr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgtqjel.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcffbcrx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwttnwkx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzuwpvc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbdirhl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrujleh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2kawpkjxo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgeppvj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvcstmi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2icedbgwe.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipntyvmj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjrtrqg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2oclkremq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnmxyjn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2zauoecez.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvgqphf.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vipbyplg.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqaaajw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hurjvbip.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2akefynyr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrpkozy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2caqewpht.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mstkrofh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nysnuzjm.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkxhexy.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cslzaoyd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvlvgjl.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmtftku.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wynvrmjc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2prxnyety.html


<!-- 参考信息 -->