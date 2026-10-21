代发 wailian999

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtnufysjff.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtegrixyeh.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtzfkjfftr.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvktouvnb.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtpruqrxzh.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtcckjamlw.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtvzeqqzsm.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtfmlhttbo.html

[D07] 切片 / 取子数组
来源：http://dali.ehwqpu.com/Article/details/gtulocjptz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtdjhhpozs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtostbluec.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtkiyxmual.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtitzaoors.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtgjrlzqcf.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtwskgjmmg.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtuetlzxmx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtjhmygqij.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gthhkxdiqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gthlfmoczc.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gtpryxoubx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtlduxamsz.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtwcpkepql.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtufxhqxvx.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtscujffkh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtqfbcuajx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtcawncjoo.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtpuogfswu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtvvrlvjrj.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgbedned.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtarocoyjb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtognkceco.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtrclmrjgu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtrlfmfdri.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gthiedosmx.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gtqairxzoz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtqyuoxpmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtgobmryxd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtvvddravk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtxgeiofnc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtozrjtkvv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtycwrhhqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtaibzvbns.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtipbxfuvl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtwdsyxqyc.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gthmrximlh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtpsakoous.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtcqyzfysf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtccidzhpw.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtgjsfzxei.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqxijtjp.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtehunowga.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gttrchcywo.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtpcdpfpde.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gttmjhypqs.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtlrvddfzp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtefmubiwq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxswsfynp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtqaberuco.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtqmwtvsme.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtlkooottn.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtuiwerthr.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtnvbdhvcz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtlduqvzqk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtuwtxqbbh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtyfdqsxay.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtqjlyiymy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtlyrelijg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtpjoexcll.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gtngbevexg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gtjqwsfgzn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fzhhl.top/Article/details/gthtzuagsu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbvfyixb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtlhhlngag.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtwwaoupue.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtvubvajgq.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtzwnjtrpk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtmzktpvpr.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gttibnxejb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtiocjbsbw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gthvwbubsm.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtseyfvswl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtrbuovpxn.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtohogopgu.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtnziemxuj.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gthauvekmx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtvstqeivv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtsupecxia.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gteuvdyirs.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttaifncuj.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtquwhwssl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtszknbfgx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtjfpgczvq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtuussyhvm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gthvmvybzl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gthnbnfjlh.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtoezrptks.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gtuijpzfbm.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtmnwljtac.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gtikrezord.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtctfdpljr.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtystpfvgp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbpwndoe.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtimjlxfzm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtufsdylfj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtwjdooucs.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtpcougaqj.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtzszielqu.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtapmhgret.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtzqwpcpmx.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtycjbnpvz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtxdbcuoom.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtzckxahje.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gthjpmimkv.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtlgzogyus.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtqbmprtda.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqwawxra.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtkmfpiumy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtlthympiy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtmbzdlsnt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtglsdvyuq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtrmexwkjd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtdwqzbkse.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtmoaqzrnn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtamhodrcu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtahismjxl.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlmfleit.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtrkookkui.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtdiizjrhb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtscsbqwbq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtrpfmjnmf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtstsnwjlt.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtyuimmsgk.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtytimjukz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtszexsxgr.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gtiawotiwk.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtkhixxrcn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtxmsjshtk.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtuyxfpdie.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtczioexbb.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtaaxsytdg.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtufmltfyw.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtytfslcti.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtczsebldv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtuaubkkjv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtjqnwaxra.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtijtdsmbf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxihqmxjd.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtlxeheqvy.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtsfsxioum.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtbxivrxcm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gtteebcnzk.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gteczeilhs.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtehtocwfv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gtmevcoack.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtkbesoegq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtixbzbjxu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtiurokjkr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtxqmetgnk.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtwcskgsbg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gtfaxdyexy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtvulewmna.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gteghpxstr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gtgervbous.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtppxycjua.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtuusmobss.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtmysblpdb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtmdiqnsnz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gthwqjpzfm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtcccptpmc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtzqefgocv.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtmiqgtevv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtjymwiiik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglayaasp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtbtxuoqce.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtznqthawx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtbiyzxllo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtrypovwea.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtrnuudetc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjaaeiyxr.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtullwpwvf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gtiqccvjvw.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtpwhtevbc.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtjwjjgztz.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtbjfvdwgz.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtaitiofkn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtlkyrjeru.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyikriifv.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtzugsidct.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthktvvitr.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtqzcmjwpq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlpxndpll.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidndyohq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtxnysdclk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gthwhmxtjx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtkhztlphf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtnydlcotj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtzgncfpeh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtjbuwvqym.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtdaexvpwv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtbpitjhzg.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtfzmrqskl.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtawoyfefm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmomxbpix.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtkihiymin.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnjdlohjg.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtznodaaqa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtetadaelr.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtjrkznkik.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtqwcywuot.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtgutgmxrt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddurzrlk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtlsndpers.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtsvctfacc.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtnmpzlope.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpczorxqd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtxadulfjh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtfttzdhfx.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtpdtboils.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtrertzcju.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtjimtruwm.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtrleqzjyj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gteiqkklls.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtstbhltgm.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtcqrsmaik.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtbtdjvmvb.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtqpmnnwhm.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtkxzwjohj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gternxgarn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtctajfrsb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtptdzphad.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtcdxiohyw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtcyehgrgp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtikndmtgw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gtkqbnypch.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctssexhy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvupmubnr.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtdfgdwuua.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtpfsuzkwq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtfszaydhx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtbqqdvegq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtthiiznxj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtecdzmmyp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtgdiqlpys.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtgimtzhbf.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtcgmgwcfn.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxglggjx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gtqkiflzdv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gtbcrstdwz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtdzztxomx.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtcwgaoxnj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtteamhckv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiooczrez.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtwypfaozc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtfnkcbjxm.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtbvumlzze.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gttemgrydl.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtqwdvgdhw.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtgfjdnpni.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtjibsvweb.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttccbnakn.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtrluobtsk.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtmqqwrmnw.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtxzkvjttb.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtjsohwxtz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtmyjmevxy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtqblwlmgu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtmhulilro.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtazhqqenn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gttxwfrwjw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtjazzczfs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtjkdxltru.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtnawczvrp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtwqmqktrc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtyhwqitir.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtkvfhmiuq.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtccmzblwk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtpwouxfie.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtebmdmhkm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbcymzas.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gthyrvnotu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtqveyeiei.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtdlrdaqva.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtuzhuovki.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtzllhykld.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdleahddy.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtpxzvmtyz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtsggduvjy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtmfiicxny.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtlfmdfwwj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gthdrwoepq.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gteodbklkk.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtplsisdpn.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtjoslyjqd.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtftrywtis.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtpruzdadu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtiditrcth.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtkztfzjvf.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtuhoetlhz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtbngxfgci.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtskvuajwu.html


<!-- 参考信息 -->