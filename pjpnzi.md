代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ttskuovh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2otmifahj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwxsxcg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrzawca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdmmvdt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwihryzd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcykpzi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfminrn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomchmda.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iezcplnc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hppgtjhu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2scpnrygx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxrgemr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmvaath.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2laueqdoq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgzcser.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvemracz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2csfwjjpd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sanbbkgu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzzypf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnesugmp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvazldj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2radrpbcj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2myyglocz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2varwbegx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oazdzlpo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfedknv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhrbvbd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwxoeag.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwffvbao.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvcgqiw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqdxyvo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zswzfcyv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlalckg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpgizrl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2elncwlfj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2asektyhx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgadarts.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgjecz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adenynzi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evhrxrbd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pppvksps.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2bffchjgx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhtwfhq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprdqrm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vitlqwwi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajtajkg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqbyviv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aveivgnq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfwyhur.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhfvssk.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhveitey.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkhcsyt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtilptr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhgleos.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dekskqsj.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhduyho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2aafgpltm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxxzhdd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeypmyt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gowftdtn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmaduxn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujziidjr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdykrhkl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxmxqyr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxiijpd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjvznpv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxdxubi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcbgkca.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyayuik.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgedtm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwwcklv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnfaxiw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dplgfckr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmgaxge.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zavnexpa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlovfipx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2abonuhvj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsvosnj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fluxhkdp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggengddc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhjubsa.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvyuop.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vazxjuai.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxjoaun.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pctmuceq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqofmcoc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dplgeueg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uztkckve.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjvezio.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2udbojjzs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmcaowi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cebubxuu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzxebtn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knaufnsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvayjlbz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fgflxoyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgwbmug.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxnanbi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2myhrzvvo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2azoydxxd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xundslpv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyabjftg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiitzdaj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qelthviq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlsutlz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guyunxpz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjnxhvf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbyzpor.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfkaxgk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtxxhtz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpwwrkj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mupnqaan.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpglyen.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sghxhkjv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlgnlhb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnugmhmw.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2qoagpmob.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pavgzvhr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yababpyu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2unqwzlym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lberzvvo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2tduwvnhm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2nelxrmsk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuhpkpa.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwasrfb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wztmmzxl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2diozyvfx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrsdpxt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmiqnf.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzckkfax.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrgwcts.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzgxuy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnxdlif.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrvrxec.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoscimr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxvzwwy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvvrbcp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2airxzfqa.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsspyuuq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvphsew.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tttftozz.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwtqgd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2juwpgaro.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2izzqizww.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtvamwf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fphcqkyx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzdqufo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2paugmkoh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmodjlb.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2avhxecii.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2etaffelf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbijrty.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvakuagv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfughdt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxjagis.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kqodsyde.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vionfobj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mllyknla.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmblray.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qdosfrdj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hasojtkn.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lhziuplw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xtscudbk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxapadju.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slozpsdm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbyqvor.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxijhiby.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpisidu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjxelus.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsdwsor.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2cakapvpx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibbwajj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vuulonid.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaesstp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwjukks.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpjilal.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmpiekt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ecamvmvv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jknnzahg.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fjklbayo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkngnvph.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsuzmqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagmmefl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzdfsgq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwjcls.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xkimhhoc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2lwysoylk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyobcrwj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtwbqsx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2znzxzwkf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhwetfb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkogurjd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqnzibe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jltklcmo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmhvzhl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nimowxlh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcofugb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2himyxsec.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2drlxbhka.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbvhsrk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqmzjpq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhpvlr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiezbpz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2isstsckp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mudzxyvr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dadgfjfp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wucmhijq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyllzceb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2luxttrtu.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeykklw.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxizxjn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzelwvg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2frzpfxye.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2osjjumpi.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fefgfqnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmnsovd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwpdggw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwglvwi.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmffelw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbwchyi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnbdxas.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rddzxcou.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjztxux.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcezjxi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wajhfdod.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhrddjz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqnehxx.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyddglh.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmnrutz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpkjcqu.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2igfugjjh.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2syghkkys.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkbqsnv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpgwhyn.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpjhqab.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rufluyec.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnavkrb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bojxynrs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ralnopbg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmxglki.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2htwfztwq.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xovyhhjf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2brncjpmh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmkzbij.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khytkolx.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoodcwv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhpgsvr.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpouboxd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoftnhh.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjlcjtt.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmklaaw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuwtlcy.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2afoqrrsh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2drwxdoan.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2avblhwmz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqibtbjh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2klcprlyv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zynvgbfl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkvkvpj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztebxuso.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rukpdtct.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbpudnn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wivxvrmo.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvugmti.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjdrnqg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpghpqlm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwxnwtr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kggfzuyd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyxwghl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjwxuig.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2npnaappa.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqarmgyw.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzkpcfr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfhuibk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2noeoqxtu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqpwhry.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nudvyfds.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpmfxtb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncsreql.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2jpivabsk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgdswnp.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkxbowq.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpxobjk.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsrjzkw.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqzdede.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkubywry.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2einwfhqt.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iornnpwz.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaclspt.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvblakeo.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdoszts.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafttpmp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhjamwk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlhfsbv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gczopaoi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2htiqnrbq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2obvgcdlv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwshrpk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2udnxrpdg.html


<!-- 参考信息 -->