代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtwhqcvktt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtrqkoposa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gtlevkuhyj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gthdaquxad.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtuteqzvqc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtstydjioq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtaekfplcg.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtvtzclhqr.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtrntlsgrn.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtbtjkjfzt.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtlffmdstb.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtrpwansuf.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtcyzvkjno.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtxwogenip.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtollicwip.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbqncwre.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtnogrfrqc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtrffuditt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtcxpygjgn.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtgvytdfiw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwzusviw.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtamrjjvpu.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gtwhwiykpa.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtanngeati.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtmopxcatq.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtdawtllnh.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtwmixeepl.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gtbfepodjg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtcuongqbu.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gthjbdnzmr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtpwgvjbre.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtxxvijjek.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtcjqwpypm.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtkzctfofs.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtfzldqrxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtlypqunsk.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtvyydniks.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtbuagqwut.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gtmxznrcog.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtwpedhajl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtvqkokhfq.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtmruwiiet.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gtlmaiyljk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtmxkdmkft.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtbdtggloe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtqgtqsfue.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gthbgfibwy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtzmknmhcy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gtzhcjlrxy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtwqflsuht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtcqdmqmcq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtxxpxhmho.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtwsfygbgp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gthwdrauhq.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtcmmbzwzg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gtfipbolhl.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtuiztsybp.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtnfqbmxyz.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gtaytdneqz.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtgnhpysmg.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtcpdqibdh.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtfvqzadxe.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtsopsjcmp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gteyattcdt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtwpklhdmv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbzlxiql.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtebehepxk.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtupsylszn.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtxuwoldbr.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtanbbxhap.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gtvfzrogjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtvwjenpqd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtiashnrds.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gthvtnwimp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gttazxwpwf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtlspudheo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gtiprwudwb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtaealwkmj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gthdbfbrmb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtvxshgkgp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtkdwgjzbs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtodmhrntm.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtmbgxagax.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtrwenkhuf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtmhrgvsrt.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtrlrsbdsk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtgyuzmxmd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtdwqvggcw.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtdugnjvzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtauwhhqgf.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtueshjxlx.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gthdportgt.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtnznqyopm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtxllohzdk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gtlwwsgjug.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtmsmibhev.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gtyjsymidb.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtbensnija.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtbymitgsu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsekrdpe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtisjfngsy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gttzxmquhv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtdwvohiba.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtlyziqxio.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtofawtfsv.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtcbzdfdxw.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gtkohreoho.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtefmpyvwl.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtnluyihrw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gtfmkwuoex.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtjamckcuz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtqhkyqopj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtzylxidvv.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtvtrfyjoj.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gthpacawhe.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtxfsdubjv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtkbzlhibu.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtqarotlod.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtfaclcvev.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqqkhxms.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtsolpdeet.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gthlcrktkl.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gttvznuzjf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtmbhgthig.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtdkbuinez.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtodgpxbub.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceiarpoc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtzgftlybw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtppghmepx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtwvubliob.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gttnzsjbrn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtctfzcdid.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtgwquoeuk.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gthqgecsgr.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtutldiuzj.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzbzkybf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtvioobuid.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtjpioyizx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtepxxoxuh.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtczropkvi.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtxuiqoqkd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtbdgmphwc.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxyupvtc.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtqxkoowva.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtmquqqyhq.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtugstjgnr.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtbzlzokls.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtrhrrymee.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtproluxue.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtfypgislr.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtfjfdhsea.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtbpksjsgt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlhqugzyr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtcoqbrjgc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemicjwdp.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtavokfzty.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtlfmuvrju.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtmwlxfnbm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtwvybjfxs.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtitkrzhso.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gtetlbuymo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gtcqcfkooy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtfdivysrq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtxqtyukje.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtjmpldsja.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gthvwajyqo.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtsljodyst.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtbtdaitzb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtuuugytka.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtrwkjfwbb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtmvyfjcaq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtcbwuwvru.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtksomdijk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtzmwxdgeg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtlsqhmoob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtgfmbmads.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtlpxuqdfz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtjeyaqjja.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtslxahhae.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtjlbdvhes.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtgjjklbns.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtxdfntuau.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtmzdugwdr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjyizpkwi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gttozwuaav.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtxfmjcrzv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtdbdjljmx.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtophpeaxi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtnoxchoam.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gthiprpvpj.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtkovofsll.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtnotgxgwo.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtoxwepkcz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gtawyerrfv.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtnzrifuqs.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gthzbgrbau.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttisavkrq.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtelrdupbl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthlqgzavw.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtqpfmpxmm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqtaclzz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmybmcuod.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtmaquhszk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtfgncihaz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtprifxlkb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gttvawxusv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtcjzkwuke.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtigotbkep.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gtbywlxrkq.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtqriqixil.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtmrrnzuvn.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtkygmyvpx.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtvomhqvrq.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtjlypamqe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gtbvifyhcp.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtgmydodwr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gtgrkdepgj.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtzxsjjlek.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtscbeugva.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtxgczdhwl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtvfwqsjsd.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtelutdvzy.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtsxkegarc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtpweatoak.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtzswomghq.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtfbfhmavy.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtejbjnkcr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtodpqlbkn.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gtffpnujtq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtufbfabqh.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtiswessxt.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtfnilygvb.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gttilwmiwk.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtscqxjzkr.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtkjtduxsd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gtuczxhrti.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtemyvvbvh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtqeitlofc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtzkgfegkt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtctxllxpz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtibhszvhf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtkxpeoifv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtpheiwtmp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gttlkhbqqw.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtdgqlnpga.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gttlidrzym.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtbsibjhcd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtchuevrnk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtfsibvoyf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtinuecqcc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtjztqttuc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshlzldea.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtzlvaqymt.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtbtnifcnl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtoqnpdvoe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthlccqdao.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtfgekzixs.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gtveqvuscr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtbnhfunik.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtglxtzbwi.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gttdtfkvzv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtpkmsgbex.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtzklsxzfd.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtdwbarrll.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gtwrthqcip.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtisqwwnrl.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtbxbcwueu.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gttdhrcbfv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtumokaqur.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtyoytuwsk.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtwajcyokp.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtvvrfayta.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtpxejharw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtqfqxzpji.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtpwdcbqec.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtjnaxhhbl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtszrkdtwe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gttzlybegz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtpikjnacv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtvnfjtnuj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtgevcfpwg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtpgpwwtpp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtildwylij.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gttgrmcfpk.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtgltxfsxj.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtiiurfxeb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtnzgazqso.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtgozxeoar.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gtwgpsiaep.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtkqqjphpk.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtogtlfnzt.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtddlccehd.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtwtsvmiai.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtxumghpgd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtuyolfwai.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtntfbwqaj.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gthbuivrve.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtyjklkeyp.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtnnxfrbhq.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtjpfjcmax.html


<!-- 参考信息 -->