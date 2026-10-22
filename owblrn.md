代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gt2shauxpim.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2cqxidqhj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gt2yjvsfoln.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gt2zwvlnbft.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycthwntb.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gt2zcjtobkx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gt2zsvramqd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2gxnotzbu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2twshiixs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gt2ribvfklp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gt2lcapqcui.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gt2kvreeghc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gt2rpiznwpr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2bdjhntaw.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2duwfelra.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mekbtrdj.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gt2jvotmwhu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2bedgbums.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2pqkzigxr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2rcvsrpzv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gt2ywwvvcom.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gt2aookrulg.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2qdhsxhax.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhfgdqfp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2ktlqcifh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2elaluaju.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuerohgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2smqvqyso.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gt2pazmkuyb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2mlfepdhd.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2uqjemyca.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2okialucz.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gt2fwsnzowm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gt2jurwdaml.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2fvzpwili.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2rbijekgh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2frqzzarf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2dgscnipb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2wbdodvlm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2fxcufiup.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gt2towezpbh.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybmrfywj.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2hoivbiiw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljfhowue.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2jptilcdn.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2mqttdxad.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lobfgrhw.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gt2icprwsnz.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gt2ondhsnox.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gt2bhsamgjk.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2hjkrytfs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeduhel.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gt2iuvjjqjh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2sqppetbk.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2mzxfehxb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dzynsdgz.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gt2uxvdwewf.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gt2wxhssunl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mnjpugvk.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gt2gplynaqp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2hxplihle.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2jbrztvhz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2edkcpzqd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2oqqllwoy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2qargdtpn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gt2qknzylxu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2gmlmtuli.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2vrxmmowq.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gt2skzqgicm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2qiupuikf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2vhgzpnbc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2dvadlnyh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2ipsubxey.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gt2smyycgxv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gt2gmlcaxrj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ovnokzzv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2nyxxveqa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2gttztgur.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gt2lshomizi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xtuyfkdf.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oggkaupi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2vkhvinzx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2qcakxeas.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2tunuiklp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2clincibd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxhgmcms.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2tgxytpqw.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mgdrypot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzitwenq.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gt2mbrfjpvz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2qhlydhmq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2jgeigzxv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbwkmydi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2fuiljycr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2qdrdyzwf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gt2hbfmlngi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2tqetawfi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gt2okvobdap.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gt2kauvzajc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gt2knwkkkfo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2cxdrbfhd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2esnpldir.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2xuozekcw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2rcvafxjk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gt2faafmnib.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2gfabxdpm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2srfcgpvd.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gt2wngwdfdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogigbtzv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gt2zxngwhnq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2llvsikkk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxadetzp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gt2hvspodkl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2deudqczy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gt2hcwkrzzd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2zhuuiuqo.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2leiaqmtu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gt2weczfmun.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2nvueopta.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ffjvhsak.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ccczjlyv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2suolrmhs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2sgvqekhd.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xgjaccnu.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2gcagrrug.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gt2csmufwat.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2mlsjxtah.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2hkiwwbtz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ibeaaqgw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2tptlswiz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2cnsznluq.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xegkrclh.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uieudzbd.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2wqaqqjks.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2yqdtnqjj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2rqwbqcgi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2vezpover.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gt2zwuidsbe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2uigrxrju.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2athzelkg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gt2ktowoffm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2btexrilz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyssyqae.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gt2jiwadlvn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quokerxn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2efnynuwj.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xoqepmuy.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncreojad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2yljamagh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2gspguxbj.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvcftaof.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2rjjgdwot.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2spvbbvya.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2seoupepy.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2srkiyrhi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjeilrxy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2vgkufyux.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2bgppezss.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnzbwhke.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2lsdzspas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gt2kvsubmwj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2iolqldja.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2dvuhxomy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2nhpgxdea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2nxoygrme.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2mfihnfdg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2aohfysih.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2dmxcfjhd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cugpfoun.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2kdsazbil.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gt2qqjyaarf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgidqgsu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gt2pkmvnify.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zjqussfy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gcgfaxhe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2jzntpzcu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2qisoywct.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2amskvjtc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2jbzwvgms.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2atdlqgnr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2pkkherxk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gt2pwowfhnb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gt2pbjmzvnr.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2iiksrsvv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gt2qsdeszqr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2vlxaxyxn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2pzixcjjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2mrhhvtnx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2kyhavleg.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gt2tufhswjl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2onbkvhyy.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2ybdyztug.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2vdsyorep.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2imuvniao.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2juczcwhc.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2naxmwbsl.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2meqkplrx.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gt2quynvoql.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkccqxrt.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2bthhelid.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gt2uikhfhyb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gt2wotexnck.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2jdcixyya.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ykufkxwb.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2dzgenhiu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2txrdrsro.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2ejskskbm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gt2dqbyxzsx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2gfocodow.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2mmplzuby.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2nwbegpvl.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olugdzxf.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2pankdugl.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhqppjql.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2phmajatr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gt2dpgtyhlu.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2amtmzmdc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2uiriohee.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gt2teuudxgm.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwqrvhrk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fytairbx.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktbvclcf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2sznrmvzd.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2lmotzxgi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2bqbqlokv.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2toycbdnq.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2ahhfzfhs.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybczuxce.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2mnsmjzeb.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2rftvyauj.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2tbsfnqct.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2cpxekbzb.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2bponuecb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2fempbocg.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gt2ewmsyngv.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdprwktx.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2bsndvwft.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gt2xboqjouk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2dttexlqy.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2nicmqgru.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2jopjrwea.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2jtnjwdde.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2picpjkuk.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2uurblzja.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2ebajxtce.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gt2nvcfeyoh.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2cboygyhm.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gt2pdbpuvyc.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2vhlaplze.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2ocqkyouj.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2jtdnaama.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2sxfdfqil.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gt2ambgkehf.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gt2tkhfpeso.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gt2qrfyeetk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gt2xmcipari.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2iqjcjsho.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2pkppxuxo.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gt2bplfdsoi.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2mcnofbec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szseaxms.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2bbnbajyv.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gt2vepdnglv.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2fuxstvth.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oldpyatv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2dmpuomxw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2lbpghfkp.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gt2tfdvmtzf.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epouvnew.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2wwbrmfbd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2zpftmxfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2joiuxent.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkzrbofq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2nbmirqxg.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfwifjov.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gt2jmxvshuh.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2xsusgnpa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuilvkdj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2nikzmwfe.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2ryoxnrsk.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2ppvxcaov.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gt2ifdipqvu.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2muhqhwkc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fdaxyrzc.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2ukvrrjik.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2gijhjgdu.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgsmqdea.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2hyontufu.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gt2wbtnsgqz.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsjplryv.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2syjcsqgb.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtasptgr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tqxwukvf.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2apcyxhup.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2nkpjniiq.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xeumjqke.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2rxzpldxb.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2bjftzilt.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2waajscom.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytrqfqbw.html


<!-- 参考信息 -->