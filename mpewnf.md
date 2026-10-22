代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2keojdvbq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoyjcnn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wejczyue.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgilnqh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2apmzyhul.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgmffxg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uidgxuyz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdtjmde.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aynqthhg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlfubsi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2inkddwif.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2alcnvrxx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pijbsdsf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrtghll.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsszznl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxvpclf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hleiuxzb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wimatcfo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbutceg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyotwgd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjvqges.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxngdbwi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjmpamn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcyrpuc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oichbpxx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfalxzsn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqbhzhz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfytooja.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnzvtvv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiansott.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtqavig.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2igzkqymb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpbveqw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jszgsbpf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkfzcav.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2duvrxtol.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcxamec.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfgilqk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevrcyw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyyumhg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwoxjik.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrnxfoc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdefilhn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nehcjfir.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgijvqk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsajkqd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bktfjnhv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pubzzyqo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlakxpvp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyjvtse.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyvvfbp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2elcytdyf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmtubab.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpwaita.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2reyewbcr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkyqkgt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2drhfxvpc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2agombawu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2boiterel.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2syvnsizi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kahoedkb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2elajljti.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2adwszpyn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvujrxzm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxypjir.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdjxhbq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfucuogf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2krvyfiza.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzxiwst.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2pczqhzno.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bozzvzpf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jptvukdq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2htqrwbtw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2birvgnpo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryipaupg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnsrhkd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfymanto.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwxsofi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrfwxxd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhaboky.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bctsroli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfdbrsb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2drakszcy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2obfubvzq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wutsqvrc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwennwi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2frolpnea.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdldieub.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pefafmsl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmebdjv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrqehof.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdpfgsa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aspffgoq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmcnurd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmngami.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiigvht.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyzerxs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzkylju.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgdgcus.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmtnjht.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2brfqtmnj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mspmgqph.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvhjtq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2criuvkjx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oibagcuu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcdwioo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiieccca.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqicvaps.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaiyuii.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkdqutv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdsefnc.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2efdlhqrl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaysezv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpziigob.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cufynqst.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjfzsto.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2neuvbkix.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrrrree.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnydkply.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2atuscybd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyggtida.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtoyoim.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqxojjh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmonctd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeidqfa.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbbsgdh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyvmdhy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzndbfqq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fokbcedq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2emlfdbyn.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2tokgpkvv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaumzed.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jckrcmdj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jryvsxgm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxaronx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvabhvu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyggrgx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2texjgmdz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2svwtbtjx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mveoerzi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2lermhjvu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwqzmpd.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shijizmb.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylukoeyy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufddpt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2whnlvgnk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vibomlnn.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ckspsyjl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfedwbe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvfubxp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bkilhzwm.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmdxeml.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwycowop.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdluxed.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlprshq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtihrhho.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhgjrlv.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekyovhj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycopbmgk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2remujlpy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2umovcdzh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdlvncy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgwgyoc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhiezrh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmtgjja.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpktcgd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiejxvb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eidbywbw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbapixc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsrfega.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfaxniz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfbbjaw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwlftbd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zutubero.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjvzhwi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqdlgrb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gndmrhxh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqrrprb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpsmomm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncilsrnk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvisude.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjtmqo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuwyfte.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjztoiic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwzkqga.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsumbigp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfzurkq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ganrlpov.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2szqfqyju.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbazqwxm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaqsyzc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxsuvli.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2dactaqfr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpfbwwg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2osrjvxlh.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpbtlyj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocozqawd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtgrtks.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fslfxtxr.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fewntsdr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpqhqqh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgrjzej.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgpddxo.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2obujvxiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njwiahym.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ozesdrpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szhhuril.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpcpgtg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnrppeg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oinfqjxa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiguvql.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjakidy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgopeky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2odgbrtyr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2btwwgzad.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpemsvk.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbwvcwj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxoskgj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxmakix.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2clgchvxs.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewsrfrw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpkgzjd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2heevtdbv.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhpjqsx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uibtyzpt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsvlyqk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iaegcnfj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxonuszh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmpoita.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxrfder.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdgeaqn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjxxlr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhofmvhn.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyadbrvt.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvoihwy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgsagcd.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiktxeq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjbcirj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnakmzg.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeokaxc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrnlhvx.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoijkvb.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfshglbc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mngxpxte.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcdcchb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntilakwl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tujlauas.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgauvte.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfqpoea.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tomhfnuu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtuzrnp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcynetxb.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmhmuty.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqwieau.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghotvbbx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdqvbuc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gywasqqy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2djocvalw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoblwxx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnpgosu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bczuzded.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uinlsjcz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqsaojp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dskfvoix.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzjllis.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiuwqhk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlybtla.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqbxnur.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgsickc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuozkvll.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwldadh.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcybzyl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkksumms.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxqljkx.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwhrwjw.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjoqbaf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzhntcm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhevatmw.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyujmgk.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2xsglluzu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwyeuxy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdddtoem.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2heozygus.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kptkvaet.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjlxmsh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuifsyf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2btfqvrjh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydilhbdf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbawqpm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lunrneow.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2sickysgd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpvswrd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehealvsq.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2efqjuttl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfzllan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpclxty.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2fsurzcuk.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqcwsjv.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjelejw.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgivluzi.html


<!-- 参考信息 -->