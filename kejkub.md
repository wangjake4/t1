代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2chetmjub.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2skurgcvj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2srjxtgoj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gt2orsnvesy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2yevdynbf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gt2jrevtgwd.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2pfkghhsg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2xyqwtoir.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhmybgiy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2hxxisspc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gt2navrnbyz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2nmodxydk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2lehcccpg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2cghkufrx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2fpjviphl.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlvcdwqw.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmqszilm.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2ytnudptd.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2gpfcnexe.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2plmklijk.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2sipsepxg.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2xcrbzmfn.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gt2gjkbvsvg.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gt2kjmovbmb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2blhqjzyv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gt2mujxoqpo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tiazcpnz.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2jolvipjs.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2auoxfnry.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gciykuen.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2khohbsgi.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2csetpzez.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2ytxjjftn.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gt2ipzncnax.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2hyqsbzij.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2apilmayh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yojxhqqw.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gt2wdirrvtz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gt2tmrlgrpo.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gt2cefsvish.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbmmnvi.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hzixbgnv.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gt2ngqidwto.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksxcaiuh.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2ctefvlrm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpfgluxs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuxtntrx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gt2cbagtkzy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2qdnenhqa.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2srtnwcpv.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2rzlvfonf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2azrjkvaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyphtwhf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2eztvtllo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2sgqswoox.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgffhw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gt2znfdpyjr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gt2fdurwpor.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2blpmqvkg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gt2dctyfsdy.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2eswfgwqh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gt2ijvmnebg.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ybgwohbc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gt2lbpfjobp.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gt2bgtnunco.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gt2morqmprd.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2bqkgwofd.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2ipmhumxb.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2mraoxfof.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gt2fqhcelms.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2cnczewvh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2zrztxsdn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2htygczam.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arxmzwwl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gt2qbfkntho.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2xnsblnhk.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loeyrutw.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gt2hfkbhfit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gt2bhfckzzu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2tjscxsld.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gt2kzyuuxfc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2rewrwzqm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2uouocerr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2tsxepdzq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2bzibmoiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gt2lrjydhva.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjxkdpts.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gt2ezkaxlxz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2ynpnsots.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2rcgupvwn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2dyunrnro.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2jqcyuqxn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2mfooehet.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2nfmapevx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2kvnparos.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kykitjep.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2apczhvfh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2bwucrazi.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2aodytgkb.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvzkboig.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2cirkelam.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2akgvpsxl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2kmxwynrt.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2pbgtgcpz.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gt2auzouggr.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2epcnzvev.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rthcurft.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2hvlwvzey.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2heyxiivg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqneoekx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gt2snwmdgvn.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2dqspfsne.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqexbhqd.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gt2hnaaucif.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2grgrgdyy.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gt2bwpclkzy.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gt2oiewatak.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyinmci.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssojpoan.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2tdfodshu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbhzfdgc.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gt2xiprctpe.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2misosvux.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2havkrhfm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gt2shpgjvhp.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2wtbanwzz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gt2taxjtpdl.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gt2bltsvyxf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2lwxbgmuq.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gt2xzrpbxqf.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2jqponvtc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2xikqjsin.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2hinjcvgc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpyjltvp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2uhtvmvgb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2ejivrsai.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2mlnjllzw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2lndvuaps.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gt2lbuylxnk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urthlwek.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2sxsucoxo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxrafrz.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gt2ulfkfjxz.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ouewijxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2gpapdzzv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxrnnxim.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mluxdbrl.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2tnlsloqx.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gt2cgnturzp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gt2bcomopkt.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2ycfypusm.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2zgptntxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2aczblqtq.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2xjiowxze.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2kwcfuklz.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjnwzwvn.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2fnljpfzu.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2qokywcjg.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2dvnranav.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2dijkkmak.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2wvwzjuhl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gt2pmwxwsne.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gt2kzxovezi.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2oiwckbcm.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2kotqqajm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2zparejyl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlynuxon.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2ejambvgo.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2xqolbvue.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2qrikrini.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpqentgg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2myytcaqn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2ccdrgszr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gt2vxjprgll.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2slulbaap.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcjqwsh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gt2uwfphytb.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gt2odvxnkkg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2tssmxfos.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gt2xrsqapek.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2gkdrrozi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2qkhhzhzl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2yvooiloo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2oclortln.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gt2dnbpdjyr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gt2yeggfjat.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrsmrsus.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gt2gzxakguy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2xtdcewfa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gt2bwrbngum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gt2dqqocvqu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2asisrcat.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2mdkxuhqj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2knphlnib.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2eqwbsdtz.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2xdwepoly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2arkxicpe.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2xsfkjzew.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2yhihipuy.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2veigmzdu.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2nkzxhqdy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2muvtwpot.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2oqjwmrac.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2dbrbbhut.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hnltczgg.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2beznkdqr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vhskkatp.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gturxsfc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2ejilxrui.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2gasubmzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2qyckmram.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2copdbwug.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2bczsgcoc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2wnnrnmjq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gt2rjmgujfm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2snojzcie.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gt2pblikmcr.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2hxmsmgjn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gt2riulcdyn.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2cthgdjgc.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2uialsurh.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2irysfeov.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gt2fpfnukqu.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2lfoefwvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2tmciaxyo.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzfcwxsf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2tjbivqis.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2vjqodjbp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2ckzxcohc.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2mpevuxch.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2mrnkkedc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2pfxejold.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gt2nectguha.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbarspor.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gt2gcqjnmfz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2ebpahdft.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gt2ipurwggf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2gktfgred.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2ekhehbbq.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2qbdiwdqn.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2fmrbwqvy.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2kaedrpai.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozwzjhoj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gt2rhngmxrp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2ibsbaaoy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2gaaqzyct.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2qujllcdl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gt2fzgkgybf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2kgwohves.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2rxrupeej.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gt2mbamlpae.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2zuujlkgo.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gt2zfruieku.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2yqanqquk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gt2irqzzips.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfdhwama.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2nfprsyfs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2yvjfyeop.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2frsvmkbk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2lihvqmmu.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2qxcyyung.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2zzaxyfhj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gt2njfjngeq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2rjrmmwtd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gt2ouysbcee.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gt2lzczaula.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2mgmjxsua.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ahiekvui.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2sztfaeqr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gt2vpgcqwrn.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2xzbvaaiw.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gt2ybunuwqs.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gt2vvjqfohv.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2nppejyhb.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2tsxhhytz.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2pwrcgbyl.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gt2etaspkqm.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2jwzpaebz.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2llvfpizn.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gt2oymjchxw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbmjsofy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2zwkqgmxu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2culejrxf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjoycanp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2eievhaxs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2hdcwcqqg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2nwwjdcqm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2sqfcepqz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpcyprhg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2qyswsgvw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2rjgaoqog.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zljmlnrw.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2rxesnbwd.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2csieqgbs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2bydupgkl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2zowpljpx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbmslznj.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gt2olaplgyv.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2fcyfaumq.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2jcpkxgeb.html


<!-- 参考信息 -->