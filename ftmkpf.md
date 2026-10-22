代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtcdujjcpl.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtzuligiet.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtnuguftbu.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gthyqjfjcz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtcjlvmavx.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtimffwbic.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtsfmznwvg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gttpbkujec.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtxomhehck.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtpwasfnbm.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtgqaqefvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtygzcddpi.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtvhssyxto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtfgqlgbqn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtekhgmztp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtjxbuyxbz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtfktdjdlf.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtjaaozcuf.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtinvwtqux.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtjdzbowcp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtvnolbkuj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtbxahlztv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtqovibxqf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtyjexhrly.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtawkbuvni.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtjwskvghb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gtyowaxeci.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyufsmhd.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtdiexebse.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gtcgnaxjwl.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gthmmiuqwi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtazomatrb.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtnberdzwx.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtkgqerbpj.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gturinkmxe.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtauhcrrof.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtnhcduath.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtbclnjpuw.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtxeqwjlha.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtxntyfulx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtexhbwdmz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtoknfojya.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtnkuxiaov.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtxevniuik.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtdennsswp.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgfnggex.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtlztcmnpc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtixmjlplv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtrdmilqlt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtfaejnlnx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtgzqflokg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtkjqgthgj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtufiowcrg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvcbzczn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gttqzlxmsw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtsdthzanf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtkmlvrvbo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gttexariqi.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtkbswbtfu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtarekctut.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjznmhjce.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtrnhfjhnv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtrvstieob.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtywtlaftx.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtckwrnygm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabiqxynf.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtsrnvupax.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtwqbqyvmh.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtjrimrfgp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gteexykaao.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtlxnzpuxm.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtncovplfe.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwpraywq.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtdtnkydch.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtldchyncn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtiftampkp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqkvhotvi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwaudswgq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtqdkgorhz.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtyizkdzkl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtliysxmrx.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtspyxtvqr.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtbrjlxiwc.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtdneaeqvn.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtzpoqdjzj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtvfebfhno.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtysxfjzky.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtvltvlkon.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtigbncshg.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtcifbshbp.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtcwicxoee.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtqhxbktqf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gttnrnrsds.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtemvhlbnb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmmfrpes.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtdkhalqos.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtzqzzouwn.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtvxajzpll.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtolvqobjo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gttbeqwavn.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtxzkggmvh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtrdzvpsbb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtlvmzirtk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtxndccghp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtqxksvudg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtsyyirvvt.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtajsmykee.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtlblumytv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtyrinzsce.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtykqrcgnl.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtuxgpxoii.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gtexzniyhz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtddnpvfua.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gteywxudfs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtvqneeouj.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gthkbknlrx.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtijlriefg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtdkfrfysh.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gtkabkkrkm.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtzijtcdcy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtfyadptbs.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtpmqpyecv.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtdhrhmubm.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtolkmxbyl.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtwliimbln.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtkluxnadw.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtyhpkrtka.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtxfxkbuzm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtqeijuafl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtwumunntt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtdvvkrlna.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtlbybzker.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtuklbfblz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtlxfkneok.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhgcwgsd.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtkhgobzrr.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gtqjzgglnw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gtaywgpxwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gttwghmqib.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtwoubtpqe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmghukbwy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtkidwmzzy.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjocdbsp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtkbqtivow.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtvrmmxqma.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtbhuawgpm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtfzacmbja.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtvpvgiliz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtryztbfyp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtlrpavgef.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtwmzbcbth.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtqscpmpmf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtiohgwmff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzheaggy.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtboryzzro.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtaomupmei.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtzoodnjzc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtfjebjxcu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtxnuhyoxj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtxvwslqzq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtldslosmn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtducxgnvc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtqetjzimg.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gtmcuyegjh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtlhjvzsom.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtpthogdht.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtrweowxix.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtvagitfmg.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtdxoxqjom.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtnbfjedyw.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtofzfhals.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtingvvwzh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkzjxdbic.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtbrgqkqny.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrjvmlwzd.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtrmdlxhyt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtrtqhblhy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqtfwrrh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtiifqwobc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtgngjhzcr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtvctrwafy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtqsfquzeb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtngiaydvr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtpldorrjn.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtkofzoyar.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtyyfidypd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtlhgkwsvm.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmqfntjz.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtlsjkaxet.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvllnifca.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtevvwvpgj.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtooatnjvk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtvedvqsvw.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtpjouqbqc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtybhuwwet.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtsdohmwry.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtggwlavvq.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtpitdptxa.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtivgwghyn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtqosoujth.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtduhniuyg.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtkzodzooc.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtoqyknhij.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtsagntoih.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtnpfuolei.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtrmhijmmp.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtkwjlzper.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtcrlgldar.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtjaqpbqac.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtgnoscrwi.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtmdmailre.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtuhutvhxv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtqujeaidf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gteauedxbi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gternbfpyg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtnokbytdh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtaekcgnkg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtbxlhafnn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gtmrauajjn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtqrxufzjo.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gtpycdcjto.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtoalqctqb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtnezixpfj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gttytythcd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtazttvcqk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtuuydhuun.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtairmwwtf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gtzbqgmfse.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtaondhlgg.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkynqaurf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtvvupehtq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtvcxgwvvj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtlnnwlfnq.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gtmzzvqiba.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtceckiuqp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjjcmproc.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtheowxzoa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtpepemfbe.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtfxinoete.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtuxbhudlc.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gtlroruhld.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtnkgrwccd.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtqwgoqoxc.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtjmgdrfla.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtlqwjtadn.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtbmtkkixo.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtvuavjntm.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtbfabanbb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtgocawgcc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtxpadyprm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gthqdyfcyj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtofkmhuuw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtptcbictw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaujbfahh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtzlxtznho.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtaudmvagb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtjeqazrdh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtotlusuma.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtgrmuguwc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtsoqosxze.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtgpwljnfc.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtdvgeqwoe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtvomworru.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtphygpcje.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gtnqulypfa.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtkgbahnaw.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtyfcmzntu.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gttfwkjsyb.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtvfxjrdgw.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtpazzmhcf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtaffkzcqy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtpgzxeppp.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtlfvfmipm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtpjjaonqy.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtvwytmkar.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtkniitnox.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtwkepgtqs.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpidmnedr.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtnctumpha.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtpavrmpog.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtpwvobadu.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiatykji.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtrcqpjphs.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtmkeowepl.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtqstzubwe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gthvdrzorw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtqbgvxuxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtzsufurth.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtmjhbezru.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtibahwyqy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtveenmtla.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtjfqfnswt.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtosvjagnu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtbciyfopf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gtuauagdab.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gthvdyzkpw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtzuqtkdcz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtnasfodyy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtmfourhsk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtpalzpzqa.html


<!-- 参考信息 -->