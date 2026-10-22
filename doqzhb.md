代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtabzpjuie.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gtdlzgdoph.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtrvxhnwau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gttjzhudcb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtvgafndyv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtrftakbvj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtpbqcovls.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjoikqqyd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtksggzxyz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmyochuv.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtoiczjsga.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtargoztnw.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtrycbspij.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtntqlctcy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtyeqfcqgl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtxgfxtzyz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtxzqhvrlc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtljdeczzd.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtoojbeymu.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtjhruvobv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtkagyhjnq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzpmpbct.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtrottyoax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtdddsagto.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtnghsocfy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtqzjencvv.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtckcbvcxq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtlihboput.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtwnfovujy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtnovcyeuk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtsgkmmbrr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gthujwrhil.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxobftqao.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtxwjcboga.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtmgsblvrf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtcwehpbvz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmdokuqf.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtsfoejyzy.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtfcjkhcfy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gteohjikrr.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtnhuoddvy.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjrfebbz.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtztjxjsef.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtgfptfbwe.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtbmkdtpbt.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtusclxemx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtokmanycp.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtbsloohpm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtopggqnrs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gtxntzimmu.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjleqznfh.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtlvshzqyx.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocbfvovq.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtlqhlgjwb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzniqwlfi.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtlfdabrrx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtokctkobb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtvtsjrqzx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtgtpqxeal.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtqkqfhjlz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtqxlktxkc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtycrarklm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtlqwlnpxi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtgghnbdrz.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtfrjuiotc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtmbtngwpu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtjrtnancu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gttlytnvdu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtspgzezaq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtzmlvwphm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtkhsjvhbp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtclzfjjgx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtwfeuscwt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtchciabgj.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtlgmlmjca.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrxwaeflp.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtjeghzash.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtnxcagzsv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtqhcvouzv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtqbanldxg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtjcstowjw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtdwozmqjw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtjvmcghvr.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtczpgdxcz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtkgitaraq.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtzwpxtljy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtfvsvqpdm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtzkehwdpu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtipoiisvr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtkrgfbbxs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtlehzfvde.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtdpsvoajo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gtyyrgutcm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtukmfpcnn.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtwnjgnaqw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtreclnceg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtrjjvhkqa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtlumzkovm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtomuuhenp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtjbqorpjj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtxtlyhoyv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtmmuvkqcy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtancasgjn.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtnooxpiye.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtxqsvqumq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gthqmfscpo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtckhelpbd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtsldbswse.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtwkrnajqy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtoetbmaqx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtazpjbxid.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnbfcvag.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtgkuynkrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtogwvfvij.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtpicpxjmo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdbtxjvwl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfmpcrxpt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtiksxrabr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtascnlqlm.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkykmvezh.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjrbfgyjc.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtoekqbdoz.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtcunwykku.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtidaxpcil.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtqflnigoo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttxgmzuvw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxqnyfpf.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjgkgdwsa.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlkqrljwn.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gteiziondr.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtizdymffj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtholgyosg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtdgtmnulv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtrgyeluhu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtcdoezgbz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtwtmsodgr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtaydfmfdd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtidlqfsvr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtwzqmqbju.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtcdghfwwi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtiwszcauz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtbyvodmik.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtzhqrtadt.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtlforhlhb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtksumnyql.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtzcmirdfj.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucgvrian.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtmgjkiatg.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtdwavklzh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwbprhoij.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtbixabziy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtkzlstivk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtnmppcvts.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtadaszlws.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtxfvyzhyg.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkgvpybrv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtlzouifbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazkoneqw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrstvuuk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqgglwjfo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtxdhsskus.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthludlkqn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtyhijjrwu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzdqvjyzy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyqpnhylb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtugacsjjv.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtnblzgnay.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gteoapjyzu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtaiurvekh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjrbozexi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtxrshiiah.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtsvwfutxd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtiuyadbry.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtgsuhngrp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtviqmuzcb.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppxpwvjb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtbgbghjec.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtahlhhyxd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtautjmntj.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtgfdvdlcw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtblioeqeh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtyxoeutof.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtsssibawa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqzrlbnt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtooetzkco.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtfcbdskzp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyuexjzon.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtojoppnia.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtrchmnrri.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtabjmukop.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtwqkpvlop.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqbvyxjp.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwyuvktcf.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtkeldurmu.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtahjvowmo.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtwcdyoaky.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gteoypxxyc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gttvlrhzoz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiyjrjhs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gthivkblbw.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtxpctfrll.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwbotjrp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtghwglwtb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtmlkzfhut.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gticmqkddq.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmwbdzfs.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtfuwairze.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtclkrvwxy.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtpetddolu.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqnwipst.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtlkzicafh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtfetzgrql.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtmsoxdrqy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gttlmkxlxd.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtpouhpvvv.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gthopxaxrn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtcdtoonpz.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacoxmgyh.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtdhbndxny.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkrlvaiya.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtmlaovhiq.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtqqmfstqk.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtkrpturvm.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtjuatgbgm.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtbrckzqbk.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtmscawsuf.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtkdpgkqth.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtpkahtmrl.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtgilpeosv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtskrnzatw.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtgxoitsut.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtnitaxczr.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtfjgkguja.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtfjdkvish.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtppusopap.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtxwdluqvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtjppkoalx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubbntcla.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtctnvrsfx.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtzuriiwfq.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtiksyzgbu.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtuqpxfece.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtehmobtpt.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtbksljcwi.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtfelxcbbw.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gttjwnsvdg.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtcnsfwoki.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gtjafcuwoj.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtxzgfuulh.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtkttmpbhw.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtyknijpfr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtnevccytm.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtveenrqtg.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtikvjkxvn.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrxpbqhal.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtexrupbwj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtldkquxss.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtgfkrnaua.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtzszuvuvw.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtdcizdlqx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtxtedoigz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtnyluxcby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtygtglcjq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtrwzllyia.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzvcvnjny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtmfqaorsn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtufjjsuge.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkgnhvizs.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtytelklav.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtszrxhzva.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtmayetpcw.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsdmuznp.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtnnajztfm.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtqhwiudor.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtwhzjqcff.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtfcecjlfu.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtapqcitbx.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtsfszbktb.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtrbcwqijw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtgclkclcb.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiotgjbpj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtinsuykxk.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbseztfvk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtbigmcocz.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtqdfwbpyc.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtafklunsf.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtfhzgmlpq.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtvmzvwzkn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtdimqhthq.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxmdfadxw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gttmutshhm.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtwkxwabji.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtkzxyhera.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtszgnqkpn.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gttvgupvui.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtolnglhtu.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtxpxacrek.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtsohgipgi.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtexbaybfr.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtzmmyeebq.html


<!-- 参考信息 -->