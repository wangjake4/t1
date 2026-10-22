代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2xkrgcwjx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2mbkbblgu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gt2isjujmvi.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2iebwbxbn.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gt2dhnovjpe.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gt2wbdvzynn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2qdvifykq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2kjkjwush.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2xqmzjesf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2zwhnznpr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slufckxi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoygannc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gt2fuuzaevv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gt2hexzhfkw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2jtmguaxg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmepltcd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gt2heuzokov.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofpadgqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2tbwrdytc.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2pahljgvd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gt2hvfugtgu.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehsuddmq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2snbmivaa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2alntuciw.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwfdokwi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zopxadwy.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2sxqgspoi.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2jvmakptw.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2xofwsdex.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gt2ofozkdvd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gt2nmclqxxk.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2socjuxpp.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cupumhbq.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzlwrsrr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2fjyjbpac.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gt2pgljcxun.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2zfjxtuqr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2kqcpwehs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2znmsrsms.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2xbkkjsqt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2aduveufn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gt2okdfgolg.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gt2ffvsyrod.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2vhbfaset.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2foqmtavq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2tbiltawb.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2prbxdmgg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilzxawmf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gt2czcnwlto.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2sgjtamva.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gt2wwlmrxtz.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2gqyqasvk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gt2jhvjaofl.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gt2rphxtsch.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2lxmwpdzp.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2ioxwqmzs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gt2izekpjsy.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gt2ehgybqtd.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gt2dwipxvsf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2ekuscscx.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2yzlbryhh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gt2glumrdjg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2eiuwkuak.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gt2rlhaeqtf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2phkecisi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfioqjzy.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcluxvkd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gt2ymxshwbx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gt2odqdypgs.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2juvdpmqw.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gt2eqlokldq.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2vfajocbq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2tmxmsdyy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2hdutttah.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gt2yyfuetge.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2wxvzhxap.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnevoken.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gt2vxgbdsgi.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gt2qonsipgh.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2oszghgjq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2vhqdzcki.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2hgiafjmg.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2sbyndmgb.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gt2ecsxhqdx.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mczreqev.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svzkonpe.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjybefww.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gt2vssezcsh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2lcebzqxs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gt2zhkknpvh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbyefbms.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gt2qgvuvqgj.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2hlcdcohu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gt2yadnvjeq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpzlbuin.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gt2dkwfcafv.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2llimdvgn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gt2jtjuayzx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2aaaqpzvs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2nvubkqnn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2umprxbkj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gt2fjgejzfe.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2fscgtjya.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxntxlet.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2naqkilur.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gt2dzkxxdcc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2obpviukg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2anvdpcyn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2zypeoywu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrneuchs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2yciiymkv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2myhnxhji.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lritycgh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gt2rrmplsgb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gt2kbjyojzt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2rnernfmj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gt2tumhnkwo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gt2ixhlfpme.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gt2eotkrhqp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2bscczvlt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gt2rruidftu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2qjavkddw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2uojzxtso.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2dkwnbpke.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2fdgemops.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2kcqssuid.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2gubihepp.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2pwmcllht.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2djoxekpg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqefhlsg.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2agvkkrjk.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2gaasuupa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2guwkjbie.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2ipdwgncm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wnsdqday.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2ahqzxaia.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2rktqvggn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2lsygfyxu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2jubsqowc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcubgidb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2pxzyekkt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2iuviievh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2rpdjlgir.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2clhxxopf.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnoynitb.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2xvuxzkhn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2pppvrzzo.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2qfycoiqy.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2oqvtuhhd.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2temcslol.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2udfnuzqh.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2njmablcm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgryillm.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2faipltgr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxajjouy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewduoxxb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2srzryswe.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2fsmjcjpt.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2zcvgsfkh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2tbendsum.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gt2xovngxci.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2abloqgje.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gt2jgbawghr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2jchfumdg.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gt2cxhmbady.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gt2pbbmekoi.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2zuussnim.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2sggfqadj.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2gqsqzvis.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2nwxlabta.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2tsoqsljc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gt2ucvfklis.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gt2fwencojh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gt2nmehtpfo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqzwpgxv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gt2muysjvvo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2rnyuxqqj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjdmtaqu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gt2wpdjubet.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2xfmcxtgm.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnnqwbj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2dvccfwdn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2hlekcdbn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2nzhhojrz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2qcbenpnm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2rcwgydbo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2ytcyhbyi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2wfmqibyq.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvccylmy.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2boxdovlg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gt2iteawjhg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2ldxxpjkj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nannjnxe.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2hfcehlbc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2uwejajap.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2uactebkd.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2ggyzijin.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2yrueuuzz.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2xubgubqn.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gt2cvhwwcsr.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2mmvhtyab.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjvkhksq.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2trlimetn.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2fceuklfh.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2gnepuzww.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2elprcncd.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2dnceddzj.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gt2kesuorgt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2xbzkbyvq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gt2zusmzfje.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2rqbjzwgb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2gnidynhu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2sgxfutvq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gt2fuzvhaoj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gt2kyfxvqpn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2xtmzwkpa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gt2djvvhmby.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2hklkrtvn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2apefkfpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2ybdldhnv.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2kuwhqywf.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2zdwvmyiz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2fbsxvydi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2cuxqkvoh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gt2loeeabos.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2gaohsuic.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2gzhqaarw.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2jslvvant.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2hxscffrf.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvfcdnoq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2sizpumuu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2emftlgur.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2ovcchczj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2frnmtrru.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gt2mhemxtdm.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2pdyofzdz.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gt2uwnwluiu.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2vssiwglp.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gt2wfbficws.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2mqiemqej.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fonnqeom.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsuqugem.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gt2gihotvqu.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gt2oorzwpwv.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2wbfawcaq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gt2oyouulcp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vptnycqy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2pjlpvhmd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2rpjobamz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejqxcirt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2zjpeqmjf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2jfddssuk.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gt2mzjfbugv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xffbxpqc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2itcygbue.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oveeotzp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gt2ildfhkgu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2cpuuovip.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2dumhxxfv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2fpmdrpkg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2ppscyeio.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gt2cmemuyim.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gt2xyowysfo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gt2dcplghiz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qavhurnn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2wtvwnffr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnkhuuvb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2einhxbcn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2cawnfgkn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2ciuxvzfy.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gt2ektgwdwp.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puqcfwrm.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gt2hkjsseil.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2crakhzke.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2yinjhsfc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2gbgrrsnh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gt2lbjbsaiu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gt2mnkwglqq.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2pibocuyt.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gt2hkopecyk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmhncfkw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbnrxroa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2iysgjihe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2qoaevzca.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gt2xulcsxil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2lxkirybl.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2tewvupls.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gt2pudxrkrw.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gt2ptikvlto.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gt2satzdgfc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npdticdg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2tqkxpplm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2wffptish.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2icqfnsxu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2nlhdksts.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2zhvukckw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cktfkkwn.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2nxypawgv.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gt2kgabsmet.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgwqeibq.html


<!-- 参考信息 -->