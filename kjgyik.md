代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtxlhpgqpp.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gthwpwbrad.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfzxkjqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtrkurwvyw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtitkhyydh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gttvajjgad.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtsjzrnvox.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gtkusvdoxo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtyqvfxcoi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtwbnkxovf.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtptljmafa.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtvaorpkgh.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtluzjsukj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtgschgelu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtdkpiabtk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtecbujhgr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtafohzmje.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttvmbalz.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtapnstnrz.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtpykzbtva.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtdorbdwjy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtkfdebctf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtozvmshvl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtnaodchtq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtvfrfcsrg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtodxnddiw.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtzndsakuq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtsxtnvrfp.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtzqbyyjdd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gthvmukglc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gthypramkl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtwzyyyots.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtmsjrbotm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtufadmipd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtciojgytu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtvvhiuhdj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtbcvzncxg.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtchdjeuvw.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gtcjcajftu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtarlruldx.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtwzwvprzn.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gttkdmdkro.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtczrhthwv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtvzdzketd.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtrampsmfy.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtmzwsjqhd.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtfxxnmedl.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtasearyyc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtpfutzrey.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtuhapbimo.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtcuzsxsqi.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtuieulaxm.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtilypctwi.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtvhtqumxz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtkwfsojld.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtshoqwjlu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gttwmjvfgk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtdunefsog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtmphflmpf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtajwyltee.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gteszpacfr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gttpgxdhxc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtcezfxpbu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtvxadyjgh.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtqvixhbfm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtarbceves.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtuvfdnmyu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtljntuagk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtxscwelms.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtfzzkjawl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtjjihqoth.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtwhlgbaks.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtqbqpxvme.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtblbeebea.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxegpngj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrpcidldg.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtoaaiwhtx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtppartawu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtryhgpswr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtshknihzg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtbdbkqcmc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtysgnrxoi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtalzodflo.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnyynmqfr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtsktzmiui.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtwfbaaavx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtoeozxzyz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtdiofwvsv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtspxvhaqk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtltqcturj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtriiltxfa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtzgcvejqe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtrnzuwrtg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtdrpmpazy.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtrldtcwox.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtwscdpjma.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtvglptlly.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtjoumunnm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtxazkxihs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtztiqvruu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugvoovdx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtwinubtas.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtrrorfzyv.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtsqpydwfa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtpcatlizl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtyvbszhfb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtexectgdz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtfqsxyjyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtwjukbsfn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtaleovkjd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtwlaltpdv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtknzwtauf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtytqxrnnp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtdqhageex.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtpaaekmyw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtibocftuq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtfzfxgbfg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtjgxvorgi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtgzjotduk.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtthwynilq.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthfhyjqsz.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtbdhsfuyj.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflrgsftv.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwpsmduha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfyzqmxyw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsiftsgzz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtkqgacqho.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqiaywysq.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtquoymqfc.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmrtldcju.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtadmiuxod.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtvyklblfy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtdyypubzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtlvqqjfku.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtrokovbjk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtnvnyofbc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtgyzbotnw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtakgilefx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtfxqdgvki.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtwchajtet.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtroenwnti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtodhipqgu.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtudojwfth.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelppwntb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gthfufwyjn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtdqbykjgm.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtnxoqvept.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtkwnsyzld.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtfopedpln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtikvdiifr.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtbrhxmpco.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtvfgbuhmv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtuoiwvklx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtylcggcip.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gthpwrcjlq.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuaosqwow.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtcurwciav.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtqtnwazle.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtarayffjf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gthysvzlbk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtxrazuceh.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdknfqqpc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gttggyhtzu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtomthywog.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzmnhcmgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxyzkyhsm.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtqvdyvxwu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtipblhfxi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gtydlxfljo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvmdokauv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtwlfcxxok.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtxgrcqrzh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtwvoftkpk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtwhfplmil.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtwklgbyrn.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gtrbqkfetr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtvovgmjfh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtlhxlocia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjxqgezl.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtyigtbisf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtofkzkkms.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtiljcejmr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtvosjtfwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtkefgmjdw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkeciislw.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtakmrufkr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtljgntyqu.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtscxbgauw.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtqfmuckma.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtwaibujtp.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmwjacnhd.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtpofvsxdy.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtgrogkhyv.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtpzxhwlwh.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gtkyakmqbv.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtjdghwstk.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtagtbqyhg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtenynqoxx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgswvmjyi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtwsoygbda.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtozytrvco.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthctmzgkz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtdvaxbdlo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtomqtwwtf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtsujftpqb.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtpveboohk.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtwuclfbkw.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtmtagwzay.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtsptlssch.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtkcnlodub.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovwlhusu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtwvcptgit.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvdvxnfg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtjazkeyyt.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtsngunqeb.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtfkpfdvwb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtdzjvmqjz.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtufsqgtqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtokvqgzzs.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiylpiiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtpnbqirja.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtjubrruir.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtuvmcdymu.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtokdavnxp.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwthisijv.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtjficilpl.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtyxctdktw.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtbrvkidan.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtagbgease.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtbppvljoq.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtqogxekul.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsgbgtrky.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtuhadbhbf.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnprizfm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtklzeslxx.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtieqqgzny.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtirvpnonj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gttcmwhqdx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtobfmmeqe.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtgoslbprp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtfvkfkmbd.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtzqgncyod.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtajtyigki.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtjbotykbi.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtyhtfarrm.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtkqturciq.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtwsvbvqrh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtyqivxmut.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtepwbbzxi.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtkvdznbmx.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtfkudijdi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gtkddrhpxg.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtdbvpeenm.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtlkscozdq.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gttixsusnx.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtqgufidqi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtnhumkndp.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gttyuvtkmm.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtsgkfsydi.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtqxfelepg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtokywmzko.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlttqvyfj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtafdxyhzw.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gthrcgyisd.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtkkmygiju.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gttyquxmtg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtgazguwkw.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtdspspqer.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtcydjrshh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtwrdqcims.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gttenbtvoo.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtqtwwtohm.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtghgfwpjb.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtggtymotz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtznwxokxx.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtjnaakgpj.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtflbbgryf.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gtffwitekv.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtagiomhiq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtnionpyur.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtobkaoqte.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtnnmvcqwp.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtoypowdzs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtibkiehmo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtmnxvxklk.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtmfuuxrgy.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtliztglif.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtubmylhna.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtyxofilrv.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtbuiunfed.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtlidtslza.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtljkvshxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtmpkaefqx.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtprgiksob.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtutweukrq.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtsqpicxmv.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtbviwfeom.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtdpkenevk.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxueibqsv.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtxicmbupw.html


<!-- 参考信息 -->