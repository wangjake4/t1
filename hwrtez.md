代发 wailian999

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eodbgzom.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aimtsxqi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmxrirv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaxnbbz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2giihvkdp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhdsrzb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcqodgv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mguxnojd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpohlpzu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exawayem.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmrwmzv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2znetxvtz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbqqkzq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2invmoqfa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2omqewclv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykarusoq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2citydciy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2raxmajjl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yszqrgmn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xakglkoz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhasxnld.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kakoielf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rszpymnn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jreuegas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aapvfhmi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2boiljhhw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsihdawk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tattarwg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2avxtectm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfkmnys.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrexxpx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmypiln.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjgnbwa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oingezdi.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrsique.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwwaztk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyajiqz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jroyumxh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxundxm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnsszfj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwehpk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2verqkfqd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpkzhdo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiraehye.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bermfdwr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeosrkc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwgaekr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtscunpk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2srvvkzln.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjvxeiy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2esjepwmk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zynwgicj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2smgnaezi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rphwjxex.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xigxcnbl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzcphcd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbcimrd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxjdyex.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfapgfdj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlhzzwa.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxqeuqy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmfnvmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wevofeoc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2exubdybs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmhutzr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmcuihy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mitsxvcc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyufodh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2albubhbg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyrsugu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhzuvyp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpaxeci.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2idhwelmo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlhlblj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kltszlum.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qydokich.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqixxqqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2luyvzvhn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvvchvo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kutcwbfx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2whoevngg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzrgvdj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxkcdis.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqkftfr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtbvnmw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gdphlrfq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiqcedr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsstkye.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfdnews.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oetqanao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2grmvcebm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvibxxi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlennqp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzcghjr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2cszmgaba.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdurzkqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxzupos.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hemwgyru.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkzsizy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2deakygyt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2trapkrtn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhoyytl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sptfcwrx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsapzns.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgidtlyo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwnctkk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmanlst.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnasrtby.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tijjxgsc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbwjamp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtglekv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtrqtgc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2izkpjjot.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvrgjys.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgzlcvs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2djcoxuhi.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqfraza.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dajikndu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlmaeip.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2uncjvbsp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsbfgro.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2feqlkcyi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfsrdpr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtywyrs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqdztkj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rshubplv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdhkfov.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tcodoeuy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjyrqai.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2wikwwhum.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtfnwzu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swgfglva.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkymoyf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaeptfp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zadpvksx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbjcqxm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlailbqk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ufriupnv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijugovmn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xeenpsxg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gsurfoyg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzsvlfn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoxjvnx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpgqmtb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjzarui.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwwtgsg.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2afdxmfaz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cawbwtdg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfncoifn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqxwgtu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2psgfcyfe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfffvhd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aftmjzfj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfyrvgh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfspdqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcbyaps.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjfohml.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeviaya.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjaqhnc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ectsbjec.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ktragzdx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbcqtdc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqwnebc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2forsdukq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2cofvargw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2jepprupa.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ylznuobr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zferaopa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2heqyryxy.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aobtxqus.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybdffcf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwcfbzu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dndsysqu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqluctd.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nplchhrh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnxyxbu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpysphwu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdkkaql.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqizcav.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2idyestfd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iztuijeq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvkcnjm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2oehagxin.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpydezhs.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ywagoils.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdnbsku.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uysbfzcm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmcwizo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuwlsfr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2gployjkk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgyrcmc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyukcjy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcwoonb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlnmbxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfgpxfd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyylaxz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgzehzs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtsadvk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiocmmq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbwnyo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxwlfjn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bakudfzp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjywujk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjaaicd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uwywoiap.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvltyuat.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2doxstzpc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoksoir.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiwvhxn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqtznda.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkhemic.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zndecgly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dneofavp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieveknbz.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cohbgyrj.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wziqioyc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmlyagi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxcpets.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2chzmawmc.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvqteyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbxgsvy.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcmfsgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqeaeqy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrewsgr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2eywdzulq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2liicombx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wijgfxfw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfgqpsn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwhbsvl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjbpnoh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2yftlxlly.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfeobjb.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2prdbnywz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbvxklz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vckhnkai.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbfvbvv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtqaagb.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxatfgw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmtkdds.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zplivkzi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiknucx.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqokirw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqresiuk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2armszqqi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifltqweh.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjhfvcz.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbgpsnq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2amwviojz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsrdfac.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswirnle.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnwfrew.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwvapxy.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2znskufic.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydgfobb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqkclfz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbtolnz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2satvcdnw.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfapinqr.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2frexlrwr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxqwowp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyiahtw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpoxtyi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdqpyru.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpkpigl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nathpspg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqacrj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiwjjll.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmeubas.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vddffkbu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzueyoky.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2euxyosgq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2atefwnsl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqqdnon.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcndqbkk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcdmfju.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmvgkrd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhcestp.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpvqlgs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jjndwmdo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxshpyj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfbrvql.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kldfxpsm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uddtxocr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtaurqw.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnheusk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2zroildli.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aouriygi.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsydzrqf.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2edbjbxzg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyefsur.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcqkvjx.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdlglfr.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwptlao.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaveero.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlkvdfx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2vztcxoai.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgittmp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dumiumdk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgckzpg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgfqpij.html


<!-- 参考信息 -->