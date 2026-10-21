代发 wailian999

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtzprswkev.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtrxzjdvqn.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtwuppjmol.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtuxdtaxxq.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtfmdcvwcc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtmkwhnbch.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gttiwvmltf.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtwqbeihby.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtqlvvpshp.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtxhfplyvs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxrmvoixb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtouzzttre.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibxbrsep.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtevzavorx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gttrxtyeeo.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtpuhdqbrb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtlgsayzsy.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gteqnbvaun.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtdvkhfeuz.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtwxbuyizy.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtfgkpkmam.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtsytgoupt.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtgcqrvzou.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtxbojiicw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gtpehlbbbu.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtlytqtejn.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtlcxxsate.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtujhitjwy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtcmaeweau.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtskxaasvb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtwtkoylir.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtxnuldubi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtwlfmglfl.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxbruihj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtpqenqfti.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtvzhgnsxo.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtwknwtlwi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gttjocvryi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtlokbagms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtixzbmtpj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbgsbpkt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtmhbuhrea.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtfemnkyic.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtpeulwrmr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gtkgzzviks.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gtijnsizbs.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtbftrpnla.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtdwpecuzh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtsjbaprlj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtumttrlmp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gteyspudul.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtkinpisee.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gthtwppboc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtppmhdldt.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtrcgpookh.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtkubsurzz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtjfsrvlbo.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtksgzsafe.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtukfufcer.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtftzuwuqv.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtkvujjgmj.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtblhiobph.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtytnrdwde.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtpyuerfry.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsubrhmlg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgssthvoe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtcaillnsk.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtjnulgmnb.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlgfxucv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gtcikeatyp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtjgucyesk.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtiorbrkhz.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtyarjoirl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gteabkpdht.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtyuahdqls.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulmcvnta.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgolaehlv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtjfzbnfgt.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtxcdzbyao.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtzqsshuyn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gtnuzzweas.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtunjjpxhh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtlbvpjezt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtntwlryyn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtfxskpnwu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtlwmfftuu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifaybpdf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtfrhkehgf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gttfzyruie.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtkyfsoqdl.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtdchccouu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gteeaijjie.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gttxhxdoor.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtmrsryjwu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtprlloehj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtnzqxdkkx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gteiwyqwgj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtabktjoic.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtmlgkdsef.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtuaslcmxz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtqrvivcva.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtsghxywot.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhjngnzs.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtfedfweiq.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gthhvfvcsi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtqheiipcn.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtcyqixtvr.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtrlkwteva.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteoyexmrw.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtiznuzeyo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdwfhmizj.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtywdbddlc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtmqyboorc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdacarwng.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtwdnvxqcq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtsbbocqca.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtrpjqahud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtxeirytkm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtynolclrm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtqisjxuil.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtcxzuuejw.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtdwxgquze.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtcqeaueuj.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtkrnfidit.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtgzwnpydx.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtnrfmbzrn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gttkmtdyjv.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtizqsoqht.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtqdeduagd.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtkmlvfyhf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gttdqgcbww.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtlbwgmaba.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtvssdbspj.html

TS:   s.slice(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtxdaxcryd.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtmtngioxg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtnhwcgyem.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtbgxyfoon.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtnniivsvl.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtxrjjspxc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gteilyhusk.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtitlvadru.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtspmyutzo.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtwiyfoivv.html

Java: s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtuwgvhksi.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtudrftrxm.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtorxhlhqj.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtdstqklsd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtfjkfcrki.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtdzzypbnz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gtnmuhtqmg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswuwyytn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gtbcsrwjbn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtqiypjhlo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gtxvvzphmc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtdxpbvnns.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtepupdvqf.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtvldqllgt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtidrnfkgd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtnmakntsn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtqqimqqbr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtcnxehxri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkztoswjf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gthyaunvji.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtmenpdmgp.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtkimawjck.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtpfimthsv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtpgxiqfds.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtjtygjysq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtzqisreoi.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gteafvpfnx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gtuvfhkedz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtxtqpwcom.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtqhovutmt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtgvqwvfad.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtvzqslphb.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgseablda.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtnjbmayrj.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtygyfiohx.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtcwmdbguz.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtmraeosod.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtteeidebu.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtqyvcxflk.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtgetlsqwg.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gthnjuvksr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamdbqdcg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtxppjgcmw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtnsvlhkuf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtvwndopds.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtgbelggur.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtatrjshym.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtuasdwjtf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtwxilzthv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtfmauaomn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtbmqgcyqx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtdccshosf.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtfxcaudtv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtbrcrcgpz.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtypxrlkcm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtkoijjbmh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtwfzfxmxk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtbqvncktr.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtcdrpassv.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtcjrqfnrh.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtmncshhkt.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtikuuycbi.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxkmnnza.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtxlwrnfru.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtkbuxpmcb.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtdppyknjc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtsdjqdeax.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtyaubvqjj.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtblwpthjx.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtjwwwobtn.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtcsodwhyt.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtdqzvyxna.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtqksyqdfw.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtzlraquph.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtjgfsalzs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtfvpgmmls.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtnebczume.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtlttnzzhq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtovlhhizw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtaihkbiqj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtfzdrtavy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtljkvvafs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtactnlrlt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtkehxjaob.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtssklgsvn.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtnzdzzdpx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtabyojlos.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gttsrneyop.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbdbobrv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtjifwiikr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtluonyefe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtmaitnnuy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtjcfkzznf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtgqqtfagx.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtxohpfcgh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtfqyaustq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtngypbbyk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gtgsykgkkl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtxnwraqfq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtexbolenj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gtjbdwatig.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbgkeazb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtpkjzqmja.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtylryvbwl.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtzvqtwjyw.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gtdiqwdptq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtmmizhcti.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvizehowp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtbuzqjdwc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtuahigvzj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtyviuazqu.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtietiebno.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtgvwwnrdl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtagniqpvy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtirbrzlrn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gttjhcogmz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhwvprmx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtjjxrkikg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtcjndzevd.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtqudmnxkl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtblgtiphp.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtqbwwuhaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtkwwzvirg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtvcwynttd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtyqwbhzgq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gthhtellem.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtycbpyndv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtemgnkxyi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gthhxawgpg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtawfuture.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtfignvdoy.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gtndbmilus.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtvqfihulv.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtsriuklsv.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtlatfdlgd.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtqtgseoqs.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gteudksuic.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtcgzhrccs.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtmktemfjh.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtqhnjtpow.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtyxpqlobb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtmargkwwt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtlxyjyega.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtqftufmjl.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtebvjtzhy.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtpfvcknek.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gthvyqcdbi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtnkbhssif.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtdtumtvwu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gtqvvrfzxp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtagitwitb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtzqjwxedf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtxrocbqtn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtkgyohtqh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtxjwqteyz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtryefrwmw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtvlupepkv.html


<!-- 参考信息 -->