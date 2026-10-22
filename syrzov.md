代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2imtildlg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urhmlfyx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nekvtobd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhxjwds.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazyvxcn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2idktbepa.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mahfsmgj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2odndmnkv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrvhyfd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2chuwuhoy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoxheqj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkwqong.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pasclhss.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zffvxfsu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuoqmci.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrqjhu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2guvolntq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2agvqmndg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pxblmukr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2meplgmyd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnzkyks.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufzkzuw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpsfcqf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjckaf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnchxyw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rokirpqd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2knwzpwin.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2abjdiurq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmpaox.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgyfetp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmpetmm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2clhavtro.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvtglon.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxlsotu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuehsst.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2emiiybqm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqwdlei.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzexpvv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oewoczgl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxzwihy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjcladf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkmuggf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2fevfhwkk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2njoprnij.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzxxeg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbggums.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zanosrig.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcwjggh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrfzyeq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tpofetue.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2edbqetgv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmxevtj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbohgmt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2daiauxiv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yibvqqaa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohifrtw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpgjary.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qoakrngg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2foriwyro.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkizkml.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpydtig.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjfbrdt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urwbzilu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmftosud.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vozmsqry.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqymfiy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrlsqso.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzfjhsk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxznlsc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgyxqok.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwbuqyo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxevbvik.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamlousn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvakyapr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvaysig.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bssowoxj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxipiixs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2myxtjiph.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpignapb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ormozdgg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcwejoa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2acsopiop.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgirpzad.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqojcftx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2afqyahgr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdhbbpv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2juwcwscd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xohfkwck.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bieknvty.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdejitag.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llpbhcbj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khtkaucf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2empyvhes.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fplmuiwq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iutkbvbo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2udcwyysp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xmarktok.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2moxfpbtg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuwvgno.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrzrdip.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vedumpve.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2adxvvptp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2imaqbrnm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2upcfgqzm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcloniop.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gltqbucc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhnpfpj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2scbgpufh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkddnff.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafbdvwg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zefnwjge.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxbubim.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlfmoub.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihurucjq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxjgknt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmojkihe.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnedjut.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzshvnb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfndgfe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnkhitn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pamufjfx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wemssvwm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbfempa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kevhhmfr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2paqyncmp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2vefrccub.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wumowtol.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtprvevl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqjejtu.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdcsaly.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcgiqxc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efwffkbh.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmfvgrj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ritzadmx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmtfeg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2fctxebzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vksurdcu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dguufbet.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gceljgap.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qezewzbf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vukutxbk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfpamca.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtuwel.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apmxiapm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eodtzmtj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xnivourf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdhpqkh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2obedctdv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfxtvvo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cxczdfyz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zeioykpm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxctwdd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yghxllsl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2viszltoe.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjnbzgp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgcnqfc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqksagfw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaullxp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvlrhuk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xutjayid.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lezvrbrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qzssscwo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdcvkwy.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ykomlqpk.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbtnmfh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2grlureyr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpwuepy.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2typohdyx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ebynjocx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzuskg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyglohdt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuivehjr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtppiioq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2dobvvybr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnsugnq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsknssw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnfryhh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ethqfhfw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzyelcc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2daowcguh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hngmhxqg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhvpxto.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqmxdts.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvyspn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2muhiqqao.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2inimqhgh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgyvoxx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2juebhovt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmzuycy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nquwuvvo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwiussw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfqgabe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmlzdjk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usfvwhql.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysejiqeo.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezatan.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbuiwaf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlwcuae.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zysnnlly.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmwiihs.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hywfphyq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbbnbaa.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhsdgbf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpzqedn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfekmkq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkoosoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjpoyeb.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnqbibx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgyupjf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrktlkus.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gywxbptv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhlaabl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwjlhgv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbgygab.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jczcxkxu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wluumnzo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxyawdd.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvvkfpw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iulbdozg.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqdfutd.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hosmxdxd.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2llfvetkx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jczkguwe.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qjksbcph.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2collpiin.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvzxoxk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2twiiuwql.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2occoujrq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aulxwcwl.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2btsspdem.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohiojio.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlqlldk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbyslaw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bputwoli.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxgmvao.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtliyar.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkfhews.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hozzwvcn.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cayryepp.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2urvzwvpj.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwldwgy.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2soonuila.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2llnibrsr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iexkyxcq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrpffcz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2urhltqct.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wigdzghk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vydhlkfi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpofjxb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaydwqa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgivzjl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2noygslmp.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2udwpjdjb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvmrwcq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jclakugq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfgacjx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtphpxyg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwbzjxg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjrjuwv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2imljwszd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pszfbyju.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2roayiayq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2cntxdvlv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2amkkffwn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqothxc.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mixxmhwr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdstdtlq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rowpxluc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjcfrhm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2srvxnlpm.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwxcqvt.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbbnvxh.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftegfyiu.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfivlubi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtruenkp.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtncowdm.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2idasezfs.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeboqmu.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbovvz.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkjcedm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxqerhz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrkefjm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dscqzblg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2urgimmgh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2htmfluhx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xepphmie.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwhgurt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2opgswtfm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpupvna.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdrqfxd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvoghdn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2remzjgcm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbspwhbk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqoddqw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpdfijm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2npsybxwk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2uortroiy.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlorfxfa.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvoptxa.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhehzina.html


<!-- 参考信息 -->