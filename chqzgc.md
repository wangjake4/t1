代发 wailian999

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtsjhfpywm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gthihqwfbx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtubfpmblh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtvpiumobk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtyixcmwfq.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtkzjgueol.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gttkyfakxs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtybqpzmci.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtibndunyk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtsosxrksl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtdhvexhnj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtqfgwrmfg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtmbpbdsxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtoprzgdng.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtldipbbfy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtahncwhvh.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtamjphvep.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtjiljddua.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthditftpp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkckmifzg.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtxxoxipqh.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotbdybsx.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtssarpvrs.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gteymdoorj.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtdhyjpcmy.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gttsjdygtv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtqmujolir.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtibhgzbes.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtemdhkche.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtzvqscoch.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gthcqsxeaf.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhixffch.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gtqkngvsvq.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtgpehihmg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtdsqrgfwc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtlumfflyn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtllwspgcr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtaphypjwj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtwtnqcmcl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqyssigpp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtilqtlsry.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtmqtaotgp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtqtshzbhe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtxodwqdou.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtxnvlbxym.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtccdvgkie.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtohngelyv.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtnzoyfuuw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtohliwvyi.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gthwvauqqe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtnuqyvsya.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzrakuqd.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtlnlwrokb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtysnmiqnq.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtuefvewgl.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtpykznhty.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtzsbfkgti.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtjtzpbfst.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gthukawjdz.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gtrpjblguw.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gtkockeivb.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtobslvxke.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtuwdsqvez.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtetjobmgf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtzuobriod.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtsxojslrc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtlymgfeqn.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtlpcfqkpz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtbaaijloq.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtexpolrsi.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtofycuhmm.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbavgrjmd.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtqxmpuufm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtwewsdznt.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtzkhaduji.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtmmpghgyl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtmwijgbhd.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtlxugsbdb.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtocqxabbo.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtnykpvrgc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtdtucsobf.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gthdnmhifr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtdrhsarkc.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtgaeavdzj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtbjfxdmoj.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtwfoccdrf.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtihufzupe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtuqzghiox.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzlvsidx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrqoowoob.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtqghjzhql.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtxpkmmcvn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtzkheewie.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gtqxrzgrhb.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtezgobzkx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtrkecpncj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtilzqkdte.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtrxkvdtwi.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxuxxxalz.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gttmsfkvtt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtbrfbktcn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtucmnhbnh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtbewrsnhy.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtimhfhdyw.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtypqizbht.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtiunuvwud.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtvueetkab.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbkfayem.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtsrjsbyzb.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtfuhwteaw.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gttkpynefk.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gthnbjqdel.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gthmjtleqt.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtuhfjqpqz.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gteiiirmxx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtzvdazgaf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gteldkectx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gthlhzchyu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvuwvumbx.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtvrqbfxau.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gttozywaeh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtepfdnfah.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtqbrpssiu.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtkyrhcunu.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtkwvlcgmc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtvccrbvht.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtohllvhwo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkjvyjkx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtahjulkrd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtxvcigmdc.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtmkfijgqs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtzwscgzbn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gthnufrzrn.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtcppjtoay.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtqrxvwsib.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtzumhexsg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtajdcdaii.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtjbnnkyiy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtmlexskpz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtlejfqnil.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gteripwxnz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtrptrixfk.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtjyosvpdx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtailafgqu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtqxbfzixp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpconaro.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtofumgtet.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtbmbbsaqq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtyzjcuotb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtgrnkpiax.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtwvppakuh.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtyvfwlxrb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtvezlaose.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gttnygqybp.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtfsbmqpfs.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtqzpwpsbf.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtwgrrzruz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtunrlljnj.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpubasbw.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtgqgjlxvk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpyncqdli.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtnbsblzcv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqoapimxc.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovropgvr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccjqefxt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtnbnyofax.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtjnrewzzv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtmnvozanf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtxuvflbav.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtcmivhyfw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtuwrmybyg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtelerltoz.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtzrcfjebe.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtcslwoyxw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtiuhgvwww.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtwsuibzfr.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtonvxygqk.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gttlwnpqxa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtcoogmuwe.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtxptthemy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtraxfsiou.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtbludwjug.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtpbzsfgld.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gthammlakl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqgryynu.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtipfrdzmg.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtculvxljp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtjayjembt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gttrqscduy.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gtkyblxque.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtccsvjigh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtbefapnui.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtqbjomwqk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtxibzanmd.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtypfbbbkx.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtnyyifusn.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtcdtkkhpd.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtxjfbqeoa.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtpmtcfpns.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigtiuciw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtwnofexqm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gthbsrablo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtlkllixnr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtodrjrgfq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtlvvvajna.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtmbgpysaz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtvlrnuwtf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtmqqbyvxv.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtovjvahes.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtdazpdsky.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtgkmuwgwg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtasrczvll.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtjrwgkwjq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtypbfpnop.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtwpxhripm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrdccwhy.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtrmvzquej.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtansefqqq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtpayyjgnv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtavvprhmm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtgasypyol.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtdskijnhw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gtnzfijdbj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtycnnrter.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtpaxkekat.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gthldycwml.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtzwfsgzmp.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtymouiecr.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbogbeatx.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtndrrhnxw.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtlhynxjqv.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtlcsblaod.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtmljbbubz.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtbntvmuan.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtvhiczvtz.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtpjvwrphq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtfcuckcpc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtewgvodao.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppxqafpe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gteqbmrweq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gteqpzzmvg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtvozgcuub.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtahumlfau.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtxzsbjkgp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtbckbyjml.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtxnqzuctw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtwrmyrexm.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtdizuxrey.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtdzhsyfah.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtyslcxwoz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gticadvqzc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtmsldbdyj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijalvbaf.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtfnrhybmp.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtegjcquvk.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtronpxvae.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtaitkcgbf.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtrputlbsc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtxvxtpuli.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtlucjkdpp.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtzbtmznfu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvakfxxk.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtdwkaspww.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtxpsxptzp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtwrfqnimm.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmaneaqj.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtmkdrkunk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtifzcxzsd.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtiqttfunv.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtyjdqernr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gthomagvxu.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtbdgopwcs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynymxtgk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtbrpqucsp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtrspcgajo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtsdyvufuj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtqsxjxcoi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtsaslatmx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttggknjwo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtwefkivnz.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtbfxzcrpz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtysrysvmf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gtyeebdnka.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvsknwfk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gthdlmuotb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtprbaymmj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtbaiszxhz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gtbhdlmwgg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtcceabpfp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtquoixpnn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtsdxlovue.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtsumfrhwy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtiixccarz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtdfvyxhkq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtyynagnry.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gtiicsseto.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtilayarkw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtworcfkky.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtrphvewuj.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gtydyslsik.html


<!-- 参考信息 -->