代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpebeexy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmcxtrz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsanssl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyshogc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2romgfmmu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnteyjii.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vemjkzzo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2idinwzgz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqymlag.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2axbebzgf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmfpvnn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmwzsug.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2okekjfdo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcehigpb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuzdszy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjgimjp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfwvfkq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhuktgv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhlzliv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmtvedz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsvfcqv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfjllq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjrhuxv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2llwydlmy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhuphzp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhjdquo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaooejt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tppjibfo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2czbwtoop.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbkxcxk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qclmqxkp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmupvfss.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuqwkhq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tenthcwr.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ygctovzn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnanhwt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzxdhki.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvxnivn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhifius.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2recuavej.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lezuqiaa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2anikgjit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgzxldn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfegzoyj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqatvwmz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2powebpim.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrysscay.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvkyhqn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbdjckr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxmwbgp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2avwatyrz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2flonieuk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apzhgvxw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnnbykj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzyrpvy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nawskkbd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbteqbmu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqonjil.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2twzkbixo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmhbhgx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaboqcd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nyixzufg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmupeqr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwholby.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpnxfug.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfobsfr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhylogh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxghkoh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbbjemu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsizhcal.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdcojoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjqnmeg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsrzcwu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fbttcqqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bokfwbro.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2oelmmzfc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bztmoowv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwzatcw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2belibhnm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbokivj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztowodbj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzfimgb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sddopdfd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayywvppa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mfugmtfv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwqbiys.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdehhibz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2egnnmitj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsrvqpt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxjusju.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjqvsbo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2znpdpjcx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2luizmzdi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiatzdfi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmuhfam.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eswljanr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzgjxtc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2nopngkrp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2eezrmdln.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhpcgmp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjowynre.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdzpulv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsnhekd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rerdjzpj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkanduq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuorqjpd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vavcmouz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbprswbx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhbuqxb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zezztxdw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzzenol.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2emdrbtqj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwszbnp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkucqah.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbblinto.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxutdzp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwcucgv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnzsmxz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wofpzdsq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qldjobhp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2epxdpiqy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hevdmsoy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmzlooy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iccoqucg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdcqnyv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2miynoadj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwowxxfu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lztuvajl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgdqrqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkjmukv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcenhinf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmoyies.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2npdmyisz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjwwjob.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxshbfh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owspspjh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wngmyvmj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqceroz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnbhdcy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhxhmgl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdzgpls.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhhemak.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzkdhta.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svwfwfsb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2skbsasgu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okgxbuik.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zddwjjcp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uthnghsu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hozpdcuw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdhdvec.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovjuxu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hnokkpek.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkpurwi.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzpcgkn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwthgfku.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbutulu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2taqgrvsf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2anbdgfsf.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cplmnbcj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekobgikh.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yanwggay.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2upckfbts.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vitbgoeu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcfemam.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxfyjsw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuywdtb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfqtjap.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbrlwjm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfnpydb.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zilsjkym.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuvbxlt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfmmdrk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2elrfbnla.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ernlblrf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmthylge.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2esobjbcv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkbxijo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcfftya.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adizwlds.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wywtjkfl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2txnyaoze.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwurbzu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnmaqzl.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rstctvrw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aewuokqy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfcyjuj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfohwdft.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2biupdcnh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyikyxjm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqwrizg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkoitrk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvytvsnf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjltcky.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uikjwrqd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2phnkykam.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjlplvo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zztpbwef.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpovttn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeulznnb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifdgivv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlqzvcu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldyhet.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2txbezcvw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwdpulm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksfcyr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bboxfzgu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeehafdk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtatzids.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbtcgim.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrlvicl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyfzghc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgceqgf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyxynly.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2aykaabbc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2depdzjhy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoqjvgv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vooawurm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuvncel.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhviniez.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyiajuz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wptaudky.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iepldrvd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhtnjjm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2glfajaze.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgajyqvn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpyysfc.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrcqiwd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2csefewmr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2szkqghap.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdiechi.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaphdqfj.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vckoaxoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybodptvc.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhynffuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfiysss.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmnzfjs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2gkefpdgd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2womqwzpp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aesxmjav.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2faacgqcc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpavydp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2reppwjqa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2intoqpoy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhogznkd.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqilzqgl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2oijweyjr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2syujoopr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfstdga.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkxvobj.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2winvkmyz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxlcbrl.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2snmjldqp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkryvdkh.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfyntvs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rehdogmx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqerziqr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqdwlyl.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2errrsiye.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgmnbcv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zilhrjvt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2crdqloev.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cminourz.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2atoqrgvi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2defjzado.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2etesqmgb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvjqdhu.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdccncwz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2smqlidtt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzupewbb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2useqbjqt.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2usxervxz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaieitu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2btovpmmt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkbiukc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xruvqmyo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqkrkxr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ligohswk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlwvefi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaxshnu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2delxhkga.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdktvbx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huqiwujo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2whqckata.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qryfenlk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuwknti.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2apxswuco.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkaiqtm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryublyzs.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaexoqdy.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hblttyyt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2mlythapx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbjeywt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkizvqcu.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zckqwdlg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2udpmkvij.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdhfkir.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrcyfow.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbqsfls.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wffodext.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2triamhbu.html


<!-- 参考信息 -->