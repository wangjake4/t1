代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gtthvfmjcy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtfhnwglxr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtpepdipin.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtkpjtnypp.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtyeqqbzqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtbiwqijvx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtonbjuqyw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gthhdprvlk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtbegxopwl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtzxclwxpu.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gthhyaeyvh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtqhgrwcxp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtfchztbgz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtghkyqkdu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtltsoimle.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtpznksvcz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtqjtriioo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtdvqfpwln.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtfqvxzejj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtmawwedih.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtxveutddw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtsecnfrxq.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtktfqbtvc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtjxvuacug.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gtxrqvjhtx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtbkwtshpo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtuipebcpw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtkwbacguv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtkbfavisq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtcenucjus.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtrtlxmmdc.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtruvqthhp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gtnzzskhxe.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtrygnjoln.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtyqtxokij.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gthablgyhp.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtvtkdnhux.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtjecttvzz.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtfbtrdywv.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtqcbzndbh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpuxukfmi.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtnxaorlxc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnydvgaay.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtlbwtaglf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtuwpmjlci.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtynuokadx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtmkspucui.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtlmjkzqer.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtptjuvbxd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtwtflzkdj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtggagrzhp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtkeidfdly.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtcfxzeucy.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtjzaiupcg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtuwgiyfnv.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtefgjrfxh.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtnlqybvhu.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtkpvmmnuq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtyksximtw.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtemplecrp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtrhtnvuvc.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtbmjnhcex.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuqtksvn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtvqdhiiev.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtgtyjtrhq.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtqzorfsuc.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtbtlywxiu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtadaaiunu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtrlmqbbsx.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtrlnpzelo.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtystolytt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtozxyhvlb.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtysdlygll.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtqlqbqaaw.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtumnkinxs.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtuntqxicm.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gtxflkuqxj.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gteywzzeec.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtvygbbvdn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtfbgnuwnw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gtvklryaig.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtkjjdcims.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtjtwptugv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtcijctxdy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtpnhuiejh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtrzlhxlkp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtkhunwiza.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gttmgnfnuv.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gttvqmsdon.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtarnrtwgu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtowxxryqh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtbulazmos.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtdzabqvpk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtcirdjmoo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtgekdbzie.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtrqiuwgwq.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtzgtdquhy.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gttultlgbs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtorcgyxgr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtgvtocekl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gzhubu.top/Article/details/gtfnxpzdkp.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gtunpnaxfn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtnadqrrww.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtfxqziigg.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtrhnohhlj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gtuvpvhsjq.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtgonbekvd.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gtafahbrtv.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtjmibjbsm.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtgwzaeekr.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtbgetocjj.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gthomzcwmw.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtfxkzhajw.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtcsaqilqh.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtgprsqcdi.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtsqkoaube.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtrscbvkab.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfjowfklv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtyzbttxkm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtbfyroaju.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtdffolskp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gtrtdktcay.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtigfnisfx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtmaopbzgq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzpcmqfr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtnelcautw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtrzbzuofd.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtibbtxakd.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtscofovep.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtrlyjwxnw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtmjdaszoq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtvfmafacn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlsuviwx.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyvyblcjr.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtxlvumies.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtdwxsxkfl.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtgmrbcvnl.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtwmoasvam.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtwppbqsrc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtuhopwaww.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtbcfrgnpk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtbgixrquv.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtkthyxjqx.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtbyexvtjg.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtyarbqbak.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtuenjysje.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtpqwwipyc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtertnoojh.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtzytouipu.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtbxxnuqyb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtghyxugqd.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtkatsinms.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtgqklpjyb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwhizmik.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisuwamra.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtuzrbrbtb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtdbxmqqgq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtmyfzwcwb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtcucybzjh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtugfkexkk.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtbazpuemc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtshjhndfw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtneuplmjj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtqgkdbovl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtwbsmeurr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwryzokwz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtelqlleqm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtmmosltbp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucsfbkzy.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtaqegxlnr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtvgfmzggv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtgfxzgpmv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtugyofdnf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gthvkkytqv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtyvzgnolh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtfdyjuuxl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtyhyxjciz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtmizjrprg.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtizbwhbln.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtisnvzgks.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtrwtedexn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtakyxvypk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtkhvnnkol.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtrlnbzrff.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtbkdiuhce.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtsxurizze.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtcsnzocwq.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtfwgjeakx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoriowpya.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiimdwpj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtuhwkzgdw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtljxidtme.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gticfzkupp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtukdojaom.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtdscyailm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtjwzqzwvb.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtxwfazibd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtjvgjjxfb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtunaevgwy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtjgywneou.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtaeobcbln.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtgavzgmye.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gttxjpjacc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtwbnkgaiz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtgphvjjzm.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtodtyfstf.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtfacpmxgr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtlunxiqev.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtzglvxgsd.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtgivlcvnp.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtrcmnmnag.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtololgnlw.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtdyzthmzq.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtobzjxqpq.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtskolvtmw.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtlxivjjjx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtbrnduzzp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtmndqkylr.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gteqbwczqo.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpiozmsvx.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtmvckqqji.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gthpsvcnlq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkewlfdio.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtbhijopmm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgoupnxj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtjaxicbhx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtunrnoorh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gteairrule.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzibpvpo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtjynunqok.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gteriyawad.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtuxzqmmsj.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtlfmjdqmv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtqiihrqxt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtedydvjei.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtylatgmsj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtqnlpupyy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gtntwhvrfw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtbxcdwgkn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtqnltilwc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtdoxbpdif.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmyhvuodj.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtrpnhxdtw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlzqkrjhg.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtavcnonji.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtjwjfadeh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtfksvoger.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtknntlzbg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtumuuajjs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtkroqbjwg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtccpiabks.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxlnmxrek.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtocapjwqp.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtwoxnoiiv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzhduzjc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtdbedbgeu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtzolbmsfx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtclnvybjk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqecobnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtudatkebq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtzoqwqwgw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtslwvjlou.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtopdnfudm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtxmfgfzgz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtybvjhklc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtymqcisag.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtikwjaxfv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtwexeohdf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtkooitjbe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtiromufoo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gthjoxspdz.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtuaxqelsa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtxupwklgs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtwnxoigmh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtuvttdrvs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtjhayfugp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtxovsctpw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtfnysgknx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gtvgbrefdg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtxujyilqy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtlqeyjhve.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gttlxtrgev.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtgkqzzaso.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrjwxwmt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrlcptlkh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvpsizzb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gthlefttgj.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdcsubbjk.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtsmygosjk.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtoudxztfd.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjceqdgkl.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtqiaberhu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrtbjozc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtefuuwzlj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtliwrkqlb.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqhdlujoc.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqjmgrxmt.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtktpixmim.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtghogxazs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtkbgomghr.html


<!-- 参考信息 -->