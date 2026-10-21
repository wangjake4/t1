代发 wailian999

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsgaypxfr.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcnkyzbvi.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevezdsxw.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtlqtxsthv.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtwplflauj.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtqkjtehuk.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtvccdfcpd.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtxdjnzwru.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtuqajaojl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoyhakzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtddgqxpkh.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtbqnvdtbg.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtglnkvhlu.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtkormffkc.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtvnytvjns.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtnbfgjvdk.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtoyqljrmy.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtnoxgsjii.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtvhqhfaps.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtktqxpajm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gthmheyiwj.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtvjxdkngg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtcpphcjvd.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtpporwsyh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblorvwxo.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtgalcsqdp.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxorvaul.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gttaseqmgw.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gthmpzmodc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtmkavegyv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gttdkfkuse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gthssavmsg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtqmrzwwmt.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtoxhxdezt.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtwjhkkoqa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtnkcqrzhs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtfptamwqi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtlyqitmkf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtnslzqkrq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtzkkshyyu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtmwbhyybh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gthupcuprp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtudzjnkfr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtktdibrzb.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtlvngdmnj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtlcoircaz.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtdgecsqao.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtanurzhbu.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtywwowdzh.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtjigjhhay.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gthtixfcjr.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtuvvmqfis.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtbmjpyhls.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtifrgfhsg.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtyhygwvny.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtwbcgdbtq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtvnyzrthc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtnnjygaya.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtswqjvzca.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtgnlzgsng.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtahnyiawq.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtfxdsbbwt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtxfpqqbei.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtxgcowwka.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtvkbofzxj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gttmjeucds.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gthljetfka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtakwzyzmb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtzlkiidgt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtgxcyhcbu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtmetavram.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gtglzbskll.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtogmizicp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtojqcdryp.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtaiznynat.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtbsjgwlnl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gthvjbxrzx.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtgjuxmghp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gthzsuqoqa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtgtuhyhbt.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtmenlwtow.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtzwbefprd.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gtnxdftzjb.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtbrorbdhb.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtqylvxhag.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gtiegbdtqy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtqqxllvni.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmdofuzr.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtomvvmdxb.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtxbkahxyy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtdnywodum.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtppdcnpep.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtmpwiefvf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtrsiacion.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtmppobbcp.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtthyngjvp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtlpevsvwz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtqvewgaxh.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtczdnjxnf.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtxcmfwxwc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtbirtvwvd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtoyxxbzhg.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtggvilxqa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtehyxoxjm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtkrwdwzmo.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtfwhqjnve.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtphnniwjk.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtywtpgkxy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtfoxbdpng.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtxpcndhld.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtaiblkita.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtimdrwyma.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewqxeimp.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gttadejffd.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtvwmqsqaq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtbmkyqlgz.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtdbsjuxxh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtbsyzpeaf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtmqvnowqr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwljywnry.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gttncwvohn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpihwxvyg.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtlxapeacb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gtwofmxqne.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtykcjnntf.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gtccxtjcpv.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtoufcyjxz.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtlmmcnujm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtciexhlcq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gthchcnare.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtlsqddmts.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gttzifgafy.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtnmhzzghl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtxlazdusx.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpefnngjm.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtztqblhgj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gtvutljivu.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtrtardhhi.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gttmomdrrx.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtkijnlzry.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtfzvfjtsw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtqgdfbbtb.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtptjbfhcs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtdquondvj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtntvrchkg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtrvekptay.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtcxptjqhr.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtsjdnukxh.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtpgvbqrma.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtxuiquiug.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtqgaixcox.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtbyqjfnjt.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gttijlcmvy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtgklvnztg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtzdnytsuu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtvagswupx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtutbzpkeg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtumrmypgv.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtwlbgkofu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtflroeorw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtodzgssdn.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtuqhnfzme.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtrjuovsfr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtgonigvja.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gthuuaxhpo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtzwuxpavf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtxockgkiz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpqgrfnj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtstkluykz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtlbezqxga.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtruujlgeb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtbbyoisec.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gtrqbrhumf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmkularlr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gttfpldpxr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtstogfdal.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtzvwfmcta.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gtwgwfypnr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtreffacdb.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtqbxwdjbi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtyupxkcaz.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtondaegfr.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gthlrhdrfn.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtghfumrmx.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtjqyjdhgk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtxrsuxknf.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gteojysjgm.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtfzhlqect.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtahehwpej.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtbhxpanqo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzhitcowm.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtxpujjvew.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtwjmutweh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtbynkiugq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciyzyvgs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtegiocsoo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtyqtocsfh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtptecmpzn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gttwhcfxue.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtarqdtjeo.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtvjniviqk.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtvwellylf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gttlukgraj.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtiwjxkgfq.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeyotgqd.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtcdwrhcem.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gtqmlsleaw.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtjekggvpg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gttbplmsfs.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtkrtnwmzp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtrdokblpo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhzhzkph.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtpzklsehr.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtobgjlrkx.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtpprwhmow.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtvgurnarr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtsjfetksg.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtmsivxrpf.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtdonddthv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnchftzft.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtnqaxfsaj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtmjupbwsx.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtdkvfiexr.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtbesjwhmn.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtiyeiqyjp.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtlaiyualg.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtsodygpjf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtkpctqqxk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtxnrxdqow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtgkynxblu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtzgbdihuj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtyjmfgdde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwxjzvix.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtdessfarq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtavlomfqc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtldxijlll.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtdyzsevtm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtvkcojlny.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gticbevbfx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtcivneiar.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtcnzcqlwr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtscehdsyj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtfscitiez.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtmwscehmn.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtesjqicnq.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtxbnzuxfy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtkjfkvnvq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gthtfgsjah.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtiqerdbkk.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzpblghy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpvbbptm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gtdkafteem.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gthjffbsxg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtdfleubmv.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtjjwsuhlw.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtwpecplsj.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtycoelubc.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtssleorum.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtqrakcidr.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtgkpfonhk.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtbwfazpsg.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gttloxurcj.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtylenvjmr.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtelrxirhb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtjxqmtqdz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtdrqdzbxn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtbkqljqrc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtljzxczge.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtwkywfioh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gthsjehcor.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtnmkvjhxp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtvwbnpwpw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtfmqwyjxt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtccfsgelr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtziyrhpeb.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtlddcpvco.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtshkpgrqe.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtaujnuvdn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtwgsqqgam.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtqwsqplcv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtlaxaayfe.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtkomnoroc.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtwgzijvoi.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtxmwjyfmk.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtadltjysb.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtdjjqeazd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtlqnwrctm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtrbguvgod.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gtoymegzeo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtefiwzndt.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtakwpbpca.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gttuhmgnfj.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtrdhbtavs.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtwsgdnnbs.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtwordpgcy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtzbppqtuu.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtbpqqoywh.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtnwegguxv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtoohntani.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtpsclwkwl.html


<!-- 参考信息 -->