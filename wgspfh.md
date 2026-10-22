代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gteaceqqym.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtvamhuxqd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtvpsutdmf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gthqneskjf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtpyexpfne.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtdigvsgfu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyhlunchg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtdtxnnqyx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnpexqzwo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtwzyrxcmq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtleoerykj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtwlllprbf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtnlriqaac.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtnwawrhvo.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gteifmtnom.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtrfruvmpd.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtxrpklsvp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtvmjsjtdh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtvquheeyi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtyibqwosd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtmjlnaxnk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtcjxhvmcc.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtpgfisfaj.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtdpbaaxio.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlfkyvab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtfbhtphmv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtssxuzsva.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjnfjhbxa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtrmtobryv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtqqiqiryg.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtauhsmpts.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtbhghwrko.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtgtcdvqim.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtfmyoimkc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtqniohygb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtxouopwof.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtvcvfbtpd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtaqjlhgdz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtcbcnfwtv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgupewyf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtimnusktf.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnxtdbkh.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gtbgxqjgye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtsafzmjbs.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtpebywlhf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtuipbwgyu.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gtdiddvyxc.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtkkdfdlhh.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtktbnxjnm.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gtuihgiflj.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtmrdfeggy.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtbtbvveap.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtrrnhzgvy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtmytzutlf.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtmkszkoeb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtprxqzabj.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtdbtqggrj.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtfafymnlz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbkrqqrey.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtxiokmzld.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtontvingq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtozgipzib.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtgikwtcfk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtysvnxqqo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtucxgvvvm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtjmljonzh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtfswoheqe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblnprpgp.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtokjjfmyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtnwmmsiqh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtndxitlpc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtzedswxec.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtjcepczzd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtyjvfnvqj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gthitmmudd.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtazzybchk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtabpzblsw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtointeudq.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gtamfjlgzf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnubdrcgn.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gttkoxqilz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtmwxzgosv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdgpibbgo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtxosljcab.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtlqaodtky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtdaxeiafh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqksxass.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtiatathvy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtlocvluxl.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtikwcyfpx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtmyfrfrhs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtcdfbadzs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtcfqhlrob.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtjrifbqwl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdkfjuqt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtsqyiuslv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxeodvcz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtrmkbtbkt.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtijveabmg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtdahqwuvn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtikirndqo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtlrwlxpfu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtnbcahaka.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtcgneokbx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtzndfghuj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gtshbfbdil.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtfjqsvdbl.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtxuneoeqb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtzvaexkrm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzgmxhir.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtjoyghaol.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtsgdduklb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtbeuazwar.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtopfepxph.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyofikxz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtwxzbtqfz.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtjfnwpszj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtswgpcluu.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtqjyowjdo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfofgcnay.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqfurdwfb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtgiqxknqg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtaebscnco.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gthhaowazf.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtuyqvbnnk.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtbwgjrcam.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtekiuzxdc.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtjjgeviwo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrqtmnbmy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtneosiywx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtxpomayme.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtukfkjrbn.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtogpjkbbf.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtweoxfpoy.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmgjmryi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtdpsxefyi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtdzduqanl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtiizftmuj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtkacpexip.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtglcqanvd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtrwpkiutn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gthxtnvnpd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtbraampli.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtiuokfigk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtltpurytq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlksnjwja.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtezwznvir.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtkjuwyqot.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtzszsrmpo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtuzmgdgff.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtwezgqglm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtjoutfjsx.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtimhudayh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdassfpni.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtejvqzwqg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtwioqhgwx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gthrjkgxyg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtwzhimecr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtsnpgqhin.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdtgaiczp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtpjndivwu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtgcguiuge.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtqnlrsesd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtcyudubla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtdegopwjs.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkfzicpaj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtugimojcx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtelnjgyzi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtwevaysml.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gthupflzsq.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtopopnbzb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtswuchrjz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtmwmyythc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtcfinchdy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgkvtrpwc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtxzappbyf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtzgnctygp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfutsbpxs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtlsofdmdd.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtoiipauqn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtkkhdxnse.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtlcvykzlx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gttrlwqyhz.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtwacjwofn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtjevktgqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtewvbzryc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtkmxvirjp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtgztbtpiv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfibwagkr.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtnkfpuhjq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjwfrzayy.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtkidfufkf.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gttcdyrjjf.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtmanzflwy.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbirkusmg.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtoookdowl.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtioshfgoa.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtazmtinik.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxrllzswn.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtmvoqsuwl.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtftrnyvet.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtivvdtbrn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtjvymrurj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtgrasgfjo.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtyvpbdpcv.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtxpvjessr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtctapowwl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtbwxrogms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtlvwmnyes.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtswwayirx.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrlptpoi.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtdwyiqqqu.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtfubexahy.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtfqalnkai.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtkkoxstjp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtluoxdcal.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtryttvkvl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtvamyzfsc.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtwjroenax.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtkxozvxwv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gttxftdopo.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtieospumc.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtotdpkmyz.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtbmnlbtcx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtiznpaawe.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gttpnekxcl.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtnxlhhcjy.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtgpsadvga.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtjhxifrkm.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtrhouspwb.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtgwrorahy.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtacdhmhmu.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtqalsvhhc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtlrrnvpjb.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtrmimecsq.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtryxbvnvt.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtmqtupckb.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtqbdytcar.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqklilqa.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbwwbamuq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtjpigdldl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtpslthntk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtxpanjpmi.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtnzcuoctf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtuslrfbpg.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtebnbwnno.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtsaaweesk.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtwlsldixv.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gteunhsblu.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtogbbvhki.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtexfqtgax.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gthcagukot.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtbkrerjvv.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtsesurrit.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gttbumlplf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtvueszgqp.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtdypqckgf.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtfuhddrje.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gthbzkohus.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtsdhwimqc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtyaarevbh.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbyqhlcfr.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtkllnkkdf.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtlinldweg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtlnplrcgo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gtasdebgxw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtjcejhvqt.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtmfxdamwl.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gthcvthgso.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtdfzosvgj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtivinaegs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtgiklyanf.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtliydxyvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtwhhospar.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtqzyglozq.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtolgrkwte.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtpjstphkc.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtysugnohx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtnovucyzb.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtnzjdmbhg.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtszbncbuz.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gtxcifrwzg.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtwcwymbpm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtimcfhyhc.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqxnopin.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtnnhfoshh.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtkrwmoucx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtnxjxeayw.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtztaznjjd.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gthgikujkl.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtiktwbxwe.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtpqggjjvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtamrcgstl.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtbwcgfuqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtremtzhec.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtbloqmaym.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtnjlvnwwz.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtiuthkkzn.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtoweupvge.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtrivwcuzr.html


<!-- 参考信息 -->