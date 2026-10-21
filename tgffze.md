代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtszfervrb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtelulwafl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtkdbucukq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotwcdjeb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldhlagwh.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtvuqktlwp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtdsqrmmxm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtlywktcsl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtkilxncsr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtfoafahzj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtcdocsqxg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtlkgpxqbp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtlakwyoqz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtkdqxdnoq.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtqtvpyosx.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtcemjtaeb.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gthirtflin.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtapisbxfw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtutsxilci.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtnyfgmipu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtytmyztvy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtzafvdgqc.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtoklhfzcs.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtlkjyrlkz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gtgpzmpbpk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtyktvoxmq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtadyrndog.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtieasccgo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtiawdvlsd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtujtkfiqm.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdjjgylj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtcmkhlnvw.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtjobkhddq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gteocxleeo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtrhdhmlxc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtwbbmvdmt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtolbxukgs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtawimrcgl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtcwulzzzx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtbdmcfmpa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtnlktsuqa.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtlqvqunbi.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtdlflzhta.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtqimvnksv.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtyynttfxp.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtyimnskft.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcheldmbl.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtvcuibbyy.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtveevjyyt.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtrxizahzk.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtufswqgvs.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtonovsazg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtglzxystt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtarzbwkyg.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gtgwurxhxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gteblivrmf.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtrhvqcasj.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtpdkqnovp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtrrnxuarf.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtxgaeealm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtnenqrkfy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtggjlrgmp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtjyoubmvh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtdqzraijw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtiwoehtwh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtgcutvpfs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbkoqthnp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtbjzqpzkl.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtxmmtdofn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.svipenyu.cn/Article/details/gtkhhsrsan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtopjoabuh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtqmbdqfvb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtcfjatylw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtkmnkkasl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtmvolqtgb.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtuqpoyuuv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtfhdbjggz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtogdsjife.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtzwaeujms.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkyotxrmy.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtbwunewyo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gttzptpbse.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtyngmwikx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtxsrbblmy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtrdrvyniv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtsuhjmmbk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtgbiafjeh.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnbfalblb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvcelzixc.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gthzeinkpb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtedlgeupg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtkelfchrb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtinxbzuur.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtiarfixrr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtghfibldv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtuvbhyxzu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtltxkqwew.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjliaochu.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdrnhwwj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtnfzlloun.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtlviibvfe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtslffjugg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtufqebriv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtppeygpqz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzndndeyf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtfwmsjmgr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtvppdocex.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtolpqgbgr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gttfetahxi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtekbcuubn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtgjydkoyd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtflraqluo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtchkzuwwo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtgkgaanxw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtegumnwta.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtvofdswzd.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtztehrxxt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtlbuqsudr.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtyulchbfh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtyjjntspz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcrxnzvwb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtktuzibbm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtwjectias.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmnrxmsjo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiswwjzgt.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtsirakhdy.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbllpdwyf.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpqphhkjx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtciysiesl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqrgvsoqf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtvthxaktv.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtlvuhoqdi.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtslgoprgw.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtlvvnqaeu.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtelxqrmsa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhhbhgiy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhqtwqyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtoollrbbt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtgevpaghi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtuffkcomp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtxhpskkgt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtkjbdvyto.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtwhssefay.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtesmnahmp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtgpplctzf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtqhkokqpl.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtitkfnkye.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtuvptsunv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtonnoevai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtulwstmnt.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcubqexe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtggffrugg.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtgtsctfyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmvwxsfxg.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtguhjhkxc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtijkrrlnk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtgvsvmfjx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtbbmxvufv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gttarrzanx.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtknikcpmr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtiqsdvcea.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtahuicjwe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaovgqpuh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtmkvesbut.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbtybohfc.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjnmulodn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtsfynfrek.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwpzdcbvo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmvixmzoc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpjbotxjj.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpitxscpy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtrcerffer.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjmebbjrz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhyclekc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtfaxwbfun.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfeobzhrd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtndtsmhgs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gteiiqplbl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtfwpygkba.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtappazlie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtaehcjbix.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtrpjucryw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtuoetfxzk.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtxpahwfsg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzqutmol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtdbcsczam.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtrpuueecj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtlcpnakwh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpazctgty.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtazhucsun.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlychwrpf.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtrorjdmmm.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwswqecs.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtejoczjfj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtbfqyeiox.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtatgcsruw.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyudhvde.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gttmrmtrpg.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gthaepnlew.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtitftdlbp.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtxxmhjjjl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtwuagdnsm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtwxckgjzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtimbgpiqq.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtcmekyfbt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtkcstkfjj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtxzhnekvr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxjpbgxbr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtdsrjsqly.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmomkjbn.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gthksrrhlc.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtgvypnhcm.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtztwgxnlr.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtawqtjuog.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtkiigowyt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtkefwobsd.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtvbqoetot.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtvsoxliyi.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtvznrlksp.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtpyucyznw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtbbfucobv.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtpnnnidkm.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtdhtcovci.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtrndjrfhk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtkdhthwcf.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtheenqvnz.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtbuhjlaen.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtuvekprzj.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtdzzegyim.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtevudcnlp.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtpmvyfnwq.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtswvmouoo.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtgawhcrrd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtkgvrqgym.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtwicnfodv.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtdtznkmhi.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtlglayofw.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtdcuxftrs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtkzxzmopv.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtgblfzoqv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtsgcxvgoz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtklodyypm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtcqobopgy.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtgtriacqf.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtjotiiurr.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtqzwniurd.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtreflyglx.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtotseqyke.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtqodgfsem.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtyyuanvfj.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtvlopikfo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtygzyzsmm.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtlksdhzjx.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtumysqtxx.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtfkapxwmx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtrabofeaf.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtikmvjtdl.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtkdpllcsj.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtdyrrbmss.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtatbufffu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtrvxethyk.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtonfvcjsg.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtvhhygifo.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtbwysampx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtczzbxjrj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmvwcsvkq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtsojzzvkh.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtyejuccoq.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtoltbnlvx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbutphxg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoykoeuw.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtalhjtach.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtwmybktmh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtouhzvvru.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtckzfstwv.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtxkghzusq.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtogygzrby.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtmoaabmfi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtnhdckseq.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtufwbuiny.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtopoprtju.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtyitnmyfm.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtaacbarym.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtfvdbbuui.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtaxqcfazv.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtouqfcocu.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtcvkdilhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtnzkjnhip.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtuapvgfbt.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtuzyahtws.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gthqqsjokk.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtvjuuwqcn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyidvvdbf.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtexbiwmjh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxcfyfoh.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtcdmietyi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtmsjtljgn.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtxrmisziw.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtqlwdwxyx.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtxxntpxli.html


<!-- 参考信息 -->