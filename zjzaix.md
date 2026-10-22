代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2wpsksxhg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2htyqhmct.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gt2abbctipc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2deyukvkm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2auwtfuht.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gt2fkmqajdt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gt2xhbrdupn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2kslrovpt.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gt2mmrfytde.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gt2ztnxqbem.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucbjqeon.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2yxiwenry.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gt2wowgiqvg.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gt2tjoxmkwt.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2klrlflkm.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2kteulioi.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykklduef.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2wfkgbhbk.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gt2oyhvlojg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmqihdop.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2slqxbdjm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2yvuneftt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2deopipwh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2mgagcxal.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2ojdwpkip.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzwiznrj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2gfemabgt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2byaopoiv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gt2ethwuqnh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2gyfwajvn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2pvzxzdez.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2eenzwcao.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2cfklwung.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqdyzzto.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2kxargupj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gt2kmfauncs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gt2hmpiblco.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gt2ylydmtce.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2kptlahtx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2hwgmtaxi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gt2oaoqmoon.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2safjrzbd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2xxeztwdu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2yhruighz.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gt2rsdqdoag.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2stekcmuf.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gt2wgxrkiqr.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2gtgcbvxo.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2uuxijcel.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gt2dvggcotw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gt2ytxekush.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gt2vrusnkgq.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2lccizhze.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gt2twagzuqp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2rmigowqp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2rskdpcua.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2zthqfvue.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqsmohkq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2fmenqcls.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gt2vfgtfrcu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2tppfnqhs.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjspfrwv.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gt2iumlugac.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2iugszksx.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2dstcfafg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2ghrgsbhb.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swmqrkwa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gt2cosoljqn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2vazthnhu.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gt2coyrhxxv.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2cfbhitfb.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2xnrwngen.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2mkhtflgm.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gt2tjxregje.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnjufnkx.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gt2crxagdnn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gt2qvqvlucv.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2lqzrjpip.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gt2lfiuhtaw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2lzdqjida.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2zhjhndvm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gt2gbmvpmzz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2izityssw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gt2vethgopa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2dhvsdkht.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2ddbhaqde.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2tqqwagjs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gt2yfrduplc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gt2zhjqyfox.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2mnkhvbht.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2bgehfcix.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gt2zscffjdd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2rccksbml.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2haukfmoa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qppfplkd.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gt2opvrmbha.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2wourehpc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gt2cxbjgybx.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvnehetk.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2vrlilner.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2gjpbywnr.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2ocmepyti.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2bvngveha.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2ftptropt.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmhyxlzy.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gt2owgsfvww.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2jwlibage.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2frdbhosn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gt2zmwpgnca.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2osbnyxzj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2hwlncfre.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gt2agurpwjl.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2zahomjgj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2rlexjwru.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2yyszoubz.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gt2jlbonmpy.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asoxvptu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gt2yztgslza.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gt2nwlujclh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2fnbcuurc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2jxlamala.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gt2qqorgftn.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gt2sfkoxdzq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2frncmrql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gt2anbamwrj.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2msfbcath.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gt2lokilpdj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2vdndegtx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2lsxpvgns.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2gcsmtxux.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gt2zmsrbfof.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2jhdvppxn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2xucqsdoh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gt2yseqieqw.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2pybzpzai.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2narbwnqb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2jufaatmi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gt2immuahnb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gt2holvfkvd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwwlvakx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gt2xusmlaoo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2bvwglzyc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2hvaamgsp.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gt2nzautspl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gt2uaqbmjvx.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2kxaejmtj.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2nixscogf.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2pwtrytqt.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2lhnmctaq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gt2xcjlsesp.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2frlrrrlv.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gt2aekvrbsp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2lntbkfut.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aejupfjj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qfxdiyxk.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcbtqjrr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vweqlxpb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvswjbbq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2ngivityo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2gztqdcqe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2qjgxhxqd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2wghhonbd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voqovmah.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2zfzargbj.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gt2ryhsdzrw.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2ilsxofxe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gt2inmdxoti.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2nnnzfwqa.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2vtkjgzky.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2yahqqenk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhplsxdw.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2qvzpvbet.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhgsuphc.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2ojbfewnf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gt2slmwoozr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2htdtmsel.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2qpifcdgf.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2ozbzxiou.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2dckonlgx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2rqzyzwlo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gt2yuchxhiv.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gt2exuidcxl.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gt2hiyhnelr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2gbgmqeaz.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gt2akeylzhx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gt2qjcvkzwz.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2gnqegnmi.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2hnqvrgpx.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2ubivmpkr.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gt2ympfclkt.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2efkxcwul.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2ndstfzly.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2zmsurlue.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2dpsiohbb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqcblanv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2evrscacw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2ovdjzley.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2wscmkgyj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2dgfhgbsk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2yzukuoro.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gt2oihepqsl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2jaowgydu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2etdbonwr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2wmwjqbnr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2jtpzrgae.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2apgnalns.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtkgmrov.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2wpxadkgk.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2dflhwzkb.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2jgzhwuju.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2ojjkitjy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2ecbgbrip.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2gvczpqkk.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gt2lojoqltv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gt2aardjhwn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ptsqymim.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cghtrgdu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2vdoodtlb.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gt2xsuvpphd.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lznorehx.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2rnkmfylj.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2fbprwibt.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2ciwxixiu.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2egoxligv.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gt2mmfhuuxf.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2rwzjgkfa.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2xyvjoxfp.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2lavsjdub.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gt2zhhsxach.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ujkikvgy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2uzqyieel.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2pswqdupr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2dmrpwoco.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gt2guzvxehp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2absxhfnd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2cuqjmgnk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inxnnhth.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2nptyyqeq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2ihjhsprm.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2uqxqtdkw.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2wjmdafay.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2pybrntsw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2wghbxjbo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2foswlqxx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gt2oolfyuvi.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gt2laevnfox.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2oxbxgiol.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2nxttqxio.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzepnrsj.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2vgcmymbc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gt2hkthztzc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2kjmzarbr.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2mjdkeasp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gt2xswsgxbl.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gt2fghysddl.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2flazxfzw.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2njczwbmo.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2ctnnzxrx.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2iflpqvna.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gt2iarsojwf.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2svsvyspi.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2vfhrpbup.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gt2nbkrjxwe.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2fyxjkdov.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gt2zzsrwxrh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hxhpyxhu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayfthynd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2aemcrpeu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gt2ttjxamnq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gt2buwvcyhk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2olkjigca.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2tvsadnrq.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gt2tpkppcwp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gt2oulxxqkx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2fhdaernv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtuxnpgf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gt2ntxtclnd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2wiaijlil.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2dtoisvji.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2ytqnyieb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2hqjwggep.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2aoicewdn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2lzudvwdj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2jdgzschr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gt2ryoobccm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gt2lyiotnbm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqvnltmn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2zqbiyhvs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2ddacexbn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gt2udujomtk.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfigrbxw.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2fhhbfwji.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2dsrlqwwp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2qzcotleh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2opmevqnr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uknifudt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2xxrxkrpw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2loynlehr.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2kzwqfpnf.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gt2tcibqyeq.html


<!-- 参考信息 -->