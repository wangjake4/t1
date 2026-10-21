代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gteotniopy.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtmfiycgjb.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtlrakcztl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtqpqjomts.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gtnqyczdfu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtmvddsqxt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gteamkhdcl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtzntaswbf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfjoeeoxv.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtksnoyxbt.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtckguanrd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdeyivdr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtwgkdxplu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtqzlxnsfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtcdeaqetd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmldpjor.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtoetdtbar.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtzevsbhqz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtxjmsukgk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgwigbbw.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtcjjdkepe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaktovrcu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtsnjjzpej.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtrrhdkzlz.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtnphpzrah.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtadcmvmit.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtkschjurh.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtnyiyzovc.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtxacqvrnd.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtnkrpemgb.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtrdfzvajh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gthhkadcsr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtfsxaplzp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtwdjqahqg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtpfxmtlvh.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtnihztdni.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtruitepxo.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtueebtmxa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtltyynpyw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtjnbuvtns.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtmqwnqrpo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtyxwnmstt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtppswaobb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtkhtnalcc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtutrrkxza.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtmmogujza.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtqolvtfgb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtilwaxxee.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtlfilhunj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtseqmjpfi.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gteqwshvby.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtpjcymhvp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtbcmokxrk.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtdjhaihom.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtshoxoyrw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtwnmjccpk.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtzyhkeysm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtedicqcno.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtktvotfqb.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtubhjocoa.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtqxytljdw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtaahlzkgf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gteeowjcyl.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtczqlrbmm.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtyenibhew.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtxhfoqbtp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtbmsyfdku.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtbjlhyfqs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqlgrovxl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtovtuyeks.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtratkadea.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtrdozfbld.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtpkjwhkfx.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtsfceuuyy.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtrqzqvoww.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gtekcpiwle.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcqadlpn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtdmsvniov.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtnftguank.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtbuibenhb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtfeimujzq.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtqtfimczg.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtjaniknwb.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtwrqhejit.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtwtmvmsrp.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtigdskfjp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwisdljw.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gtnmgzssjs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtlsiwjfse.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtjrvthlpm.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtawodulfx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtnnnvakfw.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtfvqkqbuw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtijbnttst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtiinrcucl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtjnrmvxyb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtvarebfom.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtawlhwwtq.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtcpyobpql.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtbbeaaduq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gtnnoxsdzv.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtqaybvyem.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtertpsdbv.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtytjlooyn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtmnfcueyp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtnnpitepi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtkczpnazc.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtfssagrft.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtqlvvoixu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtvmrnadju.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gttsqsnwsk.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtkkcvzjtu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtnfszagku.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkocslkul.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonbgzfij.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtyripwopa.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlmtsnzd.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtuohwbjzm.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtovdpbbgc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtluiismzq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gtzcyljpha.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtzlaslmxz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxyozcauk.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtanyokvmj.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtvpqngnbo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtdrhvxspl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtqbnuydko.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtekrbkulc.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtnjgcpyvc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtssxfpyll.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtgenmlqfo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtflrxaasz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtvehhruna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtqhnnjzpr.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtokrfsvon.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtpftaqoqi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtojtfhwri.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtlxbhttgg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtgyvscfdz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtllzgiqew.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtaiyrlvfl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzotecdlu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtuoecczgf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdhwunjh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtilgsptrz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtmoggwiqa.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtlcpnfpaj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtfzvcuobg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtiwzbmpsj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtsxclwdbl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtvszewamy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtyevujfev.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedzgruei.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtftijynyq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiflgodsa.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtzegwmnkw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtysxyhmkn.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtozrqnegh.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtvgqczgou.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtvdhrhqpq.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtlwypichu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtgntytftw.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gteskragvk.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtgiybdqsa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqjwmfgfm.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gtreypgrcs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttxcpblus.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsovodxo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtxjdzdwec.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtvblccedz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtfhbhzzso.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtqqfdhsbq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbumykgsm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtccpbsbxf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtwshmnhgn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtcrtregzr.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gtmvxiolgu.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtafhkxofb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwieokmm.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmauzpwva.html

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtntafgaou.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtuoailbhi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtyehsupsj.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtefncjtqe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtrsxtcofr.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gteihqnztu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtgahhntia.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmutdcen.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtemijihlm.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtkpldbjrs.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtmshhakcb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gtcxfkrliq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtsofdbdhx.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtnnlokdir.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtwxxdfzwb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtrphvwoaf.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtapxbuxkc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtuqauqesb.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtjdbzsgtj.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtdosvtckp.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gtuxlppobd.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtxezkevis.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtgvgxptgj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtoydexiua.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtnkxzwvcs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtgbgpxdyu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtelqcwnci.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtgtnbamrb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtrnbeslhs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtgzzpsmtn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtxorkicei.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtltnlomxz.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtbsqlyszj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtvcnxslqj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gttccfikyt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtjiuiyxqb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtgzpptotb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gteyjakfpl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtffqlsree.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtmrnbwioj.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtefydpkxx.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtgeovbhao.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtzzbbaqhz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtjpvwoyoq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtdiljakqu.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtafjuyvhv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtxwvjpzax.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtfrkhbjnl.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtflzjnops.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtqlqpqigl.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtkcuskxcd.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtcroyupwt.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtyuewxmmz.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtglocyatg.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtqintrfoy.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtjnhigojk.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtbzkuoqdg.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsmxhytm.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtwuvdgsoe.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtkthjmszr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtwxnmqpcs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtatepdler.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gttpvpauti.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtjthahpvz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgcvizxe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtbyxzkhfp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtmncrwcdt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gttgwjbyrv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtotoizmqb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtjzoccnqj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbirjnlrf.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtwycnqmco.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gttnbhzocb.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtudfhifkx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtqqvudfyi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtzcfcrosu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtsedbzfmj.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglxlanuw.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtvtqaiajx.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtpgbtffus.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtgkedwjnr.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gttvpkqjax.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtyvicepbk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtxupexipr.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtjbimhaev.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtpaydeuxj.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtqqrinedr.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtkzbaigyk.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpoouktg.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpiqgixz.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtzjrwpvis.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtravcpibd.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtsleewvsh.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtplfjdxor.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtflmlnpvf.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyovxfhy.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtvcdpemjt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtocjnfdcf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtwpwtuxhq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtojsesxbq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyrjdofrc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtfigtrwcp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gthtlsetam.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtooxqlnet.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtmcwumzva.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gthhghiknx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtbqatfwub.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthadczlmp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtrqwnrsfe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtixcikprt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtsdnlalen.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtnkqlaqio.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtbtrnvfka.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gtcyfyfvjl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtmrkqvfsp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtirxqowbd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtpxcmzqbr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gtufxxflvv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gtimhxwbji.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gttrzsggpn.html


<!-- 参考信息 -->