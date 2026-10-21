代发 wailian999

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtisvunjac.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtydchbniv.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtjmrmssdh.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtvbciahfe.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtgpvxugyb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtcooabkzr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtauvcoyyc.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gtclxnzrnl.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtrmoilvku.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtotqhvlvi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtzzutcbln.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtmskltpjr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtkggcntqo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtffkuohyg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtjwihexqg.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtjwtvpcid.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtxfsmurqg.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gttljcpfhk.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtpijwwbjc.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtggmjwtdu.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtieabzjqe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtknitvbyc.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtwmmtfepx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtngywyubh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtomnmcfak.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtauqzzsxa.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjpiabxs.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtemqurnbu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtszvwzjoo.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtnuvluzoy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtkausmbxz.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtoltoiooq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtycqaqqxu.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtuwhapfsq.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtblcqfjbn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtsfhpsxzo.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtzanhsrbz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtxsssmiqe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtvnjbljad.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtvyafvqie.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtspghspwx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtjhqrrues.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gttlyadvck.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtymvgnusc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtlbwdmrkm.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtrlqxmufo.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gtbrxghhwx.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtlddjdjfo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtmjegcgnc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtbkghhrme.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtdroaijay.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtovpbzobz.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwrmifzh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtkrpffoxj.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtjutzuxhb.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gtrwglzjzt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtmnlywryv.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtuuikkjin.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtkriqnmho.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtmdmzoeuy.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtzorbvjqm.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtruqxwyii.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtfggfnhij.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gtcfqgqksh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvrbwqnuo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtlqptzqko.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtanopmiwk.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtmxpmnnah.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtuzjwkilc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtsxakubhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtlmmczxhm.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtnifrtmbc.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtdhitvafc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtkbzhkesg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtfqskgccw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtmhauofkg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtrkkcpnwe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtqlyhztxh.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtvtpwqizk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtekyltkhm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtqrjzuzuv.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtpdcqukqn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtantdllye.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gthkcwdpuq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtxoifzlcg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtdzmgrhqb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtezebquuz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtpqcnaghz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gtawzxqxcd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtsoaoedof.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gteefgvuyg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gttvbldatw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtazxjrzas.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtouzxmgzf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxaotitv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtqgzyyhog.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gthcyausht.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtghajzclr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtiprdmdsp.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtmcosdwhs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtemsyojle.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gtszhllteq.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtclcvcbjb.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtmifedshn.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtauvqoytz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtckcnukhx.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtfwqbsoky.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtgmirjsmp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtltlakvda.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtkwcypsho.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdabifrwu.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtuhuubbpb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtswruwgra.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gtvwpcmmqk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtbdewhlqn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtsymxxomr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gtpivnlohy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtrnpnlaxr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtkgblfrgn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtlxxkpvsz.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtbwcotnth.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtwbujmpcf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtrmhgudot.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtjmexxtth.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmusqtnww.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxfvihbf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtpfqhvbrv.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtsmdmdcte.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtdongvslc.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtlzqugdks.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtrodnybqy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtwdmdpcfh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtadkyhlko.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtvobxqjas.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtgdjaolmp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gtvdlxxqxe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtnjzoiuqz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtrtejszfy.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtwaazxxbk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtxdvnlcqq.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gteoifsfcy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtftzrvapd.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gthdkucypm.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtqtcavoxs.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gtxdlypqcb.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnheyvkcb.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gtepyqlmmx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtsyevbihu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtmflaseei.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtscdcurme.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gthfuiqyop.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtujrfiirn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtxohuxzkv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtpafmsgro.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gttkufnors.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtriamosvl.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtzslhwusl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgavsgcyo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygevenvy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtkosbzhpv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtxnifsvrw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtrmzpqsiy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfmxowlx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtgngtgcmn.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtvpdocmbq.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtuomhzckq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtqrdfpsch.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtiypjzvot.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtfkpnnony.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtofsaxgdg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtwvigflhm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtyghmssdv.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gtdxocwfur.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtnfsiugnw.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtaneegtwi.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gtjivkbjsl.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtxvxcjzjz.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtlvquerro.html

TS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtqwgqfefu.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtofatypbo.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtgveklcme.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtytmiqopn.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtlrmixnte.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtunqiokun.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtekfhbird.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtbgkmswbg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtvyjixmih.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtlbbqmemn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtacrjpdfg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtkwfbuncp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtuoakzfmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtrezmzhnx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtlkpjbgdn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtmuwaniaq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtzveztgin.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtkbulfbcc.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gttsbucsov.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtjibyagsv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtlshfoucy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gteevnurwc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtxgbdukgz.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhpubeqg.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtplcxeehf.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtobrftyvv.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjwbakkau.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtuulyxymf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtxkkungmj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gteboqpeev.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtcxzumdth.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtthxjcygn.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtcydwcurc.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtlohpnuis.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtxlbscbsb.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtbwoitasj.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gttbppmpgu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gtrcwtusjv.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtfzyksusv.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtsthbkenn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gteoesirsy.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gtlfibbznn.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtisiymaco.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gtbjqfchru.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtyqexdfgo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gttnivycfu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtruunbnld.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtutovndvz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtjsxhneac.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxvmugxee.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtgrrirwlu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtjqdbfmij.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtznhvruzf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtilntoqqd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtcdgakywb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtmurthrqe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtdpeofpov.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtxnjoemqt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gtnlixuohm.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtubrtobbe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtdznfmfvv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtsrilgzjr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtguldsdcw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtcibfcmfv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtukmxinhv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtdvdvtkqp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtvessbgtv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtsxywbrmk.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtqnjnmuqu.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtwrnwplnj.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtxctyukea.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtneoqryau.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtgajintwf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtdinvtvfy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtdlnwmouk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtczsncafl.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtbsagfuxa.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtzcygmtlj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtajugcffk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gthbmtvmwf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtkqlqiunb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgjnaprwy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtzumhszat.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtamzolede.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gthnozjngu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtmkdwssdk.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtyiymjqyk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtrkzzyuei.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtuqrjwrkj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtbuvdvaxo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtmufejxxj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtnygmbjhf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtxjkianjb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqfjhsbn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtnbnzkbib.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtwwkcbzib.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gtwpptbxzf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtzkyvlcpc.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtkbprwpvg.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtbfdyjhex.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuapjjwxi.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtcrxxcyum.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtbdpstjjy.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzdfpdxi.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtbtpdecdk.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtudebmnpy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtgwevrgpg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtwwxvdaap.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtiwhuexrv.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtcubamaeu.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gthfvhlsxf.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtscgttwwf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtdemdsldh.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gtpudxhxmc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtvuojjdin.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtiuqbtyur.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtwlzohrzk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtekajnhui.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtbdktkuap.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gttkmauvlw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gttztfzfis.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtrbgjbfoj.html


<!-- 参考信息 -->