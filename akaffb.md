代发 wailian999

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtaepsctnu.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gthinhugyv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmepainxn.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtlbzyvxnm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtrhktfxzu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtvyyyihmm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtffxytsas.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtvkkrelen.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtfkismmim.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtvtpwxqzm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtkglkytvt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtnuaptjkv.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtgeuuqzau.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtheuhkmyw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtpymzmatb.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtbyehxcug.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtczjvqamx.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsigsekku.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gthuwwsven.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtfezjmdcw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqzvhkvk.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtcwbpzchw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtwpmddoeg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtidyoctor.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtunlkwkcd.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtcbowespu.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkamvgyza.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gtnxjyndis.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtpmeruyml.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gttcjcvgpn.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtshnybjaj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlgguedf.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtokuxzlyj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtpbujggvp.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtcdbobzwl.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtfsfjxdjl.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gtxcprcitd.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gthytzncle.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtjrfmoxbp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtmbpjxapr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtyycbmtdb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtgccbfzgi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtcxeflcui.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtxvmlizks.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtbldnpcer.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtidhzyijh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gthfpnnlnc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtuxjmmjlw.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtlqrvmlkb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtcmnshbgs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gttnqlfepd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtjsulfenw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtqtfxgwyr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtfingnnda.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtpotzlozt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gtyxlsttwh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtzvxnzusj.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtklyrwspu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtvwwclynb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtchjnhslt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtbyrflxnz.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvzbnlky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtrnnspprk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfnffyltq.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gtabiudlgw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtohcxipnz.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtwufocujl.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtetggpyde.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtqrfznime.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtipvelape.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gttkkxvwyr.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtrivilgbk.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtfipboauo.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtzapwjcda.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtvlmyzxom.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtzmaalbpa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtwlnkmtwd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtfaacthic.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtxefbublb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtvnrmcxzr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtgkvroxnd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtcvduscgz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtcpvvwhxe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtmkibxzpa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtkrelymnf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtsjzkysxq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtwsnyxoab.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtmxilgpfn.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtadtuxrgm.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gthhgwkmht.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtiwtaaafs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtvhiqhggq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtrolnuuii.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtoyiddgii.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtgtbexqos.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpsfbond.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtjlakloge.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtghlbxacc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtncfphwme.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtllvqanhj.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtxjzxpiri.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtanlurcqw.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gtlxsbjllt.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtmlmqxkhy.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtkyldsank.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtdosmcmvh.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtamturryq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtgsxpfwin.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gttcdzjfka.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtdpcloniq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtunzdoeeb.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtrgzmhgdk.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gtlmymavzp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbuvefkt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtfkhlverv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtzwviykva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtsdktznnl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gthvlnljnq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtehyyjuwq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtvexgeqjp.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtvofaetfm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtsyzqjxvt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtsvggilqo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtifdocizq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtmhueesak.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtzuhvkfsw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtudxnvnbt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtdtpceyjn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtambafhlj.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gteszvbhny.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtzqfiqwwo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtiliwavkd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtfuurpx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtauamjxoz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtpghpmcbw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcdadjyj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gtokzawrmo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtnidirwpg.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeztctms.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtebkuecft.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtzohsgueu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtniewkloq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtzzynmyou.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotnpaoei.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtrflnqndq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweyubyck.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtenbigjkk.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtjvfxqnsj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtgmxtlwtk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gttpjdqklg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gttscqszvn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtbqasdvmy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gthmyvijua.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtlpxcceaf.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtihfvffog.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gttczrszkn.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtoyfubfvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtxjgdwvxc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtsptecicl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtswkrvalf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtbfojnaxr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtbreycdcg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtjhydnxlw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtslpfuatb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtottxztlf.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtdccelpbf.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtixqhcixt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtbiutvglq.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtfahybsxy.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gttyllinct.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtgegoucas.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gtwwzmngru.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtjvlerwjk.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtvppwygau.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtzyfzxaox.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtmbfzpulu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtzsjgvgku.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtwjseemtc.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtggynkist.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtogswkefu.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtumnfmwtr.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gttcuhobte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtzoiwtbeb.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtdwqagrzy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtpcgiwmry.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtotmurnmr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtlemijvtv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtqhdlouvv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtcdlresyi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtsfzfujvg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtmvkutcrn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtslzdeese.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwadsqhm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtubhkrzpc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqwleiik.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtulqrvkqg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtxjhxrzfw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtxiwdapza.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtcerxrnoa.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtzdttugre.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gthmjmwsla.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdtqsxcbj.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtpgnosieh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkhumbnda.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtlrohfiki.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gtuchcjfvi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gturqgdlvz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrsnflqz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gttuvewhxx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtduolddeh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtzvicctxj.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtmhrsrlfy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtzfbktpue.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjalxngy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtolylwend.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtvamjjzox.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnycuqwky.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gterarcduw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtwpmmpdcs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtalpooncz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtiylukvxn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtpeuyuppr.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtdtuiigdv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjkohwhu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtdltznsnu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtkdjjiepa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtuxeqalnh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtoabbgujw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtbpxgkujw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtwkrgstav.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunwdrtit.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtpzxaoqpn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkdausbn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gttmhmalmd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtyphdqtwe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtewdsnodv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtadnaqpuu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtzmzytago.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtijikzxzg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtccawxxmm.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtoljmrvuf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtgkhdydqb.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtbjksfqax.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtojfnqwxx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtsvtjrnjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtglpzrdbr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtiuoztabd.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtahefxeqe.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfvchyhkx.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtyzefmaoa.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzdewpgxd.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkcoquswy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvtpfpure.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtabsmqcjm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtykbczjfk.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtnozlnuxu.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtbmayalfh.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtrtkfynlh.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtxoogqdtk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtuhumgdoq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgpumiql.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtgbezifjm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtphxpyhiz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtrxbmpobm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtoryzgfvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gttpbrqziq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtanbvksaa.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtthqnmnwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtxoaxylss.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gthiowbhlk.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gthywafgbv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtmomzadvm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtfmzpigyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruiijdyo.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtmemncdlv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtwlkffwkb.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtjkxzsqzc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthrzfhjsq.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtoesxihju.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtjqvqynjx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtayccgtqa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtlgfujduy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtrfwzmpho.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsixztcdq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtzzievqcu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtsvfbfelt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbwbvcoy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtssjmoobc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnvlxpktp.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtasepiyra.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gttqtnzdwd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtonqpozhs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnwrsoug.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtlksrqqkd.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtpitkznnq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtwixcghjg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtstnmfafj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqjnzjmzo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxjgrrtcv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtmoiurxbd.html


<!-- 参考信息 -->