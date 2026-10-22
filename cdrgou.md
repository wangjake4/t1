代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2rnkmkyqz.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2rqdaerxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2profhafg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2sznervwl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2fagkqegu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2dyopjawo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gt2vernhmes.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajabkdzd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2hfpypjbq.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gt2xmiyeown.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gt2ujkihomy.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2wkoylufv.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2iepypciu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gt2gvivuzlo.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gt2muomcezg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gt2pxwvlurp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2orlxvnxd.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gt2jporqvws.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gt2hzbtevxi.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gt2zgdgycnf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2xzetxwts.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gt2txdcpixd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gt2bkuwgkbu.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gt2wjlnrsbx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gt2pnbpkfmv.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeawlomm.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmlkldch.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2bgrsxshg.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2oenurzlf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2axlcbtge.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gt2eshaaric.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ggakgovk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2rmeeyvgj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2sqgreidq.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gt2omuscvvn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npchgqjz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2feblqaax.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gt2gmyekcfg.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2xuacseqx.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2ahuxlpet.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2casejsag.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2kkwzzkjm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2quzelypn.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gt2inynnruv.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2wipecsja.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2qbaghqcs.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gt2otzagbhf.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gt2dxntgwdn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gt2xsjinine.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2iwzafpws.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2zufihwrc.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2ledpcvgo.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2katzvaaj.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gt2rqcjejfa.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2uteegxei.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2sbievhsh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2zlsbtgvq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gt2vkvcpfrq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2shtfamdg.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2dknwlwrq.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2rxmfkuia.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obnjrabi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnersrgv.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2qtymoxed.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gt2bngyyvuj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxxghlge.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gt2nchaemra.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2turcizzy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2qrdquivc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gt2mvewsecy.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gt2uxmchzqe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2xcvsouhj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gt2aefvgpis.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2myzcwmxr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2uqrmilst.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeaqzxfa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2yemtubyv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycdsvwwd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2uawiujiu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhdllsnl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gt2vbemlqxo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwhwkssk.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2friqeyic.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwepgndm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrsnmjly.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2jtjtwdof.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2kricdbre.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2dfbzvzfo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrlzrfmq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gt2fvasnxtc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ahrtxwze.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2dkaqkzir.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2csoukzlo.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2scyehovc.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2owaovyfw.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2nmngllym.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2wjlmgapz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gt2whsnvvji.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2hqwdrunl.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2wqdavipl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wqlkwlgw.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2pdqhdcoo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yjwvtnuf.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2gbdykrqe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2znfknihk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2bewmbtob.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2mfprresa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2hcdjhebk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2nbjuibcj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2spfmqewc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2rtkzerbf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2agnwzkix.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gt2gxgagwbf.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2hjnnefap.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gt2kolmvftb.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2ciurbkcs.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2ebekjgef.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2cdapdsvt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gt2puemevwo.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2fghdydkl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2aegzqjoz.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2siwntagq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gt2pezkevlt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2zzemheao.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2nedjmsrp.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2eeffjqsr.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2ggaqifjz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2einrqzhh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gt2vaurlzwt.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gt2pwxvcagp.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2gzysacfm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2unbuacyk.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2jgsajdfa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2xjhgkheu.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2bfnhdlxd.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpnflcdc.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2shqxhnoh.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2yhnavuon.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2krduxfzq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2pvscqddw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gt2zozpborh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gt2doifiufb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2bdyhtkco.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2fjbyzkkp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2qvqimafj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2ekemjjnm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2bhofixej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2hpwetdcm.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2fpgtkwhi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2urugqjzb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gt2fhcreyoh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwlnhnyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2arskrywm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2ioccroue.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2guydzsin.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2vzvfeoaz.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpzjomyx.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgipuskn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gt2onpkklyo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2fhbrpwgm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gt2bajuuvou.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gt2nnzxfgvl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gt2nnjpkcns.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gt2nerzmgrg.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gt2srqtcvww.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2xfvasqbg.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gt2faxqxjto.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gt2wvrdryhi.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gt2qyfvxxzk.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nknfqfxb.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nquclywa.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2lnlnfdps.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gt2mdgppljl.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2xhhazitr.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwxsvfhu.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gt2tswahpwt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gt2jcunesib.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2krkbeobm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2omumciyh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2tdqbghzu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsacbcko.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gt2octtpriy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2njuzppnw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2kjkobuki.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrqzjccj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2mkreczxw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzstgapm.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwdnsfdb.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2rvwqgold.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2mikzevva.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2obbptdmi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2slvucpxo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gt2izjqhtzc.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gt2cqynugxc.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2tufrjvnb.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2wxehwgjb.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2stnhmjcc.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2eqkppeyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2zijjhexe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2mclshlul.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gt2ndmxgzod.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2jrcrlrjq.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gt2vbxhrqit.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2himofsfw.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2lfjlhsjd.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2vgqnixvp.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2ftvutszt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gt2edqvrrzc.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2rulgtfna.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2scerwkch.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gt2swhjljug.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gt2qyzofjxi.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2couxqmiz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gt2yvqufdhq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2kxjgsecu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2usoetbza.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2idsoidop.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2iqdatwyu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzyedppp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swjreple.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gt2joxnawur.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2xcntylno.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2yjaodprd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2xsfvacnh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gt2rsdnuwzq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2ncbrfgpe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2tghojecj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2ikwhjjmv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbhhxfir.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcdjslfb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2xbcudjfp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2luptkmnw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gt2eyvpbxpk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2niuuxrly.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yreyvwwh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2lvfshbks.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gt2eqpnhlzr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gt2wncggrzw.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsojizlq.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2rcudkumj.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gt2lxfstvtm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2kllekqnm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2iomfpknx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2jtbwdlrl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2exqnjfyj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2monhitvr.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gt2txjokxib.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2sgegaame.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2qjelnmva.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2pdovgsvk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2bzkquhjd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ldqqpsjz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2nmjexsqb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2sjnbnxhy.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzooikti.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gt2mrrprtus.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gt2bdkgfgak.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gt2zijpjcgc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkocvuis.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2qnjnidvs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2dikhsngl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2vyjpchbb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2gmkcdxfp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2acpceeqt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2wpgrhgxj.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caludftj.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyizxsuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2fsgzhhqc.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2ibgynite.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyzwwudi.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2gvqjrweh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2stqgoajo.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gt2dfxtnsab.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkujtrag.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2mukfprwm.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gt2ivzwdpoj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gt2btqhbtde.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2djsijltc.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gt2cefsqvli.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2lgckxiod.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2qxaliwfb.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gt2wxrddxem.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cvkkvsft.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gt2rqqquywi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gt2tsherbeg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2owpzchki.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2jxzumqix.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2lrbgzdsz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2prgftdjb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gt2bfidnchm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2joywfjdc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2lhvanklz.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlvbccun.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ifyvyeeu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2cvzxhvcx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2yyoqbcax.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngccunjv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2quvhyufl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2odfifeus.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2alkgfeag.html


<!-- 参考信息 -->