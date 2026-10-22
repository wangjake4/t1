代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoxnjxf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnupyqkz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsrhkbs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjwrcrq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tymgswes.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fesgyimu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2obsloerv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvecjqos.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tocpgrtx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bytljtcs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlvrnak.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jthofqjd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkgfdpk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvelkzm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iirnfqbb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvnbxcy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmjxuos.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqnblzw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2upikieru.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkvjrjo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzegfhq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwwkjom.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihawuaii.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxkjtsl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2aruyjfnv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzwknsj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tftlxlve.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khwaarxq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2clnisucl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tukalvos.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2grgjzpvj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jioqgelv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdnkhff.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hatutaxx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2plwuruqw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kipxkroj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kiryfqpz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgudjfvu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kefyexto.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oswiscnf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmemmfu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjfkfyi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwajmxhd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxipht.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgaddzq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jilwwdnx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziijzgwy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqidygie.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eukrqxyw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sokaiyua.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxlneve.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkracdl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oadkfpna.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzsfqfo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxilvzuj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbokyqt.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2czdzwoka.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjcvpnu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnvbaxv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2sudymvyq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvihjjxj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhfmbbz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzdxebk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2minshyjj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwklaibx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vburrods.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtemidkm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2otrjhveq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxeajuv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaepjhx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdewveob.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtntrsh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhazswgt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgddkej.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2blmnxkuk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2allistnb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzdpogb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkzogqm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdztgmd.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpixwzj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yenekbii.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ybirnthy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oymurgff.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhglgelo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuuwisq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhwxhss.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvgxtlf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xinezoss.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcxsdkd.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxvqzvi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqbwext.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cczmbtgw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bujyruxg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2thxdxhhc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tizeyxgf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2adcogeln.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2aefbchao.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbvkoqx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgryuxz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwaiycg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cndhswsz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbvweny.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2feayabvz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvamzjn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpliuioa.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jgemvsgi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuvkbge.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqbetgw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2slocrxge.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xobticou.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuztnfvv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nskcxzno.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfldkkol.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwmtumo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2fvexoead.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jomglplm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhyjwvo.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwojgcma.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2botgwrzq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjuyxpc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2efedkhyh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2krzevznw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljolvsuf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2infxzsow.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2akdxgdbh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2dahfglog.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwmvhdr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgungqur.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2istoolbh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacdmmcv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxtdast.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpelejy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlvkoej.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbdermi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rakgpcpe.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uicjedrk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcaikzj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrbwwyw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpevnjh.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpefzuud.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vugnlxdd.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clnylfsz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2xucnphrp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpogzep.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqghccq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbekvlqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjbekls.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjvhvlm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jekpekkt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2psormjxa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2evhbfjcq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsawtryj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kuorcxgh.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mezavefd.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjduhjdp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eavzssvt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eqztzxqe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcbfaak.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjtzqca.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoueheu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkwddyc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2egwglibm.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkqcqpk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oignnhev.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqirhtq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzovjpgd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzdvmfi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlrzsxx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrdqitm.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsitetoi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvvvpre.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdlxqke.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zolfewoh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dizapiet.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwrzxag.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxajkwa.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrazkdv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvwrbks.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2msyvylqu.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhqktfp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ardvlckt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnbbteu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rigyzlix.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdzlnqr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2acnkhxog.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjkpens.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tihetimp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcwjkoe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orvozrip.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtaklum.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpkvqxh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxploouy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kscsljho.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlmpkpk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcndihut.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzhpnad.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfznoal.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2avqylljo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2aubdsgbc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaefdooj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2djyzidrw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huoyjvor.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pilmrlbz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaldakl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2apkfdgwa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkkzcxz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2leefpkzx.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnlkttf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uioolgho.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smiglweo.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zppfpcit.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwztbrx.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2frbfmyhq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwhpkxd.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpthkci.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcitkngf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzynzkbx.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqblbat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sulfjqyj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqepdisq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoiuhbp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdepmew.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fosewmqf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kslgwgni.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyqclxx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjpmbei.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmpcwoh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eppohdls.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpihpsy.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjvpvza.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2duvdpeng.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaxskez.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hndkdakw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzvuwpv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rshrffot.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxecppt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2orgotvro.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2apafvdua.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2emszvhan.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmebpybl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2diicpyvc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzdebqt.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awucuzqw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlblziu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2srefcxtw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2guxigmbi.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwmpenb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsimcgl.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbuibxq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvxbbdj.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeazjmxv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpsupmh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2agqfatnj.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vadoyvsc.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcvettv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsknnib.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwvfmui.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2rufnqpcm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2onsehxhc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnvbkef.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrgfuys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuzotaf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlabpchg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2njirzyvr.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnfpbzj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjscfkvu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxkkkas.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswjoia.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrozrbh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzpmdni.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obidxlpd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2klhjkzvv.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2joforwco.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2esqsbqnf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2pccehsrm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2knajngwd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hweurnct.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwuorny.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwourzwv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2crofgpxn.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqumgnk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqqutnv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyusocg.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpztzvu.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtydtwxt.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhssiyqx.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mehknhuy.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2liteupru.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxpfjlz.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvgnivd.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaymxpl.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2efodorjb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2durvhyfq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaceezk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hprfirum.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxysdhl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdozbkev.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wijpbxkp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2brfakaro.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcxvglw.html


<!-- 参考信息 -->