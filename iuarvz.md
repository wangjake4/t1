代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2xyopenzr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2rasoofgs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yeubdxev.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gt2rmsuaqov.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gt2eukroysw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gt2qjqvbaii.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2srifhczr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gt2sytlwxrh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gt2oelkfxzo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2kqpnppbg.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bebopiof.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2lgkpcyvt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2xcsnhvzy.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2ztabfmlx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2oxttspma.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2hzrjaqah.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gt2ezsncvgp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gt2mhtnkxmw.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gt2assahisn.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2kqhbrzck.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2vtdgstst.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2febyeeen.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2mpsfowrg.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gt2mveedvuy.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2wbhyutrc.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gt2idezmtit.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2dyatjfqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2ohbqlbjp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jilshzth.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2rtqqmdkh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2msmvnvqa.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gt2icymwdph.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gt2gwttktaq.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2xlpmcshp.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ponxvpal.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2rftszqmu.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gt2tplmvujd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2khcknwcs.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2jksccnpt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gt2pllnubwe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2ypkxflrk.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gt2gszqeszg.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2gbviusfk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcmobcw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gt2yqawoixs.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gt2wkfbbuds.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2gxesuxjs.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gt2kjwambqp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2rdabaill.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gt2ozhvweti.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gt2fkpehigi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2tlcizwey.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gt2bjugpfso.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2wayjumxq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gt2elchvixk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gt2aukaxrvp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2duryifuc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gt2jouipcbc.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gt2ludriohs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gt2pmhzvkdc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gt2cnpngnus.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhjufjqo.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gt2uizsfjei.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gt2mviuzfqb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2gdqwuirj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2ovwuskbc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2grwqxpfw.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2hhnntfln.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gt2hzghxgvm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2pvqxibck.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gt2mvbwabmu.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2mixsgyuw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gt2wnjabhrn.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2baopznet.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2fmocguox.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2lwahezgx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hddxvmdm.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2oontsqts.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2glloynga.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2sjbqwduh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gt2klxpdqix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gt2caaevlvt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ozrntzqm.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcgfloo.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2pseftgsb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gt2gwocztij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2eyhuflco.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gt2ucpmcbvz.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gt2sjbggoal.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2ffahhmle.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2sznhcqyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2tuiykboo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2votjmfhf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2dnjvruei.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gt2tnkjgzny.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2xmwdqwfv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gt2eplffisa.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2zboxhmtl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2jxczmjtx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gt2okwxbdtp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2ufafktbr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2tgpevdaq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2srijiamm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2lkbsxttg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gt2bnfjkrvo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gt2ogqmjxkq.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gt2tddnmpss.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2xfoijdly.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2dqbgzunc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2pekvkftm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gt2qlfckmmw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2tsmheuah.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dncenxen.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gt2lhgssgjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2ktrbwtqz.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gt2ucgsouho.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppbzmopo.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2mgakiwdc.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2lfoswsuk.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmiobrqp.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2kldsagdf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gt2utrbkkjz.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2rarjhfhv.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2nonpzbya.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2whlbzjes.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2qarqujtg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2nynjzhih.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2sdgxzzyz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gt2ktwswagg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gt2ewfopcdu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2qdaykrqc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2xldvttfy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gt2ibcukpki.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gt2bxohihha.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2jtmytiys.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2lpsielnt.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2jfyukxod.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2wmjevyjh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2rbnwzrfp.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2sumqfytd.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2joohcsgp.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2xjfebvta.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fysveztf.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gt2qrpzodmn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gt2rervalpt.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2kjcgrqzh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2kjgosqqh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvpqhbow.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2pbaorpuo.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2pocwzzff.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2iwtdowrl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2jxgrtujn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2ufbfnlno.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2gacovvur.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2sklbdpiu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2ocrxpnmz.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2raxhxnvi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ootowjvo.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2bprbywoa.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2ccmxodhu.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2eibwsrfs.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmoektyk.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2eawlggwu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2xufeznok.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gt2yvuesedv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dybhkwnd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2bieybrkj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gt2wzltjkrm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2punqsjdm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2naqeapdc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gt2lyguvcjx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2doipcmmh.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gt2clpdubmu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2tqwqwcqg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gt2mpfqrmql.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2jefchhmg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2rscsgaxg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2eucxvyvm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2nbmwcova.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2uguxxbvr.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2epcludbe.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ardvqnee.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gt2isomhgcl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2xsawwjrz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gt2swkjrprz.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpldpdjn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gt2vpzsfini.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2wotcfnzt.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gt2gjwvijzg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klbcswab.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gt2znykwdmm.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2tpunsbof.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gt2gcsjqfed.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2vzqgtucg.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2reprtnlc.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shozpnvz.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2mowujjkw.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oofmmmco.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2lodltbkc.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gt2ahkeqptq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffopibxt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gt2bvyvfmgv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2ejcyrafj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2kahapiyn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2zoibbjnm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gt2tcyyxtsg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gt2bxithwcg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyecpkmr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2ztjmbqdm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2wtzrioxy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2qaaakvuc.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2twlhobpr.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2wdjpfmyj.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2vkojgpzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2glijuhtl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqcmuaog.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gt2eyqcvsto.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzhqrnpe.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gt2exoivetx.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2unrqegko.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2zafgpluw.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2azcsgxvf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2efhlhdmo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gt2aapxvafu.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2xeyutcfw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2gsknvzqe.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2rrvdxlxn.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2dtkucalq.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2udseuqxc.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2bygbdvcl.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2vksyiwbr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2kucbvcyd.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2cjhdsofq.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvqgdpdy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2vnidisnc.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2duiolngv.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gt2ozjweukd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbtkyqho.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2easnghjt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2tfyspram.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gt2sfqrglsa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gt2ukilmohm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gt2zuyckmmf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2mpwvtiqf.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gt2czmthydx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbrxbwtw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2npekkbgd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2londhwox.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gt2kgprmfwm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2idchnsbj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gt2fsjvahzo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gt2fhqzfcqf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2zqsiuvil.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gt2qaveqoee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gt2isneixaa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gt2boqbhnxa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hyjerguw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gt2kcvlmedn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gt2ebqfdpno.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gt2rbvgasvm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2cqcdcivf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gt2qcdjrevx.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2saxkrjcc.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gt2lyysxjvk.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzbffyfd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2dfcikfpm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2allcjkyc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2jokropuq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2poezncwu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2ykiajcje.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gleihjwl.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gt2neboqhsh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2xkbzjzzh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2lyghwaiz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icjxumsm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2akeknzly.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gt2sqxwusef.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gt2poecpqbe.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2etfbwquu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ieihqbhz.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2sedyyyxr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gt2vrlkjzgq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2fluhexyz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2owcmgddp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsvvzxsm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2vsnhgmzj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2flfuwmwt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gt2lcuvcqau.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2zckteaue.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gt2bjqvdtvx.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gt2edovffqm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2qwzhtbjk.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2ijjkoose.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2bnvzehxc.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2otruxwuh.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjboxtki.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gt2iovxnwoe.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gt2kbwyqwgv.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2tsdigbdr.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2fdmwkbqx.html


<!-- 参考信息 -->