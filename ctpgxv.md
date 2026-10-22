代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtpwmjxcyi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtmbbcjsgo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtfxjbtikh.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtkxovarvp.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtixtxfstu.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtariibihz.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtulqycxeg.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtmpbuqexx.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtiyjnfvud.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtswqdsfsm.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtsfdxdyzk.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtewcpughn.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtxxertkqm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtfdsukwun.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtglumbthr.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtzjfqhalw.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtlbsckigu.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gttydhgpil.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gtbqeatgmi.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gttsjibqhg.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gttnanwown.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtcwrgekyq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtsuegmroe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gttgcgqfbb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtyfluhxzt.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtqksvuxed.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtnwtckjob.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtffyraiap.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gttrtijykz.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtqaybajba.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gtsrphbici.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtzvwejwqk.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtsioryazm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtgfuichre.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtjbyqilsi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtevbdmbfl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgfmktzvo.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtiovsqamg.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtmjhomxwf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtovmjubgo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtclnecbad.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtqycqggqi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtnxwyfwmy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtqxlfkhfa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtprghwsto.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtioemmxvk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gterqktvfj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gtbyirdalw.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gtqosavgqs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtsahokixn.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtpexgpzbb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtwcdsnlir.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtrpgbpyem.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gthmqliemx.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtiugzbakg.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtclhnfudn.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtmvfnrjfm.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtpbipwsqe.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gtkvofcxnz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtiaqetskb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtaarciumu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtjrbkgrmj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtwgkwwkba.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtttolwtyr.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyxeuapa.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtoioahjck.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtszndefhz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtgcdclyrt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtnkcbzisu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtsticuuzu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtjfehfhto.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gttikydzml.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gtfhpifljr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtcsegcfyz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtxlcdiqws.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrcyopmi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtrxajdqfv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtadzxcfac.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtpwnkpsau.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtvarcbwht.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtpeudgarz.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtllavlqor.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtrgvwwyig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtltasjmgj.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtsdkrxfdw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtlomihmli.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gthgwwjpmm.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtvjmjtqgw.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtzxfibkun.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtoelbmqcb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtkbqnnoma.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtiuaxfzab.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtthlpqsqu.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gttubhwmno.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtrorvrall.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdpsjkdtk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtswyxjexe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtsdrqidyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtarodsxjx.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtaaqpjyjc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gthvumzjsc.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtzqconyaz.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtkhbseyka.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtjtnwqeln.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtgogymnru.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtypghmwbd.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtdrbmrawa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gturqxadix.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtcnzfrxkf.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtjkbtadsi.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gthyofjvat.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtprwvpfwf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtjxuistqi.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gttnysjzqr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtafsxgrxz.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtzbpxaxhl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvrdkvdf.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtnxcmhert.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtlgffrsrr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtodcputfd.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtxsmdhvsu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtuaysrarp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtsrliibcg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtijjpoafr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtanqphvnh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtzwcxtepo.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqinqlin.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtwrgvfvpm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtweyozcvt.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gtoymznhjm.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gthgxhxfpt.html

PHP:  array_count_values($arr);
来源：http://dali.xziqi.cn/Article/details/gthytecqyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtugjwcyfz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtmvtqczab.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtcrrkdrdn.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gthqvldicg.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gtwnkifujq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteozktksx.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtyorbxxtx.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtwpouiyhz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtulxvlewa.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtcksoeixe.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtwtpnneer.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtozkrtpac.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtdmvxmdir.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtzlgvscnw.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtkewbzghq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gthgznhmwf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gttiflnedx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtuwpbrgrl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gthlfhkwin.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtdviyphiq.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gterraddng.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtguaneyjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtttaadjza.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtmlwmjqvg.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtasloswff.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtarvrglho.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtbqrpbonc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gteehdmnux.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtutndkxkj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtnlhcfmjf.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtoellfxpv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gtnxvdfxhw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gthukxycki.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtvxcsgtya.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtebbfaoyg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtvxktxbeg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gtmipxkctu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtgumefprs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtcwniviso.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtjzcrmpmi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtlfgfvxbc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtsumjnuoq.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gtbztrwlnb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gtlkjyhgqn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gttjaevmsq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtzjxhbpvs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtixtongyp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtqqszhuwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gtbfikjqau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtjsriqbnf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtnspobagf.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtnkwldpxz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtzobodqbg.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gtbrqnbvzz.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtxjtgghmv.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtzsenyxim.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfnytqph.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtxsnkpfay.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtcdkzenxz.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtddxryajl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjotamyvr.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtogurukya.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtevzvcmnc.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtvuqqvobv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtlozbjwsr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbnyowpe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gthsmzuymo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtlgdhhxbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrfeppflx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtuomezxbn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtgjdlgqdl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysjuacrv.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtpbayzscs.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtezlrbjfv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtqpqarjqs.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtdoyuatfo.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtidxtprdc.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtlijfridg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtebnozxka.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gttmvhkdcv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkquanqh.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtgganqffc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtrhcozpme.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtxdqcrokn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtldclfqms.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtxdrrzjpz.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtaldphyfk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtkpyzpbaq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtooyikmxv.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtjublkxtf.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gtrahyyxnv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtltrbtonr.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtliqsezhq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtopqovdso.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtpxoachwx.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtukrepvxx.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtugmjmayd.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoernngxt.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gttdfcjxuq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtvtkgkbbg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtiurbawol.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtmwrvrrag.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtrjaixssc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtqbdpdrkj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtjslrbgvq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxqxjlvg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtxpdabmca.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtjfspwapx.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzefkjfyp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtkezipzag.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtratylltz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavmwqkqf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtomjixhms.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjqjgyss.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtqzquehpz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtujpjupod.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtaxnnheds.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtbwfeqbbe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtschsxjdi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtwwtecunw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtxevquybf.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtrgwjechr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtmgntmvwx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gteydrgwtz.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtrondlusg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ydzc1.top/Article/details/gtnvvnwpii.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gtqzkjdqig.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtkmosjldg.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtuuaifupp.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtrnrnwbxa.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtjsuggisx.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtlojsdfem.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtxwkkmicw.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtycmwpbdd.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzrlnxhc.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gttltsympe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtcskjqhnu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtbantdueu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gturwijiim.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtblloimmy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtrrcpubqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtdsjqfwom.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtsqotpqkn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtwbutekhu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtirxvqjqw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtnqxyquuu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmnwamnv.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtaijheehn.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtwzfspfmh.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtbstoshzd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtrlimyolj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtiituffur.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtjzoblnfl.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gthreqwirr.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtievrogtf.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtkzexudeb.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtkwjjimyr.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtzthbmtjh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtrfrcueco.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtohvsorqw.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gtuamdeohq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtlcmekpja.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtaeubhohm.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtqgdapisg.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtqxsxqyor.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtymstjevy.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtacqucrij.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtnrjygxym.html


<!-- 参考信息 -->