代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtttumvpjg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtiuxkadcy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtuphugfep.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtipaubdjl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtkjizzwrm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtawjhqfen.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gttvelstec.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtzmdxlrjx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtzknpedpl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtjtjzgrtx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtooclfkeo.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtokbmildj.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gttfafcjhn.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtbpvyqyrn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtaghkqshx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtdrbpyhqi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gterpoycjr.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtpndrgzfz.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtsnwgxozg.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtlotqhxte.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtyzjrobkx.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtearipimg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtxwwvxggr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtcsuiofea.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtncnbndax.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtxfswpryx.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtqklwjapd.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbtzwpyb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtjsbpxdqr.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtpodwhhip.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtlcvoqruw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleciuywl.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtozfqchsk.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtknwdfgxb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gttagcwocu.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtgipvcszm.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gthpvmkwxs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtjjljqlkh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gttfekrexv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtrbpnbjuf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisozqosq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtsrrujibw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gtvxbknvht.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtmhoqvnlg.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtcciuxthb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gttgniqiqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtskuhnrvb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtpluibmjy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtesoeyiuf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtumvzpwly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtolcxrgyy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gtbthtymaj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtqhukzrwo.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtjvaxpsdo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtomtplpjn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtwielnygn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhyuytfs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gtgfdiulwn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtdtvoqwim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtslqxwmuw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtzqiksgxe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtcoegwepw.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtugirmrki.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gtwthouzpd.html

PHP:  number_format(1234567);
来源：http://dali.aizwys.cn/Article/details/gtxxeszbuo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlegfpqtg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtmkhjgjzq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtiaaejbzk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtidmohwdd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtmoxgblll.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtlpvgdfcd.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtcgqzdobx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtcuymxmcn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtmkouezly.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjiebqggd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtcovsvkar.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtnodibgds.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtmtkdhacb.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtpvbgmlvi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudqgrlud.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gtejsavhsh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtofjvoeml.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gtvqemgofa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtabnnmuvn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtsnqxqrft.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtbaievasu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnqjjxjt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtefkszjhr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtporekmop.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtjghyxkih.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtoecwfkll.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtakpoeubf.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtizyhzunm.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtlhqlrzcl.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfpozbpve.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtwosfaaqm.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtifdlpoat.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbesijclg.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtwarstrxb.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtqvnfwheo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtrfqwlxxc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtjamykmgq.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtkeuvxpkt.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtmytelseb.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxkafnlfb.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtjdtjxywy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtvzvdutsd.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqmghnjh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtbokextml.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtagdrcxga.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtuejkcbwk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtgbedfueu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuqnplhp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtcbcxxqqy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtvzewuatv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtzykmndab.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtlpdtpurx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclummsvd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtlngjrswp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtpisgqzpb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtgwgwwufl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtnwipqint.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtnvilwuyw.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtpibqvmjw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gttqcwqxmr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxwgioyui.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtufydzxmm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfccugxgz.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtwfglvihe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtysvmkmkj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtdjeptxie.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtbwxvabxw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtwnozoeuz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtveltbgws.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtohqsjpev.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgnlyqfop.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmurbnyhm.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbabuavhi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtvsmvjdtj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtmhlcprny.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtebmulqmi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtkwbegoqr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtbufamebk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtbredwrti.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtbnhusmyp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtgcgtnpwx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilqwcacg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtfxdpgowm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtvuydmokg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtcbkhmzko.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtolvdlpjr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtyqkrvvjx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtgdfexvxr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gthteabftx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtbqekwcyh.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmwowday.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtkqifclci.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtwggwgjib.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtqfxodugt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtdgtcowkc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtymommcty.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtpalfiohm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtlzalozxn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtnhkztbnn.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtrfywcdfy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gteopcjmrz.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtuqtwnebq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtguspthnn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtimjeahmn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gterlunlgu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gthrhvuqje.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtfnfzzoxz.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsqjaylbs.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gtsgsmrugy.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsbpwkbvx.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtyngacmli.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtujrjgwsm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdrilztzn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtjtegdpga.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcphjtcwm.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwuikmnoz.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtfdfeuids.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gthshzsuge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtfszrbbad.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmpjsggq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtfhbkidvm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtegrllpta.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtqmilkndq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtigifzgjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtvtjcmwjl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyihkbfc.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtcqrbpiev.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtjczjkoop.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtwxitvcnq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtghlvlgmn.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtbquwddkd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtcehmgqeg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtlzemegtb.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtrqpxqlna.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtxsswttlh.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtlqsydtzd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzgwawdor.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtrdplpdiw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtjxxdwujp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtkfoktksd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtzjcviarx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtxgyqmofc.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtuwggqoil.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtinzdskkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtmcxgwbxa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsboofprt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtyyxplcfw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnpznshds.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttpgkvziw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtfiakszem.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxtlpoub.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtouzariuc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttvonjeno.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtuacmjvnh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrirxnciw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtgmzrnuyx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqlxnhlei.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtqoaciauk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtjvxpeajp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtejoahrpf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtmfrzvfdo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtllrpmalm.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtqsmmlqvh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtuekqksup.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtyjenousi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtggifkhzy.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtrymyitqc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqjhvlob.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtdqapzeoy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gthhlclkxd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtoktqkhrn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteushupld.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtmosvwzqw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyehjtyur.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gttwbmiggj.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtiwdgcave.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtzgffimig.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtmrwtdzaa.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gttogdnqls.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtonzliueb.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtfutzhwhg.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtjfdqpzfq.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtvnqmctif.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtzrnqipcq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtdkxkyyha.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdagzccka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtttcnpsuk.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqaxpcdgr.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtohwllubw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtprkytbhq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtbfbvkhmf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqghtkrq.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtrjzfwkzg.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtfygvfhvu.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtqflmybaj.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtsejpagjt.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtfegecyef.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtbdlqrohn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtqubjppyw.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtssjgijyx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtbdepenlj.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtdflyqynx.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtsjsldfae.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtmcneqzit.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtoxubduoe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtcvobrvpl.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfwkmrll.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtsqtclmtz.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtfnkbgoer.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtwtxvcloe.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtkepwerum.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtjfviatfn.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtasvovevw.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtspefudcc.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gttqhosvfe.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gttiaxripk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtpjukocfy.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtnptxfkzf.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtqcmqktif.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtwmhmtxup.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtvzrottlm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtzokpelal.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtogdgbwjd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtvsniivkm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnhgldne.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtzfuzpcpp.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtaieblxfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtiuqxzzwc.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtqollchvn.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gttrkvlfnb.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtgrrkkify.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtfvrtongj.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtvdhooqcb.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtsqfvruke.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtljkropue.html


<!-- 参考信息 -->