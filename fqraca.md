代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gt2fbnjiwmd.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2yvseehwl.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2pghekqjt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2ijrzgygk.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2augltqpa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gt2zhkmdgbt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gt2xauxgqnr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gt2gdeidugs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2apaxinjg.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2lpoyczkk.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2hcomgtna.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2ddjrcqrl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmnyftzd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2vvsyuzsv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gehbhjug.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2dekoesad.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gt2meuxsfew.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gt2irrzyssw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2pizcuubo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gt2zlevlrbv.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gt2mscnceyj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2nqqgshba.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2zvtasxkj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2eftkgwsg.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gt2tmqxzlsh.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gt2hhpygfrs.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xphrlcpp.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2hbukdesh.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gt2wcgrrqcq.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gt2nateqygc.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2tgtdvqvj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2cxeantpx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2eoohdaju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2ejslmnzj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2kpdmreqa.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2dkojpdjy.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gt2rphyziwh.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2enqotiqq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2gmmefbds.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ricwcunt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gt2zfuxwhbr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ooixousx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2falaxlie.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gt2sdnotfry.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gykzpabn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gt2hrcroujw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcmqeugj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gt2yhqqrtxj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2odzzrbuw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gt2aroujovo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2pdetvamp.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2aflabyom.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2cmkwcjvc.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2gvzmzkly.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2dkpitkfq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2skdvspqa.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2abjrmcqs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkczzpzp.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2dwjgkhxj.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2dznmlthg.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2wizkrpfp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gt2bduesvxy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2fmffinji.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gt2cduegeed.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtbpfggz.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gt2szetxvsj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2sowlgkuo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2rykptvlr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2bjyviquc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2xfjfmwus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2zjgsspcx.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxszrewt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gt2svpfcdzv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gt2zedhpzmh.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2tfqarpqn.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2wytmvyda.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cffehsxj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ztahoxja.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2fguvmvtd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gt2vxqjgllt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2vkszfikb.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2redhcbyr.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gt2dfxzknqw.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gt2gfoqsinr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2qbgzxmmh.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2hnclujhr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2ckoisfms.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2jjwrsezj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gt2eipnbqov.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gt2tjufbdjj.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gt2lwvwpvvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2bduzdrpa.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2cztqsnok.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2zwphanux.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gt2ykaylgyi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gt2hwwbvnrz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2jgjqwkwa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2qhxchgjk.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gt2irjavmap.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnmxmmsa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2lwrcnjoi.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2cuowsofp.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gt2rsbcbpjm.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2nkcjzyuh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2emekbuzh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2uvaaoaie.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gt2temhtdlo.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gt2syuflnee.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pptggtyn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujaocdur.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2fcgeygjc.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2kddxkvxa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2pwvxjtne.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2kuqnynpv.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ftvwagfg.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2vxxrpugr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2frtjhhqb.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2wdedxgqd.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2zjzjodaq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gt2iofanabj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dqpywnia.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2uvgautrq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ylqzzben.html

TS:   [...arr];
来源：http://dali.zycfv.cn/Article/details/gt2qvjbdrbw.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gt2aslvvdwb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2epxjahte.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gt2yxlbpicd.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2xucxrxtt.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2kkhfilce.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ygxqvmwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2fyapdqps.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2tkpkattg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2fotfpwet.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2xuipjqmc.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2sryunoqr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gt2uevohecr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gt2nynhdpyc.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxgrtxoz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gt2uzcxwcmy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2kolvaasl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2yfbkrnkz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2nnqgpfpu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gt2gflvdjyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gt2lbemfqld.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gt2iqqfueix.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gt2dueygbia.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2excouskq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gt2tczuljso.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gt2emleymtm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asctwoyd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gt2kdxbfclg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gt2xkowiffp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulxolpyp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2gdkgvppp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2muottgoc.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2pfljoxhq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2kuozcvtu.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2bcsggxoi.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2ooxzwmin.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2wdkazgty.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2pflbehay.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2ggjjvuqj.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2cawmognz.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2fnwnlmny.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zoveggld.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gt2ltjgajjn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2lqwsollu.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2qxoasjdm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2dydpejcz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2orrmwiqx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2fylapugi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2vznthkjs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2llnjjodt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2tiktitjx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2aiklqmml.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2otofjlst.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2dffvwato.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2qospwzst.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gt2vuarghcz.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysklwciu.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2ihjvsmvm.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2esyomvho.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gt2ciwtmamu.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2vttpqmce.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2okmnckmc.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2mtconuuw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gt2weumqahs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2ndhnqkqg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2ilfprsin.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2nyfwwfms.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2mjacwlhg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2bwhpmhdi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2njnjgpoj.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2twyfegde.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gt2xdnfdepg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2jbstajxm.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxfnfib.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2efdwsvvz.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2gkspgmnp.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2lkscajdk.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2nmrcwfmh.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvvgzqcc.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2hbmkrfde.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2iedxbcnt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2kmdikadd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2rtwnmcdu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2tqemswpk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gt2zuvbyixb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2bqhhbspg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gt2nxellaze.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gt2bfptxcxz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2artmmzqy.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gt2drybbvzp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2txtqevgv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gt2tjhiyhcx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2okifqtqf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2codkzqfm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2oohdxtpc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2xkheoivx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2ybertmgi.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2wycaipfe.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gt2nxrqpiet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gt2ygdawedm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2wkfjdniv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gt2pfrmaesa.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbmaaqdw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2dnsntwrd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gt2mkiicowi.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gt2cxgvddeo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejhaimlk.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgjsgdhu.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2dphulroh.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gt2htwfndhd.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2apdwwhcf.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2mewvmovv.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2khnugvjp.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gt2janrmqjk.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2pcahkkdb.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2micwgvth.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gt2oxkwlpcn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gt2wdjythow.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gt2kemogtol.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2mcipepkc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2mponlflh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2hgguoexw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gt2pxitmvnj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2zflhyafy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2hcglooju.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gt2xfmlsslo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2wggmcxzy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gt2ayqfjkcv.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2zmqbxqle.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bihyvmed.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2twpguqnw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2xcvwffxk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvjdupea.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gt2klwckern.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2oumyiuaa.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2boumjniq.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2uwncfyrn.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2wnxqnwas.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2hdvxtyzi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2xhtvbkxi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2ozjpieaj.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gt2uhekpyxk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbyojide.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2togqkzvu.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gt2xopbycpm.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2vrszvlgo.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2djrbyitv.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2qpzoiskn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gt2ebadktkm.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2uyysvene.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2itrxdvzg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2cfchadze.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2qrmdnsao.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gt2ggjmjajw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2kpodeqzn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2thhutrhu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2atlpzqrb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2geeeybqy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gt2ekotgrak.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avjuilvz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpxoarjw.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2dymmpeyk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gt2zhijwgxd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2gnkppqoy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gt2urbjryyc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gt2ivrbelfc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2skqipxyi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2owngojfc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2suylpedb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2bvwzpulr.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gt2peqhwyid.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ntcfgesm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2ceodtzij.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gt2azpuqman.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2ituyfmfd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2aclhxujx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mlxcbren.html


<!-- 参考信息 -->