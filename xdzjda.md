代发 wailian999

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vptogrne.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcfmlvg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrdrfzc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2laberxgj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyhehwl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdmprai.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zefckrwr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjedktzk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2moxwgvxw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsskkgz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpappsa.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsmnpwb.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjuzww.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwoxqpa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoqqerp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zbltogdx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxwlbrx.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhmcqrc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrfcayc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2obkcjlny.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cowzhnua.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2twlezbkh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2caakrabd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxspnxq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkeayns.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxgtobm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntglnxdd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpvekhr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxtqeml.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfwwrwm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fytjscqv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xecvjdxv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2raeitdyl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtnmexn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2isxecukp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzavrzbd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtgsldz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrbghqp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkhqrqv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uefttggd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkqvmhv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hprjvqli.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hccwkzma.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsxthly.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdxwpmz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmskikw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvtsntb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpftkyo.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zseppori.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrgrpmf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuxmnut.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffzqrbq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozofjmsf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zocrrofm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhnfuvk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qctjhxkj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2msphcvru.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwduyqo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtehawns.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsedpdi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtlmiwo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2psrkuopr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2umwwayex.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpwcvfm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtjnmws.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlovopoe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcufditb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpcyuzr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueussifj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmkjgha.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rerqajpl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsyivww.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjrsndu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2omatpsbv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tabiujui.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lihwfduj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnqvesh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2astzktri.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2axdseubg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzrqtag.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2okjafwga.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wylnxfoj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uayzeaty.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmczvqh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2utisqcje.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vukqvufj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfjayga.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmcpjbp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qidjvtvg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdbflwe.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnjaxnm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gswvczdm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbywvkfx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2syqegnvt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvyjuzf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuxuawh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2slslavue.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkjretv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwqzvvm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdpvefh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obokctmg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2irnuxfmq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlshqeci.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvewmk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ircyjenw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2snikejlk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2squismos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhybzrd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2csakjzwh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdvhank.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2haguyfqf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpitoqa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tybxpcdg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgakffwq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlpxxss.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkehecjb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2apjhqvmp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqiorcf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgdhozi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkfrpky.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vorxjcox.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyemwwxm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgndfkka.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdyrhkd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eukoxtgl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pufktpsq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwqtowj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlymadc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2glodhlbp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbwkcdy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszumcfv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nncoxozb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdspbeae.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfonugpj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwsdplu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuzrgul.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrxlxfz.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2txptbvkn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuafzts.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2klgxznbm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyritku.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgskjjlj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgidbyg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmofshmu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfeltss.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2iajhrwsu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiawbnff.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jceiuwvu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkcqqbr.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fquopjvm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpvdylw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcirbsh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fayyelug.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpykkkv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsgoqzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzypbyv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhniszu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkegnrud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyavfwhd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbyaumk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvbizjk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2solilrcu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2hddzloxs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyfceur.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcjouml.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvcxgmf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqwfutx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsfvuzb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrfqvkf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpzrrfs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdgbzfb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gujyryzz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ieglacdy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kaitfxxd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umvlvkax.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2doubydqm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhechhbt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnjhvyh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enazbwmm.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiidehu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2twxpswwm.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfiktdx.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaueerlc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhravhf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nljuolfl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lsblzujt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbxvfjt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2coumiygj.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwefxhly.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zntplqtk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2upagabcp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mykeykxn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2sldggwfs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmgijqp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhiyhti.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyczvhi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eujfqovv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiixabi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rmguwsdp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxsztrr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlcfhfb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qctusoyg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tudhghzl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2osbuxttd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adzhdnzo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzorwib.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcigxotk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpminmw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgckzjqs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2utlirrbj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fzytemat.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjjnwmk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mntwpcvm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmlfmsm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iklkhirr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fekstqnk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2irmmuexq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxczgshi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrnuqfr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avgtuxee.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcgesoa.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjteeqd.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2npbsbgyf.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaigzza.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvshnym.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdprjlif.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xieqbofr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2invzgzfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2damokmts.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2upocwqeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnpquod.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcubjuma.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xhekbewy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzupctdb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fybbjxdg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyamxioa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hriawxvz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2svaszmjj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2duvbrgqo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2obnfwdcl.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmrrbgv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hxifmdwo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hngmktrt.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmvjmwx.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obgflinj.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnkggrb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2puddrpqo.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqmlhot.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrztogng.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2unupcjeo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwgbjnl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dekqnlxz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaoarod.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnunwpsb.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqvnpvc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vsndwfno.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqbmpaw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaiwkxk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkcqdob.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dccugpsp.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhffyut.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jikixwzg.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2elnilrul.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcypesof.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2spymrola.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovupgnlr.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpoypil.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yiebrabl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgfnlgm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2selfnkfp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqhgbwl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhxqxvl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwzuymf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2labxzfao.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrumhey.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qukslyyt.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkipzde.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ennyhzss.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiktmvk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhdycb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jomucfgl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdeaipj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhpbhmh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbhpkji.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwifvffm.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwzmvyv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpircvb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xktwfaby.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkrapmq.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaagjpm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbbvdng.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnhhlin.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2snaknrof.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhknrxy.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pthjmoaz.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yepcyjth.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhbwaty.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuebxdlf.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndizqgpq.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uivitkjd.html


<!-- 参考信息 -->