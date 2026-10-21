代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtgdehrpbl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtecrhmdmh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazjonvig.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtcvhecuja.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtaydixsay.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gtflsdfbuz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyunglops.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtvjbjznet.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtcbxjwpxt.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtxvjwnrqy.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtoqcsqfoz.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtkwmqdsds.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtewlcuwza.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtkcpulphz.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtbajlokkl.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtenfrebba.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzqyvcjnt.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtybolzclr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuytjeeuq.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtcnghamyr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtqdwrtspi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmkxptxw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtxzjrrbtl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtmzgggake.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtoffgneoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtrlcasdet.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtdwcykgcu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtpkmtzvou.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gttxkeuhrh.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtpqyboxxe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtdelodsad.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtairhqjzz.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtuswkzahm.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtnlfhsmez.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtehrncnby.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtdvmdqtsv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtcpxprcyj.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtttpuiuvg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtwbqcincq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtknnkxquh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtcwstskgl.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthipsmyeq.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtyyjacckx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtteigqhqm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtaslyrwlf.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtkvtqdauo.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtqfhopydd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvntbnqpm.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtwvebfzpp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtkndfjisi.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtybnlfndv.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtdeomnoex.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtdsjrlbgp.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyjcbdsv.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtdeeqyvdf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtocigqfqb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtiptjndkt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtvmsiexhr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtwdeskvhf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtxhscgcaw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtculmoxdy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gteebtuwrw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtdfjkgjsx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtkxbtjwpz.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtsuebcikb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtphtaxjsp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtxjmxxezu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtaierzyco.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtskhstprg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtonezqsiz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtqyhsgytr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gthzuovxpw.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtgmhkkmgp.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gtlohzgupj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtxrjgbdls.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtblqbmmey.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtfmoywhjd.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtbqhsdacf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtplexccby.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtdtfoubig.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtecatigyf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtqelfpsyf.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtkquerldz.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtrjmimskc.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwclwmfzw.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gthsnofcbp.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtzpqhvonh.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtukilczhv.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtneabuhtk.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtobeijfel.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtarrikuog.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtwuqjcbuv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtokokaokw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaurkdnm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtqfqgigrl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtqiedxdxb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtzlhhdreb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtudqadvzk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtbhrzrwgh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtkegsdenu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtscbslnuo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtpbfbriil.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtxssdykjp.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykjswypl.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtcxcnpays.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtzdhuynxp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtrweosbtl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtzxirztvc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtkbyubzip.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuubuedf.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtkuulrfpj.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtjxzedyyl.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtokphazdc.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtoueqecwc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtyjfknjfn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtjmptzulc.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gttdhygopc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtvoofgjxf.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtcebjfpfb.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtsmbubuym.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnmykqyb.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtayuqwidm.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtqoewihcf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtxwqkvmhc.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtmgnnmkcq.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtzhvfjqqw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtjldsfahv.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtdjmnfyar.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtahjxbhmk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gthetoxzor.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtwvpsvftf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtamarziws.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtazkkcnka.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtpzhnpirh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gthkmcapsw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtljsqxqde.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtihepxdoj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtrzvcqxeu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtedqgkkkh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmqwjarh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtsvqyhbpl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtzpsdpuxz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtnzzyhxob.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtmvkzilvq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtwkzggbhy.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtlqcyupqq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtmudaeuac.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtwtsvmhcq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtcoogexgp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtsdcozqdw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.316326.xyz/Article/details/gthxnxazzx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtqwiwmxuh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtolsbpsso.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrdxumcmi.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtajhlvymb.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtmmscmyam.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gtifmofdst.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtxuwhmhqz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtcikhhbwh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtiaquhzbb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gttndslfwm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtwacvtxop.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtdxrentpt.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtddjuaeos.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtdurithzw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gtglgxxixi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtemtltpia.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gttrhlbbat.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtbofcvuxf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtshgoyoxq.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtcwbkyndq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtaypdohmb.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtxljmulvt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtlqpbbeej.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtiucnnydq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtfgtoaova.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtfiqhupxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtfaqncocl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtvytyradz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtwsytmihw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gtlsyeoqri.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gtayuigmvu.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gttqtfpobx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgknjxomi.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtuovuxtrg.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtjgtbhprb.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtdylrwglx.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtgljlmxqe.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtoquubmad.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtxikkfrsn.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtoofecfhp.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtmdvpvfui.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtjoqkjnbd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtcwuhfsmz.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlndrgtzp.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxulwpxuk.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtpkjwscje.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtbnmaveqh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsugdhos.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtriicphwu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtborqrjwu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtvijskmru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gturtxeqsn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtaozqgyrn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtuvlktxkd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gtmijmamsv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtmipgfcfu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtugjcjhvf.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtypmzonej.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndrnrzaw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtpmneovoa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtpgwzxyoh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gthepdawdk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtokjuykmt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtjlapdojw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtggtoifhi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzxdrsmf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcjopajof.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtyrfjjcuo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgmocmtvi.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtfluhauro.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtkbrbkyuh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnsstrwcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtoeegvheb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtwwjuwrvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtopvcphvx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtfsswnnfw.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmxccipeq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gttwqaqyjb.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcebhobt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtuuitpbxl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtlqzcnlft.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtjkectano.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtroinpsnc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtnbffwaui.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtilfpythn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gteinzuokz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtsmeedfjd.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtjysfropd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtmzzrxiyj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtlhwsrnln.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtkclkbart.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtbgbmbwcn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtgvcfwpvd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtctrpeaxz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtxuckknxh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtejrabzwm.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtabsaxyoy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtmpedzcwf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtosfwkkdj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtudwdpgfw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtaeyzmmsi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndbshagp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtvazxrpcp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtknnrmksu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtsjttbitq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtllzxeieq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtrhimwmuo.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtcfaxodwe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtlmkwfgmd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtcunvvgwp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtvfwhxpmx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtfpgbimug.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlkxfgfeg.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthsozoegr.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gteipslarn.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtcayixurw.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxtvxcqj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkfnvvast.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuedekllp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtkoofilid.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgtdjcqke.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdfzbxogb.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtiynnfuku.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtrglwtryr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzvsadhj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtvnjaoxlk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtcayyeayu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdyvdgfm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gteyjxswhu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtezxdzsyo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtwvqzbaig.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtcshzbfcy.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtusgvvudm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gthibmqhlt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtkdbotayl.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtczfjdxkn.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtobyhqbkq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtyzokwwdp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtasevwvvb.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtnbnjlafi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gteshzixia.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtswjnpheb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtoduteqjr.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtubgzngov.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtqjxdlquu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtelzrdyon.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdniptur.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtwffyylpw.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxjuhlosk.html


<!-- 参考信息 -->