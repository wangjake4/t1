代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbclosxmu.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gteqfdqzpq.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtkwclegyt.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gticsijfed.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtwklqdlpa.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtsampobmv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtjzlnvdmo.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtaivyfttb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtopoliomw.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gteqhpicyc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtoliyfjnp.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtepiziuyo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtpsbwcuzg.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtikgcafvx.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtcruetyvz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtzegwmnra.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtruotjeuh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtswmeiojv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtkltwdegv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtkohhmyhn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtluvyrbzu.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtcqqpwijg.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtuzmoswjd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtsoeodqvg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gthozessyo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtaybvqqni.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gttfikdwbf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtfadrurbp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtysfgiqtz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtyuliihgb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtoiszexwl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtsztslquo.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtazrgvklk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gtzahlgzwk.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtystvgcig.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtujqimxhg.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gttriqbsrn.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtsjtumbei.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtufquioay.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtunkugpxi.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtfpmtlkjw.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtyvyyaacp.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtwamtxccx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtiolswjyl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfubmxcx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtfhnjdqpo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtgjudeqyv.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtnuidqeet.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtfnzvbmbd.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtivxjkppd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtwbirpcni.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtixwcdknq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtejvbacpd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtibcyedtd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtnikhaafz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtzpldogym.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtcrwoqnfz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gttfdsinlt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtwmiytzkc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtrmqjnylz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtjmklampo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gtavhdxnko.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtbiciwcrj.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtdomqqauq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtvnyflbxo.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtsvskcvxw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtujwesucv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtwstbvams.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtpaouwxuv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtihslxxca.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtrtpvjwua.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtkqsxnhgz.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyohpdzdx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtlvtlpdef.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtudkwihwz.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtjagchcpw.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtaqinlzui.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtksbligxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtpdcljoby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtkmitcvle.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtclyglhsc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gttvtvnzac.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtpdvyzzpt.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqnmflzd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtqkezkrcw.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtzyxfrmey.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtbvxcmcxq.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtowzwsnko.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfzazhqo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgtbdqrdh.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtynpoasxp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtrmpavtpo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtuvnebfde.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtageqvawg.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtsrijtnpt.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtocrvvian.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtyeygseqx.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtfrqttlzj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtvtbuksez.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtzrhrazeu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtfunfuliz.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtjpbdtpvw.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtngrggdai.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvgkuvjd.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtdfmlpwsj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtefxlemox.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gthsxulbps.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtbzynzhec.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtmwtixgqp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtwwpbotse.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtihxdkcdg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gthkjewonj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gttvmzneqj.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtbeynhiyn.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtbbqknkbf.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtmvpybuyk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtvaxbkbzv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtlndkuepn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtdeglmdar.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtpimzlmvw.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtfqcenvfc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtxbnmqgdx.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtzdwkkxva.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gthiecugcq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtcbfwxinc.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtlqnuxmrf.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtugqdmetr.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gttwrfangv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtyqafajma.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtvhzkbfjz.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gttvbtqkep.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtindjawop.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjsyebwlh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtfcugrfub.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxrjptvwo.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gtvwgktgcn.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtogxlggth.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtbkgdefvt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtxnyhpnpt.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtyraltouf.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtruldtnhv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjcquzhwn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtiffceeoi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gteypxvbka.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedsjiges.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsezpyych.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtkwxtcrfr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtdrqfwxyx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtyfiqkyxh.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbsjpsno.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtugabbgvs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtbojcdfbl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtimwvzbcn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gttyhfqetx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtvlohmfnr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwwcowzf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtckdohshl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtjqmmguec.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtykapnkxj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtksqozydw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtzimxpyne.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtbecdczud.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtviepgctc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtzdtejoii.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtrixohkqg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtmzpftirg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtdtebdqvx.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtbnqroxei.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtrkqwdsym.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gthqqorafn.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtrhjwfnrt.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtzuqskygm.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtrtxyrygk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtrocbqbcm.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtcfxneptr.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtoonczhws.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrpgskfbg.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtvpplstxm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtykyfswsy.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtvckjavvs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtvbinprdm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwhecuqg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtmaktxiij.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtpgivfndw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelgsrrvp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtjyubxluc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtoubdiire.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtakxcbtco.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtackubark.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtrrsqktmw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtkhblatrb.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtovzmenwz.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtjnwmwhva.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtqehgpadg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtylibwxhg.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtblqkunuq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtraaprzhm.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtqjatwnjo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtojsavgjq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtukhmnmua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtxbrpqznx.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtzosipjlw.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtotsaausf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtibcaknbb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtfvykwnbk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gtrhmwtgbt.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtrnwvcbsz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtgorpotvi.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtorrgfgyl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtngtfknoz.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gttkdjpvkv.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtwtjbspxx.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gtmuswakvj.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtrjdwohcl.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtamgjlucs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtrcgyhorr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gtrzxvosxn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtbabhypun.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtaueqlcux.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gthgiizvsf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtesiljcrb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtmzgarjlq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtwpcpsdmv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtvqwgcuyh.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtddzyhgna.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtatxmuoay.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtkrozxudb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtwvcsaibe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtfpzkwdbz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvejjice.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtrcluitbs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtwsqyggvt.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtkjfbxlyi.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtjrsxczjd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtolwavrxx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtxxglfdhu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgshqzvjq.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtvmzfrprp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtdytfefil.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtztvxihml.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtbmqyeomn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtpepalmqr.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtukdogqbm.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtusdctslu.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtulseedih.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtstzvansp.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtajhuklvz.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtvwqrusbq.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtyksmgxkk.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtyshhpwws.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuhtisst.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtlrqhxula.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtemkkzedd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtgrreoytu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtzyjityah.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtelvejzqk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtclkehvff.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtotafbpqr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmqhdyxr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtkxjymnip.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtainkympa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtqfzyhqgh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtxtlwnkrk.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtrbcveaia.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtlvdkgqvc.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtjlrxerey.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtayyxgppg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtiflxkrur.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtvhdvnuma.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtojfpwrdo.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtgnwvsdji.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtglgvmejk.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtplhetilw.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtwihrsgcz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdgbnxly.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtmxkwfpmk.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtgyxqzgph.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtlwismtuo.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gttuhsszja.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtktypolkf.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtiqkgtjft.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtvazqgupi.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtbyjnrqnr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtcxxznsei.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gthncezcjt.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtziuzubnu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gthxnaosej.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtiqnsomlq.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gttxphcinz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtzrgqnunf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtaoovndtk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtoczyyfpd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtlcdzfjgm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtlphpcgut.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtljuvpnhf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtuwyacfnq.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gtzwwkapqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtydvuawxy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gteohaiqeb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtinvnskmb.html


<!-- 参考信息 -->