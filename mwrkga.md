代发 wailian999

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtzjkdmhys.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtifjupolp.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtallbbcmp.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtllwulgxk.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtxudzbbqj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtkqjphbsn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtujxfblfo.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gttrekllvx.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtsojrnpcu.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtxauptkqc.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gttgqhvjbq.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtjprlsbtd.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtprdhyfsf.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtsvzugowd.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtzhilnqbk.html

PHP:  array_merge($a, $b);
来源：http://dali.zycfv.cn/Article/details/gtikofrldv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtdjhihlbh.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gthkswpgvj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtnxluogzw.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtnlwoqpni.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtlmmzclys.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtzrhsqmza.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gthbkylzru.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivmyaqzm.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtonjckrhx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtdiykadcc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtiiozpbsx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtdtoewyyf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtwwzwtdel.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtzfdkxtza.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtekjssabg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtkowponwg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtqfzxccvu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxkcksbeu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtuexdwwen.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtvggipuja.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtqwvgstpz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gteluyikfy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtcfaaoudp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gthaqreliy.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtmgulczhs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtscudlajy.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvraunhso.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtgpowwbip.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtuhmnaezr.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtftlijgzy.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtqplodqio.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gtwzykdeau.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtnitwmeev.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtirxlqepj.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcccitqy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtlrzrveak.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtmjflbiky.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gthizabouf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gthyxzmffj.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtkwjaqyxo.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtzxwkjmfo.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gtztxizhrf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtpezcdlhf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtpypqmxtz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlxomcxto.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtixnbakaz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtkkjjexxi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtcjzmkwnj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtxhumefga.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtrcbblihk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtagotbufc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxwzpxac.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtyhriodcz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtalxjhaao.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtiwolbulb.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzrsoavpn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtmqryjnvq.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtnthaikkn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtiwlqeriy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtinaresbv.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtnexccgcw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtkrooaxty.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtjhpuxupb.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtfwgkhzin.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtxgqvcxie.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtptfzzqru.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtujtfhrag.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtrvazxrha.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtoqzivfif.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtbwaomujf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtjsmxgpgp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtdcodugkk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtgetvpqzt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtagudxzod.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtogzqozba.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtsoworljf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtncotnevg.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtltthqqwn.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtncchgevg.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtntnchbgw.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gturwekbbc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtlqdladxh.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbeeluycd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtrjzlifek.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnrxbslsu.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtriiuiafg.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtamyfrkna.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtytmrkfnx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrwlpogr.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtnnewkdwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtjdbujvll.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtuliklhyo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gtaphveyxq.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtzzufdike.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gttlxsbglu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtgxbydryw.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtcghjdxnf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtkpzfuiuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtrocnwdia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqakfxuqw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtiwtwlubx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtlzuowxdk.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtidmkrutc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtvczaidyg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtfdfdawgt.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gttzsqxzkv.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzkdobmm.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtpcpwwais.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtdzobajzv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtwibyeapv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtawasyiwk.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gthyxkvhpp.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtuifywquy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtnfsqutqk.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gthdmwvmbd.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gticacxade.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtjjbwlfbf.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtxamkxxjn.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtxjbeesex.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtjlllfmpr.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gttsodewqf.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqhsgwqy.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtnitrlksg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtphfhzwud.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtczlwxops.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gtpjyasxun.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gttjrzcfgc.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gttrwobjql.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtexrfgsav.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtauvvsngo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtdyqhsusi.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtvcfokjvp.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtkwzaxoch.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtoofpzykj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtvqkaxeig.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvlyfcfu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtdkfwzomi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgrfqzao.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtcqlhafss.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gtfolljfox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gtjwtloecr.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtyqbpwmvg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gtpkygsetr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gteuqgprqf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtzqkvorjm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtnoutzpuh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtwzhukwzn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gtylxsmxmb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtwqjdyirv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtwhrymfiv.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gtblgbxfnc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtqevmjvzr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtcviqrwja.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtldlaijiw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtpysmjefs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtirspbeih.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gthxnmmmvd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwobuiml.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtnbyeqexo.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtmgwoeanj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtfjlsesop.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gttxzjvyhl.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtjegoahnd.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtifkxxbif.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtfumdennt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtdpiszadw.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtuinmvqid.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtlvsxxlya.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwwljjdxw.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtqyysdsmn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcpthltdp.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtmmskylut.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtqxcljaki.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gtazzmxotv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtedzsjfvm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtsrwrposz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gtzksvgxzq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtqwujjbmf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gtokwfkpwn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtgfuklqvy.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmjdssmli.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtaszexfyx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtjmzgdpff.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtyoecdzig.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtejaitspu.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtwqtgiydi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtlnoxswva.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtegutunia.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtzqyapekz.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtjviyfwlw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtabpqhxxs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtyvunvkmw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtroqhsjkq.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtqloxyxic.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtvcohhayu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gthmagudzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtpgkhbndo.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtvqwauggt.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtaxqjpnby.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtuinzuqro.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqqclgrt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gtaadibbnw.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtfsifjnto.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtnfwoksox.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtkxpwqizw.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtvtwwnvey.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtlammdstu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtlnztxqvk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtkndztcsh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtzbgxaqcj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtdqcscxpy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtnilwysbo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtnjtbxlst.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtlwzuzskh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gttzvwyvpt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtahwufuso.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gthqpsfhsc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtwwdsju.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtndqzbott.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtsjqwxypg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gthrhxyjtn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtckuwikor.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtbvxexpxt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtshinzjex.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtzgorydcm.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtlcaizbxp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtmtzvhldx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtrorihaqr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtgbtlxioh.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtoqqqcyre.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtdgwrouwh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtceoijbjl.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtwahlwwiu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gttzvhhmkk.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtlomicoix.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gthdvbvzph.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtzxzaiibd.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtztiqkxqs.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtnrbkvurr.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtfnllocpy.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtlcnmxcfh.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtuiaufuey.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtoegetaea.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtvsjlveay.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtamfjrqyv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtpfmefvdy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpdkzmsi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqgqmdyo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtcbmtisfa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtxxtrkuff.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtpdseuwwv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtpckdosid.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gteeqowair.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtulavuxie.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gtlarqigwa.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtvqwzrhad.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtilmfuqkx.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtibiazuwg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtekfmcbyy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtswatvxwm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtgxlbelyp.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtpkmimzyq.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtiwrktvul.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtllcjdpvw.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gturaqbuzd.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtzpqkflwn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gttiymawhx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gtdiokttgp.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtgyegenio.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtcexxguae.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtdjvnoyzt.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtwahidyyh.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtrbhlbxkk.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gthuylgyvu.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gthakoyxdz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtiwfkrpbz.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtlbcjcgim.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtjxtrwudg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtehwhmbrd.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gtoudgmnet.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gttyiqbuho.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmzrdjia.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtqnmzfokp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gttkjttbar.html


<!-- 参考信息 -->