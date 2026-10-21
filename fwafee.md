代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtqfkdqsnv.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtsxyxfjjk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtykvlidgx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gtgrbnloeh.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtatatetcf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtgbqszydg.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtnbzmijke.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtzatvfeza.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtjilvcxcr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdisxxlr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gtymelgavs.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtbtzllkun.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtajtbzpwd.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtdfcgsdwk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsiuyrcr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtjzzptaeo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtvnjialxt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtsbhmxomm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtrcyykwyh.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtwlmcvfck.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtfntngxrb.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtdxegssxm.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtfyebstgq.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtontalkzy.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjerdyhws.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtmkowrbtb.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtgoepubjr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtnycsmmjk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtoavwrmkp.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtxunvbsda.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtgrruyqsn.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtkiubwyol.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtqpmmesfc.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gthcjqgeey.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtjogdlmcu.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtjgyxdgnr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvydsmeu.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjxviwbt.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtgoptbhip.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtldwuknif.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtyhqdjeoi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvhbsuaq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtzeafwvdx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gthnxvasqk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtbbwbmlfn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtitdbupge.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtqkhlmrct.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gtwsapmqpn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gtrudddcng.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtbccvgkxt.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtyclcxkma.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtlqwyzrfn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtwxgdopwp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gttfzhngve.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtceggoukl.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gtzbisevfw.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtftnhsoau.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gtmoghzrdq.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtjgajeqnn.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtbunylomi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtsnxgcaue.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtoimhloqs.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gteagzdngf.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtiuyyfqqr.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtmtzrlfez.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtsozpgorv.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtaezymfgg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtiberctxq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtcrykqtzt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtpvldactj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtlgwvdcwx.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtfpidnwyx.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtlrbfrkko.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtxfcyumjk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtaiayrfns.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtwsvhcyqb.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtgvahcrqq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjktljoxd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtezshipcn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtqthksgsy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtodpjoxqo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgctilzmk.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtkqsxibwc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtflfqiutz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtwsnecruw.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtyfypwrue.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtsvfdlluv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gthgtltcet.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtafmkfkod.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtexkummqr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtaeqbslnd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjnqwzia.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gtfgphcown.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbamwzrmc.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtkmvckful.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gthhvridqb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtptutjnju.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqywuswvv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gtcmhnzlcz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtvmzffzua.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtklkwfcjt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gttunfttqv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtosreflkq.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtofcvsurg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtozfuhtyn.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtwkanrmrx.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtrkdbkmzj.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtzxoptgfd.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtvdxoofob.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtydaqlxfn.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamoeyngv.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtbjjaxjzr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpmcvhzwt.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gthjohguov.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdmyozejx.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtywquwlth.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gtxtdvduyc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtxlkfcztg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtryxsfwof.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtktbgdklt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtfsqlrlnl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gthyduhkhr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtsoshqipm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrnbtdif.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtagghxwjp.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtafpyoyds.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtqfkmedxa.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtihxjpntr.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtrorkbjhk.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtzwnphdgn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtrsjtqfpj.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtzrghxbkw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtkafntzri.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gthzrmuwmp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtwceedysk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtagmcmxhb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gthgewtixj.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtdmftnlqn.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtfmcvtsbv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gtupxmbunm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtifdizxgw.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtchuihvji.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtlpgudyvm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtnilfdovg.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtrbubhxoo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtghltnmuc.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtsmczwmgo.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtzppyyoef.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtxpfarlzi.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtlnidmqyg.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtgibubhcz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtoohljipy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwppnjcqu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtiinfolrw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtfcysfmjb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtnyleqpow.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtoeyncsra.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtenhfnkiq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrclwykkm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtwkgcyrov.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwfovfxl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtmmczizdv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtaeguanuy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtskzuqqei.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtuojgjjlh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtljrpojtj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtfyhyhhby.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtubqrqnww.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gthvzfpane.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gthzyasxns.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtxxvfqcwg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gthgypgswf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtbfxohlnc.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtjbubpaai.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtsvjtuucu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtbndbjmmq.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtioxftvgu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtdmyelxlq.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtcdnfvjli.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtflnhhsta.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtucckgsqe.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtiidwewqf.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtqagwtfyj.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtdamyajsv.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtznlpoecx.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtjtekopse.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlbcgywb.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gtjwlwlcmb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxlrmjnw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeuvtbud.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtpnjimiij.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtfwgopkfy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtztnryoei.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gtdbehoeau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gtiwzndxwi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtebqrzqqs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gturoxxyym.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtfjqjulnq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtcuvfvpvn.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuqsspra.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtblomvjsw.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtkiciooqz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtjcmadohq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtkpmxmfze.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqzcrylg.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtxpxptzzu.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtwygkrzyh.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtklzkvhwd.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtcnwktfby.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gthnueezcc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtoflbxpsm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtercpexdz.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtujklplcn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnytdfapn.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtfzxrdpfn.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gturlwdbwh.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtcovnsjrg.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtimddcrre.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtelyicmix.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtrqczyppc.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gtzitwqmdt.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtznztfidb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtlmrdoylz.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtafeeeuxn.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchsydfoe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtzjyjuedy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gttcokofim.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtjwtbuxur.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gtsoivmnkk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtjfdpumxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtpckvrler.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtpwspgzmb.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gtifbebidy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gttksezxag.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtndfnouil.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtlncrenmi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtgkthzrnm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhgwkdge.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtjwpnhhyt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtvrwimhxg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtvkwvgvbp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtoblxlgru.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtbxlmcstp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtdfqwtzjb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gtxfdycphm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdyztalpq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtubdezbio.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtcyjbtolc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gttdenupca.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtdzqthuur.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtahyjwqjx.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gthwsgvgmi.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtoaxasuad.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtfplzvmgs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtzxevpmpw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlahwdngq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtrcbtxdpe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtcbguazqz.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gthfxijvdv.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtcqebnpwe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitpwgvrw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtcegwjnoy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gttjejcqdb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtnezmwbsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtmudupulb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtpnsjzpjy.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gthzebddhd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtqctbkyxa.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtoqjzbgcr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtrjqmvzbj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtpbameclp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtzzrndvvw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtdbfmxgny.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtokpsluro.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtjxmzguso.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtoazkezzm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtebbuglfs.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtrofdpuzh.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gtrtybtbds.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtnzsljctt.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgxixbpx.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtvumssmud.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gthtobpbuo.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtjhifdumk.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtroonzkwn.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtyehlitpd.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtweriiuix.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtzcxwfmdl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslzorhqb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtkmguvoqv.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtstxtvwyu.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtbeleduse.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gttwvscpyz.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtcgojtcga.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtnhmpprat.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtvozhzzxf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtsngtvyrd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtnbimzdkm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtztrgyhtm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtyifwsdkh.html


<!-- 参考信息 -->