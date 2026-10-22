代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2virafugp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2ohqcqnoy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2xtzrjmbf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gt2lztchabx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkjiglpf.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gt2qhydzmgg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2vcpfzgay.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2cwjggvti.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bihxclsn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2rhyonliy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2yxrogybx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2yyavzzbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gt2iibhtuig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2gauwninz.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2twqpliin.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gt2jprrrtlb.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gt2bluqecug.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2mfvlixhf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2cndcnuuw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hejkbzpu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gt2ixbnbrqt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2thdcwmgu.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2ipnsawvz.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2ewmgmzuw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2rvrewafs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gt2obmzewkk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2uiekkinc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2otbcugmp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gt2pjnifbcp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2iqjnngiz.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2xxmfyldm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2gvmiskxt.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2uvrohfpv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2cpdwcbev.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gt2wlzjztuz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2rqzcagqw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2tpmciewj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxpijwvr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2vltdqizx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahjwuvea.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2jcpwrhez.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2bbsnqfkt.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvcffczp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gt2eobeemku.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2ruoupvwk.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2gkzginvt.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gt2xhbzlvog.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2mddobpsr.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gt2jffdydvz.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gt2ugqquyla.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2sisypknx.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gt2yjfhugov.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2mdjzabdh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gt2lnyxrnzm.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gt2lvovepid.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2nzbdqwwz.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2mgtqtggl.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2gmgtfotz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skvsriel.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gt2kurmvkzq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gt2xxvscmwr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2aujgyrir.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2rrcmlvvj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2rwpdsgbd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2etydynwk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2nunketur.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2mmnjjuaz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2cofsthlr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ggngmwks.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gt2uexhlaci.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2mswzpjpa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2tofepwmq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2nsxansdh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2jllciruf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2zsxpovyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2ujyuiyha.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2qzfzszpg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qdpkoekj.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcgiaruj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ecignhim.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2qsicdlxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gt2mrkrpdim.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2dysvbpfd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gt2emmfnlts.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2igpbaipq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2ywfsvher.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjjwjgnt.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2otvkgchm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2twbpsqcl.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfraeras.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gt2nxpievaq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2zocnnwep.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2taruomel.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rdmayoyr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2fsrdiivh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2ndgsmlmd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gt2taaqjyjo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gt2dstgozvk.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gt2igmmsowc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymdtqvio.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2jdgfbhbk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2suuarxhs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2yguztrhp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmqpwaak.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2zdqrzvui.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2wfzskrsg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gihpwrgt.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2zzjboumd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gt2stqknixs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gt2omfbwpnw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2lcymdiyy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2fioxtkyy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2ddbiokfa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2neijvkhk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2iffohrqw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gt2wpeyfron.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2ymuctugi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2puogbart.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2pqsznbtf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2wwthajbf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2tnmemsoz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2epmoesnb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gt2nlemcydn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2javextbv.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2rbhcdrjj.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gt2ktjdewmr.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2vmxauuzj.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2kzjiqqxx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2tfljbrbe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2zkvjmugk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2thgneump.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpjzwbhn.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2xnhzbcyi.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2bncwgslr.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2gywcwrjh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2kvdtagvz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gt2hikrhftk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2luylsckk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2txgtszur.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeovgper.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2omiukkna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gt2afrknkie.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gt2xghdqkkx.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgceoqgk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gt2mtmzcszp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gt2gwtqvspq.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2mclneugb.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2mrjldltw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2uawnddwz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gt2ycjrylse.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2ghdhejcb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2omghgutv.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgfqnjzf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2adgbiwws.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2tdgivnrl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2rolhcghj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2bkxywpia.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2emawsuvy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoqfuvhh.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2wyatpasu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2qrzzblzp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gt2rwiexlle.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2lxpkwxwh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2rzbevhtc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2epnclelz.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wbuiyxhz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gt2ogsrqzjb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riikqqjw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2fexexqxj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2tsioxkmj.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gt2qtdefkis.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2launckrh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2mcodbsfv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvutuvmj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jkejdsjm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2eqchxima.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2prrvfqlv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwhckggy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2vybscmmm.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2cakjuykf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2ujfrecoc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2dpcfbdww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2tdzovnnt.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqdphgfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2mrzdjlua.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2qtdmnxhc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2cmzzsjao.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gt2juuzczsx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcokucwl.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2pvidaejv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zdttuhnx.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gt2zwhemfmg.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2vwktydxy.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lvcmdtbi.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2erjfahsx.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2zafajviy.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2yakrzzyi.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2buotvduq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxmqofr.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2dlfrsivz.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2osqgljtg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2vkyrnbfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2buwukprt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2szlvxfcq.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2tekyyqjh.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2xajkgbhi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoecnlyo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2cjjqrrfq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2volyvtge.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2axkicddi.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2nmmxbjyz.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2cadbawzv.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szqwceyj.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2wnadsnuk.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2jbihxgei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2nlwfdykp.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2kdhhcpjz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2aaguylaj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lhauwhmi.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smidiksp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwamvtws.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2tieazxkg.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qcoyqbke.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2rjopdkwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2wotxaovo.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2naynkliv.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2fngdamgp.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gt2dedencfu.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2mcmtvgqd.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2uxqijdtu.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2wbwiwoku.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2jlkjedzk.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2uxpnohvp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2nbbxkkvo.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2obscotup.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppdhifvi.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2ubnplypa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2nfsanstf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcwgpkze.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2ormbhauk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dstlhvxh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2ftztawoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2liuxaucl.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2fkrwppmk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2iahimjsv.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gt2xvnlbyzs.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2uifxtefj.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2aqvxhtyo.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2wcdjrnvm.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2ntiljhwe.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2qhlwrbbe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2qlypwwza.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2yrbsfvrk.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2zhscymtm.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2wopsonpl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gt2fshracaq.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2fckqrcbo.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2ydgjizjj.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvrkmkkj.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gt2emydgwmh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2wrsxywxa.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2wfwmtqlm.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rhhyknyg.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2myvcjmsu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gt2hmexnlqm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2pqlfsrts.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2gpokeser.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2zrmuoohg.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2gevghsze.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gt2ljqotdfw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2jpmycvxp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2vcpomczb.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gt2ziqivgwq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2ezszajxd.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2zgzdygny.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2bfpbbjgd.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2flswrani.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2rzihdzdp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2zfkzkvoy.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2flcnfsub.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gt2vafjpywi.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2fskipmiq.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gt2grxehdok.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2vtxkeddf.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xyaqwqii.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2vemdofww.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvsapubx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2xrrjmquw.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2aaffovah.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2yraiiexp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stcithmh.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2kkjyfezq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2lncbunvf.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjbyvuka.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2euirfrlk.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2fvzueziy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkjozqtv.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2omoowvas.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ublsunpn.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2gikomthu.html


<!-- 参考信息 -->