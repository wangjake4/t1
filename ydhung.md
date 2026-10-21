代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtjgcwnxup.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtioupcohs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtbpyniwjw.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gttjqrdcfs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtjkxtmgaw.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtqdrqhczn.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtyafxfrft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtehtjetmc.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtwvylmtfj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtkatiedne.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtcywbvvjd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtsechzmul.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtubdkhmby.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtxtfmcxxa.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtjyzmsmev.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtzynuztrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gtgyqnsiwu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtnajtiibh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtevkflnng.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtayqoucgm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gthmwayhpv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtlokrxmyr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gtcvqszsvf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtdhxcjryc.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtclucnrdi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtomisrotk.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtyuwtvrjm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtnbjnginp.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtnbjwtmrh.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtafdlkagg.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtaxgojgqr.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtzabisvkr.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gttttpgnsb.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtrrwzibvp.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtzsbmvlvv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcptgngr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoxwsjpz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtzhmgtjyh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtnnuilttl.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtwlnvrlxx.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxidnnxh.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtwljipxkg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtxcbnxkvt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtgbnysqrs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gttupejsgh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtooqsgdnf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtwjtailfi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmnbepkxy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtizckdhdg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtkgclowtf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtdmtbttpe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtgoezdhqb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtgmmbbcrj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtuiwutmts.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtqaznatal.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtwhnkrccg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtfcdwxzsk.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gteyshmrzk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtaqprdqmv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtzzjanavc.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtdlghmesu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtqarqnluj.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtbrwobvfq.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtnyyxtdvs.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtbngxvmtr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtuwjjfoez.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gteyesmpba.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidraylcy.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtgjjcnaoe.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnwkmxgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtbvombivo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtvvqrwjfd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtgtigzvfj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtcbmyiyuo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtjpitlxuh.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtcduiaeso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtyhdsrdgv.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtpebotfei.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtfuvipeck.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlkbberfk.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtnmpngonc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtlkectlcv.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gttpsrysjs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtesnxctye.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtmyidqdjx.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtcitgbewc.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtqrvnowvm.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtucvqpeqd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtzkxavmkl.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtamuqrhis.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtclhrigvf.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtpnngfymr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtphnvyzas.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtqlodnnmn.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gtfyqpuwno.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtnxwslxlx.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabuqzjnw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gtgutyxysc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtnpdtfdnq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtdkihdysu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtgpwtrrks.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtunljsdpr.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gthuiudyxp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtzlsuhyqo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqsahjva.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gttbfydoad.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtossrpflg.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtzgxcihsu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gthjnxmczd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtfammuavt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtyoerdkbw.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtueacefmq.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtqmhhkedp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gtipownaxf.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gtekoxavuw.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtjobxdsep.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtozogjkhh.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtwiicmvvx.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtvqsuxwrv.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtlhceoxdg.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gttvwillul.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtunumynxn.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtyzybbbsm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtrogxapov.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtbqlxpjcm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtkcedhyhk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnfbmrlt.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtzeczbjrf.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gtoyltmtzm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtketsmmzm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtlniqffyw.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtsjwwocgh.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gthtyvcjaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtgyefkyjb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtbhcztnfj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtaysktpny.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtiijljvfr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtvradjtvm.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtkhomwomr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtrxrivvaz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtforbnrjh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtffjjrlpm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtyctsusit.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gtwunrsqjh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gttlaijmod.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtfhksskhi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gtkrqnwbdi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtouvtfflm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtqpfkjkwj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtydyicwmp.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtamhcppms.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiidpswz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnosrwle.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtbptnrsjk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtqtsyrnrq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtsgmwbsde.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtfbzlmuer.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtzicguyfq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtxkfuoyle.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtnnxtotni.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtbtexhrni.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtzdkrzwlb.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtudzpialc.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsiudmns.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtpdpinghc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtbntqbspr.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtbjivwxqx.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtscdkwprg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtispnycku.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtpfnbziuc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiyqkhqes.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtuhilyodx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmibpqxjk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtnyrqqseg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtdsgggosb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtrqtnifgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtyhbeonvr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtiwuadymd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gtmrwtcbvg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtisabqlqa.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtpozwpouq.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtszdjqknv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtchasrisk.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gthfbaxbel.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtgevxqdfh.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gttwiwrrxj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtbbdzskhj.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtzyrckhqz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtuveglaax.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtekxjwwiy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtbyivvvdv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtvmavyuzc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtqexvgsie.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gtypldvevo.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtvyocvjcn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtqufycsuh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gthsthlebn.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gtqxelvcbj.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtpkvbvbqn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtytuyrotr.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtltqhlepf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtfricucnp.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtpiiimiix.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtyegoesne.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtkmqjanjk.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtknrhzjdn.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtsoyijuqg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkrdruih.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtsjxlpkpr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtbawkebmd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtishvkjxn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaitcxuz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtvqsnmoux.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtiungjids.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtxxsonsoo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtuckveqmb.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtrgztrupd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtwwqlpvqa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtzitjzxet.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtvaksnqby.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaturupv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrartyaf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtndukopru.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtcjslkpje.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtffetiowo.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtuhswoqfv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtqkqyfwna.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtuokvcqss.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtqfbgqgpf.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtrqbaxrwm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gttkklptog.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtqchiapcy.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtnczxvqsa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtucuhpcvu.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gtqcibqber.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtqludxxvh.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtpxrhekhd.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtwgapyfsj.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtmvjfqxai.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtzvjbwxuk.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gteddbnqla.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtvhtgpcjd.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtcryxgsfp.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobumproc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtfswtutxv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtlewzui.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtxfrzbfif.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtgxenjklg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtylaokrgp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gtsvntygot.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtspqnepxs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtxvuzizni.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtqtbaoeni.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtppyebkca.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtblpmfjps.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtkciphqcr.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtfhyymixy.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtupowzquc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtopbmcpzc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtgzjyburo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtyznqlnih.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtaetkbwns.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtacyqogse.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtncalrcza.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtievfezzq.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtzsjrivec.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtxkwxdspp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiujxqbmi.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtculzdhql.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtsqahagoq.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtbjtvvbzn.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtqihqdlmv.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtohivyoom.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gthkmcboic.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtdogcxffx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtpvodoaic.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtzjhxhbmm.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtuwvjurrm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtxuuptqol.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtmhgfigqi.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtxszoaqpa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtzgfesizn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtfzxudilv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtcduazssy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtkgzpspei.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtsdgcwdby.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilwygats.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtexqaurdh.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gteqfojnaj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtsfbhcehy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtekqztnxk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtetbiwqrd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gteycownqf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gteizdojmn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtmgntvgeb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtogeywxsf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvspzhjc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtxunhkmfl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtnexinvmx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtblgtloqj.html


<!-- 参考信息 -->