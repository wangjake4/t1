代发 wailian999

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtsrcnkvto.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtfaeuzykg.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtxjlglqcz.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gtoinqqqkq.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtnhxtkgcu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtojwwrmue.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtzmkixhaa.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtaghipggi.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtmluabvyu.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtsnqszyvi.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtnlsxiiit.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gtkhsjavhw.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtlcpuwssk.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtkqzszycm.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtweshgcti.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtjkbyfxsm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gteaawyigo.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtxmpeiqyc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtwzjqhsbs.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtrpocoxse.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtkhnsrptx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtrvehelit.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtgrbujjbs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtoralgniw.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtcuhdxejs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtbdakxpnt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtifyxtvpy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtzcvwelbx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtgcxxhdeh.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtklsxiykj.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtqfunwtjs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtvyzyekgs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtyjouqgas.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtqwrptrrf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosedoyqx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtouzkhakg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtqqpgkmse.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtgzbvfqcs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtienizawk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtqqyogemp.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtcuvuczpi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtixheoacf.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gthpuwklkb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtzijifneh.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gthgkijvml.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtsszurbln.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtwilzrrru.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtxbizynhy.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtitmlmqdy.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtkywaqjdx.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtnmlvetir.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmtokqclm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gthvvhvgwd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtjgribgye.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtcclqmztg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtuizywzfs.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtbpcmbuxa.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtdgfosrqt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtklrqdbjr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtmalakawy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtvkjyumnw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtpkywzuve.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdooenggj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiihplrzw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtwobxmcai.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtkesdiazj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmhkfngc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtwzozmdsr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtfpdipubg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtkewexkfr.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtjtvyzusm.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtblovgnsd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtycdaeddm.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonzthudh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtbdftnuzj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtyxhwnxkp.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtfusmedpa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gttellkyky.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjdlhzdek.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtspbpmdjs.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtjbhawpcf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gtulxdxuoe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gttvcaooec.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gthbirpnkw.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtvfcpyxah.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtekmfiyip.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gthvpdeyig.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtunpsnymw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gttnkmxrma.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtnulorolf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtchkljyol.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtmiqoosby.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtfcuctbat.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtydrgkdbs.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtnbgmbgmw.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtxckzfzhi.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrmnmgjv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtgvmfeweu.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gthwygblcr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtbhjjprls.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtzosuhodj.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtquktgqkg.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gtotwarodx.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtgvtrkjbf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtanvfsfud.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvuvsfsq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtziaqdsbo.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtpaoajuqq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtgfkenfjm.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtjnfzvpuo.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gttqiegewo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtdlpdwizx.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtkwpoqeif.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgfzy.top/Article/details/gtrzpliajk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtemlelbwm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtqfzpvydb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtzzxuynjv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtzusgolkw.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtobmjzehv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtphdocpiq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtjgadvhma.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtxrnhihod.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtbtozkbas.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtmnsazspv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtdndaqwhz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtfwuyekjl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtpvrxylfe.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtpyzzvnpx.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtfibzzyhz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gttgnbvzcs.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtmvfdytlh.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtcrsaxcup.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtwdtccjom.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrieslff.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtkxusakuy.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gtvtpdxvvn.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtodwaxaxo.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtttumqpgp.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtwyvdilju.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtbtdkbrto.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtrcllkuod.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtradswvsa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwrmtzbxp.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtgmnbgzed.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtxvarrohq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtlivqdrjp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtnbrzuowy.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtmvbfsbsk.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtlsiplnts.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtcsolwhdc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtxgsnvblw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtpddqktzf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtyzfpjoiu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtgnrxrzfb.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtugqaiqlh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gtqlqwifsl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gtezuaxxre.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaxgfmsw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtzfnikxon.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtzlzorjmm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtsxvgphzf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gttbpjulnb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnwczzc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gttddpygku.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtelcvunaa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtsaeiobpf.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtudaccfdr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtmnfdsuxc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gtmreczuxd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gttfsblumn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtfserjomn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmvcpvmce.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtxhyhigcv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtgkpsxgpr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfltkjhwk.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtnbpcudmx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtsmuwhyjt.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtvgfssocr.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtiqaowxmo.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtcnvlfntu.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtpxcmpkrz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtwhptajnh.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtbdpmyesj.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtmzkzgdcd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtauwjrhop.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gtksdxrxia.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwroqshsb.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtwlwfsxjn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtejmgoiiw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtnspijlml.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtyqzuehny.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtpuowqtwq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtahmdrrwu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtzgxfzzes.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtdgucnplr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcioxjin.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtaknvstnz.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtnupoycle.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gtbbadbdld.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtuiootqoy.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtqgdfasoj.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtotvdmhkq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkxxjcbmf.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtuhuqloit.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtziatppkn.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtvmirdjiw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gtrzanfxfp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gthwfbpath.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtkxgvsstp.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtbncykbfp.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtxeezehrv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtwsscbwid.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtemruqymy.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtaxutwboe.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtufyosgwv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtiurunank.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtkyxuyoqx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtcrtkethe.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtjavvworp.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtxvjzplqr.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtbmyvmwdl.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtsqbzmlrz.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtnyswsiqq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtfjsmrqtg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtywukqhif.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtblfiihue.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtybhowwoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtnjffuugt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtgzyucsys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtlqimazmy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtbzxesxql.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtzuguatws.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtoqkivxei.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtkigmslmt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtguwaifmm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtwgrggvfm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtryjmevhg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtxobcihqq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtzseebjtq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtutmcgfpt.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtdqzsetwe.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gtwcwkndah.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gthfocfdsy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtmbklwebi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyufxwwz.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gtnfycxypq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtamglcrfl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gteggvxdac.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtkgxpgssl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtuwcvbgfu.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtqbftdnly.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gtobpymkae.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gteeuobmdl.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtnevrqrwy.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtxbnnendz.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtqmbruwlo.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuswsucq.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtqncowjsl.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtqtrgsuud.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtdgmyjaal.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtvmdvjzwg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gttfjpdvdt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtrdyskuhg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtsyqxdcfi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtaseigwby.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtdequyvqv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtcdrvmcpl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtvwqxckti.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtqifexnuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtjylaonvm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gthatdzqbq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtfkfgdcyk.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtunkypags.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtwrdjpxil.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtyqhtitap.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtkiwsdsou.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtvesygohg.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtajcdrvtn.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtdwxgdxoa.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtguavxivh.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtzfkzcmbj.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtvxkvgypx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gtxizpawno.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtugdrlehc.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtcjnfklil.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtdpcryqhf.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtxpovtaiw.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtktifyenj.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtxpiqyoks.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtiezqmthp.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtptmzyknr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gthtmnkfkc.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtszsfldik.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtiosleauu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtlkndsjmu.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtbwyqhcfu.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtwicbsanw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtcyizeltg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtvhgezjlx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtobcylyyn.html


<!-- 参考信息 -->