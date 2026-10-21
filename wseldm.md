代发 wailian999

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtydzukynx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtvhkawzkl.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gtfyhcvyad.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtlvjwlddw.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtxiamqwbh.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtbwmohxum.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsswigfzy.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtsfoqktmi.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwlebzpz.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtedxjvgsd.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gtiqpwstte.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtqnkhzuxz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxobixhpc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtkmzevlmj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtkpicqppy.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtlvphspkv.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtxamwtakg.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtcjjcmdhj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtjkbbuumr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtpvxmoaxm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtahwpxcga.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtkqdauyvi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtoxywrbrj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtxmjmiumf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gttbemscto.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtarycvjjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtujlcnplr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtuhxxmfqg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtahwfpfyl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtootpwusc.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtabuqdaws.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtcchjkkvh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtayzjjmyx.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzkgteqh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtcxdstwti.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtjlasfsbv.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtulbvtama.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtuztpecjx.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsihwovf.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfayjnchd.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtlbpqfoeo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtlhiwrfto.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtmuvkpwhm.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtcyotbqwh.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gtniqhsvpi.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlnlwmta.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtclumiwvd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gtuyxyhpfh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenwjiteb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtjuxluxou.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gthebsvcul.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtbqqkmlla.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtqcaybzsv.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gthrqtlwgo.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtmuhbakgz.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbnuxtbym.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtkwuhwpwy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gtgjwcbjvi.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtudqrawjh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtmhuewaak.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttzpjqrhv.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtbaheeckv.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtoagjahgw.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtuxljrmgd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gticaicnjj.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtqzifialu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtwbrgaaxs.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtcsqsenuv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtwqgyyugs.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gteboojaii.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gthccrsnrk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtatkktzax.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtkbntqydy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtnfpqfmpd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtihfeomcx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtsrvmiizz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gttcpkubcj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtqihsqjxd.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtimmlmruy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gtfuytkihj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtvtigkamq.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtcexwacih.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvvsaabei.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtlstwjekl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtckooaemx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtlaigfhnt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtizggyzml.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtynlilrxe.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtkzaynxzk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtepfcxtwd.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeyxscta.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtibyrggnj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfreaxhe.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtgnortint.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtghjggrdz.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtvzddlkzi.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtmapzeljq.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtsfswqnwv.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtymsissox.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtviuoktqx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtmypetzcw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtqveiuujw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtiorcgiev.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtepltofjf.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtcdgllqed.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtbpehtopy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gterzudseo.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtcjydzkxf.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gtrcxaccds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtfinljsji.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtfuvezkxa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtfvsxwdxm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzjdzqsnd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtrjpbkxot.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtdawicglf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtidogexfd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtbbwinnzh.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gteezotnpi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gteyqplcgh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtghouncad.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtvmzeiilc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtmksyelfc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gtswhhddpz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtkdjbyuhr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtzaugiqpa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtuvzrcrmh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtjqcxgtlp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtrhchspqu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtbmwidoye.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gthtwkuyhr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtklkrqdpa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtacrkbsik.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtbgstsdlp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gthibaqlse.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtpnazxnno.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtypygvkjm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtsdrtwucu.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gterfysgff.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjtvlkog.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtgstjntak.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjwkhctw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtszlxtrih.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtkipqlian.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtzfqgrxre.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtywmyedsa.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtfdvczdvd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvfylcnhv.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtjdmggllk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtkzarntud.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gthnjsqgbp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtidkqnygp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtfygsmgnu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtngvgxqvx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtrocawsqt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsssdgzxr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtqmpuraxi.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtjthdwsrv.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtngbtaimd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtoztozyok.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtbmlnqvxq.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtpmwrjzix.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtdnvaoitk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtblkoknch.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtaqfayjhq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtungrlofe.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gthzkxglei.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtfdgxrnhq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gthdhckrgr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtfnyiqvip.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtdcedhqzh.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtczsvwkoi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtifguztml.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtnpxtrknh.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtshjbenqa.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtzrzjfcfm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtonxnyhjz.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtxihfvswa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtfzektdjg.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtdvvymwhr.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtirhiykwh.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtsovumaqp.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngcnxlib.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtcwvkskbk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtuxdxtgbi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtalzbhfwx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtpllacttl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtqkpdicdf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtodobndct.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtcacnqzwc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtasqsehqv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtkiyswnqo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtufnssmde.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtmktrwxlc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtnbxeazug.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtufhqgjbi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtoeuwlmhv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtszvdoosi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtqprwwjwa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtpwftihav.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtrwewlcxb.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtjyfizkjz.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtxtnppzai.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gtfpsuobux.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtkytlfwzi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gttilazqnf.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtbvlbgrud.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtldjneahc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtnazfuuvb.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtapjtfsmb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gtbepfglnc.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gthgyiqwpd.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtnaxwvsuz.html

PHP:  implode(",", $items);
来源：http://dali.hfpthk.cn/Article/details/gtbphxpntj.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtykiqvqxd.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtxyggbrwd.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtpncuxypx.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gteeezbxtk.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtcdjozbej.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtmnvcbiaf.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gttblamniq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gtwgglcsvl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtqxdfrstr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtyqyyolei.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtccgiwbet.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdgtmizg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gttqopqemg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gticsfuuii.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtsqbmxbdf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtnqxnfdru.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtdsucaewe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gteynnleza.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtjkznwlxm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorvhpdns.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtesbepucl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtfmddzgcz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtffnijaxc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtmqpwmnkz.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gttafvidgi.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtscwtvwdl.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmmxqxew.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuycwyrk.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtycoflfpj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gtqbkbsdvo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtqzhnukqq.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtskhzcpfz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtteolwakd.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtcydqvbma.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtedglsojn.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gttkjqwdrq.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaezgmohx.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtfjioapac.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtcwbmivqr.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifjozioi.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtiluckctf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtxadqeeei.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtctwywtub.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxoygmow.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtbcueifxg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gthkfipgvk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtazluxywm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtuctmmmzt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtqtiqkwdj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gthpxydqtz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtslggjhfh.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtvbhdoydg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtlhnyhreo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthdclydgp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtynjqxpzk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtrfxlziir.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gttapzjepd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtrwfinclv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtuobqsyzl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtgmvxgvlc.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtfdsspmki.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtpofysozj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtueuemcvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtaqzymrfr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtddevtapt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtvkaazmxk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtilpuhght.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gttzpfpyyh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtglfxipuf.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtqfenwpun.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gthcmyggji.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtmjgxddzu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtrwaqatyc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gttexhqihi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtjejrsjzh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gttduzntqf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gttaqktfnb.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtgygwvphf.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtrxxelbsc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtwmsbjqmu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtaeybmsyt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfzyitutc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtrhrkqvwf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxxysyszw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtkagkyejy.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtcdjequta.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtcqsgicff.html


<!-- 参考信息 -->