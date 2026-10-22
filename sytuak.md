代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwezvpeg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhizgnv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypevoqxa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaauqojy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvxihat.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2klhhvjqf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hziueqqp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiqdeiw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2shosxvyd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzlwsjs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2agyktsfy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrulbve.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrvhblu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wvulaotw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqrjqzl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlzeuar.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nchpmiek.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvdchyz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2usqmwryv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrhbtuo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyqxtsx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uztzegoz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2igcvuxhe.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2apjtlmvs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjbscrn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpzlzva.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2baqxgudf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpevjwwe.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovugcih.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvjose.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2omevqxnx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zeglyrby.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpmpvkr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nromgmiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hduydwxi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qokfdzcq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcktawq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkbzuqf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqsccej.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwwpqql.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tysmccqn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxdalqm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rumgvqut.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtliucx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sijaglpu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2eutxljbv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhbxnlc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkzmqyt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqkxxdy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oanovipd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2eufzxmnb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqqzsn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbyeben.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdypntvu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aodksgpr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbonnlcl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpnhgzx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2frfrnpdg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjewfzk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cooqseuv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjfhcfi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzlgvd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dimmaapk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcjanoj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjpfjvb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2btvcmepz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtizlhis.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzmlpgw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcffokmz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lmowdpbp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2laxfmsrn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gssgtoft.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnupqmyf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvutqstf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcwxute.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkcjupl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xayqdasv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtryucxm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2anbagfda.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzvbqzc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bruogaye.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvpeuxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmamidn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnsbaqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2srpkaxlq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsgpkbx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjqojpb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqohxvf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2khkwguqt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjzafrs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efzxocwb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbctsskw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aogvyepw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazhbyg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhyayxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gepjfzpt.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzulyza.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2czptfxkf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvqazxl.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2scjzwmcz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2owyqubjp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkjibpw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhhmzrl.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkamcnn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2slmnzhog.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqqthfa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmjcddt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqsqfhd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cldxlikj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxonabhv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2piiztfie.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpmanag.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2stvumtoi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdejfjw.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmprpvk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrnnjoy.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2judzdcny.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtobmmj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwalttv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eygggytd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsdakrf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2myzxrupx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyhgpwn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsjosuh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyeywha.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtpjswz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcptwtgv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfefalff.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lahwxgny.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wowyicsv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nghnigte.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2axymabzq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yixmhgke.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqdejhq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uucohuen.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyimngj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwiaosi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2yadhxtyc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2spbulalk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihknbfy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2npfpyaby.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwsoheh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxapgas.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnszhtb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hjboqqjc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2opuxtlyw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2joeuydno.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnfhana.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgkouun.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmusfel.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dahmedms.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcefxkb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2foqnrlsx.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjfmsnu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrrbazs.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqdkswl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmcvlcc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjxchxb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zofphoaj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyktmnf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrhcto.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tekowztu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qscvqxfl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2cejhmvly.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2siaxptks.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxeuvzh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfaesyu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pylltnzg.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bnambmfu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qivryfkc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvolekij.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2weveoeck.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaijhsoi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2pguwljrg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkyahrb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2sffwxagy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqvjfqr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wobwwfbs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwariwv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeloykel.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmdompq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjwuzha.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxnifpt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbjfnjx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkbfjqy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvtngjb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2apmnifpf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2owvwzxgq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2djtsyjna.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoiitxe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrwazov.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdldljgf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2xircwccq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfrnqxb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybfsqxv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhjpkvw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2soawhdmd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuyxhxh.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2umcwvaok.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwuyjik.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgusyzwo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2urbijtdb.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzfmual.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2krtloksb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhfkwzn.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zokyhsnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ceacyogo.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyzkcjq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kuofzoqp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xopbfptb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxdbmlg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2whbazwgt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfgigqk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2miqpcuzq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqlwbcv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2izbktyzx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjgouwk.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkzoemz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bygaukaw.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnpuyfo.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyaxbsu.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rekyomko.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuoofxa.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhqrpln.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdnkwtn.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2toantezw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2esbllglx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioszvfeq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnqhfgf.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bumnogsx.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2spqosbmh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ximtgjzv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyuhuii.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkgfpjt.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsilwex.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoywqbd.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgckprn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pexxjnod.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbzdixe.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2owyhqqgk.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lohhvzbi.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezajepzp.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwthcrr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuajkyi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jujxfutz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryegfbxw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnszgpa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfcllp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojegnuct.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2orvppozt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgimxbb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqehutqs.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wommowfe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsuyzlr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wftvyhvo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvuyjbr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsjruhm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyscmsz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcczlnh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2arulhnvp.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhlferd.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rcetzvmz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2cidaqdax.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdskdxdb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfrvlqx.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2skgzcobn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkdxcal.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nupiwlwv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2sprkayci.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2booltttu.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ilapstvb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvwinth.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyohnpw.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuychqi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iayhmgvv.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbdfzlg.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeswvef.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmnqfko.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvrpcsx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2mlalqthp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokyunjm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fevuliny.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjnrdrx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgrsizr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcqrmg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rimwnpcq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpfxxeg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqmrcch.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcqntwb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeosteo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaiisjo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mexaqdvk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oplsipoy.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnkrlj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqkxine.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkathvmg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2eheeikby.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtrybwo.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqjdsjd.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2skmjrdnz.html


<!-- 参考信息 -->