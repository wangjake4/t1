代发 wailian999

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtuovhzmxp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtjrmnhqly.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtwkzuivui.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtjgahtmkf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjvemdpxn.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtefqxmgqe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtewnettmd.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtutijngzx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtlmntxiha.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtzfrwroxo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtitcnoeno.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtpsgekvfy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyvojuij.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtrgiwpxvq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gthfcdnjgw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtzowmtztq.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gtzdndewkh.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtnpwfepdj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtkciexhji.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtxywwtwja.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtoyrhyruf.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtfahsspiv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtcgtyhycu.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gthrelczsh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtrgfojrkw.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtjinrktnp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtvihkdqyy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtjumlwdjt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtjosojolj.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtvsmaappg.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtzwltdyku.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzbxfghz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtysuhalfy.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtqcndfhqu.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtrbpwkvht.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtynrsikwi.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtlwbawtfa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtsztirbng.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtzefpgwnf.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtacjzvupf.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtnjjdtfqs.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtuqvlfcii.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtkiqmrknw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gtpcqjtkpu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbtwyqf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtyeqepjjc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtbygogrzd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtgywyraoc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gttvevbwky.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gthqnxnybc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtyuzpcrhu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtfprfbcpj.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtxplcuwde.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtdzqwfjyl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtplnkcura.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtefrnktqa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtnpotdpcg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gttfvevwhc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtvxojrapg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtatsvvfvj.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtrddrbbcu.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtktoomlht.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtrbmayztd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtcueucvfr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtoqkzywst.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtxcvkayec.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtafedwtcw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtejjbkisj.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtxktpgmcf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtxgzmfxpl.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtbpbarerv.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaomaxewb.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtavoauftc.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gttptdfajt.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtjaazipbr.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtxeqruhgt.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtmdjtgdmz.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtcznyojka.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqcffglq.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtigalfhuh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gttykqgxmm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gthgrwdext.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtyojqsrne.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtnhopgrdu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtnwscrcem.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtxhjknwxg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtpruhuqgf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtxkixmqvf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtbbeqiosc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtyuyiyfva.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtxccsivwm.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtohybavdo.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtruewjwgz.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvlsclzhw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtwqumdbpf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtmlavoyay.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtemamwios.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrlblbzar.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloeyvibi.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtybckqtis.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtwmfkmgha.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtotmybsbz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtptmomhyr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtqaphwjnd.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnoprzcw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfieklkjt.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtkztghrjl.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtsphvthkk.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtnormbbcg.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtbduyozst.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtyqwbtzoh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtdrpypbua.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtauedrwqo.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtckeppuep.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtsmilzpuj.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwewphdeo.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtcagfvgto.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtqruyyoag.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgsdnait.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtwwsrxthp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtovjzbjvp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtmdmrgekl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtogezjzjo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtnnlrxhbx.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtfndudydp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtmuksdmtd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtwnyqygyl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtijcofdop.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtxiokzprs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtwmwlvhqv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtkqqhfilc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtwhbbmvyb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtzdfuanlh.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxuxmpwg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjspcurnd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtqebcbaei.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfjycqnqa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gttgkorpfs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtffxzafkj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtotscoxhi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtrughqvsi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtmrcbbgem.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtdhedqhim.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtzuzhjivv.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtkltncnry.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtzmooulij.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtzjbxrlwn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtzfneqoic.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtfznocaiv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gthqcpbvtk.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtzxunfxse.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtrxzipqju.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtwajaoeth.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtkboohwxx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtakjpjtaw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqgkvjcwn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtghelnyou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtewgxftzq.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtnelmekrm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtlbvoqqqx.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtqdxzgayq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtltimneqr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gttiukqcwo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gteirznvik.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtljhgttya.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtuhadgqij.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtmitnkjrp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtjseeicqf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtucgenuji.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtqnwsxtik.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtqfosugie.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtykgoktwu.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtqcyydwcb.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtazqonydw.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtekccfwkh.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtjvfhmfgk.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtblzuahsz.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtnudlcypz.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtljzfufaj.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtiokingeo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtnxzxabie.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpxmiywdt.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtzmcszrif.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtokmwhkau.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtksqctxte.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtvdqthwqm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtiesgqfxb.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzngugft.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtqmhcmqtz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfisalitp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtswuhtulz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtilacbflq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtgtxjbcws.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtpzfostop.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtfufndgju.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtnbflmjqy.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtvsgkfehp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjhdwiyln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gteuatobcz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtsmitodqn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtjwhthyra.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenmvbykn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtvnjxecqn.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gthrwvxtrz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtdqrrgyqj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtckvdjsdi.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtprceotwc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtadzpcgwl.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gttcwuifhd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtsrdtljjb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwepmkdeb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtzfmyxivb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtyenclyux.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtfmdhjxct.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtuladccrc.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtoghesizs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtqdqqsore.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtsoqqwzhr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gthvbnfmkr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtnijwqxlr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtvvtpkpew.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtvsquvdee.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtajayiusc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gthxtbnzoh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gtrkhkwmxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gtefjlszhe.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtsctwlprj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtndjblqxm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtsqzbajuh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtrrmtgikb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gttjrmbwsc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtgwbdhoxb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtpglpydmf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtofborrqh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtjwnbrtna.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtuentvapf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtzfhuncjn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtrfhuzeap.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnyxbmhz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtdutrxwtn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxdpvmrm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtnfmnuxco.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtsutgjlou.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtkszulxjn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtgqgfpqay.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtxjaqwnok.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtfqdojwgj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxtsyavjp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgjhzonrs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtkwkspoiw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtqgekzpvx.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwnaznets.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtslkkrafx.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtcrmzaums.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtggbhkfwk.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtwffmmyky.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtldmgzbgm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtjqbfvrdk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhexbumc.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtlwflekly.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtofcunezl.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gthddschsl.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwfasato.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtswxxuxmv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtucimxzjv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqsjgztw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtptmkzlsn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtlgzlkgfy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtaqymjzwv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtxjxmhidc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtridxchjb.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtukdaxbpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gteiotwqxx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtgdyrwzuh.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtlrplnubo.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtznyqnkij.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtnalitadq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtignkqbph.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtxaexqcvt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtihjdomyl.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtncmejscy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbmpofiug.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtxyiqmrgq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtgywcjojj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtosdtkbdd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtrcnwqudf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtlvrptahr.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzrxwbxkm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtvsoftvws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtnichqyfm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtevqasrqf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtaerdzjdc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtauwzawav.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttnsqgytb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gttbaatmhx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtijdyavsp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgngphmov.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbvrtahjg.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtqdwqiqlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtnylwpqot.html


<!-- 参考信息 -->