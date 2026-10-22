代发 wailian999

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azxoekbc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lroemwzp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2udyfvxhd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnjlabt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkctgkpw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwctjgt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxusqea.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gigixyfk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2iactlyyg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxckecbr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bolblwki.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfragqbt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutgnnix.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izzubaol.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrszgvq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fvafiupk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuefmvsu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsjqmfb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbibetvr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpopyhdg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuonkyf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sfksvvai.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwfwxnr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcxygqf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmscelt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2orktzdbt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjlpbpc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxdgqzk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvtbtgn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiiizqm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2apvksjpp.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmksfrk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zafvgycl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdzendy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlisiqvs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwygyhdr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mibstdrq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ythrcrlg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2onovlpek.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2usblypsk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wguptury.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtmfncd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwebvqgu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnrassb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeuilqf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zokieguj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbhoxov.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vglcawqm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzzjgjc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqmxqfk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyovutwb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2doeyqxst.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbhmzqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsyhanj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtedufqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcpsceo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdtzkkt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxybyyz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2grddwjrb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfmisqi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzonbxxz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrhhrcf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzxtnzx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2itdndtxd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2abcbbfxq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rworvwdf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvgnjxn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xnivpeut.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfnphmj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lihxgdkf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxszrxrd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkshxro.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnygyor.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mavmowwi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyajfuvm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbuiykq.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2frmaixjk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tblkryno.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2csouggez.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxryuxqg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqstcqx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbguvcpv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2skgqyfyf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbksresw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhoyotx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iboxgikf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkmjlap.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfuiger.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ududxttt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcdwgnf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoycxada.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqagalc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpdaofm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuudzky.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mconlgim.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqvlapp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnmxxxs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpfjfec.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndfugup.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvlsasm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjnymnd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqbcutz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uimdxikq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoobouv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbinayq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2amevvjjk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdsdzzd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uscoepui.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjmujrw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qifjhzxa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sitlikuo.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2wekzuion.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfebzuln.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuheksgd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjoowut.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jswcppzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2viqmlysi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqwholn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgoigkl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dikkpyyu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgoekjn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2aetutref.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfidhdt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmgzpcu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlifpsh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shgtzllb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2osgfonux.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnmtqbm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smtuohyq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfyisxl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkhhnqt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrhiuxd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2okobsbvn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gntiwste.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2crjvojmw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmzkkph.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzurcyg.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlkctar.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2brakpdjs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuinvcu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hpugvoxg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyqbsqx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2obikdgij.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2upfbzpzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsdpenu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuqbely.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdaaore.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmdpagd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2uxersbqy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2oidwkzmh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yayhyrle.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2crvvazno.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2keddklhy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcbecbt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbctbrx.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjqalae.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtalyzt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwhvoku.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2svyrcmxq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaxqdnb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuriwzw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmtvfik.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqkbbhd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzitlnss.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2czcpeuff.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhhfweu.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdukrrh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdviqtz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmiwfih.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2alkltzak.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jocrzucj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bibalptz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uixamwxc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcutrppc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qyezhbpe.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvydbmom.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmbspjb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmvahmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuogjag.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlqwosf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdyoyac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xplxvxpv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evrnrpwi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2jefuqdhe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvfwiga.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fzddikew.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxijwgur.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkybfte.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdjxsfa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmyqnzy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxytjel.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2luediazx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxdjuth.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhcbhvn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2njweinxu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsefjje.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjsiowm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxhdwty.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyguyarm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auhxilnj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgnmnqc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2owrutyow.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpquqrj.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfdhgbe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvhynud.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dceaymcb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mctrazsx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rngqcgqq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczyhupy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaphryp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycboafdh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfjskqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brqgcqbm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mjebwtez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsebnlv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2asqgoekx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zndtzkha.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2prguuumh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqleekxo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gixgckyf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwjyvu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sihglolx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2unysvfuj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwejvuvw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzowoyc.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzgkzjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njywghrl.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjshfapf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmmdfyl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2igirlljb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuyerif.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdfmss.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlskqcq.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqlmwrk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2stwdlqfb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydysevhd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjcmtrl.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahynmdrq.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcdlrjm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tniybnwx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsupaltd.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvrywhh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbroada.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuzaqte.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxgtpal.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrqqzhy.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cijfnoia.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfluepqe.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oieorqof.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdzsgpg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtjwwek.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiykwll.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxxcdkv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvkawvj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oouykxkv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gavfblnx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zulhkwnl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgafxode.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eleudtyh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dojxgspc.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdojfjcc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2biwscopp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lajzxgoe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2enkwelab.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqctkpxa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvjtgbr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwhjlml.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibutcvnn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqopbnme.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfhviwe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtjcxwf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cchkeojs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yunfqqhw.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsfylmo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bajpqgnr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyejaayi.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoreamv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2asjfeiqh.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrfmaom.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjpdgau.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2thmpwgin.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntccbsua.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mehotpoj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2imnrsnxz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2amahqzes.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgyebmm.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxstddp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjbuelw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kodropfa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrijvbdd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuckgvvw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnekuza.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvggukpx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqfaiwa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2coweiuwy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsrslai.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfqwiwq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyxdaec.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcufyfwq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rledmsro.html


<!-- 参考信息 -->