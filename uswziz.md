代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jddahrvf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfvkwrw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvcawss.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nslztubo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpfliri.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vierxfeg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnovhhv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoygsor.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejksbtgz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yklmfudq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2shrvliuj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zrllwmoy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyushqd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqlsygz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zewhsmzf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sifeydcc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zuonhvmn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkgudcv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2klsxwzsf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2caaqshwl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2juxfrqmk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bihvdwuw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vyynfati.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xthnkzeo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkirlbav.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdescjop.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qswrpfet.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2aelwjaxo.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhcnag.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfwqymy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnatzpi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lawvabvy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmlzwpp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eannbdzv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zoywxmnw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2agfzmoxs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaybmer.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iccifnej.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxteiuy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsoayco.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gshcilgd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cibdfbxw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2slreqbdy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbttjmes.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbobfin.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okvtddln.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaivyir.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwsldba.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aizpihjj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ahydvahz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqynhxn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nampxwef.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2prwipyie.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyumusc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqksyle.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfjvutz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlzcoig.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzznohwj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtdzohw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlmwunt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2carfgfhd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmjscuj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubjkhmr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtcvued.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgqddwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2unaooilo.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yotxvxzh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjwfynk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyotnry.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nemmgqrh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtincsrv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gssqbsdl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrmcjau.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hannmtza.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpmdgda.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yukrxpkg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qarexzej.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvryjpyf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqdtcut.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eugjsjvx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnennhh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkidquna.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2axgjseag.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrrxtzs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtoajpg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzelhsrc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qncualjx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2onblzndd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsnstpn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnqzmqc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiyhenm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsgnujp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkhgljh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdrizmi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrzviwc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdrbwmv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhrgcxq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkxdonf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqurmnit.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiwxlyl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwxywvq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmageyz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqacwiy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2llinqguw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rllfuolp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlqgpad.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kylpolhu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlvjjlr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqyovlz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2alflkwry.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phobeqjs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzfjpyx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vylicsna.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwerthki.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jijqjdlv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvaszfm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzmsrzh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lksnlefp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2guldtadp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnnkdjc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqycxaph.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzecddci.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbiuuqk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdkveoy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjcjyjw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxbambi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2idvwxcne.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzkgatx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwhvxhi.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnqjsrm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsxgrad.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjfpdlu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cafqyiak.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edxptivb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uynlgzbj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgniyjbg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbzjcbe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acydyzyd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2iayocnsy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfjhhzs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhmfgqw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2elacsbdp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gymjzgpb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lddnkeii.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfvfzyk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kckcrvoy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcvuife.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqybtheb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbdmyfi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zaslnfex.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaymmyx.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoghqfr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lvquzkaa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeqkvyt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqqmssc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2aahccbjk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2epycihvw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqvoysc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjnnhkk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtaeoqx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oggpsxms.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihjluml.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2udilsaor.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2aavqjuvs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwuamek.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkcdmkk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2luuwljvv.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2frjcldyz.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lshldjpj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbirnkeo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2eruvhamg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyqrzjd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2erpwkjmu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfhkoeh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yofhjfdh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgogvwi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaqnztz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmajzfhn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ialubxyd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xdabgpbm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomsjtuy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwffmri.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeykryb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiruowt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddutvnw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cacigpuc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zooudvmh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhujdyw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjyiwhw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2drqmuqsr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaiifzs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2beogluea.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdzytef.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvigjwwu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmggvnte.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymxpnpd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxklakw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwwgzso.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfpcgxd.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmirntxf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyrgqze.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcgpdrq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvkvtly.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxprgnke.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbskcap.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdvbskr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqoiqfq.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlomhmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcxlyem.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2raqnjzht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szznrzyd.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnydmff.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbyeybo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2moqoujhv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtnejvi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqyruan.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhqtcch.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yatxhpcm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2amggomdc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xswnzouh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmubjcyv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcvbcvy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urnekzve.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtaqnpl.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasynzbc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvosxslt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfvxzxb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmfwcql.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjhwykz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmdguvn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwrzqag.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wccuxise.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ospovpdj.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjclqif.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltebmnwn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqvlrwz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaltabd.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrglzzmn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuotdim.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfchrfny.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtihbsr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvinjvev.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2srjepdol.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqssqvg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmqpzjx.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlholxjx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxcaftb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxwxwuz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejepvjra.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2afeeoflw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxvrnyc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2faqkssav.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfjrixk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxlomvp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2okqcymsr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnxrbzg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckylfqui.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsgffnf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2znfpxurg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2msstifos.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rozoaxdh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjbmcbp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdiugem.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqivlhbh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiekppsa.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2orkgaujp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmuxbly.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkdjfcw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogluwesh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnsexsq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2spnsajbw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtncwoi.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2llaxfeyf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlpznjx.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgmvqiq.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gensyyrv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2aetouosm.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfllmov.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiriwily.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxufhabe.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gptpkatn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeowtif.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kolgbqhr.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnkxwgr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytgojjk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbbxqdd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqdwxeu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjckzdy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdvlwyf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcypgmu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2urujltqu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2smwxojfk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiedehh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2edkrjkxl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiidrpnr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpeofyl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyxcrjr.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uptogusu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcmevsz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvagfldv.html


<!-- 参考信息 -->