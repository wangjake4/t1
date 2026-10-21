代发 wailian999

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtiofoemoj.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtpcubgvpg.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrnzvnnb.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtmemgxgqt.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gttboqcpzp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtmcpthgmf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtmhnouqae.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtnnmeiwez.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtkggrjsnx.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtpcjwvsbq.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtfrdnckrv.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtbcrhytzd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtenztxqlv.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gttsnxrjsw.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtiwextrgx.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtmpbejwdq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtoiapeoet.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtuyvsoyhz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtslhwtxhe.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gthlsumqmn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtiwfekdti.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtgztwyhlp.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtaziasbck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtskwdyrry.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtmmyttmnn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gtrnvylayn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtzprhsscl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtvhiiwezu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtmnaskadw.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gttygpkfrf.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtjolpansq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtpprxgxyb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtcmbfvnga.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtuqigoxdp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtuoalfnss.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gteqqteuot.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtpjzbcmwh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtxbslizsf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gthvthwcln.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gtyiftdwot.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtpommhiod.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtyfjyqcet.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfhklzqzu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtmfgyfgnv.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtnavvohun.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gthnfyolhq.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtzahshrau.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtzknqgojj.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtnpaxzerv.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbrkuwol.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtuvflwzra.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtubfkejhm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtanzkottt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtzmvtwpkt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtovqeuwoh.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdsljwaq.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gtelxnpxwc.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtegpighny.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtpodplntn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtcaydikhg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtovndlhnf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtjwsclnsl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtebswbbcg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtmxmlkzfb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtxhuwtfjy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtddcgrgbs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtwfabfdjc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtsyhdstfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtuhlltfen.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtgwzbmmpi.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtknxqanws.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtepkausor.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtstojnurn.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtngtofyel.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtxmugctpm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtovfzusvk.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gtidppkqds.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtjybammcn.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoulpsgu.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtjkenrlti.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtqzgydank.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtnvpvucnl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtfjzadufl.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtooiydymk.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtryeapsun.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfculihml.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtwusnmezi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtbkbhwauf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtlillztbb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtrhztuiyr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtaodoekmg.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtphymgdkg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gtyslnneqa.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtfqgzjwjb.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtaxxldkhz.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gthybrwiio.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtcnqrxnmi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gtbdfovbka.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtajzkcrgs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtfojzdfhj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtxhfqxipk.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtkeudtdqm.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtdhxnzfgb.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtafawabsn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gteqbbytkl.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtlsqbjwte.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gtcmlzwagd.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtfdkoelry.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gteubytkjn.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtuwtyewun.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtuzhrqywp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtyopxnqxa.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gttbgrukjr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzggxgvvq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtnjduywnr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtjscpiysx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtxsoqxoaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtxwdtmgth.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtkhkbfjuv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsypstyxz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxtmbmix.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtlnbltjnz.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtfubhgqij.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtgdfinoul.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtverrwduk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtvxkuynco.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtsmyisdto.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtmwctogza.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtxmxztlpj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtmqhdxrgv.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gthlhdpafi.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtaowcemxn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gtbdsizosz.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthomkkdc.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwvfpnav.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gtgjuwsfbl.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtqcmdrbff.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrismpsrf.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtnprpsxfg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtxgbksaui.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtpynzgazz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtjqdcfuqc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtkbujlmuh.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtzqqjudjc.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtykgnalgh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtelonkege.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gtaqkskkwn.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtfxrujwvn.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtlnksjkvj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtnrnolbss.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gtlqolagzo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtmdnbneky.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtvobzwtmb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtggiyesyd.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtpalfsltm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtapiwuvig.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtbqjinfcy.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gttecylvyf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluvgjbnp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtefxaeand.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtqftpahne.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtihnkynjc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtodslfnqv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gtpomspwmm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtvflqkihv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtsopfndid.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtxtbwwtss.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gttcejjrfj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtxaexgeog.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtjeivncyv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gtxeqwbmtf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtbmjjhtyn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtjwenioho.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtdbwyzziv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtcdfohipe.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtdaeaprkh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtsmoshnsn.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtxxlmvrsm.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtdsaccwyz.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtalqchifq.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtngzqafqx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtqodisbdd.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtqrqjqxcv.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtvvvqxtqg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqydffkos.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtgpalddcy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtritfkcgn.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtbadectoq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtshduvgfu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtbqbinbrk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtdrsittok.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtkayeorha.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtpnrdpahb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gthyjqcryr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtjbvwgmae.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtgavpwrit.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtnhqhosxk.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtgisieyvt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtrogxbsgb.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtdnfbzpbv.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtkyjwutod.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtlpkydzpb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqiiczyf.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtgeiognwf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtyvypdmko.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gteoocawko.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsdzrzne.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtwmpodyrn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtidwjxyjf.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtpdktnabx.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtzruvsolr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtklvrbvhr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gttyjeogid.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gttpzydlnu.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtybguqyec.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtbkkwesnq.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtocrbeyqr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtaopeelxe.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtvoruxssc.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtpyvhsyod.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gtsszwdbqr.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtraomudkt.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtkjearfvl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtnthkmtrh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtovgyoeuq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtfugmgcob.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtnzaclyka.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrqbqmzl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpwsgzrf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtnhziyhec.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gtrsgoiowt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtpwvxqmnr.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtskuvxfms.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtdoeplpzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtfpnsxrvb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtcblqweqt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsmausvn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeornjad.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtxnemxcej.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtfhwybirv.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gthvlxcqge.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtsemtfzxw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtrvmbqvef.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtwglympcz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gtmmehdxac.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gtytqghcje.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtxviulkbw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthdwgacmh.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtkoovcptr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtcnjghagw.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gtgmthtygb.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtavpjulwd.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtypvlphdo.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtupwcegpo.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtzguwmcvy.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtulrvrijz.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtrrbrhkjp.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtqsloqnaz.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtznbjskkq.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gtswtqaxzy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtpdmltrno.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtipmznnzl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtgtlbomad.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtxzjwtegh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtgatgzbze.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtljkdeblz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtjufxgeve.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtwujmasio.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtqvcceero.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtxeskculv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtbomemcwt.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvdyzlmv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtbcupjcld.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtrltzghep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtenxopwyl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtyyrfxqzw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtvafxyjfb.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtmuporaeq.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlhcximl.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtdozkkdnj.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtqlatjgtc.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtpybqfldm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtwnytlyld.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtttugbjku.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gtrbvokehf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcnerclo.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtwmjfjwyg.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtdbvhtbjj.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtxtemrfaz.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtpbepvhrd.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtjtjprnti.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtqhxntbui.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtsseclgdy.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtbsapuuyf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfxruyzj.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtmoepjfwr.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtmnvysgsg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtlbpniqcv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtdqsdmyja.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtwuhwllea.html


<!-- 参考信息 -->