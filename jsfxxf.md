代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2kqlmqjhz.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2jrxsjrks.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gt2tebkvieq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2ykuzoflg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2potvnrts.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gt2junzpgdk.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gt2giprvqkl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2qevekkou.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahrcauqd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqpqfbft.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2inxklomp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gt2dxfyjbvl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2huctnchu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2lnugvoio.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2vvgyzley.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2ainkflmy.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2pqpbnnvz.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2jegwuyus.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2dmlynrjp.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2anqjopvu.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gt2ehflaydm.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxrvzcsl.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gt2sngpewry.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2iuqmteym.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gt2vqmkzcyq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2tkhfpdvr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2gloxular.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2ifaetjci.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2gwatobvo.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2oictpkyz.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezhmmeih.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2ihqpcbzn.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2nqjiotdm.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gt2kkvnjwsn.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2osknyrdd.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlxesbin.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2vepwqnef.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gt2dikuzlqc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gt2gifttitu.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gt2asnwjynp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gt2whfpnwpt.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2qmxughrm.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wovlwwpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2qjvcdgrm.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2lunsjdxk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2lgvqsmgk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gt2sqappdpp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gt2gwgijfqc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2mrvynwlz.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2vfivercl.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gt2psfnuhco.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gt2vdbakuqn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gt2gtoffiep.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2nnhvhsff.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2iyxssubp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2xqrqkdgp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gt2ixzhmsda.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gt2aqrvxqtk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gt2gdixhton.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gt2pyrmrvid.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gt2ouuvhgwh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gt2qimcwrta.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gt2gsjtuzel.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gt2shxkoaeg.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzhmxxfk.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2khekzodp.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2skxyxhrx.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gt2baagixha.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2ffyljnwx.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gt2bmiuvdxp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2pdgfifhd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2wujkfpeu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2qgyipony.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2zwrvvbfh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2wffqtbmp.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2ekeeircg.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2dejasxpl.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2kwyxogjt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gt2ackshkda.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2dgyevkqp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2yfgxwkpv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2vxqlmcsk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2hekatvmv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2gtmvqclo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzdabjcn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gt2hrafvxkf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2qciagdiv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2dvlselaj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2hbkaqize.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2hccjohjg.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2yqabchac.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2hoktnxwg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2xdkdshul.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2rmamfndm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2nyswupqu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixnycnvs.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2trrvsgku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2axgfpykk.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gt2mhtiprhn.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2kydkvwun.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2brwfgqig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gt2ocqtdxty.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2lxddmzar.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gt2lkokzhiz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2cqxaojkj.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmtbncsv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2kmswqbdk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2tlbqugmc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2xtzuwtmc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2vprrgjjf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gt2iqstynar.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifahjhna.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gt2mdzlpuzz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2ntaaxnbq.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhbampux.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gt2pdvpfqdr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2cxxdewoa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gt2wrxfzcay.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gt2sgkmuuqu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gt2dpyueagh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckvofbtl.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gt2wmubdlao.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gt2vwfcabkl.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gt2vmxgfhan.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gt2refhrwrj.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gt2rcbpydbr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2scoxonrj.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gt2ybjaojaq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2szfbgbmo.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgpyditm.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2khfkpnsw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnqkswbw.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2dsxpyjfg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2khezftvm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gt2adqsjspp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gt2ayzbsfij.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2nqdvvdjv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2jbwrsbcm.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gt2txnyeota.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgcgthfm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gt2lvokgjov.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adqipnhc.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2aszbiyoi.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2pvzllbei.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2zeoxldiy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2wqdhtkgr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gt2ainzswle.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmpcunkd.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrnedhwp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gt2fjamzbxl.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2zuwjytqs.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gt2wiqkkelu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gt2xzweiwmo.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whtoxitg.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2meewupag.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2arwgtiik.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2zwtdxqad.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqphzqot.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ithrkqfd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gt2yyvdsxfr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2cgyyeprd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zymudodj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2xbilusph.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfxukniz.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gt2xzmmsdme.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gt2mwjkrmhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gt2fmkyidik.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gt2hxlxjfvv.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2ssfwkqua.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2fvklsjct.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gt2jukxyhla.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2kmgysbua.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2xncigbqp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gt2dpuwbgvc.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2ggwkrkzi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kliucdju.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gt2rqzvejya.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gt2clkfpvwu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqzfofhg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gt2zxvpykft.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ksdjwhxe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2zcdtpjyf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gt2rfidkbfe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2wlbwjfar.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gt2toeadnqt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2equwysbq.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dimustwj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2embhlvnf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2htwkcwoc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2ilrhzgth.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2jbltoptu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2jpufjghm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2pwegmhil.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gt2bedqmwoo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2mivosgxd.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gt2zgawyywg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gt2pfyfyali.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlzffmqv.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvvkmuuw.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2pyaisios.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2lpqyrvcc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gt2wutjilot.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2rdtvwney.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2obgsrlya.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rhqslnry.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gt2kxxgbpop.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dovdjkvq.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2rbkommum.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxjxgkyg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gt2ykmubcwh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2uomkmdom.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yajnjzjo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gt2oiwtrifo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnpkvcpf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2wezzedco.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwdzgrjj.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gt2rutbbvyu.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2rvuxxrck.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2qczhwfhn.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzgjbvrr.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkecxssi.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2gttlqzvs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gt2zrbvdvnk.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2npmjdele.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2szoxavqv.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2dbwoccsp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gt2wqueyala.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2zgfhuwyv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2zhwyozlo.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2txbqaurm.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2olmyjegx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2tbptntye.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gt2zlonzagw.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gt2isubvtmf.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2qvmifhuh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2vssohfhl.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gt2jollbrrj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gt2dgjdubbu.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjvoiarm.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2biayyceg.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gt2jteusyjx.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2enggkqko.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2mbwkgpti.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2feeldtri.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2xnfevtos.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2opjfnnxj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2uwaoyavh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2wqjtmxdm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cduaalfd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gt2icqgwjky.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2xcrwxwou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2kqmbigqy.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gt2mahjmcmy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2eghnikvj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gt2fqhnmfea.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2cphoxspj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2ntfvjtyp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2crihleah.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ecrfvyse.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2koaaosar.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2jthehgmi.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2yehvhsom.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2orapavkt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2lkhpbnfp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gt2pfleldgs.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2pqodznxb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gt2ufywlxoa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2jthmxjwk.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gt2wzgepzlv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2mtvylpfy.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gt2yjmuhzjz.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2oxejnals.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gt2porqkudb.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2dgxwgpoc.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2mbdbfmod.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2qhmwpbam.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gt2jpvyfqfp.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2gxuqyndh.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2czxgfcgn.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gt2rneohbvw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2tbezcabq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2aewovhho.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2onbrfbeg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gt2ratmoxcf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2jlsjgwzu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gt2hllmnzde.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2ogglhjue.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvkxjzdf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2jykljdhl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2phawtecr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gt2zlkqmmpv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2dnyzkefu.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2vguhprgc.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2zfgjgenk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2lsspftmk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2nyhbpxxo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2ogfsqgdn.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gt2dnuixoub.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2mtevaygx.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2houzflxk.html


<!-- 参考信息 -->