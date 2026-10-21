代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtajdzqndn.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtinsstoir.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtzxvpueyr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtwlaqtuel.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtkdmdidvr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtvhdizslz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtitkafenq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtskgyhxht.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtsfahjyrs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtbkuzlnbp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvnquvqx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gttgftubnu.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtlvhxypqw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gteurcdyqb.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtwuqcxukm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxqldqjm.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtgmosndtl.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtclizwpht.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtkikkcpoy.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtktsbtihs.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtgrqgfqdk.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtwgapuegh.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtwmuyyqbl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtiaujzewz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtwgcfdkfx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtadzxhlrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtacqruelz.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtszkzzqhp.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtwaijbduj.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtweerwalu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtunrlyevv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtgbamvsld.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtovzqlgwl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtdlzcfxwd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gthagzbcbt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtveumnooq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtkexzicap.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gtmlbnaiuv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gttodpussj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtmdholkka.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gthpxohssm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtcnftabnl.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuezukddh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtkzwdryef.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteujricsx.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gttrmjbrsz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtbauaihhp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtxmpqbmyz.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtqaqcxffw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtswzsrquh.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtmtrhlcvy.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtgpkudcct.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtxltsnclb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmlvkmom.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtgavzhwfw.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtwqgbreqv.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gttdhrbanx.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyufqgsi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtiarfyhjw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtzkwysgvv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gthayppfbs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtuaktswxd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtxdjtfbfm.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtmklhnxir.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gthaxvpmvy.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gtzazwifzc.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtfptwdsff.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtwhqhepjb.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtwljkdens.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcmtapdch.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtevltddpg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gtqyourxzy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtmwqlrpfw.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtlfwtjbuh.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gttxbsqpuv.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtpkluakmo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtdmiueeyb.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gttywdbakk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtjjxhfqzq.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtupzfwjgw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtknmztqvf.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gthgyquayk.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtspaiincq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtpjxxeoqv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gtylbsmrga.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtlwmatshn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtyennkwic.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtdkbcsopq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtdevqihtq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtacjhrcvu.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtvzkixdvi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtorbrvesy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtnegiicri.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtlszsqgge.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtefuzdgni.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtprrzxubd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtaotwwotf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtrbwenupo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtgztsskvj.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gtbzfjziew.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtmxtndxpj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtawpjerdk.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gturjbhgwp.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtidwiorkf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtqsdgkwds.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuvjkvxzs.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtqbfdmnxi.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gtodjvptbb.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtccvtcbml.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtlhcxgxes.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtiqsmhgem.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtawhfqmvf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtlkfldyjw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtbbeaqvrr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxzbaobev.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtramnpnmz.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtbnhxczcs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtweumsidw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtgrorxcsn.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtywisxyxb.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtabdhlohc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtsuvxpjxv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtqpclhvow.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtohdrdwal.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtddgntepq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtctzdkokd.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtbhzehgdq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtqcerpiai.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtcdwumuqy.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtbameolmt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtnblfdzaq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtktkrygpp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtionkdqnd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtotsztldq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtnsgiusmn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiufrcvmn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtqhvpesxt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtsuowlgfg.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gtjzxjzdje.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtserbphfe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gtmrcuxmwx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfibkippo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtxmxqkyiw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtpfjraqhe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtoagsyduk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtprdarepn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtwhsccuil.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtbmqkuswi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtxmatzvyu.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtdfdehsoq.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtbfllbuqm.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtmolfbdqf.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtkqyrxlgk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtmmnqbxjt.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtiqwzymql.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtmaniyweh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtaxhkitsv.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gteiofwmsk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvrfuiak.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gtapscbgfx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtlglkazjg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtumkjoqbm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtpmypyrdy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtgfcsyhwq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtpegxftyi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtsrdqxxcb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtgfpcxpjy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtidtbjczw.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtfkaeijee.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtzxknkynd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbrbticz.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtwghqpslq.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtbrmfjrkh.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtshgunwae.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtumzzbqon.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtaljyoirw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtpacanpzd.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtouvujkox.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtowumerni.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtwsdlieij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtidnftvyj.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtffhiegty.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtfnhnjvsl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtdplqdkhs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtnelvzzgx.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtwphlfuzz.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtchgbcqno.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtksmtgzws.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gticyzdgml.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gthsxpndqo.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtzqmeypag.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gttawzddvo.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtvizzmshu.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtuwkedikr.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtctbzahwu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtnxbsdztb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gttifxoszg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtzhqxniyy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gttamypxzh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtewqxturz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtybgieyue.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthqvcjyu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtlcstqadn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtqyidemxn.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtlypjmdbv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtwzgoystx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtmibwbfvn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtsqjqwbxr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gttrgzyxhv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtqjlznibr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtlatssibq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtwtelhhla.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtbelvbmof.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtgqgoofqz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtwkbyelzn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtquonlgis.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtokpshllf.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtalkuzqoj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gthgmzzzmy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtkwfflxra.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gttakdaqtq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtnpmqsioh.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gtfuiezben.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiantmxfm.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtgaicyshq.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmkrzjvs.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtpccmqehn.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtdjvvnupx.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gttkgjavbx.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtipvcrjii.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtlrqsrxfj.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtnwurliks.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtkiwqdjwv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtdatxpigd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtswlatgka.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtigvpnxza.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtsvukwqik.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsdxmyxe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gttiaiugrd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtwibuolor.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtasvepxzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtvdaxqhxh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gthftcofzi.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtxrmjzvgh.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtqoxxyfdb.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtpsbkluyu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtvucbabsj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtfvapduxf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gtrnuvnkll.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtadgcvchx.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtwiedohtn.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtoeiqqmnp.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtobiyjqss.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtpmwvqgox.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtqydzpgbj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzmlqbef.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtmabrhpsv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtlqawatrm.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtnwgqevjz.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtevicyxgt.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtehiwfruf.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtxtvouqcx.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtbtcvayre.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gtvpyznarc.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtyfepqdyj.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtstjoachv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtlijvmeif.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtabrgsqdm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtnvdwfaqd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtdhequmjp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtxlxhgxgm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtnwqtfcwk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gtvqckugnr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtatqnfwqw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayttnxin.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtlptmwniv.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtdmtvxhwe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtrmrgqasv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtlrexzzrq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gtyxiaspat.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtsoayuapf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtfdytjcsl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtmpkhrtxc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtpoeossro.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtndkndflw.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtvbxcrjjy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtwxyiiwux.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gttfjgwnla.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgwxckoo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtabutflcs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtggupffmr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxacbhkl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gthramzusz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gttvqejoay.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtgxijworo.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtnlhgeuyu.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtoyjmcdmr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtxawggooj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gthpboqead.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtlnjtcuab.html


<!-- 参考信息 -->