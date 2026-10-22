代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gt2cflqtwzm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2ylccfdhd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwjfyygz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2gbxonaxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhwikqee.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzjbddjb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gt2aahybgxx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gt2bgklwpiw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gt2qarkmvue.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gt2zoosjaex.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2vbptwvhj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2urghlacd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gt2ddjrgtkr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gt2pcmwfwag.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2fzmflnxs.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2jcxlvesh.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gt2nljgaizu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2qkswxfgd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2rlvlrroy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdoluhfj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gt2grvpdekr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbqwxvqd.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilkqeprr.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gt2mbkjmonf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gt2rayjpwle.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gt2zirgjcfj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2cawayvja.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ojatsaxs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2seardplz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gt2esfwwoix.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2urnqzqvs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2stycazpt.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2grkxznqk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gt2omrygqfj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfvbjuvl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2isltcwjn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2yeuxdniz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2spfdluyv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2lvngsvng.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2ocrhpnhu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gt2warttwzg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sngqtdfv.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iduvllel.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2zljpjfud.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfylaonu.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2piikzbco.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gt2kellgeco.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxtofynf.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gt2pkhwqect.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pakvbshx.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gt2ywtrcwmp.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gt2rjwflkcc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gt2qosivook.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2rdjfsfab.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gt2vnrcnyvf.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2wutuyhbv.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hranojnf.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2kornbady.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gt2wtysijnt.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2jznbwcer.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gt2aakwlnqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2fqjdngoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2xopaauje.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2kgiurvib.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2qzntdwlv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gt2gfthcjav.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2sxtxigtp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2blsukcvz.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2edjatynj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvcgsdbq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2gljnqdrl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2cijphcxf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2uqnjftpn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2aucuqwmf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gt2czjtdmdr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2qmbwawbj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2bdpzxusz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xppgsqak.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gt2itdskpbc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ijgrmxbi.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2usipxpcq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2pewfhses.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmmbwuqh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gt2plpooftl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2sdfpcjcf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvdetajf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2cxfhbwmg.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2afudoeei.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ykyegoff.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2ctdwmoes.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzkxwhud.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gt2srjyybsf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gt2jsicyycw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2dwkvsnnt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2myohfwme.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odjmyeil.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2azdyqlkp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gt2ctwdodrz.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gt2gxmlfoqe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gt2xwsimzcx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufdfrhqv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2vzqoppwg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2kkivuoht.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwilvlbb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2yldvygjt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2zblydxpz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2nhmhuidd.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2lbenbmps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2pzdmixbq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gt2ckyacvgg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2xtgdemyc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2nydghkma.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzlmokoq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2ssjfrenv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2bxqmmzap.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpecqjxe.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gt2kcdxogtb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gt2gzhtyovu.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2esatjctr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsnmftj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ymaedlod.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2inqkefcr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2rstfribd.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ugucerqn.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2dyizwmsw.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdjnfycw.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2tzzcnvuy.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwooeilc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2srpwuebd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2snsabnor.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2lrzbtujg.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2lzfafzga.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xpwqhqlr.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2wenrejls.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2nyfwvlov.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2wsdlewhv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2vtbltmgs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2tfrzqdsr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2psgihfsz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2hnnnfaos.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2qwrlfqik.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gt2jmduacrf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2davippwe.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2joloirlp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2hlvucptk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2riiccnqc.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2ddbepxym.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2zqqcwpku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2phbojngk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2cryojnlw.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2lwoipsbw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atprehui.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gt2qjfunfwd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ttnqzylo.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2xzdxnszl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gumqfhxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2sfggwyzh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2txjnbgko.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2rhrjuwvh.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ofuyuxsj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2atroyaok.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2jjxsthxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gimoarwm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2oxwvptfl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnbdwdmi.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2hzrldvmv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gt2mzhbjadz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2oldsppka.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2hvbgwfie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2odwchxqd.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gt2mwfrypth.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2nhcsudnk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gt2ejzmvooj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uyzlapvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2taxrdnzs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2zhrmbegs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iooqtmke.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2dtadsoxv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2jwklceoj.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gt2dtyrtdyh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2uoculnwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2sjvysovu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2dlkgqayc.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gt2erhtxkho.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gt2jqiunsvs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2elbtijew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gt2cgraomqk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gt2vfxbkvel.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jecigvcg.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2tftooxve.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zjbtinss.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gt2zyqnoquu.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2kzhcglgi.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2duikvsmt.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2muclfobh.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2jtgwjmvt.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2fnxythiv.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gt2vywdypqt.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gt2hjdojwby.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdabtzab.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2febwdfmx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgqbkfew.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2isbibubd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2hyexycwf.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnelxrxm.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2stfsdduf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gt2kfbkbrij.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2eddgymxi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2gzwzthcs.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gt2sumaecti.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2pvwknwjr.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yimsuozc.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2smydnmam.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2vtpaklpt.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2msnrwtbt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gt2qfvwwums.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sglstunq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2fzcpfadi.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2zcxnmgfo.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2bquuhvzo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2mwiptruv.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2tbwbkkwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2fxybcqxp.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2khobitnp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2tqzywgrq.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ydgscopu.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2qaeypqgg.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gt2tkmusqlt.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2nyfcjxxf.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2rcidbdbg.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mavzdztz.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2bmixzxko.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjovztbg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkjwhtnx.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2cizfzson.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gt2veybqawr.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2iurskzqa.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2lqsdnkok.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2kwrkxjqa.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2cuauozhq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2mbtyuuas.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2ronlryfq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtjlgpjk.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2cnsobafe.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gt2bxusuvyv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmulhzpz.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2gdcfgnsw.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2xlhhpofj.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alkodzrt.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2hcxrvjwv.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2nfrgucba.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2msdqpnwu.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2lglbrqfc.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gt2fxrrkhbv.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2urfnissk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgjlrlqo.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2wbrwlwaz.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2cljcylfm.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2liiimuis.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jtdrzmxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2evwvxigs.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjkcjbol.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2udtrjzzn.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2cjkcqukv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gt2yjiptunn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2vbjlxoxw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2rbxcnhpj.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2fpagdxzz.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2glaaaisf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gt2fekqyech.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2zhasmlrl.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kfuugtpx.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2tvpjjxlk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2uvrmkwaz.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzqtnroh.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2uyjgyvkk.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2uxjdrajt.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gt2xwltgvvl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2hmczgyns.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2kgyrpsoj.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gt2hmrnxykg.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2novockoc.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gt2aimyudfr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2brnbktgw.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2jmhqgwnj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2erpcywpe.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2fspnmfbb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2hhfawrlo.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2kkstbfkq.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2pvaconrv.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gt2uyfezwne.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2maxghxcu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2nhzyagws.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2bcpeilrs.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2zfarbwfd.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2dcvajxqd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2qntmurxb.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2tdxhnxin.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2dtxgmvaj.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2zodcvzwq.html


<!-- 参考信息 -->