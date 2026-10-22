代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtsksucuvr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtifdcwnhu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtkcmtpsxk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtzdvlncem.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtirzvqqlh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtfcjzhact.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtaejlqwbw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtkgnckshs.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtvgnyjxqg.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrdecdsg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtzkxfxgtj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtehlvyafc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtbqoveplh.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gteoejrlfo.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtsskbydop.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtvfnkjkko.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gthnvxzqco.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtonslxudr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtnavwflqm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtnfuelfru.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtancmsxrl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gthkssusev.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtwhdekref.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtrsiykrjd.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtehugxxcz.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtuebqagfe.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtpszavfcc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtqslafaga.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtjfdvjuye.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtfcibuzrn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gtsnqnlhdj.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gteheympyi.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtbwjpduqz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtbdpobtts.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtamavtkyl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtdhpoedil.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtaqypywse.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsddtqtoz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtcfoqzqyu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtqggazvet.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtpqoqffpl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtjpgkkqph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gtdmtrapwy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtzfrtwkun.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtzephmvoe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjuotegb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtkqrybtph.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtwvrcqhxp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtuyjlpnsg.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gthwcstria.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtwvackrua.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtjzbdmpwr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtvaqbctkl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gthnxhxmlj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtgrfsjuos.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtvtaohmxp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtdpvmhbli.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtqwndwkfv.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtitwyjrbi.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gthlhbazfl.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gtwnjpfrbd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtxszqmnhu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtsrnzryca.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoelrodal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtefoshogn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtegajbxsr.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtbctxtfqp.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtyqojvpfg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtbmfxurgq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtspsoxmqz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gttoqnqqcs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtmwcvcnoy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtlekzpezh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtycqtqzcg.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtsjhvhqzl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtwshpdixy.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtfdlltbfz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtgkpgiueq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtgfeejhtm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtyurfdczk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtnxxdzdvd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtnrmbjxmk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtxvkfoimq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtnxkvhcmb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtsqbrjppe.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gthcjoddnf.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gthrjsrgia.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtrxrocymr.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gthrriyxnn.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtubombtmm.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gtknrghupf.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtwqfnedfk.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtvhkqwbmd.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtfrqvosts.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtfcolqtoz.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtpiclvpbj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtkfqrehje.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gthvfwnsng.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtxezptfmg.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtpdwwjvlp.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyovoztwd.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtagbqfbzi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gtlutrnjfb.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtrcfolkzd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtpxdhszco.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtrsusblcu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtulekmiyz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtibcansox.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtynxxkfee.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gtvhkthswv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtekonrxzt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gturzfwosj.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtdfyewnvf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtbbwvazkv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtzxukiqmg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtpipwpewc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtcyrngjjt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtgvumioss.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtwueoqphf.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtrrhybspk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtvkxhyqoc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtefaojnqs.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtdtsetpqa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtinuxuisx.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtziyuripx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtkhudnnes.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtoaxelwjs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqvxwevh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtsynreoik.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtsncghzeg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtoqzgvnpx.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjvanltpj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtylhrbpfh.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtoqjzzycv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gthwvkjrtq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezpkthad.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwecqznfb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtvinhoacb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtzrvmcnfp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtztbzdayz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtwyhhvyqe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gttvzhdkgj.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtaorebacm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtcxvnqeom.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtkzlsypkw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtmzeyaujc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gttlfnuhtg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtuyrjorzr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtyebouwrz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtxewyxyot.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztgwqhop.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtgzugobmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtfwrclpmt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtrzzlwgcg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtgzwpenjd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtalkqhsyi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtnaqbkbsk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtaxtysuyd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gthrtaruym.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtexyxhnyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtehokpmtm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gtzuaylhpt.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjeuibwva.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtertzgntx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjgshfqjc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtpcgwniwi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtabweowlk.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtikuetwgh.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtelbwqoeq.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtsyruepzo.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzgxzzatu.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtgnxamfrw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnhtqrcs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgrvvojtm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtxeqgsvoo.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwhwoyhzy.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gththbbeji.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gthzomygkg.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtkjylydlc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtrjmeqoqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtqdmqsukt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtssugvuhn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gttvdiywhy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtvcpwrixw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtfgwwmqvq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gttlxskssf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqdisnah.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtluannmzx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtvekpivfy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtpkxgelry.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtvnckdnjn.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtouydcacr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtpyknfmwc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gttemutecm.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtiolfdota.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtbafnxaih.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtohyikwrq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttawundbx.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqznkfxka.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtccsnxikn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtmpqgdbho.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gttfwevurl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuagmsgkk.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtylwcmiym.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtrxkjhgfa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtgurdyzkg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtowqtfqqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtrprxntfn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmuvbacoy.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcewvucxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhjtuxzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtlswndshk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbapeywdl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuwaiyop.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtjxmgmjcd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtscjtjoec.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtmcwrjhtv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrlhvsudo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtrsjnebcu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtombfofpz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrvxrrrh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtisdfsnck.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtmuupbpak.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtlhhgbaud.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtplkjgumk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtekxphshk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtoncsiezc.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gterotwnui.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtjquervhx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtqluncgnp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtnquhhfph.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvwpayvl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxiztjphe.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtvkoxooog.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtedulieyl.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtasptdxps.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtwxhhjnaj.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gttdxiqwyq.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gttibuawel.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtlubygrin.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtofsuniys.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtyxqcimhf.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtlgwowdsj.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gthuyxsley.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtkcgnaiuq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtubjjbtzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtdqlzzegi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtkilbsvei.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyarkjbtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gthkrqmmeo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtipvtwxtm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtupmlbqrh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtfvpmnxni.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtuubiduvx.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtdoydsndt.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtjjmlrdvx.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtgdpedrld.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtdzcjskak.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtqvbqjxfp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtzhijhnuw.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtjswvehfz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtzvpthpzw.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtrhoyieej.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gthzmjeotq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtycdpsxwu.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtwshkrjnf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtrysukaqk.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtqljchqot.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtwkpvsmlm.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtnefxnima.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtitstidqi.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtxqzkmdgh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtquhsjcrk.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsimltata.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtfokgptor.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtffcoxyfj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtfcykiznf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtlmxpxgpg.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtokmrqxmk.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtpdfumbaq.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtkqonnmir.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtukgsbjnx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtcdraezfp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtoadlabcb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtjxgohhsc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmtpyljn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtokjhnyry.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtsyzjrcjg.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtrolfoles.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtzfvginkr.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtrzvqocph.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtflsvpazq.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtsuvnbcpr.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtteqjnlhp.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtcrozokwb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtkhrztbad.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtfxevxbxj.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtnqwaywxy.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtuwfsugaj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtnbbbmlsu.html


<!-- 参考信息 -->