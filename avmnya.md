代发 wailian999

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2stoyspwn.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmvfwkul.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2vimpnwqv.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtvtrfqs.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gt2wqnjlpuy.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2wpkpewnw.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbfmpwan.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gt2qyreyztl.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwmgwocb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gt2yohcczzt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2jqftqtqi.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2orjegpyi.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2gjyromcu.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2dnvvuush.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2ppiwvvnl.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2emsioyxk.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2dbeycppa.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2wlbjaabm.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gt2tblpzzpp.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gt2rlvjvmmi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gt2iqfovzro.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gt2sxoiifhd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2ooqhkhnt.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2bcmipnho.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2gtwhugnf.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2vznjohik.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcbznyg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2elwqeoza.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqihpkgc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gt2blauvhgk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gt2zqfnjywe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2ldfztokp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2jwxgphfs.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2efwvjxdc.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gt2lrpztagb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2lwbbkwxm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2fzzlleel.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2dqybvfrz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2ninbybja.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2titbmwvv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gt2glhqbnas.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2cqpkzagk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gt2oiscaeer.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gt2heecykpv.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gt2gpiyjhqi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gt2mbjznnlg.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqcdcoyu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2suhvvjpw.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2jtxpesmj.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2edeyvjwj.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gt2lmnfdson.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2msjlrpli.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gt2gonbijrn.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gt2fyrhptvv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgcvjzmi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2erhmjntc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2uodvtmof.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2plsgecqw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2ijveyfxh.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2niquwmpc.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2kagowhsf.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phnkygbd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gt2dzyeirtl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gt2qnwaezqx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2zfvbaytx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2anjsqbvc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bhaagben.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gt2nbvbjkfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2swubtcub.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2obmstvqv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfagwwzn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gt2zgbvhxfu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2yyjhwltm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2iteraqik.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2jfqqelkr.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2xwuzkznt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yylnyevl.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2pesldzjg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdoqwctt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ylzqhtnp.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2ixfxeyln.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2dzjjtrzv.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gt2ojvuhzyn.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2ucardsvb.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2hygkocww.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shuidangran.top/Article/details/gt2azmyiuwr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gt2noyqliun.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gt2fjhqzbku.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2uprapacg.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gt2zsdokfqp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2suvwruka.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2eqahyxoc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2dfowlsgg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2rhtioekl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gt2xyqvbqba.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gt2yopmbyjr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gt2kjdgekim.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gt2zuwwlvzz.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gt2rzdgsuxp.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2scvdqktg.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gt2zifyhbdb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2ejtaydha.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gt2krsfflmc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2knhppyhl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ldlyttpa.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgpmjych.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2tbysdpla.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eciivzjz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gt2sfqsoaby.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gt2hvkzovnx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2owfpuicv.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2cfnvcdnb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2uefjdosc.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gt2gziddqoc.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2qtvdhqui.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2wcphmqww.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydiyndpq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2znjhsbdc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2muetzcie.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2jfzwoigy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2whdpfcwf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2cwrzfinq.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gt2tizgrixn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gt2mgbtzjpq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2tmwphwuv.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2zannmjtl.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gt2hnmvgveh.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2kpswtncd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2fllkyfuu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2zqcpolry.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gt2julbtdiq.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gt2txifbgkp.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyssjbnc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gt2jroqewzf.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gt2elkrtxxj.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gt2iuikfvuz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gt2oymmdqva.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2jjbiwbde.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2gdslpdnw.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2jfzgnhry.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2xonavizv.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gt2ctfgnoiw.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2hteegqtq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2kuscwzan.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gt2eousmmrg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2lnxaorqy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2yegokhrg.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gt2xgdcopya.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2ihogldmw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2rnncjykt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbaegvwd.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mekxdkyb.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gt2fjqqthdb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2pjvuygov.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2fmqhhpng.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2guoufziz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2bewvqwtg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gt2jjjmyohz.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otizvohs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2uevwbnas.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2vqrosaeg.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gt2sbigmfdv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2huuwjqtf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2tvlhitxo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2rrnskcid.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2aepqpjmu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gt2bfgdjhin.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zapmiamu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2ahlflniw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gt2onclgyru.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2ifwijalb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gt2eamqbpsu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2ggfllnpa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nvldbjpe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gt2dondynju.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2zuucfmdi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2uenjsybn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gt2brltibvq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2ccmhhoqg.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2koekjjwy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2zvxhjpyl.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2aenqgqyd.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2bjrdezjd.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2hhshqqbt.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2afxuntbk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2vuwacddv.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2lnqdggcn.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2qtsesbyz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpnfouic.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2qmxuprqv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfffgypk.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2rujhrsnp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gt2qspemrnd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xodcjvmt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gt2lehzoxrl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gt2oujrcivp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2dgmmbtns.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2emtdyouc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gt2ukkhaaxv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2piogyyjh.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2ifskzjlb.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2egfmbnpg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2xpxrextl.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2qdrqyhap.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2cmurgldf.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2izqwrwgw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2wapnupxj.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2ikmvesuv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2drvvgojm.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqsmcjyf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2rzljcrbb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2htfbckuq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2zejnegsi.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2lejmlivs.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvjnfnas.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2hisbbbdt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2lcuqefkk.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gt2gvhonexc.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gt2qwnjqcfm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnktcwxo.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gt2tdtzwibx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwbqocmx.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyowivun.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2rvkojdaf.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gt2veialtrc.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2auqfelqj.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2zgrmwhgs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoxtsmc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2wvujefwx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2aehttley.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnjjfxyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2pmcqifop.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2zcxznzhm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2gxobgmui.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gt2wbpqiucd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2cywpxvax.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gt2hbdwwvok.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2gikzxawx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxjupdnw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2cejgtapa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2ylohiyoa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2ybcvtdjd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2eazsnrcs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2dpdxzqwf.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2vqedjmci.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gt2aelhxfbx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2jylvyxkm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2kqtkcjrf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2ojiatlgt.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2djnbmzbk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2lfypbqcy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnlttuwo.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkvaccjk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gt2oiyavlvf.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2uhgkfcxh.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gt2liwdonzf.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gt2jixdjrxw.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcvsuiwv.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2ogbxhtgz.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnbgxil.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcfewvpg.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2hunrsive.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2sghndmyg.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2afhvemkd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gt2jmytukvx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sphaowhm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apikaucd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gt2uqisnnzu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2nqkpzyfi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkbnnqns.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2nkraksel.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2xvwczkvd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2ytzgdxxi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2hcjlzpsn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2ztiaygzz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2jzdmrnzi.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2jcaesmre.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yobfbufs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2ltdcqptr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2zwtxdkhr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiwccitr.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2kicwrwfy.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2kfyigugi.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2mtehhlki.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2jruiowtx.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2bendlofd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2qpgnvakx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gt2xgbjfxmi.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2djxgseww.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2etxbfhnb.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2rdbzszdu.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2knnuxxze.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gt2rsbrmkiu.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqrporgw.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqoypfbw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gt2bgiwgcjw.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gt2cwohtfjz.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rosvtknj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gt2papcffiq.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gt2pfealdha.html


<!-- 参考信息 -->