代发 wailian999

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmcldcr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2udjjmcax.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpwolcu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2asvvxobh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2geduyrkl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2phfwytjs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhsvaz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khtayyea.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhloquw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2roffpmbg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybchaczt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvnkuph.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyxawpy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xckngycn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvfrzvz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuykril.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtokmiy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcyfvdb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbumfqm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxglohrg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoblgmv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbfvmus.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2voyhnfpt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2obhnilbc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqymaap.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxmiiuj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtdddml.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2heolwjbz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtkfuxl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kewjjsmo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcugjlv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2erapjsng.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfnxqqg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwusjtsx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxmdxjl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspaoect.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvckcje.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wssnqlwi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lytdtzyt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbfdapw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgxmeeg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuetakd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpriskm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyqlfwe.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2axpptvpu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvazwda.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcezbjnl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyljbef.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvivkjk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jurfbbdj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fmchfppy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvynwas.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrerpkd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2miouhaum.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbgjkwe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzynftn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmtided.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdbvbyd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2popwhpyj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fngmcvry.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqpixpf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvfhas.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uivyjfib.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2asvuxlhf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgpydmk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiktmyza.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bffiahqk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiikdftx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbryflf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkgrtht.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vimmchup.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfadtrpf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlifqxw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2glldhxyc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqxjopw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwvdsgu.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2msrtbksf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tncqfqlb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2krnymywd.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlobrwnf.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpepblwy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bybzmqqg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyzwtjs.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2adwnsbeb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqhtbsp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jatxqwfq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skhjxcmv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdxnxpo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2krigirky.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnbkicb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vesnjfaj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhtwmsz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkpgkyv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2agdicanj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzquojtw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppidnesf.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqabvfsc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhkewxd.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxgvwbk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tijtrarw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qusqsyjb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyvdibt.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvyrgbb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tsovgxyq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qlphhwls.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2skluhimf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nznqehag.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qomcjtid.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jogdavpe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyoxiqy.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzjsdis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2asjcuwev.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2orbuzjmg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxaqsel.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuqkxps.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmfdisj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnphzouy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2uszjapmx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2olhxokuy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2audpofce.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnlizwn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrsvdao.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2igfhrugk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2abgfqyan.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xscqarvo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvjvvu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2moritjpy.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlmhovb.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zmryfgwo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kgygyagw.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgqqsvm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bftzcuvn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfwruwp.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmccukjt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwnbigc.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kplsjfol.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2glmhgtmv.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopgprly.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yydgcpei.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2atuyremz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbufezh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpvqwxs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrfxagb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2naamrmmr.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2icubyplf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezygymxm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwlijex.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnrfgwe.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2edttypbp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2klxnmtma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2okwoytzd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcymgfod.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzufgrhz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfawjhmw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqytkau.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnbtwbq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrkvcfi.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbefcjq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2opepdhgk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpionxso.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mikvlfto.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyhbmgb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmysnsfd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlryuqy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnydttx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2rovcorzw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wopqlhkq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpwmwvr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwzjsrz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huluzalq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmmkgjh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eipcfehe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqirwsbh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxamxvy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amszjdpz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnzlfbj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwdugwe.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgahxkr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmuhdvb.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wddmabex.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxidqwr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoipdwhq.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsvxsir.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivwclmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guuerawq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdshhli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruekbghw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjgjpdx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhqqfi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoetlaco.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlijvhqf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzumtpla.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdvrpcs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzroekf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwgibtb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmvknvw.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2weqestox.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyjdwqd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfvjpvu.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzkugi.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewskbpit.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azsclito.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwidfats.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvnbps.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2glardbbd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2teuyitdr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcvnxyq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzctvwfy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwdylqf.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dujascfv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2orvmdmpv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hqohbyrc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2phjdcbbt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ansiwrjb.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrpoowv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqduqut.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ledubsrj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalnhejs.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2skgxfiuc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyinmhm.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtinxls.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pomtqxhc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqoergn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fulhrwdd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wahynlye.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbpyxvs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqhozps.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdpfxqx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pescptrh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpykntgi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrluzxgl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2yulxfopd.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssubwwfv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugbvpoh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtbnkxo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwvvoee.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwompszq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2keoslkvo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unuudowp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bukigjey.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdvuqls.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2iokgmbzo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2abtzodfx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2decztwww.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kksxkvid.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2opwhmgwy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cflrpywq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyozbxil.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2cptfxcie.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbmbsth.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sabtdtph.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcmioxl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2smmzrxml.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngjckov.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pticpyhh.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqydgezi.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkuiynb.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhexymbg.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2iczxsgnu.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2cqihpttg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arwmuqxa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2slbmgznu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftrsai.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfxehzm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hctnomfv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cccalybj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhptzplj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qchhyjja.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkgfpbl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbienihw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtpuaix.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gslhltnc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpygarjo.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvvdabw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxabgc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2eovotrix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2knbyedsi.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvclzdci.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaugdfw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aluhuxlk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhobckn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqgalaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgtjcen.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fxksbubn.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgujnsn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rcogeijw.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtbflua.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2urrodpgp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2qipymnuz.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmtvdol.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gojuhstq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgajpbz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjxbxzm.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpehpcj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2goisdxod.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoezxdp.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrqnapw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbahcqru.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqxwxoh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yflaunnf.html


<!-- 参考信息 -->