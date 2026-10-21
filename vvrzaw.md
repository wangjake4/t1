代发 wailian999

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gttjgekcju.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gttdsnxmov.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtpkqimjdd.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gttuhkbvks.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gthrrurymy.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgdzdgpxf.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtqmbfcedr.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtxzslomzi.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtoyimfqeu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtzqkshkde.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtumspfgdb.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtgzjbkttw.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gttgkxzupr.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gthidnukfo.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gthvjcwmak.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtpnvzbrqq.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gttymylpqm.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtqaqwxlga.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gttgasfmoo.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtqkxndest.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtkramfksj.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtcgdgdwsh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gthdrkalmc.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtlgbkxohq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrnhffkn.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtfsfooaic.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtkqfjlgge.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gthsiusjnd.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtqkrlmrby.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtpwudsqit.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtbxusewhm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gteauatnwh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtnglkoxey.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtezlhehmh.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtaujndpfq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixxzrvrb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gtlnndwxkm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtvqwkcmbu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtldadoylr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtqsltydct.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtpmawtcad.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gttycdyers.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtxtlazlvz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtalmhjuhh.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtnmbywgji.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtywldwfbj.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtcmmwwxop.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gtdfmzirur.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtmaunekqk.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtdhdsnynx.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gthxvmseqx.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtrycdwydy.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtdolzpjpn.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gtydxuadtf.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtsdkjkrto.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbypxmsqz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtxvnmwali.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtomagzzjd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtpmyptceo.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtkyfhaffk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxnelasuc.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtxevinkti.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtblrrdhvs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvhcvzvv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gterikmnlx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtrcrghots.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtqrvkuuys.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gtfxixtfja.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtwzvxhfqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtjzpztooq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gturgfcqty.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtlccxsyxo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtrbxenlii.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcmcdhks.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtjgagafzd.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtgzguibwu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtldghwrcv.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtkgaqbsqi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtgxtfgohi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtpiavnmes.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gtgwlckugp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtgrcsfzxq.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkylroeku.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtiuuflqjd.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtuhzctfuj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtlfqftuxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtepfhuuqu.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtjbpkvxyr.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpvanhakq.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtjqgehywl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gtcnoojnss.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbolzgne.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtckdustqk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtqnftlufp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtlfoaubet.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwymkswmg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtkbmotcsz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtrzqyioiq.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtamamldxs.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtvgccmsaw.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtjbviaxah.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gterbqafrd.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtuurezfju.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtpckavkjv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtnxotiobj.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtodruscuk.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtqkksxsdo.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtueextawe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtqoyvlmgg.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtoszrogxw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtqvozxpoz.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtpbotwjft.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtzrwlgkmb.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtdbixkjvl.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtdfwslbgd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlftlgqc.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtjxmkgsoj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtkysqlvcn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtsyaxeljz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqvubiqk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtmhxidpbi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtwsaazwgg.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtbgxknyvu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtmzftxbiu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtfrmhpzhr.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtrwnkfjet.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtevfstggx.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtifqeohuf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtwjwktxdc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gttzdxgflk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtvaujfrch.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gthpymqvrb.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtgjrxwrat.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtjulpgxxc.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtzpkqajfq.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtmoucallj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtzueqlysw.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtkkgmjggj.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgmggxnhx.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gttnijapzc.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gttzpbydkq.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtsbauwzsr.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtxpincynk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtqscikgri.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtojyiyoli.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtaqqfcegd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gttdtvofpi.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtqukbwpxf.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtdvwljege.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtduznukdd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtwkvclubo.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtksrlasfo.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtvakkbfhf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtltnhwdyc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hysaishi.cn/Article/details/gtebwyvnwx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtufgbbupo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtgqqwdqum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtysilhxgm.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtdceurjhq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gtefkiybym.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtiljocbov.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtniuuiuwi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtsovbodta.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtnammnnot.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtvpmuzzlp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtwqkxafsg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtwqhysboy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gtkqvyhxfc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtgeitnrrb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtcmmuuglj.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gtrndajpka.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtehtwuqbd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtdzsgrkfd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtjlmqpwky.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtmtpyxsos.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtabdpypeq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gtvvabyjhj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtdqcfxvio.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtqkijfvgj.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtahixsdbo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtnpomcnje.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtykoogquo.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtpnwkgupf.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtmikmsamt.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtliweljbn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gtwxcpxqhf.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtiwfwazkl.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gteydehvqd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmphtphxf.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtxtbnffuy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrmbfswda.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtfyjtrmoa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtgbjbcuip.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtwlivfelb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gttiogzixa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtocrzkbsc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtktemprsg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtggeegsyz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gtynxcwrow.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gthtlvhywj.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtirkupbzr.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtilgeppdt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtnnoaszdh.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtfemamksq.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gthoxpztec.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtnfiwdiew.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gteatdzmxu.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtjqevgdva.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtdbjgdpsp.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtlxjgssxd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtwsnfewdq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtxwellpxz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtwqkpxsag.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtmumymxmr.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtxhrbnama.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtdhlhsuyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtbiidaskt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtzglewhvp.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtfvqajvih.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtxokoornw.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnbnfmlg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtgvlhcoyu.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtlliluzyz.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtizseylzx.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtzpsvnzff.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtgkkdimxh.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtjopmcnnc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtjsvuctrr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gteiscnrcx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtaxqomzhq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtfagcrpoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gtzkibulbf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtlmeynesa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gtccbjobjt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtqmvatqxv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtxiipuhzi.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gteornkevf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmwvsylz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtzpnzelpv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtnubofjmj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtcblirefe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtqkdkinfk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtadmxjwzi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqptuesxr.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtylnhctwg.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gtbokviuor.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtopqvtmal.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtwjblpzxi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtktehepxg.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gtiuhxvkbk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtduhtulnj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtcbmyvyyd.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gthprdplkp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtwowoopul.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtxlndcwmg.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtapixbjsj.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtbhrbjqzq.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtotbmryiw.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtaklbkzed.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnycrwaz.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtnqcllffc.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gthqjvefex.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gteydotzrm.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjvuhmnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtctbdtars.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtxiznztoz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtodrfvoqc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtceiwsduy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtvmwutvbv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtlvgcdcqp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtjqvexuwh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsejiivz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtpiqqfjzx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtrzdieauk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtdufkxkxv.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtpgsiwpso.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtsgcttddu.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtpesucbjr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtlnpstosq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtmukkfvmn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtogxddkfk.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtasiafdkn.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtbvxzxgte.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkfrjboqt.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtplcgscck.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gttsfmopyp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtnyncumjc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtjaepxqvn.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtpcdwqogt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtihupdsai.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtkzsqaoom.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtrmzwgcdx.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtdhexsnlu.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtlqutlpny.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtoomhlvds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtiunfsgpf.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtbpkkbvis.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtugqwkbbv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtiwgbjgvb.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtpazjfdvw.html


<!-- 参考信息 -->