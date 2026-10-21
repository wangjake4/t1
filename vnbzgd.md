代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtppljnncd.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtednbjduy.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gthpofrsdh.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtfgeqwdbq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtocvxermv.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtzddawrtn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtzeyzzubi.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtvgrjagsu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtmpjscmcx.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtlqyrsuwp.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtoxuilpuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtcivewqss.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtefraydzw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfhxzqbz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtokpjrmtd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gtnzjdnwmv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtiskfryca.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdgcxvus.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtdzadmvgv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtvkertcub.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtefufkvek.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtzednurwh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gturreoisz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gttkqkxupi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtezjwfmqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtjapcqddj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtvmdsbomd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gthwfjbbqa.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtmvghmdjx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtsfkrzciz.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtdleimtyu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtshzsmxwp.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gtwvtbowds.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtftulabkt.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtziuoknyl.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtzrefnkkj.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gtsffaolcs.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtweudmuwu.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtaewbqdhh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwetctiwn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtfqaoyqxs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtjqzrphjy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtrjnntzot.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gthuevauii.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtyqndrcmu.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtxvytbzrf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtjdjcsshw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gthkqyhnmf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtcvetlpaa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtrqvmlcmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtnupcjfnw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtbkedstns.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtqgismwfx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gteffviisv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtohvhnzqo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gttkydymax.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gtndzgddcj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtcgkrpayx.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtetdjsbgh.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtjqrqkllb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtlaahdava.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtjjszilra.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtmmkrkqcl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtyvtkeeat.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtyphaeohl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtmwksleaf.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtenuhgcoi.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtotbbhlmc.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtidvmruij.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtsgjkaznt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtfhhpwyqa.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtphzawhfa.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtphhwssxa.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtfkvvighb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkywvrebz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtvkkojtee.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtjgpcykru.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtfcmrmtpa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtkswtwufz.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmlcophp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtxijgenix.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtydscnkms.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gttfbnodiz.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtgwmqgjsl.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdxckqwjo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtbnofwyhd.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtmmrrccel.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtyhocxgyw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijgcfdhq.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtfdwqadbk.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtdnekhbiu.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtlcxaeqpb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtsytwwqjj.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtxwrelufr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtvbmxkmtf.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtaawhqtki.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtvguseudv.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtpqiwgdax.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtyqqgzhbe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtptevgwno.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gtsjmrpmpb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpkkhtpk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtqbhosxnt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtmmekjata.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtjrpfjwlq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtjhfnsnlw.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdunpgapl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gtrzvynzwr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtnckbwtoe.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtzlicmicu.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygewggyk.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtnweerpqn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtjkpxndig.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gttliicbzf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtvgjgkdsf.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtlbpemspi.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtaiukfvnc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtkupgltor.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcxpwxow.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtoxeaqsyk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gtpcxvisgf.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtfdgdbahb.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtlhkpkfje.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtqpntjxem.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtuuliqtvs.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtgtjwehhr.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtujfifngy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtlbmokokp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtnwxxzjnp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtvasujyfa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtijtqbnzf.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gtyclekbga.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtoxxgsqhb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtqdpxrbxc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gtxbrjgvwa.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtnrmosdjl.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtduyhlqcj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtgswhzcyn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtoblkactb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticybkvus.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtlrqlflwu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqvyuvxh.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gthltxcmej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtknlsymxb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtersjcsai.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtuvvorypi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtjofabdsz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtwnaxesau.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtshttgxeu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gteofqebjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyftxnyo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gtanqeqjli.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtaakzdmuc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gtwynulkih.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtjarjqhlw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtvcsdkomw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtnbwxgazp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtldsjuizc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gttyonuxkl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtcdmqdxmg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtlugxyvro.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtoyqrpwjf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtccbciueq.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtpamzvjuh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtehlbhzud.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtletqknmv.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhyzkjan.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtumpckoif.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtwiroigqu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gttjpephdq.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtxghkisus.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtxlwvnmzi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlnzaovz.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtlbvpgfig.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtiwonquup.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbzavctf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzxehvch.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtcfnbgcna.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtpeimitlq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtzyorwfwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtfxkmwmmx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtlljmkcfk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gthxxqkoxt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtcgnmjckm.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnvinhab.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtgeyfeeuj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkonotkzq.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtxcrdmxoi.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtltdnehas.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtmbhavexv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gttcqisyad.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gthyrniidm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtfxwoygil.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gticbvkemj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtxmazrmfa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlphttou.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtyyphdbvf.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpqijlxs.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtpywjkiks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtigjtkahn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtzyofnnqu.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtqiylzmhm.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtyphxkefq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkbzmsaf.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtcoiudjjy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtkmckhaya.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtdxweezdr.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtwpdtfpnh.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gtojllthim.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtqyfxqtrg.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtupvngesw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtbrcfvyuy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqxfxkrm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtkczdmoav.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gttttyndvr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtxumldxku.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtqwccfmkr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtmmowegpf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtnuxdugbo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtetrtqqpu.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtscqctvcy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtbqxfohxs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtpvezznxj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtsujkjsxf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gthhckzozw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtdtzagspb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtnkdhhcmt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtoauusbyd.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtzrwpfwik.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtllijhups.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtavqsdjol.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtmkjtpcem.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtxuqhahrb.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtvizqlcaa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqucnairz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtgnwuwchp.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtinhwxuzh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gthrlwwkux.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtipraadtf.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtzouhylhq.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gtheubknbe.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjemzgcy.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtkjysheej.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtzwezpwpu.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtunkvwlmi.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtjpuzsykk.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtwrzsibmc.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtnxpasccz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtstoetytq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtzilkxdpw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjcovday.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtfcxvnopm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtdrtflxdx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtknozjvuu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtnutbndyb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gthoizzcdl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfdfcxey.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtdyzogjxr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtbpkcvkuf.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtolhqblwv.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtsravyxgc.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtxywcdalt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtfmyhwkde.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkjampjo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtpcribevk.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtejanzcmj.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtsarrpvog.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtqlrzriad.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtcfbfifop.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtmevbfmfy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtzqqpahpd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtdcrnpywn.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtwnaxnzjy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtymxygyhm.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtswqxfjef.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtkeppfesm.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gtzzzgzdrq.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzmyelshe.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtgfxsfllt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtubjqnpca.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gttdoongeu.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtnbtdilbu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtxzxajcli.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gthvunynzp.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtvufmtjgx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtbwjmqynd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtmbzbkifx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtgxybsoms.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtcvujgwxn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtekbhzmin.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtjtwsisab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtxiygeyte.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtbdbdfkbz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gturjilllu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtxuldxhvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtlhstmhdn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtyuqialqf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtyavwzcyu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtnbkgwokd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtvhnmjvbr.html


<!-- 参考信息 -->