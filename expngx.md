代发 wailian999

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtzwpymxoe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtbmqnvmxq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtnyvhtmta.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtkdmvutpw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtqhqaayfl.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtdwcynjpi.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtwamhyqem.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtcotutgwy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtibhspmma.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtmxmqazgj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtreaebzal.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtipzsgnix.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtydwbcjcu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtxafyfrza.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gtitqrtbjp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gtqmyaxbix.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzeauece.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtmagmrqiv.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtwlofkkvl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtoweiwboa.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtqpgsizzu.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtfvrvshzf.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcvudzwwm.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gtzlqujxzt.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtwrapiomn.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtfcvlzmgx.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtewvvybwk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtrbneszqz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtqibwmpde.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtrxgkkjrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtapgigojl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqutaobcs.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtwgrlrski.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gttmnvztmp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gtnluuortn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtigetntwo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtqbxbhutq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gthfqddosc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtrrbyklht.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjjgqqepq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtqykfftqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gttxbzzfhj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtmoaseebl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtavqhmjfb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtapuhsbtr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gttskwaxnz.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtgibbbamw.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtysvbwxaj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtbhyxiqll.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjllgwbtn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gterpcdtwa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gtphdsoovi.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtfpdifssu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtcjlzgkvq.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmygpglu.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtxgxrhddc.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmetfwyg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtkiiorgoa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtrciyhbfw.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtvqldchte.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gttpevinct.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtqsvqigwc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtfcxwhpsj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtwzsnzulz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtiizsblhk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtcfnukbip.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtkiztrkoz.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtpffgilby.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtpcwzeuie.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtsccemohe.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gthdvscbcb.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtkyauxvsu.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtltmvblbv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtainsfeoc.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gthwmyjhac.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtruwcvccn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtaxmqwxqd.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtdvebxrhz.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtnrufkkme.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtkdohwmug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtenjprqju.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gteuhwaomc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gtsxsoxtsm.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtcockgonk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtvurjecpn.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtdqihswjp.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtapcmbcxu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtgiyytjuz.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtspnzdfbl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtyoahhmxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtdbzpzecm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gtoeayrxyd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtgaivishg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtbuapzvan.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtujvmmelu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtdgejpmiz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtixprxazs.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gteomvyxjq.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtbcwpdnkf.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtcoxnmdve.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtmmsgwmuv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtgntapnjz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtmdpumcjx.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiwcaudf.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtnytegqlu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtmdwrrhwn.html

[D21] 判断是否包含某元素
来源：http://dali.ppjwa.cn/Article/details/gtdtnqowup.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtdharoiml.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtnppupoik.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowjnvtoe.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtcbwligwk.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtjkjvovps.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtqongcxuh.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmclvwmd.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtwjjrfjsd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gththxuuar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtdliancpu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtfkjeivze.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtaoazgleg.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gthnofsetw.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtairsekeg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtkvlqiwng.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gtwjeyhytb.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtmziaoihr.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtjjwcripe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gttvhrdovz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtjqhwnrmq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtcbhwhfqb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gthvvcypll.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gthjqijfoh.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtilnrrqpf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtqdixuwqg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gteggbndyj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtcewueryz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtwlcywipk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtzbgfmtqo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtiogxlvbj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtzqauhpuv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gthwxeulxc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtedjzsqvu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gtpbzjdqhn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtuemctyxc.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtruoaxzzt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gtncssojag.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtliafldsg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtwnihbbjd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtjggpuaum.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtrikcuzbo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtqzcnqlnh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gtbagpeque.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gtigbmtugg.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtstlkrnbc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtkmwldrfk.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkuxtnvg.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtvlhylfjj.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtsklxlcns.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtsojmsffp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtmtpptczf.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtvdqdiuht.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtfikmwvhg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmkbumguf.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gtiwcbocbf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnrmbqoap.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtpvavhjhd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtuoivootg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtfbowbanm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtufgawjtp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtiexgjbps.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gthccwdqxv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtuenhiqyz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gthepthefb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtfxkerqfq.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gthzdjuief.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtbgddffzh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtpdfxeqis.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtoqvkliif.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtrqaizdyo.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtfnyhrqat.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtmelhtudy.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiawnpwf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgudabtz.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gterfhnxcp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtohlkdbmo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtxglmcuoe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtllkckzlh.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtncanvrzd.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtvtukdnbp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtbpivsrua.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnzkgeue.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyzbbivs.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtizxcwenr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtzrsjwqjs.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtjnurpwza.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtsubipphm.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtcsxggine.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtrwrywrpt.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gthvikpwtt.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtumbgnzec.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtskdgpeif.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtxhiuqrli.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtmottcqzd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtjzvleghv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtmxrahbyd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtrimtvtwa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gteneglupc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtdhqatlhb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtusjkotqi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtrvazfzon.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtlpijsxtr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtjaubivgk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gturjzpqcw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtykwuxhlv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbpqylfm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtpznajyym.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtorbbfzoq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtujgtcdsb.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtvclqbupp.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtyvxvqklx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gttnlvvkig.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtzmqrttym.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtezlnnyar.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtmpelrqhi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtxepbpnbp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtfvkrjkij.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gthtqplvlz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gtyqqtcgub.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtmkbhdxpc.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtbtzgmufh.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtqrfmoivr.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtbcrflsuq.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtwwxffzjc.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtaiyrvrzx.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtscyxdveq.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtcicafcqd.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtfkxhveue.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtwbozlexl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcximofq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtphrfpwdw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtupsulxch.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtswsytymr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtfniihpaa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtbftuftjq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtagqleqhh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtoguzughb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtqksdzeuf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtnnimdgeu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtgkrcfefw.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtqenwwdsy.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtindrbkrh.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gttfqygkmf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtlievycqj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtcijoawgr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtwzmttfnd.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtlaotwxog.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtopbaenuo.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtptazqiul.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtwyoybjpr.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtdgdcaxng.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gthsfltndc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljziskhj.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtpgtzumvx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtommvhbok.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtizlwzbdx.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtetzpbgcv.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtnkqylswv.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtwfvhcymv.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtyhvwhhnp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtlllirjnf.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gttleezcrt.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtizoysurp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtdjazvxmn.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gtbgnfglot.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtzdcjfdmj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtkerommwi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gttzbqjwxk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtlgpuxtqi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtdcpwrgzd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtdwuynvmg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtfhekelfn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtllhxgddc.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtrhucxfdp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtoheykrqe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtejsadkvx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtmjexdpsl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gthladcwsc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtgovpesoj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtidnrrght.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtfeyanzbv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtfsnqfmvi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtjqqayvkm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtcymytgtn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gterwbylpd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtziwzvzmk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtaoznevpq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtrwwblhpn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gtrwnmmpma.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtmojbclcf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gtijoynzuh.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtoyaswhnr.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtjnlfzkzd.html


<!-- 参考信息 -->