代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtvlaebptu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtavpshanr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtmuhzkcax.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtyqihobha.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtbiczkdgr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtfzseasci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtmhlkzpbz.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtzcdsflvz.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwgpgtery.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtdubocrlc.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtfuufizam.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtfuzbxnbb.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtnenbqvhr.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrytixwgd.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtprwigskn.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtifgiafos.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtuecumpbl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtsadjfuwc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtkxcdytlm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtyxpjiqua.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtxppneskz.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtocjhhmty.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtdmgsxbyd.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtpvwekhvn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcudigjbq.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtybwnghlb.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtjqonswyk.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtkxhteqgl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtfkparpxp.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneykpimh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtkwugtpfj.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtnkhmdrsm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtzvuuobhn.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtwgaxclud.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvuulgcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gthkagxyge.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtngekwydc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtsiqdasit.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtmscnzpra.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtwwdjzvcc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtnkpnjlim.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtnkrykhpm.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gttzskiixs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtzifcdkib.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtnosktnue.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtclvzevoq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtmwdllfxu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtkxcsuxiy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtzdmreqrs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtqxmhzeel.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtyrzkpyvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gtcquhxusj.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtphfealic.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gttaktrbpm.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gthqvlayct.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gtwzxqhnow.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gtetshfill.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gtygwfssox.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtaosahjhe.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtbemfoton.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtzkuahioe.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtukpepysz.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtceirroxh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtpbrehkxs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtysyogbjr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtoaihoscs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtrhfajwwv.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtoswqwicp.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtfssinzja.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gtbrsmhthj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtmxihlmpn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtdnhgsyql.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtoqlmothj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtvkycqzev.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtdkbcvecc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtukfwgcgz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtanglclpu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtqfydpyzo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gttwkiekri.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtlwcyozbo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtyazexrbc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtvwglxoyg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtmaqtoody.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtfjofbjrf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gtoazrbgbq.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtibcmepid.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtvsrsuwcr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtpcigqzia.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtvgostigg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtpjgoatnv.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtxffizfzl.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtdptfrscy.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtnngzysjr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtbsfkyfnu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtpooqwmue.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtreikegtc.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtimvauvsf.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtomtqckpu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpmupdntm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtybelashj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtphhlvdzm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtvvbpijtg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gtixyhaiab.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtnqconrbx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtrsicxdjb.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtrancndva.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtnxfstsdd.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpigqnmim.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtksxiclft.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtourawots.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtzhhvwpdq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gtraujoffm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtjmmrxyra.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtzsxynpyo.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtmnfmpikj.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gthzukndpb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtuhhmkeby.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtcxhyadiu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtupfakmmv.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtozmnmtvl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtiailjcpf.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtiigoproy.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtcbwfxepq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtbkjahtiy.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtuhltxpmg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gtanupxeug.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtaeoetanh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtehckzavt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gthjtmbahx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtlhfgmtnw.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtkjofeadd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtgzmjmlxc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtufxgfyth.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gttfssawjo.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtogaafyjw.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxubdyrsv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtqjamjfcu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gthcphhnqd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneqjeyah.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtsohluava.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtlrglczqb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtlihxlfue.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gtgtbpcfxl.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtqjubftlx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtwoywqnzt.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtjzfvezlo.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtscmukqlu.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gtmbppssbb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtdjnvunmg.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiktxtdf.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtwpzveexm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtrduhbelw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtieakdwep.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtsvyuvijv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gticxnerwf.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gtvtlfotqh.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtixxudhwv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtdajddxsb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtjwqdvvii.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtvrpkuthw.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtgfatcvme.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtertqyskv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtyjgtvebo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmxbtxju.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtntvrbjau.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gtilpobdmi.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gthenequju.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gttnviebzt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtjvoinsnc.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtbkyscqmk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtaenjmtwj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtjycvszxq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtxlpxoejn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gthupboyto.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtmozzurvu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtxqakcfsf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtkfjydngq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtenbrfjhi.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtzuwnwhzc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtgdyxpxix.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gttfydpcbe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjpvslbmd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtjeaihqne.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtkqqdiwpl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjojzcgm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtwfqtyrwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtjignbxqb.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtlqbeggqf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtvripbyiy.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtlcrvusbr.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtisfnwzee.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtyznltjky.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtoorxgyve.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtsdskthwo.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtqolotxir.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtilfmvodk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjjudpjxh.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtixzpfibv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkrbghfnn.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtkrawdyyl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtltffpbhe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtzferjhoa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtvqdblcmn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtexpwimlj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnlozaoxv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtdixsfpgt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtaqmbmxdb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtpkkxxbit.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gtaxicktiv.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtwmnafbns.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtisjltmcj.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtbllbxzbx.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpiztyqtg.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gttfcvvfqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhmbijfk.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtwxoptywy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtksrkqchu.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtcfijcpow.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtswghrvfv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtljtgqkfm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtvaylastm.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtwtcvvjlz.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtyzlnzwqv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtwuskulef.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtzmymtzvk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtqjagreda.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtsgsqdffl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtfgtaoiny.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcvqcdjw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtpbyfsypq.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtohfggjdq.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtnebfaiut.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gtvxlswprb.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gttxqeppli.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gttdkmsczw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtomvcjnow.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtmcxyklec.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gtfiebpkil.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtybdipolm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtiwklrccn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtmpxbrxju.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtdjumqwcd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtnmohxstz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtaykciupx.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrmyzezh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtsknrrdch.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gteagsewsc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtmwafhkal.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqiysylg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtljdksjwo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtgqwuswmk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtiyqbwohg.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtfzwdhllw.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtmyorhuhw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgxklzyo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtmhcvpzxo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbskgwnth.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtxbipdsmi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtdjgtmrwr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtkatyksdd.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtjufevkhk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtfymwpwot.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gticmvcjgz.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gthsfjmfcm.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtmcifjifg.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtxkrfrptb.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtothdyjth.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtimhgcirx.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtejhtzcmt.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtksuvwcgo.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtngrfghxb.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtfbajveiz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtxiclzhed.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtqdcmfnei.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtbeqbqboz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtplbtdnrj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtuxtgvvye.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtkdtemwwk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtjulmbwal.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtcgsjxuoq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtakwyjjey.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtqymyxuzn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gterilrogl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckaveruh.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtyzqtphxt.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtivrkbmfm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtwzcmyymk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtwfcdcavd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtihrcsvxh.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtguubjomn.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtzxpqbmmc.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtftgssneh.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtpbryundv.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtzpujnmgu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gttttlhsyy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtkxptnsce.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtdmzuafuj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtpafaykts.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtqkvnkznw.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtrpdcapkt.html


<!-- 参考信息 -->