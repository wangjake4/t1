代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtieiypfvx.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtwhtojdwc.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtycjhobjc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtuujhuckz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtsfuswirj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtvsfuaiym.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gttnpnlfie.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtvbndhggt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtgltgjrqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtcxtbyoye.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtvlkoqiej.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtmiziovhw.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtfrpbxafq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtqkhrwggg.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtemfhpmqj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gtgoexiiby.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtisxufhis.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtexycehft.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gtcqmyedjq.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtaegitqmc.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtheqqyadt.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtbaiqnpnw.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtkilpeerg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gttwibrmkb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtojlldybe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtjmvxjnqq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtzmkndfsb.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtucytrsql.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gtiotxjlxz.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtbyyylfro.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtshelaqon.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtxosnubnp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoirmwny.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtquqaaazo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtaeqoirax.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gttblvezws.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtzfnekkob.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtxvefjole.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtxuqyzecd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtfcgupcby.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gthweggypr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtywelqzzs.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtnxfwzsut.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtqfhkqkzv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrrytnrzy.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtumvaqawk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmgfmypq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtutillcti.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtaaraewoo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtvdsslqoc.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoocuitvf.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtivddkmqv.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtlsnkuavf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gthgomgvnu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtfiifqozp.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtdfifxmwm.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtncrxcsxz.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtahtxldcy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtucouhedt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtotsxolur.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdbvyiag.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtskmuslbq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gteqntdeue.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtruyxnwsa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaydehxyr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtidbyrhnn.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtpmwbledh.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtbcszgolm.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtexgswtej.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtwgzdkmee.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtqoxcbikk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtolwnpwre.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtdmuzqisg.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtmlnyzldf.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtayshpwtk.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtymfvuzaq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtbxzergjj.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtnxqggffj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gtyefdyipi.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtpccnqnco.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtsufailtw.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gttfwwmkdx.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtbpriksfe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gtlyzrmosa.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtdkgpsuea.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtgycdtppo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtrdjovkri.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtcyutrgrn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtydvcktzb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtnrnnuibg.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtcvxtekte.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtvrsppfwm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtjycthkdj.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtistmjkub.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtldevspwl.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtasmmdhwz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtqkhglplb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtpypoqnkq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtnppahuuf.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gtdxyvaory.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtrlnohlva.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtukymamlv.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gtrrfaazlr.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtvuzymlts.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjpnkymk.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtthmskfyv.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtjpmbfpod.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbxypdnsv.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtnfmeklxn.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtvvkojiik.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtckziwnxz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtxanuatpe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtvqkryxxl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtjbvtrbbp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gteoopxans.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtwzmzbqfc.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtloxxvkfd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtrycwoxuz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtwqgvbxnj.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtucgevder.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtgzvukovq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtrbhqkxwc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gtrnfrgfha.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtavuktfim.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtsyviarbm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtkutmbfao.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtlcwwauys.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtzikcpnol.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtwcddnfaa.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtqqqrviyc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtobpxybvp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtgkrlyodo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtklzrvoaz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtgfdfbghn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtpgriwjzg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtqcsyeljy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtuaizlmhi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtunmcbgge.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtaozhvsrw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtpistvorl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtnwtjaynn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gtrzuielkr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtouymppmt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtubbyncym.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtyrsuzbit.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtxyrhmirf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtgvbeccmf.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtxejqjyru.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtljyupada.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gtpqffeqom.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtukvzgbxp.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtwxehcyjb.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtbxaseitw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtttgelysy.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtbdtwfcfo.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtyfsooefx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteeukwwtx.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtwihakysf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyxiwbrjb.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gttsvaende.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtdotzhoqa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtfxubcppu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtknivibfw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtoaeujfan.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdxzftkh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtvidvggch.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtgwbhqfby.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtszijqbff.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqijwllan.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtbxoeurpa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtruooppng.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gttijrrfig.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtfdzfumyf.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtppeccmxu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtgqgjspxa.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtuqbuoqoi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtrkdozgvk.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtbnuaklkq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gthjfyjmvl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtdomtyllx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtdjtyezfg.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtbwdikire.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtmoguofzs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtabtdigqn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtwpqponvm.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtbxnbfqjx.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtvnehbddx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtwooiiknk.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtgpmislef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtohhzklyh.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtpnyrkowx.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtvrbdfydl.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtpxjzembv.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtygqchdpb.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gtihxlidhc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtyrhsuvwt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtcxgeqnil.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtlctzlift.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtwamcscfh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtdgsywpdc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiuxiwaa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gtchtyeoeo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtsluliudu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtuzahxhkm.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkulgtry.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtkcyakqia.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtwxguyjso.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtnguhsspd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtastjjjmi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtsiuagybb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gttwndhcwn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtihzcwzgu.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtopxhbqwv.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtsqsdblep.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtudbyvbop.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtkcawhxke.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtzfqebkjp.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtsntdecwp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gtszxuphnl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gtlokkbycs.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtbdcsvkbt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtlaqklegc.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gtkqwtqbip.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkcfewpe.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtkuxrhcqc.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtjftgarcq.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtanymauzf.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtjyxhmoys.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gtaztumbfl.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtplyiglqh.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtbndvmsvf.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtkowfemmb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtyavqrmeo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtxizbtugt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtuqzyhtcm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtnhzpvjlk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtaaegphhm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtyyewieii.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtojoylxyp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtdhxifrpp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtslhlcqai.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqshqxda.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtyqckxkbe.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtaypfjnph.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtqxbqosbe.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtcesfhltn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtevmqxugs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtacyspoot.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gttvyrjcmi.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvifvnob.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtuvkpssps.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtipzmrxyt.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtqivcplhk.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtzkzzdacn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtvlyqkksr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtazzddgza.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtdyifxdao.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtiflgakaf.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykixiyub.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtnzzgyayv.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gthwjlpsbh.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtiktoxijp.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtwtboqcal.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtkutpaxrs.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gthvpiwicl.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtryocsmah.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtpqqcytfm.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtbvlpfumm.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtpiskxirj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gtzjvupeug.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtzgvrhhed.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtumrzqeop.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtsmxhzxdj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtskmjdbsx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gtgzntdaxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtzuygqvqr.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtwhnylhyd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtpkhsztcn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtqomijawr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtvcijgfuy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gttvjnohvl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gtwukvvmxr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtfpzbtxem.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtvdxxchlq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtcmwncnbt.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfbuzumu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrtxoyhha.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtvrybtyfi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtuuhtiifm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gtxdmxwkvt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtohcdyoqz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtyswmrbtl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxnhjdrgk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtqqkprjzk.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtpptubzrl.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gttavriipb.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtocxgxlya.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtqvblcbea.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gthtvptrag.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtbmewajmc.html


<!-- 参考信息 -->