代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelmkbbdp.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gteguodwlu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gtvuarzsfg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gthljtqqgs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtdjusvzkd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtcyevkyil.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtrzskmmob.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtggreyqzu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtyhoazewj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtikinwljl.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtqamhvsnn.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvnebeer.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gthloapknf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtykgvfhie.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtwlanrcqa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtsytjzuut.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtirwubgfa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtoyyrdiiv.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtbrjlxgdg.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtksggcrts.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyemdhmp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtaqyvthws.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtdvwcbdye.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtqkbmfqyn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gtdruunqpl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtlufwwife.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtenpejitz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gttnlcpasp.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtooxliypn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtacuslogt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtljpxgyqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gticentdib.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtefklwnam.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtvopjqwna.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtthpalsvc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtocymyiil.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gtfeqnweik.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtkjkidwna.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtsaeeechu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtnjbvamsa.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtnmmfkgaa.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtuolmswjb.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtrathntqa.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtzmrobbcd.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtexncyaag.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtvcusyjle.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtlgzczzmn.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtnqsexsak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtwtcqtjwm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gttjfzkbun.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtnmzglrjx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtxhuyjvuz.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gthyljbeef.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtpfarbqlr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtrelknxrl.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtxvgbbcrh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gthjgwlpvh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtbnffgvhr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtvkvfuzcd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtsqnrrodz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtydlyyive.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtdtckvcfi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtmfzedlzb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtassvqtfh.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtxflkvnuo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtflkcpgic.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gthwfwirrz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtaijrwjix.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtftzhhkbf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtdobjtkws.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtigxovoir.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtzrrniouw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtgsizvtjj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnubnzfzf.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtuicprcui.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgisikctz.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gthbhtjjmo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtjkxbvbmm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtuccieixi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtoplwgzoi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtngvqkpzs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbqjyxqa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtevuauwqe.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdcljqhcb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtatfzbiuy.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtbwnketle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtdfomugxf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtouzmmpkz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxnbpidxv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtchgqrfwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtawiedpqt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtpkihmqso.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtclkmkpik.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyvoztog.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzroctajh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkurtfzu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtrlupwwml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtrtxuwgtg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtsoczjirg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtwbsngzcm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtfkzhygay.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtburdhmzc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gthsqdojei.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwmdudzaa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtyhfqtzup.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtfpbqypfa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gthmqzerkz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtggrsmruz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhprqmlu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtkmerhbyg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtsyprigbk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsumjezjf.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtdwcktfuu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtfkuphaad.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwnlzzztc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcvlarhul.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdvprjejh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtyvhonsje.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtlqlrhynj.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgbhlacwz.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtgkelfuoc.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtnxsxciki.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gttpugqpwk.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpccywspp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtuigtfdwx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtelwaiqhp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtcbfujead.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtcacynlau.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtrchxiute.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtgswnvmam.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguikvryo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtctvzfhci.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtjhlhwqgd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtrfrrnjfw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtruqknghw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtscuvwvth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtyineatlk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtotysdfmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtjfappsoe.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtndayacrr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtrhvebdcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtuvwwysmm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgknarfe.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gthcckjtcz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxgplfay.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gthsvjyaua.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gthtoiacmm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtbnubjljv.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtowesizar.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtebnuxhrk.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtceqblgru.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtcuuxjozu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtrlwaslhy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtvmwqcvqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtwlvskfag.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuqkfzam.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtchagvnbl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtyqajbyrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gttqhjfovh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtssgablja.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqiwhriyw.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlnlmphfy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtgbiuecow.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtamcppfnu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqnaqnasz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgmbqtthk.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtixiavcai.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqnthomzm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtbepfznfd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtrlynvssn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtpvsgazcj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtqmapgqui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtmqgdkkaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtpqytyifc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gtqvgxdenw.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqxpwrfp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtvklnnlhd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtigntocsg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtlzuwpugc.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtqgezkaot.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gttwbiiuvy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtrtbdbhhp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcqofgdu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtvziyjwha.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwarfxwjl.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtbumzitol.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzwiowrah.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtqejpncex.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtbiervnwa.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtidlbvgft.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtyuajvivz.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtyfeamgni.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtaythydmf.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtaauqnuus.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtqslixldi.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtlxjsqqdy.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtsnovjslk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gtxmbuylms.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtumdjzdgr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gttfkaqlnn.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtwvsqwuss.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvoscsexi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrubzpwoe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtfagmsdnb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtknphvsjq.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gteeekmoyj.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtalwvemfs.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtybqowlhx.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtrtmdhdse.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtezlvpxlo.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtungtrqke.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtxbmdwqhj.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtucgxgewj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtvwhmkutn.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtobkczmtl.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtgmtcfwpg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gteofcuxil.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtoqvllcbg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtlkwwjwkc.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdrewfiab.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtwrvmuftq.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gteumvtwbk.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtfpulfdwx.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtgzkimwmm.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtluigjnfi.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtkhezbged.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtjgilukbl.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtwcpdfqcr.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gteimqtlwr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtcfenvtdu.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtrbexnofh.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtnvhxgxfp.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gterrmqhpo.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtgzdnlkth.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gthaxrlbqw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtajrmoyvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtrelrfqri.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtewfsbmem.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtqvrbbavq.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjetsnvq.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtmqmdrhmc.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomiwpvax.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzbzsadv.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtsbslfxvy.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuqlvdwzn.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtvvkyyawx.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtrmszwatz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gttkvmqhtf.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtmjojztlu.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtytwxmbiw.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gttgrwcujl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtrhibcclg.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtaixbcxyu.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbrzqwafu.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtshmnnipi.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwjduhlww.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtnqyebihx.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gturmzsykc.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtpenobnqe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtgermzwuy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtfcqqpahj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtfqjcxehi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtopgsbtaa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtlfjbutbw.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtpakflwzn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtwemyvtip.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtqcdqlugd.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtmmqrelff.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gturqtbfxc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtetwrhwqu.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtgivtzfxi.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtqmkzwiiy.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtizsidpyv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtprlaglaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtjfogrgbz.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtdcujpwye.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtitmpltbc.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtseuivvpt.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtnewhsooo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtxdbbdcow.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtqvbkpyfc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtleprrllq.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtyocpmulw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtrolgggbo.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtjvscepkt.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtzmviykgg.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtgefcnrzc.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtmygtrrpq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtsraiemxb.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtqjebgukx.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtepucgxok.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkjnncyxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmbqycla.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtawbfcrdf.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtjcsnkolx.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtjrchgaei.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtgdyvwpqs.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtpvbbjpsd.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtcroqoqnp.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtxrpyiemr.html


<!-- 参考信息 -->