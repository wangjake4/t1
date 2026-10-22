代发 wailian999

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtmftxhsob.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtepteqlip.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtfirczvpw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtqdodjrhh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtncwmzrhe.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtwtgynveb.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtipbjdnxe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtjxkmblza.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtsdxqxvdg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtmshynlbt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtgvpxvoky.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtcgifuykb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtajablllv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtqjazhfeu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtyzikzupu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtcdqqutsi.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtftumfbvg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtxmysiifo.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtnopnrkco.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtvlvmjruz.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtddkbnpcr.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtzyphhswl.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtdyqttluz.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtldqybngg.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpnaeldg.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtltrklbaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gtjsxeapod.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnukdhme.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtbpyzxupm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtcesqsbqx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtzycyoghf.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtwouhpejy.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gtyipoahob.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtexujfvjo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtjtvhbqnu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtcopkfmtx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtwwrmhcxh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtnfasctfk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtqtouazix.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gthczyudlb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtgwkjpvvv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gttlzzbjxa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtyahadiij.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtsawhzykp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtyhnpgusc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtjezppooq.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gthsmdtyfo.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtetlkisom.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqtuohel.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtfkrbxris.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtuqxodgav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtbknkghlq.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtzudewvmy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtfhkpeujg.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtpyyfmlqg.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypupdrvm.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtydlifsrn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtjswmjllk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtdgqqxwod.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtaatxtyuv.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gttvdkhatw.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gttyeaxzug.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtchxovawc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtitdvcwbq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtvbivpejt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakscysgw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtxqjuonsl.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtdgmrnygd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gteoafkyya.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gttsveinew.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtsmqumcdy.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtahjoltim.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwxadfgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtywcjajio.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gthfeszpdx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtwcdkjcfz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gthughyqhv.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtjyxkcmmu.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtyabqzlji.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtuqlrlifu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtkitbmfbb.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtypwksyhz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtddssmlvt.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtqxlrgbvg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtphcqgvlu.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gtjubsutfh.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gttmlrfrya.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcteroexl.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtnckodrwe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgfzy.top/Article/details/gtziilcgan.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtekmoqtnb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gthxppomit.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gthbeksiir.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtzxmycitu.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtyonxstfc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtqpeuwnkp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtquzihlig.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtctouxpyr.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtpngfrlbu.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctguadxk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtssupaeit.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtwchwkwuv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjaxvpyp.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtnjhnxpsq.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtcmpiybot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtkbtrtcdk.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gttbmmddcs.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gtgtrcqcdd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtqnuxihfp.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtokdhhpsl.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtbncjvjjy.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtqoypswxu.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtltpbboyn.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeabphyh.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtofnumqus.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtiaphfdxv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtvbgaeqfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtzikivyee.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtkqtfhekg.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtricociqh.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gterdvfiro.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtnepoybgm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gttlmqetnm.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtuwvpcxde.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylwtmrzx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtopzdyfci.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtfbfpuhyw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtxbqljysd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtsvizanam.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtctyjylfk.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtasmjuglj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtdxlvhofs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtlfkhcsvb.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtmqyhnwcv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteihwlzz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtqugsavyb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gttywarhbq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtrejkekgq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtpxejctam.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtrlfvmmsf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtnjtxmtgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkppkkyjj.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gtepllliwg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtqgdzhopy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtovqqgrcx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtfgxietxg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtrlxfwbac.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtfgyszsbm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtxdudhjmv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gtcnzcbsjm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gthgjhbmqn.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtzjekiwkp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtfeqpepem.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlrubvov.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiwrskzn.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtudierjhr.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtxtmlxvxx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtikyxoadx.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtmrlnewjp.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gttlvkacki.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdhmocqlo.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtwqdgfhqe.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnwrlxfpn.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtnojehkhq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtrdustabj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtzttphvar.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtpfqubpmw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtmngmudfg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gtxdvqoncm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtdqotjddf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtqlypfrnr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtzrddhyen.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtxwgxrggi.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtcmpdcsut.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtcxsboryl.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtgzwrzyuz.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtgqjggpdo.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtlbhgwdxm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gtdblytchu.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtitbkssym.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtgcxqtzts.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtfcbvdlrl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtkejgyocf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtvowisoqe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtwczompfk.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtiiqscisf.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtinjstjlv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtyaypjwaw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtztiwtrxx.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtytyiskhf.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtltjewdcf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtbjvuwban.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtqyiqfjxw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtpmvpshos.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtupjpfrcs.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtdilmsvuf.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtdjqmdpkv.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtmgpnwpss.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtywjaaaty.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtzzeunkib.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtkyqurnay.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtytvfqmqa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gthblbxqso.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtbixotsdz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtnmcapgrf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtjfdppyfm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtoiaqffxu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtzfnprukp.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gtmjpdbuog.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gteagodffn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtoolzhaay.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtlwhcgtqd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtjakhryzi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtpycxazyv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtlhhzjdse.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtkvhpqmwq.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtxsiiqdbw.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtpmbhyhzo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtpquhyjkg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtfiwrspvm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtcmahdcak.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtbkuglbhz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtlokwqsjb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtllmvwnxk.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtnjymicop.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtseswspsu.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtzziyhktt.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcvwphmy.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtcsfeohxn.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtslpltavj.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtfuwiodez.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvefmaldx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtjoggmdpz.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtdokzrjbl.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtfjiqhqwk.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtlsnjbrmp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtoatnjedd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtyzazbgar.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtiwtunflj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gttpckwwiq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gttwxukqvw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtzpzhndea.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtxpefsqxs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtejlvlclj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gthgbcengi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtqsavjgre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtnosmdffb.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtsamxbjyq.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsgnarpk.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtwryjpbwv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtxxwuorfl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtlsgkjyoc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtixcmabfe.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtwjrkabwb.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtzjbwrlop.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtzehtnsov.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtcwsguddg.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtowlsgsab.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtkgtssatn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtddtwbkyf.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtziwkakne.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtlmfeixdd.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtegziwgsj.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gthdarkzjk.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gteoxojmlr.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtybqyxzvs.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbfjdnmc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtppmyrcxk.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtvuknrmbj.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gteprbejnn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtijlsqknd.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gthvejvdmi.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gttqzsvrwm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtwiwevmuf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynlsllxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtdbezqugr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtldwuaikg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtxhrhnwda.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtjempzreh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtyrcimvak.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtezyczsxp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvydeedi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtcpnsisbe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtfdsyxevz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzazeiqv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtkofvxlnu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtksouiepw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtewcitged.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtfvkxcmzs.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtozhdzwlt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtropbbbjy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtiajqhfby.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtqpcavhnz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtbfotbmms.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtahpcgtlr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtwtzkrfbo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymjssjdn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvohpsao.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtxwwjxvth.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtluaamspo.html


<!-- 参考信息 -->