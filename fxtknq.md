代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gteotgpyct.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtcytugjwj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtupntmrhm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtemhrvsxo.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtefmsrchd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtgrqrmqnv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gttfgodvyy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtkolvfqiv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtfjwuyrds.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtvchfalmb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gthzrohqdy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gtnitoctzt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtuzhhivmx.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtgbdsjpqv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtlsiqgznh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gtzqrdlizw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtblxeorkn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtmjpgpitt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtymfusudt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtcywipahk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtpxvqefyv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtoqikyhka.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtzgjalbxz.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtiixskkar.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtutbuabyi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtzaiwzwmr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtciwkchzw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtcjqxqdln.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtkufukbnz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtcwybmmdp.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gttvibnerc.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtxfggoiyx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtlbygksbx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtwrftaxti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtdqrblwxy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtpyhzfjkk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtekanjecr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtoyhdvivn.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtdqaephtv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtefnhyaig.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtoylxccwc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtfglkwwjs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtlkjaweuy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtvszxympo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtkosgqiyy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtsydsjmjw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtlhdkyuqf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtvixbhvkq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtzdfpdjcd.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtudvfpuar.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gtbthrokid.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtvkxcmkbh.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtkpbkuxud.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceubmlox.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtqwtwlttn.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtnlylobvv.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfldqhuz.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtqelckybo.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtexpeirub.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtucdnnfjx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtoiodybmf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtjakksctj.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gttepahxrc.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtbqiyonzo.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gttzujfyyd.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtiafjmaau.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtclivnctw.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtfygshzpm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtelyatluf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtkbpvzuvu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gttwvorilw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwozvlru.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gttjuijtdb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gthjwwsbho.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtjqwfxwqn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtacsuuuws.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtclcukdid.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtxbywsirv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtymsiilar.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtbrutatge.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtbgjmitkt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtyfowmifr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtttjohmjt.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtakxyycif.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gttpzwceak.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoyfiboaw.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrjyhbli.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxcofjdj.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtmgjmbibs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtvbzwzevm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtmflmgnxa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gttlfuovts.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtzcthvjmp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtedkxdopc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtvoqorscz.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxrqbxxza.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtiamysszw.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtuwetcfgv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtxbwrmoih.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtpqrbrncm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtclqplfrc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gticwxecnq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gttgdxvjde.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtjubtdhoz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtfmerwxwl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtxarmgvdr.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtsupqzuut.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtnwzlqkno.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtzocjxhvk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gteghnzlkt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtwckhhqwv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtaglrytuy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtvospqlta.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtjokaxptu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtdmcbkndw.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtcdrzgioo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtzbegfjux.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtybhnqwxm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gthugbmenk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtyuackdpu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtxuhxnrxk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtewcejvqr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtgyqidfns.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtlwmpozcf.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtydpxpylc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtbzpmvooh.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrhpknivw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpkmezcjs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvenawikn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnkxchfak.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtvxatexgv.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtuvteqjvt.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlmmpqnvn.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtbpwuzmjr.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpkneygrx.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtbdtxtejb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjatsbszs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttnaprxuf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtyfdyxamk.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvqpidriq.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtkbkaplvq.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttzanubbb.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtxrlhipwk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtgvoyslhs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtkhajaezw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtwckgizww.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtvhbcwdxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtyhlmjekd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtwkijrhwi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtinmrxivb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgtnopzy.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtnzyzplvc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtjphvvahq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtvgbmecxu.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmvszsqha.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtftwrvuee.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtgmigabyp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtmdzpbvsm.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtbtxszqvc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtlpmowjxl.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtqwwfvbwz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthlocujni.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtodykbhft.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtrdwdpsoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtcbpujvgl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtghqlmfyb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtqrwwjxni.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwuuozqmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtguvvehyg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtcwqulumi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsdcikhms.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtngrlxacx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtobxyziph.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtcmjbudvn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtxpgzawrw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtbazlhwed.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtrlsymtkw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtcvvyvsha.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtnzzedtti.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxvpzltsx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtreefzjri.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gteafobxfb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttioziuyo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gteumyzzcd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtirtxunor.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtafbceyrr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtrroaiiwl.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gthhuwbumr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtnuymcrkd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtxhpwlxjh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtvktbaado.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtqjressqu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtdfdmkjpy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtmnstkkwp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtyncynsre.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtgnlvzrgw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlpqtkqjy.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gthowjknux.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnrztldap.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqslxkssl.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtuzhcsmii.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtuxsfpmsb.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtkgkyxklg.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtuzsvvgmy.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyzkgxiel.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gthjvbpwep.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtvhuwwgsf.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtowknmesr.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtevwrodrg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtybhhayrv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtnsdpltda.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtbpryrzlj.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtzcdrtxof.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtssadsngy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtalnvxq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtvbyphqru.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoftqjzdj.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtqufvecyn.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtvoaksfwu.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtlupoatrc.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtwppzffin.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtvcxfrybw.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtkwxrfsoq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtscsrjyfa.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtwcqurtkw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gtpaxyyqta.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtuxfbpiep.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtmyaxzish.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtichravwi.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtcbqudnmj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtaqynqiws.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxpaxjdnt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtwtfichsz.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtrungpfhm.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtmxlfkdzq.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtlpkxretb.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gthrturaqx.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtsnfsbhne.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtfyemxnzu.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtdbwthfxv.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtizoicztb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtwrvrqvli.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtvispprua.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtqeyslhor.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtgzfmvyfc.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtgicdjtqm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtipkbvftz.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjhpodnvr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwvuzmmy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gttrqfkqfm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtqbbomcmm.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtyaktytfs.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtpuwhwyqb.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtisbhlxgh.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrebbxzwv.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtqntpgcqp.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gthskudfxc.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtgwheftsr.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtnamqnjkz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtwroqutwl.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtufvulqfd.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtjnymwvlv.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtroywuvlc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtuhkvcfyp.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtetrszycr.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtnpdrqiod.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtfcdkqunx.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtviqfxjra.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtyiwridzq.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtldrujmws.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtyyhzdeti.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtnshbkxzc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtrnugiegn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtylpwqdnz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtdmapulim.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtmhkljeol.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtnewxobeg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtovahayoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtylcqkfwo.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtyoccxivd.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtfubcvqrr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtoubgchvt.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtederhbbl.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gthrclsstk.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtvdmnmqwu.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gteqxtqefa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtjbjsmzjz.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtfffsozej.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtmojpoayp.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtmuixfetp.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtmlindjnx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtkwpxlcjs.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtjbiipkid.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gthqcjwspo.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gttevomcwo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtrwtmxkwy.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gteisaqqck.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtqgjbewfw.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtgmikalba.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtolhsdftp.html


<!-- 参考信息 -->