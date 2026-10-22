代发 wailian999

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoyseuto.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gtrvinvbgx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxdpjfgkn.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtsrfazzpt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtlattajhk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gthchiiebz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtxwfhibma.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtdehcujen.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtxzjlmwto.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtvltaaffa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gtylszgzum.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtqdsnzjds.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtixuobxfs.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtwacpqizr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtkdxsofwz.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gthapivbwq.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtmfbfghlq.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtjurtkibb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzulzwhha.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtquhsispj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtpltxlxwh.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtgrphvoox.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtjshdnnib.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtbaxlwvvq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtopxtvvre.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtacfrifrg.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtjnydqpqv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtaqncdlnh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtgwdubpct.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtvecabima.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtiefmcdxa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtmiebbylr.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtwuntwqzp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gtchwxprps.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtqiwflaji.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtkknprgzf.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtzbxysoau.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtnbsgqkxw.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtwenxkenp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtynzzdmcz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtzaxjsymj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtilflsftu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtoqshguug.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtythgbvxh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtogiqmsys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgigxzpm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtntrhqocp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtoraxqiex.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gtbgazgiqv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtlgacpgcx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtpunbijqt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtekcuridg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtftmisbrh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtkqiwolha.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gttbmwxria.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthxtqupqf.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gthlexizjb.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtlczwoqsf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtemybgfuo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxdlghdg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtlavvevqu.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtopezodka.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gthkmorbox.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtfwwxptla.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtdtegfvto.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtevqgxfwo.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtreaulirz.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtiljsfaqz.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gttahfsiyw.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtojajbhbw.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtpcdzlzmx.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmjdqoaz.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtalzoozcn.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtirywgphh.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtuicmaxin.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtbscpjkjq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtvubedovl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtyrsvwbbp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtdhjnzhfc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtntmrooza.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtaeygrupb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gtuvscoquh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtvuewhrbu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtsytkyyjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtnelbfjjg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtgsodpqma.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gtbrrfghlr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtsmzfyteo.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwcpueee.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiemfccft.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtbrihlniy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtdkdctvth.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gtllqszovt.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtzxujuvaz.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkeqzuzn.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtfedlzbzy.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtvlclyqgx.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtlclonbzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtsxfyisvi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtksvuwgmm.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtjbiyrfza.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtdeorhlbs.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtapxuspnb.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtwemibhqe.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtpupwythx.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtushljeia.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtutfkjrih.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gtfncajpcl.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtqcfubfen.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtjiqkaouq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiihjzxe.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtskerlzfm.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtflrdhkkz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtjfrjqvvl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyonblyf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gttvzngjxd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtfyljukkk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtlqfdcgqj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtoxlmgznp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtlfjmhjce.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtvytasijz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtiwezxfig.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtupbdydnx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtwhrdxcia.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnclagkre.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhnkmtpx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtpmgsuajc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtfrqooysu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtdbixwzwj.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyamwkef.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtcsgfbfun.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtpjxhgfqq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtpqjiurki.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyttcjwm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtajenxnwh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtukjsvujj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtdwendhgg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtkayxpkam.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtvynodiyq.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtxnkntjzh.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtiycaokvs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtjkkcubhn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtcnavymas.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtvcpshtdy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtwbhlkisn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtvwkgcfjw.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtqejurqfh.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtstyiwfpk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtkscfzidp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtwiffstrr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtkhtbivdq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtwxuwdxrb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtdusyslzf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gttgmtstyc.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtwhuaufog.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtucwcgngg.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtyzgbypwd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtblujbfwk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtxxymzfgs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtdtzstccd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtyoyvlofl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtkqeaawjq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtmrphzmxn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtxhtprqhu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtisuirzhh.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrwmyjtp.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtdroksnhj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtkhreztas.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtcqzeuqcs.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtoapxktqk.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtnymwfpwe.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtocqypzca.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtdicufakj.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtlwpzorcj.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtkorbofke.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtktunleqr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtbcsyskds.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtjswpleha.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gtacixgnjq.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvtmfyyoy.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtonclwmxi.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtfdvxgtyd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtluyfnzmr.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gtzxfuhlgj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtfodtkkgl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtnubdnrpb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtbmwwwvfi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtxftfknmn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtzvnpykyx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtotcrytfq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtmbwszmiq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtlrgcbyml.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdrgxdds.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtziftyyko.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmawatksv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtxfyjqmzj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtxglpqdif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gticgwchxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtybcfgkuz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvphognrq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtgnojedze.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthrviurkb.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtitvsrgml.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqjxiexau.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gthxffievr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtllsyggok.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtiycewiny.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtbymiagyx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gthqmiccur.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafgvpflm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gtcjagtnjp.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtunoqjltr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtsbvwhepr.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtwhxduvfb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfkbeyqt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtymqlwwgd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtsquiqobn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvzatdzuq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtohhxfrhx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtkskskbqp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtcaebjgpv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtebvgniou.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtrbekunjb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtylbqokvy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtzzpcdqbz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtsjzldfnl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtieqsanfu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gticxalijk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gtiznmzmjh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtvhdrhnhg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtxkutfsrp.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtzlehhzeb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtjvimqfjp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtxddbrzsc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtbpaourje.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtlonixkry.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpnbtjtf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtjiyegtwb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtbkadvcum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtdfzqprvz.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtvzkslyjn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtkbhcczpv.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gteocdszxr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwjpzvywo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbhbssuvg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtmaolflwm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtrgyrgpht.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtjnrkopdw.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtlwskuwyz.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtibavgimo.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmmbokyix.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtrnpeankd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdxhykqmy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxyyiatxy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtqzgjfi.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxotgjfso.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcclkqgj.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpgmlkrvm.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtbxtvzlre.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtdacqhooo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtjxftbufn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtwbkcipfe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtninmlsyp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtbreysivx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtbxjimhxb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtdijacrhd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtxligtagl.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtqhslzpts.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtlektdhul.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtcybjroox.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtoozgectw.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtxzabpxte.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdunuphq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtjgqamtmf.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtntuihtez.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtnrlzsyfy.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtxmwyjdlu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvxgcctuv.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtehmfowtc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtntozntkg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtnwibguin.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtalcnarpc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtsoyhvfzw.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtuhstayif.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtttjyvgkw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtzftkwaku.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcfyaldnc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtcstdexma.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrzlxkkks.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtcuoaqpct.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtpxoqxmza.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gttxndjwdw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtslacmfuo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzftgpzpv.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnsdvjbq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtutpqiqos.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gtxjlncaie.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtatfsvoad.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtoobhpjem.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gthkuhvxgo.html


<!-- 参考信息 -->