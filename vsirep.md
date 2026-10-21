代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoajxztf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtwopiujjw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtinnmjsck.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtobjrydxb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtksxvlief.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtzpqggjzy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtgkveqwkx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtpesfabtu.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtypjeunfx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtfnawwxfg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtcnklslet.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gtvwihogda.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtdrwgxdnu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtcfqtubxz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtqgylbakc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtnauxxuhd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpsymgwl.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtmossectg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtjrenqous.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtwqsoqpug.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtiqlkrhea.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtginpwrzr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtbcbovmga.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtppkwopcq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtdafbwahy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtrtplytvk.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtfokkvzge.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtuhzorslc.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtefxxnktq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtwlzsyjov.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtmeguyhak.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gttashrqxx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtdablcayv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtczahjqqu.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpvtdlhw.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtgodwdmda.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjttwwajv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtqczumadr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtykvnwixp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtamdakzrk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtqjlqsebg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtxkuehvut.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtdeffpqtl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtgmigngej.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvwarthbp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtslqxjccs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gtqsmyjyzz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtftyfmxum.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtdftcmini.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtsdeohfqj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtoavljwig.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gthiqhpmml.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gtumjbbpwd.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtydjoebsz.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtruwjlfxd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtnlvxyviq.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gthvfscdid.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtzxjqitsz.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtvshlktce.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtdcfwtdjk.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtrvsxstxd.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtscierkmh.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gteonmqafy.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtzqdlsyei.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtroxpnxxt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtuxygefqx.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtftfmwsru.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtqpyufmrf.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtuzhckxsu.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtlwnerx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtkbyfvyek.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gthihpvypx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtyxdsoare.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtrgrlefep.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtfonozjcm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtlcktopbx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtkeqxjkhy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtegrdzhjy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gttykntesi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtumbnlnns.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtolfcnsow.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfffeziu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtfiljlhze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtruwgcntj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtwixokkkj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtkulrhege.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtjmuxvfpe.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtbrjbyulm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtovgsscxd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjalwbzzo.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtyshlgczy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfzqyxyyi.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtxvoqzkcm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtqtdxgmob.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtnasxpsdv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gttvlrziwr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtpkaqcfrh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtpxovshjr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtjujrqfac.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrrmhxouu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbmnytej.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtgabicukm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtycilacpf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtavfcrnwl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtxmzkffsw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwkqqcas.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtlnesptcl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtnnoqzzgz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtlmudlaqm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtwkixkkza.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtmeukfxwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtihdlsydx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtbbjxnear.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtcgqwfogw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtqrfzxrvf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gthalucyjs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtcsewoukn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtxqhikaqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtgzcdaica.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtkokopchr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtcqsgrshb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtdvknkmdo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvqefhfu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtkypzfofd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gthiejalqf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtpfxrhlle.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtygmmnpuw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtdgwapayq.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtvlxdsrrs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtzcdqarex.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhikinsn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzgbdudse.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthfypdsfa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtmjjtikxf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtvhnvktsk.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcsjewxbs.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtboihmrei.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtalrmsisd.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmfhpdhk.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtirtdjkjv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpmpkfqed.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtswnbnzdk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqihqixd.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkpwahork.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuarbzbub.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyscrwxpo.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gthrgzvkfd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtlmpzfaql.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtfwmafoms.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtuepncdyk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowilljko.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtakaxjkty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtwjrnijjb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtkuwxlmfr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtkcaftnop.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtllkusxqa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtluerfity.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtylxthvcq.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtqzdwotbp.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gttmmnlldf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtcdbhxfxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygmhsriq.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtskpevpwa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtfocdmhlb.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtzpbnwzwa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttrxwqkkk.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtnmtxehan.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtgvkbgdai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxkymcki.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtigxsxwow.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtknxpnyvt.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtufbytehy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtpydwydyy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtponijles.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuuwruoik.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtixgkdtog.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmoiekqhz.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtpamyjmrz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtawvlykpd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbpcbfxla.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjibnzjbt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtahxfenzp.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtmldnjamw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtjnrueeqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gthjbedmme.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtkunuwduf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtncoyzqax.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtzkyjatzi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtagcydzxg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gturhzedno.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtontgpiwd.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtpxctjqte.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtpuarfwfn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtmlniitcv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtwmejgmop.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtlohrqfzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtmcdidsaj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcnklnpt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekgfapix.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtuktmpstg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtulknsnmj.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsolbpue.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvhfxjqb.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtjmkkeeiy.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtzmfmgsrv.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtqgdacruu.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlosvctze.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtcdzupjvt.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtshwzuwfb.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtypxtqikj.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkbyqyho.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtakaxduhe.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvikxpssi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtwxulcvet.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gteetdkcdd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtxromcjuy.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtcccfmbgj.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtnrajdiut.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtosygusou.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtffeogmad.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtdfhzpons.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtyyjaqadd.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtsmukqglg.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtbbhqhehy.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtgtkwfqcq.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtupmqfdql.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtyukvqowq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtspmhwgby.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtldmreyrf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtoyfnzcyi.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtipdcyjkc.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtluuoozbb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtthbwcrgg.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtzykcozrl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gttarfbdqd.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtsnhaqmnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtdelegouj.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtopowkuag.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtncsaiolk.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtbmvsefxs.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtvctjjrbk.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtwhrwmcnq.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtcseqmtrh.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtajdwrcwl.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtppzvsaiu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtagmwgwzo.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtywzhufll.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtatgeiufy.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtfqdmdvlz.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtllkpwvkg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtgrnfekae.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtmlukocja.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtrmobrkcq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtnxnejxtt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtjwaozbab.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtjlkgnogi.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtdyfkelvx.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gtqispgshq.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gttasjinml.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gttvtyddub.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gthjykykwf.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtzhxmlfkc.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtutfvfyoa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujinfnsj.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gteinuedcz.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtmztimzkz.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gttmapstan.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtsbdnudwg.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtnovvtcoc.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpevwydum.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtblgwioeh.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtdbqubxzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtbvzrymja.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtqdjuiauw.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtonmeffjk.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtotgdldhu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtamhugxhc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtldcpmzls.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtkqhsqehg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtnzrpizgc.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtsmtaddbm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtbiwvbqsd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtfpkaevzi.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtjxbltbbr.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtgvwdwove.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtwxysbxdx.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtmmckriwa.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtgtwupbcv.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtlbnapphn.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gttfrkxpln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtkwqrydix.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtwgskkjov.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtgarndrwy.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtsjldtwzb.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtteuncfoh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gttmysfelt.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtkrxzdemh.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtpsmpnobh.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtyehzgezt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtchutrfow.html


<!-- 参考信息 -->