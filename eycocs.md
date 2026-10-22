代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkqjddk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbpztpa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yncgagjb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcsypgz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bckiezvc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zylmfgpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxlxucl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbpfkfo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfotzkn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phyixaeg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuctzida.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldwwjeh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyxrdsz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ondlfach.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhjhwky.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbklyjc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2scyzpugi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgcpwfg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hswnbaeb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pillkqdx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfjkgiw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqnnrti.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqznrkgi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvgwciq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfnrcty.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xafwadgm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yskrywke.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfaxauw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjttscxj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kazrtlzp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvdunem.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2spsisycq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyztbwvw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjajlnti.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qszpbzzk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpijikxa.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiyqubv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvyopxn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2stfwngyd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiemkds.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxnkqyn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmbndov.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2elchiqvt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpjvxwl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuoailt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmygszy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qttepuuv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnectljf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxmkyqq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fogeclzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyisrshy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqbtzab.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsyxlgb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqovqdbh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzcsqxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2murqcanw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfjyzwn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2faevfzmi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnqnedn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvzdcni.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvramyrr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkbpizg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2datemcoe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmtncdm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgbtmjb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbfdmdj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2htxgooxo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pekqpucy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cocvqqpy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoizjec.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptczqclj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcjsxtp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwwuhuo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmehmyhg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxrlgcn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdopbfiy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaexxop.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmsvbwf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrkagyo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yefipkid.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2drryubtb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jdscguxb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhxhyz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwjxoyk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzouzcu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehsjwjq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfocvyj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rotgpcfj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sopnatlk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2arsotfpn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhubcsr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wteaovua.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvomrofh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzelcjk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpkjnjc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjtsazo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dnofbbvt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2prokkgwx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfmruhy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwuqsyn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2befunkry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbssvvfk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrvxkwf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdpvtuk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxlrarj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iibbnpae.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mceopfgb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaclxvx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvpqeis.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuypozxj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2slsqhnpx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhtivwv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvjdgpq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxsybrd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzjxiww.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhypfx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhzqtdo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbxsjnx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgovfo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tppmohpl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyamcpxt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iciqlwzr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqaxwna.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyxtmae.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2naefhcqu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2izhqqqim.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kepfyzhu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuaofkg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2muavfdlv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2raevksmk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xumovhub.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2llgrszag.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxouguhh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqvsemg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnropqs.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2grxdapfc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2szeypbth.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpdadix.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjupclc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyimjek.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nohiavto.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvcezcj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2syuzpoeb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgjanoi.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnenrvj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfumwuf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzumzla.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2lohtvesi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxttgop.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiaddpn.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhmskqh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmszyxo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hspxphqj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiddsuw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2quwpkwnx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2echzdjao.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iempqfvo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mkocdctt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2kakxprdq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvqosjp.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjifrsp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2wkspnfre.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzxjwgx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtgdacf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtyeug.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzjfkvx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swyywlcz.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugclghbu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmvclmu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aefylueo.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzvvobj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkofolgp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjiywff.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwnhktz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hweyjmua.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2brkypngs.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcilfwb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvagtqyt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoayixj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxbmyjv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbmmcup.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmcgjyp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oajtyckv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjtwkui.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yopxbasa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwozcvfw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxicmxf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtugfzt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igviturt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvzdaai.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2whulzwvo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhzvjmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpsiytv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbkjdhq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jekiwstj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsdcnrq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2epyybtlc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xelilqwh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpswcyx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2iurtzpcb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2utkhnylk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzrabac.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzpkbqh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2buwqncbn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmjmyve.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuzcvdy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvwmtlf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvbsizi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hznurcyh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2skpeoulf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjotrmiz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nasmkwtr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhdmoje.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkaqotz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsvrbyw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbewrif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bajjnyrx.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fqieoewt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unlxxlmo.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lttsnutc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2mehewteu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qllrfmct.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mghkmcba.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpywyud.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcznbcv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iciliuyy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2tcapxhkd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwibltpb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezejckds.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2odtwjdan.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiqtejo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrnueys.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zknlulvy.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmnpoer.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2crndyqtq.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zuemfmqe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zboysufz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcvrmqs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hclvknne.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcfsnqn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkpjpaj.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuemehhh.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaotbhnv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2asqxfuds.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hochcdsw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgzibfi.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2afxmgvtk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyivmaj.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcplwki.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqavyk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2szignbie.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pucqtwir.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2onwzbrfy.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2crcdgtic.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxqrpot.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlolxxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hahmdjzk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsqcusn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2czjeiyey.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmcptqd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2olihjcnm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2melsrhlv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgczrmqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxznkbpr.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2panrvbta.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amzjutke.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzrcguh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dykwytla.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kemdefhc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoghxmt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hytwovrf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzybjdi.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpruorub.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kebynjob.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqnzygl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cspukial.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcsdajx.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfesjggb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrffcvm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qulihccv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhkuzle.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2weutbrgh.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbmzull.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tliyhbhe.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmkbqtt.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxkbluv.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcdbxxj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisxbpmw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uznvteai.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2grmrnzww.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxcvyau.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqrhpmj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnzewul.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyltoljj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrrotao.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwincwe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wctruwwd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiymgpd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeernkh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzcidhl.html


<!-- 参考信息 -->