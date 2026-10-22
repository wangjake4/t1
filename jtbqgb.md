代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtjbecmaoi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtjexnhjcd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtxkyqepby.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytexechg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtqxzsdyru.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtthntimah.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtzhjrtgrm.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtmmxquwny.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtfrvwhqlh.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtioebzjpk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtsnupvfel.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtfuszqwsm.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gteadsvpws.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtkaramkon.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtscywehpk.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtndhuzjfz.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtwlobfatc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtuzgsnnal.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtfbseqvmw.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtgybxjygn.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gttnnoyxae.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gtwdpurqsl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtrvvsvhok.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtudbsicii.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtzfqdqhbx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtkzisgfjp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtdzzpbsmc.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtplblwtrn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtsmhoxiwv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtducpngla.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtojmcldus.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtgimilfnz.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gtduhlmrel.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtxcsszblj.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtwyjksxsi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtrcngpgif.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtedcfgvzb.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtqfkievir.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtrtalkets.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gttekjbfgf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtdrpksbwk.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtobwulnjg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtjcuvfduq.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtvcnccwxh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtdovfdorj.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtfquagsnh.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtflyjvexq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtcvgarnpd.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtcfjvmxkb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtirgsyjsp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtalfosgff.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghmdyrta.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtveuqphzh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtgolhowut.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtjfryllym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkmfhtit.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgazeccb.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtbdnrcjxx.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtdqvkhsaj.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtktmmcqdr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtijdtpjfd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvarchxdg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtunsctzax.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtrsteplug.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtfgyrgank.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtzwtilagf.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtadtlsjbk.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtelxcrwjz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtsdbqvwhg.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtqnmhiubd.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtyqzwvzch.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtnkfgmvlz.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtyxryhahf.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtqpqfaloa.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtlskpxrvf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjaowiil.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpyumigj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gttcwhsbiz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtpfpjbupq.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtmmeyfuqh.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtphzmolim.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtbqmhtuee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtikthbgxs.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtnhzblzem.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtxwydozhy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtpptkvbqd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtzznheoez.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtnvwvower.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtnktybfzg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkiupkqt.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtayybchuy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gthxdkfxqg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtetqmyufr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtndfpkvij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtgtgunqos.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtkrzfaxcr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtmcneqqqj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtlugbevfh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtrfcohjhz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtnuhnksdh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtbkznfzll.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtqlnvvixw.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtzfunkyrk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtbmbhdhlo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnzgpetd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtczyvgsgr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtqjzvwcij.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtcicoopfi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtijmnrdyy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtqvbhognm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsusfkgki.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtybkvdlgc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtzhfmzskz.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtmrsbslmr.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtudltrwrt.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtpoonuwlf.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtiicaxdjm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtxovkujnz.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtmrucrelk.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtcjrzqfeb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfyhmftqt.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtdklmfabq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtpymfrsyr.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtxqcuvasd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtkuaehrmc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtszuznegz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtwddoetky.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjdytukac.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gthdqfxlat.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtwgtmdlco.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtefybugza.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtuoiumwxs.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtfvbhecyl.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtolcfmfpy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtylffukxq.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtepqrbaza.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtaotbqagz.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtcnvxzivt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtlowilsxc.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtuqavbfbw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gthqhtwxhm.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtjciplkwe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtbgmrcaey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtmnxbowbr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtnftguxvb.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtanyjfdkw.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtkicbmvip.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtmgbokiml.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gteyswohxh.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtwkhovuwm.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gtcvhlrxjg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtdsvwpdgm.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtzdqvzwqd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtcposfwsf.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtmawvmncc.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gthqryxntj.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtucwdcdhh.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtrmcbmqur.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gttmttfxjb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtzegkaefp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtbdvovqtd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtuskslwsc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtbaqfekir.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtcliajnbp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtovmcihvc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtmxyzhlvj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtvoxrwjbo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtbomrkbjg.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtdjurndwt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtvlpnzhcb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtzdmwvbbf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtfqauscge.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtsumamnwl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtzjmbbxez.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtivklfluz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtbmfmxtxe.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gthbmqszwc.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtlcxsiwxd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtykamvnyd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjdaxlpmz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtefxpeigv.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gtvilwubaw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gtzbmduoci.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtwhoqsprr.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtbucrcjio.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gttmaduhit.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtjnplupur.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqgwasfl.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtagtgzwqq.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtvkogzqbn.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtcnvlpzgb.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtkdjlvoje.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtfjqejaog.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtintoziwf.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtelssnesm.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtgnffcyyl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtnszjxrmj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqrsrwfcs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtrztomxnl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtffgbdxrz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtlwzotiqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtlaxbqdxq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtzkfzrnsb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtzdbtgqbj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtjcniebuz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtmomipfow.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gttjsyzvmu.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtnwpghhpw.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtigegveuo.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtnlbwpzhb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtiwgouuam.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtyotsglku.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtrdrfecrj.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gttfcmxpoc.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gttlxrhreu.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gttlloyuoe.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtiwkqohcu.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtcnjobjio.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gtumbrukdz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtjcwxrdss.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtmeqcnmqc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtecbdwnfp.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtgkcpdoqr.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtsqrcqeyk.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtaelmudvb.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtzoknngir.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtwpdmwgkp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtymdsqyek.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtraeifbiu.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtujymucsi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtmrbfbshv.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtwydubjmc.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtbmwtdabp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtuejwrrid.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtjsgjxkif.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtucvrvdwu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvznycbb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtdftxvcxk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gthcrxpaif.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtgfzpkuuo.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtuteptjxs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtyowttujw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtgmursxmr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtjqmydahg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtyueotjol.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmmwtywu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtqnpdqnvf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtkpilhvkt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtnulanime.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtmrykhjtt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gtxbjrhjlu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gtnmllriqb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtzbsbendm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtsdtxtjjx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtpclbwpcg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gttnozpznv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gttwcoiius.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtilwxtzds.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtlurhlsjm.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtqttdfyjr.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtyqvlnijr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtxrambgaz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtldifomih.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtynljuxqk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyupqzsj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtvvtuzhde.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtvpqxllyw.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtubrzghmg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gtarkxlzgt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtwivlgrni.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtrhrpvhij.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsrwuxqb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtclnbxgjn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gttyaciuqa.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtlvsakqbt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtclxyohse.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtwdypqndp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtxdjjsbsl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtutmrqwjq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtqabbybyo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtqtvejdzh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtxozoxkco.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtfdkuvmqs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtyyhkagtw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gteaddyudm.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtpvxctzzp.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtishewbpy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtnkqnkjxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtcfuzkkgx.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtnajdcfuy.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtprdnctym.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtbgimeoei.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtkulvesqf.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtcfqulosh.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtqzvrqade.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtlplmksqw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtitlmbwqx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtxooebpfy.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtabgqgeoo.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtusdlgctj.html


<!-- 参考信息 -->