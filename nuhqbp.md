代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtljbjdatz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvgkdcdqy.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gttbkpxkmk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtfwjzbuuo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtikibhaoi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtzceihuvg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtqbnbifoj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtgkbimswg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjzgbmjw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtdlgwadve.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtciwoeedg.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtdqxptgix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtdcprmsoe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtizpsndji.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtffnerrkv.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtdwvfneib.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtnkxcspqs.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtyoqgfdtg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdhspcbg.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtyjnuppqa.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxgiqedb.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtxqzacvmo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtvqofbmdy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtguviuaxo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtzzqdetvx.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtoavempkx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtwadftjsi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtccaylrpx.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtyuwhcfnn.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gtpakuurjk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtokcttgqu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmtfzxdsa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtrdbfcbjc.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtoyypwaqp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtzezdsogc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtgacfszvi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtfltxijer.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtyrodfpoc.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gtleryozfs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvgokofb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtezpocnxt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtioptwcqs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuuqvelj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtnsngkdpm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtolyswdtw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtzdsrepun.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtsfwjzvzf.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkakfbgp.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtmeqbmqhv.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtcvsghtrg.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtsgpxwzld.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtdgxxrarv.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtejvaxuwm.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtrhkwccqb.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtdfhhrvaz.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfafulxar.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtifabmiiu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtbucmeokq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gtuvheacli.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtypcphswr.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtasedomia.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gteizrilgj.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gtlsytrxbn.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhwrfncz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gthxxjrxai.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtrbyeuxff.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtdsuykwiu.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gtidgqsoqm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtzmbsjkno.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtpqqpdobl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gthtqtzqoc.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gttfmlbjzj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtamjuxyrq.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtietlppuk.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtjxjjxlrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtogedmtyz.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtlykszglr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtilbbuqzc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgxfafnd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtdjejquqy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtmihybioi.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtlzbjvhgb.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtnaryqbeq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdqeixcz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtwdekwuac.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaqvbjst.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtspcxhqww.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtccmysmre.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtpclmzzjc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtdfkkxlqm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtlladerri.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtohltnqzh.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtprsifvqq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtolkogjdc.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtutrbkato.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtndelzool.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtsvhdfmly.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtsngbeutp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbllxmyzc.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtpeuxijta.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtjuwqchfk.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtpplbsqje.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtxnhxwehi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtjyftloay.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtghzukekl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtawhvlqby.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtqpizhbcu.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gttueqjgnn.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtmoflpyhk.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjwefxoi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjcpvqer.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gttqjigdej.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtvpugivgd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtodsffgwf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtypklweec.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtjpwzkmwt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gtmdjsymik.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtcqewqfut.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtzwblsyrx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtvdvppbgy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtsdbmowjt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskgbbnou.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtaqwzrsjh.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtwoamdzba.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtleprtnrd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtkhbbqjoy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtuivflwnl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtevtbjsin.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtoijrgfyh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtibkwxger.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtditaxuko.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtxtbsregn.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtznyavqhf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtvngwlzbv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtwiqurisd.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gthirbejjk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtwrzejwka.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtpgpswuhk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtwpxxucqq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjnuglhoo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtfmmuuloy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtxdhmbyoh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gttwkgnixt.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gteifbvfuf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtauknshmf.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtdiqrogfv.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtnrayxnmk.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtoxaukcvp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteedjuiyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtbmpqkqdt.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtfqxwezmf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtymsjljqh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gtvqglbykm.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtnmvpwoks.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtcckmcwoz.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtfnmewcfv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkgxgvij.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtsxnyietz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtafmhrfdx.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtzqsqxtml.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtgdckoyyi.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtvpcwqorw.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtynchsjai.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtrpcgetaj.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtzyqayhjw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gttunyhouv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtkssjmxbe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtrturesrk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtdnjhlqwn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtvzvllcnz.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtjjfuvbid.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtojmlvizp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gtsquqkagx.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gtihqyidsa.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gtnwafycjh.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtlzqpcrfu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gthxsmdsjs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtgohhafng.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtfdspvejb.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gteziutqyq.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtnmplkbrm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaujlcvw.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gtecxxoriu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtuwqacgau.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gthantupfv.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtjbmstshg.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtqvfdxxkr.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtkgwjegto.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtihqjxkvy.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gthnmdbngw.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfnhdlchj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtjqjoalec.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtyusspcdd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtckgoljxn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqovoutmm.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtpxsjkseh.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtzayxbksj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtglafjxeo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gtlpjghloh.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtqoxecsph.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtwbjfxjod.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gttwcvqdbo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtdzavlkvf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxjeunks.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtfyryxfde.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtvynofjhn.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtwuqcbbxr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbfegjla.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtvagshpge.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtzepncozt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtmanjtmcd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtruuawqyd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gtenxidqus.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtlbqxblqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtkbwywpan.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gttpcmfntw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gthhrjerfk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtewbfoaan.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gthjedlabj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtekoskhfm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gthfsozxks.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gtexbnnunw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtaublhwqx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtjhyjqnnl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtqaghhmbp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtpjnikqby.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtcovpntvn.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtgebmvdrw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqmkxxgu.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gtlfzwmqqp.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtxnvihzpm.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtfpkzdlij.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtlqhyfedy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtoafsbhke.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtjyjglpyg.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtrqzumpwi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmypebeve.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtquksgzba.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzsyqdhmi.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtivxlgpec.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gtprrhxbja.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtzcowqwya.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtfzdpatdi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtxqwtaqhq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtcvajydlf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtyudmxwwh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtjnzvkbju.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtjgglwvrn.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtinddopps.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtrvlvkutr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtzimzgvvk.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtsakdczos.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtwycodjtq.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtdcrfhqsc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daria6918.cn/Article/details/gtwhbvcorh.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gthphnxjqf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtorgkidqc.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtglcvwcci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtpsxuoeqa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtlkpjibro.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtcdwvnfcj.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtzhhcuksr.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtvplijbiv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtufkolfim.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtazseefkp.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtceejmvmj.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtuxfwwxwl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtldvdvtff.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklfonqbc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtxfwxiioq.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtpmslneno.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtjxvywark.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtkwpoytpx.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtdnefruei.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtggeiphwq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gtuvkgqkjm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtianioeip.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtuafimcov.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtwqjstydh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtmcycezok.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtdifxcwyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtpxmwhrkr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtipilaovp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtosbsniwh.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtfzqlpjbo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gthemwsbnu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtipiigots.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqzckrzp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtmmlxyckk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtkzrckoet.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmhlheom.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtbdmjkibc.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtalsurbby.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtazxywaqm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtgwhrnqse.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtrrrsyekh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtpmqfcopw.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gtlakxfiul.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtdwqekobv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gtuywtpoba.html


<!-- 参考信息 -->