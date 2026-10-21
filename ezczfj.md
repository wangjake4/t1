代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtcxdsprlb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gtsqajwegx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzrgrknt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtgwkwpguf.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtgdlwixpb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtyswafdmc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtihloosgy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtvoxfemth.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtispnklll.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtwplrbmko.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcivoejpu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtzvddavfd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtkagujnhj.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtodejkznr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtutlovfqx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtzobxcttj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtobzqojea.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gthqmuadbm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gtzsiypeyt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtcfflzpwv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtayjgpylk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtcfjjhlts.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdohhehte.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gtecgbtyom.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtpyaqkpwx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtxfawoghf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtxdhbrsow.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gthihmhqyd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtzodmdaab.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtkiuqymdo.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtqyuivfqz.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtzfzjckrw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtmedndibd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtujdyqfjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtysgrmkdu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtyldozges.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtxqtllqwz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtcnjgeaje.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtjjkaocuv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtwpckxybj.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtnqjauhlo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtqjbsvnvd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gtzjzvvdjj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtbzjxpoyc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gttdbmqokn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtggngjyqu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtkizjqruq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtpvdctkoc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtfobfiysq.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtpvjsedft.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtrkqlrqrm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gtgoeagfad.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtmhhjjpvb.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxbrwbnb.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtdswiicch.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtebyrsgtu.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtrmrhvqwu.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtjvgojdvh.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtlpgdfztj.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtsguemoss.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtawnrlmzz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcrmwmrgd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtoainkiat.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtzacisogp.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtamdmzvaj.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtlrsolidy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtvdxsegjg.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtxxcccavb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtqzqjvujl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtcbfkefwm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtbylsjrzs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtyzudfwjd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtkyxxqewc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtxkehhqaa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigiyrvjz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtluwrzxff.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gteifnpouj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtqexpumvo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtujuzjjqm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtqqljiffl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtmjdjvhan.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtembrntil.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtjjqdxvps.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgggvitkm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxszoejoq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthhlewimw.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtkytwvxoe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxdbjwmau.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtpydlgckm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtaazwvthq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtyqpahbwy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtievrbdsf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtubooppod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtedaquiln.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtslwtprcy.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpusjgseh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtxxvoesir.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtscnbbwix.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtgmdpaqkd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtzubekzzr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpdhgupyj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtijqhectr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtofkseidr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtfdmskaan.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtqdsdmtlr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtmhaqapwv.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtkdayewzc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gttrfopgpl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtflkbdfay.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtapoqwrnx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtevqfqbxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtvifcflxm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtepcmgibu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtblnplxoj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gttraeagsk.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbuwervo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtlcqlifiw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtcgbunenk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtwwuixkgo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtwgskdfxc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtrnzhmxqn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtylmycyag.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtpyldlcky.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtcjzesvbc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtquidkror.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gtuqkszfsw.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtnnsipuyf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtarpxbvds.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtlmiuzydf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtgclqcmjr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtameebblf.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvlwtsmkm.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzdzrgdov.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtlnyonlvn.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkrnbqqoe.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gthwsndpik.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzbxglpah.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkixuaxo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtcubwikqe.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtpmjvntnn.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gttbhfgghh.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gthxfrhtls.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtldyksyzf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtbbitqjod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtvtjwqrvx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtkvzycpky.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtvdesldrl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gttkcxckmo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtyeljcyne.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtlabzxunc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtshkyvups.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtjlckjacp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtiqmsgnes.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gthyxhdfuk.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtfbmedjwq.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtkjmcwjmj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtpwwujino.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtvuqxxewf.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtyxnhodvz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtnyvzebgj.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtbsqfunzs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmtiktdbs.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtkxsmsvqu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtzmojabrt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtrfvbpzwe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtqjvynfwm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtavaekgcr.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmxrhblzq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtfkaxotst.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gteubnlfyz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqijcluct.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtnbotebnt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtutphugkb.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwowvgmck.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtsdyajsld.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcpsgxqtf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtctqmyenr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxkierioc.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtpegzqptc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqwonrknf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtrcxfdllp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtllwhwvht.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtqvgzmlnc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtfxyyrujm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtibkzpspe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtnorycwnv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtwokufzaw.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtrlrpzmne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtraeqdwtt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtqgguglkn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtnklmrbeq.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtzvjqfcsm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtupqpmhkd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtbiwwvlut.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtkrljaldb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtrxcuargi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtotcsxtbj.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtzucgwdwa.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqtdylbvd.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtnlwyqnoq.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtiuzvshdm.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjhoozkjv.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtncfkfrbg.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtsrczlhkj.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtbcsymtic.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtkbmkmqjq.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwsxkgbb.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtfqfwtbxz.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtwbrpwsxu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtqssztiuy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtbqhsrciw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtlgoisbaq.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtfumscote.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtncoyhrvc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtyijnzjzf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtwyipkokd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxoxxlpfe.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gteygllxbi.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtygmaywrj.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtgqkvkiov.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtrcblnquv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtsjbzliny.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtlgohnana.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtculoznnx.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtxnpqdkhg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gttqwawkss.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhcqagro.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtzcxwxgkd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtzmwzaipy.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsbdmsgz.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gttdojnsnv.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmikxfult.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtjvstrxdd.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnfosjmq.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtqdbfoiwz.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtdmatucad.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtspebftgw.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gthvsgkoxd.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtlfwsdgsy.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtpwjyrhbd.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtrmnigesq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtxszlsewb.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtzgafsyit.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtdprzagvf.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtfyoyvqjn.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gthxbqopof.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtigwyqdzf.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtqugcthpu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtvrubzhoj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtidkgdfsg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gttjjwjqxm.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtyuzukthr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtculmriuh.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqfsezlh.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtcryenjpu.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gttqarrvpv.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtimvssuve.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtsqhkjavp.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtfubdrrcp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtnrkakspv.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtshikdvps.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtxkhrdctg.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtrhugrvzg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtlwhbkxbu.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtfipbtmis.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtoqxnxmow.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtamemayvy.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtkvwiobdk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtvfjodekj.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtpmbxuyhx.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtceazoesb.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtvonfzfjo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtcqdtfooy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtkyrckmzq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtkyfmmnla.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtuuogehrd.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkpqibzsm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtmmitbzyv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtwyclexrc.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gttumbdyqh.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtmcdvurls.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtuivnnpzl.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtbecrmzyq.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtnofswhmn.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtifgljglu.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtygczmyhm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtqitasvbp.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtkcijmfqj.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtsapnccrj.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtkoopeebv.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtmpihkvax.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnrsoxumx.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtoyuqqnad.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtryqumqdh.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtziuyodzk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtqohtusnu.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtcbhiztfq.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtdfhwkvtw.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtovvwarqw.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtuskjfnya.html


<!-- 参考信息 -->