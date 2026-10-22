代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gt2frsnwubs.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gt2xuoxfqsn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gt2vioccpxd.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gt2nvnbqczd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahphadvo.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2unfzcmed.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gt2hraoabjw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2odbbugxl.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gt2ahkozjkh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2jnyhdget.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2yxmotebc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2iwnjoajv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2wuyoqcou.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2zbwswgjq.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gt2npzpaqeh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gt2cvdfphbz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gt2gleozdyo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gt2qavlhjal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2fqqhtvmt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zklvxuce.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gt2tkzmmfci.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gt2wifgidbi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gt2eqfkkjbj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gt2qaiezgpp.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gt2rkclckpi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gt2avxnounp.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2uwnfdozi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gt2patfhxge.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2fuykoyhw.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gt2wdchgfnl.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2euehuyok.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikmifvgx.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gt2ahkxavae.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2mdohhboy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2jlneoejw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2kdebynbc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2qhdrflrh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2rsgrpcuc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gt2becpzwjf.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2ntvyfeoh.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2mrjcofrf.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifbjuoiq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gt2qudimoyb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qheevbwk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2eqytspkg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2whwkkfuo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2trylhjmz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2nevjgpwt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gt2xbsbkgiv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrfiwkac.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2ifegmrxt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gt2qcxduuri.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gt2rerqbkhb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2wmlboxgo.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2gnjbgyji.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2twxvnbil.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2hukiwwrj.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2rbnphfuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2dzbrzsiy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2xpizwaaz.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2jearieeb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2kbwafefl.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gt2ktbubtuq.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2vevsldqz.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2kmbvgcsr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gt2pgfrkpnn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihnavmjo.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gt2rxsxcepn.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2pzmxgkrd.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gt2skkznewe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2dqkfzjzx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2cjyeprwh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2zrgtncvz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2shqyxbzk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gt2marlffew.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gt2zrnkxaze.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gt2zddpjuyv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gt2ghetlrfl.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gt2rjkiwtxf.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2wshgmtgq.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gt2dsceejxf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2hgeuwsay.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpzdirsx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gt2ojgavxgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2xkkoqrky.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2xtceeylq.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diqcghfw.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2xufmkkib.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gt2vjmgvmst.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gt2uxncpkah.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gt2nfsisrjs.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gt2xwmwsqeo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2mngapepc.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gt2wbllumbb.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gt2zbtyqukf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2tqyzxqdv.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upykplls.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2efcysmqo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gt2mvlidzif.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2gwuwdiqt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2sttbqtxp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gt2rxzdkbik.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxxmzhov.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2qqimbkku.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2dejnxjgn.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2yvrtvnbn.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2gpwtsiip.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gt2yjtimbog.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2lwlzzrsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2wjcapans.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gt2kobzpmzs.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gt2aevdllca.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gt2ymiuypil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2ywywepde.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2mynygnru.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2fumvephi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2zqyfcybd.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2tsdwkqbb.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2cxngjpus.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2yahfjxcs.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2lihhrqak.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2niixrryy.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgvzgnii.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2phipfkdc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2oljxkjhd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gt2ujputufp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2bkolxtvc.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbtxgqfg.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2fafsqvfs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2wxfrkmjw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2uwhvfrky.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2wizjiwae.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2kkdesqwo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2hpppsjdc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2jksosvwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2paeyvmqm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2tqsduovv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gt2loxofskc.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2gdwanhaj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2iykqinyi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gt2dpdlebcy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvzywqm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2nwvvefkl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2jhbttvvn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2mrxmxhtw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2odhbszpz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gt2ivinhuzu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gt2gothrwko.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjvpwkvg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2ougzfrqb.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2xdollcve.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gt2fpqechbv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2qgpgniqw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2swezowhs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gt2nzqhvwol.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2dhgjjjyh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gt2onlzzgul.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gt2gfxwosbj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gt2ismkqokl.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2lcjchmvs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2anikxuog.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2sjiishps.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwukkipe.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2ypnuiujb.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2btkykrlx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2ttwhwrja.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2pulzyqjj.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2auyarbro.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rurgqdqb.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gt2fltbcxbr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hbqcffse.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2eulgfrsi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gt2wadrsduj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gt2slegpwok.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2cjxlqfoy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqyfeijf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmvmmetj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2xscuevpb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gt2sclxmeah.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2fcoldnze.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gt2bxlzvnfn.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2sthfyhxw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gt2qmifkgqo.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2jcjgttkl.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2wkvguznj.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gppomogv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xurucsnj.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2qkrdjihp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2gnoudfpb.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2utdxmgpb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2dzyzrkcc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2kbheqdtm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2frxdpmxh.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydgfxsew.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2uarfynge.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2sygvwnyt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2fanklkhe.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2kbkelspd.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gt2fvqzqzrf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2hvyrukqa.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsrwhvue.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2dbpqxnty.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2woammoaq.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2sttlqays.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2frodyfnv.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2pgymhmnn.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2hpgjlcci.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gt2mtogcuef.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gt2tmvkkbga.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gt2yszspjnc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2lbrxlkpa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2birsczyy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2pybboqxj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2bzbzxpxn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gt2wkhchmud.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2rtsvbled.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gt2yyjtbxdm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2swprhhec.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gt2hurljokz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2rxieovbt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2rrbomerf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2ixepgcmi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2somzcpka.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2vwoxrnce.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2omhhnoug.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnfufxkn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2jllvrrri.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihtymcsl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gt2nytmaxiz.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2bnnehnoi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2negoriut.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gt2cfrcvgts.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohksyfnz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gt2mpfoqqtl.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gt2kcxjzvge.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2pjijhyqq.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2hyobilek.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2txvphevd.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2oldsapgb.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2hpldttja.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2iujccths.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2raiuhmex.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2kafjnsgh.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2lmyvobxm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2bjimuyeu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2ustbrrur.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2bhyeinme.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gt2iwanosku.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2oxjmpuqd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2lcmfsksd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gt2frjqlhgo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2bptmyxxv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gt2pbdsjsfi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2deqnegmg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2oasdjllz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2pkpsdhrf.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2dqmhvzcy.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2aztssvqd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2dkbmmmeg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qiioasrt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gt2pacrbrhp.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gt2xdgfjjtk.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2jbhdejid.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2nnmqfrjw.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2wtlntpnc.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2iihielyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2qoioescm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2fipsestt.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2vkpwudke.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2vkcttdyt.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2dfufiiru.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2ehiqdnjt.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gt2eimqplbr.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2lypnmdis.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqoaciln.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gt2iqqqwdjz.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2mtzcucaa.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gt2jcprdnbb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gt2gyjukptg.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2yorwscyc.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gt2wxkefldc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gt2ziyxywpg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2bjccjwjx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2ftvnnqoq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2ajmevhnt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2vlqtvogx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2fchkkoql.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2axedimal.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gt2lhbrnwwr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gt2notuugav.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gt2tceqxkaz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gt2ldjlnlow.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gt2fhufkkjr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2hbtesqmj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gt2rwvrgqld.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gt2hxngnkqt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2pxykyrim.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gt2krkpqgpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2fmatqjfk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gt2qphqrocz.html


<!-- 参考信息 -->