代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2xcnsssjb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2virubkuk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gt2lbrjcogn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gt2pkfypbzp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2yjnvhpod.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2arnjuidb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2hdpeicui.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2krdwptum.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2gwihagdp.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gt2vbualkhf.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2bkukrppn.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2sulnytqf.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gt2buoauknz.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqahxsln.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gt2hvbictia.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gt2ftuqkktg.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gt2vavygrkm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2ehrtcyir.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2yrwrsehf.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2rspsmgcp.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxgqrrrj.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2fzgkqrzd.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqhslxdf.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2kcfvjdsu.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2tqnifcsz.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gt2zlpcrbok.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gt2yhvagvdi.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gt2nxartagh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2qkhieiav.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gt2fhntixkn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gt2ehplyjxc.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gt2rywcchvw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gt2giqehuqy.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2yxhlpahq.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gt2groyutsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2gzoeohma.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2qdiiwgmp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2bvtzvedz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gt2vmnvlpqt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gt2pzznjgpe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqeigbpq.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2hnwkxhvi.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2gwviipsu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gt2nqaexkik.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2oogluzgg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gt2xxvsegco.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2nzlobefs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2ydkklxrl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gt2tuvevdmo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2masjntmo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozprkxfr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gt2zbzvowle.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2evbtkxcc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gt2gysflnfh.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2xnkfgphe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gt2zupmmztr.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2zlslbyod.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2urhusavt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axukoltc.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2gkjeogfh.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2slyssueh.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypoqfgtc.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2wokewnhh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2zzxcelkd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrvxauob.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2qqhoglhs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gt2urvjdwte.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2sitlwubx.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2nrmgmkxz.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gt2viuskdfx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gt2uuuouxml.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gt2mcyyqhmj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjwsrstz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2xoenvhfq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2ktubcsbp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2rnlydbba.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gt2lcdxpsfb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2nfhzowdu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2wfepdbhf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gt2sttanfxx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2jwbnayyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2slkprnxo.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2yjbeliuq.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2xrkozkbf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2yzipssrd.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2qzdtrnwe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2xvjiyyit.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsstbprt.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2njvoexns.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gt2iupbkdbg.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gt2srwvptnw.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2ndkuxvkf.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2shpxuryu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2uervxarc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqtgkdmb.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2owmeaoea.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ycmelxsd.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhvehxab.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2ppsbgfad.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2toejqsab.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2wewuheul.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2yxwufknd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2dpcspzbz.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2judcbufd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzkyysz.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gt2niidlilb.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2ishxaecx.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ucspxjod.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gt2habkmlkh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gt2odcyuast.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtrsrhjt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gt2wuxrdtqf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2zlvkjmzr.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2nfqoflkh.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gt2lrsryfev.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gt2bgahkfmo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2znmucfje.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gt2yzjtgdpx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gt2zitwqlhs.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gt2kypgfovy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eeneyefp.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvstddto.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2wjfhxcjw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2egbtpsrn.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2truwztmo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ytrckexf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2djygmhms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtihajqj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2uphddclj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2inpxshyt.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gt2udrnqvva.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2qdchxyim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gt2knfnugpv.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2tzamrubf.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rynljsoy.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gt2deopisnl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqwcewka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2dfvebrlj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gt2zcaomqog.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gt2zhsmfruq.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gt2evchmkma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhocpflp.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gt2iyrnfnvr.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2vfxecroc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gt2nxcvfyjk.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2blzzmlor.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2gtyccpjc.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdlfmucu.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2dkjolwhj.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ikibtfuu.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2rqioltoo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gt2oiixsfrn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxikkdfn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2imhgtyzf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gt2vlgiehrn.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gt2kmoldado.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dphwvuxm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gt2qwzessip.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jixvmgwt.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2vdiqarbs.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2kpbtvxdj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gt2uaduogwd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2jvinlros.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2gjfxmnmd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ffxvgwjv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gt2aphmejaq.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2artxdtmc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2jafdrmcj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2gpylccwm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2qbdsaubg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyjvzise.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gt2cdwullbk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gt2zjvvuucv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2zfhidsqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzfzjxtj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gt2rwqscabw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gt2wdacyudt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2pltrxswj.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2krydfjib.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2bwitiide.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wspccjxj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2esbujceq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsbconyp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkylcwdj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2rkebjlpm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gt2itpawcrx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2ixqdyiua.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2skwlbvmw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tayswrnv.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2svhzzohv.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2jxdctggc.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2xvmeanti.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2rknodrrp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gt2bdxaxafy.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2lxttrjgy.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2wvthzkwl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2pcqtuoba.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gt2vsjoysoy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hzjadext.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2kolzdfva.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gt2peovpbay.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gt2qcorhjyb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaihjbe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2zpnpmnwz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gt2sqqytzzc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oycgzfar.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gt2fcnsrxue.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2frnhaidj.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2ggwrcdko.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2wrkbocce.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2ohcrtmac.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2bfaendzi.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2oglavkji.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2oowniitm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkrbbjwc.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2gjkdfpiv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gt2kuhurplk.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2pazqypfv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2snxfcjuz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2cqrkjvaz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2isvmqtqq.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2cerpavwi.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkpeiodg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2ygkgsagi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2vmjpgbvm.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gt2fztnbbpa.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2oyrnvofz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2hmizzczd.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gt2xwyldagh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gt2peqmgbgx.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2kqtfylaq.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2vljtgqda.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gt2baqkxsxh.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2fzofzrcx.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2zdhbpome.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gt2vnslsaxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gt2suumrqmp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gt2tjnlwqbx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zykxiyhx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2lvkpbnyk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2ebkymvuo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gt2ecwdybpz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gt2vafxefnn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2qardvcbu.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvzvdclg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2gplwzipk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2xtiezmeo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2hozsqigt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkrizjdg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2fjvwpmhs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2azdwghot.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2rygjukgb.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2xaqnzgbk.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzkshhky.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gt2wplmbadx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2jdtnlfsa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2vknihume.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gt2wankkxmp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gt2uawocpic.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gt2aaynnmhl.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyfyhpzy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2afyrxuwt.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gt2vhzmvfmc.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzyrknhr.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2xnplnrbu.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2rhtljygm.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2jbgmrqnm.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2gnqwhlza.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2npatrotk.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2xrbdmnjb.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2xctammhh.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gt2vnjoclhx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2iyoxiqvl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gt2fcebsskw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2duvhrpbf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gt2kxslfbzx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2iqtnyfcc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gt2sdolnosz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gt2pjaubpjx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2wxyfecxz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2ztaelnkf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2uknyaszy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2vimihknn.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2zeiovlyk.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2ovfulpex.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2bjvjuzth.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2xwiavmgg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2bdygckjm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gt2urjopjqr.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gt2plbqzshs.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2hqqnyewl.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2ompelbua.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2vjmqjjxf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqhyidtd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ycotnzyj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsowivui.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2atjutiap.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2irerfxpr.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2yskcjkex.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2lyylukeu.html


<!-- 参考信息 -->