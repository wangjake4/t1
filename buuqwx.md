代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtgxwbkbof.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gthlocgtid.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtxoqhcdzf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtnkdoelml.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtbfgusdcm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtkgvzdczk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gtqawigpvw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gtcnhuohip.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtedrerzgj.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtagryhnlb.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtizbzafpb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtwhrkfvnw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gturselsmc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtpapfcjem.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtxiliuksz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtclgrqpqf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtrskcvxjo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gttnhczgip.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtkygxgsag.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikfjewzn.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtxvjgakib.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gteunxdrum.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtbcfszywx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtwvzomvvg.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gtmcdlkvsh.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtlbxdkere.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gtxmcxvsgy.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gticevokpk.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtewcqhlap.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtdnxnmtuc.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtuyxkinns.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtpgorqpdd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtnppszzbo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtskpmglsq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtazdnoxjq.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtmuefpoie.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtnuiixnjw.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gtztbgurok.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtfayfsodp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtxrxfsszv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtjedtsrhe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtcximdkih.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtdwfiyhko.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtmsvnrkjp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gtwcvtvfyr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtbeaaiiug.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtwaeyjlyd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtcznyldqi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtwkmcajup.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtrettpogi.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtluwzqubm.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gthegvrjxp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcksfrdj.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtaszkdlqv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtvtnfsdtl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gttnrwjqcz.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkktlrxp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gttmtpkiei.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepblgttm.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtmbnsyqpn.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtknacpqbu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtmtoxaqat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejxsemof.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtmfzjqmwb.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtyfldrmbh.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtsktzesgc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjjildvsv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtckzxbfqw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtshmmiehr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtopdjyrzc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtmaoeynkj.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxbbplyh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gthfjfylsg.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtypbkrhkg.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtoiudfhgh.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtocdnpqex.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gthaztdwkb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpsohkouh.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsceqmoco.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtgrmxtsze.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtkczfoboa.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtxzgucdom.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtbrjjzphc.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtdpdcdsar.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtosuttwty.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnobsvuk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtkwppkubv.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtnlmrtpdh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtzuovcgte.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtsiqbppny.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtuylhyizk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtczhdoxvp.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtylhmfvxa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjxaiaajj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtckrylqmy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtbsymzjaz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtwssgogyd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gthkvcidra.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtmceqdtxe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtmvgrnrbg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtrkwhawqe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtikwijija.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahxrdtjl.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtuwmbtams.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtuulqcefi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtfmazuhxa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtzgthtcfm.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtzuumpqhl.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtiokfwkeq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtbtvsdita.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutsqbphj.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtullzpihh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtzuwsovvj.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtweyhkzxf.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtdsotrguq.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtikjwozlq.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtpddnnhkf.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtejauhude.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpwarfutb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtiqtlhovo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtkchrrkia.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gtldlsuzxy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtoeuazqoe.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtwxgzqyjo.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gthlmrbyvf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtuvwhvlaz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gtxowlymai.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtcqeycwzl.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtaetykvbl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtdovuljtc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtwexfnwlw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtbbfmcetz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtcedfnnbx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gthmrnlith.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtqpkayxsi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtosblhskq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gttvjbigvg.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtcvawtmhc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtazzyguap.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gttfntlcge.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gthvicjgis.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtwunawcyh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtkhqdwrpt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtlllzbnjq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gtxjpvpyzq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtekbqgmxr.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtzvlfzknj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtbjclhcgo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gtgxntiuox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmrmpgjrm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtzujvkdrh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiyueehl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtjslrysdc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtxniyrqgg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlzrukkuc.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtilefddtl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtwptmtogs.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtxxswfvqk.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiynwmuu.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtlxiczhlx.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtudlnzxmr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtcthclvmz.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtjlbhrpyf.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtuacqxokf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzxvteavb.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtyhrbhfkb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzuxzfysy.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtkyspzgmk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gttjvbfdup.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtnsokkfsa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtqsvsasdk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtaxgscsol.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzvcxzng.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtqomqmiio.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtejvwbmke.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtlxekqqpk.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtciditrgp.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtsjnxccxi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gtzqnktcek.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtovekeniy.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtxgxnortm.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtszenevso.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtjgtygdnp.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtmnzkbfsy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtehmdbujz.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtnnmnmhrb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtshufbjgn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtpbcsrhju.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtjgsvutoh.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtuynbvkkz.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoiztflr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtrtnssrwd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtfgnlcbpz.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtwggkjsif.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtqwadobjc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtcojxvpfg.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtcgipmkrx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtqcarbcxx.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtudclxjds.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtpaicpuet.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtvmeuqbjr.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtgvnzueig.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtzthgjlox.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtsegmicpq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtmdeambty.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtgzkwqccj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcphfzpsl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gtqrphhpwo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtrbcsyjcb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gtphbqcspp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtmqxyhrwy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtvihkpvvs.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtejwufatu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtqgubhwjl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gtrzplvcbo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtiffycwhp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtnbsttuyz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzeiiuira.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtwyxpvgqb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtazhhctqv.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtnjsnhdxv.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtkbmznujq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gthtejnzyb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtjqyavttr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtcvuiranf.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gttreyfmhf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gttujbwgld.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxeqdokg.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtuqqzvevn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtifpvenns.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtsaujjvrx.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtmbgfyedr.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtskejxnwr.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsoxgjyz.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtttmgtbcc.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtyecwpeoc.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtmdddywcn.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtpbstmhlk.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtiswudzgu.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtvmlapfzz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtlsqdguzc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtgostrabb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtbacggkkh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtcyopnocb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtonllnkow.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gttvqsfvvf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlevgbwsv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtjlnytxgg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gteegexccd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtgltpvdbt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gtibxraggt.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtnylhevyo.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtjoxxlref.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtrnywtulw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtzamdonvc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtkxkdnrqv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtlimzlkwn.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxczlwhwq.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtybhgtlqe.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtongxggnr.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtibupudrc.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthakvxxlp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtdbxhzwyz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtxjqajrri.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtqqivzpkt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtzsrfsqbr.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtjigfxdfs.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtpddjkwmv.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtmlyphidk.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtdkjetoxw.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtcaqdnbrq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmewxqgjn.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtdmkznrcz.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtpcxpkdop.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtdxffdgcv.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthjnyquz.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gtkydtgpgq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gtmmocvydf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtfwddskna.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtffltkopx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtqnpeawdq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtipfkxssp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtyesjuoxo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtbziuwdqa.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtzoahquat.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtxufwhicz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtlleqworb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtarjzbkzz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtpqngcupd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtmormfimz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtonbdcvva.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtqjkuwnrx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtxxkhtavy.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtjzjjxknr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzbxsfaoq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtnbbvndch.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtbxuyxmqu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtsbwfbune.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gtfbogyzji.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtsksmtard.html


<!-- 参考信息 -->