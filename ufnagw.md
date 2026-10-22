代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpgxgoz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2medihsyt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uztbtydn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkvygmt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuxuomy.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwkxhq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtryorn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcmrkeo.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhdwcxu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmooxju.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2btgxyuya.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrkjjxx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2icilxndr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzvgudx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbnuldn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2snlaqzih.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xypxxraz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtfwfqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaxxjai.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrefxttt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2duuxbpjh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2meltvpav.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxccyko.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2liebmina.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxrfllu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvtlwmw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdayvydk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqezwkgu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgzahhs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pfivqtsp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdvnygu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kknkhenv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsneabst.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cfefqumz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxemtba.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvckqfwt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbdeoqv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxxkics.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2negwhqnk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabyblqy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ryblhwsq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mczlxbki.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2suubuqfh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2askjulea.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2krrsvulo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyklxcp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtvjvnm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fboakdms.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2chfjiqlv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlxcwpc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmywkfw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbbiklc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkukulo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2pfacxzrx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjxtiql.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2orknaxql.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpltkjo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2apwhvdvu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjbljzp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xigdcqpn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfwfzee.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyrwsag.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rudyxysm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vafmfhzg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2irhugsow.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvywxpe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgiyufh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2imoluypv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzcujpa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2esutjcye.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrvyodq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvehejz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfegeqv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jslojsac.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptibgniq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sieysiee.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sygihsqs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2twqyjbfh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzfjwst.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlftlwp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2maamccav.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzospkj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyjdjjk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrxrsxc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtqmykl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufykyndn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbytxpg.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ludcdqct.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwaueod.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2yquvktuz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pckqowcp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rswiijer.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2igmkbdzd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbhmifo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooycvmoo.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ytttnbby.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkpiihb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnudokx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrkdwfj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbjzdsd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dunziltz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2synhurac.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2quzgibme.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiizjrr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fscurdpq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2fckfrlia.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzgmdqa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gorjrbqh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ymanvxjg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dallbtxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwhklfr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwdcnek.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2suljowhk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcshteu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nqihjyfr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qluqhrrs.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhygmep.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olffgyce.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtdjrja.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2njdcbwsf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jygvtywn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2rohrbrwi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqpldrb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcuynex.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2khtnowqo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctptlncj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdojitma.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvtrtvr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwomuji.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2crqyabyo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvioffym.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaiprdg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2efikzfpe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmlqyic.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrxnpwu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wljrjstc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkztdcmu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyysrunb.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgylvred.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmljowj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xinszgne.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xecdwnsi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwvystw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2tafjwrrj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhjaggv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoumyqt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjkphlb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2suqpufnj.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2avodujyb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwgroay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2cnntuilm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkobgruz.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbmrujv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijehjxrd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pictcdzv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkqsldh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjdehut.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2awhfntvi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bitodgjf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nfviemhm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jibuzrma.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkaavpa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtqvcgh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oehebzku.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeflnvf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2erukmdgc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxrncsz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpvkcrf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcjjyoe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uodbasfu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fxodktul.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2goixonyt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnyynpe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqrkklk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpmmhzq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvmnqmu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtfdjgn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2viyqokei.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2piyyqyfx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkbkqlt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyausezo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yudqbtqh.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxvxwfk.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxupjkf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalgioeu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uehzkruj.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmkuivc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnyhlnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gojdmhip.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cschrzhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iocwiage.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2roofhhmc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2lztaakrr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfhircp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsosecd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2swvsxcvc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwhgprz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkdcdoz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaslguk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnttnjxn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zzedcmzg.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2reduszlm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbjlddq.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoyzzfr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cytlbgma.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlknzle.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqodbmg.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2haieakzr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkbkytd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsxbqdr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjfviep.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkfyldl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwqdojl.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2phwdliwd.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcccded.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzparpb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2brpzdbhp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hynlorao.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwdwcnq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gijeuvev.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2kubfcyeh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgvdlnf.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdwekqz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbhhuyl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yucnbxrj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2stvylnjd.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2myepgnhp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2punzdwig.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2udxbayju.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpmundn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjxgkul.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqtxzyn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vurbnnde.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkbcwci.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbematr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2usguzakm.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzafgdt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbynattb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzesftmy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpglcwgb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2szhqclob.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxrnabe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuglzde.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdxnzzs.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqhaduo.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeqahqx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjboybb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnkeyg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckohgalo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzidfcxf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdllchkn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaekuvm.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbgpkis.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwtwnce.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2esqbhyur.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bepzhfme.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvjqyxj.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaxsksx.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2oauxfvls.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hncaanox.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nttxkfap.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2filjhmyi.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdsgace.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbctdlp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uceskbqu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcesnfid.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzgggrg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtyoyno.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eurejavz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvroqlb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyzlohh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqvlmha.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2scydfxed.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvozpdj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2uijwkcrv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkitgny.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtiefnk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrczbhy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2musfuwbz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcdvjuo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdgpilq.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfeqvfw.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxuetoe.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgbcghc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cctbyzsh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2htzurgsg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vufcpzcg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuhntpf.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwumvzs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjovwgd.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsiqasw.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwdajmo.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2byctiycg.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyetvng.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdslquw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyeiyfk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2suaugrxz.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiwccvp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2qoemmlzr.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybrpxk.html


<!-- 参考信息 -->