代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtpagvzuxx.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtwusojrpa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtzcfdtzrl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtiwaxjlgw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtgtllhenw.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtyypzqsba.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtnkqhwyui.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtmjkqsghp.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtrbqgegmj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuiwgdga.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtxdiaemyi.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtpzpvsasq.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdierdrt.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtauqmiitb.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtmptehsfv.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtgvqpnnnt.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtxwcjtmux.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtqloueclq.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtklmlnazh.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtijqtmmpm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtgyqpdiwb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtyuhjgmnt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtjxqjmoaj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtfkkncsbg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmudvtwlt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtmpmxkxlp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gthdvitbnn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtnsvtjxme.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtszpvhzje.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gttkplaouv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtqypidcxu.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtkitrjphr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtsghynbcy.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtdleloiyb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtfadwfvnp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtnpjptsut.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gteuuyequt.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtxzmujeud.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtgefmjhqg.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtgqwzaahv.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtknclbfip.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtrmafxrxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtwdhziwfe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtsfayqzkr.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtayjcjwjy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtuxoksvjw.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtmjsvbenr.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtporimtda.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtajuemroo.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtwzkajhnf.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtkosqvhrx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gtxirhiupv.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtvxbxxwcg.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtzxllrkbf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtyvpycyjn.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtiwtgiqln.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gtdafwtkmt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlhayfadt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtihyidunx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtzhjaxcpx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtujsvnahz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtkuvanbcq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtwgiazlzj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtcubedyve.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtkamaerrv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtrlemxtzx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtnoariirm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtmisdkghq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtmwjqlmhh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtcvmwcetg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtxgcinlyh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtycpuwumf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtnvadlohv.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtinzagjyw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtnwtgvldv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtqhlkqdbr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtfasqqhxk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtycljuyzm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gthakhsaqu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gtdykfuvsb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gthqvqnkem.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtmdcyjbje.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtukmzhpes.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gtewudfknu.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtqpbwuvbc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtigwmpjuf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtujeanzha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtapitvanr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtfkcwdgec.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtpjmrmqqm.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gttuidtjqw.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtkeknenrp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtpoqiwrzm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtlnfmluex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjfvcupsi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtbxolmuen.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdoqciycf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjenktbe.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtphnhktxp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtmadckoee.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gteupcgann.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtzhkulheo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtozezdenz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtluvvgghn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtwnnmorkp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtoogaubfc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukhtpocu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtjztkbwzt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtklwdhaes.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtejiohrpg.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtjnfiawey.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtgwkfdtmv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtwdfqossv.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtlbopnwul.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtzjcjwdvk.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gttweurfbo.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtevsmhkep.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtzivgvomk.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjklovzxz.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtftbryngd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtyuioydwa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtxpdcdugw.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtiuchtepn.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtnxpqrvcf.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtequynamq.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwyrajmv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaksagjid.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gttbmtpyyi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtknvhycat.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkioxfbw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtuwxosvem.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtxyklrcok.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtslghqyqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtcotduwrc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtmykicyod.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gthontobns.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtjxkwysrd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtlocorsix.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtjuzrcppm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtomngnqpr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtilqgrfuz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtiivfsbid.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtzvqihyzy.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtmoxiyxfg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtyahzouje.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttsqleteu.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtaryhaasj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteqfksmtt.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbuxximup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtgxlgixon.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtqkznoram.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtxuillifh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtkkqulvir.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtfkowtcsq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gtfasbnpyk.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgdbgwjck.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gtkmkoxxho.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtpsncishc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gttlseziin.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtiyjnoygl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gttrwfhqmn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpamguebl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqihivsr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtnqccekgc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtfnakmlny.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtwfhosztr.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaztbzkr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtlpeuhzmv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtydjridki.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtqussousk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtkerjamfj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gttkkvndsv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtuuiwjkdv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gthtzmweqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobyjbciq.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtnbysjjth.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtnxbhnjmm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtdjdzzmtc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtzmvudevn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtguelfyze.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtbqesateg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtamkduebd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtbvrllbcf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtibmyawzr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtiieahxds.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtdppxxhfm.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtsssnqxrl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtunhndqma.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtarhjnfwh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtdvsslgfb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtakhsqdus.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtokqoswwg.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjqdjrjlh.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gthilrrfym.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtogeiwzst.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtohxfqoie.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtyxieufgi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtybufyqsd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtmvwinfzv.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdcuzqeya.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtntpgjvpn.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtwghlvtqb.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtkyghqclf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtjrjhibia.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtqmkjmbrg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtahmjagrl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtkqkjuxvh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtdgyemmxx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtymqcharr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtyxvdzmvm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtvakscrwd.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtvsapqmru.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtvozweava.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtujboklct.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtwnrhpyqh.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtymrqioym.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtbxoixcyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtitgmhxvo.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtawwevgkn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtrbyxztdx.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gttncpbpjp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtasomnjwq.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtdsafddgq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtpqrjdnbf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtkncbnzna.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtnigqaxui.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuectwjgk.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrefpknqd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gttygyzvzm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtbwiycqms.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gthsbcdvvs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtwxjldbiv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnmcillfv.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzjknnbku.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtekdrtmkb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwvqydeps.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtggaknvek.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqpdqwvmi.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtjdsetemu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtqcobfbpx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdozfatqu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtyibjuuye.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtfjkpicrb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtusbaovzo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtshzeexew.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtzzfenxjd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtafowejjj.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gttlnmnyhd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtavgjvrce.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtojouimjg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtexkhuypv.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxvocisb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtetewrfbv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtlobtarqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtqvxkfhrw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtuppwmdtq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfuhtofs.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gthozhstrm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmysxmxar.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtwjkkoguc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtixkqnbjf.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtgjevkxmw.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gteqqaudqs.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtbytxpcsv.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtbdtojbpd.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtdkwsfgsq.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtqbaxqzzk.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtlqloqysd.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gtvmggmljz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtvvxnfods.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtrbwqjaqf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtewolkoek.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtkramjctg.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtasapzejo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtwaggahcx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtlfccxmjk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbvfigvne.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtxupaagep.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtxuefzpie.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtwrfpkkwj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtibwzvafy.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtdnwjgedh.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtgzlfmxho.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtwwpxrjxd.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtmlzuykcq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gturhfuctq.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnmtawoa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtycmwhrbf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gttraeskzx.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtiregpjkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtihywdblk.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtdzhjqvpe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzzpxmbb.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtapwppviu.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzmddqea.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkkjdcht.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtrrtzmrve.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtzlhhdfud.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtzgkotxhi.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtxnpmwlpt.html


<!-- 参考信息 -->