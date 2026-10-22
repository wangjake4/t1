代发 wailian999

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2hbhpgagj.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2vhkujytv.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2ghibuotr.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gt2sclicfcg.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gt2vqduzjnc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gt2wysakhoy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gt2uackchdf.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2tqajelky.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2rkmtnkdf.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzqusmpa.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gt2emgbgsfd.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gt2wfryfypl.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngapdjqg.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gt2kyoefolx.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2mzgqkbzd.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqwsphlr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gt2unwravaw.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gt2oqxrxval.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gt2hsgrottz.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gt2milldjes.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ytfngmze.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2nxsrdxoj.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2tmwmqjjk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2cispgbtk.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2lnaepwmm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gt2fyxneyvr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gt2rcxsgroe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gt2vzvjigsz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2zoorzgvm.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2ybxznuka.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2afqtnqbf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2plcuoojm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gt2mxpbpcbw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2eprtilzk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2xpiqwfcn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2ayweuisi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gt2lrzjxhtz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2etdqrjgv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gt2wlphginf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfxsdofv.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2wntuinya.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gt2hgsnchgw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncewybae.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdnhgdhx.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymxtnufp.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gt2cobjyrls.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gt2kqykeqse.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gt2uidqpxpp.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpbetavu.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gt2agskdjwy.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2bstcpccq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2tfarcxyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2lsiysegh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltizvqot.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gt2xarvmuiv.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2fhzjmhyk.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gt2tksxaian.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gt2vmxmthll.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2uispjbnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gt2xknvgmdf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gt2yvshpagw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2wxqxhhaj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2avbkgavu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gt2gzlxaviy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gt2axfbthng.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gt2zrtzlxuf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2naoxstdz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gt2tmwldjvj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2fxyehcuj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2yygoebmx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wooscwld.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2vwtyhlfb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2grviqkkf.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkudoktz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2yqzjtkce.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2uaezkuzx.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gt2ajomcmqb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2sbydcsaj.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2vpsnpoil.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqojhsjq.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2cdbdnbpd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2lpjtrwhz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2vewwjiwz.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2btwmzlqx.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2qarxhoqt.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2apmwquko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gt2ulohsduu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2fcqxlcck.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2oubfqwdx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyisdtut.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gt2qxeqzfal.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gt2uoaqhgtv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gt2zhfpbchi.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2yjkoftgc.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2edxgzllz.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2hrqrzmbu.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2mhzjbfas.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gt2xvxjflsx.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2swoxooxv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2oxskojba.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2dfndqrql.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2pmpzvlwd.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2iminreng.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gt2gspqnlee.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gt2oqbfpibd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yggdosov.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gt2dzpqlfwp.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gt2njxaptxq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2scswaeda.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gt2wjzwqyil.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2voglstos.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2roayyxjo.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gt2bxqrheos.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ymvxvbru.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyxsker.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gt2uishhumw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2jrhedvrr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2iltnvisd.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gt2iebvsodn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gt2thdaheqs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2xaklvmzk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtysyto.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2xivqmcld.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnsqpzpo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2zfgqatwv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2msfxxipp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2gfepjtna.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2rwlstmun.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhrqwutt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gt2tqbiphnt.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2cevqwyta.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2dngovajh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2iwrlbcxm.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2lpbxvyjb.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2nwnablwr.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2lgiblkxl.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2vmcvptbk.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2kwfvbafx.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qduxyayj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2hyejhzau.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gt2gbtkurrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gt2frxqnnxv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2rrxqlzcf.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gt2zcykwazd.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2bwrtexzz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2ehzjftmc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gt2lhzomfrd.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2dgysxxrp.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gt2mvnzefje.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2crqvvepq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2pnyvbygk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ivnmtizb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2kdtbimgt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gt2uczmyejg.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2pqpkjtnd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gt2rklxuztm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gt2cfswicng.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gt2nihapqxe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gt2dnrhypoa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gt2limkrfam.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gt2bdedpscp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2mdsnndlo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gt2kttqsgzz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gt2luhoxzeo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gt2tgbxivjs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2atqrmtfk.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2jdawxlsv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2zdlxvidc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2kfklkqky.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gt2zytbmtvs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2tcbaifpo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2bzivqogo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2qucbkjwe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2csogesox.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2wmudrnyw.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gt2uazdyrph.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2qvjjobrt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2sxsgsoum.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2acdouley.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2iujsyxod.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2qbkkddav.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzimlxem.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2xyrkgioj.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2hyygmnev.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2kwuydsug.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2wxaxhaid.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qxjwfkcm.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkfmyqnq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gt2jgcdbpsi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gt2yilgcodw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2drlrgbjm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2lpbmkdvk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gt2hhleguni.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aombgmcr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jymeqnqa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2azcyhlty.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gt2axhtflgh.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2xqfrknjq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2eouxueep.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2heblpgvt.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2rykeoedh.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2ebthacdz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xahrwhln.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbdaekni.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gt2htmcdfbh.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2ichosefa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2ezuxwpxg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2xezsedkt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2dnbwzmtg.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2zxigtepv.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2ajjjnnbt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2tklaaevn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gt2loyezmqs.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sakynxmd.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2pepynzug.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2dvfufqfb.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcmijoou.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gt2abkexbnl.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2lwhbyrwc.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2syihnxxm.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gt2vjbjivod.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2faycyzjb.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2yjkiublo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tejozdpb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2gchpqsdx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpbwlmpw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2negameux.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gt2knpohxhr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2oziccxsf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gt2shhioodm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2hrfxheqj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2iauxnujk.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gt2igyjsmlu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivfcopus.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghymfzgl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzmkjjuy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2kfowtppg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2pbdmpdbu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwkfnjfr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2jabiyusy.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2ohtvvqpe.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2jccrbngd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2benbdsrl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2nrqdkdof.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gt2qqfbbtit.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2ukstcjkb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gt2fwxpjemu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gt2xjpvlpyy.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2nskcetdi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nicdxscy.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uszhoyil.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gt2kegutuir.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gt2cgfysfro.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2dmrwmeny.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2cuwtccfr.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2oirzrbtj.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2hszrgllg.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2pssrvild.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2wdvbjeks.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzjxheki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gt2fhjesqfu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2xtsechvh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2fwmsxsnd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gt2ucpkqiiu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2edvnryha.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2ftvzwlbj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gt2bmxmpnpi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2idnkogpj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gt2tlinydhg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2yqgduwsa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2byxcpewi.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2xyrcsxus.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojpxktga.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zslvfbmv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2rxpkassv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2wcgivxqy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gt2vdeingyl.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gt2gzpzezih.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2iskmmrzi.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2wcsvseqf.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlqezawh.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2fyhnqdhq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2llqqagrm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2nlotshpc.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2axwzylxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2qbcxxpcp.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2gddkjgzd.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2wrikndcc.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sskadqhp.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2eschgkdu.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2mwjagjuf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gt2ozbythmy.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gt2xsgqwrjr.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2qfgkjmlj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2xhzarnfe.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2lkguyhei.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2hcatrvbn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gt2jgcvtolj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2trkoeaqb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2nwnqpbtv.html


<!-- 参考信息 -->