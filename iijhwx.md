代发 wailian999

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrkbqgv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hphmffym.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqdsopg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jkodhiod.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zhugzxol.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sinqqohx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sptsbgyz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkzlhnt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lakhodkw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbethfvf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uijtamtn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoalmez.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoptmdc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmemdiv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2obkfejhv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcsuuhn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtmvdrp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieedeqbz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuvbtwb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2syzsbljn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkailwi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdiqupx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmzngax.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsdnzmb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrzytbo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sydpjgsb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2okxpxyxm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lobnzicm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfgftw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhhqteb.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzyzzdk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kekzceiy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcelugn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdxhmoa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuxmgyf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2anzndkde.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwixfqy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wipecigk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqoqima.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pnighuug.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hisxcsyt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpqjuwh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzhfnmg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfzfbcr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfaxcjn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlnsvcu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oamxuklv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxahriih.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvetcqd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2oufllxcr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2byzwpkbu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zilijlnx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnpurtl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgwmisg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2unowlobj.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhasgiuk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbqfuum.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2exfsivmj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzphxfq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrsjss.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuxiktb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbaqirz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdxqjpr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoqvklx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwomseq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jphswzck.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cldbutov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2urptdgfv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqplalyw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujxuou.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nroospfx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzywwsmm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iapffztn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oxalduci.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2itggsqbj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmlmbis.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrueosbo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vutuysfd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbikdvj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2reqyjwvh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uskfnuct.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztncjgpe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfsmlgs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kokxesno.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqlebxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjrvsdu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoduxhs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuoyglw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2obrkclsw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwioxwz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2stkzsxln.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsaxmsi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpolcwgo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaoyevi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2olostzrx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqimrpn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqlnidj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2okkoieza.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpdhbxm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflqsybl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzjquba.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxezlzgb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2whceaojh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbsljgm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfradfb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktgwvzf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hytdhhbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgocfaoz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjkpbox.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoncjzu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpfowis.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lutitidp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2awpnugvf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpvpdym.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmansgy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2watxuiqt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjpudeu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2djktmxyq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpjzdvo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2shiiqnvj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqpolht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekadznar.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrabdte.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ryotlvxu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yetefxnh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2spuojren.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkrasvf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwigjli.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2klfvwzto.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkkxvgu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imekpjzg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiolzmn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cflqvwfi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpsgfhn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqllqkkv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2soudiglq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhvaaij.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhtoxkb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfgdmgn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvabwlob.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2luoqziyv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2prdarxnu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkghtxkx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqnjbu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymosiwyw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2utvvkvis.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yswgznnc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2egtqdtcl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfzftlv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cznrggfm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2krgtifvm.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkpnudi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vytvjojc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfrxypp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cokkjrbd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2esaryuqn.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lptuxsqy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brxllzhv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2preizqtq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gctctkan.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoswpyt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbitghun.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2odprsfnw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymtxcoi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2swehtflk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hofbrcdz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwmpenx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zadrzazt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fggpmhxk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmpvkgv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjmzopn.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkyxgx.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2pavlnhbm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lnedgaqq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjnexzz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vejrfavc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnkrhpi.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpffrihk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbilhrho.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwlwqew.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cimnaexe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiocxvko.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoypbip.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2duogcthe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkakmyh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jblsrqgm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsnizgw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpzxaxi.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaucnboi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoxafsn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsjmfje.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbxvrso.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ztesinph.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2erlejjit.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skkzganc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcochfx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtqmsvt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ompeqepp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeozrij.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2bdheuuir.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrznfge.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yehzryfi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjdnuji.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqvhenu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpnbuil.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnvelhj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtqtxln.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kebasses.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2owepbbbr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzinljeh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dolyvvnf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwjvhjm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxpyins.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wityarsm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuflrxbm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnulkkk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2qacynpbt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmebjfyt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exkyxpun.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afxavcbg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zifbrijj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2scavjfmc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfjnhca.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpiaalc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2drtfrkkz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkerbwqw.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfrneux.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnllnnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkwvfzz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2agkityfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrykbzm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhabkkex.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2undtxkde.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwtpxzu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sduakbcg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hajtygpm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbfqboj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcmcvrd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdaeabc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxifmtab.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2secrpqri.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cipdajru.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgkdpij.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyptlmo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hapohygu.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsefxkg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokbuslu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2beqigkxy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gggvcmfk.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbvuayf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwtfpzx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2scwidcpo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrvmypg.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmywggzr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiywencu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2twtotpan.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2scbfbypz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pntrqulm.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhybdsr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbcnfvu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zauxlrxj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqblvtf.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpchgca.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzhzvck.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmzrulz.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsxieii.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbrdjta.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qswpktcq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkchnmew.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbwvezp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlmotud.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssihfmco.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeazodzr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnrdhqz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gixsrtou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fabiskkg.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cexjwsel.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkghbbgi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2girgwvag.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cohiefyb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpxwfhs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhpzavy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bglzypwq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwrehqr.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqemmlql.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbthqce.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2afvzgwvw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yysnrunx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmegsdo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdhkraf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvizyxf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmxaxie.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtdsar.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2vziwhdtc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2enobiiir.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbwsuvn.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymwkgdg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpurffn.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcvxkhp.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplwfpad.html


<!-- 参考信息 -->