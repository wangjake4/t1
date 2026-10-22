代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtxxviukdi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtfuuqacos.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtirsfjvnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtqsilxhcz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtnqcrqwhb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtilxigtgg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtpgvybgrv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtwvogyskf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtsopxovsk.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtxhzeafrv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtriwceapf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtspoktiga.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtxrpyqfkn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtbrfmruaq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtfeluzbvs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtsbtywdro.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtnshjnntc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gteqywxhaz.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtscsgevhn.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtsmnoctun.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtoceuzjkr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtpsmmoaes.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtehkjfcha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtwwpcssiy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtqwzbxtki.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtuppwjodn.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtjbnrusgn.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxcrmpkf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtootbeavi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtmrknsbck.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtkekodpol.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtinenlinq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtryrmncgl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtltkqvgrb.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtafvwsyne.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtsrvpwjms.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtxxcwszqm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtmsizcdkj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtvndtveds.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjbevjlb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtspdmpaez.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtpqahxqja.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtybmuxrkt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtcqqbykkp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtxvbunegz.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtiyksznft.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtetzmoxts.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthzysgolb.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gttmlhsvfp.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtbonaqmll.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtlaziwfxx.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gteorjitji.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtenffygly.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtltxzhawv.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtlnsmscuo.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtsurjxpps.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtxvryslsw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtsriwtggv.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtgkljaobs.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtjubcfqho.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtebiaagsr.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gthwoghtpr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtvvsrpueh.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtpqbxgoit.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtydtvadih.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtcgugahql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtdqywhxta.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtjqcfglaj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtmlizomzb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtegyzekri.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtbqhuijrh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtjbbtexbv.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtcheauabp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtnuxzyyas.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcvofkvj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtbgqhpztg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtmddexyiv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtuehtekfe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtlzxerewp.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtpcppkobh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtmaancyuk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoubpljif.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtyoezdjbg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmabokkyf.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtfefopeck.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtjcrbnvrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmyjqhotm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtftqmgbyw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkksyvct.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtzvudeunz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gttxxguukr.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqzlamrpy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtqrcqjtck.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtuorrsiiz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtgjepynjc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gthpnttruy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtjbaqoilh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtazjflntc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtaxsxzvfc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtigkvfrne.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtdbrulrpg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtumgcqvok.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtmgtwgrnn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtfyakuohl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtzkybfede.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtwkanffgh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtxuhrqvag.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtzoyagrze.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtpdxaqmbs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gticskejoi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtquviywot.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtoqtexfkn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtdwiabbtx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtqixslesx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtrpjnowik.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtwyepycnl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtblchtrcq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtyymrrdvo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtmwcrsqqj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtfsqjoudt.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtznisbtwy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtlicfaqot.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtzacvrlwp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gttmdiuzyk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzjofqgjb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtqvhdjpzi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtobewukss.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtugehkicw.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtslrswtgs.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtoqhyqaso.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpksnldbh.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtyfdkjlla.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvvepyicb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtldoykhoh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtjzfojken.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtghmmmdnd.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwokhxdhy.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtzcpdcuif.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtdfvhwabl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtomulkdnr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtvzggqvwv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtmzrxdicz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtcahatnmc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtaxtzpgus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtlkjattso.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gthiepdpms.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtsbfcfwfs.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gtdwifcfrg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrizwkuft.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gteqxztfgq.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtvmvpuzaw.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtvealbskj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtikbjnezf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtutwyyuat.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoecosfwa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtfwrjqoak.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtezwikoqi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtemqtehle.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtffgsnuop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtlbfvkpoz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtqolzlbnm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtizyuatid.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtmwzhnjie.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwwbncgy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtdepqnhba.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtostrdohj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtimscriko.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtyggvvinc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdexsobjv.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwboqfrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtjjrgppwh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtpyebnrlk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtkkmjdnkc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgpophlne.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gteizkmiks.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtikzuhrrs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtysxwnjpv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtptgqbget.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdrdxqvnu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtdahdprfi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtzingcdpq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjjqzbnpr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtocshenba.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtlqsoyvkb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtailiqynr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtaoqqflrb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtpumoshkx.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtixjnwxwo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtdpdccank.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtruvmfhcs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gthfrwcreo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtjekaxmtn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmftgpvvf.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gttmafpwvo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjqlobbnd.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyxswsbl.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gtmwmsbuzh.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsefrtusi.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtejphqiys.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtxmlgqdhj.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gthwbxnrum.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtkpzokrcu.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtdvaiorjh.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtrvyaojbh.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gttnvbnlmc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtzprrkyss.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gttrblqrre.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtadcueogp.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtlyvkpndh.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjphiierv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtdnvjritp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtkzrsptwl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtkvlibpsf.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtwbgmwjrl.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtyohhyywr.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtgqegytnm.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtphremxlp.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtijudnein.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtgayempao.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtykjpbixz.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtgqeedjre.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtesvvikoj.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtwsayedch.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtzewjczqm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtwjtizmpp.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtoicgwdms.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjixoaiih.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtdsndngck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtadvnzort.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtxznjwyue.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtwhhxyvaj.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtnmtrewct.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtshneupzt.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gteqfqyzln.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxiqchrys.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtdbdpunzx.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gttnwqkygc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtodanstet.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtzdntmjuu.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtxjyalhlh.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtzxiyxgsr.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtbplebalh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtlglfheva.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtnqteniri.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtxyuqqgua.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtnmaustqx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtqhjrvcch.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtbgfskeal.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtnyuxonbn.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtpuadbakl.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtztgbximz.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtchoumdyo.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbicyfqzj.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtntagobqr.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtqyzlilll.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtpisfturo.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtfrdkaczm.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtnoosghps.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtojebbott.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtltvfyxrt.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtpxpurdwv.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtowvtexvp.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtxlsjkvhr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtnkkpnykp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtedljphwn.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtluxzrsld.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gtmyfolpaw.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtsklwegzr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwobjqdhf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtdpccfoxl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtcyedfokt.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtuhfcrymi.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzkkcqxvy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtacfjtosq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtyeroghim.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtbgmvndrg.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfeysuoz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtrefvypmi.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtmfqggnjd.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtozaawnvp.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtarmgkohz.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtlwdmvtng.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtwvbuqvgb.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtnjuyvstc.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtpncadqcb.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtjopkiihs.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtpsynenuq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtsfpiufju.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtaaxjllrp.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gthkrpyfrr.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtqxdbadhz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtnwbivujd.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtrlpjnazu.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmmaghqdl.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlccykgeo.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtcahwmufe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtqavmrksq.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtebfuqnhs.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtvorhceip.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtabvrczgz.html


<!-- 参考信息 -->