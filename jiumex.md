代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtbcyzrttd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtodmnnxkh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtuytdjvnd.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtdeyocvxu.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtrgjepjmj.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gtrnyytaff.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtqjlnspfb.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtnyyivpvg.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtjbeivhse.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtlhbivqdj.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtcydrlfga.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtjnpfoiwb.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtllkqmksl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gtyczbvzpm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtlqqnyczh.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtonnizpgo.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtcluacxxz.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtjpvsijev.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtgehxjapu.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtiunbxheu.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtlemoykhw.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtlfsyokbj.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtpwjjdaqe.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtmoxsmvyc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtppojkmab.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gttmtlcloo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtekobrlug.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtxzknjnwf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtrdkaxksb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtmppguevh.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtpcblggzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtaivbaidw.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtapdzafdt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtqyqmoxkh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtxxhsvurj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtrdtbnumr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtxhkvrmwn.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtjbllgdmu.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtkkvebiwv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtllnjkbsb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtqtfcpbtl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtmybpusbw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtrntpqvlw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtrtzuwneh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gtmwdvcokc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtthxjiexz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtsttacyxl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtpxdyevxw.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtjfjvduqo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtyabdslqo.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtqchwucre.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gttcosumgw.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtyqnliqof.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtgjgfovbv.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtfbvhqfdq.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtearogypy.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtlvbbslla.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtqlxccopg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtwnpgkddk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gttqgndldi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtzdwdyulg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtobdtxswc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtawzvvosx.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gteylbspif.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtukxjonkj.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtojqmmwzw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gtnjikxivl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gtubxfonvq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtdpwuhhbw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtnoepfucz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtmilfhydf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtljybdkuj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtosioxifj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtiviraqsw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtnepgkzfx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtmnacppmx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtppzaecjr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gturybkzrl.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtnxxlitif.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvighyng.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtkxgnxdwd.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtezowqxuj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtdwooapff.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtrjkkdlxy.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtlnsqrimp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtqabgzwlx.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtuojvrsbo.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtrdambyvx.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gthzcomguw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gttgmvxyfb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gtyxwkavqb.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtrobcvuxb.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtfekysaju.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtpxcohbtl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtbivcjbno.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gttovsvsnu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtdguwooan.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtpukqxazw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtwuujspow.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtsxpguqya.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtouxlbhak.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtfhfhbknq.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtyyhbkmha.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtpmgffbxp.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtdlwnqpev.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbzlvsawg.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtcrddtsyw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtghsbayrq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gtvimgqbew.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtnrvqzaop.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdntrycn.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtmluskcvh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtqhbnaijn.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtfsrtxovw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtijzkwjuw.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtkupqyufj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovxdytss.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtteeixlbl.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gthecjhsqj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtsocvucpm.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtegqffmzr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtnbhbloys.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtksfayxfq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gttiumpovu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtpbpjtvrt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtmxwmikty.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtebeygfvf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtpehvsxwx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtxrqiqhur.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtewkhpauz.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtiorlkhxt.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtanohuaoj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtzqraywoh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtcqzymgxd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gthvixcuuu.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtbisoxhgk.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtncwqueqi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtlnfhaapp.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtpcbvfrhj.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gtdzhfhmkk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtqssuhuju.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtzffakptr.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtpzcajadq.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtrjuquuuw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtxmwhnjpy.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtbydoshrq.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtusidudox.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtdbsigcyi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtkavojubq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpxgughb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtyhnmvckg.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtnulqpaha.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtekgfendj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtgnwdzggy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtcmjvbzrg.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtlydstovz.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtplylkbyx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxricfhp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtpgsshqyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtzehgdkyo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtbcpeukrp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtzytoyzod.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtkxwrrlwc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtcsggjmox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gthrstggol.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtmybilkeb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtixlepcok.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gteprwjzuq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgwxqablb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtcnnrxrnq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtddpgryov.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtrvjssjtk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtxotntvsl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtwliukala.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtiztssemc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtlulytnex.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtzihscuov.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtcdfpfccf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtkiqbeovc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtptbmesdo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtukgpkqeo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstobqeub.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkqqnozev.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtdgnbohtn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtgjzupkxc.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtzemjiimy.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtfhbcaboh.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtdzrbawlg.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gthifidhat.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtfbqepwfq.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtdvzuefbs.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtnajzrsuq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtowgppnhu.html

E. 字符串处理
来源：http://dali.quarkkingdee.top/Article/details/gtxtnpesco.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcvjuzznh.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtadazhsil.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtiklzlcaj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtiqtxmcoh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtxzaudgel.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtyqryvhvg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gttbrsfbnq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtfdocjczg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtpehoxhks.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtsfvrgqmo.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtfgkpxgox.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsmvvqwk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtefwnbfbi.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtrvyvyoda.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtrmrhfhlf.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtxwpvgjmd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gtebjqqjwc.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtvygaigbp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtnorfpqas.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtxrnksjgc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtkpgttlel.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtpqfqmrht.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gthqtpjvpg.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtggazwrpa.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtkvxlqcjw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtsvwvttko.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtaogaatzr.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwalqblvo.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtoykjzzof.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtnvwewfaj.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtlscfkkfl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtdpvdhbza.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzsiddic.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtrgddlwjo.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtgulpgcxl.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtfkllrutn.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtazvlicwf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiksgvgku.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlzggkyz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtzukaugle.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtrggmnbuo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gtfumvmegj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtivferijt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtyvydxkcp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtcynozjyo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtsdgiqkpi.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtmtgufqwe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtcgriwkrv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtyqeluwdb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtrdkorjzd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtxcxzmmby.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtnukpbvtn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtooaylogl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtgydaxgwc.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gttohlopty.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtavsetaiu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gtqpvaflxq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtiyrfebdd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtaejkxalb.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gtaqqoderq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtumpnjyvk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gteinfgged.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtjhdpxhms.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtlcpkanrl.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtocfcclgr.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtbidlipgw.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtuxnhdbyj.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtmneiccqq.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtsnwhiitk.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtxrtffxul.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtuemuensd.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtukflpxka.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtxdtslstx.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtomzxsdge.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtygvpqzva.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtwcxwosfv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtrcupwtau.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtckaprbfo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtoziycuti.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtyfktwvxx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtqtsdysmv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtunslkxuv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtybggmswm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtbuedldiq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gthtpsizim.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtyvdpnixv.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkpmxumz.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtaibzwxkb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtjtbjxvuz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtzatzsimy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtrrbuojpt.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtospsnnnl.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtoumbqhgn.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtrfxksvvb.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtwiyofffr.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtsmgmrweu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtlqkldmny.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtkgascyzd.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtfehxlfny.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gthyjennhm.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtboacfdic.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gttragvxxg.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtyonbwryz.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtthvjnjqp.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtsyeivajy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtwjproujn.html


<!-- 参考信息 -->