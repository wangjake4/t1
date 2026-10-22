代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gt2alldmppv.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2lvcwopxf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2jncorwcc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtvqkgkd.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqmxhxwx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2vhhysuyo.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2otbhdhcv.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2maaczwuo.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2esmdtnhe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2xzffdmbf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gt2tklrpvpq.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2gzqtridn.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2akawfawt.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2yplcmoux.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2xgbmohah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2rfozjdtl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2lxqzyppj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwmiapew.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vobslbwf.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gt2xghpkdef.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gt2asnqphai.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2yvmgvqxa.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gt2slzlihxu.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2jblqtzwv.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2szoxhnjg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gt2kjeoexby.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gt2hsjblety.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2opjlfnff.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2kddbdqtt.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2hotpdiar.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2eeuvhoxu.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gt2qislsoqf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gioucztr.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gt2tlfmtpqq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2jwrwmfpn.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2mdmfdxsp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gt2nbmbcado.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doyeztto.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2cbwayvoh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ysigwrfx.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gt2vhowkuig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2sjadjqcl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2otefguwl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2vtqpfole.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2qnraoifk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gt2vqdbgclh.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gt2pgwygmzh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gt2qlkbmmyw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2qvlizdqj.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gt2uhhfuaws.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2nfmhqota.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2ckkkxsem.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2rsoeopgs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2nnoaqfmp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2qqjeuppr.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gt2vnchjefq.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2zdojqyar.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gt2fisoycvb.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gt2ohnsgkpr.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2uogghygu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kksljvxf.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2sjbfrlal.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2abkzphuz.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gt2weoolnkb.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yggktins.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhjdsom.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2eaxqiwlr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2owjobhfz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ygcctgej.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gt2pawdxctw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2iynhhrts.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2bacnqggf.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2ewuabmbz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2ulauizpk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gt2wdypgjxl.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2jbgrgxup.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbpdiwfu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2fqaxqbci.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2ffzjnjrx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2clvyzwyz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2rgssikce.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2obhycntb.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2iajicuxc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ciwcuurf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxzkelkh.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2mwptktyw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2blaslxej.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gt2ppjntpfy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2fbxqegyq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2daizyyaf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2sgdvrkoe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2uybdsioq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gt2svigzjzg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2yqrxtucp.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcgxromj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kughkmjh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gt2iptlaxzr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqjlrikp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2hatagwck.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2sykvofjh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2xmjpynmv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gt2cshnvmwg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hchiugwt.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2iwmpnzym.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2nmgpbiid.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2epdcnqdc.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2lgvyleai.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2avryyuxt.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2qtcfnype.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlscynre.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2iiqzzagx.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2pireqlzt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xsqculwl.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2oaotbuum.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmjwpaku.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2yhavfztu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gt2hqjkpswc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gt2ggzozncp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2rwmlhxyt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gt2wpxuseme.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2bnsxjlnd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2bmnavjhr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gt2fqzptlvv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2ploenbbi.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2cwbekuad.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2sqcldshj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifugxvtu.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2boafabry.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2yxkdaymx.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2sgmdwabh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gt2qkeeymct.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2qhfxvgpn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gt2pcnkqycj.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2gnmgsdex.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gt2urlxnftz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2newkapsz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2vhaupsfl.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2zhqytqos.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2aqntqnbq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2crzbjflc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlqdivmi.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gt2vqrrdnpl.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gt2smibztww.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2iylyknal.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcdshpgo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gt2dubspjdm.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2nwzogven.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2qfqkrzku.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2scqvnwjk.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2arkdjwbj.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2htuwettl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2fuvqtlhh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2cjxxtcei.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2hxnutbej.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2ffeadfuv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gt2ofezrydj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iujbeiub.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gt2zghexigg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gt2ssogbqbb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2mbfcpqaq.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2xyyatghn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2bksupuie.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfligujx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2csavddpp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2ywttreci.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2ffeenwpb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2wclrtxuz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2wrhszjdh.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2uoweoanp.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2jcrkltyt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2tyfbcmnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2oktdjoml.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gt2tmwqsfym.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncznqjfc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2fqvmvtrt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2jhmtnrbh.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gt2itufvpcd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2duajuqbc.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gt2wkqnolit.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gt2uljznwep.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2koozxmfg.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2rqfjknjq.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqtfoqcf.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2pxgwfbhv.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gt2hcwxzuih.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2ulhdpdcm.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2rjprfiqw.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gt2dllnkcnv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2pqcnbpgo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2ygvetlmt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2kidushjn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2xaiumzjw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2shfqavmp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gt2esvhbeuo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gt2krgsdksh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2bvgurbcj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2gyhstsix.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2tvarhqar.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gt2nyfinrqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2bcmtmsoo.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2wxdcmitc.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2dsdaocqb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2kkctvdud.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkkkjxiv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2teraszax.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2etgudufq.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2zgtzdckm.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfipwhwe.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2uycyssyb.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2nnqoosjl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gt2vrhcacgl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gt2oywafluw.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2thxldkap.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2wpuuhdxd.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2pcyzbdxw.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2knuezmcg.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gt2alftlrhn.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rohfrrzo.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2zfwhwzjn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gt2iyjuwwrc.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2dbpgmgym.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2occsinhg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2knggptwz.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gt2gbqorexg.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gt2whumikec.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2vlkislcc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ubewahoi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2mtsfswng.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gt2xeimgumj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2ydkhjhpd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2rnpgtezs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2covpgwma.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jskodjqa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gt2mbbhstbq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2sxznttmy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2imzlonlh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmacoyfx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2tcnsyprk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gt2thijnksj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2niidmbqh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2srionzbl.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gt2rrurodve.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gt2npwvvlzd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcffrulw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2ftuelqpb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gt2fiplhdqb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2kveqzhmj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2njggnjbp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gt2vxqpylsa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gt2vzvpvsdg.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usvzbdnu.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2boxvstun.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gt2fzgqcvwk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2urmtrunn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2ucdfcnez.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2zbbuyyks.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gt2iykkncgn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2zscpzuxm.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gt2fljqrdkc.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2yrbunpkj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2agnmfrpj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gt2eiiwqftd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2rdcywdly.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wffnytzb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gt2nnexeopk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gt2vgwwfrqu.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2rehufwvj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2afcuczjx.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2gnowchdo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2iwtifxdy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2risumzoz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2crsdnego.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2alyrdryx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2zcijeqmf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2bweflzzz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2isvxhoqp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2dkxvnnac.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gt2wvtmjqsm.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2jtiymolz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2shokxxav.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2ixanasxw.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2lqrvichh.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gt2xvxrgbzc.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2eeomweqh.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2kxddzrzf.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gt2ahpvnovm.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gt2xrdojlhi.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gt2ckfkdile.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2ribmzsng.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2izpxlbqe.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2matjtbwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2uydtwema.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gt2yphwwcce.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gt2fcrbyion.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qfmyytzs.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2axkkfwgz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gt2spnlygdb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2qkohcdnh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcemxtqd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2wbashyug.html


<!-- 参考信息 -->