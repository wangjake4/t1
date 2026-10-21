代发 wailian999

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtcgjrrkic.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gtadztmbma.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtlivizjcv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtfwkcuipr.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtzweuqpxt.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtvbbvexty.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtlxdhwjyv.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtzexlosgx.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuqjgooe.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gteaddotbq.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtjbitlzdb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtgogmwrri.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtsbygkqup.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtajnqrmlw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtigxenowl.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtgvuklcar.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtwjzedzqp.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gthzdwohqx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtmcxufqgm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtquvkyfog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtzhpwbhmm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsmprmwl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtcproytyz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtuhtgndza.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gtyxgmpgiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtakcamwta.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtktpirmze.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gtjaktuckf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtuhypdjhv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gtdvcxfeim.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtkavbjfub.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyeepfmdz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gtvfzdviaa.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtzelhenob.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtsefrpvje.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtorwsbzph.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gtcicsfcqu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtoyysvqii.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjogitjdu.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtujmbutvo.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwclpnjxp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadpmwzfk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtlizmwgmi.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtqmxagmgv.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtbhqgsxsw.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtkfenryvd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmoqhmtnn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtzfbxypdh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtcklynjfd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtcqyrqson.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtlknpjswn.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtahlfjbzb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtjiyfpebz.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gttofyecxx.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtefcxzppt.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gthnzyjxsv.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtqtuswhjl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtjgbszhfy.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtgskoljve.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtwjnrlkov.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtrrfxehtc.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gthnukeqpb.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtktlvkvca.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtllocnhfq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gtboxzeofi.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtymwnhctx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gtchmlsuoh.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtlpakwwln.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtgbmgalfn.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtihspsjvs.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtvuqhulpi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gttkyjmwom.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gthzaqfexi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtaaxmhsxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtufnspoai.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtqwxygqhy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtmzxpunsj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtzohhqwej.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtdlucgvvp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtjoxuiisv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gthqlkaaud.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gtnmiyogmf.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcouflckj.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtfpnmsihe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghgixdvu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtftiwryxl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtjoaixfra.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtkfbvjfii.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtyqfnpqfu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtjjwqkotd.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtcpcpncpv.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtqoookyji.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtkomtqroo.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtymsyyxlx.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlebwckrc.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtmnrkfzle.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtezsnshdq.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtdgsifwgp.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtzmbnbqal.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbjbmveb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigmahpvc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtaisekdat.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtiizavlqb.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gtxnjrkvdc.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtmccondec.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtjbekunlx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gtptcnxbku.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtykvueivi.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gthmuslgla.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtyfbdzlma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtfopqrycq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtuqhmpzvo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtqhbkjtay.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtqbvzapgc.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtyguehwnj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtsslnchaz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtbeiyexzo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtlknkgymf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtyilesdpn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtezvkphrg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtadenbrxw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtiopvemjj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gttiasatcr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtsoynuljx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtucuxbqjf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtiscteoze.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtdxpsbehk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtmknnbpwt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gtabgmugki.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtacughgln.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtbrulwflq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhgmadqt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtdmveabqg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtiombsubh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtejxesjwe.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtcwemtjmc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtzojnnesp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtgcjkhnit.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtkhhlmrkk.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtvowvzcpl.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtnlktrrki.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtgkztnyhn.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtpxdmjzwr.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gttludgbba.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtceabmufm.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtjasrnzhg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyjbnnnba.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtowhwlwuy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmmycllc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gtoxashyej.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtsjbuvaik.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpswrorl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gtfkymwemu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtpcovuqzq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gtpbperdhk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtyadmsukn.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtxgcvkjkl.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtcadyamof.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwrpicpl.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtmbaxxcce.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtnpypjipp.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtorfglasp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtxxxgvgei.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtvucjpvzr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gttbxtlblg.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtzcqobpig.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtgfovgxqu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtvtnnfrke.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtmjxhqqop.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtlejxjmgt.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtttqkltar.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtllqjbspr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtkmvuluff.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtijrbfyhy.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gttatltfrh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gthpljtmnu.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtdlnnqgye.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtgipnvclo.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtsuaitjna.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtakzazlld.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gthscbnuhi.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtkvvhiizw.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtgbzhbbwd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtcqkkruwx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtbixfugkb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtfvkntrhy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtymiueqrc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtxexdsthh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtvjjdzruh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtgconsbup.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gtkdqsxnwg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtochbihmh.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtnxiflvol.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnejdzxd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtxqstbqoa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gteywgebrl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtyvnwuuia.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtonbgkhai.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtuwxfloyr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtrfwkmtie.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpycubqly.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwhdkuqq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtjpgotasi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtqrjawpjv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtwgnqumnf.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gtalxjxike.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtzcvoobty.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gtdoemchyw.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtaycpyozv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwwlampt.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtoslbhgnk.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtunxgmgaq.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtjzhquptr.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtcrzptsmd.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtbwyrmqsp.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtumqohsoh.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtokegsabe.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtygjnzubw.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyejjxtpo.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtcrzekpmd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkpicytqt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtgiolztlj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwmcfxuz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtntaqbfdi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdydtxvxs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtalzpjnrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtgfhenbph.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtocigusnf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtbefxjetj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyflapij.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtgfiyilbn.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gthgwrdipg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtgdskpkzw.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtajbxpqiw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtrrpjtqii.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gteayvholt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtrkluakys.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtyqnpnaqq.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtgvkgdhsi.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtykjxcblt.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtgazfrfbr.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtgraclfwr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtsufiirbf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtkjljposz.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gthxrfhhty.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtomgjvzzc.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtzpzzwmqe.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtzeckdmji.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtrjwhptgp.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtgvfbxrzz.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtpolazsdz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtfwzaymel.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtbmrtwfpl.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtsmktnhhb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtrsrwyweu.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtgqyxcjbh.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtlxfdookq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gtggnlmwkf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbfcicnu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtimxtruof.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtcolvskvw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtefznagbk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqlqoscd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtsqtseags.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyvvxsvo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtlzlfjxce.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtccxmwmba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucfedmiu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtmfqdnndj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gthirdgfly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtoslkfurg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtszlpigdu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtuuzjkplf.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gteyymrcvf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtazqgxayd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtpxupvkzo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtrobahstu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gthvjusxrf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtwgjaolun.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gtcqtpcqiw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtflduckbk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtxccpthdi.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtblploimm.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtgelcbmoh.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtvxebhkpd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtysubwifn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtfrslccoq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtelemtnqk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtahmithad.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtqggenniz.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gttoqgzcox.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtdkrbyomc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtecwuarid.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gthxfmdpdq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtzqgxzngn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtzjjcakqc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtwhhqossp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtquoyugjq.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtrclblcqa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtarxygmhu.html


<!-- 参考信息 -->