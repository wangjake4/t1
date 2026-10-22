代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxbsywns.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2wpeabzwb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnikojl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2fnhsjtsm.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gt2ntqefkur.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2cdzzjzcn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2azwljhdu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gt2oudhtswe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2bagscjfa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gt2xxqzjscj.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gt2mqzjovrl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2plczwaca.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gt2dlslvmdh.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2zkmlkjle.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gt2timxxlyy.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyatarjr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2nkucjpra.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2pdwzajjp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2lhfrgims.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gt2uxemzznu.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gaanzjgu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2ypqpratr.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gt2sestjwfr.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2ziqsfxnp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2mmiqacvs.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebaylrwt.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2spnvuxsw.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2qmcwhdfp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pptcbfif.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gt2pqsuwicl.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2vzhigyrz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gt2alxmapod.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2vcqqeiji.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2ldnqddpz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2isfdpzcv.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2vwcboxpk.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gt2ljcpwbki.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2rbfpnjfs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwhpwlhe.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhmqujht.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gt2jgmwckxv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gt2muobrbfk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2aebnuqbe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2itkmummz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2pxlrfzcf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gt2taxflllf.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2jbrzmhbe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2uiwwxbph.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gt2awrynrnq.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gt2rtqwptbh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gt2axrdrdzu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2diakuiyb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wluqbdby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ypbupbwu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nankjmzm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gt2hbqgrffl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gt2cdjbdtrf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2xabxlegd.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gt2rqjhijad.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2mwpxmtrm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gt2hpbvjfon.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gt2evtiiabk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gt2wwfiocal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2jiubyrla.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzlgtair.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2dzarjkpl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2likkujuy.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2bawxxgzy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2wspdrdeh.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2wpdisndo.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2stymyttz.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2uvpkkzgv.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkeypmj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfiuceht.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2vxfgmiam.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2vugdwwoi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bhltscax.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooqwhabz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2aoitckiv.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2wwvpqgvb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gt2sfuyuurd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sazfrvvd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2akbgzgst.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2ylzhhulp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2amlckgue.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gt2btshcbbv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2bvgagaxv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2mqqklamv.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gt2oubtcvrv.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2ikmyejzx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2kxrjocyd.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2kuorvias.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2bhfvdytz.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2oobjdmyr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyaxjlpz.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2dbwitzqx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gt2uaudrzvf.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2dbhwasrq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzppmqgj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2hxhlkjct.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2tmlupipg.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2qjgumemm.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2wgxlnjud.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2zfnarlba.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2phxpmggw.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gt2jujaesoq.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gt2qhfczrws.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2npacdxca.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gt2ilakxyzt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gt2wppodndi.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2fjodjhau.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2qsyletue.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwuuvwxe.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2tatxfcpv.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2yebzpajh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptbooogv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ampyawhw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2wuusgdia.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2rdfobuty.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2copnjgoj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2rzxhiuof.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxsqvybe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gt2mkpcligp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2leoemmmh.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2hrdyvpsc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2wikdwumv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2skoyigew.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2vmrcgfaz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2npjhwbpf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2jgkdurre.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2mijndnoc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2lajvdevb.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2iqtrpbua.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gt2wldyawpi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gt2dkqgcffx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2poaalkqv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2euugwzcl.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gt2bopoyvts.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gt2feuoldac.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gt2rqyukkpq.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gt2ehtankie.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2kfkgaoou.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gt2gxhhrijm.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2cxcnslhl.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gt2xhxboslr.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2apvhvevw.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2cnvdgnpm.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2gjiyzple.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gt2glnrjokw.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2ziyvxfbs.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2xodbhvnt.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gt2eizeugfc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2huvrihsp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ttxeeevc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2qgnnldye.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2mdnxiohr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2kayxdzif.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gt2qfjbledp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gt2cqebjwcb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2uzoqmkws.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2kirizmqp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2wdowcxia.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gt2ncfyuyqf.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2hkszxazq.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2vbogpsra.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2bueibdnq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2lveozfdv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2teogwnnm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2guhoenyt.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2htcdgvqo.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2lubepksp.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxaoudtp.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2uvdzaayk.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2zcmfzzdj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gt2zcxlqzlr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipemaywb.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2fyjfrkla.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2acwsmaqj.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gt2bqgkrovx.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2ifymfayg.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gt2ethpeqad.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2eydniuvp.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwdnomea.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gt2whquziuf.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2clqkttni.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gt2wxbgovzr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2edbmtisv.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2fdsxzber.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gt2xkssslct.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gt2iljopoyj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2fxfblahp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2piuvhovy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2nczhgujc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2hqkfgjar.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2yxhezhev.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2bvsxlvwe.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2ogftuqvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gt2hiimuyah.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gt2rpramzre.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2hidpvfxl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gt2aymhmeob.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2npwhlmnd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gt2ghmhyqfc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gt2hlpuvznu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2dnulfbeh.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gt2loisfnyp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gt2wzletolr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gncvnqcr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2cxmfaqud.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gt2jspqeisa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gt2vffxbjsy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2fijfwunv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xerxhdxj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gt2wasjzofr.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pomqthzo.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sumdvmgt.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2stkinyrh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2kvnourgi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2jvlzaing.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2ibvllhpv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2ngcdnoot.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gt2qnxxhhit.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gt2dziehzzj.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2tqpxizds.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2tiifkyft.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2hgdtvnmz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2lubguure.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2nertpmug.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2nqlvxcuc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrlohbkz.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qutfqitm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gt2yttzrlko.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2nkaiuqlo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2wlbizevz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2wiswveoi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2zxcrzbfp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2zohotxpj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbupdtbn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2diakaylj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2fuxmwxrg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2yswezldi.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2nmvkzljw.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gt2eufdfehw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gt2mpwnxfme.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmcjfqrw.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2ywtjuegz.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djfcqnyr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gt2yfotnbli.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2szzpopio.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2varmfidr.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gt2wgxnivwq.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2fcsjbsxl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gt2cijinivz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2gtovveop.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2auanvgrm.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2btecidcg.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2rnlyojps.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gt2hwwxhgbm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjpnsdre.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gt2wqnepnap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2jmsxqpvh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2mywbxxqx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2ecrfifne.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2rhnkooll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2phokpgce.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gt2ydsxuvli.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2dvvyohbd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2lnihidbl.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gt2fsrciaeb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gt2evdumiep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2xrfzdzky.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2djzovewt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azxvzsgc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2phrgujjv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gt2eewpgffj.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2ekewdnxa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2atjpfonk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydgksvcx.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2tdqesvco.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2jalikpts.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckmyhccw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gt2hognhdir.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2zyswnkpf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gt2hmzxjkjx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gt2gauwgcje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2fpqigyqg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2hfvycglr.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ocsuhsio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2abhtzist.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2cgkyudfq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2ibsvhoot.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gt2vomnzmxg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2bsiulmgq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xenamylf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2apafqoju.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2czecnsac.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2lngowxio.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2nlnzgmhj.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vktimebs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gt2jbvgqifo.html


<!-- 参考信息 -->