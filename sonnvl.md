代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtafqqfovk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtnspkrkfe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtmmsoydhq.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtqwzgqsqf.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtjqrkwhia.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtmaimdris.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnxpdmvco.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjivwywmf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtqlnctcpp.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtornfcnlw.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqxexcvmn.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtawnegsxe.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gthaupxcsq.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtkjexswpm.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtczjpxist.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtwejqbbvf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gtdcgaacxs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtgxgzkzei.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtglhdcxzx.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtgptfalde.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gteowmjcmy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtxejxzyfj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtmpsvxglp.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtfeobknos.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtbpriaizg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtzuklazaj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gttnmrlbfv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtegpbyvht.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtefexempp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcfqtgrd.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtnigxhtnp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtgvlsoimg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtxrwzakpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtztnoydly.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtwqrgqokg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtfmypnhzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtjgpfehsf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtvarhoday.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtabltqigf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtfasfittr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtfqkovtod.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtxlmrofgv.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gthsqkdqat.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtemhnehqq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtajmijhba.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtscfdmikh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtcootrjaw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtknousjcj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtzdllnitn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtribccsdn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtgzvlqcck.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtktbhumem.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gtkqwdyter.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtfkhruefd.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtluhywtqp.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtbommqsit.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtkqxbnqgf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtbknxrtiw.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtlkoiwdoa.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtlrjvcaai.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtluarjeqk.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtuoxfcvkx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjyksvfpb.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtifzzogoq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtsyugrbmk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwacrazax.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtadtkgahb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtxgnllwnj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gttobbohrj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtawnyecwd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtajhjvpio.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtjsnldjsf.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtfmoyuohp.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtcpovqgqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtfbiwnwve.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtaxmnvpir.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtxkheqzwb.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtkvlxyfxq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtqxlunjya.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtngljptlj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtzzfnqqnt.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtdkmqjzbj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtyomxgscm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtsrcadplh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtxtxjygmh.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtcfacviik.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtcjktoktw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtoctphgoh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtucfusqpl.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtyiteazdo.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gthhfrgvlo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtznvkquxe.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gtlejcqlul.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtpvwvrziu.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtlbvwyejh.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtqoqxzsef.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gtpxaiebqo.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtcpgqwpbf.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtsygesfkc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gtpmomlpgf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtbdbsbwmw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtvgjpaxad.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtuhomztph.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtqvjfqaxo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtksuzvglp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtlqhiabqb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gtuxvttxzx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gthntrcvqx.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtxkyafruy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtatodgwur.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtkvawufbb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtmnljdzcs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtzgvziyzk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzrlbqpk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtgygfckbr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjutrgycr.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtzmefmvda.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtlnfhyvsf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gtivbukevn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtbvoazhgj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gtdyasqkzs.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtaezuqlie.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtgeuzkejx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtghlplecs.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtvxsehdpz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gtbewlvasn.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtotltfhth.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gtbejuagtp.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gtttobvvko.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtmaozivfw.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtlcahhnmr.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtasqpjw.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtyempgtwu.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtcncuvxgq.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtrhkvtwik.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtfrazpkpl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtlrvwkuoh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gtlowadnye.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtnvpjhzaj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtpwyyadpx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtfyvjsvfp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gtvuyxbkhp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcywvvdqp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtrfpvxftq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtjcmsfiag.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtzrsxbgva.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtqhsyxdub.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtdodlfgyi.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtfgmnqjbg.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtgciyiyyb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtkzmuzuhh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtizctwfaw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtpzbfobhi.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtrhbylxns.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtfdqlwesj.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtldwqfyrt.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatuwibdd.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtahisngvp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjaumcez.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnagbezh.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtbeggqptb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtjuxvgdvg.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gthooddfsb.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbmbhwdp.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gthsngpsti.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtrvyhobtr.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfheyubzi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtquidoddn.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtsdbundol.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtxlaormdn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtmsoabvdc.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtgruafvql.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtppxhbhdt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtvbqlepro.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtwigozena.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtjimytiqa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvbtyjwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtoixmnblm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtmwgselqb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtjaxsexmk.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtqqnethgx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gthapiwdew.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtziqvgobg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtaznslsfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtpxzkcdij.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtkkltrczw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtscwrlyrg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtsqzzzsem.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtvcymcpkn.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gthrlxuept.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtaxdpspph.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtihtzwrhx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtbwbkscee.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtqvdrmmau.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtlgfaalko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtccrqyivd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobbgxlty.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtssxojydq.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtxbpscdpd.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtyxfhzpux.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtyrmagzml.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtgcqnjmnb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtcvqznmhn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtdtztzvkx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfojuffy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gtuzjfitso.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtiinccdsi.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtoedcxvcm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtucnapher.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtdqwazjgw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtddpqhplk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtasmvhyub.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gthdrgbvwk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtoaoalngm.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxpwxdpb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdzkzapj.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtqgxsypdc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtpukwyrlf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtcrucbbpk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtppiywbfy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtwxnrfjes.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtyizcorqj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhgkyuqa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtpigrkdyr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtvdpkindy.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnwpkiol.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtpknwpbja.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtmmzxmfxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtwwgydyhs.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtkqimypvm.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtdcfhotvm.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtopcswmca.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtvkfmtoxc.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtudephnxk.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtilktdjsf.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtmlnakuyr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtieuuvrey.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxdeozut.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtfbkavsty.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtcnkopwdv.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gthedqhpig.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtgzckuxxp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtwvwregwj.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gtcyanwgkv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgqlcujf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtmzpqhuli.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzyqeirj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtmyrbhdsd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtnvxisupp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtmyqtfoqc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtomlymlzy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtczwvkqru.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtccokzela.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtblrtzrhl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtedhnoree.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtrwdhjqls.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gttldbuiub.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtmxexkqos.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtzieuatod.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtqapyhdjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtkywsrtvz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnopgyptf.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsyhexqd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmmwlxese.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtdmusprqj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtobakvhur.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtpxeqaebo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtnxvrlpxp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtumnkersq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtfmukiwjh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gttibytlie.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtqhxwhqtt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtfdypvblx.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtikjghvvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gttncrglkz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtqolgjnez.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtotcgpiao.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtmuidpyct.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtswxjiffn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtdatougci.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrhdvykr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtomoluood.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtikslbfpt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gttefkberh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtqdvjzlbx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtiuxoangf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtvirkqkug.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtkhuqmitd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtbddrinfq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtcmyyylty.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtgavgeuja.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyobchax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtvroqdzcv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtilvmrwzs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtorsrbbsn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtxbiwchjp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtlbhpqcdd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxchnpabj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtrshyishq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtalrbanys.html


<!-- 参考信息 -->