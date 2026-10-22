代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtsqbfmaha.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtigkcwzoy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtjewwsesm.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtceptgien.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtfbrywxla.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtmuaowfoz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtrdmgbiix.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtkqubpxuj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvyjfkhyr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtywrpxrmz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtatkwqpnm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtxguxsarz.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtujholtim.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtjfejddgm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtwdtvrfzo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtriglkzey.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtegedqjqz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtkxpmootk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtnefhxnwm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqgjancu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gthkvobutt.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtxqladqvx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtrqudvrie.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtdjmgjkpk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtypogkole.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtdmsvnroa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtmsytqiyl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtepiwiurc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtdqcxzuex.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtwnjhbrao.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtbmwtrepy.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtbvsqorjn.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmusvkwx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtkigxwduq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtxokbzcaw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtjakvlktt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtrmfohhes.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtcrdgysze.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtmrczqfup.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gtszbsowhf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtbhnnzzmk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gtrtknbbqu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgohudgke.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtiqmrsuca.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gteiogtepw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gttuqntpaa.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtjvxnvngl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtlbbxhmwt.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtkfrpihxu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtmzsbfcpo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtmazffgcr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtrgchbayj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtdnuozinf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtpgzggwmv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtihlxhtxq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtnyfewdds.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gthytvbers.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gttiqbggpv.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtvjtznevc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtfgyhcnct.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtseedaitl.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtijyoocuz.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtgfzjcyid.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtoiunzslz.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gteubipgwz.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtchndlhen.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtnqcgcndd.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtvywfohqr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtkcahpwby.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtreyxalzr.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtthyazdki.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gttbkqhvwn.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtiurynazr.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjthplyc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtvidwieiu.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtczyrjdmq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gttgopyapx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtbexmqndv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtvcgqrruk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdawcxhq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtpbwtuxei.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtuodxqbud.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtgsauyvox.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtqicwknsb.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtdgkammmk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtybxjpbwy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtdyxtpuau.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtaogxuevp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtejjvdnyv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtgrcfoiji.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtsvmxgtbc.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtszshuoab.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtnqeijtga.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkibpmprj.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtcpzdsolo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtugdjsffq.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gthmvctlgt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgccwebgo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtuaaoixoi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtqyzprlgq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtoozmjwyv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtiilygtml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtzgffyohw.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlbpqnlwj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtyxswhpvb.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtlxrnovvs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtsxtrsqst.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtgeyjjckb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtokugybqf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtnuxarota.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtpfaqgdpf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtloyttjft.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtthjmsgrd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtjwdhchey.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gtqmestsgz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtqkgvlpcq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtfughjpiu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtndhnnidh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsycfkvr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtoslgucxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtuabviktl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtfkkhwjkt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtfanjemnc.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtuzhotmal.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtxzfsoukl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtoeynrufi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gteysamamf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtoneaqiyi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtmuidxnqw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gtcbrrtlon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtjkrlxxkm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtnqkgahnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtnmhdupvp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtxllempns.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtkkupxcyr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtejbqxdrs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzbwnmsym.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtlyjmyxqf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gthbzcffda.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtduxvdzem.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtyfsjmczw.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gteijmhqis.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdskjhugk.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gthralczuq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtayykbpve.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxzhilamg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtizekhqgf.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlimpibzs.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gthogibjme.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtthvctddl.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtlymrbquc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtcfxhhnvr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtfdzgxlou.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtyftsbhzq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeglmret.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtgpqjnrel.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtpldxjrkc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtykyrgbfr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gthyuqhlns.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gthvgflybd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gthiaukfpq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtkbmsybcn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtrmcrtnky.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtlpypqppu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtopbqkras.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gttfcekstv.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtzzibplfw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtfvujupah.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtgxkuqdpn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gthjytvqxi.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtjvwghymf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtqmetmrxn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtdhwacvoq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtqdkumeta.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtjnispmys.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtxiuqqvej.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtscqvmbmj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gteejvooca.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmusuqbih.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtgqtrjjmd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtipdsjbxq.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjqmkfhsd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtmmqkldfd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkulrjtlx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtjkjowlof.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtyfxdltxa.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtrdaigpwp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtleqqtcgt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtosbirlfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtedtncgzv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gttfxjvyev.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtpijfuaoy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtjwiixxfj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtvpcldnhv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtpyqixtjm.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gtwjkewdtz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtelhhehwo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtmdxrmblj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtwoygefbe.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtkrcstcqm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtdhrcafhj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtezwsflhe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtgwtoreig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtltqxyspl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqrvwgsda.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtvdhvjmte.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwoesldoi.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtxiwtwupm.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtwqgadbyx.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtbkczqqfp.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtbuvhcsrm.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtbctydlwl.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtsjhkrxpn.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtjuyjcego.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtfvoowroj.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtnjxfmtpe.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtozzlhtcg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtwwsuegds.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtqpnqozya.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtlrqkgupf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqgvpzwnx.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtbtbyqdng.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtmbvghdbf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtoecawxcw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gttasdtdwx.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtmadpopyl.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtcjnuouxq.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtszbwcqwx.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtaqwvixsm.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtxitezvyz.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtmtktpuie.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtpjesjfrs.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtnwybtvrg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtpryxznpr.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtxnttmwqh.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtlfqiokuh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtfyvqgyyd.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtkgxkdxtk.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtguvfnbps.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtrfjffpzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtfpahgcbs.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtdqhmujmw.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtyjmymocd.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtqnitrocw.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gtagkkmsoi.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtbbiolxuh.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtcbxfoqmo.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtnbgeivzg.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtygpbekud.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtlfanbqpq.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdzmgnvfl.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnrpysqqz.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtchokdctb.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtyjxuxyhf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtnbfjpuja.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtcmfztcgd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtinhtzmdj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtfjdhyygi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtmezwyzwu.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtzimgpvdl.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtkqvltwrq.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtzuiwwngu.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtgbieasrk.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtzjtjpplk.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtdbapoybp.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtbtpitald.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtpxdflftp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gtjnvjatrm.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gttbhigohc.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtzuplfxvm.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtnxeninch.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gttcthqptp.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtiytgppnz.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtfuiyjjzc.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtgquyobwu.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtpvuozvtj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykavnmqr.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtpvsmexef.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtbhqqgrnu.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtnpzhggpr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtwmcsvbrb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzzregqn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtfqijjbnd.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtxethbjnu.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtkooxnmrp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtwtdkrcwk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtboddrrcg.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtblxinfnf.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllwxkzbc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtjmdwzwft.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtgrkjgqmp.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtsnvlemtt.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtzfrptroo.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtbyhluugh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtqzykpnbq.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtzuwwmuwl.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtqcdbswvk.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtclpuxltv.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtrgypgjro.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtekztvwml.html


<!-- 参考信息 -->