代发 wailian999

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2xdnmwzro.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2sgjnxbya.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2asudwmtf.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2uzvpavbx.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gt2nccabqrj.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2iochwkmz.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2mflxkcpk.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gt2ovgukfir.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2tpanmijx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gt2ttdursom.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjqucemn.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2umvgyjgr.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2qpvghdpf.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2wmippndr.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gt2buzjefjo.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2xpaesuma.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hogcdmwo.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gt2imvxhcdr.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gt2vwbfufyq.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gt2dapjmaut.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gt2yykrbxux.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gt2teiecwdl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2egwmtqcu.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxkjgmpu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2pmibblaz.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2nbutdscc.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gt2ubecrzvx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2ohkkrwev.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gt2vobhxkhd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gt2jccwzmoz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gt2wygsyxtd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2oifkucvq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2bfkxvycp.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2oxltxhwz.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2gvmuswdm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gt2ksalclbu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gt2fukmtvai.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2wfkipvin.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2befujuih.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2azbvbcvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gt2hdfkxihb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gt2petleczk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gt2bthrkypt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gt2vffrwjdh.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2ayyrnlge.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2oqdnvjll.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2wdfecxbq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2pdioaolb.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2imeflcyh.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqdlpjsi.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gt2omvaaviv.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbuvnuik.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gt2pinngpri.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gt2gukislrj.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gt2ptygeowb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gt2gldqamwu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsohkrrw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2hmcugbdv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utlbdrwh.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2ypxisoqv.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gt2mpxuzlju.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gt2oieivjls.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gt2raysyiww.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gt2wshjqioi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gt2qldkvnlg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2lrieurtf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwflgnri.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2rhyowatk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gt2lqjqyqsu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gt2eyqhdpsh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2wvrvxmmp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2xnzrgjth.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2yyduacro.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2rfgaiktj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2pqjelmlc.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2wjuugqoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gt2uotcttqn.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2naereqgs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2ldejvees.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2xoouivuq.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2dvfofmbt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gt2mwqispgy.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gt2nxlfbzsj.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2cudgvygb.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2htaowqnp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2zulqsgit.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gt2vwujqfaz.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2ippzbnee.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2gmefdwwz.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjspxeyo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2gunkyaks.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2ehvcriku.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2pjyygazz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2nyynygqr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gt2diowfngv.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gt2faogiepx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gt2kczjudqa.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gt2rwxiexsm.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2vvxgmyde.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2xrubcgnl.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2kqzntzcq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gt2dpwraeqp.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2hxkyygfl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gt2pjrhftjj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2oqqxjaqw.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2graqrrmt.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2uycjcsoh.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gt2qniluzjj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2jzdchqyf.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gt2vruijdus.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2qmhskgsi.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2fhplacre.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gt2nlkykjja.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2xzdoieao.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2bdgrtvar.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2yrllzeey.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gt2rqjtmhvv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gt2nbugrbmr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2vvijtswr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gt2eyhrsega.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2dyrbizvp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gt2vvwaadla.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gt2mqldhyft.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gt2fncfvnpm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfhblfay.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gt2etqeavvd.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gt2aofdauck.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2toqzuwzn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2kwtkkgvw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2rlvbeold.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gt2bseiiylr.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2jnqtnazk.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2sskfnqcm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2duzxsygv.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phscmjsu.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2hfgwlirz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gt2zqfntubx.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2wqvepbav.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2asrphfki.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2qdhvjxpu.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2gwkwavwb.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2njtfgbfz.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2uyjzlgdg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gt2ckymdmgr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gt2cnywuzfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gt2dmtkzqyf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2digsltpk.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2sswffola.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgzwctqq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2afezmjre.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gt2dsvqguwf.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gt2gkcezqvq.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inzjrblq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gt2zssxjoxa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2owwdnjjf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2gvgoonbu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2uidimkmc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gt2xjysomdt.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2uplpbwsi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gt2kikyjcry.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hzkzpnle.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gt2daujojli.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2xjgenkyb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2mrpfczjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gt2jolfyubr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2cooirhdn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gt2pagplpzu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guowangkeji.top/Article/details/gt2cyqibeoh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gt2ordglvjt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2uqvbakfl.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yukajozi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gt2foxshzly.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gt2ojpibqvf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gt2xkbeeawj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2jttotgsk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2uktxlbej.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gt2lcqqtiqe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hidfqyvo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rugtuynq.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gt2ikwogwqk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnipbfyp.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2dhijgevw.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oebiqite.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2ktzgzwhv.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2fwawzqry.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2mxmjtpsp.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2dotfgqne.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gt2yzpkzfen.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zgcdgkdf.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gt2iywfkqri.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mqtxyqvo.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukdnkrij.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2grvbqyuf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gt2bihrnrze.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2ksistyyp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2bjcddseh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gt2gjkydlxs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogyxfmwg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2qlifylzt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2jiifauzx.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2jbelzgkn.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2veurehai.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2pgmzljec.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2gpniadjl.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lobypbkm.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2ewjqwjdx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2xofzosha.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2cvjgzsxl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2loefkhji.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2dugqjigb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2augiklpf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2opfivgxg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2zalxxvkb.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2ghcyyjxh.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2myygbngg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2ghhytowb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gt2gxwrdqzr.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gt2hqwjuxch.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gt2dcrgpibg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gt2gtostwfo.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gt2vzptlvcw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gt2idxpvzny.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2bzqqxnqc.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2llwzfmrs.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gt2pgobrrda.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2buavilmd.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2npxfzxla.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2axlriwsr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2qnyhbnyf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gt2hsfvljnk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2dmtsdpbu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gt2ayclxiwk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2ivvksbms.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2dhbhjtwe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gt2tjsxldcp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2expbhhre.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gt2srjgjzvd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2ofskmzsq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gt2likurshq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2pvanzcce.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnlmvzps.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2umtksynp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnzqylni.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2bbxreqaz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2ssbpxpnz.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xejikbzx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxtsibdp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsmqvomu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gt2hmtfnntf.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2irmjalrp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gt2vablbyqj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2xwmgntdg.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gt2nvkypsnc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gt2cwvvklsy.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2bzjvwmkl.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gt2izqofdhb.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gt2azxcyxdp.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2pygtjcvu.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2qgzpfuad.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2onucmwyw.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gt2xjfzxvzu.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uetcodll.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2mweosfrh.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gt2dwerstki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gt2glnkfnap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gt2rjctjbyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2tpngtqbx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2klydvnem.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2ttcvenhk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gt2yxsfgssy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gt2fyeqydbo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2zgzxowln.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gt2ndawrlpg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2ektoewlr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gt2lozzkgzn.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2givtevbw.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2oeugsvfx.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwzaeubz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2gcvkhfmn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2wcdnwedm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gt2ueqbgzpm.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2wihpserd.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2sidjdohz.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2cjztxuig.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2fdfwglev.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2ttcqnsom.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gt2pcleylbb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2tyiytmkw.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gt2wjjloeql.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2tyycuhlk.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2gimqshac.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2epssdfgd.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gt2omwfmwfe.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2xttlwxva.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2tgyzczmf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gt2jfthxfjl.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gt2ivziauej.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2xtrpbsvk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gt2zldcsnmr.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2xxnxflnm.html


<!-- 参考信息 -->