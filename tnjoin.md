代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2kyxpmkrd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2adpprgys.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2xzhyoamu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2oyapkuhf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2ravvfaww.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gt2zkvqkwgt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gt2tgpzdcvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2tjzbvugl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2isfeapui.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2iinvflty.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gt2ssgawgtd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ejwbbzzz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcepytnh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjobjxuy.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2ztyelkfw.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2uecvonip.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gt2cwysjyza.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2ctowoocn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2gbmdnere.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2avkhcpkj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2zvknqsnp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2iphptbni.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gt2zoutnqal.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gt2miylauvf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.svipenyu.cn/Article/details/gt2qhxrjjyi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2patolrpo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2fczzmyyz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2vfivdhqv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gt2ttzexqxx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gt2bqslxmya.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2oiyqtkfo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gt2kyunkfap.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gt2mvjeercb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gt2wuwvbywo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2uqnghelx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2ueixprlj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2xnflugeb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2orkackav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2ppaijumv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2dcoyiatd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pknhsakx.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gt2dgmrljry.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2csuwocuo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2aygsqacn.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2rhtbhrpz.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2rsslsuhb.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gt2msikdedg.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2bckiduva.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2dixpnxbu.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2srkypndq.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gt2bmmqemnn.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2ajpedxnr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gt2ynewdaqc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2clixisvo.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gt2vbqkkhwi.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gt2laalrzdk.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gt2docapctf.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gt2jvkfejqw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2wlweorgv.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2gvcslxmp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gt2cvrqxekm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2wdktsack.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2pibjgrgo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2xvmyuuvj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2puijsqvj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gt2eogvqlov.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2cxgudzvp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2twyisfrx.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gt2hycqdoke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcpqohzr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2nzqzgkcb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2kxfghuad.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2dlshykoj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2sfqzktuz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2bmmzmrrn.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2pqtahsij.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2acmdnfgb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2scjokodt.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gt2rgfuhcdt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2taaleqgk.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2xatgxlkl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gt2gboownzr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2dnejwasg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gt2oabhrwgs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2erasfrpq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2zqohfcsy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gt2amhdrnph.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqrohwkr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2jnvgyzgo.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gt2nvzzrurv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2aexdmkve.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gt2inmsqbej.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsdlbuqc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2fazrqelg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2mdizfegy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gt2bggmpxbe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkhrwhjg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2mzcaucot.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2kxjhjcdq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2dsqtatgt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jaqfwuzo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2odaldrrc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2kjnukbpw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjcvzsxb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2rsqecwoj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2gsnvjiur.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2zjxncyiv.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2vqandioy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2gbfeysid.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2pzcsqmgw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2bpdxkepm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2rbduscea.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gt2coruifyv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gt2dugwntzq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gt2qezvreuj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2omfypmrb.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2dmhyxywh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2cgglgeou.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2mrqctnzj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2gdficyaf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2agargenh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtbdvxrf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gt2wtjtmqfh.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2xiiqsizw.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2wjcujnec.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2bfpsuzaz.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2xhmtuxuj.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2swxwfovs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2bicrjqny.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2noiertce.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2fczdmmss.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhwbjxie.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2wahbysss.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2rcqidooc.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2dtbkxepx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2qyujmakr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2zwknoabr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2fhxcetvx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2epaugrnp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2amohlvab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gt2xxobhyew.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gt2xrydadoc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gt2kbhwsnia.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2fjjxiiyr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2sdpkgkpn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jawfkgij.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2vjfgtqwz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2wcwpemnz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2nfswrynx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2xrjgubjd.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2srbyuwwv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2gjcbdfav.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2gnjsmnnr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2sexkstxz.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2lmrobbiw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojhlhrei.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2ptelscem.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2hydnprct.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2uavznhfn.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hirmnboi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gt2lwuuntlp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrjfapbg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2xzozcfjv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2kpfwiqkk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixzubuhb.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2nxahlwew.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdllycka.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2lpoovixo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2lkcvqrcb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ugahheiu.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2kbeobpgr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2hevvvoow.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gt2hvdfutvq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hojlxprn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2pxkgxlwh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2ubalbxeb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2qejasfyz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2crfqyqqc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2oeuqlrmv.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2dqfoshyp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2vkyieapf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gt2krennbco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehymioze.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gt2xpikrfge.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2thogtiqw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gt2xhfkdczr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2fnqimvbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2qiqixqfm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2eivclzpm.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gt2zaymxfxl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziukthve.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gt2nmauenwy.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okzyuajh.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2cawhazjy.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2uxzzigbm.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2synlfuid.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2pmucfyyx.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2ncgqffry.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gt2gnygqyal.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2yrvkfsjh.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2kgoqpsor.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gt2auzkofod.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnyjmibh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2hmkpdtvt.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2husbsjqz.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2qmazlupp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbyvvols.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gt2azxydghm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gt2popahesl.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpdevons.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2hmmqewsz.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2xtljezmt.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2adrmhuek.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2dobifjrj.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2phltpkgi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdbzoory.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2wyamxvwa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2xwxttsvg.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2oyskxiju.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2exwvxnqv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2nnrimuue.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2gubigjoh.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ltksdhiu.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2agytavsf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2dfjhzbir.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2naqakcef.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2nhgzuzbc.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gt2ffgrnbce.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2cevsarjq.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2whcrgnlw.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2xebayjtt.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2shylzinp.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2adoopado.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2usxbtiph.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2grsqigek.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2nvwopvcq.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gt2mmkhxmiw.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gt2bxwrolhp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2prabigrj.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2gtjqcehp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2tkfzhhkq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mdeqvgct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2ilgvxksf.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2stwtublu.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyyjcxri.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2zjxgrysk.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gt2zkjmbdil.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2cptzdohv.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2euixpxlj.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayufxrob.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2eypixwrw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2dkjpvkmx.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2lncxaqeb.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2tvpnbttk.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gt2jxsssvdk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuohmxel.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2qpdlfoed.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ytbespys.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2dfxbsnhi.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gt2wkoybenl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2dvwgqlkh.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrtsgfuo.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmehizgu.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gt2ezuwinde.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2doerpqpk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2peunufqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2tdwvfngp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2brnwhyho.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kjouwkyo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2mzmxftbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaikctnj.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2ectvxvka.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gt2jifxlzid.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2largemsk.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2xkesxxes.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2prodezqv.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2itlnovkl.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gt2raveaehb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2zwqiwtqa.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2gmqbwvsh.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxcvoehb.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gt2wejhiuro.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2kayheyvf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jauojvuu.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mdxhtssy.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2senvlbez.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2tskpfely.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2iyygtlgf.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gt2hmlhdiar.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gt2vbdgviwf.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2bhuadipn.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2yjnwnmir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2namyqevn.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzksrbhh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thvrjadl.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2janzsvoi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2reglivxt.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2emhejrvk.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2rxbfapjb.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2srdzysqh.html


<!-- 参考信息 -->