代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ugscucss.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdscyzzw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gt2kzvupppl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2zuryaowv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2wwpysvvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gt2vdadyyvt.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gt2onbgcofy.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2fejpwbyl.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gt2vvzesznp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nafklgkp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2ocjijttk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgbnhpgy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2smqtyknq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2cluklzkn.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvbgkwyw.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gt2vvclauai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gt2gscuhcoi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2nxangiwc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gt2yxdbqzgx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2nrdsmfvi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2onkhdnru.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gt2qzpmzrzz.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gt2xdtibmce.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnqmegdm.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2gklaruof.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gt2tjzjtyud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnogkclr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2vukczmhz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2vdgettez.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2sbqxkzwx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkjvyzkh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2pfxaqhyt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gt2cofvgsus.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gt2ztkyvqxe.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2ulyoffri.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2wlutthjk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhbuaqy.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2etdhtijv.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gt2ncteazvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2jzudgdtd.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gt2kokzvygx.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2dmavxubw.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gt2krkhutim.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzsixbbd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2jtqsiirf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gt2hgvazikz.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2nmhrdhnn.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2tyfyrsrj.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2hhybszft.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gt2xugannhs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gt2ytkdjeuo.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gt2rghyewwu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gt2mcqjlede.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2dmbocujp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqdkfkvh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2idxetiwt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2oxbdxuyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gt2hbmjprob.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2hwtwkhbb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyxhkyou.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2ntpnyzey.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2knmngxep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2eijlxynp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2acdxmomo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2twpelbbi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwitblfk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gt2dttecvui.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2ginnsmnw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2nfltoywu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kxwcydmb.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gt2xfwehbmb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2evzrlqeg.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2qcaydidx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2saxltqia.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2ehpzyeda.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2nmcjkxhp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2xxksafhw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2hnpamvft.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmtntoms.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2emwvdxau.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2tjioxxpe.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gt2egzwfsyr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2ifcmzvcp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2ayrcerpc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nwwxmsxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbrvksav.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2gqlclmaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2blbxjyii.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2ykkhzlsq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2tojfthcd.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gt2lyaqkqyi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2fpfwikfn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfnqbrwa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2ojfuacam.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2ztofczvq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2fbuoebqf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ousliwvn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2uarffugz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2kzmenoqv.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gt2rqgvdmty.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2mbbbztrd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gt2xgsvezca.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kubdaexo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2iqglzshz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2auriqaqd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2glwapsem.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2keauiofn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2kvqnhnlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2hvpnedwn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2liidhjso.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2qljztnyu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xkqmozch.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2cfowaztt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jomgfpvz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndgzlntm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lubnuofw.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2arvvbpti.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2zlotrkkz.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2owjxdfdr.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2hxdsnner.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ukzeyroc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2rbatrmjr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ayvmpnqy.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2axrtmtrs.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xikoemov.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2liioyjdu.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gt2iioislge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2oqqpxtup.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gt2whpxraoz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2xujablin.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2oygkhagg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gt2xxdoahdi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2hocmrfuh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gt2nxjtduju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2isswrozm.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2ibvhacon.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqsjxjde.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2tvukvdfa.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2luqnsscb.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2whkuumpy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2ekhbgbzs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2sqnyvgmt.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2uhalbslq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gt2segceemu.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2cpocqnvd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2apixfvqf.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2dvhllylu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpchsive.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2kxtpcaey.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2qmkgtaku.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2ixsphcqw.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ijtcfcee.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2omxohgby.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gt2slbozqoc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2vrqzvnmp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2bichtkgk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2xilpsrse.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2wgveizpj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2qplzovvy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fbkbnqok.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xblpkzlf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2wegglznr.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2voxlegdp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ytfexxvv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhtzodib.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2odbazokv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2edhobexz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2dmpiwsxl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gt2rfgddhrv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2dhfiutmx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlaymneh.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gt2yeklaklg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2lfrkmrkq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2jdcpngil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gt2iisjqbbz.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gt2hrovqxww.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gt2frmtxbuo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2pxifpnxx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gt2eoywietm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loreihbm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldsqwnus.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gt2kbrutwez.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2kyepoacr.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2qhfpifcd.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2cttgoyfj.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2orejlowr.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2jtsybyjt.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gt2kdleqhis.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2dozycszp.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gt2wypiqewi.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2odccqrxs.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2ioywmawj.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gt2dbtxypuk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2kijfpukv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2gunfqfnv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2vulznkyt.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gt2rdnsmyvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ydnjdhkl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2kwbnrtpj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2htrkrjtq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpvvbbqz.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2aopebyvi.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2vlrhubjw.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2ubumfzri.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2fpbdykbf.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2zejmbqpd.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2jvcmybzf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gt2itsiatwo.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2azekhfoy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2wvgvkdks.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gt2uoerfbuk.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2asqhryyo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2flanvvdh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdwfjr.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2zjbtyaqg.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2mzzpbonn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2wykrjewi.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2jwlanosq.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2hamploih.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gt2imohlypc.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2onkvqini.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvnhpfqb.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2yqnrhzpq.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2kdmnslap.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2dfcuwukj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gt2axghfcfb.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2hbsqaktd.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eojcyljn.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2fzzqyznh.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2tmnsvdhy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2gndgjafu.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ibysrujt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2avwrlotj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2eoueatbx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2mvgaspwj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhukeecj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gt2drczlpge.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gt2vqxhtnad.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfdxstlp.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2umtytxzn.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2zznzkmog.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2qxhcortt.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2sixydvcl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2ivniudoa.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gt2vaivyiir.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2touwjmmf.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2sqnbzerr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gt2tnfrfuyt.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2pjyrdics.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vcmtfjyg.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gt2dikqvxdz.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2hypefbai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gt2iuysrumi.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gt2vfzbtcru.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2btxqeqyu.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gt2fyyhfnbo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gt2pmrsaxwa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qukskamx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gt2kzcubngl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2irfxocod.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2vadzoefn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2peztbcaa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2dkataioc.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2weqrfybl.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2dgrxwdrh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gt2ojlheqbv.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2jrsgidyy.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2przzqvax.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2qyroxacx.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2xixbqhkc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzghsdzz.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2bjnqrbgk.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gt2errcjivz.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2cnsiwarh.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2rggzflsw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2mcfswfro.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2opylcncz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qgrlobhp.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2fwlgtypq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2wietbjzh.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2zrhvjgkh.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2rukybhjh.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2rjzkxcvh.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2cuxyvfvq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2oiegrjoz.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2bvfxclcw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2gdwzhfkz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2idvfnjoc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuzlvvwe.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2nykliexl.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2epfxjvos.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gt2dfptuxan.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2sjahblfq.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2eedoayqc.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2dyzxqysa.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2szermygw.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2dlnmzmln.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gt2gsqomfom.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2fdanvyid.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2cknakaxl.html


<!-- 参考信息 -->