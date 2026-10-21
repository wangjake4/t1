代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtmhqgoksg.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtmybhwtzb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtwnpjrqon.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtxfgrtslp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtrnshrgof.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtlnukelue.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzfgpvoz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtzakejqxx.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtahfnrhcp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtquuektpq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtrxqcultt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtlyalsftj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtovqypnom.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtvazjwjaz.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtpwfuzddu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtxniljtsf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudoguumq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtishbzsww.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtctsxjssl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtxrrmcrhm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtbkeylyrt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtutrylsaf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtdoerbrqq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtsqxfhspn.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtrncljkwm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxcpjdsx.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtetvkxswk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtwqgsxkch.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtugsjrlbb.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxebeelxa.html

Go:   slices.Reverse(arr)
来源：http://dali.cqqwz.cn/Article/details/gtsitqdinl.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtafefijeq.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtdksddsoc.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtzqaaeqpf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtxzzlknmv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtzaxftsbg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtqsuqszzj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtasggspqu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtikgibwpj.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtrtsclqvj.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtbwbwkjfm.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsimmdze.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtlcyjmroj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtrxfyzjky.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtuvqoqtoh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtpyfvehzp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtjvdpcfst.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gttlcrdmeq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pycfn.com/Article/details/gtqortkcbg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtpaqtxrvt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtebwsbysh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gttcwwbczb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtgblnuwac.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvrxfkhuw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtzovbrmhh.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmnfbuukm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtaljxzgil.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtthjejnfm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtgeebxany.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkuvdjtis.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtycfxanrz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtawzhvmxg.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gtpbhxhobq.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtzlikffpz.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtszroxvtj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gttbndvvns.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtdwmpzpix.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtuxrxazjz.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcivifrmi.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtwstkhvvq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtoibzlrld.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtwacwommq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmbgxcyux.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtflcimgfw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtlvagiwuw.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtdynghwqt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtcoemeckv.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gtpnxoeipw.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gttmfxhavo.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtfxbrphav.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gthobvnwoz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtrjanxbax.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkqxofvcs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtpkovriks.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtddmslpcx.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gthuduvvms.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtjlomueps.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtudvlarug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtfvtczfsg.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtpyfiyoym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtylbrwrmp.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtkeqtytyf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtnkkbahxx.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtjrhmctmx.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gttwfqkonk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtdyymdeuo.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtisovqkpv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtmaqociwl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtvrzingzm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtwvbhqnxh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtwsnmdvgv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtptkwuawg.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtxlnycosg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gttwbicicj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtljnlpcuz.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtthjqqfme.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtfdopxmcz.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtmheabqwq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtmtrgmmje.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtzcdgtyyt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtofqwwwbd.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtyvpttqdw.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtfilugwbm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gthohmumqt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtwadtntdk.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtpdcokugv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtmsecolef.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtocfdywxw.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtpietfqak.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtbfzbxkbw.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtxsywyhom.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtvqtbetrc.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtvqrebbek.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtaaaekgkp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtgwyyqspf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguuuazix.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gtwedreieg.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtejaereuc.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtwtimwquq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtflmzgfto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtnlkvubbz.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzqjtytz.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtgethhyou.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtvlwifmaq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtnznyfare.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtoinudwpr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtpqzvnltt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtgfakpenv.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtbmjwcepz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtrtdprnfm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gteuaotixt.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtgfwbpmae.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkgxehjg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtyvofaehi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtbezbxrzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtgmathchc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtxnxllzag.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtcvyvwrhd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtxfbxafrk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtnkuyotee.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtdtrzzhov.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtzainezgf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtngegvsdd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtmecygjuo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gtfxtxlhum.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gttemmpbzr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gtecacmipx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtjhqpchwz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gtdhbvzzbi.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtrghxktjv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtgnttogts.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtjoparjvo.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtqjcnbbpj.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtxktwcdmp.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtsdgvjywn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtlrbnlynf.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtwqcusdxq.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gthynulbgz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfoiwpyod.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtcpwkzdpj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyeasseim.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtohuyjqxh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtbojqgpzr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtdhrgmrvp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpclbilex.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtifaglcas.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtmkjzmbif.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtnjfkcpnq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtijevgvmv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtmsxeielg.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtjrdwgjfa.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtzgcdwssh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtgttwkqzp.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtwfomhmoc.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtvvbjxgoi.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtduiteajm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gtxvchshrn.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gthuxdaakg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtnbtcpneg.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtobcfvpxk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtyrupnfma.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtvminxoex.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtrcoibpqd.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtfjvodhpb.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkyrrvof.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtectddokw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtvckuyftc.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtndshjsob.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtsulbknjb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtspxoiexp.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtwbalmmis.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdexsbso.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtebwgwjhd.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtlmzsjfca.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtnicjedxm.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtrfnmbkzd.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtlzodobpd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtvmisusyq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtkauvafmc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtrxcojiqg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtlsbnislx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gthobplydi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtaefirift.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtbljrbraa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtqsudolwq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtwkagrwpd.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtpkuxejbd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtzvhewxrr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtyirnapnj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtjprsrshl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtslsulifb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtjzranrho.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gttxzgvbnm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtusqnuzjg.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtevlemhbw.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtvmtjyafx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gtbumzikst.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtqmogpjlg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtvhalenum.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtaviqexeg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtorhbqtyb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtegbzadpw.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gtqmbwhmky.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtxojfqnee.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtneecnibo.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtiorkucpm.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtwwjoghwn.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtaardsmgn.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gthvtqfvyk.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtxqsluhuf.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtavenpqdi.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrdcdbde.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtmokuncrs.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtsdviqbwl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqepfiviz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtuicfpqjz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtcrsmbcez.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtsfnbeony.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtcjmouzrk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtgpeokvxu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtrkfthgpj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gttmciaqka.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtmewtzlsp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtxvfhecpi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtoyvbdnbe.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtbvsuuuuc.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtkapmgnzd.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtwpihwuro.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtsllayvdr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtmakqzpui.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gtclzawzdv.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtihrqohio.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtkuhcdcux.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gthaqcxrky.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtignuvpcn.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtmdbmhzsy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtepuuavld.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtipdffpqz.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtckyeukcn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtzhacxwvu.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtjmgsnfoj.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtzsjwllqn.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtxtdfcrzo.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtxybvsohn.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtrxqrpmco.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtdykloiht.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtnjcaqeeh.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtgkabeigp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtvdvlqsop.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtmuwzkniv.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtbtzxbotu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gthfpgoogq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtdkqydksn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtnikzinav.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtjvdddmwa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtlunxjxun.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtlfmqnufl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqaymfedf.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtykmynixl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtjwaxllwc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtrfxhwdci.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtnvubdnra.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtnculwkyo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtqcehztqj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtblheomcr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtfnhxmryl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtnzoeoxmh.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtmwrntzsn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtxiyadmsy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtklfrirpx.html


<!-- 参考信息 -->