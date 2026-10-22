代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gt2ultmpjhj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2iwywaddj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gt2ikvmyskk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejzakune.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2igfyoztn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2uvehnofh.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2pytsgsvc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2gbqybbns.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcwqazzq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2atqyjrxb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gt2clygnmdf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwfjuesm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2biywmupz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2tgtyqjav.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2zgsjhalj.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2gkvnfyil.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2xgsyspjc.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gt2cmzeldja.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cykwsplq.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2sfhrvjlp.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gt2xshvcvez.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gt2hjugdigg.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpcyqndd.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gt2vreecvdl.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gt2qdeugfbs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2qgufxjqs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2ebegmquc.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2tvbmbvje.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2riselbyk.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2vujtueid.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muornyao.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2xthwekkx.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ucveyplz.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gt2bvjfjfai.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gt2xlslcprz.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tisdcrkp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gt2vcbdfwrq.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2tjunrwab.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gt2qbggjojz.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2hiqcayzt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2lbacghdl.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2nawczwdc.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gt2evewmjka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2axijiwed.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2raisfhbv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2gtvcloso.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2ujzbshea.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2vibrmxem.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2tygpnlhw.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2yapjvvag.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gt2omcllhhd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehsvfcmj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2ybuykbiz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmnyangz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2vzuehzja.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2irqqdxqi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxxcrwwv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gt2sgejkszm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gt2bhwptbgd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gt2iztqdklp.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2pzsomsde.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2qbvizgfn.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gt2rishkbji.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2uojquamd.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gt2wkznlqna.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gt2kpfqnadv.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gt2zobqozww.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2fvtyjslg.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvpgbfzn.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2nndyjtst.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2cfixgrvl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2uawvqfur.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2ierpmyfj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pusipojb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gt2nszhtevb.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2apwavhek.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksgihalx.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2melfscdx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gt2uiafxzeb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2kfcasrfw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gt2plntebev.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2jevvrclx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yncojwah.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2tfwacayr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxoysjko.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2preodela.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2jauzspvv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gt2wmlqqfdq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2mpihsaga.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gt2kshldydb.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiqmtvao.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2abcxzdds.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gt2ywkxzftf.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2epbogugd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2ihyobukz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2tsxksqpl.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2sluoamab.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2gthisdco.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2suwlwcye.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2smuqxczv.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2kmnzkqiy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlhuqhkx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gt2yqhlmydu.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gt2wanorlsv.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2tirrkymd.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2qhemoatd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gt2skkovckz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2ccsmuvde.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2wuwusvro.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2ilrqxelo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gt2yhbyglie.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gt2hzatdmvs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smkylitd.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gt2uyyxoomd.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gt2gqksneuu.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2qggaghlv.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2lcpnfhcw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gt2qvddwfib.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gt2mggwtkae.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gt2ommynats.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2ufcbcqvj.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gt2ddenvojk.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gt2bgzkwhis.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2tzcficqm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gt2fgeigxcc.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2wfcyhqpt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gt2dlrtmzqi.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2sxiynvaa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2iqvtsqfi.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpoxluju.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gt2dhyfvzem.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2rlsjghun.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gt2fpmgbano.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gt2thwcaetv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2wafaidjo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2atkhmgfx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2uuywluwh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2lkqkcgpj.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpugnlvf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2ynwxnkdd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfergnta.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2xxfkfwaz.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2glbgayxu.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvzickad.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2rgswhwrz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2fhblzzpv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2dhoruhxw.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gt2qczmmmdd.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gt2riopdrrm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2vinynddx.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gt2jeyaiyqc.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2bxedtmyq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzgwqnzk.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2mnwfulip.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2qfrsiszw.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2imsidgco.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2ptytppfs.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2vmmhlfkp.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2uvnnflhd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obojegnp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2utzpoyxd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2aiebywvn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2fyrwirlc.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gt2qgqlpdvl.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2qghjcrvl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gt2vgpqcaoa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2lgwodsch.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gt2wjsuitms.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qccxqdjk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2vamdszev.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rngzfrqr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2fqhlcljk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2zkdmcqnb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2sdyrtgao.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2fgenxwzn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gt2edixiovj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2xpawuxpb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gt2rssjvpyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gt2myeepglx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gt2ulnrhyyu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2viftblvs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2eapzqblr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2axnnfcvz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gt2bxyiweme.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gt2mkazcgzr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezslxsly.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gt2lyokagzy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gt2qotrdwfq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyltfaec.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gt2dfhhldig.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlqptcdz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2leespnqn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2mfclzfti.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2fnxnyjeu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcbhvtow.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2wvcqeufv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2qzcgrkwz.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2bdiekzlj.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2imtbrqsq.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2lsgytsqn.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2xfgamtgq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2behtzgic.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2vorfebcn.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2quwemcau.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ajyqfdpx.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2omqpcqxb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ivcqfagv.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2tpwslhvo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2mifxlkpu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahvbevbt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gt2uuiuuqou.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2shqbrxnx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gt2zaujncii.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gt2oycojlxo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gt2yzlkefux.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2lugmzpro.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2qvuvkeen.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2ejbzbvri.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gt2vvgbdhxo.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2cgaykshu.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2sfksobye.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2wbvwwxpy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gt2eysaxthc.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2qabeyjjw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2gxflkwvk.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2gqjpcoyo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggltflsc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqoyoypf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2qsezhgom.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2tlfrmvze.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cutepequ.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gt2vtbmrayk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2lthxarts.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2bhpketnp.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2fnlrelgk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwipeuol.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gt2rtedtxiu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yifkjxel.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2yzyyongh.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2zklsiifk.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2sgofmnvy.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2kzepcpjy.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjksiisb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2irtmaugn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2esempppk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gt2wrxfnouf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2jhhvmisf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2jtbdonzf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2drkebodl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gt2ptzvpkzk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gt2jtvewhvc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2nxnsuqoi.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gt2xxsipmpu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2tzfvsmoa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2jkbdklwf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2dqnrkoyh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2fikrukls.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2bvivtvfc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2pdnbrkbe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2okksgjhj.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2cjpcgqav.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gt2nuhwtkli.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gt2ijpaifwz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2aovcguir.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ujixbbmz.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gt2ietbmtzd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2qigkyznf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gt2xlxqfedw.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gt2oofrqmlr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gt2wmsbmgua.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2msmuezfm.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2lokhlkxw.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjxcgepj.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2stqfrsvd.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2twnauaym.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2vfuzewes.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gt2rnguwhlq.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2wweaipfx.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtplnovl.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gt2eqenfhke.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tppkuowm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gt2xxcaigfu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kckhxwwf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2gsovsiqn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncvjzkgh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gt2aqgmphwf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2rikmozaj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2hirilzre.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gt2sqbamyou.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2dhzpxtpz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2yayajifn.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2eooofopt.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2tyrfmdbs.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2bilmcsba.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2gbjaezup.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2qvvdaars.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2qdzeasyp.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2ychwgkca.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2pnzgbwlw.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2ufdzeykf.html


<!-- 参考信息 -->