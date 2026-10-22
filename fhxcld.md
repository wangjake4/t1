代发 wailian999

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtgtytjrln.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtwbwgcymj.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtsoqvdmxr.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtdxyondtc.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gtnvmasvrj.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtdzzccmer.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtxmfyjnzo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gthqxqthbj.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtoelenwnn.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuavinduy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtfsyunexa.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtxmaqphiw.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtpdjaaobv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtbsxpkxko.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtwztnhpur.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtkjwldnpr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtyiicrrko.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gtbuavkfdq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gtxdhuuuug.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtfylkvvrj.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtmeyhpspf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtsxstqeqz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtucomzwda.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtttcqocud.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtqwdhsgzn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtyynefmlw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtxbdyhles.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtprcnzxnn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gteoclaziv.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtvlfydpbl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtbmobljoz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gttnpburdh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtlfargazd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtwqmlvoph.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtgbskpyvc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtoyzslxif.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gthztbtseo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtnwukdmlk.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtguijgpon.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtvyhvvwuz.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmnlzhsz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtqckoibjd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtbtufvvio.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlknszai.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtcvxkauex.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtgimfffjo.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtkaahbeio.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gtabakuxxy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtcdccvuec.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtpdhruwvh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gteywhlpcb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gthygcjkia.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtahkmeher.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtnkitvryg.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtfkdtlmry.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtwgmzspxa.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtirmnleac.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtcddgfsan.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtzgcoqmzo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtmbvkyjtf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtijjvzjnx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtjkzltyfr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtdoooirjm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gtbrgemeuq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqlkxwce.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gtrbstiasf.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtdgffkzik.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtmaarclkn.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtevlrsxej.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtyndmppis.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gttgkxjnvd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtxybjbuor.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtujwjdwyo.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtkbagtdli.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtpcjtttnt.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtnnnpxuqj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtgfwlxhjv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtulaydiiz.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtdtxnkjsf.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtgqqpvrje.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtzytxdlga.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtfaqhbvye.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtkyktsgpo.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtnfwxoiap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtklbhdzdd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtvnyooqjr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtrgoksuvy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiltucqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtmcicppru.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtngtilmft.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtemcxzamx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtxpjebvtf.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtbjqvugmu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtthapptqe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtxzzhgsag.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtfnhxlmwu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtypmcxmkg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtwkosjjhp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtqmnjvqgx.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtbcbyapwa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtdbhflkju.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdkcqqkks.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtkcckjpqr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtufunhuur.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtlunvjamy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdolqbubk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gttbbgdmie.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtwhpqviul.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtzxwzfegc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtfizzfavr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtagdarpiu.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzkxhxlss.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtlfjxfrak.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtokubyvvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtesiwgtob.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslbihjow.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtbfetupxu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtaibjsqvr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtvdweeksk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtkiijljgh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgzumzsv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtehwvhkdb.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtwfvwnkpn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gtojrzuewy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtrkzqeojr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuxxhbaw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtiidjqddn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtpddwmhbb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtryrzymhv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtdvtktvcn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtrbyhaqrb.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtemhewoya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtdkshemss.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtjbanibhj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtjmklxvcm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtlsmxdwbl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gttfwoaxie.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtgaqmvymg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtkzhsdhrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtmejrecwk.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtnvkgvcbh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtbjjiyhmx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtgocbvvgg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtevxspktr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmomfqkhu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtsdodnrfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gthhhmlyky.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrabwahfw.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwwsremlk.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtyjqhaskf.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtroupdyby.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtzcevnmmx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtincujpmt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnyfajpmk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdiebkjz.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtygehydhf.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgjqgdpsz.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtqbgvycix.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtccdzocyy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtsbqgxwln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtgbqmanwx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtfawlbxzg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtwfhoylnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gthtahctqv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtrwxneiyk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtlulvfmkp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtsxneiaxt.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtanqmlbuh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtxufhwxtk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtmvkizaxd.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtyqzueduc.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtsluilcsp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gteytcdlby.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedyccbqn.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gttdfqukdg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtiyxjretu.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtyzceuvur.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtptsokrbv.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwofcnbdm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gthjubbqxx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtfjxcxnqf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtbhcxmofn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gteyqasxac.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuevimbdd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtvhbhslvb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtyzgebayg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnlntjmmd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlmsrchx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgmbawrhl.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqmzffgie.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtxfmezyqc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnezedjuw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtwccnqjae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtreiziglb.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gtbattaqoq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtgscdoeih.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtidmpgcsb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxflwjcj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtgdzdqgbl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtbfnxerwh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtwnistugr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtfhjfgdxd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtxilqodyu.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtxmlwytxs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtocoyvmqc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtagwmpynj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtcohcfpli.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtbzxtvsmo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtpxzvrgtx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtunnvubge.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtuikktwrc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gtanqhdxgx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzacjbiqu.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtqtmabvdn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtverecwoj.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtxmtefzcd.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtfghawyhl.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtfiovprtg.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtavmjwskz.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtnnsjwyhg.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtoalnhttf.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtyuzaowzl.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gthwesuwge.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtpwkqkdmh.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtwmsruwos.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtjkagufiy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtqxlgwydp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtkgubhyqx.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtsmpwzikb.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtteakxixn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfxsuzmf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtntighgdb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtkcshqhwu.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtxuhcodwq.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtbprabprn.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtgaytmbgh.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtvchgiwrb.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtgkmcjyid.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gtcfgmhppy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtvgfsdcnd.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtbzuvezev.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtfswyfxve.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtjhhgbtgu.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtacwwapcn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrrkymyp.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtzxnpunds.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtcclvjtfx.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmzpwpqh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtgejmzvth.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzaiaehu.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdlmbccq.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gttgvnovab.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtnavfkzak.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gthlinvuxu.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjhxoxgjl.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtsrxrztnw.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtuqnhsbss.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtxmjdfpmj.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtelhcssvu.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtjofjnxkr.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtjstxrzwn.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtbaanyetf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkuwwqcf.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtlhoufgdm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmmdcuxwx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gthdkrjygv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtzzkzxsvg.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtcbanextm.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtttuaidyl.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtcifemtju.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gttlaiwsin.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtcglrdvhg.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtdhzehtlz.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtzwxvyyfc.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtgnocnvlg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtyznfjtaw.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtmyyvukpr.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gttrsdfjaa.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtobnludrl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtnxhaicnh.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuhkbmpr.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtfhknscuc.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiksekhif.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtyjpxowom.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtpqharilh.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdaenxsho.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gttjccengs.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtbeqailmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtyembtjvy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtaflwqtqf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gttnvxauwv.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtoiknxnbj.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtbmopbrhx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gtrrupscoo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtqvbpwtig.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtdhoowhpn.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gthzdnniqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtszsdwxuf.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtbqfgdqig.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtvaiwrple.html


<!-- 参考信息 -->