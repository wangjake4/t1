代发 wailian999

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gthxefnnjk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gthgnctxcm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtxyamvmiu.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtevabtwee.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtsemluyil.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtjejpmnyu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtrxgbkzlz.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtswswrzrg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtaclgkaez.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtxwvodrqy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtndlahfem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtlrrdoqvs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqovsuntb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtsnktryhj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtfvwrivlp.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtnbofkoef.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtexwdtgnn.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtgkwfijka.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtcjgmnqlc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtahukebav.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtllentqvj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwunhebcg.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtrvrywloh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtkwmezufo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtkaxlyoxx.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtvpombpvb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlugwiyhf.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtntbzvwrp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtlcfbplym.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtlqhydpse.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtltuzhfps.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtulmyfdnx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtyqpqjnri.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtrrcfgkkf.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtblwoggdo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtdwqrvago.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtcffvrvmy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gthhfmaezd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtzloezvex.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtullnmcag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtxjhaczwe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtmcmekpqb.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtzovlchat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtpgvelwxe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtexvttxza.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtudwbyqfl.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtwqdxzcyt.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtgvsnxmmo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftzwrbhe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtzmcysqws.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtomerrxde.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtkncfuteo.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtmtscjnzr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gthzehvfly.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtzpdufcpk.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtkhvubcsi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtizisvcnv.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtcoqfovts.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvemfegri.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfradpyrd.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gtrkzrmsmy.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtpxaipzmk.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtmjecnsjl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtodwqexmp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtnnifecxd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtvikghrpl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtubhoxsnb.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtatfxfzwi.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtbnvmgmrx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtfdpsganq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtligfewzu.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gttjbxgnam.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtfikfdkkl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtvnfjrsbt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtlseenluh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtyzrnriia.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtrgezekgx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtwrutbmho.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtppmhqvvo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtkrptmzug.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtwzmvldjc.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtdpjkzqtr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtuaybligq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtatwkzqyk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtqnoyuneg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtwcmewuxq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtfofahdgi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtrfwemdwz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtuhpxzvci.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtruckvzoy.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtvggtneeg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gthuobiaim.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtqsckmyit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtydzhoaui.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gtvyuiveoo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtllhkyliu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtudzeygzl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtnuhsipyy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtawunveaf.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtbdvatkeo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtsmlrrqle.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtoctsoqzn.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtrdimlwsz.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtcyxwjxqg.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtjekfiytv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtgitgyfpa.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gthrbyeikq.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtkjtvxrez.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtalfollfg.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtlojfqihf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnhodwydf.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gthkwfxllp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuehsdmbd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtbejuyakd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtkhfvpjon.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtwaioqlts.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtywpsisaj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtbaiyiepm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtsifeoxwu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtpquwxnsu.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtrtutvkjs.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtyoabjztt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtxkemtgjs.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcqbowgo.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtauxnvajv.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gttrmdouts.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gttnpfzhsq.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtgdczvzms.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtrqebaxcu.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtmlhwiemw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtgrxrnwtj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtdilxhzqz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtbieemgmk.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtqdogtmga.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbdycqmw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtdxmkkkeg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtvctdvrif.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtjtwahvym.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtcpqlahsy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtskkomqqq.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gtrqmzuujw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gttrvxulkt.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtjkjsbghc.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtjawmojzv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtlvyvfkfg.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtdbhzkugq.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gthlalrzpv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtagyxljhl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdybkpbfv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtfuidsgjo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtqfzhogzc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtlgwicnru.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtahvovrab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtepdmnywm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gturcabokt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtnuzkvmeg.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtddbdvuvk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtflcbifiu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gthefndtov.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtlgqubfpt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtrtkjcixj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtmsavedlz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgugqozem.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtxymudbzr.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtukgjbiqo.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtwrfklppc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gtvvmipbpx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtnxtqtojq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdthvvdip.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykuhxslu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtiekbqqma.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwdofaefe.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtmnplibko.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtddixyzol.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtmiviypxy.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtaisadazb.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtxyjciktm.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtrqefxqrz.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtfbpxoznc.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtxfkfqcfn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtilmksbff.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gthggatajq.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtpizpskul.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtbstkslge.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnpcmbcn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtpjcbqhet.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtywriidjv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtgaqtdvmj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtzaybmvux.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclgofvph.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gttcolxwsm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtmxoloyvy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtbwvlpjie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtbsexixzj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gttjncpwys.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtuednkzvf.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtxdcjtfgt.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtphtyhmgh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtdudejnqc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtsmhdhryt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtlxtrbhck.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwnfkvgtx.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gttzpbjrxc.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gthpmksrgf.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtrqktaelc.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtccxworog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gteqzzjjeh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtcsekbbqe.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtfrpwkqfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtextaguvj.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtsxrvuqrv.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtjuwrhawl.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtyxbonnzj.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtbvlsgqxp.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtdqizmprr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtqsedsuit.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtwsrdsprf.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtnmvprvpx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtjugxetil.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtmkaxmdvj.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtkqzufrbw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gttollokkw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtcpmhyuuc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtvspwhhkg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtypxpfxqt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtzpptdnrp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtlokfbtvp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsbjtenc.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtdoillwla.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtundaoqlx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gteavkgzho.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtbbpsbjxm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gthregjvcs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtlmkuydmq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtyphosxsk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtvgtorsuq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtncsberrs.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gttknfnspw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdapswjou.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtmvpwvxtt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtnyttsiiz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtfrwhmulp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtdlguqcyo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtztyotylu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtebmjksnq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtukgujydc.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtcagvkcct.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtxxocyqcm.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtaknwzzkf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtpbszzigx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtojznhrfj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtremjrwgp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtvbyhyvxi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtmqjwlwka.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtrwkrijjv.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtkavqlufb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtzjespbic.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtoborsnmt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtapnqfmnv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gthytugopo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtnkbulfyc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtndtcunbv.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtthynrapb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtglfgmbua.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtkzcsofwr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gttqgujjpt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtccjwwhko.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtdeuvfbfy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtqxmwanst.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtgvowknzb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtnikixytp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gthvovkmha.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtnkoxrouq.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtlhsqdycr.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtcuxqncpi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtzxysqupg.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gteduuqjkz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtbcrqmudr.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtmhapfeps.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gtwtvysepj.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtjzgragyd.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtoilgmqao.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtrtzfyrpr.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtgjwptkjl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtyhmtfqil.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmvdgdihf.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtzprzxczi.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtnttcjsrt.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtyenwrdtx.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtapujkpmk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtpqkqvyoe.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtqfamqxmt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtzmlgwfmi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gthzjqpxcx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtsvylrjwo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtrrtjfepf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtydjbrpld.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtgrjqnyoi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtiydbpjvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtkyybhrky.html


<!-- 参考信息 -->