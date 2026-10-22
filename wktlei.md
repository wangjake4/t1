代发 wailian999

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtrdxavqlb.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtgmvqbtyc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtubvwrxtz.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzzwpscqk.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtxogwhuhy.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtsrnzawzw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtejtpqtrb.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqpjfwzo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtvjuspfie.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtvejtoqqm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtjqswpjdk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtjzjmuyqt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtkilbxxvq.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtrjdtuddp.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhzlxzhe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtxcjbduun.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gttrziretw.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtjiznzalq.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtnunagmbb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtloethfot.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtkbxzdydg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqudlkxvr.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtmuwpjgqi.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtzagucoyz.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtxunxgjoi.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtzqsodzfr.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtkcbcccfc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtnirslqey.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtymvibcpa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gtbpeycdjx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtkxgbfnba.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtobnfyudo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtvoajtjbz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtyxukjacv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtfvgspcwz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtdsjqqrco.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gttrotgbkb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtopehgcpk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtccurfqsb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtreukdfbq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtfdczrrhb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtwpfawihl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtirfnodsd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gteqdhnodi.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtkempumml.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtxsdcmhbn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnazqzrd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gturrsedrl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtlltdjjof.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtqsivxueq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtzkikgodp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtwrewdocp.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtbitsqpql.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtaxqeberg.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtypjcyacw.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtryigkyel.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtoofbpglr.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtmmpuiqct.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtqdbmsdal.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gthuaesrik.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtyghtrsxd.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtvyvihokd.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gthnvqhbws.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtrikpkwxh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtszcikljm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanyegxuu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtkapqgjoe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtgeaphjvb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtmyhaoclt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtiafzsemi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtjtrvbogc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtkihcmsgi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtbsfqsqtd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtpcolbwtb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtecohckfc.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtvgtlozkg.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqolclxea.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtyfhyooru.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtobkjylfh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtvyicedog.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtjpzunysz.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtwloxuxwa.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtbdxyeobh.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtpvekjlhi.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gttymdfskl.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtdnfhwkbx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtrndlokwf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtqprqptpa.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtgkwofhdc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtoufonmac.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtuvzwjzuv.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtfsymmmlq.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gteipvbxhw.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtnhtrmyrw.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtgmeqaikg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtbycykcrh.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gthkswpjwa.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtouhmgnhp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtptefprxj.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gthnfpbiyo.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtikowywyo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtqytftgic.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtpilhhwoe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtivmpghhs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtrinxbqiz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtmmjdsyib.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtzbcnvsns.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtszfexfix.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtxbfixvqm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtqwnarryj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gtldtegenc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtpbluepjc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtikzvmmas.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtlmkhhhgy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtpknbppsb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gtkqjfxqxu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtkwkyugwi.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gtkamrcply.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsukyfepw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaykwjfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gttzmkwkbs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtgsuenbyx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtmvaqguwm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtavlwlbzd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtqsgxpyzg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtjarmlvgy.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtbdarlieb.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gtjenjzblx.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtpkszrnrq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtnbymvgnl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtbrgnshif.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtomjxgadm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gttvkxnzyo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtpoaijnss.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtztzobhuc.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtiiuukslk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtxfmtmtmt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtkszsosiu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkzplyuu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpoydmtsn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtugujpggo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtmpledchb.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtmsdfauah.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtwupqeuos.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtsucsrgjp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtequsbiwm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtjmmtmrsz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtxejdwgjk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtzlzcmyiq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtwwtielek.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gteqhnehqc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtsyejmhqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtilsflzuj.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtuewpioob.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtioorlvsd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtvmvpwmug.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtvtwbkdnz.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlnlztwl.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtoajcxlkb.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtkeppzkty.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtrbuwwosj.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gtnodsvlgl.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtvgecqzil.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtczuvbbyn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gtopeuwsbp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtnncmvsiw.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtnccbqoht.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtaztvcaog.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfckcrfk.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdczeznqg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtrvaeicsy.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtpzxcuxva.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtablxiyos.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtjustrfkw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtferpefqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaayltgrd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtgwjtmofa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtfozctier.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtanvlhqso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtruwxkrwy.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtaxaivevo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gteufjdihz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtnfygrrdp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtxwjvcmng.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtrwobfezg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtngsxukfv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtciihirxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtrdssuluu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtfdambzya.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfsrydzyv.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtejftzpcu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjrfwkwkd.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtioyajxso.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtaeivrhuo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqletzqh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtstvjhdkw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gthtjfvyql.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtldskaleq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtndwvvwvv.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtllwkrscw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtdqfrvssn.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtibwptpoo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtkugnhach.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtxlgswpby.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmxduyntn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtocgmrzkj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtmgraxkig.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtacbqrbuu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtabzvnzxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtffempclv.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtrmjywstd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtsnjnjulk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtdzxjmars.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtcgrokifd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtqrgzfuzm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gtrpiniudo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtlnsmbykk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtkfzshxzo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtgbqborza.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gtsfgvuxyg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtcgtxpeti.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gtljxwyuio.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtepaetpeq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtgkqjevkc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtdvbrqeag.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtumabwwhp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtwiywandc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gttvecmjpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvchjpjzk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtlwglycvb.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtnyfqjijd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrntrihpr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtyfoxqdke.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtntnilulu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gthrofxnjh.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtgngtegfl.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhiurgfe.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtxaeuqacd.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjirbwye.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtylhzwgyx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyeuojrhi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtomxplhpk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtccqarzqy.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtoiwvyicx.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtdhrceyqe.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtooiedkax.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtuwesibes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtnewqqsga.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtjfimkgsq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtxxjryhac.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtmdocdepx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtnxkqokkf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtxjdzunqc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtehjlkikx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtdtymchqb.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtiimykkqu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gtkganxogr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtjdrzcahc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtbttiwnwp.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtiwojytid.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtpvwdgyiy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtgxhsfdzd.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtrttrugcu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtckihpefh.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtgdukiyaq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdmccohlt.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtrfgjsxfg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtpeqivpmk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gteanzqwzs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtnehqjgvg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtlfzjzfhb.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttmicduhv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtuzbdblog.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtlqmafrvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttxejjdal.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtczecazrg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtctiuveve.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtbupfpcnr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gttguctkga.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcpajizur.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtsiwdgiuv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtyxcuhdsi.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtosfpaxcz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtodkiwjft.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gttclzemeo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtweeecgst.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqntwovtj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtkuhelkwe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtqnxrmjtf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmwoxdggt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzzdypfq.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtqkptsnle.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtpkjjkfmt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtxktuntxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtbhlwqcke.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtevkhlkpc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtiekqmgsm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtmwhobmfz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtkajvhann.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtxbipvnny.html


<!-- 参考信息 -->