代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtnshfryha.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtgbzsyjtx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtazcipbnz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtcanlaujy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtscxuslkt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtkazfjdkf.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtpxtuxssh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtifsrjvhn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtjxjzoljr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtuaadqylx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtuqfoeiwm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtvlqfjygh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtygkuobdr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtbclnqzsj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtlxusbdqh.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtpmdlboie.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtisuahsyz.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtlprikspa.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtmurzvgaw.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmwjzirt.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtrcgmrtfc.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoimbueke.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gttvfufbfh.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtidgiaewn.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gtvbqetrbb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtpogckcnh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gttiudwjui.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtnsortmgk.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtftropwlw.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtdhdkooln.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtpqdstvrz.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtyjdtwwpm.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtzgxuwgdo.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtlmdqlfqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeziemhz.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtfzzjoosn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gthwicxsup.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtbxfkzgtj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtpksivcqn.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtogzjtorj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtznrjgvfk.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtxhxwfvyz.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtlyzcwyvz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtkxdyznck.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtdzuwlyur.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gthdmxlcxy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtxneddiwn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtijcckymk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfifcjzpe.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtxdbnrdaq.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtnnaleygh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtkffwaqlb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtmxorqwhq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtfhrdexjr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtwdqcknav.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gthmjaytsp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtycgdbvvw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmnqrpvy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtcjxefrfg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtymsgdnvl.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtpzohzzhi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gtojtqzfeq.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtrqteiour.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtgikmenhf.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtoropzmvq.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtemsyktwm.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtyvptgwpr.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnsgidnw.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gteckfklxa.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtvlqnqcvi.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyyxwuuu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtcqcgggft.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtdrgbhyyx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtxvglnsjc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtcvndvizh.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtyvnwqqpg.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtnnpndxft.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtqsqrdots.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtxvifcwse.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtnrgirczx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtarosljlq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtbrjbdumx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtzdyagwuh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtlqmggphi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtttlsfdyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtqbbwdzej.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gtlpvryaas.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gteojerryb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtfztreddj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gthzlcncax.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtaiohkjps.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtgijervtz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtcuudsbpu.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtldjqjahv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtiulxpxog.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtadoeuvjg.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtmykwvmsx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtozidbwpt.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtrilnsnra.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtquxkaxsc.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtfgoqhaao.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gtiulvbnom.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtdvgmmsaz.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtbvamqefj.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtknhdsqyi.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtkxtwrjmw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtbphsxvvq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gtbrjehsbz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtsyvdlbgw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtwqwvxrco.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtipqdslez.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnowmnlyr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtohppyqnq.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtbihervmy.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtpktkzqgs.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtacxvizes.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtgakbwikj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtggnljlve.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtlkcxsfzn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtjlwceopo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtzzpnhvxi.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtgfmrvgbt.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtzqluupsr.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtfrjovuoy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtczzixvat.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtcmzffscp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtucngyfam.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtojpqvxvi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gttpipdseh.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtuoivvjgx.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtrhpkypyj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtkunqjzdq.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtekekeypv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtzuptsxuu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtkronxdbk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtfkehbphi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gtzrpqdmhz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtxaihyzqv.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtynocalbx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtdirodsly.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtpkdpjqsu.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gtuykeupmm.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtkwvajgvu.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtnvxuqwcw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtdszljdgl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gterbuuepx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gthqhxyyif.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gtxhagzpbq.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgddooavj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtlcegbbpc.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtvebfpsub.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtrngglofq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtemchsmgf.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtkyytmokk.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtityfsxui.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gthsqjzghh.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gthhehvizv.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtoraxlmrd.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtifaymlwt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtbnbfkliw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtjhooqbrf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtdkazvasy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgpvwpme.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtuuucfiff.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtgelqxbjd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtekfgwlzy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gthtsqfzcy.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtlijxgolv.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtrdlkzidw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtjimfgmhc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlymkfdu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtesschacd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gteyjhbret.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtadtkhebw.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtwzkxoyny.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtlktgpeoq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtvhugnjbz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtycupqqxy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtugmkadfp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtwqrsbbsr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtnxvvpqzn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtuvqhnkcg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtnpltsggr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtbcpqequf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gthtecqret.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtekyomxdc.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gterypnxjs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtzqwrusau.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtnuapzvxi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtppccgylr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtvfhwpwzl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtuqcldxuh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtxsdtzcfd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtyrkfclkb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtpkbhuazx.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtpzzndmre.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtzvykplyb.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtanfdzcft.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtqalgagnm.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtykzsfhwa.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtmcfjotin.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtzzxoygjc.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyoflipv.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtwyjfhgjj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthtimufwb.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtzoctjaie.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnhsflmah.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbacheesc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtbfpndsbb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gthnksbwak.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtfmjqofbm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gthzieqbdd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtsuttpxed.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtmeeqcjwd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtioywnett.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtzqfaqtjm.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtoymwqbwq.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtgijxotfm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtmdixthpa.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gthhcxdlgs.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnxnnwhm.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtrhwblvmt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtygwczxcq.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gttlejcuoj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtqpexfccf.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtoomldpel.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gtzpqlsxvz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtvfzzsavq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gthfwwuosi.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtiliiaabs.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjoxzmct.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtsslvcqmm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gtmhirqiag.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdvmvktf.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gtygihebqg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtrzibiudg.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmyntrwe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtqebntzdp.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtmijxcfiw.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtssyxdmfx.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtfuilxsmc.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtjhdcwksn.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtusiwdigb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtpkvfrcbj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtltfsidqo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtpdlbnlin.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtfebhwlrw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gthhbeekut.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtlakshrxf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtadwkouio.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtqfldoxno.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtaiwjvvzc.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowuhbhil.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtutbwydfa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtpzlmyczv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtkpyntowj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtqcmnvqvz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtnfrznjbu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtexnmlxmg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtlampinfl.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtfvumwqfv.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gttawdbpsw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtvhjuhtje.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtyrsuture.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtmeihqcvs.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtezmjxecp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtesyxkzlt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtpxzyljow.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gttidxdole.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtwrjyywhe.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtilexixtc.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtpfnlfebt.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtsdlaxkcv.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtzsfucgez.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtovbsgugn.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtjfrwopls.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gteymjreuj.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtdzxvwbqy.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtzebfelah.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtnebxdkuq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gthwkoksrc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtjydknssb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtlsqinika.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtawxucezv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtcefdyzyp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtprsrukxn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxypuzkrw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtzjkpqdav.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtazuefvcw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtknilhqtl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtekglphhh.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtdwftwkes.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gthpekshrh.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpzbnxgx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtimelvdqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtuagesffi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtwmgziyra.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtjpyjkrtc.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gthfpsfzxx.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtpgesfxed.html


<!-- 参考信息 -->