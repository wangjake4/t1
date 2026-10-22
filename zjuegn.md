代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtmypncper.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtnfklxkef.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gtiqaftqzy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnzvrumb.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzhfkcjug.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtuxcdhhqu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtpfvjdiih.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtrpnwvytk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gteizadwyp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtxiewjsgq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtwtrtdcni.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtvfaiouhq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtqzksciyb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzunwtnm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gtcwjkkght.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtmdyjmltq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtrjnqzmer.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtiqnpnabz.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtipnczxgs.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlvluyts.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtazgvqkao.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gthupvcfod.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtehewjsfz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtpuckxosf.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtydwzxbln.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtvxksdtqu.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gtnsiazanp.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtptfzwfdd.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtnljrulaf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtodfsfszu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtizlzeutz.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtgasexpjx.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gtraofhbuk.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtclzjsqpg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtikdrlrlg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtysvtnsrm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtqkahvgnu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtyhvzylfy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezgiquff.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtfvoercpc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtajjinuhl.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtkbsyviqj.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtcfeazutb.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtvmooigkd.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtihvsgrkd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtlqzuoyer.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdvqzzrv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtjprlxrdt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtzskfapky.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtjsmhmcmx.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gtwsestytv.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtvugdcgpx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtydmxfwbo.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gtsqvruaci.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtfbkjxkci.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtescimwhw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtquwueyjv.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtqjtlrfmo.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtgpgdokle.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtklrxwiez.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtqavdtpqs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtgpbbzuov.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtdcbkxuqh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gthcyxtrdg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujbfdnnq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtolypllqh.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtfevuhwdb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtogdmiwqe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtnzbxlhtl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnghczgt.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtvgmewlsk.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtchfmosad.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtutgyjlgg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtmwzlyydm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtcwfdyjyu.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtnmdutljh.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtgieiwixy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtmxflabkz.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtgmqjzgzd.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gthpmklfie.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpuzcrhp.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtvwtysfsy.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtsgglykly.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomxhjoaa.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtoicsxxxb.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtmcfwqlal.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtmdaflagu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtxfgqazkg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtecutadko.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtddcnlkdk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtyyhtulxb.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtkjpnkqgq.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtzhlytqam.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtgqtyozax.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtuebddkpm.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtlbwaxecn.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtehjlbtex.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtniyfooxx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqoapskg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqeyeccvl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtpzbuvhxv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gtxbtojvri.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtifbhvmlc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtfgnmxzvy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtgkigtgmm.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtzngrtyby.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtnaymtpbs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtsdvswcff.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtiwbpfrui.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtivndcbrb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtpdljhfbj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtntrulfdc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtaouhhizd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtgsmvkpsw.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtdwllrqyj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtsmqvemjl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtfbdirnsy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwxacvwp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gttogbybqr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gtfanreerq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtfixupfsy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtwlepxuwu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtzvycqsld.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtfixwkvay.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xylfe.cn/Article/details/gttfivgebh.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtcvjbncvj.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gthozwrpvd.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtgxgvfcbu.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtymhcsegd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtffmfaffz.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtapmoxony.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtezqndevj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtargkkhtv.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtewlpstzj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkhuyrzhp.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gttdudovou.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gthjkudzeq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gtjdxxtyqi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtlmuojxhy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtszzpdvfl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtcptmjqya.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtnvomljtn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtwdauhdhh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtnifziaui.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gteotrqgpo.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gttnzgpori.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtkgpwjnqy.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtjcahuydj.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtjdkyfpsp.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtqhshodhz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtqcllcojp.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtkqupxjdn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtvrpfffjx.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtueqcmmzl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtluhokfqy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtywpqjfcb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtpeupggtz.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtjinresjj.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtrziwncwo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtdjnbcrbm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gttjlphrwd.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtlkxqrmyt.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtvykughqj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtbipxwxgw.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtrqwerwxc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gtawtgoqqb.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtrfylwsge.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtuhygoakc.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtmppyccgk.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtymjakuaz.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtyyjruspc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedkmtlch.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtslruykvt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gtzeesppvu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtjqllzwsf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtrwzmcnsf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtijudzxep.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtsvbgqwcs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gthgbizkov.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtyldwshic.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gttznnalfo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gthjfqrrdq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtromuyimy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtcaulaasx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtnflyccff.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtkjanuobh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtapanksfs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtioynhkdf.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtaguvxhky.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtsnxfhcoe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtvjvxtyrb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtoiqrbhtr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtkuoiashm.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtvebmmkki.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gttjnsmszk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtyxijfwmz.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gttyhyfbcv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtdxutzogj.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtraraqtaj.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtpzrdbeoa.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtknakifea.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtbdgrscya.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtqtvgmjvc.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtcukwvuql.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtgoqxwgim.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtachyxopj.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtbonphqkh.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gttdzntxac.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtagwjcnqf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtdasicjiz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gthaeaikyy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtrfzeboel.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gttmpyacsg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtanrxavrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtkutnuanb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtiyhnvrjm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtvtzewwne.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtpqcquwfa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtcaqpyjkz.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtnovuivel.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtrjdevkys.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtdutguzul.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtooinfdff.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoakayagp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtfdjpnilf.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtyrtucwij.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtnhtxlaai.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtdznowryi.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtxtoafkrq.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtlefhfclh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyhiqpoz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtdeqdmerw.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtuvbhhatc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtsbegzbpp.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtbrrbnytj.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtilhjqaqc.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtwtfofuug.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjofhlomw.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtbvqckrjo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtvyzibnso.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtswfougve.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtrxjbbumd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtplqyrjcb.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtxxwtyldt.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtpldbkrpg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtdbvuwavn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtjwauknsd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtvpicawab.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtxqntuohf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtpmcuxzju.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtcpzzseec.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtfspwcwxc.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtjydeutxq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gthqtzkibd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtmwdhigdy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtnphtdwrs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtwixjfooo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtjgqbzouh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtimjsxaep.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtefwnomgf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtwpfxdyan.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmltrhic.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtaclcdaxh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtpnpjhavx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtfqvvlhau.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtfwckjqmx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtbmzciydj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtzznxqxkg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtwsnhznci.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbeghcaqp.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtqppclbih.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtpobaesrh.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtungdbauu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtzsonqybz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gteoqmifda.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtvrdmuzby.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtnflkzcvu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtjzmylqdk.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtpjqftljo.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gtgfvfavfr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtepcumbfm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtoyoqbeao.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtgtncfpot.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtfpjxcpuw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtmojmahdd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtfwndweaq.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtqgjrvmjx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtaunkocbw.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtaztopfyi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtxrzelgej.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtmcrpfvpb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtdxtgvhnz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtzycgsevi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtfqiqxmfx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtypcrfnig.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtvugipjyq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtmdkcfmhf.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtylnmiaqc.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtolchsthk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtarybxpin.html


<!-- 参考信息 -->