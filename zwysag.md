代发 wailian999

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtnphsvtsh.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtycozmnnu.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gteipuxfit.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtqazwasrg.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtuoabsyxq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtpzuyepsq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtonwqrkxm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtuhjyrlok.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtatcihkve.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtvsbntmtd.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtpdxvsllb.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtobqptgos.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbfgvwe.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtlkgkhphu.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtkdjtgjoq.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtjsehwdwl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtjuzdolmx.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtlkksvnyz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtxmzwgfew.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtuewhinsg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtmbapcpgp.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtfddaeoyj.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtxxgnwhqk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtgojsjhbx.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gtwgcmmugk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtxsywsdat.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtqyfwphuj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtdugxvpcd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gthlnauevb.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtagqkyhty.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtjpgvblum.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtnjyjkisn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtqqowdovw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtzwjmkoxw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gttlgbnfxn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozmkkngr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtzunzgxou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtgaqfagrs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtzrfodhib.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtwshhkgqv.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtfudfnvgg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbulmdfrt.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtndsjulms.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gttyocanxk.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdscpuie.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gtfmxibsiy.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gtfxstrepc.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtmeiqqdfw.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtwvhonyjx.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtqozrbwdk.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtxavnxukz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtjebafxxv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtzlppphpn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtmrotbjwl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtrhkqaijq.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtdqodfrfz.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtsxjrkvux.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtpedkruow.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtnjbvnfpw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtlsuvoese.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtfmqdzmxp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gturjfpttq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtdpxgqqqt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtocpsaddh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtvhzuvyck.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtdkqoziub.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtxcbpgzep.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtytwtntun.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtbckjznfe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqnlrgmg.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtrxapkwgo.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtytyrjbyc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtdmuewqth.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtibzxqcda.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtpvovqvwq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtplksfzlf.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtxppvxcrx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtuqohlqkt.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtgebefmpo.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtwwhasctm.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtllnqqplc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtbreeumod.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtyfiizzww.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtnuffjrru.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gthqfgfxmo.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtvhycfmpq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gttradoqfn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtvxozbwxe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtxocrfzbv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticwxplqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtzbapexuv.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtokvpnsmp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtcmpkebjk.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtffncaeux.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtyorkihty.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtyrxhqzhe.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtqdqcirmu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtgkoqfvak.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjmjtrnw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtobbfzyoy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtxmxuoluq.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtpjrtyoqo.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtzpjlgrhl.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrkjtmxd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtjjugxdef.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtiivtmivq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtxvcitrde.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtlilchylv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtsyzqkfzi.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtnhvssqbw.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtcwztwrgi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtnxalookm.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtbcpdoaqf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtlhdpieyq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkdpxaav.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtxzwxrbto.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtxyfcjpxg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtmsxmtfnj.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gtnapsjfgw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtnhbsuxqt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucjjagvd.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtmxwliukb.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtziqwboce.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gtqygqoivv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtpyxjozwd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtcptphucb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtcogyyrcp.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtbbvehbnj.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtitjkqcka.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtchxhmksl.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtfpfgxute.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gtkztgwgyq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtzafkfmtb.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtfdrplzdb.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtznhgdeez.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gthflxcnmy.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtrukadhgm.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gthyegvgbx.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtuefoaqgt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtkfjakrct.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gtfxogbsnj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtfgmkqnlp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gthbjjzbth.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtmnzkxnft.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtzbebgppp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gttvwznpnn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmlwwljb.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtszshbmsc.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtocmeapsp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtulelpvvd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gttgzlagwe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtxiafahll.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtrplyulov.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtzxhwfujs.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gthxunjoly.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtvypozfgg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtipmolbhf.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gttsmvmahb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtfhdgkzrn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtzeealybr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtdftrvwou.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtrlpjtirp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtknsztzlk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtbeglhfol.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtmitphncz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtpjazmujo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtheensfhe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtrlywztay.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gttpviugyh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtximtoxjl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtvjqkckas.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtceruzage.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtayemoysu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gthuovicjn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtkayiisql.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtbgqequoi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtkobuirlm.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtnbulolhu.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtzormcwbn.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtugagrzbi.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtivijiwrv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtoyitbnnb.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtepwjjtif.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtfetwaiyu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfpwrvcge.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gtrctkegxr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnstokmsv.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gtbqnzwaxu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtarjtypdi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtphhmnxeg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtihuktdik.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtewayqkky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gtsywnmsxm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtfapmmtmv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtwzufglda.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtndksfobk.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtlzudkalc.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtyigdrvzh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtiuccrxws.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtreyzlxuc.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gturxdbdbq.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtcjdeqztz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtqvwiplay.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtxopfuhex.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtkmpqtfli.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtfovupfiv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gthwzgimfq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtfmjkfrqc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtzpkbqzvn.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gteqmmhpey.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtoetfninm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gtekikepme.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtiitlwgwl.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtcqmqvrdf.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtpzatizgx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtwzcjexrz.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gturabnlwj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtwfyjaick.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtncnsolow.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtttylwjfz.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtlxznbfds.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtazypxjpt.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtbxdgwzwb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gthlumqohf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtzmopbgzp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gtipuxkfgh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtgbnafsiy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtbquxkqbz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnhrabyo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtbcycbftm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtcykzcmue.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtotkrnshh.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgmvysum.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhfzpptk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtmzkxoaom.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtueqoiprl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtbuughkep.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtgjxvexev.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtgzausaav.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtjfixzjlq.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtjkvjxqaf.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtttjclobd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gthbgzlpjn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtknekqbya.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtyafbihud.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybinvbto.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gtaxfknpqt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtenpvoxqm.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtovgoespv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtedqfpkhl.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtojepnjyw.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstjfqdlv.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtwogsdtti.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtslcgxomx.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuiqqobp.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtczaxvxqd.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtjrwrgmqo.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtnvdvxlqw.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtidwssdcs.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtyoarkgaf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gthwnstnpm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtyhsjxocr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywadgasi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtngirjvhe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtlsqunlla.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtgejugenj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gtktwbkcvn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtbaemvdet.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtcmhijnvu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtrqgazthf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtnpbbscaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtvtogmuyl.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtspqmpaft.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtutjayzlx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtlnectmts.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtcsbuemky.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtbqpzjwjb.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtegmbaigs.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtvldbksyo.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtnhpnxjdw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtdkgzrjmz.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtynfbrvls.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtrkawsjms.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkizdwzd.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtpxrqzpib.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtsgsqmwng.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtzhylaaah.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtfobsbjzv.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gturalcvmt.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtdwsxikke.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtsgkzrgyv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtlspgytgj.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtbnvaeqlz.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtrlkkysbi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtbravjdog.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvrbmcaj.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtkqmgqebs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtcjtrtsbz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtaivvocuh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjlkkkik.html


<!-- 参考信息 -->