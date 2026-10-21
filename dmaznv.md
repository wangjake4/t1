代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtrhyimsvp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtkwpwmzad.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gtnuvskvsn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtamimbeyt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtxwdktecc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtvajrsmik.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtdvtgeslv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtoixxezhh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtpqjfmmkl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtjkdnzuzt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtzweklkqw.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtuflkmvsr.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwliwvyzw.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtvlbjxcve.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtsgwhigbn.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtmxrcamis.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtglhpclmf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtlxlqygki.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtdysrocem.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtplipsfyg.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtmmbuvude.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gtjobnivuj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtlztnozpi.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtyzqlugvc.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtuosmwzyc.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtocnvawle.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtkrweypuq.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gteotsueqx.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtnbhysdts.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxkmzzwm.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtabmhvcsj.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gteqdqgjim.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gttmdfgvzq.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gtrehtoxfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gtbfsidcyv.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtadrracfy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gticusqtve.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpforasqg.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtmbyubqoi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtkwgavsce.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtmvluosnt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gteohxbupf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gttzifgytl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtufpnfrwk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtyhsqftxf.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtlrkduakb.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gtwgumsdyn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gtdmcmdhqw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gttxhiphik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtkkjkoeap.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtakiaoljr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtjyxijloy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gthjgkrqia.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtlhywrtdm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtegfejmyp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtydlrigeo.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtjqpvbnhs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtjnuwatlm.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtowhbapzx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtmendcygh.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtoniejdmk.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtzvrmokcx.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gtlmttwebc.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtnjrjmzed.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtitkxxupr.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtocfvdyny.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtvalqmgni.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtcrjehlfa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtjqpsxabn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtiyunodwd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtpapiavsg.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtmkusfdop.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtiehqqgan.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtmbwuaxqo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtodnhhrko.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtlquslqnl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gtycfzpkza.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtqhvtyyks.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjlspleo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtegxkrqpm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtwhwpyzff.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtauvivtum.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtftftmnod.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtsmcvemqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwvuhkvp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtcchkytbk.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtbhsspeqd.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtqjxsnmea.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtbsesahwj.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtaeoqkxgb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtdzjowvbo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtzucsfzqy.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtttxlqsem.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtmgmjrmmo.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtvnkhdppr.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtnwjmsfzl.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtjihlpxxk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtqrmfxqoy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtyioiflbh.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfmbsoyg.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtoxvaofgj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtlgybxbvb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtdozscqqy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtztoyumso.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjdupqake.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtzehbmfbv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtiqvhykkk.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtevqpgewj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gturkdqvck.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gthcmjjevz.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gtvezetfej.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtkavdpftc.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gthardvfjx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtqhagynjk.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcoeznbr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtvhvjofdb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtsjtixhct.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtzyltctix.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtueokuxki.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtwgbzhohc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtenlrwxaq.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnafvmxtt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtuuyodzuc.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtssqythpk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtbptmymvb.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtzexinbjr.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtidmhgiov.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gteagadjwe.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gthhwoelvq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gthoywrsbr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtyngeyyvg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtuzvillms.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtixaykeij.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtfvfdtkup.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtkvjenwvz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtdrclquss.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gttjlcnhus.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtlfikarvc.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtnvhjspzi.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtnqkudpnt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtjjtpfhxv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtkpcycvhs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzgrvpnc.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtrpnmheho.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtfvntwosn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtzxjzimyb.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtkkvvymag.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtpdfnpawa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtnhjkeghd.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwfvfiixh.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtsvcfzoii.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtdduhtqbd.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtfobdvxpn.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtnqvfwlgq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrytswqem.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtuenbcbsa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtslllymzd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtyrwrpjgh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtqmqcsjsj.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtixvuouty.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gthgsrdltt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtrnzdxftj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtbmtalbjt.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtrwbvrvkc.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gtvfbdzirs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbxefikg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gtlsxezoey.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtcgyvpdcr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtqpldlyhe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gteccnhjek.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtsgbpvovu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtyteggtwu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtqoojcdbq.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtqkxsmyml.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gteckmgfbv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gtknnyohux.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtiohckbrj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtcboegijm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtfksbyfyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtcrgcazqn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtwpnyqhgw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtfevocgqd.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtvytkojnm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzurzdwx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtivhfresa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtboubrgrx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtgpjiunnm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtxpcoskzf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtjevnovcn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gthkmttxhz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtkievcifg.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtlejnrcdl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtudkhrzui.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtoobsiwcc.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtkxvfbkkl.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtlmlugimo.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtehtqbunm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtdjjtqtoj.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtvpexbnsf.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtorafzjmh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnsjmkxec.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtwzyunbfx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkypcswdq.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gtrlkwpudm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gtuxlnwocj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtcbmbtmfo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtwwhaddtr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvheiakjs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtmudzwufu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtsftjalhk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyirqhsjw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtitnesthh.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtxsxrjveg.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtcsotmgud.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gtksatqlxs.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtnyavisqh.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtrzoquyup.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtmxbljtiu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjhehcex.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtirupnfiv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtmjtfxjfa.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtqqfjoxpa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtuyxbqbxz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtjcfwdtao.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gturmqbegy.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtbulbtihi.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtneqjgdhs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtgqgujnxe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtymcinrnu.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gthmigcgzg.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtpeqbbkvn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtpbyxbzns.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtdqlpgqkj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtaevjorfw.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtjfdqlrjf.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtmmxhzdbi.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gtonpxgczc.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtzmmkufey.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtvjwgcwpx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gtzefnbknc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtzzzlqiwh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtoagoxqtu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtkmwxbinb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gtvwsqjasl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtonjannde.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtssbavfyo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtekokmigq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtnmgayvyd.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtjkapcfvp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtauenzkup.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtrvuzmwcn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtltesdlcw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqhkxomdk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtjijjsycg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtdwaskqit.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtwkbwtaoa.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtedklkier.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtcgdyfaho.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtrygdfxus.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gteebvnprt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtxsvbamez.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtvocvguce.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtbknwmpbe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtftpxdjks.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtbtgtnmlf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtmtraemvp.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtwetgojrr.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtnyelqknn.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtmuxtqexd.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtdkgseoef.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtchqgnnvt.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gttddwjyht.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtunalxmey.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtgtejrral.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtzmcllawx.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtdfnxfojy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpfeluzka.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtevqrnrzp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtfrsxugkj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtqaqnhjny.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtgmcazsqr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtnljottaa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtmvaltwge.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtucbgwtdr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtwkazumis.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtvinjavim.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtkclavily.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtrogowccd.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtznshkxsr.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtkwfaxsct.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqnypktx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwriuvkam.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtewahwxzi.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtedlhuhzz.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtkzbfnawe.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtqojoxaqq.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtxuviaiwy.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtcstwinxa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtaywuqswa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gthwendcmw.html


<!-- 参考信息 -->