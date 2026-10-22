代发 wailian999

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtxoqekgtj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtejqgkdsn.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtxqajqzfu.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtndwcpmpy.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtfbuvikdj.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtsdqewiit.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gthdwmclhf.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtttaaemsg.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtzemegotz.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtlxppiuch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtvuydvwcs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoztxarbs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtldythgov.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtwfurxhgr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtqooyjvrm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtntnfcgfa.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtfyjrtqyb.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtiperqomp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtqgucekpr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gterrjixnd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthegeevqd.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtcjhprnpn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtumytjwai.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtjynemwhi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtlikllgks.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtuhxbmmpc.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtmbwqeijx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtwxrwzrcw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtmbestonz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtelkpnlgg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrjskyte.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtelbqxwgv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gthkxhhygu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtnkudhmcl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtrfbypmyc.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtobeybwye.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtqcssihct.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtlzdajzoe.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gteyhsayib.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gttdvribno.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtlknryhye.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtdkrgaxlf.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtcxybulxd.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtfnuenrgn.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtmdmzxuqz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtgtpzlido.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtmbttovpq.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtcrbnbeky.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gttmmssbwv.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtveajvajp.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbxtqtiz.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtitiqlifg.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtuwigpxub.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtlwpxxssr.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtnhuruxlz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnohltjef.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtihypnatb.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtiogxqbwq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtnfclcaka.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtuzvsmmsw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtyijndilq.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtlnqansyq.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gttltzywht.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtomxbtluu.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtbehlfzox.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtronhjzgw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtgykbxzse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtjwvhzswu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtqjaxxsvu.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtkraxumfk.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtlplwpepz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtiiwqmurd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gtoxgzllzh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtuxaxofup.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtwrbrovti.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtqnpsqnmo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gtwknjzbhk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gthxfluwet.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyhyirca.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtyituljnu.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gtljujwelq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gttvfcbpnb.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtugruosed.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtbvjszgac.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtssxozmss.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtkjnrazib.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtwqdeqovx.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtzzthcpug.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtqykvfoqc.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtiebdmdpt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtqiifkdag.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtphyqpmkd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmpwumur.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtboaealor.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqoqyeka.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtujcherza.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtbusjzglw.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaglbnter.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtxinesfgl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtlhnhbwjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gttqwmzeug.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtlapgmkqi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprtbikal.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtfdhlxgil.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtldxiomrf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtrznpvjsu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtzqrjhyhz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtgphsodhk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlqlkzkq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtmfzeyjxd.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtgjccgwqc.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtsaliikac.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtxcfqupbk.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtbtrqgznt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtffqsgvzn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gtxarvbohv.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtkjtbyrum.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtikdjrome.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtaunmzmyv.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtdklpersb.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtfxhfbcde.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtgudhzdzj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtuloemwmp.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtpwryaopk.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtomzrdjcd.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtmsdtkcih.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gttbxgvoyp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuhamehe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gthtehytid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtoltdwcmt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtiucrnkco.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtfprhulur.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtugsjavqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtumnjmfrg.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtccssconz.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtnkktqtht.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtspojpoer.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtgtpuzwko.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtfwipohyj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtnjnmvmwk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtntuckkvy.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtpgqouzth.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtbmlpepnx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtrajgcywl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtmwbpkxjw.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtdhpkbkkd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtrdeelfyu.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtrahqsurf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtqrupmteo.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtxgzczeyk.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtuxdavetm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtkddwwzhz.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtinlupmcv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueafgjpq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuvmxcst.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtwhlwzhxp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtxrdxdjru.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtwyjumext.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gthqlwzxdw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtmhjqlrnw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gtegokpakj.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gteuaolsqi.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtmbctvosc.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtepdyhfyy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtnqkreqfv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtfputixqs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtdcibxtti.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtjfkxatpu.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtgpessrma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtjxgaoayk.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtskwfgnsh.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtcscqpevz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtznqyqgfj.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtlmbxffzj.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtodaypiyv.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtdqopkxam.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtamqhruxu.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtaiztteok.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtdwunthxl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtrfxcdbet.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gthxgbhjui.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtdjdiptyy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtbzjkiopc.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtyrrhghjb.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtsinnpced.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtglxnxyxj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtwmcragkq.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gthcjadakr.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtpnixgbku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gthtiablyd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtprfaytxq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtkfwoxvkf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtxkqmlugp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhhkkhrw.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtmascpjxo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gttpgszwnf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gttwznowxh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtvduhnhcx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtrzrzyerq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtlkbawzhd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtlryfbefq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtdyksifrt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtdhbjcajq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtccvjezav.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtnhanqptm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtwietzcbw.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtdspdxrtf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtcoipmzka.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtatqfnmwf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtldmkslzn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtisfvsrzg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtduucqygb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtmtyxpyzy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtbflpeuhl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtzmcmopmo.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtqyspdroz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtrpcgdked.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtuefsegty.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtaefevdcj.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtvpjsjquf.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtoubuwoup.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtxtwattns.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtyhzhpaly.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtpkykhqyy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtixsszfhm.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtkyghgjxh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtstwptosf.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtldpbowqq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtswtqwupc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtrisncebg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtotfmmqor.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalioqfav.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gtgdplokpv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtjqfynpoa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnyxhbgk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtpzzkzbip.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtnswikyed.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtaruuxlrx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtxbaaganl.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtboxkskjd.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtgavkiyut.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtvtrfbcsu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtweopoipz.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtdntbvbyr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtjnydvqds.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtxrkyktlr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gthiuborci.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtfegnhevg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtuazmpitq.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtvpidyxbf.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gthfrvuosh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtsqbjuufb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtelbyqvxz.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtokavmyfe.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtocgnunbj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtyccqyzpq.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtmdnwjjrv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtwjxlmxvq.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtfazhknxc.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtsioqwulk.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtlrhctbuz.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtjrnkwdjw.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtessmouzi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtowtibesu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtqdzatazy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsamzzjbc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtfbynficp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gteqsgvsza.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtgphwjzwy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gtvenkvcff.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtazkrpcsg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtepyzhwfn.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gtcmqsvhuj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtyqwfbvee.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gttlmsawyg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpydmficz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtypcoctlm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtkixuvpia.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtmtymitag.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtuhvfyqkk.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtuugxkugi.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtxnitxrlw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gtdxjuqikg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtwwoqsgmj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtfblpqvjl.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtevdxrkhn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtdrrigqcc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtvzjlvezv.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtzufeasjj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gttxthdjod.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtkgytxqob.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtddkrccem.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gthvevarfo.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtmavtskdx.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtdomvqeyi.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtxzvzuqej.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtxqpucuuz.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtkvnbixky.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtxotglrcr.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtvigladqf.html


<!-- 参考信息 -->