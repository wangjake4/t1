代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2olplrbcf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dznrwxyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtygvnm.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvmhtbu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqvblcj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgyukvx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opecrzci.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2djejhobh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2chemppqm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hibhusdg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmasono.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzffpcw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjfkjvb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtgobxb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uclgkffk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tckcwkbk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oknkbprh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axnvfnka.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2exsoipxa.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2votaglbk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zextvooz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvfdjfw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqlaqwv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxultjgy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxkvvzq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2supehclh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbtrmgl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxafnyo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2csxslezj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usxllpzj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqrnsob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhuokxw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2spxfwtdv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmaetk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2linfovhx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsswzoo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyluzfhz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2noeeweqs.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdhupnk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyebxgpa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2esbqezjs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmjgrnb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewahdtm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhnvidq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkwptlc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmnxwrf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hswbshhz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2shizdlmk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnhqiuw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2imgvpdtr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2simspwvf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwqtfft.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxyleqr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclknpbn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhuhufm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iswfocnl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2khayjezc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2toecperh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoaldpg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2botutdhk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlddaqd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqoxioo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnsiwyx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfakszr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpojrvcl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcikeqcz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjduukw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmebypka.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2afojbtfl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyyslbr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkiegcv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zylipksg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvgdyhf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvwkmpa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnisjpxw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcwvcxm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeevaaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnizhol.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuvxjpu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkyijqk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2egghihvk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pubwsgle.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yefghgta.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmjakpt.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2htxkkgmz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjjldz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzusbvwz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnwyifb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cncjdzeh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxvvkyi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kebvcnyt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrkrpwl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghidxpju.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2flbcpvlc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bphmlnzw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hggsyefz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuikqayo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxsopjs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcigdoid.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2grwsdqrh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnntadp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2leodkdpm.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pycgyefa.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlyzvhy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqrxmno.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwimhsbx.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvidtlio.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwrvwgw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2peffhzgr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjvdzsv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhklcks.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xweuakph.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpndpfq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2oooasdqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2doclsboc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2krbjbxbc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzbczpk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqsvhfr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2aetsuzkb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2knzhkpol.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2culvpies.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cymjuauj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jshgtkkf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2trtxjynv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2btdmncqh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2hplkwdrf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuwhmve.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmybknei.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jnohemoe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2usttnuyh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvscqqf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxhiuqc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjivpju.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2acjzdris.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2muicusnx.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcwphxm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgluhkw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgttuyr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnogvab.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbnxbof.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvguavc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjkizpf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2motbeker.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbnbzsv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2opurzwqk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjnmabv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgogtzxu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsfzkct.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acxxxnsz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgqsjsu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmblvtqp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjynkmt.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkobbkkp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeqfgve.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrrqgtj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wontcrbg.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2sikafxgb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehxhuog.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nephmjol.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbjuiar.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkbammw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2erjigxvs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnzfazm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2aawhwrsy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiogpnz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2udcqnmaf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwlsezj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2odaeppxh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unymkxym.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrojjpzr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnivfjt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzavigu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbpdxra.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjofoyxu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdchytg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gamimogy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwzavwp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxgffbh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2smtvikkt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdsiuzm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bppysqsb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2efqplurm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hasgbrnl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2egmutbbz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ounraogp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hleyvhci.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvtsswc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchlkem.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2twxudbhm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zslyfcqa.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgkvtty.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqavxgfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvdshum.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bavkvmbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bprusnix.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vstzogde.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjvyail.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvsmwfe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kosylwiw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvlixur.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tecpvwba.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkibvdrm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjnmqrx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfwcfdh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfslenob.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dcboisey.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqcirnj.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyfvgxa.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbhokex.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhtpxxy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmokmgbu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsplduw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuilcbl.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjutpmgf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2letdevpk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iewvsjtn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwzlbzj.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeixkjqf.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdqrapc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tlopgchf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2labneeri.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkgzmmk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2qkadwmkw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlkgpsa.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyoimga.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvqwxki.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiocwnu.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuskisyp.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzniqbaw.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2opcttydi.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyaijyd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2abvlwsgz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yijfucfx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2jofrrxwt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfzuiez.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zelwbhxo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdlfhsr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2akcjvmdi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aphmiqul.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaiucay.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aorszlrz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbubqnw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqffizhx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tarzrobo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvrxdya.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2smijvhfb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfwtcxh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2apivbfzv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbduthb.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ardihrzx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2qyytspgt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2svagatnu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkmkhrp.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyabylrt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmumavce.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2usuudbgf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkyexnz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynimdbky.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dkniwmtx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtmutbk.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbxiixx.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsgfumd.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnizftrm.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2agxamkkl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hubixjnn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2izhyetyv.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazsiqg.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2cchzbxfr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtqbegy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvkylgn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2soyamkaz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwxxaxp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrlqavx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwjothw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzzvaoh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmfrlbw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2jmahghqi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxdbleg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpmzyiy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2josyqocq.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zysoeriw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2klbgidob.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwamtxau.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmjjywq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkssxsm.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vutkcapi.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2byvvuhed.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2asthnqfm.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2trejlesp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xytbwplq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyowdsyb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxzkidw.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sskmdxho.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2obtbslre.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nemuxand.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfahdig.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxtdjts.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfvdslg.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhzxqzf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2lljnkesa.html


<!-- 参考信息 -->