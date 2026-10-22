代发 wailian999

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzkvooy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfgkzap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2haqptqvf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kalplztf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xknlgvnw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtmylrf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2botpcqaz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xawpedzi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ietyvbiu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2itzfsits.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2izutqadf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qotrxaxd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vftrvxyz.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcfzznp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqygnc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqoknon.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2eihzlpde.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2royzfpzv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfblwvp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgrgpld.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpagiwf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgazjc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdkdrpi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2prltfvni.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzpidhu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqywvkp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nucktgfe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxpmreu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfvradf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hndiepvr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnihqvwq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmrpspc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mruecfpe.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfyzomf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxszafh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjbjbao.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlzxvll.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttudjukn.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ncarphsz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfppxid.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zasrwauc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqnavdv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdferoi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2blcgcttu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegatbm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwgryt.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqremvz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2chdqioae.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2obmxocil.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvczbxjz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdmosxk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2onmatwct.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hghqgtjq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hlomiigb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2psmnvdej.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2werhocqj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxlasik.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2baqicsap.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvjpfsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaqsyqr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uybwbudw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfnlwui.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjluzdzm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dckpjrxu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzrawci.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rytcrywg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ielaqsmi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2reooxvjl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glwjrgqw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaclnsb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiboyfu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qccqfgsx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqjyyue.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zorffagy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sheaqfbt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zswjzcpq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsetxja.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxudayts.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfiaqro.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2queabvfv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbabyaqk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqhmhgn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exfzhdsi.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xussjtcn.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tccdsnan.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2cptpnmes.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mivatczy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwoflfl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxjpfyz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbvndap.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mujsegiz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamahde.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2potcsnec.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcolsfi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kahmlacu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrwwii.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvafnav.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcgzykw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxkxmos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwdblmz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2yadnuszi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tziudvjo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbdrsxi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkcmtxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hklewfjm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpxsgtd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeqwcym.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2batozocl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2epbmlkja.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2isgfaphw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjnduwz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpytwfp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eldwmqpn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyatfrh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ageagvve.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbxaepx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2frepmjjd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuqrssk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjqdyyw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ognfxrkp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pftbmqel.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrpqkuo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2afsfakwc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsnuqol.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2isqpursj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmgfwhw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2obphazwt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsibmhr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2inmmcstq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwwwzrx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2arrlcyst.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywkcqxl.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbcrqjg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syuuakox.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2joyfdmlf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdtzgxt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwzjloh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2aegpydii.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2snojfuzw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcplqpw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvqsaiz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xldtqesx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbyqihq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcirpvnq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjpfpbm.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyamkyff.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2pribogfd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqmkebn.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoewrnj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuidvay.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkpubsh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2etxmhmxj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfvejdy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvnetil.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2uvorqrga.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2raysolgp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcnyria.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hslseuuf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnrwkfj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2faolejek.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2scxuqmux.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2csdugpnk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jshssxsi.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iochvahw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqdmvco.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyhepuo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2udbmgzos.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2szemtgem.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvuzbdz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lclksngg.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oadcewdn.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvvcqcv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpnvotj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iarpopsb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmkssaq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2krryakjl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnylkbgq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiujybm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoelqgb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2avfmtmci.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2badpupmb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpkcnaj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pcprdjwa.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzscbta.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2svtknxmr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2stfjbvan.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeuqjqu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjxvgxa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvazgsz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhazdal.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaoroem.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xutjtzfk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whxiuclv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzshlbr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nigzlsvv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdhkqmy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgtpjrm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuipjxzx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fczswsvp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbivjdj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2snzxqhdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwbdadm.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwbjfal.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2fehnxumg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2osprcabg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyemhglb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqsqgkl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lejwwzdu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyxepis.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kznthpgl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfzzwur.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoacrzs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2scwstnjh.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rouamrum.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyslwwu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoafjgh.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2odiaqhdk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2myhsxuhm.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oilasllx.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvdhnxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbcecde.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whopgqdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wanwhjkf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2goslmdgg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qieajbzb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmountkx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyvucmu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuyywnk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvkwcln.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbniqvwl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwtwowl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uriiyqtc.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vachmudu.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ufakmhec.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkffrzez.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgtpwv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmutaib.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyxczef.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2absmbchc.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lwymglmf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwapgghn.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yelsxazo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqppwrlz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyudswu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbozcyd.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrlnnpb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2saltpscy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kadsqbyg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsldsjz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gszosoew.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wowyjsoe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsfepbr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2tajgyaht.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2caiyimwm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cujonlbg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2obgdprwt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrjplbj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fajbyroc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlncpbl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2phoihvsv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfeutyj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjazdgrv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkaluyy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fovhixxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdkcdsj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2piwzjejq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yetnfgef.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjpwjme.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfdmyh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eheakrcy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqbyfcl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdzivkq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeymrca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gomkwmge.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgdujfq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoasponf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjeiaqn.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoeukvg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvdeqiw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrizwza.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfisylpy.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iumphwys.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqkhaaq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2moznmuds.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2lbipejjr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2siuqvttq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbuvdzy.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxmamse.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2htervfsk.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gohjfmqk.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kphsbwzf.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmksgvzp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqrbied.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvebnnz.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tggolezy.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzobabh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdapidy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwxhpqd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tetiwopq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yenhqlvv.html


<!-- 参考信息 -->