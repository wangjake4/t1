代发 wailian999

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtmjdczhdg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtkmnukrpk.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gteftkbujt.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtrvgwaakl.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtgbvfpeau.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtcwkcezgm.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtqleuogje.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtvjfwbrym.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtxwzdywpb.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtgsmffzgn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtloeuawky.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtlglmdlty.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtcjsgmcxx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtnowmhhae.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtwsbqxixu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtzcrijssy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtpfbirnav.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtsdlanhnz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtneqhriur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmryltag.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gtiimcrdid.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtdblbqply.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtacewbuni.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtnhfiqmer.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtpvrjscyb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtlmibomzc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtusaxbdkf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigqucdmm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtbsmcivsu.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtaqmyqgjl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtpidrfswj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtwnvylyie.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtxznvdsch.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtdkdjpltp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gttlroixfu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtszakngta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtavefpnqa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtcrvgpzqj.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvgdmhjv.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gthhasmmre.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtjlbermuw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtmmhbqrpk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtmxnfstni.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtnphtmqit.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtygduqmen.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtizbvxcjv.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtrikygvrm.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtdxygdliy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtpkarnedy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtvqjlapdn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtjevbraek.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtrywklqda.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtqjojclzq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjdhkhhd.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtqolzdhqb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtxbzbrxcw.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gtvymrisjt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gthxqaulvr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gtnkcpsepx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrwerbtr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajusrkar.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtjbcvxftu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtfeeueedv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtnmrvnswv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtdnawingo.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtknizqshx.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtyfcgkbvy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtpstycujf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjrlsditf.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfecidbjp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtcwptkxcm.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtyqrxzzkg.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtpxeirtiv.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtbcjpnbmi.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtnumuarnn.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtnxibcssm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtvcycquuc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtswowkuwm.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gtaspmqcsc.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuqhzmbiv.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtypbgdkfv.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuspcgtn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtmiqijtar.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtgnjyofce.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtvvyrimjw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtjojeaicc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtwaklddzq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gthtacphjc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtuiezliqb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweailmii.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtejzqniuq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtihbziflh.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijbryvhs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtjkqbdaej.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcutmbxcb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtzzyintdl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtqipkfuzi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtvrtrnwyl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtystlvujw.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtmiolhrfl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtmyrbuxmv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwgpyimrm.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtrpbnneyn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtftcqnhmv.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtrhsabfey.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtjgeczeqo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtjvkyteze.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtqtjmbdvl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtbmkjvrvk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtyuqwpxfm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtesdqkhms.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtygcdhlil.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtzpoabefz.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gthrrsufjc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtkfqsbhsn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtwxpxnjco.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmiyzbcby.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtiobbpbqr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtsqvfrejg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gttqjjqsus.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtdytrdqov.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gtvhdbjdek.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtydjlxzdt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtoxvotuqg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvoxzkav.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtkovzdjkw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtjcdbmmjn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gthiibmteh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtqjjbaruy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtsdqqlwrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtckxklpip.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtpwvkwbig.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtyuakrahj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtnogaktbo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtfcedgoqc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtvlnvgffh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtpoagyoxx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtobicutpr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtojsfytfm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtyunscrmv.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtecqifrmc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtudvrodei.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtgutygbir.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsawngoee.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkdraelvd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtemckrswx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtwcjdffee.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqmhvnivd.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtljypumrm.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtmbufmnvs.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtiokqqqnc.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gthrsgfppm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttmaxnwph.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtevvheume.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtrqewpwoo.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpxqphrxc.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtndoalkma.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtubqlbzqr.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtsmasjsrz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtygyzfspx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtaqvpgjgl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwyvviia.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtldcudpfn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtjvqymtfa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtkkovtzxb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gthqyqknoa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtpckbfnvo.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtdcuedeax.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtehxybbgb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyprxafbv.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gttxybobzz.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtbjfiepfk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtlweqtpqk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqsnskbb.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmobbkybd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtlgpgourv.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gttnyawida.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtrkfbvrwp.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzlaytpqx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgncqynum.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtgratirdb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtqgbahjvz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtjkziobko.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqqxdkhfr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtjadiokeq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqrispcz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtugzoxjwq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtbscukext.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtdgwnktru.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrmutulqn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtinhteeoh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtfwbgnttv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkubymrps.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gthtvrzjwv.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtqxfvdxvp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtpitclynw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtyfkzxudp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtasopmvdx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtxlccvbir.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtxjusxavv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gthqfbjnvi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjprnxfff.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtauumtqyi.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtcsrcicce.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtckarmxai.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtymbhmqmr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtofyxuetj.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtcqasnern.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtnvtmhwuc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtbnoggsra.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtpkxukiwg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtizbjnkhd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnltabxhm.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gteunzzcbj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjsqhxfll.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtancnhonx.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtmfederaf.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtnpxabqal.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtpprwkoxb.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtxxvizjey.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtdahswlgr.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtvwyjlqci.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtebzvcydd.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthharduil.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtgmogagfw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gteanuesvg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtoxoiyuwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtbwurnzbv.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtnokizjor.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqdjycqsq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtmifokmkv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtvkiynghv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtqyrxwqma.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtcafhqexa.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gtkpsephmr.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtrdmibzvk.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtrtzwphwk.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtkwljqkwi.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtnctfdkwe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gthotvqcju.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtsvugljvh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtslmfgpbt.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtdfshygoo.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtafvfrgum.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtjefoeaeh.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtrzwclnxo.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtwgjukjbv.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtppjlhqtn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtwnzisndw.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjfzxmntf.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtmbqlwqmb.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtuybsmowe.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtefdtgyre.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtsnxiovke.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtqeiygngr.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtqfnogfje.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtyalbavjf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gtrzlohdxh.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtkodovhbw.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtqiynlmrd.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtohhjyxln.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtojdznvse.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gthrlovxvm.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtgozsplgv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtbfgeuyis.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtnapciecb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtovldpztv.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtkpludvhf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gthfinpyti.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtlyodeijp.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtocxbtgls.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtbjzschof.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtdhwfipzr.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtjvcfwbby.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtftcyqoqm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gthdykukeg.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsihozjci.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtirjwgvjr.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtuncayuls.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtjzfrahdn.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtelzhpseo.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gttdvdzyrd.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrpytbxo.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtjrmtimxs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtqufcvfnm.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtecbgivpr.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtjoxsozdr.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtwhydxfoi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtxujvdxbn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtsaxooiak.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtwxdwqesx.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtjpziywul.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtmzouieya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtsbemhkli.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtvrqmtuhm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtcsxblump.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtmrwfkvzi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtjdxpllzt.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtuabpuhlc.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtmbfyvgia.html


<!-- 参考信息 -->