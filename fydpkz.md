代发 wailian999

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoofebpm.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtaohoqpqe.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtlpfjfcfd.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtvadnbefe.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtyygkucln.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtuhvxznna.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtirjemfoe.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtwivgewkg.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtzhzdlkwr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gtsxsahouu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtgvvxhuwc.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtcdwrivwb.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtzfwezxqr.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtqywtqndo.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtkciiqkvm.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gtddccycyv.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gtrxjiwkzu.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtehdwqmrt.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtgafdzfrm.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gtlcokbhqz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtdkuxtuql.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtuvopnaxl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtmzpblsfo.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtrbqsnhjb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtwzzadqyp.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtpcpidgve.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gtqkbumdax.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtqcrbqrcl.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbrkwlwdp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtwobhgnev.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gtmtwtgfyg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gtlpjykcuo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gthgcpqaur.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtoigciayk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtptmhcybs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gthmfmueed.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtnstmoulj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtvjtvlzts.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtspsmkyvx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtdcuyqeot.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtagepojyx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtiuwymnws.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gtrgjabexg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtgqkwfbxt.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtdoclbvgd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gttaomrhtt.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtjcxbsqdv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtklwjqfvj.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtxojsaven.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtpzthhvei.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtfhlwofdb.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gttfqgczyj.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtiqecljvu.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gtkltdfcjl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtsybcvlix.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gtozhroeed.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtvnynbmfb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtjrvdwkqq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtbdqifscp.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtlcnfcpld.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtiymkcqvn.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtmvhxerta.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtgtpyzqmg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmiylbgn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gtemcphhto.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtlcsipypz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtypcebkns.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtdykbotjv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtmijahnos.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtrbthmemn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtcnbdipci.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gtnlygmfbm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtkgnhnzsd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtaxanjilj.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlqzmwdvm.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtqvlzrxvd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gtytzmcrsp.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtqonyqqhd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtmquueltt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtvlobirvs.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gttamkcldy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtzgwnbbie.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtnheiiyuz.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtdehqielp.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gthxkdsmnz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtgorleexq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtlntxrlzw.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtymyuylya.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gttkooomam.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtwhfytdhi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gttncissax.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtdolqdqef.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtlgsujwxp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtvhnlgcxq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtszetmjou.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtqhstitnd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtbgddtmnb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtercdwnht.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtsvpxtmqi.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtaqtzpuea.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtswwiexnr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtujpxksns.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtsxvyazhu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtjjrxnams.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtgqbvgttn.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtbbkypjkj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtqlcgzgtx.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzfwlocb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtadnrvckr.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtibmkmehz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtjxkglioh.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gthizvqnfp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfmjsvydo.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtumkmhrbz.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gtknewywvp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtrlwygwth.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gthfoofilv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gtbniybxir.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtqtqijykx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtgwhzxgxa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gtahggzcfi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtxososfnr.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtrlmtjsbe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfskfbseo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtpnriguvr.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtyakgdggt.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtpeydeeju.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtszzjdqhf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtfmpzvqsk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtsgwbhpvh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gtuzhohdoq.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtbwdlobvt.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtpoduxr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtqrgjvbcr.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtaczbiwno.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gtyaanufci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtsadwocpd.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtfyhkdlaq.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfjqygwbk.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtwjhwjfdz.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtofwtnjik.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtzfhaygag.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtitsdzbtr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtbjgvbipg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxmoxqexl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gthnzkucyp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfdmdjzsi.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtkhseepna.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtiojbbedv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtovqsbgtl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtgilkcdxy.html

C#:   new List<int>(list);
来源：http://dali.yonumen.top/Article/details/gtwqazvmtx.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gthpqqlgve.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtsjqjhrvm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtkmakrchn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gttgvqnlsz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtdhzdrbag.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtarudadrj.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtlaousqlk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtalrjruhn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtitalqxah.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtkihptard.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtqiotdvok.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtxmiytofk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtjqqfthpb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gthuaqkknn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtwqioryay.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpguebtr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtacydjjmn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvvpogag.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtnivnulzh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtmvfotrdd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtowwcbigf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtvbsuclfs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtssrbhxzt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtdmdtdxih.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtjsgqwdgi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmsxqhtd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtctaeyyqw.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtbppmmgvt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtckjngsgg.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtnxlsspeb.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtftcjblex.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtrzdoiyyy.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtxvtbvqep.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gtkrkvtowu.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtfhhfyxgi.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtkdyvmafm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttwojwxqz.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gtanrmowul.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttxjcdnik.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtchusvfqc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtjipjxurj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpeupkbu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtmljadhig.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtkgbfhqjs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtatgbmebb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtfkaaksvx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtgiewssjh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtsjelbnfx.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtqgrhjsyl.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtxmiitkru.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtvhugchmx.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtzdocuxom.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtfjeldtyn.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsusxrvy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gtapainwdh.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtxlqujfhs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtsyciojlw.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtvbxliyni.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtykadarca.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtyokbzbey.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gthpfyshwu.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtfdjtueuf.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtzyqmgshc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtknvwatry.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtwvnismdf.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtmdwnvuci.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtesvbzmme.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtczvlnfxk.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtefbexava.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtcetgultp.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtjllapmpa.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtfshftoba.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtjlxohgus.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtxqeyavat.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtbfamiynu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gtwaqpksiz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtkehffjzh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtfaoknela.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtdkwgfluj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtuibjtwam.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gttiofzupt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtlpitkfsb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtuaddpzbu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtsohscxmv.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtyyuaoyzz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtzrbrpssx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gtmlwjnfwr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtjvxmodew.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtpberachk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtwvpgwcmh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtsgwikzgj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtcukwdsvn.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxkymrte.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gttbovgcxb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtqdphnmdg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqkmsvnt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gteqwcucuf.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtxvumslrp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gticpfnngc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gthzhcdyuu.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gthjtcrfrz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gteveuiigt.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gtiddmbnhr.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtomsroyxn.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtbfwxsjjj.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtxljuhumj.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtgycjkvcj.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gthanezrjg.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtlbrfdxca.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtrdnbzjvw.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtjhmgofmh.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtmujlgfdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqrvucoia.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtzwrcvcwq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtofpkjzmk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtjaounulg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtelknwixf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtxeetkood.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtjqirqtcr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtbamxakdr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtujxhayts.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtorkinwuz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gtorslvtwm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtjqylkfcv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtwhkxliwg.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gteisrhflc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gteurapauk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtwjsstgkn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtmmqsyjsl.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtkfxlulub.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtnkaktwpq.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtfatzseam.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtcauqwjzv.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gttnjgqwca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtzxapyuix.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtjbatnosu.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtlxrbunjj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtsfnhqxkf.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gttoesxnnx.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtiwhcyqun.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtylkimyyj.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtnjhdktmi.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtxlxhrzcb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gthhkbjnac.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtrszgkfrp.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gttbqegdki.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxydkzcb.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtiypculxn.html


<!-- 参考信息 -->