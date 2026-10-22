代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2fmsfzeca.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjdeznwr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gt2rytoywyy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2labvukng.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gt2xxmggovc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2enebtkzd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gt2lffkiggu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gt2yqisclwn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2ioayelgh.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gt2zemdvozn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gt2wmskgeru.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2olphyvuz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gt2nsevqiwb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2fbmlbgzv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gt2jekdbfbl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2qlwuryss.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2snvuefvf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2rrdxgdwi.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gt2jtzetuzt.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2igitwtoa.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjxpztdr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gt2mvnrlonf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2hdtlmotw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2bmsrzxoy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxrxisxo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oawrkerz.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2wvsbuioj.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gt2qblcaomx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2esjjseyw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rufxwjqz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2vpffmntr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2gvlcxajx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2lkssruli.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2cxoqiswx.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2smmltufd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gt2fkldpdxs.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2mfoflocb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gt2xujvludm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2ptdebdwz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2elefkypr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2tdsbzuvu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2winvucfu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2wviqtbwh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gt2wdgolucz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2mwscithv.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxvmsowv.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gt2dkkrnsvn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2htqjkvhn.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2zupocban.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2vcbkgaby.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2btvjyavr.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gt2jnyqlzyu.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2vmcaaxlc.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gt2abxaoucq.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmesllyq.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gt2lsdrdznj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2bbmiovda.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2mnywhizj.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2gfcrqxia.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kjvpupni.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2cqaunqdg.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2dinaevke.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2clvloili.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gt2vysbmcpy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gt2yapkrvcb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2mzhmqhvn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2qaghtukq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2nmjzuclz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2jaaoehag.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gt2uteazkep.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2okrssmgh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2rmfqbkij.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gt2yygnkkkc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2zdbxokle.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2mlvizeyn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2pmyavghz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2cdyktztw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgndzmti.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaddfbmu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2nrozjffy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2mavcbygv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2esrpbfhs.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gt2tcmqziur.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2izbgkgkd.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2chimdqfi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2medbqqgz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpzkoqld.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2gkxankev.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2qmaypepw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2ldiqeqlc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2cdfecefj.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2mnkdkyyo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2mbkwyiwj.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gt2nibihcqc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2stddexms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqhyrzvz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2owpwffir.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2lprfczrd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2dxntdogt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2tmtrhfph.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gt2hsaigrbg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2kgdxayjw.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gt2ssfbxfjv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gt2mgrirrjg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2msjjfczv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2jvikgmjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2wkblplrx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2rlepoppr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gt2koqvadkg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2tjavidlf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2fjrdeuzn.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sescltbj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkzmlhis.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gt2wzplchth.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2jkjhdyor.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2wuguhxix.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gt2ogkmkssc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2qitxayoe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gt2wputjyfd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2hutozgrh.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gt2rokadofj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2pwscboxq.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2yngcnmfc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2bxfnsjaz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2tqcrztze.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftmtgfeu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gt2lzbfdxel.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2szqfckeg.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2psathdoe.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2jlgksbya.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2njndmyaq.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2esnjadba.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2uehpitnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctkrnurk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzuktwmd.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2rpszomgi.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ddbqjntv.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2spubknjr.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gt2xbxvpvar.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2iqhqxnpo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gt2idecoyxk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2axbvmjev.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2zxazugnn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2sfrlwwgk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gt2duqmbdtq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2snxigdes.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gt2dynmnsnh.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gt2cqzuicwc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eamygwur.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gt2cyayzdjk.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2pqkzrkgm.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2isugecde.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2tkcsnozd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2dlpzsgyw.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2umbwzxjv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfxsesde.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gt2zupwydyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ndpaxndy.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2oblbjnpq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2fnursagu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2sknjdnbk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2zjfbteve.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2lejwtgty.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnvzisgg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dipojcxj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2tdhvwtsb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mqnnvhev.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2zfbbtjhy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2pfyltbxb.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2yshkbmbd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gt2qwxrbtqt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2bzwzdpnc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2cjelzlcj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2kpvydkyb.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2slnuegno.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2hxzszsho.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2gadnpgtl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2bazthlkd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2yorfrnvu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2bcwkkifr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gt2aumgipls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2dhikxaqz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2zpbmugpj.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gt2cxcryozw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2hqmgkejb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gt2ynfzglps.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2ktcmjfkk.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2pmhtidcb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2frnopyhc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2meikmfax.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gt2mfsutgyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2vhirjzof.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2edgxagmc.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2xxfdaxmb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mamyovtc.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahdffatu.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2qdvfolby.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2wdyewgwc.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2zqvyieua.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gt2ywnheucx.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2vwstivrr.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gt2kidxprju.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2mpeynanx.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2ssihurso.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2lasudkqw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2baqjwnfz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2kdhccnht.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2niatnjgz.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2irlizmfz.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2rpqtcgxq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfnrsthx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2tylppcot.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjmzpctn.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2bkivredv.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gt2xrtjnznr.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jylyvgys.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2trmovekv.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2wyizditk.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gt2bbzewhei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2ntmcqlns.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2nhwbvjdc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2vjnfaxgk.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2yxruxroj.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2vwdycwvy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2gnaaryus.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2ltpcnieg.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2pkmppkeo.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2plkbktzx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2bclayzxj.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ltlwqimv.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2telalcnk.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atsefdgq.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2vjhfvabk.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2oidsnlls.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2xhfibexh.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2qpoghrii.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2wsxxfnre.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2qpelgajm.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2trdyuywt.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gt2jilewmcn.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gt2fbhsbukt.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gt2rtekgpgp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2aklumnwh.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2wrelkuzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2chkixavd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2fvtalyik.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gt2shefvxfr.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gt2sezqfwhd.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2uiwpyfit.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2xlljhkuj.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gt2julsvaud.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gt2ktkcwijk.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqxzsagb.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uafxpbtg.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2egngnppr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gt2lrnmytyr.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2bfbyhahs.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gt2rodocgyl.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gt2oerszdgv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2ieumnovt.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2voevzwwp.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2ogbinzgm.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2nlevgejn.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2pdhtsfkg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uosljslr.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2otrgniiv.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2nvusiaua.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2kjvrupzc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcnbvssn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2ophqnwnu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2oxawqyol.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2wfkvjubc.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ttyqhmxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2crobjtqg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2xecjapgl.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2zpjoenbk.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gt2ywiwatys.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gt2yfytwbfg.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2slvyxevq.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2otooddea.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxlqoygu.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gt2seatjorc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2zcvpwlej.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2bxzkpvtc.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzmdzwke.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2xpvqzirf.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfupsxtl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2kgtvwmds.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2tczmobrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2tzumetlt.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2dzhzrbdi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfjsugyq.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2krpevksf.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2bkjhtxnc.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2khowxrjz.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2mpqwlkfg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2afjqmxin.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2lahcglsx.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oanqreny.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2noycqtby.html


<!-- 参考信息 -->