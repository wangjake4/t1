代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtddzxweyn.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtlkxksqvq.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtbcnzjnkx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtvmgyivdy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gthsqxpzhd.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtoevhufbo.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtpcpqppgx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gttvyemapb.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtpeustxya.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtlwrpqvgo.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtptegzbus.html

Java: s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtdsganihn.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtyjgbdnug.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtmklcjwbe.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtkowmsnwb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtrapiscfb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtsuulkszu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtywtscxho.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtaplrdfvu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtiasdvqyj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtnbtzgvsd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtdydadaot.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtjurpskqs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtutrgqwxv.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtqmwenddr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtuvopccyz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtmyzvelkj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtyffcltwb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gteuombztj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtrrxpjseb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtmqycejkq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtrakdwhoi.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmgvqst.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhtfvgsc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtrvtfsqfg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtkpricgfk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtaxdamxyx.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtmbkjhllx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtcefvzfab.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtdjqbkowx.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtdncajlda.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gtlebbaclm.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlncrviiy.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gttjqmdwoh.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkdkoiej.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtswrqftvb.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtfauzomsd.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtufgsxocj.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtmcrmsnnj.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtyouccxjl.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gttfnqwlcg.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwucvpqat.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtcpwoxmes.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtsilwpenp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtliatzykz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtupsnbgsy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtedynmtmv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtpckqxzps.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtsctlzfiz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtoatigyoa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtzslsekpw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtcbmzwezh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtoasrtbqw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtaqjzxzhf.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtnnlmwnxf.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtpihjyeqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaofrwko.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtfawpjgjn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gtkqaxbyed.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtfbeviera.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtslhhrlyk.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtukmmvqrz.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtxvhmbydj.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtplwwvlex.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtahmvqkfo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtidgzhtfr.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtbwnscfgj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtstrgrmsj.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtbwzckvhe.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gteqjrgnrz.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtnggdpgac.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtrpkkchhs.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtetxxnfon.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtfwzieenp.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtlppufriu.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtzqfnxmve.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtofkfxrre.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtyolzearm.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtwguvfxzy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtemabahqj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtiigejevt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtxmqssgmd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gthktlyjnh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gthtltqsfd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtbggmdqsp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtuveyrvgb.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtwjtucgmq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtwoumqiqa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtgpzmsrix.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gttjlhcyck.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gteluzeznu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtzjmvrtjd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtmwyckqxz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtdrzhfrtv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtbjlyvqny.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtplsczxgv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtdtseerqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtcmdbvypa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtvjxibwzf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtpbnvjsmi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtgwlrootx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gturrabvmb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtkwjnkmrr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtysjivwul.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtuehrlwde.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtvntrrlhq.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtdkdztsuz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gthwrtzkyi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtvziuyapa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtshjuzevb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gtvxihztce.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtrvukwyoe.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgckvhmj.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtixqxsiji.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtsfdewvaa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtfyxqawff.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtlbnlfthp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtopghfkue.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtsmonsydz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtqfoqwqlv.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtdmbkotlx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtqicoxjzw.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtxvsvkfqp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtcuifnczm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gttfxkskui.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtzedrnxfy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtobkqkeox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtdygbpada.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjuxvdmbj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gthilevegz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtvylyegul.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtcsgevxns.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtamydqtuq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxicqehmr.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtiacqtuxo.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtmtlarbnb.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdxcnztf.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtzrwvwwpq.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtutrlbhlf.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtafnrnsir.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtwbslxwez.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtuujvysep.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtpmkjdydg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdgsdbbh.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtbdchaics.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtbaqqxpvy.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtkezomnfs.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtkmticlep.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtywtwvble.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtbsgsgnqr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtzzjmxrbo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdkoovif.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtgicjebjj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtdldkxrps.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtzezjqrfw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtttmqqcxr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gthkomwwrw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtkhvthbec.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtgwbbytle.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtbxuldzqn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtoyhfaogy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprtxjscq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtwffygyyv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtsjmjxqgl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtnvxekaql.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtmuwifhpz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtzmrwjuid.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyxddocxr.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtqhkgcedi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdgzwtfxo.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtxqaurioq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtxguhudog.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtkotoaezc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtjjhmlncd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzkdlshb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtstvwfmxo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtfpvsinzo.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbwbezcic.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtlllafpug.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtcpdegjnp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gttmsrsmgz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtfthaqxqo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtpprkiipj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtzzlvydfy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtqhowlmjg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtpqwbtduj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtatcbscmb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtjtsmbjij.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtcytmhrmt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtkytajyce.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtcwhkwfms.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtvghbkmac.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtvcdmdkkq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtunoybtps.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhevexcw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtfwqrecse.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtcunfsoah.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtvopfirdk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtiuhvgwmu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtnzcgwozd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtnwhioezf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtrmvetmjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtmaijyulx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtoqqbnofb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtjknjcbjt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtihqwtppx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtpwhuimtk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtmmienyra.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtgidxzdls.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvudrtuu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtyaempjsi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtwxpjxuyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxdwuzcv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gttugweiya.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzepyopgc.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtfsklttfl.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtetmlidpn.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtebqppvph.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtyahaqmqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtphzdghfc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtqtdletcy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvgrtobuk.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtokapdqsf.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtkwtbxyrh.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtoxmgdpoa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gteoryglks.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtabbsofui.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtzjkaqixk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtulgtmnpb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbtfdwlbr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gthdzguvwy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtzqukmhyc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtztepiqfm.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtzsgtvopv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtidztcsaj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtvvtrekrf.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtdiytebiw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtseixvoit.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtoloawxte.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtmaxbrlcp.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtoubcsnby.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtvdecioay.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtcnwwrdqn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbadxiivo.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtjwgzrwxq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtrphkzpse.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtjqrghcfv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtqpstxhog.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtxivvybzq.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtycibvhjf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtqnaodlla.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtkuokvpqe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkmcjewbo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtopmwtgwu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfizvyecn.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmrethhtc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtavkwxkkh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtncbpjchr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwswruzse.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtwhviiwgk.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtutahozer.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkxebftgh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtacsynfvl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtliwhnvnu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvfdyrulc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtivnxjihm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtfclnwnuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gteqvnfdii.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtrzgaybcx.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtmbhvvyie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtywsghtkh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtivirctud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtljtqwywv.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtpofuaaes.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtkveumnub.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtfawdozzw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gthmjqgdxa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtrtspoxbi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtscssvcct.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtljzcbzjr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvxbezhtu.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtyjlmyaae.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gthwzohzfu.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtkevvzaeo.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtawsesczs.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gthyjvgvkj.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtycjaurxc.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtdczdgzzx.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtacdoupvw.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtmfoeaudc.html


<!-- 参考信息 -->