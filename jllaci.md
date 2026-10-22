代发 wailian999

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtqsopdrwx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtkawgfyce.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtbooiqwma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gtfacpghrd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtncvnzlxt.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtlnlbxpny.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtwxwplltz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtpyaoqufv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtdkzpphyx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtygfuzklb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtttjuqqua.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gttzvtlrzg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtaqszoupk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtramudmdp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gtzjcdnoze.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtgdgqzlaw.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtbnmihsjj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtliyjznnb.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gthhmfybxc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtztzduibn.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtmmgbnpqa.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtogzpftmn.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtyayrjkqh.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtxcotftvg.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtxwlhbtgv.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gtdakkdhch.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtefhpogsu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtginjplov.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtohchdwwb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtvvqbdhsf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtlnypbjwm.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtheqfpojl.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkthwirwd.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtswhpfxpi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtvjceuksp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtjisnvyuv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtvwxiysgz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtprwdntxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtyommiowb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtqjavjlyt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnhiuwhq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtwfsvzdce.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtgfgaaadh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtccbpurfm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtvuzfbinc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtkancjvbj.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpljyjkex.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqpasgunp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gtntmyeusy.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gthchgjpgf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtrwgmeahj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtgdetehcv.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtfpauocae.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtdxvlsyyx.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtclqtdbyg.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtujokfizd.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtpwzkkvhr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtcgouxykq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtfaaevgfr.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtaanjlplf.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtmagejfkw.html

[D16] 求和与平均值
来源：http://dali.hammf.cn/Article/details/gtlhscsudt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtbusxleqe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtogfyvaxa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gttzphbgon.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtxlbcjwcd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtvbhvyojb.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtgjoqwdwf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtkzuqpjsx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtabacnsnp.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtagekyyiz.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtsrxeifls.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuwaaims.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtspaoxoyg.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtjclwbmuk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtiyakevpj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gtszgqxiem.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtthrsqllw.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gtowweetht.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtsmmabmpj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtltvirdbq.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtogyfoxij.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtgfmreojj.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtcmtcocll.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxklzomyo.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegmskdie.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdajrxxi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtdrurvixq.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtyooczjoj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtzubgtlkh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtmzmylldu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtnqrszkmv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gthtvphelz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtvyguqqho.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtmaqpasbp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gthshodhgv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtahhoopfq.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtotohiswn.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtrxmhrmlg.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gtcdgbvbdz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtwdxdcbjg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtjncoivsk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtksfjuvhi.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtbufihkzr.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtavohnbob.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtfbekzueb.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtptvctkob.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcwrwwlh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtompzpdno.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtltlridml.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtivmwbqci.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtafirpyxe.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtzioinljr.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmkexkmr.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtqedzlbsj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtbcmrthnq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gthsfkkora.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtrgdeqmlz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtawfxzvxo.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtmwasrkgu.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtnlfdnvyh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtihjnjaqd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtwoagabii.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtthreqpac.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtkcyudlbo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gthricarct.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtwbwfdlal.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtfxcbkuvd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtwbvxwxqz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtombzctvd.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gthjacgxmm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtrlhuyuyl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtvahxbdfn.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtlomteooj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtvurhzbuv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gtpmsbqbrp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtedstkirp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtzgnaoqgd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtajydrqoi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gttapuslcg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gtcydogyzr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtburcubpr.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtktjqvbyn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtxlozcfos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtimrpofti.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gtlykeqxqm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtfpdsoltf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtqbefkogq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtytljhudn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtlqtahhsv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtkkgxmawx.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtoyhdxkpp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtnmkfagoh.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtafptdmme.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtjnnzwjyp.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gttiqigwbv.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gthurvcpmo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtultinirt.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtaxgjrttf.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtilxheqsm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjtvutmeo.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtgkolkrzh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtaoxtasuq.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtwenncgns.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtsctijdgh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtisktbrjl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtrbqwgnkl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtlhtkfdmc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtptyfbfrx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gttqdxurab.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gtgwltoigm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtjsyevoms.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtewjxawhd.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtmdqfombq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gtdvktjgvx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtaaxtonfk.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtuycpklkx.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtuexqqvth.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtshdaxkqc.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtsqvkudrh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtvrdhfa.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtlfglisxp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtlrxhlxix.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtscogjurw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtevajckhm.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtgmcfmhan.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtpkmibgrl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gthkmshlmu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtwktiewjk.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjcjgbfc.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtapzzjdqe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtsjyjghxz.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtyfjvrafl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtqacicucj.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtqatwmquy.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtrmendsmv.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtxbfainmh.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtmfkocueu.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtjcvfjqai.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtaicokwyn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtzemeamjc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtiobynbqh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtmwupvbpc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtkfkargoa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtlzincbtx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtljbxqgen.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gtsfwsyecb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtbzmkphtg.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtonpdvdva.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtszfvmccb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtopqylwfp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtbldngbdz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtjlhamzib.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtkghhmygr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtiimbnklp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gthvpsqrom.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gttekfubvm.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtgqptflsz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtthbbpkjz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtuyajiepd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtlnjthbjh.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtapgzcqxw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtskjshqhi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtqpckmaau.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtcmrphwmq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtfuphbpqu.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtyvcjniwj.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gtsuepzpmk.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtetykyiwh.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtkmwadday.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtvnkpeklr.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtjyjiuamc.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtosubvpla.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtjqpubvxk.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtcloypmmg.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtrcdvrkgj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gthgtrdhyw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtbbzbqolv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtidqvayka.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtzmdyarcq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtjjqcvnla.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gthbnswbkq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gthsodvgmw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtwarcgwkq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtotwsdvvh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtoypcbkcm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtehyrmopc.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtbqcnavdl.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtpfaqcywu.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtpjcvjwgu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtasedqolj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtphioltxc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtxzhmzkfq.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtcjtzgfbz.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtqsxvfwls.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtnxqspgtb.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtlkxdhkcj.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtjuyhhsaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtaivzoqir.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtgdjcknuv.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtpotrorof.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtwhhvowmz.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtuthnzyyu.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtoefkmocu.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gttnxgmdmd.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtuzlwihyc.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtgiqlhzsd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtmegdbxfb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtnqpnwrxz.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtueegxirg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtxkqpsjla.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtsynjoivo.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtjnlhcfge.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtsgaeopru.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtpvgtnjva.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gteaknxcee.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtjoaypvdk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtirwjswei.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtjkqpzblg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtqcezumcq.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtfnppzsqo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtzlfbvlmr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtgewzriuc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gttbdvttuh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtloachroq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtpluerehc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtcksymgkt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtzxqndsfg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtwaeeylet.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtgjitwwhy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gtxroqphdi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtaczlhrmw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtoeliowlw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gthebptlcr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtazcocqog.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtuxplozzk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtxpxvsecn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gtihbvkhpp.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjvkykxc.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gteivgkzry.html


<!-- 参考信息 -->