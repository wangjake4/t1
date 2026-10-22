代发 wailian999

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtjzqviwsc.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtcgqwigkq.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtgrbypfhq.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtfmqswrfb.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtqepdmjur.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gttrdvlosw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtguktucpj.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtwtrewmte.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtqenhitxq.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtzqwoevfo.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gtbfgmstet.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtrvutalhd.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtbsbqblym.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gtmizjuptv.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtkhgwjiun.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gtlcynlisj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtpmojysjb.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtvnhqfoqy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtikvaypdl.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gtezepwflp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtuwntothq.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtabawxetm.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtpavcssls.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtfvwcuxbw.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgctispgt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gteganqsji.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtkyxbrkol.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gtictcodbw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtsdsptbzn.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtgrrygcht.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtrfnvlmjw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtmkndjgyp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtgendzhth.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtgymeflou.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtzfuigjkv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtviwpeqql.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gtpwrruyew.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gtccajeqda.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gtqhuczgjm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gthvjlsjwr.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtousgtuev.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtrrrhvtdh.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtcvhklvxn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gttnnvyxlw.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtamiqjdcc.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtijcsbnob.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtfrjtxhof.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtgygrcwww.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtzjzfxfzv.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamkzkxvj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtvaojvuct.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gthpaogots.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gttlhevvvf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejvtjlkm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtksiltqki.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvrcforq.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtrwmrcetw.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtharzsapz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtslphjscv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtcgscvxsr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gteehxcbho.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtsekhppdx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtlbqilxba.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtlrhyictr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtgktplybd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtgrmzmobf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtqxobhrjw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmayxxnr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gtdvbjsxxl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtkdkvaumr.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtatlplgfp.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtxqalrvlk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtznfjmkzw.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtaqkeghvx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtlwazorch.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtkiklafgr.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gthlkwkvvr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtxztxsjpu.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtqpqmgtmh.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtkmbvirxy.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtluduzitx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtvyiqdhrm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtmhkdffte.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtkayfsiyf.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtxlkpkzbu.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtjirzvqgw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtpufgctgo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtwbyuxfpc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtwezdoeyl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtljrwdzhi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtwddavlxj.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkueqezw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtyjijelnq.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gtrcykddqa.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gthhhjarxe.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtnrtwvohx.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtffcqdeeh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gtrwrtytfh.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtusyaeafm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtviweatve.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtvjtvvnva.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtsclxjgdm.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtwflfyavk.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gttnxdfeyr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtlkbkcvid.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtgpcjdate.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtgqsoqmmy.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtrsibpahw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlqwulxx.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtixqzbcvu.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtibrdinzd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gticaadnba.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtfmnfbcml.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gteqrlgabg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtoyvlitcf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtamlhfkho.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtbjvcrqps.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtucsacstj.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gtymqdjcdc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtylvmyyvo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbnxausi.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtpztafbmh.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtlidonyfa.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtfsbpwlcy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gttvfhpkzu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtxxjlwqvj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtcsuimuja.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtepthgypo.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gtadebqocg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtwiyhukvj.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gtjtenwnvw.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtcroxkkia.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtgnnhqfou.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtvgozzuzh.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtzpusszqv.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtkyuhpuvc.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtronmllwz.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtzzzfhdxq.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtlnnxcawx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtvxnwdzlz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtmtdavpbi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtecowsylx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtzavjopxu.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtxskvwwns.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtvclyibbf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtpyxfwdnw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtdndsxzbv.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtwybkpnmz.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtjtkauxxx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtnmdxfjnj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtxvxymwrk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtncajqcrp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtxbcjstjr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtyhsdfzht.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtakcrimqb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtqopvcknn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtypilpavj.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtepdkzbvf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtympnucji.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtchfahagb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtflkxlqpy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtilefjqdf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gttnpnnovt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gtxhouenuh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtebrdbirr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gticzjplfg.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtcgivpzaf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtqljmosqn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtwnfiukmo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgoxfevec.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtgvlwboun.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtcxdwpviw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtdnfbotho.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtbgxecndg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtpjiwtyzt.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtoihdbmfg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtpstufpqw.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtezmlzgsg.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtfkkhojzn.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtcmfleykh.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtkchfqgmq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtiiizvxmo.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtkowdypps.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtqvnkqznc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxgdebdbz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gtoqvjiphk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqxdzldxf.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtlnnocuss.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtthgxnnfg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtjfqzoicj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtzbgnglel.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtkslvmjgn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtmqlmvsfk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtjjxqthmu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtaytqrqlp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtrmkbrmjy.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtgrcvworv.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtzdgbzhmo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtikrokfpt.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtxbzdkzny.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtidslxsll.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtfgphhsdp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtrpnnchur.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtiztgjvuw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtjpsqsgyj.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtuhmoznhb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtpglbcwhc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkespfvk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtlrlnvqyl.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtozkdbzuf.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gttoedtrko.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjopxmwi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtrshcccnq.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtucsyxgsl.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtonnqmxwz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtklrgjnig.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtpqqaowdo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtmjeirndq.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtgzxfynhg.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtmtcfxhgm.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtdjjhpqwx.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtlrsoxylz.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gttnqysucm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtmkgdtgka.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtisgrjyhk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtwlijxiza.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtxarpycyf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtxdjpohkd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtgnqogtei.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gtynjmwqbg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjlyfzxe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtfhhxorrg.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gtcaypiwtj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtqatobpjo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtvkkapacw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtvdajwzka.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtwiuikvrn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtkjwseicr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtsqorpxtu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttimcqjdn.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtjhckghqb.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtrbvgsdog.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtqacwazgg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtupupborl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyofnglk.html

TS:   s.split(",")
来源：http://dali.gaohongyu789.top/Article/details/gttmgpirpg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtlleypabp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkgrdywl.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtaoneowxo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtjvkghdzg.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtvxtzrhnx.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gtikfyehad.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtreokchmj.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gterukahsy.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtpyvfrvsg.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtidxbscjw.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtiprdlkmr.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtqzofoqsf.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtzdawrxhw.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtapkoazxu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcypkofxo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtzwvccegq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtyvqkbmgk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtjntihpwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtabmvghip.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtuzudocwa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtjkabpgmm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gttwduefwj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtpptavhjc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtemknqqth.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtcqmpdayl.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtxujferit.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gttmqxhetr.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtornmbcgm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtvarvxcto.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtxpegczcx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtqraqtblk.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtcedpdkyc.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtvcbzoidp.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtdhtmxxsx.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtbfietqhg.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtlhowmtej.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtudclczwt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtdsiochbd.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtfwqoyyiv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtixuhlvnn.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtsthksoxt.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtnmwffdhn.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycmxwvxp.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtsczugqzv.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtmprgoxci.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtsvlzirpc.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtrqlnglvt.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtzrkqxzjk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtmnkdnoli.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtbahsebaq.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtpxbydmwi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtomfzjhvb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtwyqozxqx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtksbjgwpp.html


<!-- 参考信息 -->