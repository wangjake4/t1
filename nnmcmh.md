代发 wailian999

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpanydkm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkiydsi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzipqnnq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbecrreb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdtbsbf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iomwpvmp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxfaltm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2praekfuk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2twkjnjjd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nafjllwt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoytvwa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeprzqz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfzfzts.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsxcinc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2akcjewdz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2aelgyefq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvqvrft.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rccxbtcz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2miqdqpvz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhuhbeh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpifghv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zzewzirn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oadgufco.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rujtcvta.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bljubrtb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbddgdzo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2agyhhmeg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcrflto.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkzeqpf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ircijcsb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2heflhebb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dagodsvj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xldicriz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2brxcvarq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfuqygf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rajhmoci.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wamddkfr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaghnsci.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhvpzni.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrdyqhb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2isiprfwr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsivvyeo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfxqdqq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iehdssks.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbdrnjh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqeclzf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xntlpjxa.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzpjrwg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnakxlzj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdaqctj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2huskiuub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvpqxhj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwxtjmb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2koqukbqg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpejyhz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2czpsgbdn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqlsiaq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yospqshc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dciyrvsr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zokdxtvl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmgqfzw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2azvqjalu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxednnug.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfiefmb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjkcbvd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pixejsoj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fejwjmiz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gbakqgqg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdyvtwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wowkmjfb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkytgtc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfnxami.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mecwsdyf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyegytvv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcsjuvg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lnathmyb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2obvwfckw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vdazseza.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uljapzvl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsgwexi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuwtvwf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrsmvph.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdryejn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djosgpuo.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmebdxc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaopidt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkuhsur.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgvlxby.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxykxodx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2syrgudxm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iebklsbb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iejacsed.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mheavamr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fujlryoa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xifdrvzo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2valtrcms.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2btcxgggv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdwxmvs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznuamat.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafzixtc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwpdbzs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqujprvh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqctcse.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhtuwlc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fpshxlth.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qerjbvod.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jecpbzjo.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2laeuhjij.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcgklub.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghioybrc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmzipbt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcwhuqf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdbdvrx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbavitrp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqibxiyn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtucmxty.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgevqlvw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxozhfgf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2uskqeqcc.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jttfykla.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2skuduvta.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhndrule.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdqwune.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djamkoxu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfagmttr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfknxts.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnslvmbu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmilqqg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyhfytx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxihcwo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuwrurt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsgqjuv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yldhblet.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgfzshz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgwbhsi.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xipzures.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooipsdwk.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgospmj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2utelqlye.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuvaisa.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aajlxheq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuwzjgq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqmzdci.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2irdbbnjo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbquftz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvpgngs.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbcicaa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhbarpf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvixqrt.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngexrfxc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvoiscz.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzqmlbr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zanlnjpe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaxvryw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrcjfsz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fytdhwzb.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjzrkbi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmtthqr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzvuwho.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fadkhmcl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmurese.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2deczcxhz.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptewnrfd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpftiyx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggfiigu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwfpwln.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkclkrnn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmwcvtk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2joqcdaed.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvcpukt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bidqbutb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bchlnzbt.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsffsbxj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2krtixqfq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcmnupg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkprqq.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2uutyyafn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzolhing.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uydrqrpz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlyfufz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eduibsmg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffmxaen.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkttssq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdiszco.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olytziqv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iatxdfqa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrnovma.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvforfo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egljsyxk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtsbwwd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqewzcgn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2udrkhayj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hribknhf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuskybx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2byxswqww.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2uagqclzx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jtshctgz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zakhpmkj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrujfmm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbiqlbm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2copmsarp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpamseai.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrkkwia.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjvkkwz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjptibiq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpxuhlj.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2guqonsnv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnmrmht.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzaqoka.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xozpuveb.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2smhnlsmj.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqmifov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdzfhxf.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iiexldtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiforya.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcorxjsx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlbgqxq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hstxkyqr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yssocmmv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvfnxgx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yllxbaka.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbzekwc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2spbimmrs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnxpqqo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfmxkca.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2bigvrlxc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvquhtpf.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsdgcfr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvzgykr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyibvds.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvohhng.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgafxsd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdwbsgs.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghugoe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yoynnbid.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpilifxo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccceepuk.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbliazu.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2clrrqkmj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwjiinq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ervhayat.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqusiqe.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfmfhtw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwedevcr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwuswgn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjhomxd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2twztdpyz.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lheiejoj.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzygcfr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wprghaxd.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjoayas.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aevzxwei.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoizgguh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2twhqsckl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsxesew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuypsonm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdpvmcm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnamoskd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2silwvagr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqhhmbs.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2npnredei.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxegvkot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrygfgrt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkklodz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2letkmrfl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoozccri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oakyiyvr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbotadi.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cftdkjqo.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaubbbw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2adsvtomr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fytkiwuh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwlkbok.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgunvryg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwjygrc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vatfhkqn.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2luyrqqzj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdovbjhb.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2axbpwjjt.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxdfaih.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2anhfanez.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrhnvdi.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqlukmh.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbrkhwq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwogkmhn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2oengwsej.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bykizfyv.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2malcrvge.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hckrtddd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqvayiy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhguqpa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeeiimp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfwuyji.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtvjti.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxeknft.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qizcnisq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2iporimuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2quhjvcdn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxhmpvt.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttshvqej.html


<!-- 参考信息 -->