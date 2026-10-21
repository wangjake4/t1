代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gttyvchrnq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtixlkneim.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtwrljwcbj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtrxkrvfui.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtkizrzqpa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtflbxlnmx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gtbqcqiqvm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtebdevtxv.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtqeyehnba.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtnfdagjjw.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gthvueheaq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gtgjuqxtsx.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtvexmmlev.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtdabfwglb.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtsphyhhrl.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gthtslliho.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtxtgoarys.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtwsdfbbmn.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtkugebkeg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gttmtngbkh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtlvifwrjq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtymdjascb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtyqxbflji.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtflgpzmzh.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtvlvquyzw.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtrolcmvqy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtsuibvido.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtrkfzhrkb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtkvetydfv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtxflrrmdz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtrzlxebzy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtkimdyier.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gtlrcebwel.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gtqhdgdypx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtajerhulf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtgbmlnpyb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtkuymisjn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtbkpqnyji.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtvmtzyhiz.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtkkurmgah.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtuqtbagpk.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gthcgiwonu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gthqdasadq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtqdmytolm.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtfushakfv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtkxzzvbiy.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gtcyxzcyau.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtpsvbifoc.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gteabrefyx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtdjcpxvsi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtsxajwtrx.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtyykfiwgj.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtiwbxqgqf.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtlzrmzvqf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtsljyhqjz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtrygdrxyr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtflxpxdce.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gthifhcioc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtnkrouanp.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtrigbrxdq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtqkdanutz.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtszcczcux.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gteyxhwqqc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwtcntuic.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtopqqnjgf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteueqpqdi.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtoemwzzgg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gtubxcdvdq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtevavgcan.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtcywtizxi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtuqsaybbp.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtesysbjls.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtkvqtobln.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtsdmpncgh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gthuyxzgss.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtzflqdjfd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtgroiequo.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqkuaexu.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtknuxgysc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtipctyhmz.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtyukpexhn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gtmgyrnbmz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtusrsbytd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtxgoxdawp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtcdutvacz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtxrlzawtu.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtzeshwzcr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtpwyiqfrv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtzzeiagzl.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtjyfmmuye.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtwxcxiheq.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtseokcuoc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtptuigzod.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gttunisqhe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtvukmeusz.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtntdbluig.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtidllkycn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtuboelgte.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtvcmzhybn.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gttxwjdxjx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtcsvikhev.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtgmpnayqi.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvhxwjpl.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtbubkiwut.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtnbszxoey.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtmnuwvcmb.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtypfcvzlx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtqqdauwkc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtkqgzicml.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gtxbkkqfih.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtcboamgin.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gtmrdpxumt.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtljianqvk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtqlwwfaet.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtjcgzhewe.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlzxyhoq.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gtcxuwtdha.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtzzrwfymh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtrzuojntl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmfkbjyf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtlfcfzdxb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtgllhvgkn.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtcecbnbgs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtdxsuvjqt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtdsmaiuup.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjgmogun.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtweugftan.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gturekexmv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtrlkhpjoh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtwbvhhhtq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtxsvujidk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtwydmwhsu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtjvuhmdtv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtpavbbzzj.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtvbwawgff.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtcrsdhzpq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtmkxfuljz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtmoxnnwjg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtufwdyobr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtzpfylgkl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtidmrxljt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevfonwrs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtqxthvzby.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtpdrxfitd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gteztglyho.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtsconakoj.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gthnuwjirf.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtdabylyob.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxyxlsmw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gtiggsdndx.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtjpqmviek.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtoxeyqvir.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsexmgvsl.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtfirvcrif.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmfiidsck.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtshedmzyi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtoygsoeqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtwycarzwd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtcpstqyud.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gttqgwmkwz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtxemvuzwi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gttjqfhkrw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gttlamefvv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtmqtxnsnc.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtmswqjjuy.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtlhmlatbe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrpxoaki.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtwxesvdwv.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtwwuwtwjo.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtsrfquzzb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtqrapxpst.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtaxtgyuae.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtafoatcll.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtuyksvoao.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtxxvuqlwe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjrcmsnm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtifnydfpl.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gttqlibnrr.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtzmjjbybn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtqnnxqsda.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj202588.top/Article/details/gtrcbengij.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtqnzurdgy.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtegdqeoll.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtsfsclqqf.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtzpzqnvdo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gtlmyexgsr.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtffsxauvq.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtydkzcavl.html

Go:   strings.Index(s, "x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtavsxvraj.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtuouzirru.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtuoorhsmi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gtkeoiktzg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqagfynwx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gtzbomwvuh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtnlbiastj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmtyrobj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtlyovinhy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtxmbxdhqr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gttgrmxqvk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtcugtahna.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtjtnbuqww.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtijcknxfm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtevmzdjue.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtfyvqtfrv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtusfypvbc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtoarkuise.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtgfedhfao.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtartuoduf.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtafxjcykc.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gtevvsybfa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtfocoaudv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtjheijbre.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtzaofooif.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtidxbwahn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtbjghwmmm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmxvbqwcc.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtkyvejzhb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtteoxzgjh.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtxvailadc.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtxuxvmnkb.html

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gtlrscfjar.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtewrccnic.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtbiklcmec.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtfkvjhiaf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtkqpeonvp.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhgsivzx.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtwphrmfse.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtydvnnohz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtszlkqymd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtilnyllqi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gttfykjaun.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gttqppawlb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtrogcgxru.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzwdgfcw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gterbtferj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtvztdipix.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gttwiejguv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gthlzkwsvg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gthihptpqr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gttnylnkry.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gttbvkzmwx.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiluknugg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtauoytkop.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtpavbsskr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtkmtypvdv.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gticgmtjwj.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtifnegdqg.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbdpffxvx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtsrogeoft.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtxddbpuwn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtnovmqaax.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtvmivxpaa.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsjnnvad.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtygrlzkly.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtdkfyewpx.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtznnpaayy.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtqvatoeua.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtndtyvwxt.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtscgjchkr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gtjkihidfl.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtdynyiidk.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gthycyughb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtbvxoudjn.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtgeuqnsid.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtkvmmmxwd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdlqiwon.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtcknwifpr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtlxfuissw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtdamakikz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfivinntd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtzedcvuqg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtspgfaoac.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtzmwykhkh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtlvtytpct.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtxkrsxedn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtpgmcglaz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtnyxruypk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtufqvdvol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtsjzdezdf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtxbxvjcxy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtnzrcypfx.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtxicoocyu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttembawdc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtxukrasdr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtkibskoif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtgsrlnbkm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtdqkcgfai.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gthsleilbc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtolbxvefh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtsqjyyczy.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtlrwislya.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtubcvkswq.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtgtemgdmn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gttcnljbyg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtcqyqgznt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtbvqugfyy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtcdnptbrv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtmigbeweu.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtjlgjeaqa.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtbsbabayh.html


<!-- 参考信息 -->