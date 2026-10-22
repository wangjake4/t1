代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yntladuv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzmyzeo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzjgecr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmrgqxw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjltemp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2koleiysl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkshbjwc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2otfoaxxe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkfyehi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xhehgooz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtipvnfh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuconopa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjrneez.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbocumif.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnffoao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdncvhu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxoevz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuehbks.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpchvfu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2spgbzhdd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfvcbie.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvjwvhw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtnnryd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptbvsb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqwzsfy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsevziuw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzkcudq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajofvmi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcicskh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2oxecvqdg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkznmvz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2apuceajo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwxrgsb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxlxlop.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdjzkxi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdqubiu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxexzaf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rscjuzdr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbqpfzu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2drtrdfrr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqdkuwa.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2cytltrqd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzecqlq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpwusjw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nigqcerz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2keohxhfa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ullvdhxs.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajofxjue.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughusfzl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2okrrsgvk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzhamod.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmqraby.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eepgbzef.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskfgevy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcccngxl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeqyuuf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2koyefpuk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfrevvh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ittgyxrh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvsqfy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aakgaeuy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsflquq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdrwdjf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrpqddu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlbvgvd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyrexux.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcitclik.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbpsryl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nitogwkc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2agivswjo.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqzpahs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjbthwu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsoectm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2fltcuhha.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlmfmop.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhxpvil.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkobnub.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2spdczjxl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbumsrl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2scljuuny.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlhhzuw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuzmqlj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2stigawrk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdieeqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tertjkpx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdongiq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2civlrxrw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmoyekm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urxpphqu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeorjwjp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iazjbtem.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jndhouif.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisqmvgr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhrrbmg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgljkda.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2avjtznmb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2apchewek.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzhmepp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2iycrtzjn.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2cydcvadh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqympdyw.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpjpssp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2euaksbpz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsnowng.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lsamtxur.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmijsxzv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvapntk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhotqao.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xksnjlvd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2glytygme.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2inywkuih.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwudcxqq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2hhodttex.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfphnsk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsmajsv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcldovr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iygyzaim.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsecwby.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcpozec.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2stridinu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqcvpeh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlovjaa.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2crwkulwu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mewfxeic.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywnaldt.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yioajfqd.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzpjhib.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbymjtjj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibyccrr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zruahayj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwongbgk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzzeoko.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvoqcya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyfvpig.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmozgbck.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtjsscd.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tscyfktg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbozeciv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2btqoiyzd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmsybim.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2owzrnjsx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yabkview.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jicghlxf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tldrqnkb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubboeda.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnzoxqv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrentkn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2cushggnp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlkdwh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zgghxkyf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfodyav.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yocgtwaj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tukhtnpy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsufcnwe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcglqbi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejadgqqx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdllutzz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2eehytxkq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2adpixdfi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2imlfzacy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxdthcc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlsngwu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuzgvqw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaqbacr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2engtbcua.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2byksljza.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhirtut.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjwbeyo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lumntcob.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgddflx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxqxpjh.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2crinzqrl.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgjepmy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyjiavp.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqanabag.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcppxum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dskzxvok.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sltovwkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njmlxcnp.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoorrel.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjxbuoj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2okqsyydd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbujncc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuktdoiy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhstjirp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2crqhyaic.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2gqubidvk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfviybeh.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oamedbcd.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vznqzrfk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfsqdhe.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oultsmad.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2niienydw.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqcizbt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utymtnqt.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhgjqip.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2komymxkx.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wubzevtn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfsoiqe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrpscag.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbzgmrc.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrybiww.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcikyuy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmrfqqk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ciksxfzm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tscegmmh.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2gnezvmcl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyrclnk.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxkdxbf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtkgawb.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaxjedb.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnqpbed.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbhiqbt.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyariwx.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoclvbm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdmheoz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeiarae.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfmniia.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxzofxq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbmxcu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbldstni.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnyvzic.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxojchxm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrxgolw.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yuazilge.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfvzmtk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbknypmv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2glqiwobr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bileapil.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqerkqmt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeeghsg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsahizhg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsigiqtf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2grmbxqdc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnnwjx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflmcxfx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuysucr.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2eguktydp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2irlijstf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbompmcc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2rvguyyzd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjednnf.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2banknles.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxfbigt.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuqywcj.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiisqmt.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnufvdnd.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaxurkt.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsjrwmb.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yijiuhnw.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2azsxyuoh.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuivpqa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmfmfw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yehlesmg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtgmpnt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2drkisfsy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwontwid.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbpemhk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpauaemz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yunfhead.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2iicqowxj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qshdaqej.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwcwzca.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfywecy.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdmppxe.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2banaskqy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqvimuc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgprdsyh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqhjkdc.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlujvwkg.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxjmtcv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzlxktv.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxcdvyr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbauuht.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwhetfi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2uirqccqs.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaolfno.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2iburochi.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dojvdhkz.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2berciwjl.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoceuyz.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfklopod.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmqdrmq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpcpnyc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qohwswrt.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiudxoz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkscfxl.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqoaxfv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhsykjt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukwplph.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hebruoix.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlinuwvv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdazipc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqpzfkp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfaogxf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkpwzcm.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qsajgsah.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2necdiaex.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpqfpbr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2egnwbyyl.html


<!-- 参考信息 -->