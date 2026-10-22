代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtnayszsdg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtmsxzlvsy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtxnuckmzg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtegdegztv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtplqmtjbk.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtvexdtsva.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtgsuklgmu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtjzcnpdhh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtddczbwyn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtezdoxpxw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtohrkxfum.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtfbknandg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtelfhqwlg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtgtfxhkgd.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtzzlcnxqx.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtggpgexqq.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtgannmtfp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtyuccnhhk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtxmrdsycj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdgkyavx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gthukqsrnr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpsxhxau.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtjrgycnjx.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtrrdehrvy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfegshrjv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtimnrnadk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpfeehlrl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtwzgqjdyi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtosfijlex.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtsrhmvzhz.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtxhcejccl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gtajzhiely.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtslpdmzcl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gtbmmsdovb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtttudorkh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtwfimhmsm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtulcuoxnd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtkjtagrqb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtirqmjrfd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtpbovhmoq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtvwuakjfs.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtddgphdqx.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtmkkfkuyd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtrmvletfm.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtnthbmswh.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqmvfghs.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtqphzmcdv.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtpkbafqre.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gttjxmjcyx.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtnycrjwqn.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycgitppo.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gttifwhfjm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtszlpnsqk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxyhumwiz.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtganjvzty.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtyviypnyc.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtlvivxnhw.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gturikfpsf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtpybmfkfn.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtbbjgsctk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtxltuwvxa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtofykofiv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gttoqsdwrz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gttdraawwn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gttadkyjbl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtccwpkisk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtgwoizula.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtyxokulch.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtepgkmxyx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtqsnslvsd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrzuevok.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtfvjnzqqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gttbtisevx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtzgmddair.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtywelmdcf.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtqwagnwwm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtdyxnpqlu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtegqgjyco.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtmuaaeohi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuoonykhq.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtrtitheyd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtiorttlql.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjkqzihdo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtgosjzens.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtggbxoabg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtcmxlevga.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtvyjnhkpw.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpjqnferb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtzohsrhhy.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjpdtgpto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtqmycwlum.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtuqqzrdhz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtprlaohyj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpescfvj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtmjymozdp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gthbegyqjb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtnimiolsp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtxlnqchtf.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtztuvgqsr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtkfnhpayh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtsmfjmyon.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtiflstwxh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtlpfiypyr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gthadjybsa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtibqugppy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtrcufgtkj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtoaarcufp.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtdvjqicku.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtkkscbceq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtnukkngio.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtdrbcpqau.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtolftojxz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturswbmnt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtulcjdkrl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtzvhtqqqy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtqxshkfac.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtqryufdxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtegfjwgtl.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtkehczzbe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtalxogspp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlacfxdrg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtjjztabhy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gteypuwlsm.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqjifijmr.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtduxerlsm.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtgsnfvsyk.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtozezbemd.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthshvlbiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtrmpgwdzb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gteszyvuik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gthmphukix.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxyvrqrbb.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gttfnvsqwx.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtviftgbua.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtrjpgftqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtffnivvyj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtijhssudd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtjgvtffdw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtwqpldgkm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtiufnevnm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtqgrrbbjk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtlprmtgmu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtavlkgjpg.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfymcsshq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtzfqlvbhh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevxiabks.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtkckkqveg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtvukkowgh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gteildhxzz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtvuxggpes.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtyazwllkm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtragqhwqk.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtmutvuocm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtoxurmrbn.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtdgjpjfsm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtjwgtentf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtqxkpvvdg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtzjqizxwv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtzbcwixau.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlofbknlp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtvmnvrmts.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtxsyxczld.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttbopnapo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnametvct.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwwvjeuey.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtujacfrtp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtbkugtqmj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttmpmqvvw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfejmopex.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtffkqmzrj.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvukhwnts.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtdkagkujx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gtvebbvzla.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjwszmfh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgykipjnr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbiicmai.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtufiegehz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqjwetmae.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtnkmipwvh.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gthxvsyjjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtvocpygyi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptteuooa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtlvsiedsx.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gteyvnuaxg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtfdryyhua.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtbvhkasid.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtdqtwodlj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtxfzyappo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtydyoikik.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyyzgntk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvjvmxlpl.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtghpaglzj.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtddqtruhc.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtukbrvejg.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjmcxzedb.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtwjfqltmw.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtkmwndtid.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtqlopiqqn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtwtpcpxbw.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtzfipvxkh.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtovxsmxsu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtolhvwzje.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtfgrthwzs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtludjxyqf.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtvctlfzyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtyxxqkrxv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtqjbtzvjx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtuqqcnett.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjtefrlrg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtqjskqpeg.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtspspvbly.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtwjpywdvm.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtqgrfqfhq.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtteexqmum.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtdoxaqngr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtbuvoldta.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtovkdrsji.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtdgkkgjht.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtreiyowhf.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gttxqejbaa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtstauazml.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gthhtepgwm.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtqjppsgkt.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtpgzsaayy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtvkxewlqd.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gttmovohqh.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtvhgcgjaz.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtgwrdhymz.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gturfeawls.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtxqqjqjyw.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtibverzce.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtgaooxbon.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtdexutuzr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtihrefwhv.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtfzkbgaqo.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtdefkasha.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtjycgnlte.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtzsfxhhic.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtodmmdvhz.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtvrmfqubf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtchmtjxha.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtkfetjjqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtynbjxe.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtlfmcrbgr.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtqgglcguy.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtzgxpmkdl.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtknqpgvoc.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtrtnjhcuz.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtcylbrgej.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gthlltfgon.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtbzealiiq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtjkauqjey.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtcbjjjujq.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtntzqyvik.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtuhysswks.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtqplzflmr.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtazkhvvap.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtkzalctoo.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtzbcorsrg.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtbrjzzvdk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtkkfvgwoc.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtermlckwx.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtsyfgtcpz.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtpifgkvii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gttmghkujy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtgafkzqcw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtglubtpnv.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtyhvmgfbx.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtvpcwrgax.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtdbkfriap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtdhkhhacc.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqvjwmtcy.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtxojskvbc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtbmsmpavb.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtaaqbikzb.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gteijfniby.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtvymsfyte.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtdvshpprc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtculahrzj.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtxvlbvffh.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtdxegiscd.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtkgwjdyqd.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtxjcsilzt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtcigtvhhx.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtvnfxfnja.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtlxosksoj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxmfptrgh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtoqqhtwca.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtdxkyktyv.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gttppuiusj.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtsvczqqlq.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtqcbqqduj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpycmtvle.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtxzwehvhl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtvnjidtpj.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtzznfqqzn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtybmufnro.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtddiyvpxj.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtrxylgoqp.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtnuvjslfr.html


<!-- 参考信息 -->