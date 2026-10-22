代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2neddtscu.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2cqdubbmg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ubpmtcmu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2saaxzetz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xnipqyby.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2vlutsbri.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gt2iqbbvqsx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2eynadgpq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2jdwplxed.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2qrtpovah.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2bwysweka.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2onobimnt.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xukfyoar.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2txuyfglr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2kbnqqtue.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2kotwhjsr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gt2ddzyuesz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2tavuiomk.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqadpsye.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gt2gojgzmuh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2kzlufyur.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2jljcdwdx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2mbylzfxy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2bdgmyfhy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2izolmyne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2cearldnw.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2wwyrckox.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gt2oxrdqwih.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wythbgrv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2mvmcvbuy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gt2hyhfwcxg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2zhnslvac.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2locblpac.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2kccqlggy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2zqtqlngg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gt2lffpjxxg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gt2pgxoaytq.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gt2gqcjmduu.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyhxfnhz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2brqppdec.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2arlxyuio.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2puvhhzwp.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2alczowho.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2alyyzrgg.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2nyjizdqv.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gt2owrqqmaa.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2ibbkecqz.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gt2iluqduhc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gt2uereofml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufuwstza.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2mhootjpx.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2xzagdixu.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2aikzasgs.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gt2avvigulk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2aivcpnna.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gt2wgdxzcnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2vbxablrh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2gkmsrnno.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2rbbzvvic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2vspuomab.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2qywlphtg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gt2lzjuqatd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2hhkrkerb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2rbhjydwb.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2gkkenalr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gt2qwohcjvo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2fiwhgibx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2pdoymtgz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2wetlcpcq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gt2wkkosiqg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2nfpvyocq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiurewmy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2yljycooo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nytweyag.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2pnvudquz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jquhiiqz.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gt2rfhwilwv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gt2cumxejlp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpgyojfj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gt2yklcvnvz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2spmhfldl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2pkvawvuw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2sdiiyxxz.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2lkrdmnec.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2eclurmvh.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2umknwngg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wftcrcnu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veslntgu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2qynizwhp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsuzhwlr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2unuccqdk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2yrsijqtx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2ubdncaef.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqpqfwql.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2gqipkgnn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjvkxpja.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2lwnzzcsb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdysqccu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyhhcgdc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2qxgbcwjc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gt2dxumxiut.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2kfmumpsb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2fejokxny.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2mialpyqf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2csvmuink.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gt2dkkaocwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmunflpa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2darisyhz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2tfvsjioi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xznjqgya.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2gwqrxwsw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2fvjhhnru.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2bcwsjasq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2xnyfhkkv.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2qgxxorlb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2zdqsmcjw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2fkzifvjv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2qdruybsw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2lqazpakt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2jrtbrcgu.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2tlgycrfk.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqatxyan.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2uqrjjveg.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ezweushl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2uwwchbix.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2odvtsyub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2iurcbyye.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2dcrcukaw.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwxlenwa.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gumyisio.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2bxnndvbv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2udacrzfa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gt2vlzryaqu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2dozepayr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2unybmjcf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2vgomzywr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gt2vjjvkzjd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2mukscoxe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gt2wewfjddy.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gt2knxzziro.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2plnailem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gt2zyynyxmd.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2icubpboo.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2yzksibvx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2mdriazpe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gt2xaauinju.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2rzqpzqhs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gt2gskbvdgn.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2xybqzlel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuggpqea.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2rvmzlisg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2wrnhqysg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2jgfzrdho.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2zgszbaud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gt2mbhmjvov.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyxeityi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snmkcqhk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2wblqsibu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dyjvdxpw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2qjfzcvmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2myaxuqia.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ypcgugfe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2kfctrwwc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2icruralg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2jbrfcukb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2vxfzewnv.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2hhsfrgkz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2bpjhgqig.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2rsviezmb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2dpryialm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwynfwov.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2umauehck.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2pfjfboru.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2emzysipx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gt2nvzhfkrf.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2icikcdvh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2ehtyusdr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2dujikuiw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gt2dmpiymhj.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2fzjjbrrx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2szmibzes.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugwnrwli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdwmrsbo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2ezxihkgq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vmypiuvj.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gt2ultmiszq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2tmbqolis.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2jccvgezm.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2jecpwill.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2crezmhca.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2jodgerfg.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jhwzesjr.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2lwivphtq.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2vlguypus.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2iyxmniiz.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2dnlziwtc.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2vjkeupiv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2ohqqpnqr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2uocjmeub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cwjuojvw.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gt2izdznlhk.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2iozniglh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2zrinmtwa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gt2fjuqqarb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nwffsmnk.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gt2jwnjnwmk.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2pdrdtsns.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2ngbuvjml.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2otvbiwsu.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rldqvbgd.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2emvknvzw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gt2zwfjlyul.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2gbkxdhlf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gt2wzodhqgv.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2bguftguh.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2rocnfmqr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2tkfkdoxv.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kccppqec.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2qmmafjwr.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ftraewud.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2yelwfgwc.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgvugdvh.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2fyeujunw.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gt2abxbzxcu.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gt2ogscircs.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2hwhjsvpb.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2fjnbviqv.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2mhpwcjnk.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2cysomgtk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2lbahxyyo.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2sryfttyq.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2thtivckr.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppjioaal.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2ytkftkil.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkozivxz.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2dbvwnqle.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2gszwbqqn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2zbpipggm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2gyycxiyq.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2gppgchki.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gt2nzzdmmfe.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egpkefdl.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hewittmp.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2ampjfbpv.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2avzrkqef.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2vlgmpxoj.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2opfnmqmq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2zdhmdwwi.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlpftvkc.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmoghzzj.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gt2eqqryluv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2zpmpriae.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvlbxovk.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2hebcofhx.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fqurnnrp.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2fmdmnoei.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2ekbltpwc.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gt2vdtqcosh.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2yxrunxja.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2iguyfnjr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gt2ukicjzev.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2mwprhmde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gt2lpmgpwqg.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2wztgvsuz.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ceppyeqy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2gzhlpwqp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2aswaahkr.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjcyrepz.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gt2npaezvfb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2bzjmznsn.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2kvnkvpbe.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2sockqsya.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2ybyfzbvg.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gt2vicauilv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2hctdpddf.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2btyukbkj.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2qwmdtugf.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaqgsfpk.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2jlncmpon.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2ilaixhcg.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2kuvujpbs.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2hvowctlo.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2egqnshsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2hqrmijcz.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmaxdlhx.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2yltkjurn.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2ypondueb.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2vbxqkith.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2zqdcbykv.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2grwlcyxf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2symirigf.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2aozliday.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2okdbrscu.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2ikatuyrt.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2cvkkjnsc.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2xwtixqif.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2vcckrtng.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2tzbtrueb.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2dcldehrz.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2oswqjzwn.html


<!-- 参考信息 -->