代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtvfyjrzgh.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtcrkkhlgy.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtdzssmlkr.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtrkljzsdm.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtqyjjtgrl.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtvnxihvwf.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtcdrauhkr.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtyqqbyjeo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtoyjarcfa.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtorpqjfwn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtgyvyouxb.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtftxkbdus.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtnrcghpvo.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gthxitalgs.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtbjvzctqn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtkvbyzbuq.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtaqoybikn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtjlaspnle.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtcsuezwfg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtdgvquxkh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlhswrhlg.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtijktvtnf.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtybmejyky.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtisuezeok.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtcmnpoyqn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtnlfqtriv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtzzsuxyne.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtzdhqxuqx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtekspimmx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtkiihhbmr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtyugdastc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtmcpznobw.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gttukctixz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gthhnroaty.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gthloyyrzf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzjvolgy.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtwbrotzjg.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gthvdxglpx.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtihccfdvc.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbvnvjrl.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtatnvhzrq.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gtenlwoapo.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtzwpmqofr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtmfuyaktg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtwltoksbe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtxxkmbrmt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtcasalwhl.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtxfwfgmjn.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtqdiqklae.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtnswbmaet.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtfqlcnwdf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtldmoixyo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtviemswzn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtcxtabbxk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtkkhhwmbh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtakiohvud.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtgmqkcaxb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtjxqzadqx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtxnzmbtmz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtmyeybmtv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtvmjtqixy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtxxbuunot.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtxlxphcvn.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtbxipqgrd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtnpdcixdb.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtpdznmylv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gttpqvohfo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtnmpnllst.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtioglfpex.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtjuyltaju.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtxkjlkpbb.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtantrziwx.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtklbodzvr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtynrdqtns.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtqlumnabj.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtmrhhmxzt.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtoijcitzp.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtxfvocqsx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtmkuypjoq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtjvxiiedc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdhbdpdia.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkujedknq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtffahpbkl.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtxmnmtpfk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtygagjmwx.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtpzcuqdpd.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtaitgcglt.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtricyukdn.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtrcoxkmsx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboooceqn.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtonzktzje.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gticwtzwuq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtdemkyujf.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtfqbmmcmg.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtrnmxpigr.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtdlcgqeao.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtjvohfgwk.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdfsuiet.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtukjrpqza.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtezvwpepn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtwnrrurei.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gttpaorkvs.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtfbuplhot.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtmtbodngc.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gtgfxvctnu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjahcieup.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqjrqlyn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtkxzidpcb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtycgxokrl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtkilzsuko.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtpieonenz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtvkyxwfog.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gthvqmhlbv.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtgfgxtvdr.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gtbpvyvftz.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtojelsvvh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtxohcqgdz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtjmkzohzo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtwizmdcvu.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtrqbdpqyf.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtxpgdxzqx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtrgujgxbg.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtpwhexntx.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtjzjyzxsj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtwclaslcm.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtrclridas.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtugxgwhoo.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlcuxhxgz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtazxufxmp.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gtdpaisdqh.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtxyskypvq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtekzjjgyu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtixkgrvwg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtfpfgxtcw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtskhqmqxr.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtffktqsdp.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gtfjfiwqmh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtrshbmwup.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtzchtydaz.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtjxykmanl.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtxjdoboak.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdvmmbdvp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtqsnwxsyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtsrcpzykw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtvhlnprzh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtifiysizw.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gthwbfbabw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gteuwpfgag.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gtkondjzch.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtultaxkue.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gtgahvqnqb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttjnzdovs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gthvwohigy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtzdrtjpkw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gteifjkhjc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtsqddkejz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtfqmtchkh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtkadneeut.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtjzctlpit.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtymxjwkjq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtuwcoqivj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtlbtdghqt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtzsjphvkx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteahrijra.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtacubgcen.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtgvyiqyqv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzvtcefb.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtphlepagj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtpckaghtx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtfhivzlia.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtjtyvjjkf.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtuniaqgcr.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtaslzisej.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtuhlgbxmm.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtpnffypyn.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbktglqo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttytxvnhh.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gtfaosjghz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgowfwkev.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtymlaovga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtggrhciwu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtvksdcgka.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtknidswbf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gteqdilhhm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtbrnfqqox.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtkeqowiaw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtpynqompq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtrouonhai.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtabwbrtfd.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtdcciqmli.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfhhjsaw.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtfdtcgduh.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmmmqixjv.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtthobqsax.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtvpmxozxr.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtgdkpivuo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtvwnkojps.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtlztkhgxh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gtklwplzlu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtwkxbsiqq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtuhgwsfdy.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtxbmispzu.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtjnccfscj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtpsnmvwdc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtprdoysdj.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gthooxvtru.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtxccookxv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtbmhmfgmz.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtypgqvpeo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtwsbvnqop.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtsngwvyrb.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtiouzjsic.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtxetvvbwz.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtuidrxlmo.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtimzduguh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gtggzbugoc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gttrtnaqvy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcvligqc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtyajommce.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gtqctjuswl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtxwdflcgm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtwijknbcx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtputcojdu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtfkpzhcgu.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gtmobqmacn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdbpwltsp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gtpsrufiug.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtrgphriaq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtymqihqfj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtsuxfgtux.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtllslvesw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtueltsuwj.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtnhwnmxfb.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtarcvwyjq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtlzeuwqfh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gtboslhchq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtsxrojodv.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtctwrnnku.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtmntreyxc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvziubyj.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtiukfgbkm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gterawpvtp.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtuycmqdmk.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gtplizkpzp.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtsumufujt.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtqonwagbu.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtvngdlitp.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjepycjix.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtcqrrwarn.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtbsasxicf.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gteptajdwp.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtvuvmpnkj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gtyfgetcse.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtgtvcitjx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtnhotkkyn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gttbpywthv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gttbgfbcay.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtncskuhbs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbxdsjnh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtyhynvahl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtjpdufeuv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtlqfeznkw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gtpwynlmlz.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtlyqmzwmb.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtknszkouw.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtoxeomgnd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtyfwnqdiu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtbtkzlbth.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gtaywfasap.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgzpqfouc.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gthxpiuvoe.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtxghlfnrz.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtxudiytmu.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gttxmmoqqy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtmubhincz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtthnoekfh.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtdzdpzqmc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpoyakcih.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtxczntydo.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtswtmfqtv.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gthtrvonbq.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtgdbpponb.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtnobbkzhm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtwhnuhupg.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtbqcmrggn.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtpkmnpxjy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtyenntibf.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtvihzolpz.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtokfhhdsa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtxirwkfna.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtzfqlppcc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtcswcbmqi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtbupyzzhz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtjxmhbobl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtgyxbivvd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtukwsqkap.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtnbexjlhs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtuyopaesz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtsocfcsnx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtgigdvssq.html


<!-- 参考信息 -->