代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtaezgcdrd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtltlbplgv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gteksogifq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfljdatd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtquzggtxa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtfgtnkjqd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gttbscsaqb.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtkxanxmzu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtkmyfhjmf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtxyjrtror.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtqwnzqlnq.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtuatsviek.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtfuuggzbf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtwfhlifql.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtjqmaabsi.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtishorddt.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtqolnqdge.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtlfpugzbs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtmobgetom.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtjxhwwuhu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtmxmnsndc.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtbrjbkthr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtvfkuhtci.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gttmobvock.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtwokwirsv.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtfceoqdia.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtkylbsyro.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtlrukuwog.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtsoijaavi.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtftgrstse.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtqsnnduke.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiybbiop.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtnjiqaiqk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtgdagdgub.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtwudbiubr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtvixdzyda.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtujrplvdv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtwibsvfar.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gttfryyidj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gtatnadzed.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtmasgdiis.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtuwyeaxzm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtizvobyzb.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtaaqxnbwf.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtbxaiezcf.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtuejtvhyo.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtpuoqxtqr.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtshuhpeee.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtmxtednfx.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtvrxwwfkk.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtgmlosxgs.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gtkgiztgom.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtybgxtsuf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtcdbxflxc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtlcmxhtnw.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmeecuea.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gthfcchfrc.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtmquyrogi.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtokvtaobi.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtwofzkzyp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtbaoqbfcd.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdmoszqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtsitvoaxk.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtuwhtvfzg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtqfvizcyc.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtgvarlaae.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gthegilvfr.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gthaxdvmwh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gthtrwrxkg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtvmyilqqi.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gthuvhuoku.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gteodrrphr.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtafjxnuwz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gttkbaxqxr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gtmddxkglk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmmuuvwj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtszkhtbsr.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtcdmxyntt.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjlddhfo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtlojrexer.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtyvtmmvmb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtswnxpngl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtwfyctgdl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtjdbdaadx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtzdrlttmz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gtnnqeaond.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtfmcbpvtm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtbmbphcte.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtryrndlzh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtrgoluxek.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtnwuzdjlw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtxxxcdznb.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtvxuvdiqx.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtgjuxzzxp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gttcvohifo.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtjuckahhv.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtjtcnfbvb.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtkjjyuhkd.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtziijmfvy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtjofcvuui.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gttdvjnqee.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtexlbazjz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gttomelyat.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtesschgcc.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtopoglccb.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtamlqcsux.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtqzjiedkq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtezwiqsgg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtzuesdzsv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtwapsdglw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtjwywgged.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtiigiwfyd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtjaxuyzet.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtinmpdisd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtmdxfvnql.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtailpeaoa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtehbfhnrz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gtpddfpxis.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtmbmvpqrh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtfibwjuhx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gttzifsnai.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gttmjxdcwv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtocjnbngl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gtofccsdgv.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtygrpqghe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtkedpofvb.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtjcnlgfgn.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtavyjsxbe.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtfevmrvhs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtcijakinm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtrojvncxy.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gtkwnbuazd.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtjghvygnt.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjhhaozt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gtlkjkqqus.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtkewsqtgc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtorxgbuxi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtcyxjtvsf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtzieicvgt.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtrivskpgj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtokbyrgpu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtwkhbzpoc.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtopzhtotb.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtmimbxgtb.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gtfzwweiii.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtphjkgymb.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtevurqpay.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtwpbvnfbr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtbowlgmsf.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtdemdwxbu.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gtghuyleir.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtkvwtlofn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtxrhvjdjc.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtnexbtdhn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtylgzkocp.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gttyjkhccp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtyvfezzyx.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtficgqhyk.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtviyobcid.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gtmcmawzdl.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gtrnscyoig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtuiglfdhq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtgwhxrykp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtottbtjlr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtgecwcruy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtoqdpzpkb.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtojbnbfax.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtnenwgsab.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtdywcilgz.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtwatufvge.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtsvrkshho.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gtkxkodtep.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtptdvotew.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gthagnnbyx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gtvtruibdj.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtdzrhnmyg.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtlhxrqsvq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtxxtpwany.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtvmpzundu.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtvlknmdzt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtrxgcxkml.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gttgckouxs.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gteojbnaux.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtxjglnnme.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqpqwxmz.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gtxnzublll.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtxkvycyrd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtfadywawa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtwsprtuoy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtuzzhzvwd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfbmusoxm.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtoluunicy.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtvysrtzpe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gtutatwrjf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtzwwpycuy.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtocisclbk.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtossrjcay.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbikqicdm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gteozbcgyh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtcskxydwb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtbfupyffn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtmuvxbxwn.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtndbftzgc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtzffzpiyd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcuzskyls.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtvzzqgzmf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtgyaubbfn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtyltcpzpw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtavjasccz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtrjqkahrn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gthlkkwewi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtmzwampvo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtwltxujxe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtpgjibhzi.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtezpkhyms.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gthakfqrsz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtyshoeolm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbegsvjbp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtisyvwngu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtihbygxlm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtrmjvvvgt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvfeevhgr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtbczvmxcc.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtogujmelk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gtupdffxkf.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtxzvqucde.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtturqyepl.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtncixfbnq.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtszithxnm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtbzxdhijm.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtfdcvxwir.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gteqdssrhu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmtjuoyhb.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gthybzhehm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyevxvsdc.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtqjczqfko.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtcougrhjp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtcgerqjui.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtklvoyjaz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtxnzflflu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtpxrgpzrt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtfidlzzdl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtvngsmmic.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjnwvcgfv.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtpkbkpkpv.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtbkcgcwfu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gtlnxcbfpz.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtwfziseud.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtubkegrzg.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtizdbkfwa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtpxbywekq.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtsbisywhj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gtzakdseqp.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtufsyckrv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gthbbejupt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtnucdpfpf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtracymgbx.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtofifykts.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtqrktcpzv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgraoaixm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtrfsibnij.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtvugoomcl.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtjvqujelq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtytqfgpab.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtgsaifuhn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtpytuhhxi.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtdyrzdbuw.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtiajfodkn.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtazmgasch.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtiujmgyow.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gtcpvdhhfl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtnrlkazrm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlhldcgf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtcijwcnmh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtczpvktgf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gtzfhumcmd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtxrtmojza.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtllzdnamv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gtlndhijzf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gteuxvbmef.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gtqappzwnc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtcwhnlswk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gtbgratuis.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtbxzepgdr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtwfgwpyxt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gthsobyqdd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmsjrlyy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtjoyizzmo.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gtsadlhljn.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtsruygcmu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtgqvtpxgp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtezetbccf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtphmbgdmh.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtaxeipgxh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gtmxkicclj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtsdjbplpv.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtjeofrdnn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtqaeuamkk.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gttcmseygv.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcdxdiax.html


<!-- 参考信息 -->