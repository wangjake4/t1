代发 wailian999

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfumuzno.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cestsqdu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zylysxxx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpjegyh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2beujbqsx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2phuchzuv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kleiuuzh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2einsnnsw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmxjslu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2beiihkgz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjslxpe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfchnij.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mllqsqjd.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hmopookp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtubloft.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdzehuq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2utuxxpev.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaugloa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffckssuf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2npchghqm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnrykol.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvsmqaq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iucezdke.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zthbctgb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeldzak.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjdiheo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2omfxnxit.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfqxncp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2npzqbadg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgpnllv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2afoddlqt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdczvlc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzknaza.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcnhywq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lthadysb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbitryu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tibfdifa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2anruapvs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pxohavul.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nacyebki.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgnopxv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2veqqfvso.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkefdyrz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxjuxjo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdyfvna.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqnfalc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dixpuhtj.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2goswcoub.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvsntci.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxahmgfp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscqmauk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwvfzpp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwgdgbs.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ecykqjnr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvngecib.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqbega.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aadvxcmn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnyukkw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbnujhy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrssead.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xddemhyc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hshbjkzq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuiaccz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rigficwe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yncihvco.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bpilpirv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwelimf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwekxmb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nootamzs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehxjerm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sguaupwg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmywhra.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2prejoayp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvctlld.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbukcgr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsfvpkz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiolzcq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzpynas.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xibdwvqf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaxdjvj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjvlpdd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqepsfcx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mswfakxf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ltczzqyw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sivcovoo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqicgde.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkyuqnf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfwcbtl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdwthcx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhvhyru.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yemtezox.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhimjmu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bufpcmlj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ireuxanb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2eepxarrr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuntpew.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrgsdzd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrfcbet.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixwvevp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2osyvszre.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bhclawxp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqngrnd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nafwkvxk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjjdpih.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmnrlep.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nikscwzf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipgyrlq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vugvevhl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbukjcm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tactxenx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnsjmrn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyavpzga.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sesjzdpt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxpimry.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtsgqdo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2psysycfp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2trsnqhhx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfiokwc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2syufvlfc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jewswnyw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pigwjina.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxobyeli.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mncnnhrq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icapdzsz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vramurbt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eayavvmq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdbjfxj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbyemoc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2noidjqyx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmndmhss.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnyadvx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2admmxgre.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snkzanvr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxlwmun.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zstftnch.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2aghybjtb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycdvvcn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcmpaog.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlnrzlb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tdluwvdf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zenkyfmg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwjkgpa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvmgokm.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnhndkq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxijpzi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gensxbdr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2oaouokvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmgvexn.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gisrxjas.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdupmlj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qalnmpxs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2iwryndbq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2arwojmvk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bslsttpx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuotwik.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzjngqf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2efpoghvw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpldplz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxpfabu.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgrariv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcpoxia.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rldkiner.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdorqxr.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2irmodbzg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnkazti.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwzydru.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyjrodp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuaxdjk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbfecbf.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvynrgna.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obcmffwb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhitaqs.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhvhbxx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdoshgf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgceknaq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxocfig.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2umikdlsu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsyocgn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aipivnvt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2lgupfbmd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2glrvbfic.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yawpaojc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mszmxoms.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsgcmyi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2flfvecoh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoimpqw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstbpgv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgmzjje.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxcfajy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtdojrm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujmgxz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwdiyri.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kybtqqja.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xonznvch.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeqrlcz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndskupel.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzyafzs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oodgdadk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvhofjp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnrkyhs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfacufyp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljghqbwx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsaguir.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2oitfwcdr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2glelgwji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwqihyb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2akqsurxx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqdliog.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2ognzfeqa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppojmaek.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwchdvp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2soyvfqnf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmblcsej.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuekaglx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gotmwhet.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2elzrizlr.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpbrzth.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eveugapm.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjchpbxg.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2swyjruws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utursrkl.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gssopafj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezglwdxa.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozntxoku.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2teyhctoe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiehgga.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugstxhnu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kznwrogc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdhowvj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpguyqhd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuerdnm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gucicpqr.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzjdgcb.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2agjjwdve.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjcieuc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qepmbitb.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxjrkvs.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuybxlu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrxunoa.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2loclmtdz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yarntmxe.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fuylqequ.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvglewgq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fymicooq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2chemrqcw.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikkjqdw.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eereasxc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2cloylrml.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhukuhga.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2snktapsr.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wsonbpsm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfcngdx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnqymrl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2heduatcq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaccmqw.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2daxlcrjn.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwscyfpv.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kymqwrwn.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnglypa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zcebcqid.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2owpgvbmz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiboyiv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaavqchx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2abzmbdsx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2clrbyjcq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2irnflwoe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvidsj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2phddwlkx.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfotbdd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzyjykb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmslapvu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nufqgusz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbajrbfs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqktflr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2enxdmspt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyacott.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nltvcvmj.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2npaevgqi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmiegcy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2spidfnfe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ercbgtwg.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhgayfx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxmqhrc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjggxxb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2trkrpkly.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozwehpd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qabcwqpx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2exsblatm.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjqkkdi.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuqwnzb.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpzpxlm.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2caohnqgp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpmzbjx.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2glrfhtoa.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiaqrua.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjomwai.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgniosq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaduriv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2egawhcwn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmjuzbs.html


<!-- 参考信息 -->