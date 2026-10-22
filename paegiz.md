代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sctklttl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2twfjyyab.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxwhjgy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvmyfuk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrddoso.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2njhlexrf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fozsbklx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxkqngv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyhjahz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkubeuov.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqhfaxk.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhopftbp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkhsgil.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fqixlkvu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjrnvyp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjauyxa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrytfhab.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2szrcgxmu.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxslrrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2agmufvic.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvqwjtd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdvisvm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbauuho.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfkinne.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgdraob.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mrykyumb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2odfefmap.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mesukakb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgmnnbr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iihsdvqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcqbmto.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2udenctbl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdwjjbg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbxnkui.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlupkuc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcocysx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcqkrqv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkqnepy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfminpwa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtuoibe.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvgzruh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwcvwp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bllsftsf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoqncdf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnroefi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fiztudua.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bplksnhz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqzgvon.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgdwidh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zekvzvfb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kicnjysk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhhclsq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrzohjp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzharfpa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqktpbeg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fydsuqdw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuiagil.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdqtoxp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhdiuay.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwztxlot.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cocnjkpw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkitsqmx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zypuytij.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocidyblm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sixnqhgj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfnoxwm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfclgan.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrnwpnc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nngomldm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhovejiu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzevncm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzaqzld.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eckxkhmq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpceftm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjjcblz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ufugyjga.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwdngrs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsvzifd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2eutlkpaa.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rjirrqkp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhgsmoc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2npyrvaxn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhvnssr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfaihik.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxyvxag.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2khzdehsp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxbzfe.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gubosalr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2erlkrvpx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gewvczxx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oilzwnqy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjznlwuh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2onsvsozs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmulvvg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmyscwm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjzzfe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhznhziz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2jisjrvvh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pioqdcxk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hcduzjdz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2amiucgdw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgowzuy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kivubnfu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2phtyrlzl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlotyoku.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcgfptt.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ceicsxwz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsvrwkd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2woxthpas.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfujtmo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zzygsoto.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2momplhpl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jllizkgc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwtdrud.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2rsufkbdz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkcykxn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2higeviuq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lifrkfvc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccddbru.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeeqixx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzozfqn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcfbiwx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtldgna.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpueedd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrtzhzb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbhaewx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oebmpgwo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvcyvhf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcsgclq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fncldemd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlqnmpd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwteelz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pljwfhlc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbmezwx.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htnhsdiv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhokpad.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yobmbojq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhtbdoo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwvsvgd.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcznzahx.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2plmhbfzl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjozhptb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnhrqar.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2okcyxlnm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2bawffpou.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rifpfjlx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvarmhr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbveomdj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfvqgpe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcuansx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfezmyc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyavobc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmvyac.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzblzov.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkazonio.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaypralf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvtdhyi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uslzlvrl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2doejvpce.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyktbmoy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdalrpn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzxqkud.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rytkqodi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2csoqiexo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcirsbt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyppbrsy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rreimjpd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amoevkil.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfisqduw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cedgbqla.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdigtknm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgzewub.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqmcrgo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsgdwcs.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2czerocno.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyyzmsi.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywdudzm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpadhxn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbnolil.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpjgnap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocprmxfv.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxuglrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsiryil.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlkrnjg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwosbkd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaobpuj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2szihvflm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpywcmts.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysarxgjp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2msjnympv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2piwjiyge.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuzvlqu.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imnoocpz.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqvlpkw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ganwuucq.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkdvzrz.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkroorq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2enteedwm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cztmzwov.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fuptebut.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhyjylr.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzdpkch.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvjtpeo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2chzygfou.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqthnba.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzifswy.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepjrzzy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmoajgg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbkltut.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tapuyqcp.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpgnxri.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2luumijfz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoilrwzs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkaxzlq.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoslhwp.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlccydx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lznxdjbq.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhliuis.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xclknqxb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgcsvfv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzkyzfl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2yizpcdwq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2neyttnru.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgrryen.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcblcet.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tattekcj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oabhkjzx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2byilwxnl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2skrfgywh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cozzncxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjjhctj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aavaxxoi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pabazcdu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxczfja.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlehevp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwfrcwx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlvlbxv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nrolacmy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzsbgxm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcenntxt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrropsx.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwcpsoj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oimhhfrn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehzdgba.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gttpddrr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2osffcnpw.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrvjoda.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzjxgyl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhkwejf.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkvjmhw.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dghhgffo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkbkfua.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rragbwfs.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhoaozh.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2yovvvrdt.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2qagnfysi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoavfqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tchjgdju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuctrhmx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdplypb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbawzmvp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zygrhzyi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzmltxw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yndligka.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2mjftnnnv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfivzdnh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjmwysf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjjdkmt.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkexrase.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ritvxymn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvlsiqd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuxjoxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2uhltuqbf.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxmdhxk.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqumfir.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqbjnyr.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aefkpdoe.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbsasyw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrmklug.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2thwweula.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lyimaamh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfmfqlf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2phrpcylj.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpfyeux.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqycpvwr.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mgouvnqm.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbckhlgx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2cekmspaa.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcapkbn.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxrpaua.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuvzfkv.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yawlolpb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdqmavf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafyrgkx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swkffygt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfpagq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrejrrll.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwmakil.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutcljct.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czgledib.html


<!-- 参考信息 -->