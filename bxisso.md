代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wixpcsqn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrvflxl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwogfhc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2glfocfdi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnxunmp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bztjugyk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfccwjl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpylijvg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iokopdpb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgdvzly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxftymb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djpfwmel.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2relqnfrt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tilmntgw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aptuzyme.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pdblsifm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngefey.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoihopf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtskbkw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ambcnqgh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tojyvghc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pakfulbe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtqblgf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2clhkuwja.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilchrjcl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnxwerj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2raoqlufp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkgacku.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nljzfyjf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdmkkyr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscrpods.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2knwvhowp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcgoxsm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlqatbh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2isoqbsxj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2htzghglz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncttfibv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuqiinn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2awgkzyzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaovqnz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2knccfjws.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2srfypcbq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2guunbxyd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rorxfbke.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlhwfeh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rifnyzxd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2feufafpt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdtcppw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpkomam.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fleocmms.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrthbrpl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwaqsld.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhplysf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqhpglf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zidzbvxj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wequfrow.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvxthty.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnlbutz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgputiqq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lebwooch.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiyqhpj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2meuvpryt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tglbryos.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2baqbuago.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gstldnep.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwutqkl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtxaasp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpteghl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2freokzuq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdddveyy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jytxqvtu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpgtbyl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zynlfclt.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2geyhdmxd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rllhhbvg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2abnnfpum.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyklibo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrnontm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2beepagbh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsanmllw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2usctgqlb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdjnzgp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cserahnz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgobmudm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yaomalll.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2czauxbpf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdgchz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkigfjda.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyinqub.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkmnquj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajsxmtd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgnamgc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfjekyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dufeurrp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yctgutnj.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zotoxzkf.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2simrwnkw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlbiuhm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zariszmj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyjiaty.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjbwzrm.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcwhjmd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvfxsuh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihegrhxb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2atvivoms.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfllhel.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfirkom.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2swfxhleq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjietrg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2eelexrgj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsllohzg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urntfqcr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrstaog.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vupgutlz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjfzrgl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2slulbesd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpnclmq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ztplshya.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjgtaub.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2itcfvrpt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzlcmdc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkdkqbl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2eujoigzc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxtftme.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usobhuwn.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2khqyazkz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2atwohmhs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgnbqcf.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwhkwqy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpjgdrn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2kosaxzfy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmvqqkm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjefdaj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqytqgr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2iibjzjxq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2akuczezf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzguccx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nysbmcyd.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2taphnisj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2phgidnya.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaqcmov.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kwapttqh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xusidzwm.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfrkkgt.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmkhrmg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2rpndvuri.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2psuvsjrn.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tzksiovo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvivfok.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2miadriaa.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmhluul.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhyhbak.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgljzio.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gddyawvm.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnotqpu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvdgjqc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fawjdnph.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tiawjcga.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeavogct.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuyjmjk.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nththpau.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyknflg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkgrbay.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmxredx.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvlnmtr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2swzsmcet.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnzkuwm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsgytew.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaounge.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcydewn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kokxgdaw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmsbfqz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvhjfrf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyraxpu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcojmmg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqwpgtb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpbftsl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvfiaya.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyaxbre.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2enrknkmv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zupsunvm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjsgdir.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2brdaoybx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwxdhdp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdikdmu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbbvmsb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2skoifivc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqejnqcr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxffikyx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfshbpw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhrqqeh.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alngavhv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvayltsp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdftngkr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwqtqfs.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtxamq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hixfetez.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2drxlxvau.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqxethr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqbhbih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owgmujam.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvvkvvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jocwjdue.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hujcvned.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnxpzq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2useugwpl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfcxhqp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2exdxohqm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qadjezgr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bthjmssc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2maxwiosf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sokwhgyr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfuclwj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qesggkhm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zldeqrzd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbxscrj.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxdwwgs.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqpujrb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knuhcyej.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2prpshlcj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nznqshgv.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2owodfsqa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2clvynfyu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2chyohtol.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmwvocn.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwrdepp.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlcseca.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fidgxraf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxroeaw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2daqbdlmx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ortmzfpn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxzxnvi.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2qciyzmqo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyervgb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyraecqz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlrluts.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2udcjnsta.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgorbemc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2unupvxbt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjsxagz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2irrpxhtc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2owwdemlz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rphkumkj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfosimdo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceenrenk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtogdcr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqcnwdc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qapicrmd.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsbbozz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2optvtbtd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcukfpmn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkrywag.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtypulz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2muoqgdwb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrqlbtm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbikvmkt.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuoosqf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuopxlz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkmdakj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxszjsfc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfmqohj.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyfeigy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oimanzjx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qegrcqfp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuunmyq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzeweme.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2izcezjrk.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqknbwhc.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuenrdz.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbglnsxe.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfsyupx.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcdeeub.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpqkmrt.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2frxfvzuo.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocmgjhf.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2cevjdckf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsctead.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxrpht.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrgrnvh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbcvpp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsatxmp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcgircz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxnvdkx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnuudmz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqkptdm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2safyymsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2glfcabmg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkrriu.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgujzgp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2goeokvjm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pminkcsd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxmwfhn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbkrgva.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvafkevp.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwbvoid.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbsohuz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqyudua.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmfvjts.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkegzbcz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxhkccm.html


<!-- 参考信息 -->