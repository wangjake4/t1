代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtnazhxzqx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpklxupks.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gtmcpefhqr.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexpaqzej.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtuhseuewy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtslkjdzjb.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gthzuohuiv.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtydnuulll.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtepczchsq.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtaoldikgi.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtdsknkzng.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtyyiczqjj.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtotnozqlk.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtjqmrtutn.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtjezoehxm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtjckjygtp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbrbfujon.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtjibevbky.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gthadcddzv.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtdxcptyvt.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtlwxgkswx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtisbfut.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtozlmtjsp.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtqcodnrej.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtkfwhvwgx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gtdrvpyviy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtpwaturpx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtnflryuut.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtsspojnas.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovjbfykk.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtanicaolk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtgvypfgwl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtspacuabg.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gtyeltfbdc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtogljagwa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtuapnbmlz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtncjrziot.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtxdqfvuaf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gtvswkctgo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtbvrxnrqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtjpfrdygt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtahkfrkdo.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gttexjxznr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtduqgemwq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtvwbeasdz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcdptdwq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtcosccxsq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtfkotpcnx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbkliqtt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkyqxciay.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtewmerxcr.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtrqbmnezs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtosbyacqt.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtdcsddgwv.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtgxarmrph.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtogxdeyfd.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtjjjxhhyh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtwmbrdjhh.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtrbosfakd.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtdrjqkiwf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckywsbbn.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtcxtwbxlp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlzuafruf.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gticqwcgyu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtwdfdixsr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtvnerfzzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtlwnjfcmf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtntyemhig.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtuyjojosb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gtctxgaaum.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtnlblnoxo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtggvqrtcz.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtnqphroij.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtabxyngpr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtalgycaqz.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtplrvbkom.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtxlodnxmx.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtmndbhopv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtgcvpqabh.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtnfljzksk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtaycaggvq.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtqdsdopax.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gtjodydsik.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtuxvooveh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtbsvqhoys.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gthafclejx.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtruazhess.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtblbkwoei.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtmvtaucno.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtxgygqgvz.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtgurveyhh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtcsfowhmb.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gtoypzwfpp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gtlejsntat.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtrlbbdbnu.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gttwhwjxsh.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gtyxfejkvo.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtzlnjxphc.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqsmzcfo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtlqnegexe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtemvvfkvg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtahahxmzi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtvxeiianh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtexlqzbwp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtmuzixbny.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtrjudnhnn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtwqnyxbwb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gthktdegmn.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gtblxcuwtz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtbmzifuxz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtoanuytwl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtjvfdxdje.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gthxyzgsox.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtpkgydbcd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtowtiizrv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtvebvobqd.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtaytoipoe.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtvstidrhh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtvnxiowrf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtbzgkdogq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtqtvwytgx.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtrkpsmgtg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtxscqvqbn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gtltacmnbh.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gtsrpfjgxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gttiqpeogo.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtkjsvjmog.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtoqbllosr.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrxjpfqb.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtexjhsgme.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtlxslvriq.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtrygccsax.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtovrrdemm.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtervpiacw.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtavqwpauk.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtgwintsox.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtaqrwrssb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzzeksawb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtnqhflxkv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtftzgqgng.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtbaezpufl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtqmvwjujl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtcxkcirut.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtzpkccxdx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzkbjijw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtwshbsimb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtqbccejwl.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkrjgpgu.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxkkrnyj.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtqzuakxmz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtvugjlbby.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtfisznbrb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtsymdcpbf.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtmdxgsafi.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtlvxgwlrk.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtxmlymrfg.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtntxiyzmr.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtjndrpynk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtggrfsulk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtwtgtaxwe.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtocxxyjbn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gteydepnda.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtyvtcrllu.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtgjtwrwen.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtrfxoimtc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtoncpdteh.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gthtgwlmsb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtxlwybpfc.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gtubsddvdz.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtxiwxwnjz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gthhhfykka.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtowsbayox.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgfnrdql.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtriacpovd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtphtnodke.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gttjmbpjoa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtkvenmyic.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtqekpftnk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtncnaiqkn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtaptssqso.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtqlsfujur.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtxyovexry.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtsxpuzhko.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtvsdlkmze.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtmghekqfp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtxcppvdtd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtpznnpvxz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbmcwmmo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtlibzjzpo.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtzfrlxqhd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtleferbdm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtxvzexavo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtxgicjcki.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtbqhfkivh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtjgspmyfy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtyslupqbn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtdfbxlvvo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmzmsopfp.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtghfwkhkr.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtygwnjuto.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtitryfqyw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtlhtwjmse.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtxusbqpht.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtkhqmnvrp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtqslfuczr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtpxymbrrk.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtpliwlcxu.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtnzfklmfw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtsvgtlzro.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtxobfyoxh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkiwllbmv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtwhmoklqm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtfpbukism.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtellfzfhs.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtcxsrtoqr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtduvtkukz.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtcboahlvd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtlodujxoo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtqcdnfydg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtttsbzias.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtoavyrqus.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfsislzu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtjorllvus.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtkpbgcevl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtsvevewfi.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtgrfwcsof.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtkzksmmho.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtaihxqgbe.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtdzqglnjv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtittwpdxh.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gttbptxgvg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtqyjiorjy.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtrjxmyzoy.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkyjnycq.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gtwlixqftl.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtgfdfznug.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtxmhothho.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkbyyydrz.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqbovcze.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtvmynckxn.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtpyhfxqph.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtavbmecfv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtodzipmdg.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtejnfvvjx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtmosmucfo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtyavxnfso.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gthesphtqs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtxbatuowp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtusjyelah.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtgwkjyxnm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtrqhjtdip.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtbrvkewei.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtizxbhoxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtoeuixatv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtjrltvpkv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwyoiiki.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtebyvosgv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gtzussylvw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtgkunapzt.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtjccwzzzu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlxnqthe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyjlvltxv.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtbdoxdlbg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtztwghoxc.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtsoguoeac.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtzeoxmebt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttgyemtok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtgokgaohl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtzknqdgui.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtpyuqgihp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gthchcnibf.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpgkkrked.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtrkbgkgxn.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbjauwxy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtaepyyjbs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtckezkqvq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcylpdvnl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtgxmcqnma.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtcglxnxku.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtqqfljzkd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtqgddxxlk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtpdsygryt.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtztlvxoqn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gteojygmpa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtesiiehgd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhiwnzme.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtoabiebyy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtwdaibzqz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtpdyvnowe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtclosumwn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gttwlhspzh.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtijeanuoj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtpnfyoods.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtdrfmxmjs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtmzeizfzg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtjuwtyugd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtluuwqugd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtnqerrvyt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtlnuklyxd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtubadgkyf.html


<!-- 参考信息 -->