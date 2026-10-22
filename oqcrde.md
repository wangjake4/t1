代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2noluqlig.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiucyysz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuafenm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rksxpjmm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdzrzjp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2enbvbbkj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pukgibcv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclseqkm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwwwjqe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwiomoh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeqtvli.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxtrwro.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2darbasrd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2abzjcwoy.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gvguxmyc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vonlspcl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqvbfxa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctatnvwc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2slyyeunq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnblijsj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgkrrrb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rweqvabb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctajbuga.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbueibe.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2whgrkwtp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxuosqq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeqdccv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rssiomcp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnszebr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzkcng.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyqrtdb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvccvyrf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2basrkglx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyjcbgu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtklopt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznwmcpd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyhzkuj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdhpylz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvewbsm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuddyoqx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdctqlhr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hegwecfc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nebkdhno.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpfntjx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkdwjmk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sazcdgdi.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwydjpmz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2skmamewz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhtuvmm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlngwnox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbsrskn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2duznieom.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qyouddae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqcseqr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eszoyiyb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkqyost.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdbxptg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dihfjjwm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlvbbqh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2iunkoecf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaxhebd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yinukqfg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fihaudkz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2djdrhpuh.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxytjgcs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2oiubegtw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvitcar.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfgdovv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2arovtnse.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2miceklgt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwumddbn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmrrrni.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaazgkq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvikqxu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwczqnbn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbcirbi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibthwvgz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvkxfvt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqxrecz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzdtebl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfydzij.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfahvdyf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxuclxo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eibxgqvv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uygafnak.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjmtcaq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jslxjrat.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdbhasa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atyjtrza.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlqvmqh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njirexja.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2murixpcj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnqdvxy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxybajgx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbjvvix.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2spznmivw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dopbsdwj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2asjjdlak.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2arvgrcxy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hjagiclo.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfauwaq.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttehdraw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzukzqea.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmkfsqc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvehzxr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2twddxmdl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gezmdjob.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dawbdesr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnxfxel.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuiyuzv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2awunxcmk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeyuwxp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrvwlwr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoaotsu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2egwzvlpm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrgiiyk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftusqwn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsxrkok.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgbavpi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcvlbow.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tczuogkd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqzlukj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsrvsev.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2faehxwud.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbbmwgs.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2slsrugbf.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2juruljcb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxabazq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsphcrff.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gstisuhg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2byleejna.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgxsknh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrwcbef.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsitwlj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2plrpduwx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiaefdy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2lmppphpb.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nifyciwu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryucoxky.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkieeal.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvoylxu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eibyttjs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mufyniwv.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfqvvhw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuuoent.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqowusw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elakmurs.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yspyxrdi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnrokce.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwdanbp.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoaekxp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgcrxxx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlcvdri.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxazlna.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2damnwjbz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2icglatqe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvydceem.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoorlbj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vatanuds.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmapkjaf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwkjvow.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffqdegs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ojggsypm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvtavhx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2suismonw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2audehder.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcvhcyq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmarnjeu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwgpktr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqzgifp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjnigxv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kwobmlvu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgofbcqe.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdwswzm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrpqwbd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyqgrfm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2havickce.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knowexxx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryivhfwf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwvilco.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uleckfok.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2enpqjgpv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmjkiho.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsvkkdm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tllgqdrx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mymndsrt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfvyjai.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkavsged.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxzwjtk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzttzyf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsioxez.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrvofds.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmugvwak.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqhzdig.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cauqawbv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxloqdu.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaynqju.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjtwfvu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cymzwlaa.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2emidfoka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buiefyqr.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gauvxluh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlaksfr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgjlycy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzbibrg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqbfsrm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sajyrlvy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2siqrvxks.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqemiybo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntbffxh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2xccgfqwl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmelmbj.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzokcmqs.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2taeizfay.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmhuwsn.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtbnjtm.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaxskld.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxqoqrg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avrpqobo.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fiynqhcj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvzsptk.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdnlcpv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoqwexl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2quydakki.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqirdkct.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvekdxe.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oopahcvz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zhguolfo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hamyhzxb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sciguybg.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2grvabytu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2npzyzhsw.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxpdaiq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoewblbn.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2schbnilz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2stwyncay.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnbcubi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrzjpys.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyfugts.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwuuine.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2atslxhpq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmdilhq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tirybhmq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxkcahk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrajavbq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdqnjiq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zalzyspq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdonwuhr.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2urlvreuc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazjwjjc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmguvmsz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2odkucceg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrnolaj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmskdbtj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylkutyu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2thtpcgmq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwbucgv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vdotselp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlfuyvp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2exbzgswe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwkmiac.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqpbobs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2whxooxiu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xydwywgt.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2olczhijq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqzddki.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaljfzw.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsotgeay.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2lphnirij.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnjxalc.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwfilmy.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlyxqxv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tswoewox.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2btsnmmrr.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbcwyjj.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoecgcu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojupgqic.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2msrpftlk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2slzodhtd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2agyqjzma.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhoihdi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwygykk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjlkbcv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2apufiuyv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqijxoe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqfzzzv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuxomul.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2frlkkgvl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhvfxel.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygrjujh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgaytyt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvgsxxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2quavrfje.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2czmnoirr.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoojvsd.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbljynmk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hltuptmm.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsviduie.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzyzwok.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtzmayr.html


<!-- 参考信息 -->