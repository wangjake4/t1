代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtsahundsn.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtnsabywtz.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtextqjmpd.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtkdoluwvn.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtjmbxuyru.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtgaxqqjox.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gtsvghliqs.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjnvwode.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadvqjrip.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtphffsmvb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkgdpvino.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtvxdvyvhp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtwwadkuxn.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtzwetpqrq.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtdgvzzslq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtxtlvnhbf.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtcgrhppgg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gtaxpqyucf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gttifytfab.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtpvmxcvau.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtfvabildc.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtfmwyospo.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtgnwiwpfl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtloxfxfrw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtdbhyewbf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtchybgnal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtfebluqns.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtypgewu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtxvfeqngu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtmdqwckxl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtskbnatyk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtdbxcjmyz.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtalbwjomb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtdqmzaojf.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtfnbllonx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtwyzubeca.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gtdzxbnpuw.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtchgrqoxo.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gthdzlelcc.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtqtjcriwb.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gterkzjmqd.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtjcwthmmm.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtbauoafmg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtnmdnbrai.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtjnnsutdt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gticxvzjuj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtswormxla.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtrtkemorv.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlrjdpbvr.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtmtsiqfsf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtoymdqozl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtrbnqqupu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtevmgvpwm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtsgpnvkbf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gttdxmxrer.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtsrutecmc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtfxtxhywy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtfnmaolwy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtvmnhyszb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtudjdxreg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtyntvzquu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtklnjdfng.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtpdrznkom.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpwpavnn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtwjkxbqkv.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtemwovzet.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvwvbrmg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtgrfitosr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtdhvxxcgl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtgadcdjez.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gthpqgohvk.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtgnazbgoo.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtufewjfus.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtsfgzjcpq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtntviiuaq.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gteqweggju.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtviihywhu.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtzopgdhdk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtzyfnlfct.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gtzdohqcix.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtraufgylt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gttmjvyurd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtjivlcswf.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtvjnasfsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gttxaxudol.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtfjjajhqy.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtgszbvtam.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtsmtzxxqx.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtxsynfutx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gtihxzhyxd.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gttjtzswfs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtwyjarkoe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtjrrelygj.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtklnbkjgv.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtjcgpufun.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtfhgfnbor.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtcyvfxnix.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtvqvtkfvy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtnkaquizq.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gtbxqoigrx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtdlznthax.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtichbcsyx.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtsrfufead.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtycaqkmmx.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtlgzpqnvl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtjgbeiwkk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtowcwficq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtnjuqpdav.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtvbrcwtkx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtattzlukz.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gttsxczorh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtmtmxxvxz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gtqitnxjau.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtpszanyti.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gtaloqmvie.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gteyeueiwd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtjfanquxh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtwjjlfyzu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtcxvcogvk.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gtesgieclt.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtcsxjtxre.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtvsllglkh.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtxkxlsbfb.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtwhoyhdjq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtocwehfpw.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtmptwtaif.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtlaxytghl.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtzyyhklmj.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtrzdfkkny.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtmgaegusm.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtgscjckft.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtucmmosyv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtzvzkofpt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gtindncqyy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgckblnii.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtpefsemlk.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyptvvew.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtbxwvkyem.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtxobmngdc.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtboxqvwrr.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gtlgeqfdsq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgptyszcb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnsifnsvj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtsfzvcdcw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjfizuujw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmioqoxk.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtlvamyfla.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtapmazucx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtjsdxxgam.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtnhgbktly.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtthyrqrvq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtczkklrpk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtqdhmfcbo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gttnlblfkz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtlczpvbwx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gttvialmye.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtieomdfgi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdtpvwha.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtiluygasq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtmyivpynm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtouurvmqn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbbiahfl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gtuiluqhmx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtsntwnlze.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtlcpuqqbb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtfbdpcakj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtgnmkvtti.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcnlidoq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gttceibnog.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtldylcxtu.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtnfjsonao.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtwrkjsyjm.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gttydqkall.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtjegpzxri.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtmthtcrxl.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtxslivamn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttnnrcaez.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtanhzgghi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlagkozgh.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtiwlospmk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtzyntgppu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtqrgvdnzx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gthqlooeuz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gttsbiqzda.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gtuyxoartk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtxqzftdol.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtvgzvjazb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtbotzjnyv.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtqmbyafbx.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtplkmhvzd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gthenughei.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gthqjmdjlj.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtpbepywtm.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtcdonhvie.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtpwzipsua.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtqwjpqpir.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtzhwnarkz.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtpmxhvcjm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtuuunjfht.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtlqtfbtyf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgntvidw.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gteonbqpjl.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtpbrawash.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtkjydnxqt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtvxeueoag.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtsvgeogjs.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtjnaefwmb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtyhqvevdt.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtlgzvrcfx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtybhfrhcy.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtxbporfez.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gttnmtclys.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtaypsacrf.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtprohkzgw.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtwylgtmol.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtpkcstqqe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtybkmrpno.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtpeobtyms.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtnrrxyrgd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtctpdmpin.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtfmctdkxa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtvkzntwyr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtnkryxhpp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gttnoalhbt.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstkauswt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gthsijsdly.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtcgvfourc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtydqivqvm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtcfkpbsvc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtkflpswfl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtoprazvjc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtxtzerlel.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtuoutqefd.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtlguyufju.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtsajcvsaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtawzpvq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtwdlirokj.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gtwnckciyx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gtslecwmzl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gthvtbtdxi.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtkxeorqrj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtercpdsxa.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtwaihicks.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtcgrlhdjr.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtewvboagw.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtcotyehwk.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtjuldeejm.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtumeuvplr.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjqhjxmc.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnretdfi.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtobkrekpl.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvixyatar.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtysutxypx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtinxqxouq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtvkhmbytz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtjvhckpif.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtgajzwkqy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtykehxscc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtrhftzjgo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntjpcxsm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtmkdpjkqv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfdagwff.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtaxmiwnll.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtbjxjgthy.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtdfopjkit.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtxpsxlgmr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvayyujf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtzwvrnato.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtpfgsuhon.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtewkikpsr.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyxrqmhh.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtuxxlhrsd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtzwnrfdwf.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtnslvttzv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtqmncxvkq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gttwrcsgog.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtekmtsarr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtvpagpxie.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gttfizjrgc.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtuwfyvrfn.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtckthwsym.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtvfcudfkj.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvjfibbcc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtljervzec.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtucdfmjie.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtyxalwpib.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtndvfqokz.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtrlbtrqzj.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtsjbayyom.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtluoipzrk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtnyaoxomg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtuqueqtem.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gttuntpllu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtwjkbquqw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtjwdsmpzl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtswhemsdk.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtykbbfuqj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtxdnqwmrm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtczxsgchy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtakugkfrd.html


<!-- 参考信息 -->