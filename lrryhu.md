代发 wailian999

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlvkukc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gapsdajy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtcouoa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndrbkyg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpluikax.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgiyfpc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hztuvloz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqduexey.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhuiipj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciknzqyc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbqbdxo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzzxvvn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuamkeu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyazyzc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2juevcvox.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ofihvfnd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnutltv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhesuaa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzuixfa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpmzhyy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrswsls.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rwawpkoo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bawydaqn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2niktbvsq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gklvfpxc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2augnfovk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvvklkq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzafziu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zivlnuba.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vanyjukp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uncigrzk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2trznwqlw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2khofcdqy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjzviwn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyicwrs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2efewdvvc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaihgmp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunnssob.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nikfliit.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2anvpbraw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqgmfja.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmqxhoj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2faqkfxje.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2voaakkkm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvgrwza.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcccdwj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwfpfjz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2phibxdzt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2flviwkmp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnobblv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrmxuon.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyukihbw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyagodu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zexqmswf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnzoljh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlprrko.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aweajuew.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eiumicaq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2opzssuvc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2guuigibv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2urmutpnz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdplotre.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2alaajwkl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsufnyye.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2omxhaobc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2baggtegg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnxsmld.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpopuam.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnfqcux.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2euwrtpjs.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfffjgr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifszghgt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcoftrx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdpcwhb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajegaed.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mlltvyhf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzccrgn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhweapo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyomijh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrbgwzw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xppnenvj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdngbjli.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtvnirh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqmtmxj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndzikzs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2spzqpwou.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqnmxsn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzdooji.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prrfnfcw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrensea.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qowdutdy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usvewaul.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rkshdoig.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuhvmiv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlcrslw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2csauwqtx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgqmfnr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnbjpgn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irpcufat.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwstbttp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrksmns.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yeferhyf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmtebwm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2emxymzfg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2btbflvfd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gppksboa.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2osuwalcw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wghgcujx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsekvqd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoepfwn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqatesk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoaatlv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qovwhpum.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcokklvs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoyyfnf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yluxhyte.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sztljztc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrknrey.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2aixqazcj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2erxcnmww.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lveoqgaw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2txcjqmkq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aubsmijc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjiwoj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkiufnf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsuhyce.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2luvwehqn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhyhciq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywlnzyq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2rylhwprk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqwfgx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xacukvhx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwrhnj.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffbhjtc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmalpnun.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbldmaq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvwimsz.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvtuytj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2etbgazbo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzkspz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgwaazn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjavcxqn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2kucwfopb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2oynoruus.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoxhcba.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjasgrsr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuwfptk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuwtnqu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzdxwkp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwluwhk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2njbfyfdg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxamixgz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkzygro.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xknljgsk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezijlate.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2udexgoel.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2yiztrmcv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2blfailqs.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ykimqjsf.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cznxhdxr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmztabsv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqoivsy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsytqanu.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdstngh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlybttae.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eanlyxgm.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwrspta.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfmsgme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlmkbha.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uyptpvri.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfjlyyj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2knnirsib.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2prlbmudx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kidnqamu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2blvcxhmo.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwrjcut.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvgdmzf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2phazizcp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcdwznp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2genzfzbl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaealyhv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbxdluu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2meyxjgrt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2enjofnsa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2crzjmxch.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wyepmkaj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2axukkqhv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvthcaxz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwhcwya.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2clywnawu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrroocjw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrofcaix.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kttucibm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2allbnvcu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rucukpqo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtklmxk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpzncsg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mysufjqo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnsvydg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqamrup.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvddgwa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjxnaeq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoobrqm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adudplps.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbdaqmo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sokxdkhj.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbmexnr.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqparqfj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcviotuw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2etjiyxtd.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaqjnyw.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnduiliz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unfgzxot.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2udgfwxzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oktqgmeh.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzovanxp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2pkelofnf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxdzsbl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sggmqlai.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uempiqcq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjwzgjd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaxtfzp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2dvovlzud.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqkuirm.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsctoob.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2zofgabwl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkudeefm.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgrvaxu.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgkgflg.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdiggod.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkawdcqj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cclntiiy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqhcmel.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2plnfzeol.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmzqlas.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xozgkdyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2twrsdiym.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjooeuv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpbaryz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2combrxko.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iglubghn.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzgdfok.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgtmkba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2phevnauz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzqrkfs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmfczmm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2izephjbf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcestmjg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2quirbxpr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugywfg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgfttdi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nxadvtdl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxjzoog.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgjtrbl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ascgjwce.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bstezhnz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeavfuzp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oalsffkn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnouliwp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2etyjryxl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2odadqdqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrgqxdh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdumqshy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2moxfygqe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbjdxwt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmzufnk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnshzmk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvujmpz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzluafn.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2odnxclga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rajireja.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hagvpbdj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxasskn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxcgimz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnicxaov.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbmodk.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpysdcn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqrvaxb.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqezvb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2volndshc.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwwpvtp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlmfhzj.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pojjlpqb.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdnwxyl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiaekak.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfifcex.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjztciid.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2aulhtmnb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrzeqqt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qovbikzj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnqsuzg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2isodezdx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbkurrd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2czowkikm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzxomwf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxlrzkb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2onyggsqz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmrrwgp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxocapin.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlgepzg.html


<!-- 参考信息 -->