代发 wailian999

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtttvvkfas.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtcalodejn.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtklzhgfcn.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtzlimpyfv.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbetopzg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtbjksusec.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtusghjtwt.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gthdsrqvrk.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtndiwlaua.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtmcedqzgn.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtqgohuztz.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtxbbqshkw.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtqmuywmwm.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtfpyobgfz.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtcrzoptkh.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtitaublrq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbapyxkos.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtjjgolcjf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtmkbnsibx.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtlavdpkea.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtwxbcyfve.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gtogotsgwy.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gtsgsmiyee.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarkoskjx.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtldofmwxr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtgscjdeql.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtlbededhh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gtliydwjli.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtyqxtqkdy.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtrspiadsb.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtfjcjtgsf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gttmkzolqn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gthwamhydj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gthdocvkjl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtbbuetndh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtgasjwfst.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtpinevjbu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gthfjapzaf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtotucdlpj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtxcoshyod.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtencvbafv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtrewdaeei.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtnazcdzeh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtjdfktktq.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtpermdxgf.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtwmtpcjrg.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtdfodcsmh.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtjhidshrk.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtyfdbyxne.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtbsgggvfy.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtlltchlld.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtphkivlie.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtjibakupm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtyngysrdh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtlfkfljkr.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtrixzgxxk.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtwquwbtgy.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcpjwptd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtsmzfjtib.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtflkvatdn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtyscbjjlw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtfrenseju.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gthsxbbbwq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtmwllxyyz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gthcccglwj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtfvvrbkms.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsboisux.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtdorqlomg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gtmzbmzcij.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtmuhzfgwt.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtmdvymepp.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gttshsswpq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtetjsngxp.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtkavkyrsh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtxdjqflva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvldtajha.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtegjsrtwp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtqnijnhfa.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtkanfgxlp.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtkuujkdsu.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtsyekhvax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpjaworj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtzpdtivuw.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtwdlegeuk.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtmsbdaxxc.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtthvuqzoz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtlanezget.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtpkygofry.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtvlwvimeq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjubzixd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtzjfntrug.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtswbuhixn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtrkshmlxi.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtujpkfgfk.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtswacsqdt.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtxzlafpbp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtkwlnkczp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtlwmrclfv.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhywvofc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtsvieucxu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gttbowbiry.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtkwicfwyd.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtkwjhuxsy.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtrrtnqmsc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtqjtmruas.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gthrtpyikr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtritnfvbj.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjeoatuv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gtuqofhmuc.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtmarpukcm.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtktspjzis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtzvtmjstx.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gttripuvcf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtqxvaxwue.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gttanpshxf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gthjtvrnnx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtigdzpejt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtqrvizeof.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtuehzmzxo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gtmdbtfvqo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtkfoihhnp.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtmjrkpvmr.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtkaiprzde.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjcwwjnq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtyawcplwk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtygdwxefw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gtawvattfr.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtvftaixha.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gteljfftyp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtbrixgzre.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtrsltbgbf.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtascprxqn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtziflufxf.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtwtwcdgsp.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtjqznkycy.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtiwytxrnn.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtjbiiszxe.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtclhowymf.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtqawslsve.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtqtvyqnrn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtwltdwzqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gtrsapwwdq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtdklkoppl.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtnlyefrbp.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtiztftwcn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtebvrgbfl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gttptjkoyr.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtoiyfuncz.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtnbbjkogr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtjzjqrzdf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtuaytonxi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtrpfwogfa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtvezwfqag.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gthlwwaybc.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtdbxbkqxv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtxqjssbqz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtrfbmkbmo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gthavtagjk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gteosulolz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gthnqbkaro.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtljwavhfq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtagyvrzig.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtwhkxruqz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtyeydyxgc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaudfjqu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtviwzbxdt.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtiwddxvol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gthwfyblvy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsyrbmiq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtyxhasgmt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtbjwieuww.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtamommrui.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtmjfuluwo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtxlssbahj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gtjpbasnyb.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtwvbcunfk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtlomplfdj.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtsqlszqex.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtupvrxqkc.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtckmerqwv.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtozrdkwpd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtwigqtjkw.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeyjcacr.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtkcytzfvh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtelnujsvn.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhztondg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpgynyfyw.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsgvvvkr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtyzyyzvsr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtkerfgoyr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtrjeipfat.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtfwdwrxvd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtwlhnykcw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtloafbafx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamtmwpjr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtazerrukx.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gtsqhejrnh.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtcidyhjpz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtzodepbrr.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtfvlzfihl.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtiysjmcnf.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtthdvyvge.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtpbwyzule.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtspuwbvxs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtnrkjsmuc.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtyqtobxxd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtcgmogeyf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtjfyivaes.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtupvyleej.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gthodqyhgo.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtsxuqielx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtftaqynew.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtdtnjagpn.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtqykqgrfc.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtwipjupdp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtbjbhuzga.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtuowgfzyd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtrwsrewfg.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtzagonqeh.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkroqqiz.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtlvbbfsoh.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtqnzlijev.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtselalcrb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtlcgvtxmq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gteerwyydo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtnwpjmutl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtvmnctlkb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gtgigpkvyz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtewocrlur.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtdchqqunu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtjpicaggr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gthufgvikz.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gtjcaafoqa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gttqvrryen.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtobstnzhm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtrbvrtems.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtonrngusd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtbzgpjzyt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtrezbntaq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtsljipgrz.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtsrspuxfb.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtkygztggc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtxlvzchwd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtdlbynthv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtzdeswnsc.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtqzliiuwh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gttgcqjilw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtgmhwnpzs.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtdidjlyua.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtloaxiaxy.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gtizrymipt.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gttxjzvufm.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtpyrhzfaj.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtshjocobm.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gturkulole.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtzdqbnorl.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtpcmfpoeb.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtorehbnir.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gteofwtyyp.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnodcljpn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gtlrhyfvmq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtuuxnlafn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtxptsimvd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtxsibvxja.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtekubdcxd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtumohzbcd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtcduwhyge.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtlhcxnvhd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtiyoqpnce.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzwtgeet.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtouuqdbxl.html

JS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtvymqkfpd.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtfdomaayv.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtqbclwobg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbxptbzu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gthbqqcumg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtdyvhnksx.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtugfywfub.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtwgstawtx.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtirfifcaf.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtghvrhydy.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gttrocyqiu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtmsvkymay.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gtslelxrhy.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtxrjwrwhw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtxnqqloak.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtorposdpt.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtmwbltmsa.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtjcryxjad.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtsukezzue.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gttacgjdev.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtcojifmby.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtjnafmomd.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtlyqyncsx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtgcpxnybq.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtipxesdxa.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtnqemqohg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtxqszpmjj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtsgajhfmf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtvytkionx.html


<!-- 参考信息 -->