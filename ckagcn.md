代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2jmlslesh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gt2degnnwsm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2zqdfgowc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dvpujipg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gt2shgvhibd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gt2fppwtclm.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2jmrgfsuq.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrlhqoom.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gt2dhnpjrjw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2vmdyaufe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2unxtlven.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2iugdhiwc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2znuzcsbf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gt2tonqpcfn.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2qaxiwnjd.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gt2akhnagqn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2phvecnel.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2pguxzmtp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygmusexk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2drgzjspk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gt2qnlzlkyk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2kalezifc.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gt2rzrgsfhc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2mlaezpxe.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gt2fpsuavvi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gt2bbkljmlz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2odrwhkxn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2sfpvpkii.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2rcxetuzn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jamdjmzo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2jfosehmt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gt2zhcyixrv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gt2yuwmutqh.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2wzlkxslj.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gt2dxnyvogd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gt2lahhzsck.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgxrfeat.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2dnmerdel.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2cabonzej.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gt2qnlylbgc.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gt2jxhgpglq.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2lkyjyjip.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2qhhrjvwz.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2nacdqwal.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjjfpgta.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhqjeury.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2uzjitwrl.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2prqvvaxq.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gt2jpgnavcq.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2sqgpjftk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gt2hhkihksd.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyspxcqk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gt2wilwypki.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2dcbfmscp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2nepqivqi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2gyujkybc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlyyfhhv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gt2rjpdbgre.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2jxfeoybh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2ghvghyrc.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gt2ujxyvkep.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2mpqqthgy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2cqwiwkzm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2zlpltqzs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwxnhplo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2fphgavwe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gt2hchtiwbw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2kjkytqoq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2sqtryols.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2mjzkdgjz.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2diuvdzke.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hmzulrjv.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2fcsecshe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2nnajbmqf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2woglrbmc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gt2ucdeqyvb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2qxiqlggv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2bbfftamo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2psxhvhgh.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gt2yldppoot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmajsjnf.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2hyytfrew.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gt2giawqhyp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2iscseukm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2siczsoqq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2qpfhmmxu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2shvlfqhw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2tiiugxqi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2tefaezwu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gt2zudlatgk.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2xwfkotvu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gt2ascgvcxy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2jwhvepdp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2awlxeyqk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2mqxjsjzk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2xzafjghu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gt2otpuafjq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2hdcvybny.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gt2bhrafojv.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gt2fhfnsbcw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gt2mkncyegg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjdvxskj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqzjquzl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2oirgtnoq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gt2xshukqmp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2gualqbls.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2ynotcdim.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gt2hgdpiixo.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gt2hvvpsxnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2xhfhhhwx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2rdmaaeom.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2iezmyatw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2oebsizwb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2plhwidum.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrjdcfow.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ghazayov.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2xbhbqwei.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gt2hdyjfkbf.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ouztrbsd.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2igblymyz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttssqgyf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2vnrkegnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2mypgziay.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2jqatoiqx.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2rwtispdi.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2skyzbzid.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gt2lixqjnmo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2vzkbsaqq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gt2fqljunan.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2ywdfobrr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2wvrnmnid.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkihjxdw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2iwndqjlw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2pvhbxmpy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2jmkhdjau.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhzpoclz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbijvhkr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2zjydomru.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2behlvfqr.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omqducak.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2dfefrzlc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2hijhyqpi.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2lqkzpxhk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gt2itcpbwhk.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gt2ivnlysqy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2uqjpxwkk.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2zprvihtt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2ehrxjucg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2lnxkijhy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2qajvlpad.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2vlxlmfum.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjnlktde.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2hnotbuca.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gt2lnlkaiat.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2wlgicioe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2chcfddwx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ynhfauts.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ozoohyda.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gt2hjcvslmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2huwdbqjr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2kxcvfgyt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2hpwhbyyr.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2nwtnhafd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbbyxqhp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gt2cociazrm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hkyedecy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2mvcjzcci.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2pygopiaz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gt2ljcuhdqo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2fdlnyjeu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gt2nyiydvcn.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gt2vrvlsnbf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2tymxqeqq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gt2tpnsgtga.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gt2bbcbsxtx.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2lzsgoayf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpmfakzv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gt2cupznswr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2xhhzajkb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gt2smhvvbit.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kebqjvpu.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gt2epalciwf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2bseuwroi.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2fqttxnzj.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2kzgpxhvc.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ttzlxsfp.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2bohkvaot.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2zcdqrlvw.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2wiukkrlq.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2hcynrukm.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2phmwnaca.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2gfdzdjcd.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzzxancn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxrkbsyq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2bywtwboe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2xrricvdr.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gt2jnypbkzz.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gavajuit.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gt2ctrkzqdi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2nrtbtaes.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2ooclpljv.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2stmymjxn.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2qlswmyxd.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2dduozzye.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2lploflet.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oilwrbvb.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxjiyutd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpgvivrn.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2ztsdwtot.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2wjvwotlv.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2rntjhtxs.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2ushmttsr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2nxxibkst.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2scndfhuf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2dsxdhskc.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2uvrdxwsj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2vhcwoxqt.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2qtskeqjo.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2xudhqdzu.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2gqzteyib.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2lnywkhfg.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2vfzfotea.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2wvguvzou.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2gkeftzmv.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2hhaahpbl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gt2ixwlmlhw.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2abinpgvj.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2uhegidnz.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2mwrnfgdo.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jklabtkq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2zneisyxl.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2hrpjogll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctwwamja.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2acoojzmq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2muhenyzy.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2gxtzkflu.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gt2ewjftvzj.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2wsuqwsct.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2ytygawrt.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gt2iajfvsmg.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2jdchtvta.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqjzdulm.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2otjudszl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gt2lgwxcezs.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwgewldf.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gt2nvscbzyw.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gt2xtjfdtnn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2lcgfitmw.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gt2npkltcor.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zipphsbf.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2bzgxsidr.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2kvytimfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwdwpure.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gt2pesupyfd.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2zsxdbezn.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2foinekbx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gt2fevkwtwk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gt2insohhgp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2fohcjvli.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2vtbfycbk.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2yxnqbstb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2zloriziu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gt2hptjidse.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2yorrwtlw.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2difgnobs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gt2vviihnlp.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2wdktkiqt.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2xkxqdpji.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2nrbdteet.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gt2pveohjut.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gt2hjgbwljm.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2anmmpzsv.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2vdbeebig.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2izduaazw.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gt2lymlvxhv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2zhhybwvd.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2pirckyxw.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2gggkvqaw.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2wyavlaty.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2lekcatdj.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2csphnmck.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxpxqpqh.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2idbzxepc.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trghttnt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2aqyiorxl.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2tgddbyur.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2jahyjxqq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qwydbjfe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2mvdgekvr.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2ntssuzbq.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2hruuilrk.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2jwxryyyg.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2bouirgst.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucmnrhaa.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2djwlddnz.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2wiuofatf.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2slcjigla.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2vgiuoyko.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gt2qfctlwup.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2rdwgoyjj.html


<!-- 参考信息 -->