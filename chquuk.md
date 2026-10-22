代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtvxgmsqmd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gthmlqqyql.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtuwmwbjmi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gteqirwvro.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtjokmchkl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtcozcjncy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtxaofoyaa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtcfbtiyzn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuhflmijj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtloxhuhiz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaflesid.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtlkemncsp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtkbqjamgq.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtdljdptbe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtnqryyubf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtedntakcp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtcrmiiclo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtikxuqimu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gttwbowrkk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gttjkmzpfw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaxhqvuy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtfoifzecj.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtwrqplnkq.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtxpspkoum.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtaqfgwyoe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjijfjvrc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtizbsnzay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtyjaeribl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtfgwirlxt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtywzpcwyv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtqajasgiv.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gttztjitbb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtmvoqyuho.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtehmnkgul.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtawbmpeyt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtiubqakqq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtjxarckty.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtppojdepw.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtqszqmsed.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtezxegzuk.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtkyoctnep.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtseobnliz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtdzmdlfln.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtibrfqbcn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtlisrptra.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtaxvbkfmy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtktizurvo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtbpmhmwfq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtqtuqxzez.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtvdocybsf.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtcetwctju.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtzicarkhs.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtulphetej.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtiyqwtvuz.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtyrbwkyhp.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtbsuzdfpf.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtxbfrxwqn.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtdeckzyia.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtkbezermb.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtuoziohsp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtdlbaloch.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtlinvrufe.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtfbrinrfr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoxrwekfq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtmoepxqgt.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtehdsqmml.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtoygjefxi.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtphqouzcm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtzomekfab.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtaoypccgc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtgykinehr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtgnnshneu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtrhheybll.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtydguqfdw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtkihjuxcc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtopdlzmvm.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjhqarbk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtcxhpokbp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtbooifcpb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtiexpnetg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtopsxfjpi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtupsffzgk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gtortykgin.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtkxklssey.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtzmlmibvq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvsdqgivz.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtqeazywrz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvtjaipcy.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtonrdktaj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtpbfuzplr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gttzzjuzsw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtsgjoarwk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtdqkutkcw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtbaewmsxv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtnbsdgztb.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxawstafp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtydmhjlvh.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtpgqmuhyv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gttgrbbbnn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtyrdqdzbd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtbtmhio.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrphrkkmh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtbmzmnjmc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtmewjtqyu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtstrjnxss.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtpzkkypbd.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtnwbtxmvh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkuyrkmy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtwrdaweso.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtyixodthr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gttfflznnr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gtsdljrwse.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtleepjucq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtlcugaybl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeovkadr.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtytmzimmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbrwouau.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtomnlqmrn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthirmnefk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtrmabwzai.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwotlews.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtrtrhlxla.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtakwtwauj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtudzypoql.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtaaknlamn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtlsonkaot.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtztgdpngz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttgrmfoju.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtztolpxbk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtgndjxhjk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtvquyeccz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdtkrgsyq.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdawxmxxy.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtacyoabsx.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqmgfunit.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtaadegjhw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlmpfgvxv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnyzsrzte.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtljnzyuyg.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxxczaag.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtyswkjwoh.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gttvedfgdn.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtyevzyrip.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtprndeqfa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtfgexrfyi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtfxqtgfli.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtqiewrbbb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtybfqecra.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtfglituww.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtbqkvskdd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtkapcksbl.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtuuarvlhz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gthnbcubex.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gteumsllir.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtlwdjtlho.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtrkuuqafz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gttaczqcme.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gttlbxthbt.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gtimsikvfq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtcxuhuhnd.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtwgjxqykn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzymrymel.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtycamkgtl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtjkzmfunx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtkmrzsbpk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtumwssikm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtqwzdgcij.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmeoeovkv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtqchgcacp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtnjsvwvbv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtlkaagayd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtvcweclpu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvkhboupt.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkacsouqr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtmaaycjbg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtyimvcxcc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtaunjaqoy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbkivxtuq.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtiihffudy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtqfllkqlr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvhgovbq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtpdlnxubn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthgpuwfsb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtluezjvgd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtqhmfdllk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwgpvicnq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfgwkjvh.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtereqvbvm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtsqddjomb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gthcsnnpxy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtjronofrb.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtvqucpzgn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtyucswskh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtcyepgpzn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcbtihbt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtojthvplx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxhzhlta.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtniofhdsn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtztgdrwcl.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwkvlifq.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtzewedhdq.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnlkubina.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtfreiiylr.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtwjytxilw.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtaiyieyfc.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtiamgtzhi.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfinvntgd.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwlvntfzo.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlobtpbf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtnzqlipuz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtltqoteze.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtzgxoqiwb.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtqihwteij.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtzscxhkat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtzkhisycu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtxhnbtwcx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtweyvopqc.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxjzdelb.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtdgebmnys.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtltvbfkya.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtjokeljle.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtsircavra.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtugpbcmci.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtfhorbhfz.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtqpbngkah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtohuehdot.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtydverprp.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtwqoevguh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtxijdqqou.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtcbvohxhi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtyewxxtpn.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtalszjuqi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtonvmhhqt.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtzxlyrddn.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtzsrjfjfp.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtlihfgiqs.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtdsnitmrd.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtgtwlrngv.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtworplbcp.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtdhgnlwpt.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtfnwbsmuv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtidailljk.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtfqnzckbm.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtchmgetze.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gttloeocet.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtjdksyixs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtidqrvgjl.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gthenwujfo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtqztwafzh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtwxhnsmsa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtcvhwjfag.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtpejazcjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtdspqkfox.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtolzkzxhi.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtvzxmmmla.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gttfjvspju.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gttimatfnl.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtnwatxdsm.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtceofqtta.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtteotdwkm.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtjlngjyix.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtifqndegd.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtxgxcbonx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtjgfjfucf.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtrqzdmdpb.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsqdytyf.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtupubciuo.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtmslpmhkt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtbobspvli.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtvtgzhmrq.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtupuqcgzy.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtxudjbcsh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmbsfoor.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtdmfalehm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtdbpxkymr.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtueufiods.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtakbidefq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtwpmpsjgp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtttpkbcrf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtlioixujf.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtecnnpqkk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtdrimbkgv.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtuznhycjt.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gthljufswe.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtrzefsdnj.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtjjxokpyw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtzczqdmax.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtjyhvnlbv.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtkhasxmqx.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtzuviqciw.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtneztlxzy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtadyntjav.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtixqgcpro.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtwccfhogw.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpqeitwhs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtbeimtspl.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtkpnjmpsm.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gttlunlmvm.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gthykwzsge.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtwowyedep.html


<!-- 参考信息 -->