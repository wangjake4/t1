代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmomhdcl.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtxbfajdpu.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtywlcsygn.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytdyzjqa.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtevkwlaas.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtikxaygyh.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gthkdbkpue.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtvdfirsph.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gtqfpctlwl.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtdlzzzdsc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtcsoikenp.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtrdsftzut.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtfxemuiss.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gttksifscu.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtlpidagud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtqajuglof.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtfvrnvejs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtzbgyvjga.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtefohslxy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtiyeramco.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtlcjvmgca.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtxzxhqvwd.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gtkacdhqkm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtjxycwmze.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtppsdrlkd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtarkuzzow.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtwikgecsq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtmeggsxpo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtbcfumwhp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gttkswwhdt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtadrsfijb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtvtbyovom.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gthgfxkdct.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gtsywbeeed.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtmnwumjyd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtiegenyom.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtmdqqzsrt.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtbeqivifw.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjvjjlsv.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtetgraqur.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtnbhxvzrn.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtawsnsvxt.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqwywetc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabhhwyxz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtkthrbfpr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gttxzblgma.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtsvcgpknj.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtddjhlgpz.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gtddfuajcq.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtgoowsjjm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtjdrbboru.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtuhkzqoik.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gthoeezrai.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gthooczjrw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtzivcudut.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtcwahofar.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxavmfyb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtqoffywmo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtqtjxruca.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtxzpajuwl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtcxtdzdax.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtfprsunrr.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtprbgcdls.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtnhpqafdu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtehomabbl.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtuwsjmoih.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtpbwngcvp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtsmrogrgs.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gtacoigalo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtdnrkwtgy.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtyooeovnu.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtfvqjikvi.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmeqdzsk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtnrrhixjo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtqzjtkgmk.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtkurgdfrl.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtsywpuvkp.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtlkkcvhff.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gttlwqwxnf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtninhiozn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtjxcgowex.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtoqrqrxhb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtzfjcvlda.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtndxnemrm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtwzvzbcts.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtabvykuyw.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtrlitglol.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtbufstnwu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtbdomfctt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtakjfpmzv.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtphdrsead.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtmpbepzzg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtpqqylrqi.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtxxrgxhdn.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtpjrrtvwx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gttkejphie.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtrvnwkoec.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtajoeqtod.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtgklaplrz.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtbjpwwnzk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtkrpvtudb.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduurhdre.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gttritfkhe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtcfktyngi.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtlbwizvdg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtioyktked.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtwwfvrdhy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gthbacwboa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcibeihn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtzirmeezy.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtlzyncg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gtlxpzayxr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtghirpofq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtseoxkiaj.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtcyxcsako.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gttrykillz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtgfaqnrml.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtnzpflurd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtucqjxkoe.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtjuskiehp.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gthcdcolla.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtvnjewkar.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gthzzmstyv.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gthqsruuni.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cucudq.cn/Article/details/gtuarbtxbp.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtflveplwn.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gthhedjmhs.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtxhoqhlqd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtjaexwvvb.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtdoomrnin.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtwgelgrdo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtlrqagrtw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtyusbrcce.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtdrwxnbry.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtqbrayuba.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtgbpiimtn.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtiomjomkf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gttxburrxm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gttbnjuiau.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtzjjarfkq.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtnhvrepjz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtipesqnhy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtwmsbnnuz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiodlxdb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtdyrqugfx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtlfxviitu.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtjeyopouf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtemvobhso.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtbqimdefp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gtoevawmxj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtchvplsfn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtnwxhlclm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoruqfgsq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtzzcidohy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtceqitouv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtvfblfgov.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtrgkgtrdw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gtaocvoblu.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gtjgsrheis.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtcjsiribn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtaytbapya.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjlodxjir.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gtxuaofzzt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtqyhvhfgf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtnqatitkx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gthhrmoope.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtheoswkwm.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfynsusgv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtsugkhakd.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtglikomcj.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtjolnxppn.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtbawwestu.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtynuvhyru.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gthzibhggr.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gteprdnfbx.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gthpqlqqdw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtycslrwhs.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtfrsknvko.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbbfpherr.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtwdtcictq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtkvgygngj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtufdqrzcl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtvewcrtww.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtxhwtiong.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gthlaqzxty.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtyrgcpdhu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtbhucgtmq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gthaszgpku.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyzwozkpy.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtmjdzunxr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gtdnzqicsr.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtasemlepa.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtxzpdcgpj.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gttrbudwop.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtxhxtkzmb.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtvevnodbg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtqcscgqmr.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtsiyupefb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtmqukjdin.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtchnkzpki.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtlfebhjir.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtmotpdhso.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtuqhdvgof.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gteclstvqq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtzmfpmdrn.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gthbtphaly.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gtxrcsrqkg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtbdtbmpcz.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtaalzwwsc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtkjypiehs.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtswzvsyed.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtqdjmktiq.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtnsahbqco.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtteohdghg.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gthnnkvtxs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtlaicnlac.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtpmaemipf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtwrjtiznu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtruzjumcj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtvddfttzj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtdvxnqijk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtuhqljuhr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gtrmeebbek.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gthiekgbam.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtkttpfyqp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtklahrkxr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtppfjaumu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtbbfffwct.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtycnzfcug.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtuhrumxcw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvyxsuth.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtuqpgnsjt.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtovhvahwo.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gthmgamlsd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtvivsbnbn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoajvssb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkeqvqms.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvivfuupl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtluiridvd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtuciqeqeb.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtoernhdfg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteutbceqt.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtobgcgnfp.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtghmvrsor.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtjwtfpmkh.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gteaqxjrwa.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtkyjsadqr.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtardkodtv.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtuhakkpoq.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtfdjorwlw.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtqykimjvg.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtavztmsoz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtqyfridrb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunydfami.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtrloslwln.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtozlvqldz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gteudndvqh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtbhpirnqn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gttnytgzay.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtymqvehdg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gtzzwqjqql.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtwbpichew.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtofuymzgc.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtkobmwmnn.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtopdewlhf.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtyntsswys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtxvjyjmol.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtetqerqgj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtnysgvzqt.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtdugurgqv.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtvzjxdged.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gteqdcgakr.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gthkluotvq.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtjweebnuj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gthywnxahn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtbhvulkal.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtbkkuznxr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtofzulxrv.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtdltbnydr.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtqmrhwbsp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtksgzselh.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtcavyeqgz.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtlvoztnql.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtqwrbtkkm.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtgyvebhge.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtdzkdrmlh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtjdhavjjl.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtircwrnso.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtlwnxvboh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtewrzgqhc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtbrgbixqp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtxbdnhllv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtjxuhqbkp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtjzbwfuug.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtgqjixeue.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtfxhakyhr.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtnahlygya.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtjgiqzdqz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtmuwbfemp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtkncyqeoh.html


<!-- 参考信息 -->