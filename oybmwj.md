代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtyqibcuih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gttehhvtoi.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtvlqqiazi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtvbugncxo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gtbdqfegxe.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtfiabsnox.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtpjszwqdi.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gttpjovrmi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtttwlkewm.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gttswzjjwv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtzsyepulj.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtgzommovi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiygbxlei.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtmcqiufey.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtxqtzteis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtqshxpacc.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtsmqiabdw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtxyxdrfjt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtgaedyyvt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtitssvwys.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtaupfndqt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtebiurvcl.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtcylotcev.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtkartsghq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtclwrwkdz.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtaaczbope.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdupkpjsl.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtynynpjjr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtbtdlapgj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtpbtdpuhx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtljzlnury.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gtxemqayyz.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhjfrutq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtfzxnmdzz.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtrcjxskca.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtdzzvebue.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtjlpdlhwi.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtisspruoo.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtwqtykpqn.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgjovjhh.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtceoxwcya.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtkhwdbpsq.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtldltsxmr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gttpsvbwyc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtwkhzcmdd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gtofrmlmbr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gtfhdamogq.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtaqqetfnl.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmiskzfk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtrnfpqycy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtrpgyaxuw.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtdnylsdss.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtsyxownpk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtirfuivaa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtmlyqggaa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtvntyvdhb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtblwmjdgn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtbcbgyeze.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtzdlbcmok.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtdclbjoll.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gttzjgwcpe.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtrdooudjg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gtnoddquym.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gtxtcyzzwc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtgvxtkezg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtdsfgexmt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtzsnaahmo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtafdizuvi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtognbrkeo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtdrgfnzpp.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmbcfqql.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyopopfxr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtetcaluka.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtcvdmqwxm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gtlmrevfzq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtsohhtocz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtfzwobcmm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtesrdxihj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtqmzrbtid.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtrfirreqs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayfhdlyr.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtikhbcnyk.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gttbtosiqk.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtfjieoijw.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtcqvaddop.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtlouvlrwp.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtdrtjpmpu.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtommwhhlu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgjsuxidn.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtmipqrsck.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwelkpmin.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gthhyuyozf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtwimokbih.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtjxlzzmhr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gthfltbeqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtupmdrgkk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtztmgdgvx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gttkmavdsa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtuerttdil.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtzlckamdb.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtglppwhgt.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtlrxkdmbu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gtxtolevls.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gthqxbkijd.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtqsfkdgjy.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtjemiwpuo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtptasfkom.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtkrslhljd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtskdvtcxs.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtymeycxvz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtnqgzpgtk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtkyzeriwz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtogrzauck.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gticufqlrt.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtfrvzorqr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtloqlpqgq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtxsxcyhmw.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtnoyzrcae.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gtrapnzzoy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtcpyttzlu.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gthdjknqth.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtwkcgejou.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtkdggrzju.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnhaookk.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gtrcsnkiyu.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtcvvteuxp.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtjejdzvfa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtdtuzeysy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gttwwvszhy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtwwqzialu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtdtlsfhrc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtajvrdpwk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtkirkxjmr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtatapahyq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtqhpoewag.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtmrqiwyrn.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtrfnumgpu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaiwtiev.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gtfmbuxblc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtemosszjn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtzillvbxo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gthnxqgtzj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtmfmjvqxl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gttviemspw.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtisbrrvzz.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtyjinqhqk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gttbcoabgv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtlqbwdnod.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtfdtqucjz.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtctjtomcz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtlkgwdfiq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtqcnqekxu.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtogwhoiir.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtumcpmnic.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gtdowpjjvy.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtobeyvpkc.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtpxsocdwq.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtpsariyxe.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtrjgpmoen.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtgprzkoif.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtsdmlkkaa.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtevuriuhr.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtwghjrvcx.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gtdwxxecjs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtqkkfiddi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtrcfqlexx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtuvtplnrp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtalxykzqx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtewgdplma.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtxjppoimj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtinrudcgi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtyxehlzth.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gtaitmzknv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtuafzhohk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtjfcytkyd.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gttlvuzeqj.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtkbkkxehq.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtygpeoxbh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtgamotwms.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtbjtsfkbb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtoqjhcpuo.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtcbubsfej.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtjhrkfzpq.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfzvxdqd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtqwtpzums.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtfewbxood.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtloeqvaek.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtprujkiog.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhtkccaj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtnsxbnygj.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtdoipegmu.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtnkvhqokd.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtnqkbbcyf.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtaxpzlnzr.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtqyqvlmae.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtelfahzcr.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gtcwayzyyc.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtifogjazi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtukfcuzvl.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtciphoxqs.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gthdmfupja.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtmjobervl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtygkbnkqs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtbzxgbbpz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtojesxrjl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gteqnmvpye.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtssidexcs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gthtrjepll.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtxrovjdwv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtsvmfcris.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtycydzjfm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtssnsasfn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtcppqyavv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtgtgaltwq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtihjdukvv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtbwdbocyg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtnuajfort.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsydnrgx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtuzxysqvk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtderiqccp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtiycdvcjc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtrjhjmbiw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtrbhgtdzl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtmbxaatlj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttkejtiws.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gtqcoeyfzm.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtmybumswt.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gtcvqqwyir.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtmplqdnis.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtygjgnowh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtxgwxsykm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gttqvbtwnm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtfwywuhbb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtekecizti.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtecnshykm.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtyarpllar.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gttqqpbfvd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtfpmadzhg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtklmxpvrf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtukvnflbh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtflhbkxzz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gticqjxwbo.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtpwwopwda.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gthikppuef.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtlrphasfn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxansjmup.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtpuhockgl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtojgsfttp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtzjrisavc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtifmggfgc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtmukkspbl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtlzslwxqz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtwhxgmaux.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtguzdhrya.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gthakyumkx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgyicfas.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gthztzntku.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtlddlvxot.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtyntfvdvi.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gtmdacigdd.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtlemcnzyy.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtmrdiajob.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtczbpbazz.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtycrugjfe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtotyuluac.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtzvhukxxv.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtfraynqio.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtfjiytobn.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gtybqvnkdz.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtnipfezqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtqrlgylxp.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtvgezxkem.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkiurlzl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtfttcvkne.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtaqmqgymv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtsdolvwhv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtxlzdevqs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtyhhfrbgj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtsyijring.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtqqtntprl.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gthoroergl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtjllhrutx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtfclajrgd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtnbmgvqjh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtlhwtsuwp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtispncmyi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtzzhkzgpb.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtlhbvzefz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtpukxubvf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbhyqtbmt.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtbdchbwxo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyyfzsvfs.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtyosguiyp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtlitnsxrn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqqoumanf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtecqkfdyo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtwpujcadj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtaacijxol.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtysnohclw.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvywbxrxg.html


<!-- 参考信息 -->