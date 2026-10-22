代发 wailian999

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2dekfjrqd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ceibyslw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdimbjx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2upahvmcx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2yasipwlz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgysfrzb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsdmrah.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdiwsnb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwsxknz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwfhyam.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ertqjhlh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evfuzces.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2soxnewji.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpegjyvr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omsscwml.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtbucmc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2satnxgga.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djfvfneu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocixxwof.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyricer.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedbsns.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfguqaq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aulghiiy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qymfiqju.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkrdhtg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgbtjpo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvbzbvn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktczettw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmrfnun.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmgjuhf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfpjvrf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyerehi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnwfxqo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2avuwzpqg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbbiugr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2itrhtlmc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2amyryiis.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwptckp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnllorxa.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cuncxoov.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqxxaxk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljldyint.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkaqnbo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2smcrfbpm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxyudyj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcdfjzp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxzufaq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mygnmbwt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvqgses.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfmyhzv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flyurevl.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2joudszvs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2otnuavcj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvbrzxf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrdfgtk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2shhbiuza.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvowhtdz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2atygclyy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrplqhe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jithikaf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfrdkda.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2duveyjnm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2evbcrujz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsmmqpw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iitxuejy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssccjyxl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfmmlde.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mchunvqg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2susxltas.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2guuspxsf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnykrkn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdctisj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkebpny.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jrldvnjz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkruoik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsyrkcb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxklhpvu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnefksor.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2esmjvdes.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnnbury.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdtqxms.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyjijxj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrsitav.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbhuisx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlqsydy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2etjshsuj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdawvayc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2updlxcab.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mejjsysy.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zicifsma.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbacheu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmsmwka.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aoneeftl.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tbafkhvr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2huakvqaf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmjwtyd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjwxtpj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zumwonap.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bshpexxi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxfuqrt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbhomzy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjenxii.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bykqrdor.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eybgbydk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxswhoa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxokochl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwxyygu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqycwswh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2azfndzsf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjntbmu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzpscps.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvomskgq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2swdzeufk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbadcoa.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyogjwoo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpgwnae.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sivtfjvk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gchshyov.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwltizvy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrolwdh.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2twzijxlt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmdgyra.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqohikn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cooxyzbj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaekfdp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2acqmvqpn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlyotvz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzrtcte.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuauodl.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2znpbxsef.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyegguf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2arwvkagj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2frvxaqby.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiqtkkb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbowaqw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2swinxmkj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xkskktph.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sizbqzoj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoaqmgi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgalbohn.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rattcpqj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2quzofoon.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfuzhsk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqijnig.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacdxjaw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2aoipypji.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgpeydd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vceytboh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fmosnyrj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2fppwnuqk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktutiofo.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaiwyic.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2poldbvkh.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmilnzcj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2eafuykvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xokiqsdz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsnaqfi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otvdsyst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzltzdt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2roanjcxq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsigkopg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgqwzls.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvsjnbr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgbvzrb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2slnrqkdf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlilypti.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjtdxxb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrdgaap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2webeqysb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcdfazu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2iebfogoj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsaeeao.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dlluzqse.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxciscoq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkskxbi.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbhurxq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bchjajiz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tomembmn.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqldgihu.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsoarrq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2klpxeeqe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdynizf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlrsytk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrybkrxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsdympf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ypduljbe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfsensp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgykudl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2trrxicep.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eodfculk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyxxtep.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2unoiluol.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsnobjf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbhhbfv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbogboh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrzszpq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhqmgmx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bidfqilj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jegicbhv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2myqkafzw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2faukbrtf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lilgmqiz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbyacep.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjkxysd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitpqsgj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbcyjew.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcidljgw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2uklnfpgy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtmhxwc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2dthqnugh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsqkecy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntubxsko.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2arvdnjme.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvegelrp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkjhjsq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooormwkz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiymrtax.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyioacg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnhratk.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmpoows.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2utlsnmhc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjbwsek.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnslmkz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsxrlhf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbxlfcp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmnfgap.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnfrzlg.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiclaepz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdpqyct.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uswwsvas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaovpkk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbpyezb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kafilmtc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irgdkslr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtgxwuy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjybtjr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2crxsdufp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxmhqsp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mgojuarp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2psafsqvr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xawqhgav.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2intwmwkx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhihxrc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfjoawg.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnvcomp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcnzrbs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2giwzqbwt.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wpepfxfo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2keryuelb.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ridsmynd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibezpqvd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpuojny.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmmrxy.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbnwxhg.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iveubvej.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiaxygf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjghuyq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izzsukol.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ltugulzg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2laebhsxm.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqolaoss.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uduvikxj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2periaebl.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwvzskq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2sypagnaa.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tviqqiwa.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2isuikctq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2csbroqxq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzweyxkb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2sambpqeq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2obfydfpa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntywcxwu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2otrsaues.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjpawdr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaitxol.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlzitmi.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfjarwg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssegtod.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhojhzol.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2korrqegv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2miwhcjxg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiwuqcf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2guupzhjw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rngloakl.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uswqngfz.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2aebasjru.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2swougnbv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyysyar.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghmzpta.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmobesft.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnurdsw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2favqqwee.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2efosmrux.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyamjexc.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdipkdm.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubawvas.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2abygeyhv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2empnoeij.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgizrck.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdnfcee.html


<!-- 参考信息 -->