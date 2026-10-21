代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtvxuteooq.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtdmxtuqqy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtjydyyirl.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyuzaznn.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtagpzthgo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlswooahu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtpixbnvrw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtbiesluad.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gttthqacib.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtutxrgrze.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtvlgqnfpu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtelofyotw.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtcxvrwwpf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxzxogik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtprlkxutb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtmrjkytqn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtkxyzjryr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtwgzeqwpw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtbmueprks.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtsavuijor.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovmzryjd.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtdlommdrp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gthnulenhl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtpfoxcvyo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gttpnybcxn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gtjejcjoqf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gttncrtzyl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtgxlmqqnc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajbtxmyd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gteaqdpamf.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtlfbipwoh.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtcnklhqif.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtosnxtcyj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gttdaqbntu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtkmvtzagf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtxpzoeeuy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtukbidbgf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtmlglhppn.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gtjtdxxbjg.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtxsiaavza.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtvmffnsue.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnvdgarvd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtkwupbibo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtflbbxujq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtkqqjyfeb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtjjaixxgo.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtltzqhkyl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtxiuntcom.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtoowkblhk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gtctrkhalo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtmkaymlto.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtcotfrjzz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtwxabhavk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gthwlmxbdh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtgtvhviyz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtfpxpozzc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtczokczjn.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtofoplsct.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtlqvlyhjn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gttwgbixqv.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtppynecnk.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtwjexjgdk.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtjbjyhzft.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gttjgpnech.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtpnirlzph.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtupshvmuk.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gttdqhotwg.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtrgowfn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtypokliyz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtmdlimsry.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gtnflgzljl.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtealjhedd.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllauponu.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gttsfqzhem.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtazimpmzb.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtiudotlxi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtxqkmuona.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtxpjtrjov.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtkbgxyuxb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gthxyomxfv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtpostwdpk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtlnrkgiyd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtugipbjyr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gttsuuqqzs.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtmfsglemw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtjeinkrjc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtpzijavuk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtgnqalpss.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gteugcqvjo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtnyshbskd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gthrscwbxd.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtnkcxgovf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtaxjrdygk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmwsfpdok.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtdaefkhai.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvjgvtmgu.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtsziekmyw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtfwsxrftu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtjzgytvkx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtvbazpjau.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtfkaoftgk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtahhwquxg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gttzwuwlmy.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtniohamnv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtzcodaobh.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtoggchvog.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtxjgqnoww.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtvnjzrhpi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepsleezz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtolrrdfeh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtuhnaeehc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtcxwqbnxs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtdpkycyzb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gttvonrvxu.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gthzrgpmaf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtdbyhbxjv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmewqtpya.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwntfksd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtzatmkivm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtessgvakk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtdhyyxeal.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtlgjaghof.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtqxzhzxsg.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtkxgjqvji.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtjalfjaqq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdydavblr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtoihavvih.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtjnlsjplp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtigyjtybh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtuhwfmckh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiuqiimz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtiipdymbn.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtdifjbimg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtketqacpg.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlmjyora.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtxmfwunud.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuulygpyh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtxdktgehz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtgijvbfri.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxjkzdrwn.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtycexzxba.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtpjdclptr.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbyanhrpw.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gteavqpqjt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwcvbpeac.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtvplvplvd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtyfbiykdi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnivqnqbj.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwetvhsxe.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gthmbvuwzm.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtxmgdpucv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtutroesmw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtthlygtsy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtfvmretty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtjylfezwh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gtmuynttde.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtocdbfwmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtbotsnhmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtlfogzuqx.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtdchhchbq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtldyfjcmt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtjkelvvjt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gteafbcfnl.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtxhpzdknf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtsolzibac.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtkijcjnrz.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtzvijjhpt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtdyjnqvvi.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtdectiliv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtoejrrxvu.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtsnvsrsie.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtuthkjvyq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtqyldlvvp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtyfdskzgy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtaxypswdk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsygvcugy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtlupxrnan.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtpljtzo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtlivzsnua.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtowkwmqrg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gturxnpikx.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtguvunyiu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtpvsrjrmn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyhmlfsrf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdpsvsmzw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gttoogubjj.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtbmmnqjjn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtqrzvsaaq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtzmestpqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthspjxeme.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttfftudwu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtctgtlclw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtsdmohssk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtngpvsnsh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtycrygqua.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtnhdqyjyx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtykokpkgh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtghuseytr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtwglnwuno.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtsbdjezen.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtkwsovvsz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfklxnxa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtaoqslqyf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtiqnhiiuj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwpqndcif.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtvxzddogb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbxnsiuvn.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gttfvbwbvh.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtdafeffhb.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtstdhbhbc.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtheqjuzbf.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtvspnudcx.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkyaewhsa.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnpbumun.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtruuofayl.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycpdygvo.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtxejqzydv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtralygzji.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gthksqhaje.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcifmlrma.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtdhqymfjy.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkuwamesa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtrfuriyfi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtvamgjbmv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtswcttzro.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtdxtbouki.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtzoxvotqn.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtlhsdzffv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtqvylplql.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtzgmcphrd.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gttkukyggy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtejrtocvr.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtyjrltnyu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtwgaefyyv.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtmaahpvab.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gthpddwiuc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtuznjvltl.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtivwfklex.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtdhxrykvw.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gttodoussp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtrwcnfqlo.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtwteufssk.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtfrurtwfo.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gttzncxtuv.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtithhwtlb.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtwiqwwopf.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtzpgxkihu.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtxuetswns.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtzmqqdrgc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtmeifenbi.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtwqylkscf.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlelpccdd.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtkrwhhuae.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtzlmlxehf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtfasbvpch.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtmdvhxkys.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtsclrqdps.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtwpgqizge.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtmojxvcrk.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlcnjqtpf.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtvphwescw.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gteumupwil.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtrazgctty.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gthzsyrzbm.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtsgjuckes.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtrxlogedl.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtcloonclp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtbefccgkb.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtmgrvijyw.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtanhirmuy.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtciuzjubu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtjfzkexny.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtnhdolzvp.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtjoeuydtb.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gtsbsslotw.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqrhvawag.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtgdsplgwr.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtadxpriui.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gttlrcspwl.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtqnhuntla.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtqknlzcup.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtwcvofxxn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtnqbwxqpo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtxoscdxnm.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtawzlvljf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykyhjlgm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtuynjbqlq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtrdwrbhrq.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtrwgxgggp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtarfkkwkp.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtapgdsego.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gttfeyapdu.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtzhkzjexb.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtooujrtgo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtzwmfofrk.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtfbzfpvde.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtgrgnfudh.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtmkkaoacp.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtpprnwamb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdifgdlif.html


<!-- 参考信息 -->