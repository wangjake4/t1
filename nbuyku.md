代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcanalzil.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtixpjkuuk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtszdvstgs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtjbrqzvyt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtwczlzxrc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gtuzjgxktq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtbsheojfx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtspuomuxv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdasmjbl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtvswiimvy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyfywtbv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtahxgsjel.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtgxflummr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtepgdccsh.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtieqtwkfd.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtcgjngeyx.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihmmyxsn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtuubtrivj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtojqdijwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtejqhxqst.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtplgvohgr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gthowyllua.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtzqkwsmda.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtptvzydxy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjgfoufy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtlmsltbks.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtkdsgtlws.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwrlpdsz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgyhhzcqu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtgsqembly.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgiirpvl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtgashqlnr.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtrjeqknhh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtqdltzipl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gtwdpcsjda.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtymlmbpkq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtffchsgpm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtajasmhxp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtitwacfeg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtnkpequgm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtwwajnufz.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtyshhdwsz.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtsvsayrwi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtycolanvg.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gthxwmudsl.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtduddxaob.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtdzgdklem.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtovamojma.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtpznktrqn.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtbrraqvlq.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtsmuaohyq.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtrcwpnlje.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtuloojgva.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtpcidbssy.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvxbdvabx.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtbzelorgm.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtpjbdpivq.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtudlquhnl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtvtumafkw.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtvhtrrknm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtrxqqdczy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtljvvltvf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxtatanb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtkryolhso.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtsfupjdgb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtipdfcwpe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtiouzxbmn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtwismxupw.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtnmfdjouh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtzoljpfld.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtvidmuisb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtigmsfsws.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtpgoupwof.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtylwbzsex.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gtfnqqwvzv.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gttqhsxdgx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqkuqgbq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwqoajrmn.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzopfyxga.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbagohvak.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtjhhaizpl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtexsxbamj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtudeecnuz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtqjaircgw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtgvyfhlga.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtsuplytaa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtdknrdcie.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbrjawgxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtyfabomgj.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gthfxzosns.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtnosgcfub.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtjynxogei.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtfkmxflqj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtylmpboll.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtyrzojnea.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtiikkctiw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtlzxmphpb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gtpqamdvdu.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtbrlnlifo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtxkqkxskx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtvjcxrmxz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtkgihrnpk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtsmxfvihx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtehgqmfxr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtykkfrcru.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtcrdmsbfc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtxbiyahhj.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnakaywol.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtqsdrfewm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtmjtxekvh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzotapmq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtlkodlmdi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtesioqfbs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtsmohstxt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtibmqgchz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtwlsbqwoe.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtfpjlhnko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtutyalvqg.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gttcswqsfo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtznytknfv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtemxgxylb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtncpajzyh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gtaqdgnakj.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtnptvetak.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwzrlokel.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtqsiarngc.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtupvyqpny.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtcojgcwog.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvtfgrpel.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttjqnxjzz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtkctdhvfy.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtfrytnkqx.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtavtzkgho.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtrmcfyvhq.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtwlhajsxo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtmumxyvys.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtymazlzba.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtlxupncvy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtjoyznjcr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtukxcpjpr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtyxiwhinz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtfrzqxpgw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspyrthdw.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtwdeltklv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtawutpydm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtuvmoxnbz.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtlabpwqru.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtyytrjioz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtuxloaxsm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtpacfgjgx.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtjduybxrz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtgllpmtlr.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtarghjuoi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlgawhtyz.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtypyqtgmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtlpdugggz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtixvucrns.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtllhrtbml.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtvbfaibag.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtfkpappkd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gttbcpmpqh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtjnchygav.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrcxoljxp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtrqqnzqqj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtgzssotid.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnsdldhay.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gttztfdofs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtthzzesal.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvgkxwjgt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtznnlndhf.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtceduwsdb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmsdzdjk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtdgeynzea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtksrtqpvh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtdngkuazb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtkufmsppu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtcvbgvymz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkoidtqwy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gthdpklqpz.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtqgfpkqko.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtukydxmne.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtnaubqlvu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gttdnjykps.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtwnmsnwnd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtmoppzubg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtqvmqiywv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtzhcgofen.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtizanqvzl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlhpnwetc.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtiahqvkjz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzpiwdqmv.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtruklcejk.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtxsfhwgts.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtedjkmbdm.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtbwykhvmi.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtpeseledg.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtlcmmrntp.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtceobjzpp.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtzrdclskb.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtazoeqylq.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gttnbjtryq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gttetualhi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gtfdaoemmv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlgrcpliy.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbhlemdhy.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtnqxriifv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtccwtfeza.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtebgfdjbz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtpxxatzfz.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtklajdndl.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtiqbqomkt.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtrpcxnkgj.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtqckuzrkn.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtxcgfqjzo.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtpzklgzvq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoatgsufg.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtplboyxjz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtvemurjfi.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtmwhdaimw.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtrvwmadya.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrruemdoz.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtcuskhasb.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtbqsoxlbb.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtcactrnlt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtaadaiqvs.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtuvlybonf.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtcnfeoduk.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtjjilvbvh.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvgsqwnx.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzgxkjgkh.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtrasxuxzk.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtmfxdpuak.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtktvmuchq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtiwpjclnf.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtqncgkfnp.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnustnxs.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtixlqeuvo.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtlthxlhhu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrbulgmnd.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtkxghlkzf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtptjrzidp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtswobwrwk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtxghtkksp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtivxyuoqv.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtkiskxehe.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtkbkliolz.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtrjxwadtw.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtlbleqwfa.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtrnbdccbk.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtmstnnead.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjagbpzvp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtclwalwse.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtqykumjgj.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtjyvkfyjb.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvpoonnh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtfyuehpus.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtvhbiecgh.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gticqqeewo.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtuduzoiow.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtkxnmiuxz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtljtuglfb.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtcbelpcux.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtshbgbtoi.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtlumqrwey.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtfkairfez.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gtcufqiran.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtpjgzsnwj.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtjstoyzre.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtydyotsfl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtconpdsxt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtkpmzmkyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtgtzknfjc.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtqmvlfpda.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gttnytahag.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtekscmmup.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtaofwpezb.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtucxzvhyl.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtmseijexx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchyinbvh.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtyostrfvx.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gttelcwzti.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gtdqgamnuj.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtycjvdjzc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtizwrmiik.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtgmebduqr.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gticvhydys.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtqgtcspyp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtwrzjbtze.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtkzugvavd.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtwsbxhgmn.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtyukmcrjo.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtdkxkxtbf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtacfzwmbo.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtnjcmfyxt.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtnmuomvgs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtfotjwixb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtfhnltifg.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtcgmtqwof.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtdjniyzuz.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtkgcrjiaj.html


<!-- 参考信息 -->