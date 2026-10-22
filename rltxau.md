代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2mlhhgyzo.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gt2rhyuukij.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gt2sdrpjfbc.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2dvbmyfnm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gt2nwonobvw.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2lowphhlv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gt2dljccatd.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2tosiyytn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrcnnzbe.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ogdrebwm.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gt2bvbnokef.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2twxvylvc.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gt2ddasrdin.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gt2vylqdygy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfvtthlw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xetqacyd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2cftryrnd.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2vqgomzyc.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gt2frrltzat.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gt2epxosnsz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2qodhqoqf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2cdnnuaef.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2zhxtntih.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2ldtnhhun.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2ffyozbzo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gt2tcwmskgy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gt2qmrfxsxs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gt2azufcrvk.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gt2odcbgbpl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gt2xvwasfrq.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2onperqid.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2zogiuyfg.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gt2mkfhhxnr.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwejaaaj.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gt2nzkxcfjj.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2akzggbqe.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2luducbcf.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gt2yxfwfvui.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gt2zcnfmiwu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2jsxugqqm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2aghwsleo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2dtfkpzpe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gt2ajxkndds.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2cglrscmj.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gt2zornnlsl.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2ylobnzdc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gt2zuudhlkp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gt2wglokazj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gt2ydfhuktj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2kqfcnpzb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2vbilqmia.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2xrljoyez.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gt2rmoqyjwu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gt2loqihxee.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2ylmoxhrn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2srpwyhhg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gt2ijamrerm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2gwafpild.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyhyhmaq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ukdcaifs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szvstnsq.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2skpwgvcx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2odhgffwq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2dgnwoich.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2zobapjbc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2rfhdvaxx.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2vuebprnb.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2ymofqfil.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2cpzcfhsc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gt2jhhubnpg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2soxhdtqg.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gt2tqpyoodc.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2hioidtig.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2qrztjrig.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2wdhcqyhc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2sqidfdax.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2jysvpjea.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvzxzgpf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gt2denwhdnd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwthczt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2nfplrbpx.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gt2snkhwcjm.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2kofhtzcm.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hpntcqgf.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vajpduav.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gt2yifwfgxc.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gt2aqflcqfq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gt2orcseaeg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gt2nwunamlo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myfbowbo.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gt2enlhcjpq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gt2nbzzzxih.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2opetzqar.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gt2entcjpxm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gt2lwrbyoqn.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnsturge.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gt2lrqqqdni.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2mthxkxsu.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gt2qomnroxu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2holwwton.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2txswpamx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gt2piuappzq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gt2wzxudnmb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2heeackqx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2uzuimccu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gt2ugdmsene.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2spvdaisn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2fnqspdti.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2igvtlmgm.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2wcozsmmw.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gt2tpyeeefk.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2pllihrlg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2nxzzspzc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2ccjjptxt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gt2fdkvkorm.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2fuauseud.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gt2wnjervwp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2bgrykhfw.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2wtzwqgln.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gt2zpfivtvr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2bgggxewc.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2xssrvqkr.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzoacetn.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2okxvxxfn.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2jvkweqad.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gt2gwvmiqmz.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2floyatnj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2qwlxyrqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gt2pqigfjrf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2gtueogbc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ubityigl.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gt2gqwgwfev.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2dotyryhp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nezhgmdj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gt2rsrlsypv.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2mgzjiybl.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2edvghbgm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2japcrerq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gt2kzcwqrpv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2zwfdenup.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2vznbbpao.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2vylqcytv.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gt2irlqerfm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gt2hllwdwrx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gt2oxmxwnhl.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gt2vdmyaodk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gt2jhvelubo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2kpbaiwnz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gt2wpbbsyhx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2gvvsoyqy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2brmkzxfi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2inxmhvno.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkzqblja.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gt2zkkivfmo.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gt2scahfddy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gt2eveevegf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gt2smtyhmiw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuujlsjj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gt2bxtdppjm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ituofght.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yyfwmcsw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2fmeoxpyl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ashghipw.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2cxqqgkdb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2mjeaquwx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbcfuucl.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymeowlsb.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2zjurlcqv.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2vvowamck.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gt2kvtumyrl.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2ifmajbte.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gileiuks.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2pcptjsbu.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gt2kskgfbts.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fznvwwmj.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2yasedjof.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2vklqqxsc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gt2zzkljqni.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2dbvdseug.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okmxucix.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2jgexaqly.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmdbqrrf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2qdtjrbkn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2gzswcdie.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gt2crxlksgr.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2ukxlsdkx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2bdmpamdi.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2pyytuuob.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2cvfiuknf.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vkvdlsfy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhcnprgl.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2kohdwcoq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gt2lhimlknc.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gt2tiyowkhz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gt2zjsyoclj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2gzpxmiad.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2dyekzbzb.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2ivudajhe.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2pkugapjs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2snnsxjel.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gt2jhhqppbz.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gt2kjusinkl.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gt2tydfbfxs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2hbllbuqg.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gt2mycgupyv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gt2aasxkfui.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2amodmlgu.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2wzapysan.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gt2kbovfrsr.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgzjtmpm.html

C#:   s.IndexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2ouczzpuj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gt2wcrvejid.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2hlaltrbo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gt2sqlszohd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2fiiqfesy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2pvpdqirn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2nawjxttg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gt2dnrojcoi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2qzamfuaq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2bmtwcxpm.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2oxejdgbf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2rywsxhlj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2bpcggley.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2afeutwat.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2qxrwzmka.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2qeksfbqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2pzqlzvyb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddjcjors.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2ltsccgye.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzdmnndq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gt2muserssp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2dzootmcq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2bveqcume.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gt2cgetvtzu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gt2wqizfwor.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2tdoffgko.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gt2misjvmuz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbcszphg.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbfyxohm.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gt2oagcatwb.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2vvvipbgy.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2arrsnilr.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2awiaxiux.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2ypuarkea.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gt2fwuwktzl.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2nlrwjruj.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2rnwwfdza.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gt2hmtfzozs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gt2zbnigfhn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnfaxtul.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2xudeqyjf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2wezzhded.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2ntrmfzgf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gt2prpkntyt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2ertkyfwd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2wmksyfru.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gt2nqflguok.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2ewfeusmm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2aotbgkaj.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2gcffkeba.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsazrzzl.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2bphlbzvf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2fjybexvo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2diyejnil.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2aocjoysk.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmusalej.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2olhrnckx.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2rrntvvvi.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2ynifkjnq.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2btabsbbs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2ozdzsljf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2pbbpgkov.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2lbedgiss.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2dbxdvfxo.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2biinyasc.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2ptoyhstp.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyjmfgrh.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2twyqcfra.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2dkpeygfx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gt2oonhalpq.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2akhjhycg.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2qpuifrmo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gt2oywaccja.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gt2hxwotkaa.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gt2jearyiwf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owesjtkk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2bblrcbgs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2tvtggjdi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2ikvfkqyz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gt2qfsenfza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gt2vgpleayz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2hfedlevm.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gt2vtxgnnnk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gt2qzuzgnbk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbkeweoa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gt2mxfudrjn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2sytketgg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2pcfuhpku.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gt2wxxwkuco.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2yrxrycxm.html


<!-- 参考信息 -->