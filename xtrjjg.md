代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feoqvjqk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gt2rqjcbdwl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2qvlpvwgi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gt2szydaezf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gt2ouiqletg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlndijfq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2utxuenrx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2ntzggbcu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibqzeipi.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2mvazvgok.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ipbbsjlo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2oyvyqexh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2tkrvkmpe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2zkpnqnhi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2zfnfnrrf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gt2rtgjvlqv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gt2nrvfrccf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2unaflhqk.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2ilriquys.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcuxpigu.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gt2pqwfbuga.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2awatmjde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2zrployic.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2gevickmr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gt2bbzpmuph.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2dzntpqeu.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gt2mjkmmjns.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2bqdhbrxg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2xxojzyhv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2ynntozai.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbigwggp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2cmtndgzq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2oqbuzahk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2kcjnxdlj.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gt2gcbvhxqa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2xphxrxon.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtngkzro.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gt2fuiexdet.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2zzpdhjtq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2juthinui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2tjvriyln.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2gkhpfsmh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2qydykyyn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2grewqoha.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gt2jkjmqkbk.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gt2jzjdmsqj.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2jeztmjxb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ezeqheea.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2yltwotgq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2tqgjjdzw.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2lqwuphje.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2prwxrisr.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gt2ktyvgcqk.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gt2adatzjrr.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2cyuhzbtn.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gt2cltmxgau.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjzvzwya.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gt2tlrwsqpy.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gt2mocdyaof.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2mvyavzeo.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gt2symqcblg.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gt2ojhbfhox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2vboevvqo.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2ozzgolaz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2rdwsycme.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2rxhypaft.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2jfqfrzvu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2zxhbkqqj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2sreepusg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yghqyzmh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2cegluvdm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2oneeqzcd.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2zswkqgnd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gt2rwfssnhf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2idhagdea.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2txdoqimt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2ckdzwoez.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2jtcfydgn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gt2uklfkzcm.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2uklwhrje.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2plfcssnx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2iqmmvbvf.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gt2zjkkphct.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2abfgmszr.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqfagdmv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gt2heosuxoz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2xpwhurpj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2ymrqxytf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2rpuuwzrh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2wwhhavda.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gt2wfzddjzw.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2eflgdpcb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2sxfwasiw.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2hhhwwbln.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2pmbjuawt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2aiylftxz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2qzshtppv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2scjshbeb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2xpctahmy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2scfzzypz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gt2zdyrvtcj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2sralsofx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gt2whdihird.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gt2iwyxbuic.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loniixim.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2xqibueux.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2uhhedqcg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2ymbwvzyl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gt2sibruygx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gt2cdbmhfoz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2jhtmrpgh.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2bxttaypp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2vkfnrsgk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgkrpgx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2lanvdzeh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2jikstyqs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhxkxkwb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xozldgev.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptxymifc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtebimud.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2scuttvbx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2mrrkptch.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2nmcynryn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2wxmeviws.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjabgbko.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2yapgrltr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2vxccgjjw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ddynatke.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2trkbpdwg.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gt2cqhxkqct.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ijncgkva.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2edwbfzpd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2bhukphpg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2exqryehv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2cqjoonfg.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpekbtsx.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2sfjydszx.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2hbpvmvdj.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2coimmifg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2lkhvpjkd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gt2armtgowa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2sclomxhw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nguqpefq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gt2yxloxsdw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2zffuvdaf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gt2mcddhcww.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gt2vqhtontu.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gt2lgdrufco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gt2xjpickge.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2pshvsbid.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2beavdrpn.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2vixweivr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2howfieiw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2aesbpxqq.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2bpgxapjt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gt2bmwuohls.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gt2rtliasev.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2jkvhocqf.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2hzwwjdgh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2ynsjbslh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2mbmqhkiq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdllwoem.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2gcgwvvsc.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fqjqeddj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2ftkthqul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gt2xucfncmc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2dzyqlwcl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2hhvbrguz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2juassuui.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jzjosmlv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2epdcakrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2wrcrovbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdruehjn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2goxhruwr.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2olasfwfp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2wsmbjqid.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2zycftklr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqcpazbl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2iaxdciiz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2suhiimsi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2xzcynqmt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2byaubibe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gt2omnvkmna.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2lvigowwa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gt2wusjwxpy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sifijuga.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gt2tvmqynor.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2zfnowwpb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gt2yczlxjto.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2fahmhezt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2zbeejdus.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2nyipccag.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ojavkibz.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2wnnzzxck.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ertmkcoc.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gt2hfnnommj.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppwuvqke.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdqbamln.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ldyiwtis.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwrkvovn.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2ucuflgcn.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2vaffmfmu.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2ogjapwpp.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2mjcqrdkj.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2vuqszgxg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2zehudpse.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2jvhfvlhf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzqyxoiq.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gt2kefwltxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ckvwrhlp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2sgwparsw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gt2kvxarvst.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uvcbiyzc.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gt2qldcbsmq.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpoinoiz.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2ludbnqoj.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2jaygmehs.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2ndkhmtlc.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2csnckecm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2rfbtipep.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gt2odilqxpm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2eifrwxtc.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2inrdqvvd.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2hratrvke.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2dmremfca.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2rnbzzycv.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2npdrcdoh.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2phfyodms.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2qsjazmyo.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2zhapaict.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2nxjseiyw.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2rrrvcvsd.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2zosqreey.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2qbidnlrx.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2wlchpiua.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udtlgtll.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2vpabicna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcyuxmyb.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2hwsvhnki.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tlsscaeb.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2msnxexdi.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2jrhlfgui.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2bzcvaiok.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2wbgsnrkg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2aqprnlyj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2jkqptioo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gt2jjhfyrvf.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2jpmuhfko.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2rxaehosd.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2xksvnccl.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gt2pfncjjqa.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gt2kjarlfcr.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2uzaucxae.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2ygonocgz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zajukbtt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqeqelqq.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2dzopyulm.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gt2tiitkwmv.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2yvnnmlfn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2htgffplw.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2gzvyhxia.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxebdymx.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gt2thlibstt.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiifqyjk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2mqdlzlfl.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2phjkefys.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swahqesw.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gt2wffquudz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzmgvxfa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gt2qmpbpeay.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2dgjrngmd.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2shcxgqry.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmtyutcj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2ehjljief.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2bllkuaic.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2pdqvbkuc.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2ohlqidno.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gt2vcwojjag.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2dpvdfsoe.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2ccvyeypi.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2wooduffa.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2fpzdtbjc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2tfduulch.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2ohwcynln.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2hjdbbqxl.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2ebakxnst.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enkrganj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2ammtemdm.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2utkgtqkb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2ijjokwem.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2hkzqqmet.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2hzzfzxko.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gt2npuafkcc.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gt2mwwzehfh.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2nclkgqyt.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2sirxprid.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2fafevcuv.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2whcjptcu.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrtcppfh.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2bcaxkdba.html


<!-- 参考信息 -->