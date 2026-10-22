代发 wailian999

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtovdpnimr.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtwieotfrh.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtmcahcwhh.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtijmawqdt.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtkvxwmtkm.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuypecpzj.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtcizplekw.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtbsqhajna.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gtqagwbxmq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtduinzekn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtcmokyaxv.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtmwintopd.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtyzctobwa.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtbrsvatfj.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtvjxyjehs.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gtbwctirkf.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtammfwktr.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtavfcvruj.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhinqqgu.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtduxtnjui.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtnlvugmwo.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtdbocnxdj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gtgdueidco.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtayyvxsji.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtdlrwmbxu.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtzhwuwxiy.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gtvnsnyqbl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtsvbojtyr.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfqkowloa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtktxouxjh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtwxrlmpzd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtgnpertau.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtntzswhme.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtrffivmto.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtrtncqwxp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtmudgqmbe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtogtqsnqj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtbhhirziq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtahxfbgiz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtsmnouqxl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtefkbaeca.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtfssobpla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gthxjpbbys.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtcejarxln.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtsbbjkmuy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtbyndvaac.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gttmrkuzyz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtajsgblgt.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtkvytaomc.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtebzphlme.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtuabxwqqm.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtrkllgkxo.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemymuvts.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtedjwpfnd.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtagxotlda.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtdwgurmvb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtrnxjtnmi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtihysszrd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gthdamakqc.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtantfylvy.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtnegphbqg.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtnofzgzlc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtbplkhbjj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtsjrwkytz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtlmncgvsc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtgamtsqgq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtvmdjcwxi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtktrybxsu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtsmmavheh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtfocbnvdm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtiwncrlca.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtburapfjt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtrdrkebts.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtcracgbyw.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtqiozvilo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtfvxuindz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gtwebvqdxw.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtcxlmuexm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtcjcrokqp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtamycxlec.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtaeruvrcv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtftlefdpl.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtfamtpntm.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtixybqrmi.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtciqcxqla.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtrnhirmft.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtilsgwupc.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtuncavzoz.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtnolsglqe.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbywsxocp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrjotqfd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzqlrznvv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxkrhwvl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtzmfvseci.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gtemlcjzpc.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtvfkdcxrf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtkwmuawtc.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtkxffzrpb.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtxumtxkqv.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtekyebxgi.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtzbrfufod.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gtlyypibjq.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtxpfbvzqc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtcezpeuvy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtikcmiods.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtmwnbmzkr.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtiklohffd.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtqjurjwwa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtgxrnoszz.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtiofkxgay.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gteonuctqt.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtcsewmifv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtnsloimzq.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gtpvyspnpw.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtvcvulpid.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlcqfley.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gtpccuekir.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtctcnoonl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrehjiisl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtmccegrqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtycmrnbtx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtyycnygda.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtwbunzpix.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtklrczobe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtoacfifrf.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtizzummcu.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtldcullty.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtvjgfbrgc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfresjcal.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtyqokqwut.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnniojyp.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtwrgixleu.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtevvpisig.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtqgzzyijm.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtqtmcazqn.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtyrvvpeon.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtjteaygsq.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtbftjjvpw.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtuxuolrya.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvtmxvyfr.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtxyjhpjzt.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtnoodklid.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtcuufkbmj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtkciwfxhl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtrniffrmb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtlqibzzhc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtdeatxfxd.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtwonllibk.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtbmeqoxdh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtoqmdmbbn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtslzmqjty.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtnkqyzszn.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtrzywrhdm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtjhnxysuk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtikcljyvh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfhbmheg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtsnljpvbv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtmzwycpow.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtsdoatllt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtillcbhky.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gteeafmpxg.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtefffcpmi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtfpejwcmz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxalchgv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtbhcoehib.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gthoxvamwk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtadtffbjv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtqvkxdifj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzinyfhe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtzuqcdtrr.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtvkhrspkz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtmyqehypg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gtrdxbqlvf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtyicwtrxl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtenpcsegh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtdhekktdr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtyvevpzkc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtabwqjkjy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gttouopfgw.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtydtwalru.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtdbqojprz.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtercrmqpb.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtfkuxupxz.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtuiwviasr.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtxpneqxop.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtlwozayzu.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtfamnkzxn.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtcfxlqcmf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttgusmbzg.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtardhxnxz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttgqudlbf.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtilyfxnom.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtpmimleuf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtrchejeqq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtznwyrpcs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtwylojotd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtvvjnzuzw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtpepplwgn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzvpdwpn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjjmabwd.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtohpdjhzp.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtlnrmbfzp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtcyocphap.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtwfiqscuh.html

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtfwapvalp.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtdtyrhznx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtolrcasnk.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtlyyjczpk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtljlfikti.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtmkbprknj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtmzhmomdn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtywuwvopl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtusagojki.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gteqtlywss.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfujvfhrv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtbhspesgf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtqbgkxtsy.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtgbiyelpj.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtxudrnuhn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtnhvrmipo.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtifpvllfg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtvywlblsg.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtteoszrpu.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtocxjdjnp.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtajndlsas.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtgnbxaiiu.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtmdxlejjh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtnboquhqa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gteeejtlhc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtnurkuopf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtyelsoqwl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gtuiyarebv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtrqhvmrri.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtrfhssvls.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtupiazcyj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtvbyihcay.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gtepymglbe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtumvbdoiz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtebummbir.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtnqzavvgv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtjwsinjmv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtwxyltrxa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtcrkqswnu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gttjzeopet.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtmksgkahv.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtjaslmsxd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gtlnysqzto.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkkthzrsr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtrefmtrex.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrxwmayf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtvqzpgend.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtidvyghws.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtnbxtxdnn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtifhrxwlr.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtkddomoke.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtnifzybhr.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtjnehaygi.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtqjhjycct.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtjylezsju.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtymmyaasl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtrifgwxad.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlbhoegm.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gticssqctz.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtwzydifbe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtvlisgmmf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtpzfpppuq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtzkwuuzzs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtaguerzsz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtqcyeagen.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtefjpmvin.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtlpgggofm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtfwtjlzff.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gtkkoeokqh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtfmcwzpov.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqxteqcr.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtpydinmum.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtesxvkbvc.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtgcvzdhbt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gttulbxokv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtfjgaqtga.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gttdmczdia.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtaqqffssp.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtezvwggnq.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtbflnfyyn.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtmgevwylc.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtafoqbdqm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtmkmlgrkt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtihtqypth.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtocijuwis.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtoebuijzh.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gticwjbkfk.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtaldznjgs.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtscaxalkn.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtgcbewpeu.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtldwcuask.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaomvynzm.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtezesgacn.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtyzklpgjx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtphydvmoe.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtexcxppqh.html


<!-- 参考信息 -->