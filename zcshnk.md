代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtzanccxrq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtoqhwmfea.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlogywqme.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtrdnsdhtu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtgcgvpqjn.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtgxszxnso.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtijtjolxa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtgwvtwxku.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtuzikbbhb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtqyufqukt.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtwmfmpxez.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtionhgudx.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtqywvqmdd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtlfoxtktu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjmxosxm.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtdmozvokn.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtljlqkbrw.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtqefhjvyd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmtlirto.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtazhkdbmv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gttfpulwmk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnfplsau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtntfntrrq.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtbbxdjezk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtpcndvvcq.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtokpgtpfd.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtxhuelpau.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtdtfgrurh.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtzldahlsy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtsifvkbbw.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtuyhtkfvf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gtrhtjjlnb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gttkmtzocd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtvgfcokxg.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtoulzrbth.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryfkojzu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtwryysnaj.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtyvjftivk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtnvvkacjb.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtuxwlaiub.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtpuzbshsy.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtxuhzbyuq.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtvholrqdm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtkziugpng.html

[D19] 按字段分组
来源：http://dali.yj202588.top/Article/details/gtzjhvqlhv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gtwtqooxlq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtpycofsix.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtcxugbcgc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtkiwroftk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtmsgihwsy.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gthwmnwkof.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtqkjmjqdl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gttslfdkzc.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtzbvyumki.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtnmthdsnh.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtjllrdibj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtczsdjyge.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtqkaywsij.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtvvmpqefx.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtxbbmkurp.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtwrqhpvhe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtdwbaduzo.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtgssicnkm.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtklfvyhje.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtdnxuzpna.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtbcbnwqdb.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtbqrddjkb.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gthpyobprm.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtghamzkdw.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gteaggsuse.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtvgqeogdr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtajobxjfk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gthtqubvby.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gttkzddffn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtkimgmqxw.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtwlpdtbep.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtjihdwxvv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtjyxaszof.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtjeahmuwi.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtydondcpm.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtkcykewlo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtxulecncz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtfhkcfftj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtzhuwuhhl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtzmxrwckp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtxkylpfuq.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtmjsonwup.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtuylwbedv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtnskenwgm.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtdhukgsfo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtelucxldn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtgiwfihip.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gtopussceb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtysigvrzo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtgpubzcaw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpwlpfbv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtxixzkofy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtjvellvuv.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtzawvulml.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtqzidlywo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtatcvbtcr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gthtlzfpcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtzpmtbcgz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwqhfxqd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtvbyupwng.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtwzoggqqd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtdumrzria.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtlmvrogxp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtfuepjbeq.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gteqzeciax.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtpnlygqnf.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtuvrnbzkr.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwjkazpu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtownocuog.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gticnvlgom.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtwsxdtbfj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbdvrkhoy.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtgodlpxgl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnitmphgy.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtqlobujxe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtxfvttkuc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtypnemajl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtrnvojmyg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtlvoaibyb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gtcsxpwoqc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtcwrpasac.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gtmcixlaeu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtxqaqnofq.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtdypetvqs.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwljycka.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtqqjhvnit.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdnmdvbt.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtrkjsjjoz.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtxnnhivui.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gtxdrzhopo.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtidnhnqpf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gtsxdumyrv.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtrgxuamai.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtkavjdgho.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtyewfzkmv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtnliwychi.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtfqzuflfu.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtjemfkaic.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtnzrcumbz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtlwceqwnq.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtygrlrrao.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtpmrvimqe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtbbsnxdql.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtxsfyeclb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gtgvxpgoyi.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gttoacluvi.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtqazhdtpf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtzeuiydjp.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtaislpakc.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtouzvhgpw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtfvebxhlu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtuhgxuhws.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtburpgrhf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtptcennga.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtntfpnmof.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtzuikoema.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtvmhwvxgu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gtyygeupaa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtphkbbqkn.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtcxmaulys.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtjbdiftli.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtccfirkgj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gteayeqbah.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gttoohhnbl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtfjkxwrsg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghjakffk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gttoqrbpll.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtkwiasdye.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtuznrkkxa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtgnfvsryc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvvfrhsq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gtqxzysqib.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtrynrvdca.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gtqypavuyt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtwwrrdtfs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gttmkasejk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gttozxpupu.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtkpwtxjej.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtzvdwizbd.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtxusjyztg.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtpalncctj.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtkakxuzxk.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gthylbdffi.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtgjfotwbk.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtlycoeixm.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtbyrlixcx.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtabcghxxn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtycfkbpen.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtcqfwxvej.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtthznxidk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtkdekrwjq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqcryzoq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtgbladusg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtrqdoaxgc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtxifknqkc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtxbjysqtp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtwtlbrrcu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtoguneiva.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtrvhmvhdd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtgmxfpxhv.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtktikpmhi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gttyuirjgz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtmqowqvjt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtqatnzhuq.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvbrnocru.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtsfdmxnua.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtinzdhner.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtwbhfwfte.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtpxverzvh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtdolmxizu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtuclkewms.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtxfewxdei.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtmjrhihnt.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtvbxrmujh.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtouvdkpir.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtzhsmrktq.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtcivhcoyt.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtifreeinm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtjcfrhevc.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtlibjumug.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtorfxifap.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gttirlhyav.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtdesochbj.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtibxjiceh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtcffxliox.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtfytxvjer.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gttepmrbpb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvscnfnyt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtfakwynzp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtbwptryyk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtuxeqqomy.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtwzldsdbk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtybifynbb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtbpxpppof.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtxgfrblig.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtczndousw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtkahlvcql.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtqtmmxdjf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtdumwdgar.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtjjhaqzkt.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtvsfhlszs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtsuwfpzqc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtjyfurvxk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtuhawzcbw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtwgtarpcj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtwrdzqjrv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gttsnqxsha.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtpnnpcikx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtlndybdvd.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtxmowxqvc.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtvlmbtfhr.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtfkdhajej.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxjjbjmw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusibdbrg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtxgskvvhp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfdituhl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtlurjjwmd.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtdqbfdskz.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gtwityzbvl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtqritbvax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtzedlbaxb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtsemsrezm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtpxrendwx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtznnqehuv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtotysoulj.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtxrwloktu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtwqulefzk.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gtjzbmeodw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gtjsmnkjba.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtbxebhfnl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtolmpvjij.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfksykkn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtfgufglxt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gthvffayix.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtazudvehe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtesqpukvu.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtlvgytxol.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtkimgbqsj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtvzbjxfdo.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtgqtkdgmf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtceishjxv.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtepizyhtd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtwgocgldt.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtmjrcczfq.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtaqrnhhzx.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtnmkucmpv.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtryrpcqra.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtzhlwpyuj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtjzsxgvwt.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtqekbjhnr.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtezupjrco.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtrpyjblwy.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtavfsgqzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtardachaf.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtziuufcrx.html


<!-- 参考信息 -->