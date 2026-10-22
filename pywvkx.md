代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2mgpdlfqc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2kdhwbeti.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2xdqjcyro.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2frtybkdb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktyppyin.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2voseoold.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2nqjfsioj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2ldtgkbnx.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2zpgiqlxm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2noytxguk.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ogyytjwf.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnmbiouw.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2ciadupfy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxihoqxk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gt2osmmsdjw.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldtriqls.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2kyrkpmjs.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gt2rpywdlqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2oczxvqbp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gt2rcgtgagv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2rmfuyqdc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyolznpe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2wrlrltnr.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gt2agmwvkjc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gt2ryiybvcc.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gt2kdzkorte.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2kakmeejx.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqgofczs.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eerwqihw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gt2gfgvxcvd.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2dgpgucum.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztpgpxji.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2xoqqfwnr.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2nlfbiwxg.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gt2zjmnfndw.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2wiuzjpac.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2exyjxaro.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gt2mqxaruii.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gt2rbswwqxc.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2lpznumuh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gt2wyejjbad.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxjrmqmk.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2zedntcix.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvfavibb.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2yqrdpvsa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gt2wugbecgr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gt2ygjvgsep.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gt2cqfkibou.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlozcjiw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhghvbeb.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2xnsjwnke.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gt2htggmhiy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gt2saecfsxb.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvbkpnxl.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2wpsqrbib.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2nycgeylo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2szmrynxo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2xrumshoq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2ydzpiajo.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2xllemrrx.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltlotejv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juuhssro.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gt2pijqdypn.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gt2uutsmvmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2gunpsqtu.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzvwjvie.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2arhmdsby.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2ffcluuup.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2jbdliigj.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gt2ctnydett.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2goemptnd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gt2qauaynmg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwdzlykf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2ujvwzvqn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2xcplyryt.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2zzxiytmv.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2golcnafl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2ljccuukp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gt2kalnthhz.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gt2fpgxhtij.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvrwssas.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ueblqkfx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivruipgy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gt2pnhdxolr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2qgzicmcv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gt2fwcnfcsn.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2mupsacpb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gt2jehlizjl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gt2ambsaqwq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gt2wygplabl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2nanvlomm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gt2odjwlyqd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlayuvoc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmluofxi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gt2bdtcnzxf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gt2keauaxxl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfmoquwb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gt2efvfevmw.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2iewjvbpy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gt2rdfoqjcl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gt2pjdhwrvg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gt2qhjxeclz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gt2tmbjfxvq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2duwjmibz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gt2voqkhjll.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2iogkweoq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2hldofdac.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2oastlgtr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2qjefhgde.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2qljvgjli.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2piipybzg.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2hhkoqzxq.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2zzclwshm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpscwaut.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2xexlhfce.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2fpylcekn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fxjqnvou.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkostggz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2puwpirkd.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2fkslfgfs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2uksgkdyq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gt2sqfuncch.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2vvlzwrtq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2qhjgchts.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2vyjnyxwk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2tgdmvjal.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2ydyxefcj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2brbblizy.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gt2ujzzszcz.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2mtmxjkbh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2fmhysyat.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2bjtwkxhs.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2rnwkiqnc.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2inquipds.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2rkjbwmpe.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2wksxkpoj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2sgvauqag.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2neyznkpu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2atgxcnjt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2kpjtdvuf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjzwehcb.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2ijdfpxev.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2pvhamgac.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2zjtzgihi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gt2tqgchvaq.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyumbyti.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gt2kkpifxiq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2unhmonjg.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gt2suixxqmz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2etuyzqet.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2bdagewea.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2vqqosttr.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2oefoyszu.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2toocanuq.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2aouocvvi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gt2scbqfwon.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2bdqtaczr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gt2vtkqpghh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2fkechfae.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gt2mpphuamv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2aaccvqwr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gt2hiriawfn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ioomkatt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2cfrvfcya.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gt2kzbxiypv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwabcqxp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2qiolftpw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2ezzfendh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2jkngzfmk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2kuuecdvo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2xczonwio.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2ltxmtyhh.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2xggqtgev.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2vvtjeokw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2kefftzax.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edpgowrb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2zzecjyla.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2xhvbadwi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gt2dbwvsfss.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2naghobwa.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gt2yygwgdxa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gt2vtkocgzx.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gt2ryzrfkdp.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2bnkmdsid.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gt2zqnyfafu.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bixdvqku.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2ugpepqgh.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2afugkfgk.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gt2ykbsunma.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2nukmotbw.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2nmbrvmxx.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2saparryb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2amwtzuhd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddvgozrs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2lzymyonq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2emgpxxkb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2ulrukxpv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gt2zymdlnai.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gt2spjkzaja.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2hdlgebsd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gt2gwvbbwwq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ityhitxj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gt2tbzvxtpz.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2qdvtsjcv.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhqxpbxl.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phbkakqn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2wjsasyva.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2bktxyshw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2mwpacvpq.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2tzflfppx.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ruyzkyvc.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2dnsacuvd.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2uzaapnev.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sozbygbi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2alebqkce.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2bugxbzgg.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2slpxfshy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2onwcadjd.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2xeoyrgue.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2nlizrvjc.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2kukytpxm.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2pvqznuzk.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2kdbljmcu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gt2lfmjksao.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2oyhbvwpg.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2iaafvnmu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2tucvtkec.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2uxezzcip.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gt2lcuqvudw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2ntgmhntx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2vkqkyeuw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2andloysm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzmiwqu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2inbhmqjb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qakeyjwp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fncmuyni.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2fbbqnwkl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2rgjbuasz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gt2nnfqyrwu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gt2rzhuazdy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gt2kasjaxxl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcuxzllf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2gvxfhpmx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2ettktnhv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2wnaglvyl.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2qppqxcwe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ibwqwpds.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kngvpylv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhhspllq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2iusspvtt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2gceokyfz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gt2aaqyemst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2uqkijkwi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2lezlqlfy.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2kvsnjavf.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gt2lkzengli.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gt2nosuakym.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2katpxxzf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2dmemsuex.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2obmurxrn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2malsehgp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2cmrwwjmi.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgtcptyj.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gt2xqtdlbmg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.svipenyu.cn/Article/details/gt2oxbonhkf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2pbubsrzh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2sglogbcm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2nkopiacw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jklmmmve.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gt2mqawwggs.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gt2ijuajmad.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gt2twaeftku.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gt2hkkbhmnl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gt2lhojpanz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dentquju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2tsdeckru.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2qlxzrsya.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2wlngpfan.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2eobmdnnr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2ijrwtsoe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2ogdavhlw.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2gsatuvxx.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gt2ashmprsp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2upmpglip.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rthchvnq.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2mqsrwooi.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2dczoyocd.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2figzcrjm.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gt2mrefnvjr.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gt2fbewkttn.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzvsqehi.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gt2qfhjrqby.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gt2vrzdslpt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2gfrkylrd.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bcrqshcf.html

Java: if (s.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2fmiokvfb.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2wnvetvhu.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2kqxfvbwi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ejwylyna.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gt2qhycgrrp.html


<!-- 参考信息 -->