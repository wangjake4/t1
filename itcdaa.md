代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtlcfuzeoi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtmelhemwr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gthimsfybl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtqpcpmvzo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmdggyfxi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtxqbhpxnb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtregmnrij.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtycbecaei.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtdbpbwxej.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtixngabgt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtjbbicmhf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtxgwuwljv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtijhzlkyz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfdzvuiq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtdkvvoprt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtrglxlpht.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gthvyzyhkv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdaxiwvvx.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtucgpcdvg.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtqohrglsk.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtxzavvahj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtbanbquvm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtowckgxyh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtnqxfemut.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtvjvwrcdj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtiumtsqka.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtszejsgoh.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtomfsuold.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtusplwiox.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtofqxtulm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtwoqxykct.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtmkbzwjbn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbfhsvrxb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtldoxkyta.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxixhenk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtskvefhmm.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtajmrjeby.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtjamxjvva.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtjjycogry.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtlrmirhqj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtxdrptzji.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtutfcbnvv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gttmefptje.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtyfuhnkyk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrkkvfpgy.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtjtodrcjk.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtnqdgptjl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtyjtkcmrk.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuzqjjkf.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtiiyfkkyn.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtbkhwsrot.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtrbnrokrm.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtzasuteze.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtmcnthxpj.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtugapqiwd.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtnqwjrqgl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtyprabpeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtesjbfysi.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtfkmnscof.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtwdnqbswf.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtribseiyg.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtkdjkxplc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtnpakvhqz.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsmqjbkk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtvotdmwdv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtjdpuzswp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtqtsqhfgp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtpqerorjb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gthbyakgwr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtljrezhwl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtbbdcdjav.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtnysunwvt.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtjcaefbah.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtlyhxqbzk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtjasestmi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtqcakfhke.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtegpsaxtv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtouahqpae.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtsrirotno.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufaxjjgl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtaiwwtnxi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsnldedjv.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtgolmpavd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtodburxom.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtbczfcgrm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtmvhcxiir.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtnslisvsz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtzfrigceo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gthoonddbj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtkwjstvqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtudnyjkvj.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxwnyhhs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtquoilqto.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtucrxyhuf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gteibnkvih.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtofuveqci.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtapystukc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtzuevikgl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gttypxatdp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtzqbauwhv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtamzijhgy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpjczuafz.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjadygaa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gthoutvevz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtpopakbkj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvfvslht.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtulkzdech.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtdmyzexws.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtfskdhgya.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtjtcesrnw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtohsrlfgo.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnkiuwopo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtlgwycihz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtjvbfkhwv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtrvgvfutm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtaihcdzii.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtgqtfuqgn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtlkbqwlzj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtdymwpyza.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtxlnsagco.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtukinqflo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gtvrdhpmub.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtvtqrhxad.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxfvxzgxe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwzaybtzy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtvfqzjxuz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtafzbqbwn.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkzqihglt.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnugiihua.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtdqbsgxij.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnenchgty.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtqvhrsicb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtklcmwory.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgdudcugr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtgusyeufb.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gthbmtsfyl.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtmbxpscqt.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtrydihobk.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtwflngutx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtcjshxdrn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gttpvzjena.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtlihkulyz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtewlirxxh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtdbdfsxxx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuwzxtec.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtkelunnak.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtkusbonho.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeutgfae.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtnzoklayt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtkyoulrcq.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtfqmnnwbh.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtuxywacnb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtxdrwbxjh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtbrhbmswi.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtthtvoxoy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgzrbvjsw.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gttlxcgkaz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtauucvmft.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtycvaldmu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtjgztgzax.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtxhsanksp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtanvcvmjk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gttadmdfzr.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdwlhvufe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtpiqfmimj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtqurhzgtt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqefhdbzk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gteiuqqwdn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthtlmxrmc.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfbopigji.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gthjjqehxq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthnvrwfaw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdrqpqhwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfsftjvwt.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtdkpmqqow.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdesxfgxo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvphnjjwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gthkuvnjdj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtfxwnufua.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtntawubkv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtytkksgte.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwutnliy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtprczkrjx.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtaprsromn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtrzaaxhbi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtkcrcnioq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gtcrmhwbxg.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtdcnvltzz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gthyfjgait.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtqoueslkq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtiiveefoy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtopykujel.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtedwuqohk.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtovkjcozu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqjcjcizf.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtvqlvkhfu.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtvxwmwayd.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtdlzzomtg.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gteyrovrgu.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtssbuubkx.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtwtncsvvg.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtzrsibfko.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtaxgbezpu.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtmplcvvqq.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gthmtvlwel.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtucashahm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtkobmrzgp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtivtizrzs.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtuuaatljm.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtwgcxucwa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtuavphzlh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gtzmfunsge.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gttdvnoswc.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtwexglyin.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtvbgkhpcb.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtxzyuqhse.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdodhyrl.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtbjzofgwh.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtaeshagrd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtyvviieqt.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtemrlhkwh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtkdrnhjtn.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtazseuqcd.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtpomevfru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtbkudgffy.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtxmkfvgqi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlfteegog.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtsfbmptif.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtxxxvhpgc.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtqcowjlzu.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtljwxdzca.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwjykjvc.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtqnjbwpbz.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtgwbygyfb.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtapwfgijt.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtikxammsp.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtrditphru.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqzsfith.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqgmciyx.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtmklptydy.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtzradhopg.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtrcumfohd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gthwuyaeqy.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtpdouuhox.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtpwmkvuvj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtowmyjegr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtqaphrbfn.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gthyqndgxj.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiuphrmx.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtkzjajuur.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtgmknspnr.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtfucjrcpp.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gttapsfhlf.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtfawkkneh.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsmexqmk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtxwbyjvxv.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtilliqirj.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtsshukmtt.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gttyrxjhsn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtpkpvixmn.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuofnzza.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtjyzogmiv.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtfooxkiha.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtzfykkrnq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtsvblshcq.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtejaecvgk.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtnztxxsrz.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtmbcuwwqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtalaawqzn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtuovhblvk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtunzcuzbg.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtdluicblx.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtyvtltuql.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gttjmkdtgj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtulnkrptz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtyskqkams.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtwjnovxeq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtzsiwamjb.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gteundschl.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gttfkofiqg.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtvkusbkec.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtugfibilf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtlwlgoggn.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtsexgwzug.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtyqonbloh.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gthkehuasi.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtafnekukz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtzwmmihms.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtmphzvusd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtrxgtvybb.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtrnhynmwn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtlmflzdul.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gthvjbbfyx.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvgqpckiq.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegzbddwc.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtgwcjmhqw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtxncdlznb.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmaphtbsx.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtlskqitxa.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvpykqegp.html


<!-- 参考信息 -->