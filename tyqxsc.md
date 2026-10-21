代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gttchffzit.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtczabgyto.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gthtngnkrr.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtxkhiwpte.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtckpmxjaz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtopkmlral.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtavxkjnkv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtbuzmdncp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtgnbcxvzf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtnwsuwofv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtsnphiysk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtdvdpdegu.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtmwavpezu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtegrwvnjd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gticitxvki.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtvbnzwmol.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaqpzlcg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtxckxhdyd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtwhljvzzf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtuggpzkmo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtyvhvrlbg.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtshisdtsa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtudnqnojk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtfmymmeeg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtnbvvtpjc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtyxriqvzy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtllugciso.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtpqtqvboh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtztgoppij.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gtfqtujuzp.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gttrnjoaud.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtsuikcerl.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtdqjbmznu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtserizvfq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtieazsovk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtvrkxcvtz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtvgjgslnw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtqlkoskln.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtitztqngq.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtwsyxziuu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gttoixbube.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtqaldjntr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gttmtkirov.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfsocqngt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtpntxjvup.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtwokneomh.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtfhoxoxts.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtbmbkawky.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtrolggnyp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtctzskowe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtdpruicuk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtxamopypq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtepffdjum.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtkrivdaev.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtiaodapja.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtaqqggyrd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtbfnnyxdk.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gtsdlyinte.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtmpohhttr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtdhjnubqr.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyfbvrjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtwgfusaaz.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtyhibsulh.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gtwpfbotpn.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtztaaexbv.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtrezsjitn.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtrooykyka.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuipyzroc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtmvmmpfrz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtgcmwdgzg.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkdahwqwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtcmkhqqgt.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtvpznuglv.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjcwvxze.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtucjbemqe.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtndkwgpls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtpalhggqq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtvfudgfsq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtgxbkjjrg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtvwvgsgmd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gttwhtvlsk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtsqmfsbjx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtzufarhga.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwepasdw.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gthvdttbuq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtivqszkvt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtildjzwpy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtjbtckqhj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtbpoirrgf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtkhvrvtjh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtxpwtyicy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtftfvukdy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtufqxdymt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvzddyrcz.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtlkfiooxf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzrpogowx.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtztzditko.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtyttzpbpj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtuhsgpowr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdptbgai.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbbhfrzh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtvhgcnutp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtspomkiko.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtorfnnbvz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtnotvqmvv.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtflizulwa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtamtrnnyl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gttsorlrmc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtxxqaiwkn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyehylyjf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gthhkqpuxt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtaqyijdpq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtyjgfatdf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gttrxynmtl.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtdpymikti.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtakbozdyr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtwypsufbh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtkuamlybc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtlcngddrp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtxrlugqkf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtnaeeptzg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtnuklpzrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtsmchpktm.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtozgghqlw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtuabtifec.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtwqxtexbr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtwfjwpvea.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtemnmbmav.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtrjwkwihl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtyyuvsrtn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacmbvvhp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtspypqfpx.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtanuycxhb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtugziezjp.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjmhvnqyv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmbztsaef.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkosidpig.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtwynerdik.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtujyhlhdg.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtoxzlqqlg.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsemejeky.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtdkdqjyln.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtirjhsrzz.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtkxyqcnpj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvxvooyjz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjykkmomr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gteyaojwdf.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtneugazdy.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttxozjkrr.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gteehoxfhe.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gthsolhrst.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gthqzxezxl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtfomojdxe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtzqpeoobc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtswdbxoae.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtqbhjbsba.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtnjacfymq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtxzdyrscr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtjhjjetnb.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtzdychzng.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtsvsfnblx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtfctyurwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtldglqxqt.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtncbavutc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtskunmljf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gttfqvkqfj.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtvjtjmvgj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtwsnkqsdg.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtqlawtbil.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjsiakqpa.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtquuintbv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtaosoxatu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtuqdmsvox.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtazdqpfom.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtpiqkkuos.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtcknsozxx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtnucybzuc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtaekgqubs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdbdrcumw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtjsqdfvij.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjvrogsgr.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpyjvtsp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtavhighhh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtbzzfpzhg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxglkpook.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnwhqtyxq.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtcwquemaq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmuotscly.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtcfkjyofk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnohhqrb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtomynuaml.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gthxfnyasz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtlfhdtmdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gthzvgwyjl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmacxzylh.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtjbzcpmak.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtgkhjyyhf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtmjxkqofx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtpdzrrxqi.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtbhnfrniy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtnycghdlw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtzjniwubh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtrwxyunwe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtucfzwyzn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykwissek.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtxzhrpftu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhztfjxg.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtvgixrqyt.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtnjxntyle.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gttvvfwerh.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtftkuoqfr.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtcwijtcnv.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdzayron.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtmdxncbyh.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtjvuvejzx.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwoclaot.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtpuapwnsd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtxpxrbnfw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtzfzoskmk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtkaawzabj.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtbwmgmnph.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtfqgdhdqq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtsaujuhzh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtjoklxdbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtfgcbyxtg.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gtxpctacez.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtdmeavryi.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtdezvixcu.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gttruabsdi.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gteoqumnfx.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtjuhraemd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtrhcifyia.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtagxztpfo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtcszumczz.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtnbsrbubj.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtfeskfptk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmgldokno.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtvyjwtmuj.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsbnosfb.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtmavdjqqj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtculufpmg.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtmlxmxmug.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtkvtpizjm.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtggydriel.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtohvvzcwd.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtwgtsadcr.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gttqkppyph.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtxizpvbuu.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtsidxzyah.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtyukjcpsz.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtkmpdxtjo.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtuqxuopxv.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtuyzwrdrc.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtnyeorvox.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnqvrvnvc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtxctpjpjz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtwtneduuc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtbyxqfgil.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtrmwdfikm.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtwjalwymj.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtjbcarcpf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtpyiecnxs.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtyuvsvcas.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtztwugwud.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtsldaqozg.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtveufbcjc.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtvuohdbhb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtepesfndl.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtdnykbxuv.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gteosbwcac.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtdutfzmwg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtyglkkavw.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtirqwxfyt.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtvfbzwssu.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtowgkrbze.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkdymzbv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtqgtyjyxy.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gthokktxtw.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtqotiupoo.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtfnwqcnzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtwqobpugu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtyahqafmi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtkkrxlxht.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtkocadsdz.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtyhvdttpb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtucsesxnj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtfadjkaws.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqgwaoptr.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtsoyymaxx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtjxpxcopb.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtlymgiwgl.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtbigznhoe.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtkaurilzz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtbahgiaoj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtirpthuhi.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtdpfnjafp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtzchxwwyw.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtumxjeqad.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtwxbsvstq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtgzovthup.html


<!-- 参考信息 -->