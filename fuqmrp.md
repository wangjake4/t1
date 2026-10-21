代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjzgimdb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtscrjmsgo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gthhlpysqx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtcngcvapf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtnntrdbxl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtlruxphhu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtgfwjdfxn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gttxxmlwis.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gttxyxttxv.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtmxgeehzc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtopbobcub.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gthzxxkwjc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtzfynsrmr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtblmeqsmd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtihnkmuvq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gtroptxdnb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gttezobixn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtpxhsdnag.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gtdsmmwwvm.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtypeapzyq.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtpnnklqnh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtfwkxttgy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtmxhsdyyl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtoqmsgzzh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtahevwbvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtnqqejvwf.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtomapnazo.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtdsdzllxy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gteczegtjw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtlohhxyrp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwzbuink.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmxyhohn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtsdcfsvfn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtrvhurbjn.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtomwuqbtn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtittvdyzw.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gtogymsizo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuuscxdy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtvtttryrx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtxtjlffxn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtooeowqax.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtrsualdev.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gttprwehke.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gtrtmbkqyc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtqoojokfn.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtjfgsbxlj.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtzjikodas.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtlrbfzqtx.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtfjlxxnia.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtwbykyyan.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtoiheunim.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtdeftsspw.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtrwergwpy.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtfrolkjdp.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtlxxwaszc.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtyqjwfzps.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtynransxa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmdzcxam.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtcjyaquhc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtafhzjqly.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtsbbpcxxe.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtelnfrriq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtqnmpkndf.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtljzumfwd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtgyumnrze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtelfzbeiw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtvmyudrdt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtipogcjms.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtbgbbauxw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtqgnohrtl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtpjkrkfgi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtsmkgkjka.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtxxvzvqsy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtwtzuxwdy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtnvafoipt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtzrmtgjoh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtmebxlgyd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtqeytdfvq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtlylixkmm.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtsutrmnkt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtfnuipujw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtelvtsgqe.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtysbienvn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmuijfioh.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtpjsovlvy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gthzlxjeya.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtnzlxyqnk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtbnekioss.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gthvfbiiok.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtozrvalcg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gtgvrnoeoy.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtochlirqj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gtuknjxher.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtdcwprfaw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtvyjgqsnh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtzgrlveqo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtzxjptczf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtbyfpkhib.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtvuokfwhi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtvubznfrm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtnqqkqaik.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsmoljgd.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtebjsogaq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtjbpdlllg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtmoxoksvf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gteqjgxqro.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtfgoymvaq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtitvnbddz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtmjmztckj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtbcegpdvg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtskkhtntq.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtvcrdzwui.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtqddfxwwd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtlgmytqtp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtxiftsfyw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtzzhdygml.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtnmubxqbx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtgvcuefiv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtqjrvhpou.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtrgwlgxow.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtwblxrzll.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtbzrfrryc.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtubagklwn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloyqdaif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtoxksieci.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtubaoxcqg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtllcpbauf.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtatlhzqez.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtohnvbiay.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtlmtiovpu.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpfmycll.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtlhjjkoox.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtsurwqxfh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtidlwaugp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtrgemovno.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjemlczd.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxhhpdees.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtgxdzvofm.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtekhvkrer.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtocdlzkel.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaskckbb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiilrmiba.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsbmhjho.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtuexcyzwg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtkxubtnoh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtussbezxn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtgpavtpke.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gttzdkffjz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtzwhjuvep.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtpwiohjmi.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtztexbbcf.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtudetnwuj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtqidkexnh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtxdviidgj.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtmagyfyjt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtqqirrrce.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtjtidnvnz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtezgmkxhh.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtsmxyzxqi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtxejsnenc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxqqqgrh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtnpmnvygg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtqpsdlyln.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtnhencvxi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtbzjbujvr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtjzdcwvxt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtgmcacorx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpygocosf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqybxxyxi.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtvmwnqvky.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtngnicztl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdtikqpok.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgmtfcikk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvwwougqr.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtyyrxvnsz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtuvmybnxf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnauyumbc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfhmnxdf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmogyolht.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtrctvhqwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtlszipylr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gttqqddyvz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtggzgmguk.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtphrqvlbv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtupisreve.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtgohtxidf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtahjkhvpo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtwaiatkmm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtpmnzkafe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtsrcigiiq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtimtijfsu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtcppqfmet.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoyguqiya.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtimlrvfde.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyhantut.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gttkumbrpe.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtwfzazaxb.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtmlwjhqmu.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtlliyttdk.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtnfvjarqf.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjxnlmumx.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtvjppttlr.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtpprwoqzl.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gticrzmgfh.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtjkpglvsn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtcfrmgecd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtesvwumgh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtyahqbstj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgtqkuoob.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtdfexxsib.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtnjbciqvk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgvzkthm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtvspyjgjt.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gtpnexhncj.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtacczdtcd.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtzhtyzirl.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtacwrsamc.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtpzomgqbz.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtgdkhrqul.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuawfzoh.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtjbrgtcda.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtxggwqgni.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtxyydluir.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtatakilng.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqahudbrg.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtrvihztsr.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtnhibqntu.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtcxykpnxm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvevhdjo.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtfhcbxaug.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtzcluflpn.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtjyyxealq.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtdapxukbg.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmlmaatiz.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugkvelsp.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtfixbztkn.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtuartxzce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtbdfjmydq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtqyoadgaz.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrhaunipn.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtzuwgkhfw.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtfqztjvig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbynlcpaf.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvjacsls.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtyagjaryw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtujziikns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtrmvmgvrx.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtuntopuus.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtaokiqhkj.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtxzaajocs.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtkiivlvzv.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gthqjwppsu.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtmjhgylap.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtwlrwuxhr.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtqmynvwwt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtnoyfbmrb.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtbirsyzws.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtrtmbefiw.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtwuazbdip.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtktzqvkpv.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoyjfdxer.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtdqheqpju.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtzbooqyxb.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtzrelhiwa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtikcuhezq.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtlihzyzlv.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtoapjmoae.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtrtayzqod.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtgmpauzvr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtsinflhfd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtbcqxoduf.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtimselifp.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtvxxqlrii.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtbndfldom.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtqkhfpfxj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtxpigvlco.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtfzwxmiiv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtrqwhntql.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtoaxaozdn.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gteodgpvre.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtinvkresi.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtcwdiefnj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtcvkjiqzl.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtdqezvecu.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtodgzghkb.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtlmhoyqfl.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtgvrmxkiy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtlfnlfeqi.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtmagohubu.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtyucnhxrd.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtooiriifc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtdaumjuba.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtkspkufnj.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtrxnaejqf.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtpfarjcdx.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtqhfjipbk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtwzqjaawt.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlxscivl.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtovtyaazt.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gteyizwfbx.html


<!-- 参考信息 -->