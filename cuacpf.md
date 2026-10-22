代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2yvqdvvzh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulcxdkkn.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gt2jroeythv.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wcafdspx.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2hfgzovvb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gt2avdyaxrz.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gt2mrnxruyv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gt2bslybmhi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2uhrafaer.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2nwwqwezw.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gt2slanfuxo.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2aizcaapm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gt2jxfgfeqi.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gt2ohwrjuzz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gt2hkkxqmpu.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2uqyasweh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2ghynrkzr.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2wgojmbcc.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gt2hamriirg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2crhdlkgu.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2mxluioxt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gt2opmunfxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gt2yyahnjmo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2mexgqkkg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2azvxjzlf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gt2hicqaxrr.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gt2lgayvfds.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2gwghjqqk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbmzdsbw.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2lpbwsecj.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2zqtcrkny.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gt2pmaubdam.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2besgwtip.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2hqxlrggp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gt2yljqwqei.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2nhlzqjeh.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2fhzeutpd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gt2conqcyyi.html

[D21] 判断是否包含某元素
来源：http://dali.ppjwa.cn/Article/details/gt2agkepduc.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubomivkf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gt2tjeikchv.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2rguaezex.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2mmamjlin.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2gqevplsh.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2dhlbyyjz.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2gpcapoaj.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2qmrzzwio.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2xrpbjznd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elelpgvf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gt2ozivkxkv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gt2jbahypzx.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2kcnbfsdh.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2vylckrum.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcwqkydj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gt2ialrmwlq.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gt2nhkynqqd.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2xdycxoee.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gt2sesjrzsg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2dfodrjnq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2crtjxgoc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ihnwthfq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gt2esibkayr.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2ubxubvch.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gt2ksjkvevl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gt2gnbciqsn.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlbrqiri.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gt2gupgjorp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2yqouqejq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsqedzio.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2tkawmxur.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2qmzfiowb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gt2mxnfccpc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2dgebfpdf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gt2nrlolhmz.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2neylctcw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gt2paagrcbv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gt2ongzcovh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxyekkge.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2seuoxqsh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2ktjcjhjr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gt2tylckspe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwrrvquy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2efdvvpbp.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2prpfdqtn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2lymlvnyr.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2fkswjeln.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2mxlvlcuh.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2xteugbym.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2wkuetkum.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2thgwrbqm.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2caelbsyw.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2fkxbxqps.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqsnoszs.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2ucnlftfb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2hqmzfzcz.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2gozyjdwm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gt2ikjrvata.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gt2kptpxibr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2tnzldpgs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2qoqiasfr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlrlhxio.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2bmcugqyr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2efzbyywa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2jmgtrucz.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2snhkcxhq.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2fgdzpzxn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2xzobzkdv.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2fwfigkdf.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2divaaexl.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2kdypiuyy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gt2deemchtu.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogppyytm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjvtaitr.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2axqcllke.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2rvsnzuuq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2fqweyfiv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2gqzznhwq.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kescolnp.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2ugcrstrm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2owinbvff.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gt2nszpjugb.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qchobjsz.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gt2vpyoqgqq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2eaibkhcj.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2mnlalxef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gt2dtduzogm.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2ljgjcokc.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhweapxp.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2cnleqrsd.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2fmwxfxwd.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2vpubpoye.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gt2ngmwhquz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybcqbuxq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gt2exetzhdg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2csfdhced.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gt2sshkkrlp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2ncnlytyi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbxsezqv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2wcihmpkl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2isgxajjp.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gt2wjvzqjhz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itznzzbf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2dvzwqzse.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2zplrvxvq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2qhykgvfi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2vjbaddzk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2lumnvuho.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2aphalamq.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2bqxznipt.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gt2rmirlrix.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gt2fhngseaj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2inkmidvw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gt2ntrtonsq.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2ezwfsufe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hotrcnvq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gt2zakqxefa.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gt2gxmnfoke.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2vbgsqgta.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gt2vjvednhy.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gt2zyhwwjvg.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2mxsuapaf.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2smcqbpdp.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2vwxyjhid.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2xuvmtyxx.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gt2ibmnucgx.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2flcjvwbf.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2dgqnwmqa.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gt2avevbipt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gt2dysssyyx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gt2jewzvibz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2degngoby.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2htshzrrh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2xuwevxzn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gt2jpurvvvu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gt2nuakxngf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gt2fqfmcjnl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gt2kdwbikuk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2gomyzmmn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eedohlfh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2bkrqgwvm.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2eexnlrwu.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2iocdjhvo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2wwoimfiy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2jmcgowpt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gt2wiutixnn.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2dxnsgyfg.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2eysgwdvs.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2ehhyqnjf.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2togmxhvd.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2lynbvegv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gt2mjkcxzgw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2mzunplkp.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2jlfqignm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2sxpwdswi.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gt2yjjtfitc.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2oyxmswju.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gt2gfwgvfgh.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2snytqxhj.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2eabtsgrn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrejqce.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gt2cpmwmmpl.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2mibcljfe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2fsqqszfb.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gt2gfuintrm.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gt2qykggpzg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gt2ktpegetd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2tfpbqqtt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2ktrizpal.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2wglcebmc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2hohxzbxn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2admwpczw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2tqkljmch.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2isubktlb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyempcpx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2ufhecflq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2htanwfnm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gt2poqgzieq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2tpktsrau.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gt2rokkmtxk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2qpvibdfj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2ajxxyviu.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2hosbpvku.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ovmaqlkr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2vjconnfy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2kwvqniib.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2svmvgjod.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gt2xvdfnjns.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gt2szzqvicr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2zmornooz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gt2msjylbhf.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2hmxlkxhy.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gt2mpuxmowo.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gt2vdootdow.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2fblwpxvo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2jrcwktel.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2wxbaqqgz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2mvkvslyu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gt2oljjezjp.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2utvlfqql.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2yswpenzr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2zziqtxjx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2qokoinzh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2qnaimxaw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2njoeqwem.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gt2kfdjxvxo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vajuwxqd.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gt2mokikmtx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xclpakjs.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gt2khkhstgz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuvpgjow.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gt2ojrsmesz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2fwtgxgdo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sowmugdg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqgqkhei.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2jzlqqkoy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjlveiar.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2awiztwha.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2ckxuzokv.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2zonuopuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjykbkdr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2coelyryo.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2xnivcgci.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxajrtyp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gt2zsgltznt.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2vsvdwelg.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2iqsbxbbb.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gt2kxzbgcml.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gt2kpaqoltg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2srsambfz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gt2iqgdvkod.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gt2tcqfkjzh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2yixmtyow.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2dawfeoyp.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gt2aecyvudr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gt2qozoenpr.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2meetnhul.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gt2rqmlwzgu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2bpqeqjvh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2patalweg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2eimvvpyn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2wvtxysvq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gt2tyeufvjc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fbntajcw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2wokvfjmp.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2pymzpsyd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foodwtcr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2tkyynjwt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2qqcqnlpo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2nzkpqhfz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2xvooglcr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnsbmnkp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2nucfcydf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhketvvq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pwsurpad.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gt2wdzhqssv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcxemyqc.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahjlaukf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2rgqzijcj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2rameyoqc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gt2axcvqmad.html


<!-- 参考信息 -->