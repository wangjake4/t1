代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtajuqgcvo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfkqqoqvk.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtcsuqdcrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gtywyxyyov.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjncxynnx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtsonnybuc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtopkxtsxv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtrozwlkik.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtxwdsbmna.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtaqnswxpm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtbzsnnypg.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtkhvjdvmc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtmuuwjhuh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gttgspaitc.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtqkmwubys.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtxxlfqldc.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtiuxkbdjb.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtyrztieco.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtsugszrur.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtaeojwfem.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtswgqgixx.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtedbaylxz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtyfwrjvaz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gtafufdibk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkjycgawi.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtilkswnkp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtwhimtpls.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdoprymc.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtqlshodho.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwwgdhjn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtwkhacvan.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtcqiamqwt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtkpernqmx.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtloktlzla.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtqwrhddpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtaceixrct.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtiozkrqmc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtltlcvnfd.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtsroqsoet.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtxvoymxub.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtcmkzfzxf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gthkjayhyc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtrjmqemrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtghjlabtc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtwdcmyxdw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtbobcwypl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtkfzcmtnl.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtlyneelkk.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtvomsptpz.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvdxsktzh.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtysxdwrrt.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gthrfokhvw.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtdoixtcyx.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtgqmvqaor.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtlqltwejz.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtghdnyunk.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtzpitlnfi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtuebsswou.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtycwkmndl.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtyfatacmt.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtuvkrtdbe.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtycbsysjo.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gthfnowfux.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtadhbhnti.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtknsjcwdo.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtnnyknshb.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtqiwxaqvk.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtjuhscecj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtxfhefbeu.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtjgwfhuaa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtosjrrybb.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtxfjftfob.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtzezubbcj.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtgkfxrtmh.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gteddtpfof.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtggfrwpjx.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtjjcicsez.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtkoftjqkx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtwyrgfhto.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtfrnjymhh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtntmhyesz.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gttkxhwgdn.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gtblrzbmda.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtiaaewdnb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gtmtidhjwn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtuzdspxep.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtplxakoum.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtpobeahqt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtlcfxnsmr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gtswlhurrh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtckdluxcx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtszgsewtc.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtttqbezff.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gtfeajsbtj.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtoddhyfkn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiauiwyg.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtosyugycx.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtvkrovwgu.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjorcycia.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtpuxolsfn.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtkzloioqz.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtcbmaigsf.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtswlkunon.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtovrmjdtq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtuuqeuakn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtleptfdku.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gttuibokbt.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtwbeqsqdp.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtxpjyztku.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtktipnwiz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtmhzcwjqr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtvrwlpxjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtiyqmwrnu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtvvgfqosq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbyvpudtz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gttogpqcfr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtmfqxdpth.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtbvkmseoh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gtblsextyn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtdinrfklb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtuuommfrb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtlusfvkgh.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmsygtpa.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gthnlpsqqk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtsemgkliu.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtpcdbkrxo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtdojqeivu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtgfhvgldr.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gthplpwabt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtzcbpttvm.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtfnjimeic.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtugixgzyh.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtcwvltses.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtbmsmazcf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtfqlrrmdi.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtppyvwkgc.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfahmyut.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gthawpgxcr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gttbmqyvku.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtekzqgiix.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtdrgltvwu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtxcrzfgnn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gtkhbsowom.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtlgshlddx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtyujapvrm.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtzsexuyum.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gthlyrwkmo.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtuwtgwykh.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtspssxoww.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtudffcomn.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtupczcpmc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtsloflsve.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtpfdyjzac.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtkdtjwktg.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gtmbqdkcaf.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtiawioaps.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtxldpkeph.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtirpauldu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtkhpykzuv.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtqkvfcuwk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtjxztumrc.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gttskbtgbd.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtwakmxhqd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtsgwtslhd.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtluyujiqb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtjfwqovsm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvvhkdyl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtrhreuilr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtlnoodxje.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtpsjjtaaf.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtrzsthmqb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtrkbpbakm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtmyuczwqv.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxqcxcpu.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtarzwedza.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gtegylwqvu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtjckdgyzd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtktbwkbzp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtqqqjfdsd.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtoycgcrdk.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtzzdingch.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtpgpaoxkl.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtdapnodit.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gthustkifb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtjrddemhx.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtctgxlubm.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtbbfrimgr.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtqnxazjmf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtzxcabcox.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdqzwrchd.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gthvgbbxzv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtoczvfiwh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtqxbbytmc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtguwsfdsu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtduncamyy.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtxcsgnhty.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtscoizcnm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtkejulnnq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtwyhyzcjl.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtdemowuex.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtawdbmeeq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtcqfixdwu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtdcswclzl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtumybiljh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtwtgebddu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtdyelpvje.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtlmubdoyp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtqymegxqw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gthuxpobcu.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gtpggyjgpw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtijlbedoz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtjsegpqbj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtjqydfhef.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtzmxshiyz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtttdyujiu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtprbcooxp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gtpunjbjdu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtngqwzinh.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtwgvedkjg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gttzjifjhs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtdqehiols.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtlnknlmwr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtmrkfwrmz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgiqldhil.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtcgnlslvv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtigijjhtw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtguywzple.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtlwziccyu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtfenhtpqk.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtyxjoehrx.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrreszac.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtubrlcroq.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtvubhkltn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtgcyrkdpg.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtjuuctnen.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtrvhlmjct.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gteavjmzzp.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtdmewslll.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtifowcxfn.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtkyorjinr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtnjcylxsl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtmcelqzaw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtjxpivagl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtfkktoacd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtqoqavxjj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtzsbkoeyz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtgvexplam.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gthovcolru.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtqjumswxc.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtdxbzxvcv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtlchckffd.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtwpougsuu.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtiovzihnr.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtklysuakq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtiivyhnlm.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtpgboufzp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtmnnepsia.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtplevvngt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtykdecdmm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtruivyodi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtatympgdu.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtrsogfofo.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtczqahlcs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtleoqpsjt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gtyooljcyn.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtnnhvvdrl.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtxlyuxdyd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtyxqhvoby.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtvliojbuz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gttnebjhau.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtvflpyytk.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtgvitlfqz.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gtqvmiywyr.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsybminip.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtcyngslsl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gtqkodztlr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtobupoluz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtlgmdqipk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtxyzvgokd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtmxejtidf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gttcksltzj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtapvvafvr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gtpoulwxqx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtptitppjp.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gticxbugds.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtoifpwjgp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtklhyaktc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuzazpjo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtbzekjuca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqrdkhbp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gthmcwpwgz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtuykkwttr.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtswbtnyfz.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtuybejgcb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtsngkfaii.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpciicws.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gteqmnvrka.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtrfapxkpo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtbdqocqgy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtsfxkfaev.html


<!-- 参考信息 -->