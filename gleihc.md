代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gttcfbcqoc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtkhnzjiwk.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtfcbfyqqo.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtauwqcwhu.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtppeposju.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtsrhsqwhj.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gtudjzrali.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtjlluppyu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtskxdxwrq.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtokcpocdd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtuyvbycql.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtiyrpntmw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkduxsvm.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtzrmvprad.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtnhspqagz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtstprlosg.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtivjjauid.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtxykpfrch.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtmglkxybm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtmldfhjxc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtpotmhqbi.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtigjohrtw.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtymyhceci.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtzpjpekqb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtoekiuodp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtugmlzrnw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtvzdncvge.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrawkzwln.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtqllfettg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtxdxxqyzl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtgkmehoax.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtjzwncxio.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gtnyzembbn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtqgymehtj.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtphclvxuz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtsdtunxmy.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtdskjgjkh.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtaekyxnbg.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtstyhtuvv.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gtlqjkpzlu.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtpcksjoov.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gttjmnpqma.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtowbpvkwp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtufqjkxaj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtojbaktoi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtiuwjcxtv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtjlgcjdjo.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtnrprsqgg.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gtueokctlb.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtnikuqmue.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtxyegfswv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtskunhrdm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtbfsjfrof.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtdmzmnltc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtcgdwnzkc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtxoncfyha.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gtwycamgbf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtqgsphiun.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtjijyyrxb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtjmbuwdju.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtvzxakcfm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtwukrnrzw.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdhmuxnx.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtovvaatad.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoqypqus.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtixhocuwv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtsaxakfay.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtluucmodz.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcxkxics.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtizfkvuiv.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtawldvvnj.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtslwnelss.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtfffjmvrd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtqolqjdgf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsbzepck.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtgstznqsm.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtnzjjbpwg.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gtltwpykwu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtofqigewl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gtnkmyyuin.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtupgyrfjn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtufblkenp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtgdkezjnk.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtqfcuximg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtbncyqnie.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtaglqatcm.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtzasmcabt.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtqwkzaizr.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtnwbapkym.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtlkmugros.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtzperdcdl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaialzlib.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtvtfwygqj.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtochoazxo.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gtxlwjdcjj.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtxguiwdmh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtzjljlfsd.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtwqgdjsrb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtqpfuefxr.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqyzowlj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtdfeqwenj.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtrfbjssjp.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtloyobuga.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtiarzcfbi.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gttnqxjfae.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtkeazoibg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtcengntsp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gtjbwfdnbe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtnhvsnsam.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtkqglqoul.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxdqegd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtsmpwcysq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtdspytwth.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtidwuxmfk.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtymigiohy.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtkjobwxoy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gttukvwozi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtrmnmyugw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtvcchweiw.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gtejhnjnnj.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqylrayv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gtxqbvochw.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtpqgagbpa.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtsmgguhxy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtmsrjolky.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtxfygygpp.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtwpotiacn.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gttkhmgjjx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtmhbnkmol.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtqqotjypi.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtninrtrhh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtvtswvqmo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtvwxvvbne.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtqizuiqix.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtdbkkaszg.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtwhaqrfkg.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtlvtzlnrh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtybenznkt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtbxeuelda.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtyykfwpya.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gtwkfxcfnx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gttjcudhih.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtjlcfbgvp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gteokihtsm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtuzsjdaqz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtjtrmqmyy.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtindagapq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtnyyrghvw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtxynheoyg.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtqqkfjanl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwmedek.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gthdhlaqve.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtacqwfeiy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtahudlogt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtvockaqzj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtzrswkowy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdtzmcqx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtipeaofee.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtcjinspxs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtfzaoatdt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjnyauqh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtsaoqnpsn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtbqvlozcp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtadfmruwe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtbdhbohpk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtsuvjsvzv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtxlhixooe.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqiyvalwu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtznlfxkrx.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtrlrmzbqp.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtwcowmlix.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtgxzymdaf.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtpuisxfcb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtjecaqklh.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtpheekogr.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtydxojqfw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbooisovw.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtsdmqcywk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjjtlupdv.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtdlbahlqc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtjhoxmwym.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtxoprcmne.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtmaxguzpd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtwongmshk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtzpfofpwf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtzlbeftre.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtpzyiapgy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtzcrvtfgh.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtlgtxhiop.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtbenpmqsk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtqnqqjaav.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtaivdutmw.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtpmrggzgf.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gthukijrbk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtaxywhhor.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtvioczsbg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtmfreubdf.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtdtuwlobm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtmzrurerd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtlqqkjlsz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtvbxkkfcl.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtqscicfyh.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtshtztgiy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtnuiwvxtw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtfddlfrks.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtnbpkslgg.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtblulyufj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtcdkrewxs.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtrmotujkt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gtqrmfdsro.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtvaloybob.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtnxotmnhs.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gteyugcxef.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtrkpxtuez.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtvnbivsgn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtaissetcu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtxlbfktnp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gtoyfukeno.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtinocfyzf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtrohlimpz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtjylviums.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gtmbfxnoao.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtjxqaqjmh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtljpjhnou.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtkvrnsdic.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtburhbxax.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjztguqud.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtyrwdehtj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtkrfatbyo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtbgpjrulv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtfcqmfaef.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtxgpicnjg.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtxhythtfc.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtjhbyuihh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtjebtjtea.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtjkbfmncv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtehrklcsp.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtwnpxhqef.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gtwgufyagv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtorasppxf.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtonrjapam.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gtdnpuqlto.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtmpjuuyug.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtgqnidkih.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtmgpslacb.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtjoamaqnd.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtrfvqumyl.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmhqiepo.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtlfxuvlyk.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtfaihsynb.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtqbgsyels.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtshzvxnnb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtvqzyjjfd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtaltvdzla.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuficfasv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtyzhyguru.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtbgtzdoxr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtkpgrtiks.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtqygvduxs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtysrdjwdg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtnhdgfgny.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtdmdgdexu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gttgoqccyj.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtdkpunrty.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvragest.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtsqemgefh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwkhxokr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtrqpzwopg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtvimsxyte.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gtezpemyty.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtbklplzov.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtsnpfzwib.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtoivjinwr.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtxpjhjhdt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gthetoljso.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtfzmguqyq.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtvpkjkkny.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtdjpavfaq.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtkupwjitg.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraxbbbml.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtdvmiokru.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gttcuvbaid.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtbipkqbbq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtqzdirnwg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchdkpvlm.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtrfrpjsix.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdhsqauj.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtqwadxjbj.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gttayackjp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtswhczkav.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkdwmiwl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtvgesbawb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtthphrxnz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gthjkwoyav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtxgjdwype.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtitfsffvm.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtgrxgbhwl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gttycfncao.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtlbqtyltt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvdkegc.html


<!-- 参考信息 -->