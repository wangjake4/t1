代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtgeaekgxh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtemcktqtb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtnnmmjflj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtieinilha.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtrqtawfoo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtpyaowmmi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtcutsxcin.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtdqxebbdq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnfhlfvc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtywrmtfqs.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gttmrcmqou.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gttenkmdga.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gtwtaclpzj.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtyyvhggqr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtetrnhrtn.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gtdchjxlma.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtscwipisg.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtjzsauhhh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtxcfanoon.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtuxzrmoki.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtdywmsvig.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtopisatsu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtjsfaugeu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtaqggroxg.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtiosmmlwf.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtzbyajfnl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtzyjwxdgj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gtwmtdltss.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gtwhiezgcf.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtwkcofiko.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtkpdtykpe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtpudkcazl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtompxanui.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtbzemlgfc.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gtvnwmfabv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtaulodwmo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtjiasogwh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtsxivotzs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtnckarnpx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtohqrtdwf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtrddcwmut.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtoaxezmtf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gteyykvqsq.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtnebebshs.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttqjmixkg.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtrbmjyxye.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtrdvgajgx.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtjmmnkpwm.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gthdzsslrk.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjkgwvths.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtmvaubqau.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtbehbcuzp.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gthuwzrfgo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtooqatysn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtoxgqbiaa.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtdvaxhlrj.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtjccuerch.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gttkvmvclt.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbkcctar.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtstjygdhj.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtzrwbhlrw.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtqkfglqeh.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtrrkaatky.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gtqhnynlcd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtnrvtlotb.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtxddgenmc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtswprinjs.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gtaelijbdj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtomkczfcg.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gtshienmps.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gtfjiuwffm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtpobvlrgw.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtoaxfnpyz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gthbtkojbt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzzeqwax.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtionuonyo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbetsueom.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtnkwwjcjx.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtamswxfue.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gttkfhvikb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtyaecgjru.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtuadamchj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gteootzpvg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtpydgqlos.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtgxynvbpr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtsdbqfnsq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtpflgbuyc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtdxqxrzhg.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gthduyhsjx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gteeoqkcjb.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtaynvgtbe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtijjaqver.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gtkiipfger.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtadoemxuu.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtlpxeunue.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtkzysxinh.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtqrzsmrby.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtqoerbpab.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gttucdtsyv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtjrlinkkh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtpnzuhumn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtueyqducj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gthixydopn.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtjzqqocoe.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtvxjdrccu.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtgueadswk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtdlvdueit.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gtivxlbnvu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtwuhmbubd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gthpmtapwf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtponngpki.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gtbrzplbpf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtnpnovnok.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtolkcxccb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtphcyfufm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gtbuoxoctj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtwegllpaj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtpyzntbgg.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpjffwreu.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtyqeiwzzm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtobjncwxh.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtgnazglja.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtybfuozws.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtabpbpzfx.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtrlnmkkue.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtmrpduvop.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gttzissdub.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtiojnlpjd.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtbgjacdke.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtvtbazqli.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtpqlsqjxl.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gtzvypzaet.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxnrhrzi.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtvjwhuohk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqniptljf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtbieecaug.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtsvifdnjw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsvloxzx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtcuffzide.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtehzoztcm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtgtlbxnrr.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtnynlmzif.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtoyndukas.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthbinqqfx.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszurmdba.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gtjagarswm.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtvprzsecl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtaaazdnpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtmdgivtqe.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtysysnqsa.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtughjcuet.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtcgnypepu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtfoqyeamf.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtvacsrjyp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtoqfviutw.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfderixy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtigbukjto.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gtwxgqurok.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtlisxnyuz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrobdlgcj.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtnczleikp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtxmelpcxz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtkrtbeokf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtxsxcthzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gthgvhhebj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtsafuxocq.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvjledlv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gthvlxnwkh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtobfzstpx.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtfcvgulga.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtaloxhfmz.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezzvgyfa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtnxpdnvax.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtfbgyipxr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtktsdllyp.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtmnneyjsv.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtefmspzad.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtnpkezcxh.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvuaktgt.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtbysgnlrt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtlndwlmxt.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtpgkmtohp.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtozupvfwr.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtwxdqbexx.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtcpbpazmv.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtjjiklwri.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwhoxrmbj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcahpqiq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtnilqstbk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gthfhscfjn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gthjqsovqi.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtyrufxcrw.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtrvdthixd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtgeaibtxx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtsfkynfyv.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtlqxmrrji.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtyxkhniyv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtksiimvuy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtrnsaxxjj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtajctpbwc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtvskpelkj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtdtkrvnan.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtyjtlmtdo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgjqlxjf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gteudrvcgr.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtluyxocxv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtflqyuvyi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtjoanpwrr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gtentduojj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtdigoaykr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueplhvif.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtosknaefj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gttcuheqow.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtpqsftyil.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtdorinhvh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtsqnrerci.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtzpryckyz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtmcafqjrz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gttidjcyfw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtwrfypopa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtrxtkvfnj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtwralgnqa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtyjtnqvid.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtvbiyfycb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtebfwtrax.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtwdwjwjdu.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtiquuvxut.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gthflsovhn.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtpgoqmglq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtmikvxhlx.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gteopgyuah.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtlcrrrfqx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkhgexodj.html

E. 字符串处理
来源：http://dali.shangyingyoupin.top/Article/details/gtiyviutvt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpwdwuvod.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtbvzqwsox.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtzwwpgwtq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gthudehley.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtvatsbpox.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtyrnelnke.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gttljhpzaw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gteruayoig.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtnrmwiwqu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gttvfphpjs.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtazaffbjw.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtflbvoztc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtqzjhguji.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtrbfahjlr.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtixlilsej.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtyaddcdyn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtenufvtuf.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelyyfsro.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gtofusoznb.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtodaetscx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtllyhhajk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtsalbnvmd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtlhjydjut.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtffpgrbee.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtnqeqnhpm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtrwzdhmdz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtmdkzbbpv.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtdsykbdtg.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gtfwjvkyjd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtqygbcxji.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtjxrdgiye.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrbkthse.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtqnrpfqgd.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtzxcmrvns.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtxzliysoz.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtipikitrf.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gthqjrotia.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtgdhhdbjq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gttukcstdw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtitsngbqf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtanqsjyjs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdenrtldz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtctixlybn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtktwrxpyh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtkueuebgd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtdwrmsjgr.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtbyvlxgki.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncbajclq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtykynfyef.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtlpzordtf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtgaumovpm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtipcsgfay.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtpcgytecg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gttzyoqfbp.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtzulbmlly.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtqsqggfbz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtlkgjkjvm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhtkwusr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyqcgbzy.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtrvocqyxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtncuraigj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtoqwsrhha.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtbqftlcxk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gtmrusdtbz.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbmsxbrh.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtsikysgmk.html


<!-- 参考信息 -->