代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtugkspwcn.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtonprdhyw.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gthqfrsmlv.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gthkjjbibn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtugvisgle.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtvlnafxdt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtaotgvdsg.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtnqpijlvy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtbenwxkhw.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtrwvgxsca.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtsjnusknz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtfrurzpht.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gtcrqnkgct.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtmteadghp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtfzjqdayk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtscfuwsbv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtrtykikrq.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtiisqvphg.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gttylonbdh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtzwbhysbq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtnonleixm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gttgvztsxv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtknfoldjl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gthrlkzcui.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtssvkwjfx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtlvmtewmd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtaarlllvq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtorzswyrv.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtopzgwajk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtiedfpyiy.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqwsswjop.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtucgnjpkh.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdzajkss.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtysmletor.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gttslqsehk.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gtrhupflms.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gttewrxunf.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtpfywcflp.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtxtouwsyw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtdiddxujb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtxmxbadlc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtcrkehows.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtgynmxsbx.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtvyutvnxp.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtdvjoszco.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtqhfgtxii.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtopsyumlm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gtwvtllipc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtbanzfdsz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjabgjudo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtlddaytvj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtbvqfjned.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gtytudokzu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gteyqgrlaf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtwsmpddix.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtghfwlyyh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtuyyiimyt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtrtzrzyot.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtkuarhfcm.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgfujrokh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gthbdwhjln.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtokubqphf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtvkksiwjg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtafslarvs.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gtdkadhxxe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtydtruumb.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtbswtqxtc.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtoqmmtrsb.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtohjbsevo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtqavyloyr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcppdropx.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtqfzdhepg.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtvdtwsrxz.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtksyuwcaj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtgihzrjpx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtesmgavuq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gthhfoojjm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtwrbbthvh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtjhzbjzin.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtdzwdnyiv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtflgbmscx.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtrelzqfar.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtircjhtzl.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gtihopblzf.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtmbjnxflc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtmaaneilp.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtckoidpsv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtbdzpukgv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtzgjjlwzj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gttplusgds.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtiucldmtc.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtmbvnkrbq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gthaomlctb.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtwibspyrc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtodvhrnuq.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtmadafvwz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtxzsdjaph.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtttronskh.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtcgelslfs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtjtguqdmp.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtmhkyueog.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gteoamhlry.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtnbrxnvbb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtahokajuo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtcgsxdrtc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqwgwbjq.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtnhfalosr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtrtngofbw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtnvacfkrn.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gthjeknqne.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtxewvifcf.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtancptnwl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtkelenxee.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorgdcben.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtubrhqlrs.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtsiigoins.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gtsjokzwuy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtpcxgrwil.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gtkjrbficw.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtgdjedmos.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtnjyiosvg.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtfmccunhr.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtavnlafoq.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtftmfxpqi.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtjbqkxskg.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtqvqrqsqi.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtvqeburez.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gthqldjlxt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwgidlfnb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtogtlkypa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtdldhvjvl.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtfzgtilpa.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtgruxczxx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtiynutvtv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtqlkwkggw.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtmqdredys.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtknsoskrn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbobpbxa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtwhdqpnfi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtrelcpbbx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtsfjbdfay.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtthvfaftf.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtpgiazlhi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtpodbrhyv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtwzlgqpgw.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtvplksyej.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtronudeyz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtdfaqoqsq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtyntudnoc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtoxygvuje.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtyytaspxm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtnvfallau.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtbsgkpnrk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gttkggwltz.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtygnlxawl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtwwkwyblk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtnjkiqvxc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtvyrhugbr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwntdovwy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtlfyxvrlj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtsqnbpxhi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtvstfkezj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtjmsjjtkf.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtmgjlckfs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtxoxgwtly.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtglcfvklw.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtatrtfziy.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtujwoouyc.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtxmwwqhbt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gtihbrrisn.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfcsrtrf.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtyxfkouah.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtthuvykzd.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtgctfzlze.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzclbexyr.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfaymsqp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtndwtlwql.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtxqxaahys.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtgpggtovb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtaputdsis.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtkeahzciu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtlcyduply.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtwfsyboyl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjcqysxbg.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gtnoxapjwp.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtpfxpusac.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtomkejwrs.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjitxfecg.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtuqjrikbx.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtwhkgbtka.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxgzmfql.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtrldjnjjw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gteilqdlyf.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtcjuuhjoi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtncfhggwa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtxxgkthxa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtrhottlba.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gthspxffse.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtnhpovuke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtutvkexkc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtbhywunmo.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtidotuncf.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtbfmcsbfe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtfizaqxwc.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtblsrnohb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtelktucfm.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtnrstuvmj.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuyllemb.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtpgexgpbl.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtppzgls.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtzslcmhgy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtcuobihzu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtkuxbvydc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gtrlusebhq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtfcozuxlw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtgkakbvbk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtvibvfwka.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtahbdlowp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtzrhpktyg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtnhvscbuh.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtqljcajvu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpplotmg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtrwqywuti.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtaysdaopq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtlprbkvio.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtehojfcdg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtookyrmwl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtoogmzbte.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtaiecedjc.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtqdokbgyx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtqixygjam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmglquboa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtzdrbwamk.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtzwigpxxl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gttfxbwbjh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gthilsnbdf.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtxxkuxrav.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetvxltzc.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtvvjlenrv.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtyszdeuax.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtxzkubnmd.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtbaqghctw.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtexsiamag.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtrbufqupl.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtatqcpgwv.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtsbjnlsux.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsiorxsq.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtaxowzzid.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtgifmcxpe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtvuoiniql.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtutjwmczu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtkxshyyci.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtqoazyrlh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtrsgaxoid.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveyejqxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtjedycbdc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtkkttbwra.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtvomohzqx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtanriyonn.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtbfomhbij.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtdvdyvego.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtoktdiouj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtieltvmqp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtzrkyuvja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtpddxeedr.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtzetqmetl.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtglfssqes.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtvpvmdmnr.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtppplxyeg.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtumpzpvze.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmmapuel.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtlxicplfh.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtmkyrktbx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtqkfhzsrg.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtuvfgxflk.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtyicanvvk.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtmrkmtbbw.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtptbzscxm.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtvbcviusi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtckzykgzj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddmqmflv.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtxtdannxj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtahwfwlmy.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtwxkbubqb.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtrzpndnhm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiorvqil.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtesuskhjz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtyzilmetq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtwolqlkhe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtduiolgwj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtxvyucxfk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gttbhggjwy.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gtkpqqfqqf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtlkhdzgjt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gtqsdxuwww.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtjtfkfxih.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtyfpajqeg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtsaltgesr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtjahipbds.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gtxhvoovpt.html


<!-- 参考信息 -->