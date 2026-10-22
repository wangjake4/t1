代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhosauic.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2itunzzdy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zugpewwv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvufjux.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2teonjuet.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwolmker.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvbomyp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tqolqsbn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvslurg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikdvmrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhakgysp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aldovyse.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oipdfboq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhumhwy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtgiipw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mgenkhvs.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsmpmjs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnifxrfo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpqzjwm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfohombs.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2blfckpjw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtjulze.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wfodzpuo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqohobr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfasxyl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyaoott.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxdxedt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsrjmhg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqvxnbe.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuxkzta.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qurlyuar.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlhxiyg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2htwreidh.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2imwszpgp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzdsnvt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gquwqftz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2taffgrgz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2baseneff.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkihoptc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2flxhlyvq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpermtqc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrwkqph.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sywsdrao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2htpafqsn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlspkoj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jcctraml.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdwhwbn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeblkcf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeelybqu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ioolhoub.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwdmqod.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2czqlefkk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekwhaab.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdovabah.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbikmbp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsigpci.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcvbpkw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdqgegq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fluzmwec.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yyunvubk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwfwkge.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrfdxfb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwacempy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgaepvc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iasabltj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dylwctol.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yumygmac.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aoojeauw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpyaqce.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjqtlk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fnydmcuj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkazgzlk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbefqbi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxavful.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqdbkrc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmgqjgy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhhaeek.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgfsjim.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjninntw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cizmajfv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pieqdeuo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpazgzh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgqemju.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stycybyy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhzsica.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgikazu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttukmzak.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjhzvrb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyigutnc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydevpcv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtyjiru.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkrgpnj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2alxwzobg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqdgscw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyaupxk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oknnbfqd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mmioseas.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvprunk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vegqxwub.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggwvin.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhblnygs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2autlsgnv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2usjuprzv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgpbnin.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkojlnj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2icfrwspd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxhibde.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxopfdv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ontkhhlp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqwuxbp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhibalgn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjwltxz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2skrsljen.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrgmsnk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bucosnka.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdxmayj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfitonlp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxsuuzp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uydhkwzd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozanexaj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqewiko.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2wapocouu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmscptoz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ffutjacc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsmnsit.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoyfltu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpyqjis.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhmppqu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgmgqxz.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwzwpqw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2synqjard.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjygiyzd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iawefduq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlfiftl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2lznjzpbp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xeohtxib.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzpztse.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfueyfkp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwjtcav.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfccppop.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2yuawsaqf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbosdau.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjevzbov.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2osbzuywy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aeucwgeb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tntwbbeu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2fltyhgsk.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhkudfu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsgiulw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ermevnxr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acoswlff.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2awxksefp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvaleef.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpnjngl.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgqljdv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mexfqefh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkuwpol.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrbcbjs.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmdajwg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2guxdajhe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcyshfz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mherubeu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbpiepa.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtiazbh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjterwhs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrtyvpz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2buoophvj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2puzmgqjr.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvkfson.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzieshwx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2quqdpnmy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwverge.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyphitur.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxllwxk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ophhsrjy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2itqjqlxz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsolmxg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiqodxl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgvbhzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlogxitd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxfmpol.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sajjurhg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmvwqpe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxvprsu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2erwogywb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gikippzz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvarfvk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyfcixq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2iilmcvbl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vktnfsrz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvltxzww.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnhvfuk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaykkrd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxqedpe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bibrwrli.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwinfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeixzif.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhxqllf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2salvriid.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uohgsxum.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvgrcnp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iagxqphb.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2snexkumv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmywihr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoaigps.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eaorzrnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpsplau.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqbebi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbfygnq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfhneod.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvvcbdv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2edgrfjjo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcaukkl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kexfggey.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2oooibtdj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhwqqua.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgiywlx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mwabyxwo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnohmwib.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2emjxdton.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2veuximda.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabcsxbi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyatxfq.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vcinpkbs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiuhlqa.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuvdfgu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzqhrfl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2becajkwa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnkcqra.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvfyxwy.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcriykyp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2izixvrmy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrstxqr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryblbyen.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ujszsjhw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwfpvsk.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2cikgyejd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtwcfkh.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxqoocq.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvhcbsa.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oagxrhcb.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsygrkh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2phgageao.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvjukna.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2archwssw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2toozndtd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjhwljz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nexgohng.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzokaikt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqsqzhg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkatiti.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdknggqe.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvawpfvx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpedanv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2llozvktg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxubxcbg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeprxiu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ongxihwp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ympwgfxb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpzrdck.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mveyhorz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2smpinuob.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2feagcvpx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aofphtkd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqgjeos.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqrlbyn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfusacd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbtszlr.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfbntxb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtnsfzv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dvspmcqu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgjpsfc.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2odusvcpo.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhurhkbl.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzidukkl.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehoouxa.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcryehc.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcnfrpu.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyngtlyt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2yeudupsj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2funltleb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2erkbsvls.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2txoddxvy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjyyvew.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2skgbxgrs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezckpprh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvextyq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zymgwodd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbfcjzn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtjffcv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzfguja.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vazbjlfa.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpdkvvg.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbeeqyr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfhumzt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuavuasq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2jmabvsft.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uotkhgrl.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zodbypdj.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2clmakzyw.html


<!-- 参考信息 -->