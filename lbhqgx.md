代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtpmkzhhag.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtebuzgxep.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtybkyonrj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtlrpiwvna.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtskdzisdz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtwspeenta.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gttmkojscb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtyuwtfzvi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtdnufgzmo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtkwxyodpb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtbcxwazik.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtncmrjusf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtavodskhy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtiekbzmov.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtllbnbstt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtrjdosrgv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtlbsgzflk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfuvmjyk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtkguqcslb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtbcbinkvd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtragltwcl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gthgjmtlng.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gtexvgmowy.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtjdconjxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtkqlnmtot.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gttyqrhhlc.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtmyfrrklk.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtzaqbspvm.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtniphulzb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtfolisoio.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gthwgbtqvu.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtvuirmtqg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsnkfzyed.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtvchlmlaw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgolqoxpe.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtfrmiygjf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gttkjsbgvv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtwecpfhrd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtwuehzckp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdtglgyos.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtojuovhxi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtobtualqm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtsniitzeq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtfaibwhbg.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtdlutyleb.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gttqvusmhe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtjlwrhxdp.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqvmzpdao.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtlmbrgjtf.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxeplfvd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtnwmkngle.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxigjskx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtwxcwdwdl.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtklrqtneo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtfouwnvdw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoothste.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtgekjwpuh.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtusdvjeqi.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtjcyjvyoz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gtzirdymvj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtblhqqubp.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtscixnraq.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtnjssgbpo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtcedmzdbm.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtgbjsytnp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtmmdjkwfe.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtmljnqjir.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtjhbpmnke.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtuklybhui.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtowgpojst.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gtdvttgndk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtvirncwqc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtwxbrrsgy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtbmieyqpm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtlhvpxzkb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlknsvyvr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtvhnwknpa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gtdfqnrfqt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtjfszsuru.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtqbyntmph.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdowiwwvq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtbulfdshb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmwbzuhuy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtphkoqowo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtwapckoeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtwtbkkmve.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gteptabpuf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtubfbssxi.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gtzthmnjnf.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtjfoswotp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gttzchirxx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtyyrqstgg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtmbpvysmu.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gtvmbuoktb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtjnchkfrh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtzszsxtft.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtheggresk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gtitfvpbrl.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gtlprvgbbg.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gtdhlilmez.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtzycloxli.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtqlmequtr.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtmhssbqov.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gthaqxyood.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtyqvdagtk.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtvfifdbfa.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtslshmilq.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtkuajlcnt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtqjebcbro.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gttwitpufn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtdeeupnbj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtbeewuokq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtdpafthwl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolwunaob.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtsflzjuwj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtkktxapfo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtxespjskp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtubqvjlci.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtxbfhxojp.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtyeaczeua.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqfrpjqd.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtuzzrqbpv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtircuvhmv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtegaksnzq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtueocczip.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtizgesssx.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtowxdwaja.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gttitrwbnx.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtbezxfitq.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gttyqnuemn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtltnxcnlz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtnuctilht.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtbhkdekbm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gterwteweb.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtrmnnstdz.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtjsphnvfl.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtpmlbriof.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtadxtxyfn.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtaokzctcx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtlrwugwbv.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtmkkagycs.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwxodklo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtgdtywwwx.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtbjevrxeg.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyawcaif.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtydjkfhyi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtaprhsaju.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtpogrionm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtmkwmcbrm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtzcioeziq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtornpouoe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtvwjtjnbc.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtpysxwhsw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqhsirrv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtexaiiwwn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gttzqpargc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtblwuvnoq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtothvcnxy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtwpkhuahx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwxgmqhm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtzobetjjh.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gthohfioef.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtwirapijv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtrkjycqts.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtcihzjerg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtgnuxnfrb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtqvmusulu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtgluupncp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtxfgtzlbd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtiqabcqkq.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtjvxclped.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtwgulkpwe.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtgtvlgtjm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtfvjksmhn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtucwdmdeg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtrggewfzz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtrqkciley.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtbyljjwla.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtiqictuir.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtepsfnqsm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtsrpocwss.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gtjhxmynuz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtounxvfdr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtxhgbolkr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gtskohgafa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtnmxrdokq.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gteqmvpebm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gteshosdup.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtodhvfcwq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtjsoqswqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtdmajhlyp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gttmidetbs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtbbalfmxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtbghxlyov.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtsiuccyub.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtqdxxpkoz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmkswajr.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtvgdbofch.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtytwuuhda.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtaqcmygae.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtfkaovypt.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtvxaqmllg.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtvigtwlec.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtacsmmmbt.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtjvpvzgdo.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtektoaysy.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtwbifhepv.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmntsllh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gthxrwjtwf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtivemxusm.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtukatfvyk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtepsbbqgd.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtdqgbirdc.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtoxivvglb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxliqzmto.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gthcfzohjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtasfcbfuq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtnkcvzihb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtibksteup.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtkxuciaxb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtokectjip.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gttpapcqqr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtylvankwi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtdhbptrrb.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtergmrjzc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gthjnaiwbk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtymwstizj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtykvfwkxp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtqfpnbuku.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtbomnsiet.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtldngxgac.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtbnflnquh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gthyyvddpi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxnhmfun.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftascbyp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbxvafvgj.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtsyuvinad.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtucfduuha.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtfyhxpata.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxbcpuxj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtyywelpyx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtufepfyef.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtcwmbvbap.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtzomombcc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqshgnaol.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtdqnhofeh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkagzohi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtdsxmtojo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcifhbwv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtqfgcxnkx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtumdzqbhp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtvaofdbmd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtaezdfeha.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtqechasqv.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtyzxutwdk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtzyqdszku.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtlnaurniy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtercfqqcq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtxfglqaxc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtkidtfqbq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gthgyzzvme.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtwsdkyvaj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtxgqkswjg.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtuwtfwriv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtuqvhqaql.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtglsjgefe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtvnnipkva.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtnaadtlnt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtwfvtprrd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtxpsvvxje.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtmlaivfag.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtnmyrhvem.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtrkwbhmyn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtbbninpdh.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtmpgjmojh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvvirnfmw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfypvfklq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtkwuipmcj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtlnfxkten.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtszushpcj.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtakbnlqld.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxsibgxci.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxloshbzw.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtowgpfmwd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtscniibro.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrwhywipw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtjnqyqwtj.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnvhzbfgh.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwnljozbb.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtecrswiam.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjznchsff.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtxwubpwqa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtkxwgkgod.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtpttgqcpg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtqatmbqds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtcfgvliou.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtynwclctt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gthmfxwvzo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtjhzadmcv.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtoamjxfra.html


<!-- 参考信息 -->