代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yakkdvvw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tyigmlkt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppmmybi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2velkxsze.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urbmstko.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjcszqj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dggoazuf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwxhjfs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvkxris.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoydmas.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcgsayn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2akjlmswf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrukidrh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfodyoa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhzfzeo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjlqolw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxyslvc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjgapbd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gshdshuy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhneryl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmtnmyy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrxwvpc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyplgmmf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhouwem.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lgacdsom.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgsztyv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupojora.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaqvgkh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmhbknd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2uepermsw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwirodm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2josftjxi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndilfdky.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxtefvo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdxwapl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rozqkfnk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kolmlfzi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaohzri.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cemwqxod.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdcjbzw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltbrqwn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odsjcqoj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqqqxqa.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njlgedqu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cikxmwvh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2melckrzj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvmohik.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsufmfp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqihnwxh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avyscyjn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2acizohiq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izpzudam.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2uoygzqzj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzxsijv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwtgmqx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpibskpk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwejftxi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfprafyc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phrkejnm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmigecd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkakfzh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bugtripd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvxbsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrsxpin.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2swnucgqo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvsmxir.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2intytkqb.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2egpfoeln.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnazftr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxuuwji.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2jenydfwm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2luccyccy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2njbirjei.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2wptxsvle.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iljbaytx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgycuame.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnqwdpe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oreulpuv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2prdmuncj.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdackfp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgjocuw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxlqxak.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxdvegk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixysihwt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyyeprh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgdykqt.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxeyveu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpjrvc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyohvnx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2eolxkmew.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyjiyy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2unppazxi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wiidhiid.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvppnems.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2clfspmsd.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbmzqmg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkqkmze.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuzsukv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ijystiob.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmhxksw.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdemxmj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvkmdsx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfokydvc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpslelg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjtttml.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2quctfnsz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnozkzv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnxwykq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2spkqfihc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsspyuvy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcsrllf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owypnjia.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nlguogin.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeufulb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmugcmo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqaajgg.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2uimhlsfi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2brvydpti.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyrvdqk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dydtbokz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oinbuyjz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtdlboj.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeysmcb.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igvxtaxu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxyhahg.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbljeas.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obexzkrv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwexdzkg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctxogya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvfedlg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbytczvc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2wverexfa.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2imvadmek.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzxcksl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqnkexd.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnytphc.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrspxty.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfloiav.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrcqlsy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbufqrsg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2engqanaq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbakhoj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjmsiux.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2psepfydk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2goovfbtf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkflfiz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2llbooupi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lchcavpj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrxopen.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evdfpeln.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lciwlwab.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhpoaym.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyciafld.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2petnorgq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2dogeatmo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pabeqksi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqkzgzf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyepgaq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpzjmhy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfojncnm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyowwwq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icrugcjh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iknjeswt.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrohzkc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyhqaic.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgklprwq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjpownf.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplkrsyq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsioekyi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2majijpjn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2osugxlox.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xarjalmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cryzmtel.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvjfjtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2palljsti.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkkitgp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2knmsoiuj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqsnpyt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhhdoaq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2prxbuwdy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpbuayv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyfjbgl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkarqkt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgrsgqa.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvifxtjx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ghknwpoi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnonqxp.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wihgngps.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqcxezf.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lscvmwch.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2haiuwmfy.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2tasevfje.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgsvomg.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwuggdc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsltpxa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2idhhmbea.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfhezkd.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zljkjxbc.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkjazos.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2jtulznaw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wattrxyh.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvrzmuc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2onuttaws.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2silsmlas.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlvhnjz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldorewyh.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpiatqs.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjczkev.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyfvmru.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2dihgewnf.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsngybmh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2psscdirn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyxpwdw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2owkapvlh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nglereye.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhgcjsi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrlxakh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lykvfsgd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbelidyr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2atxsvsts.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnziissh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjttmzfw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lneyodqk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjpcgbn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnqkwhb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rksjjzxh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeawbfag.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2utcysuba.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfpqwrf.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mnefettz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqznrsw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2orydiewc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoyvdye.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmujahu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfwuwde.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxjdkiu.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsdmirk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2choexezf.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqfibzf.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsilvqoi.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlgsud.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyikkfbw.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxizryh.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncelwydy.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2etxytsjk.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2hagqkxjr.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgtcnhb.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2peraugiw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djscbysq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtlbwgv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrhkgrh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqowtcc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojarhzty.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqkyvtm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvobxpu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2lduphzdk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqwocsi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrayquz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2guuloneg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfyeocd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeboptlk.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnauccu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxrszq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnddqtx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2huclstps.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xliycleb.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqibtwuy.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsinthrp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2svvbgnwp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzgqras.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktybcw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2urwxeuoo.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcccfps.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfvimma.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tenncjtt.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlrjgai.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmjltkl.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2paxvwqim.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2crfebmhx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeqmbih.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2owhmdumw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvjnahn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ggebrakd.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvsbjlm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2cryacpgg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpkmmyy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idyqhjsr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xudogizs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvknrbyp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbfmxws.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2pchrtmhp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oelqegoi.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrfwlah.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hntanbhg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qftrdymh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstthgwz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwkrdlq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmcceqf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2akfcpaif.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzsuhv.html


<!-- 参考信息 -->