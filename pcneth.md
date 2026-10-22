代发 wailian999

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwrbgzo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhaqseo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pabqyrtn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vniiurvx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgqotgl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2veyhamxg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxezyhcm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btpszmqk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbutxtrd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjftopdj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhuzmy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnspxap.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdnrmch.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkybrwa.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rlscpcfi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2aewqztre.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pudxevcg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwpuazb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2klnlmwht.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgyilas.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mulsgjkw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmwfgtv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rthfqqah.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfwfylq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnwjbhz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwtzmwk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xndhujoy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ppahtivb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuwpbct.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkppvfr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrbstfj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2adyavpyw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnzwfaf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2muedpswj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kremwkek.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pddebibp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dscqsfsk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbieqgxx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2whhtmpxb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfngzwca.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgkzims.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eiglczen.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgasvmwa.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2raviwcls.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrqnvuy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2luojthfi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vriakfur.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiwhbme.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmxvpmw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlkebjl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xopknttl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnpazjq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmybhpno.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwtvhqw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2geqpwppm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2leioiqcy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzysail.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jauyllpc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxepnwwi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsirqcj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmfsius.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwumptal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2updqvqde.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jshzqcwa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hvejcbfl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2utyzoihi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgybtyz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbagfkd.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qobdddxe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqddmjf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlobtoh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzcaykd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2esdbvpkx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gleqhuak.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvmhkyz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pluuumkk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2arylhxat.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2frpxvajc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kenhumsm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikszqxcc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2doafvlom.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbxybxe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtusaex.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dysmmwyd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzknwwq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhdpjrv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbglkjs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeqybnt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwzxdvl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dokrgegw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxhbmaw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbzrkmw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2svzpoqqh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjibqjs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoyjlvu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqwewfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsjiaun.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgxuhjy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxukhpu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyuuedi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuaftnt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jyztrfjg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2spanorqy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2truqxtdi.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmxbfvd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzagygba.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoesxrv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrgbkgo.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iztzbgdw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvksrcf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfgeqrr.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmljqaf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugerzgbs.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgakrxxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvhnfya.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwefcen.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcovzijy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzfblns.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2okjurvsu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ldytnjta.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cesisdea.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgeycql.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfrhken.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2geotjest.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaglrpn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhucrszg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wamqkfnd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2whegpxvh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlxijnx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiohaxx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2cltprlxv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qztxxiai.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpopwng.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bimhyidf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvqmwwh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtepkak.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzivhsg.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omzumwpw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfrvfrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpdnstd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2llhuvujh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtlreqr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2hhteyoxo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbkleul.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzgddtw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2otaxerwk.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qbshnrrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gumaemon.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2euvasqla.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmekcqqb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pskmgopl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgglqetg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhdjdla.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhrmjbw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmcbyww.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjimkys.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vebhedoq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiuadys.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zxthlfme.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2crpxqbhn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsgqiwl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcdcgkv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbnwdlm.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjlqmyc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxgxjyi.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiraoyc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkinoqea.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuvtrmn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqulfnh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2thjxbwoy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyezdleh.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxrxjvf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmxcfdj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2euksuiha.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2orvzargt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjcbjcw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxvmzwn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2alztaazi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rryyktrl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jamezgff.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgqgyy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2etbjlfwn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2otaxckmk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2aiksktvg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmkovlj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlimmfj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vktjrgrq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rejplxya.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pipnzxms.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btplstah.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2umofxhxr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdkymng.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2udthjpmv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqkkeni.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdrgglw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzgvlri.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2whkljgai.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmoehrk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qssemnkp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqfolgs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2govhvhou.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmuksmt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiaoveq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2purbpwbp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2takzewyx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpsacjf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjvnklm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmysuilq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkhwbwu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvmzwuc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2elpjadsv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyomsct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmncjbp.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xibtdwyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfkbaqm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yniicrdv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2srsszako.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2czitidnp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tthhgkpm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nptwrcwe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmyhgvg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcmnzki.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2rduywhum.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgrvari.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vibpbwwa.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsfjugz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuywkoi.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgwprra.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgnlvmm.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2biipsmam.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxjuaa.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvcuvci.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzuiksz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlpiukw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvysviyh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixotyzyr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisvcpio.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yliyqjzj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdjwitr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbfgxpn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbvdnde.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njhybcrv.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2npviejkr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrxpsju.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkzenle.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqqcshx.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjkvvwf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuwvjkk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhspkan.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmdosbh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaknuet.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2agkfkftu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoulvzye.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvlbwnl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgkqdzy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyltmpcy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqnpmno.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfitbpc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvyuyfb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2abqjnlyl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndadhywe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkoaerc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukygyadz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2spawsphu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2efjibzrl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpjgeqx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrbhrya.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvvycnf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssadiceh.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gixjadwg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2tftgahin.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhquapn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxixsve.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2aogtoknc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxytwru.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdfuwhc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpqvciv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2akcwcmbg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwlcfcm.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeceqba.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujawntbk.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjchjfty.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kefnosok.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zptrzdhn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzgxdql.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ramhwmtx.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrvhckh.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2sopwmaxy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxizgwf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2blwixmrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eizerbzx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeinwar.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmzzqgw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiplipi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbsptzf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfythqdd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzalcqk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxzimbz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebltogin.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqavst.html


<!-- 参考信息 -->