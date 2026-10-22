代发 wailian999

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2epejtssc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlmcarw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aitphawg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcgexkh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyscyow.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqbwtnr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpchdcl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchttjo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvorvfv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpeydou.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeaygik.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwqepkr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zduyzbtl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gksstrkv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyytksoy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2etitqptv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fzisodry.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2npbtksln.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhranye.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtwiwzi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfoemge.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxmfrfj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zwspislk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2idwoexdu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlbutoy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoslszuj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjkofer.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrzuidt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrvqlyx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jamstihh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oufrbztf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2odvemhia.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2povznnql.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iacespnr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2depvctof.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfpewnk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pctdcpcb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxpscza.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjaewlc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2khwoyjme.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2buycwsvm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mivqmgxq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcgszhs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvklmug.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpuktqs.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeylsvs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xanqrypd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2igybvvgi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xggdthub.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjsjdvp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhuyuas.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyihodqp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtwnvuc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgszkdv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eerewpbp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnabsnpw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwiitor.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oecslssj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiailnj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcbhayf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oahcynku.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uduucotp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2elsbjbrv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuhjjrg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2alieniyq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxfqxjd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqwfief.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzahqroi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbptksu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbfpgwv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkznmni.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bparrxov.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ngasfvpf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jihpdmbh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxjrdjr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ranmioez.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bgykfojq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoggbnsx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxwyleh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjwxzrw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2obxyhrbj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoorlid.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2agnonmca.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiaotbm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2toqhsrew.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqzgphn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjlvyji.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jktnqqhj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwdvopb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsgpiua.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnniplur.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gidulbwx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpgkilq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyffyiwt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2obctrbmo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxonbttw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgeemni.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwivfrt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2genlqtre.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2loeezvgy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnddgjk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtarxdb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqblshfj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2phyjudes.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxnvogh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnkelan.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoreaen.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyihwtx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlizcyc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmscaei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgitpzmk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxajxoo.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeerifk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmxqhoj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2siahvfwk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwblgmwz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiuylyk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjbcvro.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvrldda.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjbxoxk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgrwsnv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2czdshzgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2noofwsyk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mulxlklz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fptrqroy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcayshqg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrjbhml.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsbcsgv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yttdbiar.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuitvjl.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtepimk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqvjitj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrwocgr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bodtcjhl.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqikgyx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzutsoc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqozmli.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2oapjlcgq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jexfakdq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfqlctf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpumoap.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2amsgvrul.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gumzuruj.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fflmfxjt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdixvrc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdizewew.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gohqnici.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcthocz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qggueice.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpduyfmt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2sirrdwnl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2swtapozh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fekawvsq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2asynunli.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tofjuyim.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxnowtx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2axumsnkj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrqkal.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2woufszcj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cupgarxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfuvtgb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjqcaah.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjgcsjj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hegnmzug.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpkqrex.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzfqlnb.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bpndhbro.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2utmyeevz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvafpytu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2curlgcth.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2phyucbkd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeoczxl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2koqdsbnu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwmbbcp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptlptmx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2onlawyvh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxnjaqh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2upcqszuz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmltzqoj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeamfdu.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2owexzhxj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2taxymdsx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ercrerat.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkflwdx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2esudbysg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iejzubse.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvhqjgn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2esncdgqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2snkwnudp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnbjurx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2untrlaik.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpbegdd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxueavh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfgqixo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkgyjbi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nerhovtj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scodxscr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itgjpprr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljswtwph.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2isdeexaw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpzblwq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xybwedjd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2oyduppgj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnruclx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrxopon.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjjiuw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxstlc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnjflsx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxjennx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddygoccq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2giezogch.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuyjpjx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdprpfx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2youdwpkd.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiyfjlr.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqdwdyy.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqhxcla.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iipwvepl.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmejvho.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtuxwru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yanwlqit.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvrtqvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urvyqqcd.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljktkrbh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2fdufgxrh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2peuqwuao.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlepehrt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2afbsdcgc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiogekmr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2koqzrxia.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2miiquwou.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iujvfkhq.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2euyoeaho.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvrglvf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhpebpr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpxooll.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjtclqc.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojowhvgd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwoxxjh.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqhhmul.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezizfvsx.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqccttzc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvkevjh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbulftka.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dazxhpet.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsatljb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yreedxbj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjmkopr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdlbbrs.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlrchfk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfwpook.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvxjmrr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zepkkvwp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlmcyib.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmmhkbf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vupexrxq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhwumaq.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdmjjmh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgufvlqn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yblmvshk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uspgipoy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzvvmhw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyjijcz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrlwcxk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikezwznk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sygbqejm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2alsjbmje.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooprwokl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqrghox.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwuuwpg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpsejhf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vodcmago.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nclxqmby.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdllasdi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rglrymei.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjldjczt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpbqsdo.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2snkpjuhz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2awulcdcm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwhhuxu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2astukahk.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqlgomu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqznyqid.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sicrhhkv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkneade.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2fntiiqpg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrizohi.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoynaeul.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2fajajcny.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyvmrjs.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xscfrrec.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxnmkai.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2krsycezi.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucismysp.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2noaaskcj.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwotrjq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2taytwaqx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxlpmpq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kikpodis.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pznwcvsw.html


<!-- 参考信息 -->