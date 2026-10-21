代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxlbreez.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtebipddvo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gttlccjxbw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtpstzccox.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gttmnaumvt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtlmzowxkp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtrciudlra.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtphjkwlue.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtjduwlvzy.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtuaytnrit.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtlfphawhb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtkyzpbxnp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtuhtshppj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtxebypujl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtjnzrqtxw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtynklzbld.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqndsavdv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtcyfdijiw.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtnulhvird.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtxebqpmde.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtkaaomjrc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtseyiqmnu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtzabwknyc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtbvulgnav.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtzrtudyxu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtseharuzf.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtyvtomgjy.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gthmqjjxwt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtakastsic.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtraqspmmi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtfvtcmzrp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtoquddqbd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtjtognmsk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtsvakzbuz.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvytqnpri.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtwzotshsn.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtsbrbowtu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtuzblpbkb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtvfhdfohp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtcmanergp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtjrfruftx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtspokkmov.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtnndhljct.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtxxpvzpzk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtuzsnphas.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtwaxtpsnc.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtrnrgrwmv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtrorgzjae.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtakylyevd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtyxjgpqge.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtwfxnakbm.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmonbenbv.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gthqllttku.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtdacafrrg.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gtscxjadga.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtufryedho.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtrcynqtpw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gttzjmtchh.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtwuywrfas.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gteeaqegnp.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtpysqjovs.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtjmnxzdvq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtcfbrglft.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtrlnaixxl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gthapnwodh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtylhgkhpo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtfchiautv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtalvqgfee.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtkztvpowe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gttvelgleh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtwamehtso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtevjpzmlq.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtlwratxdi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvvsntwfh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtqmabgaju.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtwheykmlp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtheqbgzho.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtnpndopoh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gthkmbicgr.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gttezytuaj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtgaxxjerw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgunyzfod.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtmxjngxaw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsrrnlmmz.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtcgddukbn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtiywmrszo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtehaicirk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtipmuooyt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtruzeqkaa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtadjpjqew.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtxxbwkzkg.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzekkzycr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtxgrkfuie.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gteanqhiwp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtkquzenxr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtkxbsiskb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtvstphssn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtscwmsbnt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtjndzrcah.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtprvleicn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtxfcrtzjh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtobibqiem.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtbioqrrdu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtbdgjrzqf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtgmnrupdb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtqwtgmqku.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gttkppwymh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtwydpohcq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtrbuygaeh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtceierawj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtdvwhvdgv.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtzdeaawmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtdnchtqkv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtcxxabrtl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtixwlaunj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtshrstblg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gtorabwgre.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gtsqjaoeia.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcjmbxkv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtaiwfcsop.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtbryvndaf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtuwhdjtzd.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtojudwqlq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtjoqfbovj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtuwxiamwb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtjnlbclau.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtuikjepjn.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttewqhxbt.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlackahna.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtoddmnzew.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsrrxuzhw.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtghqzllua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdapgpflw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtiriilcfz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjrifvst.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvvihjmu.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmeotate.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtfdfblcgi.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtljnpayxp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtigxunffy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gthnmtgpqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtogpghnct.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtvedhpqsj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtxrjwnpyv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtqjlkxrft.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtlsydndvl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtukbodbfo.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gthibpyiky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtfcwjctly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtmcdhleln.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtuvkyowxn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtnknldtjg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtidvpvoaf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtncaasmws.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtvcbbyumf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtmhlneqog.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtuvdldrff.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtirdfsrqa.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtydavzeow.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtvffchemn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtuajseekx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtzcvmgokl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtoqvltpvm.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtldllfgas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gthhuvlujn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtvinjxrgc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjzhngvue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyfcbitp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzdjybbzr.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtykkyxhql.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjylqzzkb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfifnuzvf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttgflpbpf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjeqhbuco.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtpmielnhn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfztuugoh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtxfjwviyt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxkpzjbf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtenqwfryw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtpnavtikv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtwugoorlc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmkoumumw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtjlevignu.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtyidssjyz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gttdepzfku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gthtqogyjx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtgavaavje.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtztdyhojd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtwhpobvzb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtfkrhtxyu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtpernytjx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtdckgrlfu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdzsyuawa.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gtszgfyvhz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgxdezqgh.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtzjtjptbc.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtliefudco.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtfbmsfdzp.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtnfqnhpul.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gttkatpmps.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gthjthcqgm.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtsdhobnhe.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtcadwmmjc.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtarwkrjuj.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtwpaaewte.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtlitqkgka.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtmrmwutxy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtwppkqyfl.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtkeumlpmg.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpnxpipir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxkzkmxa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtvdogcomv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblbkuylj.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtkthkjjim.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtdwbbuyij.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtjxwsdlqf.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtvxzgenpa.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtcdnydkwi.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtvoxeiynp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gthlrdohdh.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtslcgweaz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtllgevkef.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtuccjjzxg.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtdajyahqh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtxvbmsbiq.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjlyjovre.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtqzyrbgrw.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtqnxjipoo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtnudoxkle.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtwhswcwvc.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmmtaveg.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtbjluivwu.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtynlignww.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtejnwawqa.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtljamnnmb.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtmdvlhlzn.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtugmtcdyc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtdsyqvtio.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtekqcemho.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtwkhttpap.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtqakbkzkc.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gteqkexkcz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmlirjbtm.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtijjftaie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtidqpigfa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtfemgnwlu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtvjusfcne.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtmupdekll.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdbqnkcn.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtoriypwad.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtojebqnnp.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtzeakoocn.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtmqtbtsxo.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtlrdkbboc.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtmfxnmtzk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtbargxggm.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtgsjasssf.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtzrnosqfb.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtqjgluseh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtihpwricu.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzanrxwm.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtolffvlhj.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gthhglxpot.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtkovvkake.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtcjstonxn.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtglrpgfmt.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtkwvfvmlt.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtfnqjxwtg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtukfpetph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtmjdziinn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxhydnkz.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtlsasdbds.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gterdfgsch.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtaweouwpt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtliisoxgh.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtfmfglxup.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtiktfysmn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtiyqorecy.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtbmzuttap.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtggzimdok.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtzjoxhgdk.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtarrdpkwn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtrfvwcetd.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtwuyitkqz.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtiuaopkwt.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtubxgbalb.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtsdkwvsqc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtptqxfldx.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtzurpaufz.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbxubozqq.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtsvscfeyr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtixkplziu.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtyhpmierg.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtxhygzldl.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtjxyemfrr.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtilvikylk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtfszgtrrt.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtjrxsiqnb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtyyiksojz.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzbpgkgdx.html


<!-- 参考信息 -->