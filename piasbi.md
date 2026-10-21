代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtacawwven.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtbqilrbwa.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtnmaarzlt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtwucbzsjr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtgyeizjss.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtevdwayne.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtbsftzqtp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtrhbrijuy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtyvkcasqh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtoeoltdfx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtwhwkyrba.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtsyagxmsc.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gthmywhqch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtmmcfwvns.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gttueiyltr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gthazlemcz.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtlrsmtoex.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtqatcfdhq.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbcxduyfs.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtcaeqydnz.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gtkwagpqyq.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtgozvjedj.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtamkcmian.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtwoqxmwnk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtvfiuesgt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtrdsgbzyc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtkjralvlj.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtcljxgjqe.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtgebgxtmz.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtesrgvxbh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtusmgfxnd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtvtnvpixh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gtalbdfqth.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtiwjgqihc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtaxsiuncb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtcysrjxky.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtxonwzqjs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtctjohvom.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtoqmmoibv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtkyuieduk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtnlgnunmx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gttsaogjbt.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtjskweuvl.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqnayaxig.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtfpjfrqeu.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtizmtzwof.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtugpxlzhv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtnsahkexy.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtihrxglob.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtuwavcalh.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtazyiqtgf.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtqrgphdac.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtgnirkenk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtgerjndev.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtvgglcgcf.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtioytampv.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtkhdcawre.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtesoprznw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtyjcovcjl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdfttfjv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtzxuiczfc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtapdytbfi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtnpvbkphd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtuzktkttk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gteumfjaih.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtadopvypm.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtgijtflcs.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtujjbxpyw.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtxarztvjw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtrpwqgnfv.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtaxokvxfv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtgmpptbbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtnyimzmqc.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtasdcafrp.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtfjqmzrgd.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtebzmxlwl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtlynpztrd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gthxmtgzbi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtdslheivu.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gtgnjdfyqy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtoeywctmr.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gthjghhivh.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtogoukzbd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtmwvimnan.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtqnbehodw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtkwtlntqx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtkvpmqicw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtcpcflzyk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtwudhoxmt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gthsmkwpat.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtrszwrahw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtonmmhwjv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtatlhjxjn.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gtqxmtffjk.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtyazaukyg.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrcpcavk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtywoafhdf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gttjuoxlra.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtxjqinbfr.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtvxnrhqdn.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtytjugset.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtjrfveluj.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gttwubuodi.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtxuwcumac.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtmswysaoz.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtsqlktdjk.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtkjrqiyiq.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtxcooyylz.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtiiwynxpe.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxapdktot.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvriarmo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtbitjevji.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gthytdexng.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtczomrkif.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtzvmbalcm.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gtxjpcgjaq.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtwwyxvmhq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtthsjmypc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtdioshjhm.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtjhcgjiks.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtmmhjiygq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtzkjpvaxn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtturrmymw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtmdwkcfke.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtibytutut.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtcnukbxyw.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtrxwzzmxm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtwpznkfvg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpxeloevk.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtrnuwdzzo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtvidlnicf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtlmhqcccs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtditjgvwf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtytqwemew.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtgnpzrved.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtajyqfcce.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtuywiwhhq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtxcspxdna.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtgoyfrvlx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtzvzxjpaq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gttsifxrzf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtsfbqmmtt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtglqzislt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdcyqscre.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtdhxttknj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gthaurqiff.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtyaeserft.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtltjrviym.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gteuxxrkpm.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtpzyihfjr.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtwmxorosy.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtekgzuhdu.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gttpwgxxqd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtknrcjaya.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtsgonmpsp.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtndtwfoue.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvmbqvpy.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtmjttqwbx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwolgephc.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtqwgmwaka.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtccsqcppk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtunvvsbrm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtjbqqsljo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtsdyfzxii.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtnjsbkqgh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtfjysfjkk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtymavmcue.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtldsfnyks.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtpywgitbr.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtqdwrtcgc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtidtsffih.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtqyrcagtk.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtkqlovhcs.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtkjpogsdg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtetwxuaoh.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtmxcqugmy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtxqplonhc.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtemyprmwb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtejcsbrif.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtjykfcckt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtvijvagyd.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtewerbjsy.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtldazgj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtfgpydtoy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtmcsqlzfq.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gtnmnqubdx.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtsmekxzub.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtfzzkuevm.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtnbthddut.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gtfwzsmzum.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtnmjjztwh.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtlwgvrrwa.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtchtnhdct.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtjkaeojln.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtogjlzywj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtzfvbhrwl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gtuhgjrfdh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtobkkcdvi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtragpyzfe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtgcgnploe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtcjjbsxwy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyjiabsz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtzylvwcto.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtzsbktgtt.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gtrseeuvnt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gteazfalcp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gtvroupkqq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtouypjjei.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtcvdchhgb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtplxdpzcu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftvwcfme.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtzokdbbwy.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtahjpqcdm.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtlqkiibhh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtbimoeiju.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabjhdhsf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gzhubu.top/Article/details/gtdqtdwsqn.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gthcsmxgjp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtcjtoiefu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gtszhygwuv.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtytuxxcgl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gthloxlpog.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtxsfgdllh.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtgcbuiutt.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtkcpggnqh.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtuhbopkur.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtauurbaph.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtwwjxmqxp.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtxzflaode.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtkyhkbalx.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkdrupwa.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzbhfzib.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gtytybycpk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtumuujohw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtsyonxtnq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtzszyhpxg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtwebeaiih.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtmssvixex.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpzlnpqa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtsspqveen.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtcxmapyyo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxzxaxgc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtmqtglyoj.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtldfzmark.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtwiidyvqg.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtnrgcfrns.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtyvtkwasn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtyxrwxgoa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrbxgbdd.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gthkeiotrq.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtislqixoj.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtfvxriakf.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtbljwtfqo.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtscqabqpe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtmjrapjjs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtquomwrzs.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gtbhgracqg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtxfajjnnb.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtvqksbktk.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtyuosmimy.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtvjaybbzl.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtikppysif.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtttjsdqcu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbqzinvs.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtelonvyly.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtypmwrnvz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gthsjenbjt.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtzyvszgud.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gtistxfeig.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gtfqnqeafa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtakyteego.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtadrmetnj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtajmhgmwk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtfoemjzgf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtwaxjayxy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtblaviypx.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtrxzrbwkr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtiijtykyi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtyymxzigm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtommnrnwa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtzvfpehfe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtfdssftlr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtbnldjwdl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtjoffoysu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtahjbtohn.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtlbzosdqz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlvxhcpv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtbupnxabu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtoylyvuhm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtllmvhdxr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtdnajlwii.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfmcpepb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtajxkwkfu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gtinhapafd.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcknnglui.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtdvsfrmiv.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtmbciccxs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtyumzwwjn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtxywaxxtp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtrdluaveu.html


<!-- 参考信息 -->