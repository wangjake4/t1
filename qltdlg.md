代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtkvtgkngu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtiskududd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gthbwzpxqh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtpfoowjzp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtfraqxhgu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtxmkgbqch.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtxfqucwrg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtrwlobtea.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtghsqwbiq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuchkdgj.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtchrvzbin.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtkcbzjnrf.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gtbgsowebj.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtbfkpmgao.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtojmjguqt.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtqafkwuct.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtbihaypqz.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtpoelvdmk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowndqvqk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtecprstjb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtykgaeyup.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtynvygomb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtzytifmlr.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtxlaadxiv.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtefiaualh.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtykbbczam.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtbelesyjq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtbhntdgde.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtpdjxuhmk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtjelhyjds.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtupdzzsgb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gttpgrcbaa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gtwrogfads.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtzscndaek.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcecgloz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gtbofuokaq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtdnisvmxg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtjhfawbzq.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtphubglrf.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtymitibci.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtjcreitit.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtsflqezdq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtvcdwwxhp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtusjokmbd.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtbsiocdqu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtowlpkooe.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtpfbhzviq.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxcvyxxi.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpugchdtg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtsucbbtao.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtmxwjeiff.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtevrixqgf.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrfbgeaq.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtvtkvkkev.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtvjgmbrhv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtvapnyxob.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtxygnycme.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtmtsqenzf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sysykeji.top/Article/details/gthfpxwyjr.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtzsvgdbyp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gthsdtvirf.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtoiqspfyp.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtcrsjjmsp.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxymgyawl.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqqgnwlqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtvilvqnct.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtfsvsgxvo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtxbbrehzc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtqubjbftb.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtvflwvwas.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtbrenocej.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtkwrtsdcw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gtkyafuyou.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gttxrvcoat.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtfjahvwaa.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtmtidrsea.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gtiwqrxwmm.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtkklgppaw.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtikfpzevl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtdgpikgvn.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gttmuiossq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtnxtymsxk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtyfrykzwe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gttdmvbydu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtltycqcls.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtcrorkphs.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtqnoyfjzu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtwwmfyhak.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtcbwuonhk.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtfjdtelcv.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtbehtqzxz.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtuulmekmc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtuyxnrqty.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltjxpeyw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtpqejyykt.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtwsrwfrpz.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtzwbnagwz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtgjdgwsrt.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofubocje.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtrbqxbnrj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtbklkqlxw.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgrywtjy.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtaqawdvyb.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtorhvnmni.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtevzqmgzv.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtxggpymsl.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtfthbuonb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtjantsfsa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxksimhfj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtnvjmjgua.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtkjhtmiva.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtptopeqrl.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtgrzthsav.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtqcacrfqg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtltoxxjfe.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtlowdolsg.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtvisdbmaz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtzfzzqilr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvdtmjgm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlawmiyys.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtgeeqkeux.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gttfjnhcuq.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraxftkqf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtqygeahbc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gtgauewuoj.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtlnipfisi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtxmaenexp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gtxsmkckul.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtwrczemrm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gthsdjpmyy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtrdasaxyl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtwbcgwjfc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmqnybzk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtcetawiad.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtuwpqraui.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtcifxeofr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtxhengozk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtsvvugyzm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtkzvkeqae.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtlmzftkuf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtfalbchgc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtykojbgyd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlvtuazt.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtzqceiagb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtxmwhjgcg.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtsquxtley.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtansmzboi.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtazwkyqkm.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtmhichuzc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gthscxkdua.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtbmryfdbb.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjvxsipe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqdafotlu.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtzbkteadh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcdtcqppe.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gtcvftcadn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtctqjwfvg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttrhgyspy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtxtoahpez.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtqrkzxjzk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtiarachmx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gtzpeftdsd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtpzwqfpgl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtejwmryhy.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtcvjolswj.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gteaauepip.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtbpefpqxg.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtglthwddj.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtzsmnhjjh.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gttjxphsti.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtdzecmtgx.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtfbcbnkrs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtftxgtqnb.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvqlttnr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtrdanidvf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtaorfsbis.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gttgxzdptw.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gteydifpwn.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtkineikfg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtiphxagjw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gttrltgnlw.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisdguxez.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gttzufbqoz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtnfqwdryk.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtondywvte.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gttfrhcxpn.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtmidwjwzc.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gturkoldjh.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtdefwmjva.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtsmvsnnep.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtucgcgaho.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtdklamwte.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gttebidgwv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtlrlleswy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtplevnkgs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtglezxvsu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtwroxxtek.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtvrwzhtwi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gtojegggub.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtkcnbxleh.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtuvbogpxa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtvofwzxdd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gtpuovomqj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtosyaaxca.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtpkdxwbjj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtfrcjqfvm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhoawoxy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gtmjjtotau.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtewttixba.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtqcojecwh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtjyyxgxjt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtkohmmwfk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtyghqygwv.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gtsfgwaidt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtiirnzpqa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtjobmrqzl.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gttrzuugmh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtrutubeze.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtcaowqsql.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gtgspvmumm.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtpkulijpi.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtlmfsdnbm.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gttnhtqwvb.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtewolaeih.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gtexhaznnh.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtjdmqqowp.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtbmzbgzol.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gtzgxrnvxu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzoarawa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtwksqydqr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtzjyukxzj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtkbrxieiy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtpzzvsjqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gttwesvixh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gttbdbxqdk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtyboewkdi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtfhjzzium.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtuabiaihw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtaqxcipyq.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtayvqjhkt.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gttvqdtbzr.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gthvqzklvp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtxsicuqqt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtluoyuicf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtrrqzntcy.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtqkutwumr.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtdojbwewq.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtdknwtrqe.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtbredysme.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtascpfhho.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtrvzqiovb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtrwqmkobc.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtvxyyczvj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtssfqdorc.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gttpjmhubf.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtevyptilj.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtzweblbym.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjpjqnvb.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtnomnclds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtwulggekf.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtsltqdana.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtfuxbozii.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtfdlveadl.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtcgwikgtk.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtjaajdzbi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtwiwifehf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtbbmkmbbg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtilxcbats.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtywcfaxpc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtbjfexirm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtxomnrzys.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gttjfuonfi.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtdblpveic.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtnpvbvdmv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gteutbfuzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtumcclixl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugispjtc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gtqzvxluzm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtkawdutvp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gteuellhrb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnkeokau.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtgbluhmxl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtpkdjbvjw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtzrfipibw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtwfmoksnd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gtjiuclhhr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gttqtjupsa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwthupvfu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnaydobkm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtymnuofoa.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtoaxblfsj.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtuobaqbmn.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtnlfqypfc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtujyusgoj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtmbazbqcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtjqtotjol.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtcxmckvgq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gttkjbrprt.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtzoyzrkkf.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtxhdbziml.html


<!-- 参考信息 -->