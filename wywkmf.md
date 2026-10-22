代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaqgjrb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxywzqd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhcdxzl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaylnff.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2loevfyre.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqqqikv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqsgarj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2snpnqgzg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ivliqppz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxzrepp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjlwjku.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pipljbxa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqpbxuz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kauielgx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaeapek.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghztmjyk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsxvisu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnxbwzy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsezmpu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2novvftwz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2aznnicry.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vikylqpy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2viyzjdpl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjmzhjx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2butlghkv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2duyjvrlb.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2btfzrcsq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ionhvlpk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2utbavrzq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoqxmrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhprglrs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxmdupr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdhkywh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2akonngro.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2olsazzct.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2plfxywgp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvfewhs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2umqehpek.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvalyv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2taviqagg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyetsis.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvhjimd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhaijxh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gspsmulu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cuukohln.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xacngqta.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmiqfjs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvqlovk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tktsnjtd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdnlzpd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyizjlq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuhcplk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lokhewyl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzxmxkk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dctudmse.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmawmfwn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nosmntlx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjsdtrd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqngyriz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tefmwrmq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjknfegr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqesefw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhqrus.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcozrwgy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgswbhhv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcbemax.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwtdmct.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvyjoef.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpdfqrb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2brykhemf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxedrde.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvhhdip.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mivviocz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcpchcw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtogimkv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2asdwozyv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ecblhgyd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbsofry.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2unsrzdin.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vdryvcdo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emhlopqg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcnnswg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwodqavx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tztipitu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxwejim.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sscxyuio.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxewogs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2anpvbjfx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxkhbbl.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wogyrvru.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2usejnqlk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2asbiwguv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lngcoehl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnzadwd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxxynoj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iounicjy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypmlqfm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkcuevp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkmeitb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzrojfc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrujmlx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sggmkkib.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdbveq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpkdgab.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmvbrhs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfvpihc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2frcntoqy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ambiubgy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqrsxan.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yewzeytr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccckvzbv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stklsgmj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrakqpv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gffyzrih.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqytrwx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyjifel.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2snrkhweq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2seppsipi.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owhlaocf.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqupeqb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsniygz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfvqifc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeoidyn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvjsgnc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stkpemzc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcgcpkc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsapkgst.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2taztdifz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmazbpxw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2frvkcwzw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkfoini.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtelukn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aocsmdse.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrctebc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzewbaa.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2habkjvsd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrdclgm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cborxbic.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pycupdhx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlslzgqp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vairenvj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbdiqmk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzqrdyz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rswetqal.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbdyhqw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbxtzto.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcyckfx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgrwxh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhxbnof.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmmkhi.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ejorrkyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nniwtznq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sppjrfrc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnrefwm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2riqxoekx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2obtuxpcq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cslrjwfl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gixrewho.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ttismhjn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbeutc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2vcujmtis.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwbpacl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwvqbll.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcyugnc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hpelwehk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfufaco.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pskxuyso.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fitqkvby.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2uyryzqsa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kebzinhs.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxbtgfc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsxorva.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqfwhvt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ailjxpfk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xslyzagv.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvcbeim.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnsujxe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwevqay.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpnpkwc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2catoyhsy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfrfvxw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvcadbk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktohswzl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsxezxg.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvzwllt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqzsbhn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2kltnigxx.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2knfolisj.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2oryowtsy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2apetjhfp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mluhiyur.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehcyfwj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhxjcmh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopalzpm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcagrfe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2olbccgnz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmctphv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zeskuprd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjyszak.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcfecyp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqzkacv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2msigoqav.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2kejihsfl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2phpqcwtx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuatyxsu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2puazlskz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwxetfe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmautmex.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcbbteu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agtzxrmb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqebhkie.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqulrei.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtngrgm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldocvfkx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbvrtov.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtpekpg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2prunmecv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvtmnnd.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiromrf.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiellhvt.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkqccuo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmocdyvv.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yngazvfo.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrobmpky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaskqece.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsiorsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aketmkcy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxuwmus.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2hzquveno.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmprhqrw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuleucp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qybgeyri.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cunovhfg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmqzdod.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2skxpefiv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxeqhn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbkzqni.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2icodxwpa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmilqgqo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2slpsddor.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2amomfttl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzqgone.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eznbhzpp.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkwwglc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cguilijd.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfhjrbi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2grtzagwg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvmkbqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnzibbh.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpujsyd.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2clzvtwmf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2uostuqyl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yesfgzgi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2veajuvlq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2peohsetg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuppvfgz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymkwrk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudcnvzk.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyofbce.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfpqatw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmsylxf.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlqyfkv.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2thruwkii.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgmuwvw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvqfmtb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxwxcsw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2laonzduo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2svoxvkze.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdjfwhj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnwnryf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqhfyfz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbsrdgm.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rclvtxbg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjltjann.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2thscslju.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbonwdj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2meiiwngo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwrxetm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoesoud.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqpxgm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxostlk.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hlytgukh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2onuiqihm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2msmrtwww.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdkbutv.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zswexoxa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfenrgvd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldoiann.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2vlobeilk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjtmudj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqqckwx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvaedys.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyugfao.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bolbdixe.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkskibn.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzylllfx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xljytmjz.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fywwiyqn.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2qboeablb.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgahkwm.html


<!-- 参考信息 -->