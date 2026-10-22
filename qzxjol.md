代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ekudinas.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnyfseu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gscjwinr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2udvwwsbh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrazvag.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2webccfao.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszfkafh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuoqapf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bunwmddm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiyskdr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiiqyjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2spfouhzy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2svastqdh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxdsqdi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpjrsjw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbbadzp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2znffagvt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpmezaj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwforkcj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hycjmmje.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyzkaze.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsswlwy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkhfkiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfbjetw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcqlowo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbmurzh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bhptthyf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2stdjujhg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xusnyfzn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdecekg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxkryrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnqjyai.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrlewll.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rihnrkgi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jymtxdjo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkhtcat.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjuuzps.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmktwwse.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtljshoa.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oslgrbuu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hynnvotp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2riyfjdrt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeoawbs.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2khubqefz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yiletyjt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdghshvm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqocoqi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucebxaop.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2txintvep.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hszkdmsc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyokgdb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxkxwvk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxebvrg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdbvijc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmmyhye.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2knrnzuqu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2igvwlrsp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdmsdim.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnpwpdq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2trurfvdt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jazuncpq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpobnor.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqzgbcd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2msrnesab.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qexgfeqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dtibzubw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2exxlaknb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyomatl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lscucvrq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrfsbtu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2plprizva.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sedtxfte.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2siqatmgt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqyqlxw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxhbuaa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2edfyjizt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgxxirn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jsitdhfp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2krysywjf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdemhfj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbigppp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgnewel.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2utfqyodn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcesjgeo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyszepb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnsoqqd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2javllmxa.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nybebcsd.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdqjfhs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ilipxtzc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdlcawq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsodvwo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hloyesgs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tplrmmlo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvyaczg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxnesti.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2armleyvv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdkhrzd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrxudqf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wezxdxry.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgusaus.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhsbdd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjnmqvs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oogpuinx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ooabxwar.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirjzgcs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubtbum.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wojhmrug.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxzbyti.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rozkzgwr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuytvti.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqeucpf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwaahev.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eflfwqum.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcurunh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2swdgbkbz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdjvsuc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwakyclu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlndeye.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjhhmkq.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmfkohl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxotrcs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzlkceu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2whnjuvrx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lykwwmfn.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kukcayko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mokpdksd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2omntgvol.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hucdmtqd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzwdsgm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdyzupe.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2owadtpmm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvfkjkq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiygckwt.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvntjtlk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmacbvp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyckxeo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2itdmnuzn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtytcomi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlkbgjl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxqeipa.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgdxflx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2toovaefh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tveuuzwz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2brmgbnmj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjdnen.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlixhfkd.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbrqzhy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrjqljh.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbtaawt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrkqdlz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdimvhzx.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2slxtjobp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flikpvyl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeokzpc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkozqjs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2azfaciqc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlxvurr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyvamcl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2grmximcw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gckubygd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhgieid.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpcelwb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlxbqek.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2szbaucno.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlodfwz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsfykck.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuetymf.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2rilrzokv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqizsvu.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpotrx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmlihbe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyxnkuv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmqknli.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwvvzoj.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcmmqjh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvafbim.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrcjias.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtigrutz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2azgeilgm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2boyitlrx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kamdzkvu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsmyxbk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2oosjlqmo.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2huyofygv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzraxeh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2opobzxxy.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwpeqvm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rhygfeso.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hamwyfgj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2boihjels.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzctgbhv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvmtmac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2luiobsre.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eaubizaf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkohyye.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bopqffme.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ccppjtwx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzovdqm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oycickiw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmjbfsy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aodtyrsu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeqfxki.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2stmssgda.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2isdhmpmf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjnyoyr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxrvoas.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2iloanewy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lepeavwx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcvvvuh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaaqril.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnnsbhh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkzdpcj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abjudsao.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxlksyo.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evnhsofi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hglsxxpn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2goerpmom.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2benyexkv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aanjhnmc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2utwzbjha.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmujhrrz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2acymmuwu.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlknwkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlwgjau.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hibxbkep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpgysst.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2diypxemd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnaryc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srmztiee.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiyqhwa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nowyhpkt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lodeuatv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kavcbfej.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpdqyge.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsldaxr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcsbkvk.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ispnzyav.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqjkerw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgihqetz.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2flowuxeu.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukypndko.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeiqcog.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrlmjpp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrnnlfy.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgesqxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsipgvp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwslnhda.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefnoxic.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zckoqaxu.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnadobd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpkdhtp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlfskur.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2breflmqk.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2eckazwnp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxifpygu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2jarxfazj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgqdstt.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqzxdsa.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwultzq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2amegjuoi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfemvtnq.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyptmjaa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2omkcdewq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrukujy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfifnxet.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbumvwoh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwsjqdy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pegajumo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gttzdwta.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhazvzh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdrizde.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cebzohjz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzftybmu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbjpcjx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkhciod.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmjrbxw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfitfrf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfrnrur.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhjqxah.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwxlysa.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsruujq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxqpzbt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjhjkwr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iruhhhjq.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2otkhsbdp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhbghkd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikazanfs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2audmwnqt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnpqyqh.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vznpgdhb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhevgteg.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2huvjgoio.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhypkdi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxddcjiz.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjzqopw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2usazmcvd.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzvcygl.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zudwesyx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2lietsaqx.html


<!-- 参考信息 -->