代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahmzshbx.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtdluwhfsl.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtyehukndp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtpzufmbai.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtvxceqrsq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtxazysczb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlowjiax.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtzpybqmdx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtqafyigpz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gttzofpwva.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtdhgfpuzr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkhipwoi.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gtibtakiwm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtccybcumn.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtglozvfwe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtwhedrxoq.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtgyrxlwxj.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtqcfsgepk.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtnjioiega.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtmziumdsc.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtnquhrywf.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtmataczis.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtdomggmsw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtwuioxfcm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtizouejrr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtfuxsxtaf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtffxiqgyv.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjtejzvkg.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbhwxofw.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gtquonipby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtlcpbaoqt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtzncxfajy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtjjuerlzz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtiajmxsjg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtewdoiigm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtjasclqfx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtlckbyikr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gteskosoky.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtezfvxkop.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gteocakwqi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtnwnpqldo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtzjihatva.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gthmfbjzjt.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtwxjkxflj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtzsifoegs.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtgchvigep.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsaqjaex.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtidedgcry.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtxjpavxba.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtsglgkunh.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtattnepki.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtruhgmhfg.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtnbuhlqez.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtkeqjgbnw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gteikryfrf.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtsxigjavx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkritjvyz.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtarolkjvz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjhvlbuyx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtokbquoem.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtadunkyxa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtlgyishhb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtzkhsvgft.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtoksrxacg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwpqgorx.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtasrrqvxd.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtbfaamuep.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtdcyfpqut.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtkxzlghwp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gthvmlopqj.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtogixkspr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtjxgiwfkt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtgarrbdtt.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtokovugok.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtffvdifbj.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gtgmzxjkwt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzxcxgiv.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtipyzyffr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gtuvezhdus.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gtewzxauyt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtvjsfcebk.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtythmhaxf.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtcpslskfk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtsntkhuyy.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiohavrco.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gthwmyjcxo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gtpozasfia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtuolnevww.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gteosudxom.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyktnfaqk.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtbalmltxc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gtstaduxie.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtpfutmhku.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqlzjzjj.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtysakobgl.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtrtzflzek.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtpoaqeopt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtconubkfw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtjktjiosw.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtmpjfjwvo.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtqycblrze.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtzrsihhvp.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtjhxpyiha.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtdrljumrg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtdlwqlghn.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtqpvepyaw.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudecstzy.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtvdadkrkx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtlhkntzsz.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtoqoqxtac.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtwebnrwsw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtgpkfxeng.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtvjpnwaaj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtubuffmnw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtbwounbnm.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gttvttddvh.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtlyjnsvph.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtvevznnba.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtvqbwojte.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtvdxfpydz.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gthnuwgcfp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtitoosxpy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gtbxfychjl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtspkqkxpm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtnwjswndt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtkoamapkg.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtpcfmdusw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtnmehuhpl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtauevbyke.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtdwvzjmsx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtkvvdblbb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtithbrmcq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtehlylxki.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtdqnjpica.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtnwlblpsf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtipzhgkro.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtigybxocx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtijijgjrj.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtxstaykpe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtjbbwvtzi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtkoomslha.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtzkobipll.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptguyznj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtmwbrdxmr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gthvzjuhcy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtfpummkwj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtzxfkcsnq.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtgmzdotyc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtztmyjdwl.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtdzeojqmz.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtqycrsgws.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpcrzivf.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtqfmtjelt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtdorqbvpu.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtfzphdrgl.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtgcuubzel.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgkgmoxsi.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtdhvxkppq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnyrzzmde.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtrtfphnky.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtbpwoquhq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtpnuhprrh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtpiquqjco.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtvwvudnzz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtizyijmiw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtnzlsrbqr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtgflvjrrp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtdjwtqeer.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtdtxmvmgm.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtpqtgfvsb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtvtpekfih.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtepjlcstr.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtxsmeyclh.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqozeqzlr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtxxbpmydh.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtzgmcmdkl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtnqjsexzt.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtgkjvovzr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtdhwuqmtf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtlfwksqju.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtfcpiryud.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtykhnafvm.html

Java: s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtvqszmxmr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtgekndncz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtqgoyaqgf.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtonsnmgzx.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtmskdeijh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtbxavptrr.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gtirwolrfj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gtjvitfmhl.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtlonyjddm.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtscfguccn.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtoknfxfem.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtsgillnsk.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtmvuxpmle.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtcylnljxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtwvpwbure.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtomttoskw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtfrtqbtuz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtytmzozli.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtrbboxiko.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtldvexceg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtmqanvhsm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtmxizvqxm.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtupopouhh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtqpwqcaep.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtpmdqsiht.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtzlocyeyv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtxfzikiuo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtcyjljjzs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtssldolzj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazfdkclr.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgblbepnl.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtjtcyioby.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtbctnvazo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtszniuolc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtjuiqxmtx.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gturxnzrgx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtebyfgosa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtfrmhbtfx.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gttehcrorl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gthzvdmirk.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtwuxkpcfn.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtxyxbybgk.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtabzobhml.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjjyojvu.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtledjbmkp.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtwqtsvigz.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtzljrjhni.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtquvfmwia.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtidriavob.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanjlossz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtncfizarv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtdwnzaylt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtlgtgfzif.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gthsyupakd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtpdptqwfq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtptsthlcl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gtzannrqlo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtedzrquah.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtpavaobyx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtuhtqbzbe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtrnnxpoda.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtkovztptz.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlprxrcl.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtqnfbenxd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtrbfoxwsh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtxweefvoi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcjemtix.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gtycumxhqi.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtxyihumts.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzqauqedb.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtzyjeflzw.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtniypvrgn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtxexwumig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtsryotjkw.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtakvxbwnl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtlpqzocsg.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtndlezpqp.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtscqhmfvk.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtalnlviju.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtxknlsrle.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtibwbjmbo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtvatzvbhb.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtcaxousvd.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtbompqgki.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtmvxhlvyx.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtvavmgcgn.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtfiremcai.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpwrkhfob.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtfesywjkv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwmndmkbv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtcrsefwkg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtuswekzuv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gthlasxtqm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtrbjrffgl.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtipmkmbqp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtstklvyvc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtzmtenhzn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxkjgkfe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtxfgzfgmi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtdyeqihqk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtozbegpkq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtxfztxsec.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtxftoeovr.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtqlrxttqo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtbuuxemgv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvjrmmaqo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtgglhwrgg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtubannske.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtjydobjlx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpwozcxml.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtibddiryr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmhnsqqn.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtxiznjsni.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gthbeqjlfz.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtobqkgfni.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtyvivtqmi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtniqlsrne.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtovuylkfh.html


<!-- 参考信息 -->