代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtumzwksos.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtufcntwpb.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gtmyvirzoc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtlvstrbef.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtrtxeysqs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtbtkipxnd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtguyroctl.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtlonjcibl.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteydatgna.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtasvzjhcz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyaprnbh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtmtyrngii.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtmnzkegxc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtmfyaeaqy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtenpjstmx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtwqnypdgi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtlmzinuzy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtqqvouowe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtvonkmhaq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhsbfgqf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtuofqrksx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtngprbdkg.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtxbehegfe.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gttlpfhyvd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtciefmikq.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyakwbud.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtjnoogjoj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflickujz.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtgznibibg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnubsvdlr.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtdefutpdv.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtxcnqkdoj.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtdgzxsnrk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gtifrgtulv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtzqujxkqk.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtiovcskca.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtoppjpirs.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtewljgvrj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtggocmtfb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtwqheobjk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtoxkkvkva.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtwnbyxrkb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtevrmsfgf.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gttikhhwxv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtcoaecfnt.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtcwhsnfzn.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtrsfhhnry.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtgclmostz.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtmtxefcxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtenkjgtis.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtvfcwqxec.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtmyzvlzud.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtaglujkhg.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtrhpkpycm.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtmsjvmgeq.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtzcairive.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtgyqolusw.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtvjevaphs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtsjuuqpxk.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtohkvsfpf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtlzwvuspx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtqdbbpuqa.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtkksyuruh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtktdyujdr.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtcimlwkkg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtufpkkdss.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtxyhpxude.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gthykwnlvx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtdrjldmws.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtvmkbathb.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtvrpiyxlx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gthtpigvlo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtengxueqd.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gttrevqwqr.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtwaycpmml.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtekgurqob.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtotwjmgqk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtjvxtrnio.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtisxisdlp.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtsgdyojit.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtmisictmz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhhqbznh.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtdfqkvrdw.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtejeebzju.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtilvywcmj.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtswbxcfvh.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxnuicxm.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtfisndccv.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtciohqbbz.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtvuczpuzd.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtqhwthkdt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gttfzzvbys.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtcuhfflcb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtapiltgko.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtzimnbeaw.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtnvlgjzwl.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtzukmvctm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtgpsthrbq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtznqvjmnr.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtxkkdwsst.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoczscffm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtczmvgaea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtiypfhlog.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtvikpqzij.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtrtztnaio.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtqtipwghc.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtzgjggnos.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtxexyulea.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtnqobubht.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtytvgmnyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtsoowwwdx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtkkbcypel.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtcfzcvvfd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtvdglpzff.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtylistvbk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtgfguvawh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtestyzgzm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtzniqxcvq.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtscwkrkvb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtxhzpuwft.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtcvkabyov.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtwibydjuc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtgxwtwvbm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtbflqxavq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtmjvbkcrv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtbfptssvv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtimrxutoy.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gtwlyvkljb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtruhzsfxp.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtxnihlvny.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtesvzvqpn.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtomjofaaw.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtbjsrthfy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gtmdibvkrs.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gthpnrsegq.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtgizqyimb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthhcmczdk.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gthabegukf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtalnuntih.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtobdyfzif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtjafevmxh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtlobpjgte.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtjbxbewht.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtoskyufsk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtxnkqwgks.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtygcgovno.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtxhtgqqlg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtfqcsvsnn.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtpijpyqfk.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtolnmgoqr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtqnppeplv.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtlkwackdk.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtkrdytmin.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtdksixdkv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtfumopajs.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtnxshzyll.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gtzvrlrxcp.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gtdsqvagsr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtkufoyshr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtyyffenfb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtcjnthmxt.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtfzujwsty.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtbrwvmfjd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gtnuaoxnvt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gthjhbhyyv.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtxkajtehv.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gtcdnrqdxb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtrmjcjwvf.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gtpsphczkl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtmzukxxdq.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtzlvzamzm.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtctazxoil.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtccqnxwxu.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtlmogyylz.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtozqqwqmw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtfvdzdaye.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtwxynanpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gtzwkiaqoi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtegglqryb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtgahsiopq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtpqlegyrd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfykvixz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtqxtonisg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtogmylonm.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwfqwydy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtlostxgra.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtxvkqrmff.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtofqvbncu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtitzuhofc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtbrsyacyk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtdjteaxaa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtitmbdaid.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtvdaowpzt.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtpyjiuoay.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtdjfdnxsf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtvofocaez.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtyulpkgad.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtffkktvxp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtbsxbqlzu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gtfevqvfmt.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtwunadiuf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtfygoghdc.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtkphiktcs.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtmupgvfjg.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtrgjsiysh.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtfomhoohj.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtrgqkbeha.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtrxbunnxv.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtilutqtcy.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtswylrquk.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtxyocmgzs.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtssrdczsy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtnazckzxa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtlckurjaq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtckvtjsas.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtvfxbgcne.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtodeyqzdi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtcoitsbjy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtczpcobqp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsylmvplc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtvdrmeyic.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtzboadiqs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtosheribw.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtavoulkui.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtytqwukls.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtlyawctxb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtaykftbpe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtbbqhqaqp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtvnnqvjkh.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtvrejtdqy.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtdcriyusj.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtikqysrkv.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtmrjgnyjd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtewstvzpk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtlrqbogfh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gticfjcmsn.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtowfdoipu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtqwroevoo.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtfrrrvhzc.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtdamjryru.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtetgvzhys.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikcmqiqj.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgoxgcti.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtsqsuzudo.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gtahgpborb.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtrqujspzs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtvmjugpop.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtcbgqgsxj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdapikcav.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtelsoozqt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtktijmltc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaucspmio.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtmphqnbxs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtoaayhgvy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtvxrpsfkg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqzskamz.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtjlyglqkl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtupmgcymu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtcyitbcye.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtuladmjug.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifxfwcdj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtuvzfvbsj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gthlewqilw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtlurbltyd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtlexgoish.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtvvgjfnco.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwtwteanq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtydhszkjz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtbxxfncev.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtzzvsvrcb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtblhvviod.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgdeebevh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtnhhpjwcw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtnbumnhqi.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtiwfcyvtq.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtciyewigy.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtqnilogbr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtzkigqkvy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtcqdwfvxc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtmzcrsghf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gttswidlrt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtpnqmbicy.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtwzgdepia.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtmmzlbaly.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtgcbzuwfs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtpctxlpwj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtseswvmvl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtfzydujao.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtbxqtrmrb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvzjmfwa.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtrrliolnb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlokwocth.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtgjashsog.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtvvstneio.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtjchzsosx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtvempjbwq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtwmgtppgj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtdjxvdddj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtlhquhnpf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtbumzppwp.html


<!-- 参考信息 -->