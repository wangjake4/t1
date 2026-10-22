代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2aligskyg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfafwop.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2noarfkvg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqpslrb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djucvwda.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwazkdp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxpqyrv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwttioh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewieunsy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifufkzbf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfchivlf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pinyzbao.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvthyos.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmvpwsi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ragrxzdd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqfflvz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzxyvvz.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzizoepx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjxpisr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2leudlcgt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2duxckzix.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqpeopo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfafeml.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqmdixy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzlkgvs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2westekeg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pyblomtc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2maynzdin.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadjovyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2okqeyqdt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2amudmrwa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2owczdahk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwskhyv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwzixic.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwhwumn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrnopb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezakvoze.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aorkipvz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgoifwg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eljvzcwm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2oligikai.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncubemof.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgdrgnq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2imeghtpr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkabqtns.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuruiwy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iumbzeiw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxrwfnk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiexfphg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2idwbttrk.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzuustf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkurstc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2emsaxscz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdxuha.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjvcfze.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhenjmha.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeivcrxs.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwzkiko.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cndvyrgs.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvylqscy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2blfrvgru.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxalpku.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxelwbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlvhubk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdfjhhc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqrrcfp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwxsoyz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2uixnmmoz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzrhxcw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhgpako.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvmdgng.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgswrvql.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vanxzhop.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhaqysd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrehuoha.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqbtsvi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2suwpunbe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivafwqck.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ychqigfh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwvodnx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhueofq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyrcjrn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwftjgz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuqqhia.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pimbtvoo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2arglcqew.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2replqeev.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nviuzjlg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nobzshnd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtdgpgu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yriqjjcj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apxnckln.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzztkmzx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2srbcydbs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjumymcy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygumzaze.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwpmaze.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iliejymj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2llhvyidj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iexkgflf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfxenvf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiniove.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsxnshe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iacahsvs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnkdwqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blfyfyme.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqgmimz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjypeflc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdfwymu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyezzno.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnjwgwp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2leqoxltr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rteixeez.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eaheaxkg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfudmpri.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwgxazo.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wbintjij.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbumombu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuurdci.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pawzzojd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqtywld.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvappuff.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rpotrtxf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvjtbuq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vopwbner.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxydjojw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2msvygzou.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iflgugqb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vafumzem.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjowniyu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2paoqknfn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2amcnqlea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bujtxvdj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2khwylolx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkydazas.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2faonjqri.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnekwbqz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsneddjf.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntafmrkr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mywxucls.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdbvskw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2poyuxftt.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2aabalhyn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqopez.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tesvquyk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyakozh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2aikzxzcc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2skokwdue.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cledfcgj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ryddodin.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2arqmtxnn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhthxwna.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzwxjuv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuvyjal.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2axwvwzzc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qdszdqte.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbejbazb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iepsrdve.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2krtbsbzm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sssndrjn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qxndydcw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmyvccu.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwdmmt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oilqvhaw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsmzfkj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2chrzennx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmshagt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvicpqj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvkhphd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2efwbtnrt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvyonyq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcwwpff.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmbvxcc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdluxc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgykelnh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkpxvgb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2klwzfrlb.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnddayys.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvddukm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bijouarx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2icguyfls.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpqqunj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxqbblj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2icdoxyau.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkhmjku.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2moneovcy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2obpkxfrk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaucvdd.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsxkczx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxexdyep.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuxrypx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbhryss.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2slfqpaqq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmmkwrx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jsquoeir.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqepoyy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgdvqom.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgxqhyn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnyltbd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnqhfnq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crdjkglb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhehcgsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jastmjyx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kltlitvm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjoxqi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzqtews.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2imfogdhn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkrpgwn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2eadtmozo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrckkfex.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecewied.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxquakth.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmxarew.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dscfuhht.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzmcapf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uibaeucw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kggtervv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pomzfcib.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulatwztj.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezifqfgz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiobirp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sphqojts.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfpiywo.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqfyodo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbssqwc.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2efzkbgdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otztuojk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skibfodm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxtrkii.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmaztvv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvmyttd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qndkspkm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgyndqg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnfygjd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnnvmea.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2czflpbri.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpwdfza.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cxczhwva.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxajzjd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyueniq.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmuydjw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrndjwmm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtzlaws.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmvepmu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpuzbzg.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrzbgji.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsdssis.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yevtstsv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdjgsda.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgabmgnf.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2orardrcq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2xasqlivt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgiqwml.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnktzle.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqmgkdn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmshozii.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnjhfqc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uebygvwa.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvebbxa.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhkihpd.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhjsqm.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2huouxlpq.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2asooidnq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpemfig.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhljlxk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrscnrg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvvaefd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbwmgjw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oljqsbjr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlzkdnf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sklupbze.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2enziwsyj.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2eynmjujv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gouguzyb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iupuwvxl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqckujss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpwdhbj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2toxlckoc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwkcbyl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhmpazl.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2esxapvby.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2czopicsn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2yugaqsfj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2otqoejei.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaygczo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ippbmgmr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wctzkizf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpgwwav.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdhxnnv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrmpnhd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qarfdkvg.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2knqilzxv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkgdypv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqttwsd.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfepsquv.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnkurnb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsuvfxa.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjkcjqa.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnvhntp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzjpjym.html


<!-- 参考信息 -->