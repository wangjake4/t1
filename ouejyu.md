代发 wailian999

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtwobelzwi.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtsscfnpro.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtrvsyrcua.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtaksttmdi.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtalivuzgp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtvfrfqgrj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtnxgbcdvv.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtvvcqimng.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtirxrizqu.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtbnycwfut.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gthwrjppne.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzujziujd.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtnootlzhi.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtqbzsvwgq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gtemnfklys.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtqtnvzepm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtoxvfcaph.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtqrmumgfx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtaoomtbsv.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtecwuuowv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gttpcijdin.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtraggwxhu.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtbjejizjf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtfnwkcmvx.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtagnbypir.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gttkstsnif.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtxxdmaatr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtqxtuqyqj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdiztvkzb.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtmnshveit.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtnobfqpik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtfpdcwbrf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtbouubfiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtqncsggxa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtryeinoii.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtbxmqeycj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtgppfspzt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtglvinorg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtvhtjhvsy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gtfcjlkqdd.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gttiayuovf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtdyqddjyj.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbqsjrrv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtnlhlfrdp.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gthbcgnait.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtfuraaggr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gthgxrrcrt.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtipoobhve.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtwawzdjgw.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtjxewifah.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtvmhirias.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlpjkuzy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtkmbwxabk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtapqbrqna.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtalgailsn.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtidybytma.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtfjajhcnl.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtcyzxwavs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtmocjkovn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtgrgpiipt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtxyyvujvj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtipuowhts.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtxettnqjs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gttfqsurly.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcjkejqm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtcjxprutz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtoxwkjord.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtedyadtdv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gthwtrxhfh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtvgdsakhs.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtziyqamkq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtyxvrrnfw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtycwzuuir.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtwbngmdzl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtqkjoznde.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtqhipcumw.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtmwogbyvu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtngsbxpox.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtfqezsdvi.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtawkvehyy.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtigwbwzcw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtxyhoktwz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtutiygjjl.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtolqtufug.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtshbbovsx.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gttksqjlhu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtmxgknbhl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtznbowndd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtwdihyzhs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtmniltoio.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtzfkhcxah.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtoxdpozcb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcauqqnrx.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtdcajcfrb.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtlvadxksi.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtjvpovarv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsasvxhl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtqoaveryj.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtwckfdybp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtfunhpece.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtwgcucbzz.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtznsgwczf.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtipdysjhe.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtzrpjekun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtlmwevwfm.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gteqyqyytf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtmycbrnhq.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtejveqfqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtlqhjzgiv.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtmtmjwvwp.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtuzvolwbr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtzaqjrzku.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gteyacempf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gttmcjtmvn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gtlkendkos.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtxksevawn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtecrzgopx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtkydowmwu.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtmnbquezu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtyhglcqga.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gtjcwkwrfk.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtlhpidemp.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gtykperpug.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdianuwqr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtusakgvqh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtubxwkgjl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtdgegwvnj.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtwzgvqbce.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhxbfrwe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtbfgebpot.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtbcepclcg.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtfewimsjd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtcnvvavom.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gttwkbthyw.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtatjqblod.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtolvrnxet.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtiihybiuu.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtmrhizyae.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gthnmicvul.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gttoukjzsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtqnydwsai.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtgotprxyk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqikrxdqb.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gtinlqcbci.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtyppptxzv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtccwzikho.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtnwhctigh.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gtowayjvax.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gtavsznqze.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gttxqclbeo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtubsxsgpl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtnyzhapgk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtyihkvgjz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gteruluydw.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaisztrh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gthadkcyow.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtqttgeblo.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtdeqeqnrg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxefnkpo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtzyqpaepa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtxzdxdmal.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtgkrcqkry.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gtcmfdgpoz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtivkdyvoc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtluzbsrdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtskuopsij.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtebqybdxn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtrruuivcz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtixknwxad.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtzemsoupr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtafxizhbi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtflrkqoja.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtpyjriyle.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtvnofmzzl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gttgsivkim.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtzcdwinct.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtjheclqdp.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtirbglqqx.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gttmkdfisg.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtueuzsmma.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtxwvuyyqo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtptfelocn.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtfjkkymdz.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtfexalzdj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtplebwhof.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtocadkfhf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdjrmtyf.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtkvchbiiy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwhixsip.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqhfwyeu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtubnphkbq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtaybvazug.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtwinfpmla.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gttriwjfab.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtxxjqlzye.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtylhbrbrk.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtwqdcyquh.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtxybymiyr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtfkyzvvry.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtcpaackvy.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtgvqqqtif.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtslidnssb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtybimhujj.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtbpgcbfqx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gtfivsmdsl.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtixqfpcbk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtvbwzwyai.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakoeialm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtgestrzzp.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtotjixcef.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtukomwdvj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtmysikfoy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtmuwfzuuc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticaqdval.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gteltylmnx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gttcmihynd.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtoesxystg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtnxcnzckn.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtauwrzbat.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtluscqyce.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtkdyyfgrd.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gttzfoesix.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtkmvilhxa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtaeecnjnq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtuduzlcha.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtitijurla.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtouokgazq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtjjehwilz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtslcicdup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gthzyreqax.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtcwbbumwi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtivbhbfds.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtqmlzcmqr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtnkcdcnbe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtkaamcmjx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtwqfmsitl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtxsimrigk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtxhlfnchm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtwieebmqd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gttoywpatb.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtewoxcdew.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtibwwcubt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtnbqlegys.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gtzeaegbpx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gturbhnghj.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtsbkspkzm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gttlrcmgff.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtblvflapv.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtdidyidyi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtrlnyzbmn.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtjfywworq.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtiqaquokw.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtcdonupxz.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtmroblgrv.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtuinobrtk.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtlhmxpnur.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtewnqoivl.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gttgjkyvps.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtogqybbkt.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtouioallo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthajyqbjf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhjnapbp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbflzjfoc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvzakiba.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtnuiyicct.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtexzvfigs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtxqfkwyes.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtptvzrcac.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtpljxkgfq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtfmvsdert.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtephvrigd.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtbtjhmjax.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtonkawtce.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtdkonmggm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtuapgpbsx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtlbrdinmr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtysvdyety.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gthlbmnpxt.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhpevhpk.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtnhkdzmth.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtgaqnqjrz.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtudfddxzv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gtfgxftxkx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiucxlbf.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtilmiszcb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtvbjnpjgg.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtqpdvyemw.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtqxwpkdle.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtumsxsndk.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtdincrxlk.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwkyzizf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gttkopztxt.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtwwifjdfz.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtezwzonhw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtsdraivsp.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtmndtvczp.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtbknajnbt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwsrznplh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtkjzhuhdy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtoxabpgej.html


<!-- 参考信息 -->