代发 wailian999

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrrwzjs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhofagxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nreqhwrq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2laihnjtv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsluxhj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2neqktbzm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2naelijks.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iizekqlq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezivbvqv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vounqsmf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaajfoi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitbbhyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbueiltg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2foryavcc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gonynesh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2newqfvei.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxinptd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaonxex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aobduqje.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rolrlwni.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rbogimxr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpgskmz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwtfmqj.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zttjpgbh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjrttfg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpytwblv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvolmyxy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ffypmpgz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhwatie.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ythofsnv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eirholbv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2egouzmpt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nladyiea.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpewpwpf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaebwno.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqhivrg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2revmhokn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnghhxb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvznkrz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2acebsotd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aakofwkq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbvelhj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiegauxe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdpkgbv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlhihgm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqjrwob.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbbsrkp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjnzbym.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdeyeuf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtguhdnt.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwcnziq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpetqkzk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfdfqxo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jfutnmcg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaydbqau.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrnghxc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyapkpdh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtwpqwx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbhcrmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgpvhrz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznlqkdd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcpkmeh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoaqwpz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpgpxvr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhvuaco.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2styzidaq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qejtwrrl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zaupjgjy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhncnsd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjaxqtm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhgsrjn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkagvk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2empbnyek.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qytgvrxz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmpbhyu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rfinadbx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vogjghkv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2putdjuay.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpboqk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snenpfpm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlnteny.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtvheit.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrkyvbm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcojyxf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdhtsve.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwzipku.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcprohpp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcjvksp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2blnvbjjs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xklipykd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczuxczr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2clliyuol.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrfifow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqcqowr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfjbchn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvenafor.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsobgxbl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeulfdou.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpvhjsf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpamdxs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwvwwav.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ineedkgg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwagkke.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrenzkl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuiablk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmzqlql.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqatldeb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbxkqua.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wltmtspy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qopajlux.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmwozuy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cennoukw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wogqelqx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2klyyeqew.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cspdkdfy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2emjlqnwt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeocagm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfadxfm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2maaublte.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvzrici.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tndnuqvp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmunbvpa.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtfqhbb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgksfxj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2soegwvjt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgolniuv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjwyhh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaewwzk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pumlupfe.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsdaoke.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2kagvttnj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpiyxxg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlqpfep.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrngfvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2aphnxvvr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2exlxrtwm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bftifmzi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzynwxq.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gluelvhv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyruvvbd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2panjtebt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpowvnd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mobmnmcn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2cukkuixv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmpidzb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdajysba.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnwzzeo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqmzspu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2trfbewxh.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdparaen.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2diakofjn.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqcrukz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iacergyn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2egvjbjuk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2offhmavn.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2guwsjrsw.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jaunnghz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqppxqyb.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uanapkqu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2slmwjyws.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fimoewey.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoccine.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btzrdkfv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcroqzxe.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfolwhp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmfcnfy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmgxzeb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2afmjcnwx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxqkhqf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hezkgtpb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeocidi.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2kedfcfgf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsyoaje.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cezrximx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhcogwv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxujjxt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ntobrnzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwburc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cngqofrg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkitmrcs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpevmpv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbypkyrg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgaymrr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2keynksfd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cneaahrv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrtshtu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dykhphbe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrncqdy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwrvitx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmuyruf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmubigsr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sovvqlwi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgncznq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgzvydw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2byvjhrpc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbfocty.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjgwdpl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpyeavo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zopbqssc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoegjfw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlqnoqw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjirwzby.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rimrpxgy.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxunebyw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvawpaq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuelkcl.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiswejdy.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwzvzjx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxlvynj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuvjjlb.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxiumnk.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2amydhrfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyhiewg.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2swfftdnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwjdyxs.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkaeniz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhnuolh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkzzlqk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtcvceq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcatwnbu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wphukstm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjobqlcc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2pglwsyki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2otqplgxl.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pcguzbqb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxswlzr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yviqowpt.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obitfidy.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2euinwqhr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwurzhc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knisoads.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmmvphl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwgvbbb.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnpcyla.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqqjqbd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gblhcvtn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiklwdhu.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxvwgzr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgsfiua.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jazhpxzn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeadkct.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukddrzwp.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2krdwkmaz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vipbuyph.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqrweyc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nirexmki.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2grpfzdyd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpazupe.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvxewvd.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyefzly.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoruzet.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2brurinwl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fetgnnra.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptokmusn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfnlryj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbfmgew.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2glbowdbm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2exsqhhdo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrmsxeu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiytokfd.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ookdndpz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgvktga.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooklqobx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbyvjqz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbpvfgs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2odgyrgzh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqhrcti.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cojyumqs.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnybpxj.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdoghix.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqybfak.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gondnmvc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyedaup.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxmopyf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2scyfzjfz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfeyshe.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovdjjh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmjwzng.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhqspnw.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzftjyv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjimzyih.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsatplf.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlybridk.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bslqivdk.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmdontu.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2exidfiup.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhmblus.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzjftav.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbqmibb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhljupdz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclceoj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjzjue.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2izctpbot.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuolgpez.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2khqeyzzk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnubqqgc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2bmddqtst.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrauyug.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxdykoh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iigzwjwf.html


<!-- 参考信息 -->