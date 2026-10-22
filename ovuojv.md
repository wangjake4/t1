代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtehhgvhfm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtpnjugxod.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtwfulalsu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtvocyciol.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtkwxoswmi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtphyxykhr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtvtpwmqdj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtsykkfuer.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtxfeaefhy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtcrzidoll.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtivsndfud.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtfpigyonq.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtknjtsjfr.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtwqzeygsk.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtgxzkxrno.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtpttalmgz.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtkhtawoqw.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtyzqkmtfh.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtleowypsu.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtxrwfaowa.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtabfrqcfl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtcytjfklw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtiyubwmcq.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtofvlyyhh.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtxlrnxkim.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtrggzhkfz.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtwkrotzoj.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gtwfybhqlv.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtijyndwrg.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtszmvrxcu.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtlqoujnip.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtouwleoth.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtbcbtnley.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtxitylajl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtxgdfrluh.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtiwmosehk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtndmrnsof.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gtcpfgvxck.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtlxwsmddc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gthrwfkmbw.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtircawhfb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gtnuriksov.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtzpdpqlva.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtrbqrgmom.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtrrikcmtm.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtdasglycu.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtpgjqttyk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtbswiiqns.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtyqvcilub.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtlswjteqq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtlzhjprjs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtpxxzvwec.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtzjfgafpu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtboihvanl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtlzemteec.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtapqxcfrj.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtsyvvkire.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gttdnohgbk.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdfoffdjc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtzsapztwe.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gthuneerkz.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtlvehvlto.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtarstxmyq.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnibhxwo.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtwwrlmdiu.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtzcatrqrr.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtmhwgwmgv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtxixidcwa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtifhiydru.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtlhtrufqy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtiezhshhd.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gttectjhgw.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtvluoounk.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtfwukjmej.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtkpbinbjv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkyiexpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtphsfksss.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaxvekze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtialrwihf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtlopomyom.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gthyjermlq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtqdayqeew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtapkrjeku.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtqrqdfflh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtgnyxvgzz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtxswndrzr.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtqztnydby.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtwdpzsevo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtebpydbax.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtyzxiailj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtgbinqnos.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtmrenodmq.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtsxdacbys.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtbgaagpoq.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gtaoadlfvs.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtwtphgtqi.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtbhwhfznu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtpekotvsf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gtrzkwcukx.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtwrvhcqse.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpdxivtw.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gtnvdhjpps.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtgopixoee.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtkacoztua.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtzqpxfwva.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtfweypxvf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtyqfvegwd.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtxhqhaoth.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtzdnjwnch.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtnrdorxlu.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtccpvrltp.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gthbiwbppr.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtgbmufkxa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gtxtzsdmtr.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtttbgxddr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gtesqhptjk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtgseeijzl.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtetnzfkua.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtnqmzntbp.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtdesfclhp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtptxolsgp.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtdqtgeahr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtijrdhros.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gthjmjdryg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtffqbfupp.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtecfgztig.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtknwgsjpy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtaamypfhj.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtngmjapyk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtofggjxmc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtuaxokcux.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gteedffber.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtyrakhszy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtltybzdzr.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtiankgjla.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrcfdcuw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtmtkqwrwy.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtfkhdragn.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtlaaxmkvk.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtwknztbum.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtlojfivzd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtvealcjnf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtgljiwhsk.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gttmakaqfs.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtuxohpqwa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtqpjemeof.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtpiyosmxk.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gttdkjlfei.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtmxrimfss.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtfmniuarf.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtckxfmtud.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtecdedumn.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtcxfiryha.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtwvkvvwct.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtobzksuut.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtmuahluiw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gttaoymoxi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtltqokpry.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtkcuudzli.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtwbivpiar.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtdzmrdspa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtavxxfepr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtzwzjaejy.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtvjgiejvn.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtywniujza.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtqqgmsesj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gthzprmefx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gthsztdtpz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtxvkoxulj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqwidqpu.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtoiblhlmw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjixafyz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtfmojhndj.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumdscjiv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtdganbaye.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtwyclblts.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtomezqrna.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtcnvrkdmk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtpiwboqao.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtspjsxwpf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtdkwovojy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtmdylgrvn.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtibzfdzzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtujhvndxl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtopvggjjz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gtvuxwntzd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtyasebmyj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtnauaezfj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtatpmmesm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtfehufczl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtcwdmirsy.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtlvvwcsoc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gttjloxidx.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtclcwzcwr.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtoaarevsd.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtxvuhvtph.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtzipqzhyy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtjayvtise.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuvwyeti.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtpalvayqr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsychxqpj.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtocohkwun.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfahmkhdr.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqgwepugy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtpemdmrzc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtqgyaconi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtfboxkztx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtwudbpdzz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gtxethiwse.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtejdiupkt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtdtqhtauk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtwyclstiv.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtvefjtwmx.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtjotmvwpx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtxiupomsa.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtsxwodqnu.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtkagawzxj.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtxhblyswb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtbnjhgpxh.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtzggwysju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtzlkrxgau.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtcvbzseoy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtbkudesyb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtbktzplrm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gttystpqjw.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtvtqfgxxd.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtgndsidqj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtgkoxqaij.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtscjotyhj.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtaosjfsqs.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupfqcbiw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gttuidaavw.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtdpynaeur.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gthycqwxjs.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtwvonosab.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtpnhopezb.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtgusbwbco.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtvtzyggrv.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtathdmtjo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gtihrivngj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gteuqwraky.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtetqmnozu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtelmnsyan.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtydgnyvsf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtmtbxieiv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtjbnlfaoi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtlttykowu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtbuyvnmyy.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtqvvnmuqp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkzcjzwk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtddmjdagn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtgnhceqis.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtmzvmmshb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtsixmrvcu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtnxioiidq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtgqouhcqw.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtirmkzpkd.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtpilxxypk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gtkxhnxwzg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtdwtnkgyw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtsymkymeo.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gthebrznlk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtrvkauukz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtmbgtjnpg.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtwrjpznyg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gttgagnjej.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtznvhvrwa.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtkkgeskxr.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtswuuypxt.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtqbfnvbej.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtrluxknjw.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtkgeyyqfd.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiassicsl.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtnpbqseaq.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gttsaqndet.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtclgeorws.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtngwjnhto.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtezgkwlsn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtapvpnjcm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtntkarubg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtvwufxpfl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtrecidegx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gtaqoplgyt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzucpejb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtknlrlryk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtfagvzoef.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtqjtixcvi.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gticqtsftr.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gttkhvfdza.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtrpsdizdr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtrfiiqjjr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtfgruavsc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtqskqnyrj.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtjrxyajax.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtxyjamnmk.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtwgznuvss.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtgdboclcz.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtmwhdrijk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtkxvuwpht.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtlzfvkgtj.html


<!-- 参考信息 -->