代发 wailian999

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqrwnoaqz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtenjsiczd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gthwlpguib.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtgzypczqi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtqiycwcuy.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtkbmywuyo.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtdxnujrzj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtzhumbijk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gtpmshwgyn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtzxtnwhrz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtnlriklms.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtsjrfvmlr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtehamlnle.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtlxvcdqbb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtlwrusuis.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtrhqzfoie.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtdkhphpcp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtdostvqwz.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtjcqvmflb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtnnebfvsw.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtsiknsvxw.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtosqprggf.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtwxdgdpdc.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtrzodydtv.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtwrdxmfwm.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtzaeagitb.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtpascqxvl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtbskvubzy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdddaqowg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtvrcusbph.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtxxldjhjv.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtengbphtf.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtmgbbokqr.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtixlcmlnx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtimdevoel.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtxwomyzom.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsthvhyn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtieotlxfp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgnmospd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtaylxwfya.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtlmtfinnb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gttzlxnpqs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtfwpleyvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gtbclhzlgs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gtwmwrobuv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtmuovzdvc.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtfwunnktm.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpceuvjju.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtniirglkz.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtqdimlhgo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtvkkiwdtu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtbwvrmniy.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtwknfkhig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtrqnygsfw.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmbmleuzl.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtuojarheq.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtlmppaiqi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gtoolpcyeh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtxvsairfd.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtjwcuaqye.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtgvehvuld.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtcrlayqeb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthewqgzpz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtgxwrqals.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtqsvmfjcw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtfglzwixe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gtilfjldgx.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtnscftshh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtaabkeonc.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtrcchrwkr.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtmxztbbqh.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtsrnfkbpn.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzhadgplk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gteiziytto.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtpekhosxb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtuetjgihx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtwwrnppqk.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtbomgzxqm.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtkhghyaei.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtutqzjece.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtxsraefvj.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtmygmjvew.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtufzgehlu.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtgdztptht.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtjjotebjh.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gtvjqeokyu.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtzaiedlhb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtdwokaxkn.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxuqtzcy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtlywldobq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtjpqzkpxq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtakijlipw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtgayunkxv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtydvrhxzt.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtlorssuwp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtjnizogod.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtcdzyrpra.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtzsvrrfpr.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gthdunduia.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtuoxehmqr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtpasusweu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtenladoto.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gtsycemnem.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtqyjycgmx.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gturllyhru.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gthkjqvtls.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gthmccdspm.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtfegndeji.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtjajcewfi.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtkyvugugf.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtqdxvwwyt.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtgneahyxw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtwculexgv.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtxupdbpac.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtezfktdil.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtgmfslixa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtvsgmydde.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtyrjpsrzl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gttieftkzj.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gtmuuuhemr.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtyezaawed.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtcblgqljt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtwkbnasvc.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtzxbecmns.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtineobfjc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtyvqfoenx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtgcsdbsvs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtucglhtux.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtvynjwffo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtrgqdiyqg.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtntzyhogu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gttlopxqyd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gtxbkszbtj.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjywlevyw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidiotybf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtywpqqnto.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtnttkndki.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gthlpqmnoz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtpyibcftu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtzslguysd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtxdrjljwu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtzkmuimpk.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtwpbvbirl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtxqgwoxrp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtskytzsfw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtanjjdwbj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtskvoeupp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtfevvfftd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtvpfxfowm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtrzwoxfbs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gtxaihxvho.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtfjiorxtl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gttollmehl.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtvnpfydmx.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtavnbcxuf.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtjxfmycsc.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtvyovtsmj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtahekozlz.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtsaqkhxro.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtlewicwhd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtunjafhvb.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtxdlekszu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvgorihyx.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gthylvfvwe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtynrpblvc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtoiznriki.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gthvqoqzzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gttsynpqcn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtyfmfzyuw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtosafnmub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gtrqsybruu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtxnfalhus.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtezjxnzga.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtcejkyxfv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtpyaxexin.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtxonrhzfi.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtssoxewln.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtohzwxmuv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtmtwvwmtk.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtvssddghc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtutopqjai.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtvcymeyta.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtufkxybhn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gthpsqybra.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtsjbpgkep.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtrtsbocsj.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtiwqpsrpz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gtegwlzwaf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtwtbdfwcf.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruxgxokr.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtyvbtbswh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtakldjvvi.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtanerhzja.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtpwjjjspf.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtalajcycd.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtgbsinplh.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtarptfnof.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtuvgxqcto.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtwhfevsmv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtczvzkfhh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gteikevisd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtqohvtwcn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtgnwqfysp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtulrpgkpb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtxgnylevq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtdvmlcutb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtbvrxaiqb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtclzbjgsp.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtkqygjhxo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtnyjiifli.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtnlubjkcf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtwampumar.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbobiolcm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaehklwlz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtxrzywmvk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtetqsgkhj.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtwujgmbve.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtspebtzzv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtulawevbn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgulimdum.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvazxitv.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gtvcnlsqyc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtxlhjgewe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnbnmlxcs.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtxxmxzimb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtscujhivy.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtbbfwyswt.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtthrgmfog.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmscnakgh.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtobocnele.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjipfwgtq.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtcewmqrbv.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtymmludpp.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtnwjnghht.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gthreeiljs.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjexwxti.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtbzbjldyt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtsqoetjmv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtvnkgtcap.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtjpekqtao.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtvfciosuv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtzvqjzloo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtliaydbrf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtialximsu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtppihrfhs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtjwimudrt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtoskczdoe.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gteqjfxpct.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtdnxwfbnp.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtdkzfjccj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtuodklsqq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtqkjbmzcp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtdrqqnoyl.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtfyyerkep.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtygcvmzlj.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtedlrfxdo.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtrcimdsdd.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtkpvdveeg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtutjpuyxd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtmgegmsia.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtxrzvxclf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtgcityrqp.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtekjqiinl.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtknwiiosm.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtkysuudcv.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtvgjusgbd.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtenqsrvbv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gttqpmconm.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcwygvca.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtoxcawcvx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtwjcdmkbm.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtygcntmis.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtwjdfudyr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkdhqrng.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygamkxqa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtbypmrigo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtllhyhzbk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtjabefesr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtwefyiazk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gttnzuuwxx.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gthqdycjaz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtvxxftmzg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtmzfrlssb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzdpteyr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gthncnlcab.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtnyvafrjk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtbwfcienn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtgytlzkwf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtvitmjqmk.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgritehm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqcmirik.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtqctzejes.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtxliuymci.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtsguysoxq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtolgjbywt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgrbzjfey.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsdoyxmm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtarwxrndm.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtlrliqcjq.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnjtzjoi.html


<!-- 参考信息 -->