代发 wailian999

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwnbomm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqethsc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qdefvzry.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuwxfmt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuxabdi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsakjpqi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpoezgt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozrfeac.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzilqho.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkxkhij.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjljjuf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcdevgs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzzwvwa.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmdwczm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qydfykcd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfkiayg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eijbjkmx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxojhdi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzddegw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaevikqh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrfzqwz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmfaayw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2whvtewtt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmjzlgg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqicbacj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qicikjis.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2btqxeiak.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxengen.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvviopp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxtluri.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jihyhvmn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxydzkqc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqccmrbi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2byxrlpgq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjsbaub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2stcpotmn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqlgiyo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qavxupns.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxjqvob.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehilsorx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cattqojf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2puikzmas.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyipomp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iofpunxb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vidrwrlq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgkqmx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uukcqrtk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgslgmc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzptwmu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvgzapl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dierfdos.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kpypgwru.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiadnkn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2knuynsyv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oudahlpu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfsgksy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuifbma.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkhvtox.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlbskzg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhwdrky.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbymnah.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdtofgg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekigcars.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqlczdu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcabpdo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhzhvhd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzimtsx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuwwpsw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcjblvd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhpawxb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwruxvap.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qesevczr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwumfux.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjokgany.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoujxaqs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhexfvbn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcffipqy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqaiwmx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2foswbnbb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfazgpkl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xlroovyh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtbbjfe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnhzwqx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yplrrsyy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsukslo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgmhgmt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnpbtio.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vusrbnyw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gseebnci.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2aupjifep.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqybecr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cssnzwwb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnyrdns.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2patocsjf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2sakotqup.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaijtkv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwyiarg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2heqlabdv.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lowshbmx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnupjsz.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaywcuif.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2omymomqe.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiltcwdl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mepbunbr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaqfjvq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeazfla.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzgekmk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rzytpmfs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qbftqiyn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyuhico.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxmyres.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmavbgx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmopjta.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzahwrpo.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuzppvz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltepjavm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2onnteury.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqtoust.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2gfysvpkx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqjqjds.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnisrld.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2aozfaatw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2lybucxkw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvzoktp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2oolhyzbc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgaclpp.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqprpjqk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxagzzrv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2evxdzpep.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jboahblw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwwznci.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yixqpodr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqtwtph.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cveyqkay.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ckahnmmt.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnqbseu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjutoneh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqnjqhj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctttsxnp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sftvcjjb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2szxcpygk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bthlnqfi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2daxxpztn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2eospilqs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfijfyut.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2djnumzar.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbuvsr.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkpsyhh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2njkijwgc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2halhsvfy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zljbjzqx.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvuliat.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxilhjs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttqyfkr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwdgtqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2batyxxfe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqvfutx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkzlmzs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oeykwwbv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2swoaeuez.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2grdhxczz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmljonvp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwojjni.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rupogjdn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzbjyoq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2feivpebj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyyvybw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqttporl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2koudvabr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdiaani.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkqzjns.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwttznhy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pbamzhxd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyiuguv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfliwrrr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlonxsg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2baiyscwb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvggtdb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojucbydt.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhayrpiq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgntqpu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnudnlem.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyuwiwx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrzmmyi.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlvfxex.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrmyzwr.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fugbbaem.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zihwkxmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gopkgeum.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfzylks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sazzgblu.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2beqshuxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgecclf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvzvcbo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwgxbrz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqopnpk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2przwdwtq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvxoidl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2shqyfgxh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxguaak.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbcbiru.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2phuwaaqq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuvsexo.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2exfpkfoa.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxorxqi.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sworqxyx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysemhlot.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpsbbig.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhqmtek.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpfncrv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrxzzvm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tytobtzk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zusyfnni.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdujbql.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjxepvi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nfehtthb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhgiugd.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmfyes.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2bbemcgqi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjfdltu.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbsvxyb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujepdcbd.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsbaqb.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzguodut.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwxuneg.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuevaep.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bagiynrv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fjepqyjw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhiuolf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdutvakd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2htcandak.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2twvwihta.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2urxiqujs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsztykxw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeprkqu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwrozfl.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbwrahb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvinrzxl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hupclusf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2egcyqump.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrwcvic.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnornkyq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqzqndh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfphdfh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjfajml.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uyckcvxf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvbpclq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wflhsxgg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxeiqmy.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrhgbig.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2twosvqbx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeoilid.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaaeqtl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhywudq.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cndhdmle.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycampuzj.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2axnvigks.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ritruapj.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2budnsnjd.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmyjxym.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtatveu.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2artoiuem.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2choncrve.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ptszcitg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwblvgh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjinevzk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2besjniai.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nktobjzu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsmwdmr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvijgbss.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltipyjiy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyapuif.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsxlmbr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrazyeuu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2naocoveq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2etfhsmyn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqencnk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbunylep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2opexkctt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2otpkupfo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmsooej.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gincgxmw.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2paonguqa.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxskggwp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kopepvgh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuclyupz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2znazkhte.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2flcvqddt.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kipjjpcy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2swiinrks.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeaglro.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yibiimbc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2pomrigfb.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jbynuwcw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiwtimg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtdneok.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewexcfjq.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuseqdxr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2nslimgzp.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zgchzpok.html


<!-- 参考信息 -->