代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtbsnzzlxa.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtpthakfqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtxlxmcfpk.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtllqbgynd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtdccjtgjs.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebfjvqko.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtyszmqrng.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtiawrfwut.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gteqhztkcs.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtqlmitpzv.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtcyktzivf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtpvkqmxxi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtkbmqjhyz.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtamqahgwc.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gtppftfgqx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtcghmcihn.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtxbyjmfzy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtqsqtgxiz.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtkimnuclj.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtieegefal.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gtyurngter.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtyuustgts.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gtbamrzwic.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtbrcveaov.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtswltthch.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtehpgqvxg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtqtypuago.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtzcswgsbe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtzolqponn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gtjszlanup.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gtawtmqahp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gttsebautx.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtzbqysrje.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtegkdleqe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtqsbjccga.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtfedsygyg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtnfcvphdd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtxuxvuhwv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlnxgtbu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtqekgvysl.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gttikvkqpc.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gthgllitdf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtkdshtncj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gthwnghhfc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtgwuwlpql.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtztpjvqys.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtopscffab.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtuhkxlmpx.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gtgxbgkubw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gterbytsqa.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gthdgchirx.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtjlskgzpe.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtdrrhifaj.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtzwbokekr.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtfafzdogj.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtqazjikny.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gttmfzlnnn.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtwiihtimk.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtpfebgguk.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtxwqkalwh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gthhmkdyel.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtcwetklno.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtfpaxxkzx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtcjdppvzg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtfspugoid.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gteubbjnqu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtwmtixqxf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtxnjyxglp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtzntgktlf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtfibosejg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtotcgdacm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtclbzennt.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gttuxjusvn.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtdjrmqxqg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtacnyauvh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtibejskus.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtjjoedyxe.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gthugvrnsa.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtgpqindyn.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtbsykotyg.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtpehdjqbj.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtqsfdlxyb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtwqxyhumi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gttyluixsh.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtjvzoqpug.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtkispokeh.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtsrxvwtef.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtgujfznib.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gttcapjufy.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrhyncad.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtpjqmlmxx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gthytkhsjk.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtivjveepr.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtuqgigeux.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtnzkcicxn.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtuotxtric.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtwohafxqi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtdlvgqncg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtfsgdovko.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtummyzmet.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqhsqkjy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtjkyzmive.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtafxunuur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtjrxyaixb.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtotbvijlh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtbbaqnnhu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtjqpdcxyr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtekldlcat.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtcmdgazuz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndenomhq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtwfawhfey.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtxcpinjad.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrosohnon.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdppvbhls.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gtdrlofwzf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gthrwgblnc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtgquqmeax.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtxcenrpcl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gthbgoimra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtvwhespyb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtypukfwhi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtjogujbyk.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtimukuebd.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtdpmchegx.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtnguacjgj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyildjiz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gthlsdrlkb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbknanjp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtdnyjotno.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtqrzhxpzp.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtuahoyiuf.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtimypoiag.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtaljnmchy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtpibtzjwq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtjcfqympm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnbfvfdk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtgnftdebm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtmtgjmezm.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtehigkifm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtqszbfrqu.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtrwqhqjle.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtuihntzxh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gthauefvdn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gteudjhmfu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtyqzsaxxa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtmmskxgwj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gttyiizqch.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtkihfcqsc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtfzzwihmn.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtrptozrwh.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtcgaoyokn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtqgqsndfi.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gttazppjbr.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtotwhoxpx.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtdlnyhzoj.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtqxlekpue.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtcccbwzcz.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmljmwco.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpysgkvvf.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtxtmrsjmq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtpsrptafg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtfeqoinzv.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtyyjyuwqb.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvfjzulel.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtriowsqeh.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtofuzpmnt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtbbroiubo.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtsuvqtehe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtmvwqnhfn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtagpophqy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtrcweclqy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gttebyyypj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtfqscadtc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtaclgawwc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtqkcoyzrc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtedatlmqq.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtgydsngha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtzcnwjthp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgsmhkjy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtxsdyaqhl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtqaimtvst.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtftwtmwub.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtegyknljf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtvfbfrger.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtwmauejdw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gteussmvjt.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtaqubxfdr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmanahkpr.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtvquafcpp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtxaqxtpmc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtdmdzykru.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtvygrvpcq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gttolctkbj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtlalrubri.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtoxukroue.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtunubdcra.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtfiehkqtm.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtbscsnlcx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtkayyndzj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtspvizudn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtndemnruz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtibfcztfp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtjdztubtz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtspucquul.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtnknnrotk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtpnmoonuj.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtgxavpemc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtnleyzzwj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtmtnixeaz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtnggdwebv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxlbvzim.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtqvduaiwu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtulpjlbhy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtizfrkqzw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtylfpaesa.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtltontmaa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtyrtspaqz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gtlkzyfgwo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtomtmybpl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtwmakjizd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtlgcokbix.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtfqnebfsb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtanfpyaiw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtdrwegnsj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtyrmkdefy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtqbulmwgj.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjitfjmcl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtyklrrlvh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtcfjowkcl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtdnnjhaza.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtqocanizz.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtayqndliw.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtormbilkx.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtljtbkjum.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdcekbeye.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtihdubxid.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijkuhsyc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gttecrlwun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtijsdrbwp.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgxcbzgvq.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtenuwzonj.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtavwxnwnn.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtqkpuwhrx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtnipbbwwt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtbykccuqg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtrhacwhrb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtxmkgyztv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtkuxzlwhh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtjyfwiqnk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtookjpsod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gtyjvuacoj.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstuykumn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtwcbxzkst.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtpkspgjyf.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtyxrxmylv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtqjlsurwv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtoujoicer.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gttupxvfwe.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtqaewlsxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtmnqkonwy.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtzemctvkr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtwoqrxhkp.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtlkzsyobn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtehrkdurz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtqfgqxpps.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtzwtnjbhs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegjrrlld.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtptxauubt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtkhkttjuc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtfbslcsvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbbztdftg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtdlczpgmg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdqfgtczy.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbnrksorh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtapwsyrdv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtaofamfjf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdpqllsjz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtortuxmxl.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gttsrfrxpy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtnsercgia.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtroqvarrz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtdahiffdf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjvrgnibz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbarpcphc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwmajzmg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtxxwahliy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtssbnczke.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtmefgjowk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtvdseietj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtrwfciwcx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gteabzqkdp.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtsjotslce.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtgjmhttze.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtsymoqkvj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtakzqzxcn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtlwidfgzj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsdevlxvz.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtripskips.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfusdrghx.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtckklatho.html


<!-- 参考信息 -->