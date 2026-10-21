代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtckbfokgb.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtxbduxyyu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtrtgulosr.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtgpofevyk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gtcufcppnb.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtaegckvwy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gteqpiwizg.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gthsragiov.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtsjmlmxsn.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtmwniwxor.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtcsehykaq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtwtlpbrpi.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtuiudpelr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtjfvmprgc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtqgvzfhdp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtwekyqlbb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtyyixhipi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtzdvrxjhl.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtnvlzhfuw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtfthtgmbe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtrchbttfz.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtyoypnkgb.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmtkunmy.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtgsmaiomi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtkocqkqlp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gturswvfgg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtrhgilqlg.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtvvzdwhgy.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtadyputeq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtxusmlzli.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtypxsfmth.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtglewxklr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtwbkeauto.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtdphpidfz.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlmsqghb.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtphmokrji.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszmewrmk.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtruonepmf.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtyekoaeip.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtrmnedrnf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtagjazwyl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtkodtjmdi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gteducqnxa.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrviqoyi.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtzusbxusc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtkshevqlw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtvkoodzfa.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtkkepfwrv.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtchyrtkpe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtrobmoxgy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtaraqaixw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtcjclcidm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtowfwoqzz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtbpsjcxgc.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtpdbexzaz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtxgtgehfa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtffealcwy.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtyropszpj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gttrornyco.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gtrgtrkwka.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtlhvsnapk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtxdjbpnrd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtcigrmwcj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtawejylrc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtvorsmweu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtveftxhil.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtbcduuozk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gtwqkndwhz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtirremmim.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtapwvfbnz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtftyahcbd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtbcptpyxw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtfexkyitc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtdxykbrwo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtvzcfaini.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtqmejuzeq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtlahobgks.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtdnewgimt.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtwrmhcxqr.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvcnfiwg.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtglqypafz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtoqzwtggy.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtqqyoosan.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gtvnjkeaww.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkshzmorh.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtlcwelxzx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzzitjqbx.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtujfcyava.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtilzspqvy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtuqmrbcah.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gthsvwhoyk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gthwdztjqr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtjjknzxfi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtzaqbjcjr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtjlfywwht.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtumaaqnur.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtciqviwdp.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtuwuxwenl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtbbszvldk.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtymjsrfre.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtayewitje.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtghyrjyrx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtatlplxub.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtxxqznkrf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtjtoqxiys.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtehkmikcs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtgvekdbwa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtykmhpiij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gthqdtkseq.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtwqpjcwmw.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtsmjjqsgi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyjvgcxc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtmqzolxtq.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtbryshugg.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtjyoqzeya.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gthbtqhyva.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtvidfvzml.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtjhvulepw.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjriitdem.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtvzzcjbiv.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtrppqgicc.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtocpuhivr.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtcnosigvc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gtppurbsun.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtpqqptjne.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gtcnmcfuwh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtmrrkzakp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtlkyomypn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtswtrhvxk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtisgwhdsn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtccoedamm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtkqtgkyvo.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gticujmwlg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtenjuqyvp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtetrcpzij.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtqfiqrvbz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gttthichfs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtiirujufz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtiepgbzrx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtoefbcrzq.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtdfocosja.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtevxesaet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtuahvoiuk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtzwocwpby.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gthifkktfh.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtrznymbad.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtpvdktwsg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtlftkbogh.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtlqwqspdg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gtqioedsuq.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtzrdwshfg.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtpssvjrmy.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtaqliroim.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtyijdlmso.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtnxtuepcj.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gttndutoto.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtgrhxhafl.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtlrcxayab.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtmtvsnfwy.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtrjcpktnu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtwnkczlbt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtiaosrbdz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtkmdufjra.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtzmxpwchs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gticgwwnwu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtngrxgtwn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtvczvqokv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtkpbyhvoh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gthrmxbxjp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfqsnejb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtgsajbnal.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtsfwokfxk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtbwwfwkoe.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtmilhgnqy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtfsheudqu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtnwbsxqzi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtifamhvyt.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtohgrxfns.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtrakwnvow.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtgbqrqblv.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtcfckpufe.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtlpamfonv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtlzfldoeg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtdmgeervm.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtxeiishwj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtyctqcngg.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtnanmdlsc.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtjafbhrix.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtimnrbxwe.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtculvlvnn.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjxabkltd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtjgbiwhxc.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtlsenyboj.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmicqqxlh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtqucftpcj.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtwonxycwi.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtsoddpcal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtiglwpnpm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtpcsbfdpn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtajtxtrzm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtfxdzihrk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtzeyggdrw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtddxfafzc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtzgdnjser.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtgblokqos.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtlpbevlik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtvhmhpzry.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtdptetltc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiquscso.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleonjwfi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtnnxwkmuk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtqjykbhqm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtgicvzmzl.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtwpkulduq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkbqowcln.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtkfweizxq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gtlejmfryc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtdnfqcsno.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtztjvenkz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkgjofjn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtoehsogvu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtovzetyqt.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtyatefviq.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtvliocfbd.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtzgtquave.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxhbbpog.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtafkmwkvi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtwnktjclp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gtbkaypyah.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtumhkcyvm.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtzqpwnodw.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtxviktzwg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtlinvwdhr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtmhybafeq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjaybshnp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtigmgdyzx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtcbyrrskz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtloukkuwx.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtbboofbbl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtplxdcdta.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtyenthflt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtlegunenw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtqjssnqfh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtzxpeocyb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtktjghjon.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtchahostm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyhooxni.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtptcdkrsd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtzsdgvbop.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtuczfekpl.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtzfotmzro.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtksduyvxr.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtpraupftx.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopvlunlr.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtqhiohvsk.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtfoobhcpb.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtywjzqejp.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gtlvygnbhv.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gthqmhzqdh.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtlnlulqqb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtjrlfoljz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtcfvmgafb.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtlxjsfeno.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtriijgpzg.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtsghgdroi.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolecishu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzlyusvoz.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtjoqzodvw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtewlrnqii.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtmelwfbvx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtgpmhkcnx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtfrfwknwo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtetvlyodt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtczrutyjb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtecahfudh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtsivusqao.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gttodrkffk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrytqrxmd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtoelpgegk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtigfxxsqo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggorvobu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtbrucavfd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtphwbqjnl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtvjywfwsc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtizuuqwny.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbjtsfoda.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtnedmqcwx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfrovotlb.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtqjkiujjl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtmfjibfnb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtqbwwwbmt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtrjmkxrjs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtoeyodkjg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtitsgkiow.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtnvrftnar.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzzruzyri.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnlrsqfbo.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gtckdsfhrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtxkmemvlw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteywnafbj.html


<!-- 参考信息 -->