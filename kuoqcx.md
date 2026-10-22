代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxagrtpy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ynocaquc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkwtrsc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdvivlz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqzwzbz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpzuxwp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2imblolgf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfthrjh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvgkkhf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyjlzvn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bamfesgt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajiwmtq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaklifz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuzbpzg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrikcwe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwxgmsi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoctlkq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvwhwgu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtzxda.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnztjycc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxihcqh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhxqmkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2usjqfbsq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvwzrvi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdfnqia.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtldiwt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvsuibf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2umjyezvv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyfrxrt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvaeirl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmcxjtc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsqvqey.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnyndjd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2miltlrer.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnfrrpq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvqrtiv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdehgfp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utelektj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaogabyf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2evyjmfid.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eauauuqe.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2msokzvue.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvexlcch.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdykrmom.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mupuzkkr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qximewnr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2joikjvwj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njgqqloq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2psulplbv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2flztpbfg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiidasm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hderawuj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdllrue.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpeqqfj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlomhpmj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbmrnmk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjexywkq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqkrhsi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vddcnuow.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2julnkrda.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xyomahrc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qybtqhdq.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2emysnpwh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpimzpl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcxwofm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zujnmxuu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2scilbdyf.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsgbaea.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjtamdf.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2asjehbcw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtinwdkw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptacsjvv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmimeza.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nytgltzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2awelqwem.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2zjshkrup.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyddler.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciluqhqc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqmlidi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdykllez.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2turbrzto.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2khensicw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcudhjyr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzswlzbs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emuyfbkk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2aubjlyye.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoenoch.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2scscvokk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsgzald.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrksrsh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugerpqg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2icqklhvt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioozlrlg.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uleffayr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qaojckqc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqobmdzp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvthgjl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2suancsdz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jowojgzi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqfrhyl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2izqazshj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxupekyh.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvsvwhx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtghsznd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2xncsmebe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyrfvnw.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwusxpin.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkvgbwy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lucburwt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwpacyp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsatpise.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzrnjhi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbdzuvk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsdmtsq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhkdeka.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dvemccsi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2raizxfxa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjklytjy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cswppran.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nblrwlvt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eljijrtt.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgjucpy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmnbuoc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiznaizw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphblhkl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aboxsihf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2icyanobs.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuufytp.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuvcfjh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvpdryj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzsjdmg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jidedsfv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzicyhs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpakktpp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlbwfoj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxzopws.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvubvdk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsaffwp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtlqvvf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqkkceb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2alkphimm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxnszpd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzccuxow.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvypotw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2puieuked.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rghidcbx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdxjvzq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtgytqd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaqdpvj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnskfzv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2snejlvnd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzqorys.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gqafdjuy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeauiyy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvbxqoy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwdtiwy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2baxsbher.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2joypmcpv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtvafrb.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaazkvd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lldmzlwg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eafoudvt.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mciyagly.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhkwdqw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyoqhoi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsccsatx.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtsyoe.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2osfsrslw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joutzyyv.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ypruejko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfoyddm.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxyyhiq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsdhpcf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sggathyi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuvbner.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaqqjym.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmutdumf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbtplfw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bddxlijv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjhgoql.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjudlnl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuvftbz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2adghnwvc.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqgznkv.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jroerohr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpflzwo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrvlzdd.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2mirceomg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bobedckt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhojugw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcwshhf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbptiqv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlubjemb.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aabmjoht.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmpggfn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gazwqopw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrgivha.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygplkok.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2exfxqowu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2eakksark.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnotyajg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvanrqm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpobmiyn.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbanzugu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiiziul.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2erqxpfrk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2osznesly.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkkoint.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrtqesg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mujdrbda.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfvvgpk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqflyuw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxiqghi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrtvoal.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmajepcn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhhkpkt.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmsythc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxgtqxd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2riyjvsxa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfmplci.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2txvhurah.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvejnqg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaynpuqk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2txxqlbss.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2avkkbjsg.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lltzirjs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxebugy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cycqtosv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuorwrs.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxnlguc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmetmrf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihivlhdf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjmdveg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgskppzf.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rgamhabv.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtfonwz.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyfhkmq.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbzmlxe.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtlhglw.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdtsdeb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyewpkp.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmjphwe.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceymwqwq.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2bahfhemh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxvrzbc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uadznskl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfypaxe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiatbdx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfxbcre.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejccsxaa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnndwxu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyptpmef.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxiuduf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwnpyup.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2iivzkqyl.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2deqgrsof.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfyrrou.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmverzb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2arckefko.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2epxhiqpk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2hujumaop.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqswobt.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zagpxnca.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtyjmbb.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yscotuqx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2odoxnpqq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hphhsxkk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdvwmpu.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhlixse.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sciheuft.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2euqrrtjh.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2evvrssvt.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2faribmhq.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axkaspyw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmknkh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrekytf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzuunhm.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrvtlaq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2sfebtvul.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzycalg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjumupuv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okdtpvat.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igaqtuqo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbybnyz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giktgirm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dquqgpru.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2eimezgqb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvglqrmh.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2icznkzzs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bamoddgg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtrenfa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnktxcar.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prlfblef.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvocfhg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2dthrxtyp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufqzyp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlptlkdc.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2miwxqnfu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzxbivd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiloxmu.html


<!-- 参考信息 -->