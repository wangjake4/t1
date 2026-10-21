代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtlhkzezpd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtihyvadak.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtygbvmxih.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gtrgmsfmqj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtdoghqumm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtkcofgccj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtjtjlemtr.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtaaaaxycw.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtqwgjdegl.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gttaajbdfl.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtrmanfaxi.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtxwhhqftv.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gtztfrprxc.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtwifqqgxb.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtpazvsvoh.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtmwijspaz.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtjcdfgwum.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtosijhwje.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtazeaccjb.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtxvccetpl.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtxmvtgqwb.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlhrhinr.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gtqlhtdrvj.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtucsmyqis.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtzptbmrad.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffmqsqat.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtbgbvlqkg.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtvajxnjyg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtnsjtgikx.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gtewamgdcw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtyjoywydw.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtgmirzojb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtormwxgqa.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtziklcaor.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtukynhffk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtztyonvcj.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gthtlcgsqj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtqpecssod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtfeulemqz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtvsoeibhr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtxvinxlbf.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtrprekwbr.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gtxlugessn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gticjettag.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gthmlleplj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gttsmrbznf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtqigyobar.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtoewglqvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtmzvccrcv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gtsbuovhwx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtgatcopzu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtecozbmnc.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtzrzsffzz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtminxijfg.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtnumubydf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtkagynchz.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtduvzmxyl.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtgcwfgbno.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtnnuobyhr.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtktnqqooo.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtcviadbqw.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtdotzspkn.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gtpkkuxago.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtiitvufmq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtglrwjavf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtcpvupoag.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gteolpqpig.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtgnrzjoxm.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtktjtlqhq.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gtqxnvjcks.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gtygihesqv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtetqnjfuh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtyrifzsxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnwflnig.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtjwuumobr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmwjndct.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtekmeqrvf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtabkfrtvg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtaoqvuqry.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtvjxrrwlz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtlbdtzhud.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtskmvtjyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtbzdinbvj.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtsapvfxck.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtcwdihoym.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtodvzaoce.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtegqwkjwy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtxnkgddmx.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtxcbjtohi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtxrhflboe.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtbicsjzgk.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtrtlbkdij.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtmqqfuajv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtsjjnwjbm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtarsazzbb.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsukzzdj.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gthgycgrux.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtoizvawty.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlomspxk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtfusleesj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtsewreclt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtfrwjtybw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtvsdkqmnc.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtoodxossr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtmmuffpoe.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtdqtodmob.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gtztwqygty.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtxcaobzih.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtvvfdzhkq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gteqogmsaz.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gticemxupk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtxjrvftur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtrvmyqkwv.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtizzmdyek.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtgihjbbhj.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtbxnfzcfc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtemtpgkcl.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtpzjmrrio.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtrgsibutt.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfqmupcv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgedejkgp.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtazkvafns.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtyzbdgofn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcscccelu.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtflxsplao.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtlnvxgpyx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtakrqpiqd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtjqzqdkvr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtecbrabxt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtttnwxqtu.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtaadmlggc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtygrerzmh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtkancmnfl.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtfqwtqssh.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtgtcbfxvv.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtrazqiqcf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiazijrz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtsesiebyn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtfsrpedcz.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtiwxacesi.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtjhvaioae.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gtpqpsqdjm.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtvyyfdfhd.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtxbeulbdl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtzbktkugp.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtwsuhgvgo.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdjkpsxi.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtargistcw.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtzikpngkz.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtvzqmdsrl.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtpyrtbmwq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtmvlgriqy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmkjcxagc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtdatkmgjn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtwytclzsb.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtzmkmzose.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtngqgruez.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gtgwhqhtnp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtnnnmighq.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gthbwceyht.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtbkipzeai.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtvtlsjehs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtpvdhasgh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtwkqlkodn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtlotmvyid.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtalgxepzr.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtagmpotht.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtrcdtideu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtonhqitbs.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtgouohqxf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gttwopglww.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtacvsxbgt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtzphcaoqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtciqjaviu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gthqqzvuxi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtvrmtujut.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzenopttm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtfgidxogx.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtbmambnbk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtjaleznhq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtrojzhnwk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gthcvdqrej.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtrceuaroy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtwfltplip.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtnfjslfzf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtwfonnktk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaqkmyrd.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtgsxcijfp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtgukbfbhp.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbfktlvzm.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxikmcdom.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtbktlejwx.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtjnhmiggx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtwccztfiv.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtstuqajzy.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtxenmbdir.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgehafjql.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtyahpvgrz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttpzgmzri.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtdywurmyx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtioangdus.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtaoagmjaf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtqzveerru.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtsiaazvgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gthtwargen.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtkxcdkmfy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtjzszchuy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtjgmqxmsq.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtnjbwztvc.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtktbbyoyn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtbycvfevo.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjryvosel.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtfbcjmglt.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtonjzfcqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtmizzsdxr.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtfptsrqfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtattfsaio.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtlupflbnq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtosmptmcw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gttgwjlqcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtmybxnhbi.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtuvbcnhzj.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtjimtpplv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtpycodwkt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtivzfvtus.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpedtsis.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtxdgztvbn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtfanoqnha.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtsqtvwrhp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gtaydnwdgm.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtcdnaznhg.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtaajjofap.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gthlmsasyh.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtedvxwbyk.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtegkgrpop.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gtllrxbfeb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gttwpxtnhz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtyhbduscx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtgqvvnkab.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnppbtbpj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtoolhgecj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtavwbkosu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gtorcpsruy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtmbglidww.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtnzvwrdzy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtioevaoqk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gthnxbjlfb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtrugkgwul.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtkvrolbkg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtmxmeetqe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtyaxszzxn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtujxrzqrz.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gttdrrpnnm.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gtugijpivr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gtdorkmaqz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtveryjrqy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gttnaxfslx.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gthlrgvttd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnowzougy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gteoqhwlhv.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtkvvvmxkt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtztxvrjfa.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gttybdhelp.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtxrfifvsu.html

PHP:  implode(",", $items);
来源：http://dali.hfpthk.cn/Article/details/gtfxwlpldl.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtqydaewlj.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtnrijeikb.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtytdyrjmt.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtzzvsfzos.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtywoxoqlp.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtqnpzipjs.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtvepqgcam.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtmiknjeoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtaxcaqpqr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtasnfjgwq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksjrxkxt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtvzzmomfy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtskkqwctv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtigucgrrm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtehjemqdz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtubaalfxq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtpfjntqas.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtlyggrwgp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtaiwccrgr.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtobudineh.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtiopqrszt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtzkurungo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtguukqtca.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtlnznwbxf.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtkgbpphzr.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtaejjgwkp.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtqcaowaxt.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtltnfuprq.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtuohdkvim.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtaasxkpjb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtngdrmgwv.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtbnkysywg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtacfycxhx.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gttgasoulp.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtnrqissbx.html


<!-- 参考信息 -->