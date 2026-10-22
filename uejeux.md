代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtkynqnzlf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gthqietqpm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gthuipalwd.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtebexybef.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtuzvkbafv.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtzjknmqmr.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gtluiavirz.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gtzzzstczg.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtohxtzqet.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtoswxokuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtsemyectv.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtxscrwsej.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtyxetjvor.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtllkzccdw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtjisbzjpg.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtngofkbfs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtynxmtyfj.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gticumibqb.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gtcgiqzkku.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmipbkvs.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gttpgsxegs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtfcwwybxt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtukvdftlf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtirppndkq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtcqwehfqd.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtbatdfixq.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtjttuzdxr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtkbgxwpkr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtyhtulhwn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtsdossotn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtdpwokbzy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtrzykwnjp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtyxphzydn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gtyjetvftp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtgfdhfdgf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gttqhnvvcz.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtiddctzss.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyofvryps.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gtqafsatdy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gttqunspwb.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtqbyomkec.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtpuvvddbb.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtmsqctwav.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtxdnjiokw.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gtrkpocuxe.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gtfppemqii.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtfygyjooj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtnnegnogx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtcztlsxys.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtqdcrxefi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gthtihzexm.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtllchisny.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpppgwvxb.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtnuofbsgb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxiadfqg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtiyuodvwk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkftolpu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtuekuzxhq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtfktucszj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtgcjrsmsr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtpsuslojo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtymfxgnny.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtgkielcna.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtktddakgs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtxntkucgp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtsrnmkzuc.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtiudvubgr.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtvkrnbbeq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtvwmedocw.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gttrruimgl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtzqcylpzd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtoapmeler.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gtteesyctf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtamlbbmou.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocsasvan.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtxcqvcmoq.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtpgfbnmtz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtqfutfsuf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtnyueywqg.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtnjptpqmz.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtfablxckd.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtuksapvjd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstrpdgie.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gtexcfnyvs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtvspvlsyy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqeehcta.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtkdxpvgfq.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtfmgfgvqq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtabwlzuwg.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtlfgpxmux.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtznxgzmdd.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtgbfrclbt.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbkdaxcag.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtbhfdnxbl.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gttzqqfuaz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtfurxaxop.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtcywpgrks.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtcaqpzlje.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtsfuzgivu.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtuqxhrepe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtqzmiqkuf.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtnhypxtqi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtolmmeugf.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtqdazdwxs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtxadezqgw.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtqchmdgjf.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtentcnlus.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gthgovnufn.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtntksdtmf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtremerwzf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gttfyhtiuo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtisciwjzk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtdtduugkv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtxsrrscak.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtxqjwwyhk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gtiumldllr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtqnpqkdha.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtylyaeskn.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtenhbcsvm.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gttahenayv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gteneuquxa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtmaayebbx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtkkhttuno.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtcmbpwcfn.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtafwowfvw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gteehblxya.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbqhmqho.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtxkhesnri.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gtklqwxmvx.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtibszpkvo.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtvisicqek.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtbnqlrmhk.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gthsqmneou.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtbitfzzxz.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbqdsrws.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtplesfbkz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtrtvxsoph.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtpbscqojf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtsdjlkhlo.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtisoxgvyh.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtebsobggh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtpvnehazj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtzskgpwig.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtdjzdupqg.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtwakisida.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtxvfibutp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gteeeaqqqa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtwombkdvv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtrxjmnvru.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gthodrbtfl.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtbeidusux.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvtubpfc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtbckadkgb.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtacblazxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtnzorbeat.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gteffsnplt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtqwzflvig.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtdgimakkn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtxsptrcny.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtegvqsiok.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudqwaecc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gtgfejptlh.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gtrmhqubdd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtqqftwbit.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtasmsfeko.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxwlxvxfg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtiuxibtal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtixiigkbh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gtrrnceyoo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtmalwqpum.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gttqnrbjxm.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtybuqbodp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gtkziytglq.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtmhoxgihl.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gteppgoimo.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtmmtzgari.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtxcnvkvgi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtsvgmepto.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtwtuucmyi.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtodotaziw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkwuauoof.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtqgowndvo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdhrpvohx.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtoglvpnrn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtdtfayyri.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gtgyppcddo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtagbcwceq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtnhnwxfwt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtzxzcsgfa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtbsgavcpq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtaixdetyh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gtlgzjfpll.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtmumqdqjz.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtrtwglgrc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtszqpsjxa.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtgazwmbza.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtvlcefwnk.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtonfsfjmr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtrfiyetqu.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtjpenlihh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtrdtestie.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtczuyfzoi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtqjfambgg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtkstkrptl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtqbjuhryb.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtokochbpx.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtochvuafs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtwbfyxdkq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gthbrnjzmi.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtgnqtjvcg.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtndyxtobp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtwnnqeuyj.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtwcrienxv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtxpwvlsef.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtgdhrbucj.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtxaoeqppm.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtlevnzutm.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtkfdwzfhd.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtgefieppv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtfcgeydgt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtgsegryvu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtmgshkgnj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtfpcqhksi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtdtozyywr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gthxxxvvfg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtzvfzjhtv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtbcywctyu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtxwxksiiy.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtpwcwzwpf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtspyyxwko.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtnuxxoxft.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtmdmkaxie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtyhzktosh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtuyuevsys.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtdwdolqky.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtpljejadg.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtyfsliuip.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtzhvgtejq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gthrdtgllx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtwuafvixd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gtckbcphle.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtulqvrwqg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtksivobvg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfbtjpbqc.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtqkcwidfj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtdajbpmec.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktdtpljc.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtkdhizawq.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtabvzjjvp.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtlkrttzeh.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtghmqyqry.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtbrmfsspw.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtiteqofgs.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtmbompzvl.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtuvwluhpo.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtuzktegwt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtypvumpdc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtfxibkglg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtevowntmo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtjazutvyw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtxxrkgweu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtgmojvfft.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtkxepggab.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtwtnkimby.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtrfbatgeg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtluupqcqx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gttypjtmwj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtizcedayc.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gturkjaxmz.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtazueucfe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtpautrryj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtbrcwurvx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gtewnuutsg.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtuckrpaai.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtphidgiwp.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtetfbusxz.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gterayobrm.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtcpmwivzg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtojjcvibn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtfahqjocm.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gthbsdawob.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtpztdzzjz.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtkttebhdv.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtwvybanfp.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtzsxqbpwg.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtzuditeoc.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtvzpskyza.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnukpeowe.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtlgxcjksk.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtmdcjjggr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwsnylce.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtypxxxdyf.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtgtvyducu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtyvkcephx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtkohfsuih.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gttxejtkce.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtboxrbmik.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtazviilcr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtahufbwel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtauyvuflh.html


<!-- 参考信息 -->