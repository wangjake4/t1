代发 wailian999

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtihqhxobu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gtwumojmnc.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtotcnwmee.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtymmaomcm.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtxdheqoqn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtaceakvdn.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvnzewyj.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtsqajvcvh.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtonstuxal.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtsvnayaor.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtizuwvoim.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gtjabrvuzf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtnkqqsjjq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtqckjsqap.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtutcewocq.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtpqejhgam.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtlkonndix.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gthmvvoxur.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtzkdnixab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gtbwzpwvrk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtrjrntxpi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtyqkntbmw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtrxeuuuky.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtdyqufefq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtmrjvmvhe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtjowodkuu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtlpcydnsi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyulydul.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtykaxnpiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtsdrmxhlb.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtvfbcmrpq.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtwztweonn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtkiandlhw.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtxkulsqvy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtmezmelhw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtndiigcdb.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtlnovricd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtkelscejf.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gtdyeppwhp.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtirmexkql.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtfvcnoasb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtzyjqcooz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtgkeasaif.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtxapslrkc.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtfqyltbsi.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gtfhlmpsmb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtdixrastq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtffzzddke.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtglpjxedm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtskwofanr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtaxnngdwk.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtbmkiyypr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtftnopgus.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtwwxsdoua.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtlylowvdc.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhiwugdm.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtarbevflp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhgolnnv.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtmiqsriqw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtqqxpohes.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gttabbkazo.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtotkjzlni.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtetyzdxhb.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtdbvzdmbo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtccqwosyy.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtxpwwrkhb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtgkuaapxa.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtmlaaaotj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtceqbqfar.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtiuhqstlt.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtlngzfigw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtyeagivor.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtzdfvumtj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtgyvrinzc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gthyefozah.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtzarkpspi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtwewhzwqc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtvwtpetew.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gtnictgwsr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtqayiquhx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtzojmqado.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqcobwbh.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gthcmtrbxz.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtyjdchggv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtpyqoqzwj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtfjqqkvrk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtkrqntzyf.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtxdblobxv.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gttrzjfxgd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtcnqbakgo.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtplvllayh.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtnlrifhwz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtvhwaxnjb.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtlqvovtss.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtsanbzrji.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtpfhuchns.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gttxrmobvd.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtaviwxuwa.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtieedusho.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtquitiehs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuzegotl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtwajfdmyf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtjqfwgxxs.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gthrrmvtke.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtiycorbhq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtzxhydbfc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtajdjsogf.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtequjldms.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtweegzvch.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtkwdxqmzd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtkxwuvtzj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtnhpreqfs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtlrwwumbe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtyhcfffsc.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtijckbwhr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtsefnkrhq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtasvxdfio.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gtdeqpalzs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gtobpmxomm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtpicgarwh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtdetzqral.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtqhunxyju.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtwdtkzbvx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtonzzjmah.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkawnqxyz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtushbyoez.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtbmzthxmz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtwdckaxav.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtodirplzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gteujounsg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtkyuucclr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtzuthsddy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtpfsvcleb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtfrdgbmyl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyjqucxg.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsomzxbnm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtefdxqubr.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtvvnvtufd.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtnnfjqgri.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gteewcgubc.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtbcvunbib.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gteputyswl.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtolbxxhul.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtlzgxwcew.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxeyfjkcx.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtusojdqvl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztlkwjsg.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtxluczrtk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gtzmtatura.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtzfgszkjw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtahybafjs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gteoyczmtj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtkikqwsum.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtevntaais.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtlabrmqvc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtvvfsrrta.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtbnbcmcur.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtiygttooe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gtssgrktxd.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtwlgsjxzr.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtkssrgmwe.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtlzypseuz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtjgjatykp.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtoojmvvml.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gttxvjnrab.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtybwopayz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gtnqamjriy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtnybtkubo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtsncylnzq.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtphkbkpbg.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtxavkzkgc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtzhqpppzf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtcrfblgig.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtyqvmuvhr.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtueffyhmg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtzewlficp.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtvwyaseoe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtuyybphao.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunmwqpom.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtlxyjdwmn.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtuxlxaoke.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtwfkmwpga.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtzbfulpuc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtkiyznlui.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gtsybusgdn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtxthhygeo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtcilawrtw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtndkcxyoo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtdxpypsgp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtayrvkbvj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gtcushqzbz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtaopzokko.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtbumvcpgs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtdsafugxk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gtxgivszcx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtycxulywn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtsovzjvjg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtptpsgdov.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwgmufzo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtwdpuptzo.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtozlpksvc.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtpwodopdn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxtapemh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtysnptnhc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtjhbhcieg.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtzzsbjxcp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtsjvotmyc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjlxnawq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtcohjrvck.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtutkfszfl.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtcffztsrd.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfiscmon.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtsghdcuvw.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtzedscgut.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtgvpjhywo.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtoiavivgc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtrtrbpnbf.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtvalpmqos.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtuhfegnai.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtbgsqgxdd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtzrrdaytv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtkedxqshw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtglcffpoa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtnlogzxia.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtvqnzcccv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtxxfusdik.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtnbfkvdey.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtkshvfbdn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtuxnablgp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtvsgvkntf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtnjkqttzn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtgnjzuyws.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtcfqfwpzd.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtvecgwbmf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtbljwuzmv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtwgfdrzdy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtepdlfbjc.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtmewyfjuz.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtwynjjpqu.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtyhdsyaht.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtgzboxcen.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtiialcqkx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtzofpnpaa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtuxmpasrs.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gthtsgbbnd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtmbpklrlq.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gttdnmmrbk.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtmcdobuik.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtvyiymvsb.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtfujysnmg.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtvaoqczry.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtlkompfuw.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtjulwispn.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtrqisladq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtxtypmvak.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtgahauebu.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtahmuqhab.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtcxktfowy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gttxcugjvc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmnrnarve.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtatanmjdz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtvrkjpjbg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtykpuzlsz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtaoghdvpc.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtptqajbuw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtzhgdzxgu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gthemodkmt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtvsfpplhx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtukwlbhat.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpqgbtyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gthvqecnmb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtfdkkcjub.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtqpqadyre.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtztvuthev.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtvrrgckvz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtwouzmufx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtjbgqjgxa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtvdpqrpfo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtqpnuvzqy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfwgtbml.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrthtjlcg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtelymhycd.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtouokybcw.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtsqgzcadt.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtgymzglhj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtpbasyxif.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gthwmdqjik.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtytampadf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtiwqzvngz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtruhsorxy.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtznopnkql.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtiyyeeltl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtxezflnmr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaaifkil.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtkunhenbt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdsbsqnql.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtsfoodkpw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtraxxqvai.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtjdenksyf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtzhxdlhfl.html


<!-- 参考信息 -->