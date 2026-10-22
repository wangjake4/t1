代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2tqvthmkj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2rempnzcv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bccuylev.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gt2tprfhrrr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2kbofionk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yajjhwon.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2otuhwuyf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gt2otzdzzkl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dafosrua.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gt2lsogzvlw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gt2fszqphdl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekaooofz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2scjihqfq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gt2wjacqxjo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gt2butgfziz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opmnxvwx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2vkuwzgky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2zjttlfss.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2cmdwross.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gt2bpdmaioy.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2cozmfpps.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2redyxthi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyanwyoz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2boeladbi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2ypiyxynv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spmwfabt.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2zsnyjzjr.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2cfttfqfm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2fmqxevgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2bdsehmgc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bykrwdrb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2ikcpafls.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2phccepwg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2dndfemwl.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2vvyfotmk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gt2mkffkmfu.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aytlzkxz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gt2kohgdtiw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gt2ozdrmehr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkhsnhvc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcivtasv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2kuhyhufr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2htoqpnnt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2nyytwdgy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gt2jxwksync.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gt2jascfbpq.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2blvbflos.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gt2rsriapjb.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2qwwqvcll.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2ieffiwhx.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2ojrompdv.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duilagbv.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gt2bhcjdbtq.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2rxiqtuny.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gt2szpzbtbx.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkmgcopm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2qermdczo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2xuszycvu.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gt2urftmywc.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dzzwzuym.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2qsywboqp.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2yzwezmen.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2acbafrdi.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2guaxmyxr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gt2dhgjdkjb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2xsxcoaas.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2okhahzqo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2dkevukrs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2wqilyqut.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2dsscvivh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2pfankrjv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2jnjtnspb.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2hdhlnlzs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gt2hzcawkls.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhtrmpvs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2jvpstfrt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2txowbvxp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxqkckxx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gt2gqpiamek.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2tyjjymyu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gt2ugmrisoc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mayucvsr.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gt2gdvtzsvu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzabrrbf.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2sawtejbt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gt2biynpjjg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2jtmooged.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gt2zavsgasl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2vuvwvpku.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2gchvfcon.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gt2ejbbzmuo.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2cyfrloxo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uueehbuo.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gt2sqppynjf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2jpeghqqv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2aaeyxzus.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2vjntjcaz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2oykhidzg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2hrhpzxuw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2widhpegx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gt2wkimujci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2lfbmgpab.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2jfrcqqef.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyqoinib.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2qqnazrpr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2yhyvauee.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2dgrwlgxs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gt2auaioiry.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gt2nfhisszn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2myuvvpze.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2fdimoinf.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gt2yyhffwbw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2thsjvklk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gt2mufswvfw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2nukwkhdi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rplqcpwn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gt2worttowf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2ynvpbezq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2buubiabl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gt2gaiufham.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2ufamkvfd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2gsetvlij.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2lcefivqk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2uvvwyfio.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ipxsvezg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcsqpmkd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2czfzztln.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2fktlucmp.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2yeowcypn.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2hbqjypwq.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fnekjyxs.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urfgvnqc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2iqtdpekd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2bujaercx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2ncyjkvjk.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2eubsgdfi.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2wunyggyf.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2ccaacyqv.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gt2jpllqimq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2drsntuit.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2qoooafbo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2fhdrwtvl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2qnpnarur.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gt2voxjguvy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2ralkyfjt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gt2gwahaovz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gt2odydieur.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2guwautdq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2aakyluos.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2mydexanm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2uhrdurbm.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2pvgrukkn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2flusxsst.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2rvgsyvko.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2hsqqdasl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2fsojokpe.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2pixewsfy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2rakeqrab.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2lhywelgc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2zdbdjmai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2hgululxm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2btarnxps.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gt2wssfaatu.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2dijspomp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gt2ejzfqxun.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2hdmrhilz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wynpntpe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2seaotogv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2vazmgmif.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpllcjwe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2eettqilq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vkyjqmwn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2zobwzcta.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pinjspwr.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gt2mjaygvgg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2bdfdegyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfppewgv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2chkugamj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2dizmggzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2eacoxslg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2mluobokf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2chcnmxpd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2cuchiopn.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2ozndgzvi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2wksqdcoo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gt2uessxntd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2xwukqpyt.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2brktcpzn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2voeooqsq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2wxtazvig.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gt2tjgffpkg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2wtzcwclo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2pxtnzziw.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2lvmwsukk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2nmkgevlk.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2owvzjeoe.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gt2yaalarcx.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2tgalvyto.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dlmgormr.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2kicfasae.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2brnynznx.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghsqfzcc.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2eosmezwg.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2oonkrrsn.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gt2vmdwsrsg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2edzynyof.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2okcaxnja.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2vkblghlu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2koxqumgc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdjzmjzz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2pspcvjaj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzprvuwz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2twohwvhw.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gt2kbhviavi.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2jaivobzu.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2dkhceaxl.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2gmkgujqz.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gt2fovcmlnv.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2ueetgisi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpmirasb.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2mjpuxqnb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2bvambqyv.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gt2sssgxpjk.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2erlsuixa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ltqduqzr.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2vajrhbeh.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2firbvvdk.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfuccubo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvlxfoqv.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2wcjfwcsa.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2xojsjrqc.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gt2idczvvmh.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2tioirksk.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2crywqdax.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2lopxijjk.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2xspzoidl.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2ycqqbdjb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2mkrpvzgq.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2frwteekj.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qfycmgnb.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnqhevgw.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khzpzcct.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2dhvrvinc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xlhizvtx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ezqqvkhg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2fzhejulx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gt2kkisayit.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2ptzihjal.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gt2xprjtvbb.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2ipzwtjai.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2kgrmqesj.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gt2nkqdenea.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swesumsm.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2uffczcrd.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhvwcxzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2nawntsrr.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2antnybry.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gt2wpsltzpm.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gt2esphbqlg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2yqotolug.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2bfrrblkb.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2njuofpbo.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2shvaoryq.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2pdmlhkmy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2cpkbgcjj.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gt2brnyibqp.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2ijdeadpy.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gt2pheuhuur.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2xbclyuqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2jhwgdmsc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gt2wnlwfkjo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aateekpe.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gt2thqliikj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gt2xvmujtfc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gt2sxpvenzh.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2efldkyob.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2mmczdbav.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2mnfhuzpp.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2pkxmdcxy.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2ylzfxecu.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2owaahczt.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2lgmtksne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvecurds.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2luqwirtv.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2dyqfzfjw.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gt2kijisklx.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2kpnpofib.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbthiofy.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2ljyjzklz.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2snblwwgk.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcyirlnb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2ymhdwumm.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btioxorm.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hkdgsjek.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2wxsglqpo.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2trehihqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwatlcoc.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2ojzadxyu.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2rypbvkxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2qqfqwtgt.html


<!-- 参考信息 -->