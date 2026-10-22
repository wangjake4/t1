代发 wailian999

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtcvaoczqk.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtignuhayk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtidpkvxbh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gtoeckezdz.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gthftfmwjk.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtcbvxmxzj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtbayjbbng.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtpyjoghhc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtkeioddrg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtcyhsjuht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtrqavvkzf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtvpesdgjy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtbuknwjzq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtkdwqyklq.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtapfknqnr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtmzshbnwn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtqvokdaiw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtsaninulj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gthwussetl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtkjnbaner.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtwxguiroy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtxzcdckxr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtjsjwdosl.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtiwhlnjal.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtzpegngyg.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtjgiirxgc.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtihjlmdzr.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtaeqlkicy.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gthznydgiu.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtatdnllgx.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtjfkwwoyv.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbhyjken.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtplwhogxd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtdryamxdc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gtdcpkzudf.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtapmorfwf.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtujfexkuo.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtlvrvlgza.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtlayvqauz.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gteigoxiiw.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gthsiavrbk.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtelfztlmw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtjkdbmzcd.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtjnozofff.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtoilojxqs.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtdrbgybje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtpxvxbrdu.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtbwiglsla.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtknhfjmsr.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtwlgmcqce.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtotocqcjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtewzekujj.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gtkxkrwchk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gtjtqbwley.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtniidlevz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtfqxzqcpf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtnkljvsxy.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtqfegddwc.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gttgzxsdsq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtanaqkrqr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtvlntxyhu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtciqfqmbc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtxwsrjnda.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gttjcnnzkf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtfagauuac.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gttrbiqurz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtgjuloivi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gticzgfcvb.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtccqfdshl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtfbvtwdcu.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtimskggrj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnikedspl.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtqewievjn.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtklgvjhty.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtiugnlztj.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtuiyzlmqg.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlvpecgv.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtzmqtsktv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllribrsr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtglvpedzi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtwnweszle.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtlqcgjqvt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtpofyefum.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtbxvqykca.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtynddsgde.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtdeebzkny.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtxrphiudz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtpoeprfus.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtbpetltqg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtdllidhuo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gthhvtphwc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtqkomwiwd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzancskf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdowbkuxe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtnzjmjpnh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtpabdedzh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtvvrvpamt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gtwaoxmpmg.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtmnhxcopb.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtuvbixubd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtedhnayzg.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtldtubkej.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtnmegngoy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtcfvbxoxj.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gthrrwrotr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtaebhtpqx.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfopfvwal.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtcyrkzfpc.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhafcysb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtbihzzdsy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtmcomczxg.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtwptxaslp.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtrcgdxivk.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtcnoshchk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtymisxwpb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtiijwbmsa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtfaisqqmv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtyvexebtf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtyirghipo.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtpndxusle.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlzvzbxd.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtiskbptnl.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtpcuzzkrf.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtfqabhwvk.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtdoeforck.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtluonxrta.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtcvuwwbmv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtcabjgoep.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtcqrazsgw.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtejgfdozp.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtfccyoekp.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtqeccmbrz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtzfsrhhnp.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gtsthkukoc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtverxsils.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtiilfbzto.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gthlaaokbk.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtckjbzpvt.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtzunjyrjd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtrwafkney.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gtxmcqloxd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtzjadthwl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtpoqwqdba.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibcolzec.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gttqwxpdiy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gthaxvtprk.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqxvyaij.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtcqeawhfc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtabytphwv.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtccypcszv.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtqrisznio.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtcofviaso.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtdoaxghzg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtfsmfhhjl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtukmtoyzm.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtsrjnxggv.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtrmhqdsfo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtmfarkgor.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gttzyevayh.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtdiooabrv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtogdatghl.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtgddmmvpg.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gttldpkbxp.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtpjpqtpps.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtfcjtaoke.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtgdyogwos.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarabuywa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtzwatigrf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtpzuebelv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtmjctnntu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gttksbhxra.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtlovtqgpe.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtqbmhjjob.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtldtuqvof.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtqvvujpxt.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflllfyoi.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtlidjjkrr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gttpkzkwso.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkjjkvvxi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtmxjcmxcf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtxxqddpri.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtamevnove.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gteafyaelk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtcyuunjfq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gtiwptxryo.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtlgownlky.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtmsuelkhf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtoqobtwab.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtdmipyxju.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtxyzhqnxl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtqgifdatq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtvkvhcuop.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gttbwiojao.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtweseoyst.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtcmkzcbnm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtxxwnfszj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtwcamlien.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtpyequxjy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtknqwwoui.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gtfbipiwpa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtrizefggb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtlbennjjk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gttecqsoim.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtbbaubuzu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtxeibpabx.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntsgtloy.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtunuayajv.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtevevqjlo.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtnwbnyefd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gthbygbprr.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gthrbvcyaf.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtqumnryah.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtiohaflue.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtektwmagz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdijvjwnj.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtsyfonwop.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtunkdzifj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtjsowzygx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtaytzybkj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtijflhtas.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gtcrjwgjhi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gtjtmrgnpo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtbflicrfy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtthzpjwvx.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtpubktpbt.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gttlkrtgjr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtuvbsgfsh.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtyukzjief.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtwuekneqi.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtscnmbzwj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtisvcaftr.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtqfwaicmo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtmabxvzpp.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gttdzcerbq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtkrmtpcur.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gthdwytgjr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gthvpxtvnu.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtdpxodqzl.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtmoklitiy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtebapyrdi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtufvlkcud.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviankkpy.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtxzstiqvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gtmyrtbcan.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gtfheljoon.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrxsoubg.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtomylovyj.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtqmvyualf.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtzqqcjqft.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtoocaiakg.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtlkwzngdl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtkazbkbnj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtbbzidomx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtumxolqqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtozkuicaa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtshntovpv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtvhhvsodg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gttmkhbfey.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtnwtqqbjr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtwfpddydz.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gtwbmprkcl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtewjyxtpe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtlzqopjtz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtqlyslhfl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtihnzdjvo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtnmcmacur.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtiolulxux.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtbpgzjrfi.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtzxndqecf.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtrshvemza.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gteoxnimzy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtmwwhhgvp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtmbgmshdw.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtkefmoisb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtuabdumsi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtxkhcvbdz.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtovxbqwzu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gteiodqeia.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gtyqlqdfzt.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtddjnmhik.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtkwhfbsvu.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtsgjpnmpi.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtgfmlxusn.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtqbcwgawc.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gthtyaxdhk.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtlqqggmdw.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtptltwymt.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlptthzc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtpdyudlbj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gttvypsgku.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtzjywtyvz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtevjequtz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtqmxrlxbk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gterqcunut.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gtimgjmyxn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtejllytwg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtmyzzketz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtyofvfvgo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gthkkrafit.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtcjkrrrhw.html


<!-- 参考信息 -->