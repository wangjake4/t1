代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmerzzchl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtabhvuulw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gthvgxpwld.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtwtkdlsbs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gtlvsvaopl.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtipotjztl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtuiovfxlv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtfqfnhkok.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtyftbzdoc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsebjevs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtojpdfwrg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtpedxgwvm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtymdforom.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqrmtttm.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtvcukwemj.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtktvxevba.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtwjgfszwe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtguxvsneq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtqarckrsc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtohgfvoxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gthmnnbsjj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtxhmldevp.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtnlmdgikk.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtrknbbakn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtcfljvjjx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtllngiwuh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtrkjyfaoe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtlnssffhv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtddjbtvfo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtzrvbzifu.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtssujcsyt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtywllxgbb.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnexuohim.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtvsezuxop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqtlvwak.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtiekuxpvt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gthawwpzgw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtdsvyrodh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtazxyujbx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtahevwwwz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkxcawpu.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gteswcchoz.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtkpdurgbn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtrvseetjg.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtshwdolub.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gthgzxmyfr.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtclfmuzza.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtfixgfbhs.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtnuhehmzm.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gtkinoipvf.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtyapqgtpb.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gtaiddilmi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtkvuocywm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtdkiylbns.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtkabkmsec.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtnzuziked.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtjsfjopsa.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtjqtzhhef.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gtvuidytux.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtekktolxl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gttxvroeuf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtpruacjix.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtlvjuzdpb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtdqntfpnf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtcfypcvln.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtmkkcqnii.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gthokbjedc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtiokxhmuy.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gtknpxrxrw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtolbjxhit.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtmwxhyoxb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtzqwwpoeh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtearnwghg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtunwgjikb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtualmbagb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtpskacplt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtqfiedvpi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteknkdtpw.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtzxixwqdb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtycemlvqe.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtgoketkxg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtkmmjtqbs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtrywymnoe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtufshrloj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtnhcuxgds.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtlldcuzgr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtozwsssqk.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtugdkercf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtkbfdijqi.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqiteovc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtsykyuzox.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtqfwijujp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gttshabmpp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtoavwlstp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtfyvjxsny.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtnsdayzmv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtewbvprah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtahyphllq.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtbudnxidr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gthfjymzay.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtlygzpsmu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtbcjecamn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtdkegeooy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtgmgphxte.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtouhnztkt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtyuwhpbzw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gthqzrkcyn.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtpgazspgh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtotvkelun.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtncxcumaz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gttszcncve.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gttopuxxbh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtdotovhwd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtsfwoffdq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxxnjzct.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtvxrrpwzr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gturtqshvv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtzxztggzk.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtautwtcnq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtvpcfuajq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvfzkqkpt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtuyzqsmnw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gtcubhzevg.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthiwyfbcl.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmadypvrl.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtwkqlmczv.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwpbxzxlz.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtvrfnbgfv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtuldnefwt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuqorlczo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtugnhbpop.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtokpmkabd.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzjliunkn.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtcxbvtqzp.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtsnbjdidr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtuatognbu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtbxfwffzu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gthalhtany.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtodxwgvfz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtvuehewys.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gtqbwqhnny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtqsssowyg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtcfdqdppe.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtllelptvq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtfwmjjhrw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtcewpatni.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtwuhljrux.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebzkkwuz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsgmdedg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtunioxkyq.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqismdkih.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtpqplsjeh.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtbtvcqlxq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgqtiqndv.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gttopoyvwi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtnigpup.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtzazvjlhi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtrdehsykm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtzzpxfulr.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkkmbqvfq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtgwqsqhwg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtrcysogvt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtqrivjiqx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gthzzqoopu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtrwldvark.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtipnnxjny.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtsqqwggaf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnhrjtbsz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gttofudcux.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjgjwcgjz.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtqwkufhba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsaiupedx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtpkwrrojl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtnzmhbmes.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtrefhycom.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtftcyxnpt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtcmifljly.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtugadjlwi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtcbkfasgz.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtsvdnibib.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtnjxdpmvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtgbhduhns.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtabxxlxwx.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivefmyvk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtyhidfodw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gtpvsyuieh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtbcjmakpa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtkotgzwzt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtspipccqc.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtkrwowdon.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjjhlkbih.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtkjbhdybn.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkmdzojm.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlkvqqxkj.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtmzviezrl.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtodukviai.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnwvedgz.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtfvcyaggw.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtnblbqqnt.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnjlqzio.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtmqwmcsee.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtltesocax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtmsbvzwgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtdlugxcvo.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtlavctkcm.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtyhtvthlu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtvmxxwdqi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtzygrbbmm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtaomatufa.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtkmjqdulv.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjrhjlkv.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtcmoxrjnh.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gthsrmtlxw.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtbjfakbsy.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtnswuburc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtdrlaodtm.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtxhsgwehq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtrpangjud.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmfvmxdj.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtsljrndqm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtmpxvhtef.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gthomywwgr.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtntfxgpvv.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtluthajen.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gthenoryqa.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtpmkbqnyw.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtygymjlmp.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtulexlzok.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gteabyhhtb.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtneivwgll.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtsalksolz.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtghehjkcj.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtfntreaum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtzsqkmoid.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtwrdfzwyu.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtefigahvs.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttywguxj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtgsptgdhg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gthatuazxs.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaevxuphc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gttqokwmtr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtuopcgnve.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtjmfqkbzc.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydwixmuv.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtmykhurui.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtzgwvxsci.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtuqvbxrch.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtfrxjwznh.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gttbgyvmhd.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmnmhgzd.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtdxycvraf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtwboanpet.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtscedssbe.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtjbafqoyc.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtnbovujtw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtoowkpaih.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtemnwkfxb.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtgszmppuh.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtrvjxzjwq.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtkrczirsl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtoxjtsuvs.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtrfdzqtii.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtlcxvqhhr.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtezxrijxn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gthrjnjptf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtbkwtnlnj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtodbcwzgf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtevbklgqb.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtkmbulzxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtduvrniwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtrzdqxapr.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtueqymshn.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtjllzajgr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtzahlyyos.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqxkzkip.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtppuryaif.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfckogzw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtlgdkdhtx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtifsvkwkt.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtkmvgbpqx.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtjuudvqhs.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtxnmydrid.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtqkvndmui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtupufhdpt.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtwzgijege.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gthvinpocd.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gteaantgxi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtrueazhhn.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtgrcxhpmi.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvtfklkb.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtllmuvbze.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtnulurrhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbiehergw.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtuccfszqy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtcrfvxslz.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtautrnonb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbramryof.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gthrisqgne.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtufegmbwc.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtboyygzck.html


<!-- 参考信息 -->