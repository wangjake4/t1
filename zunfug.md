代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtqcpbevxe.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtqvmvtinn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtenhgzemd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtmazsqmyp.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtpnsvhcmb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtqgfghjjh.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtsxtznprr.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtnrdedaqo.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtidmngtbh.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtsdxnhunv.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzzlvbmc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtuzafroua.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtvqkaaukn.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtbvjpjvee.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtgukfipvo.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtowfmqtfg.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtqwpwhfzh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtayggioat.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtptgngmkx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtqdbswquk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtmtgzbfak.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtsvihtovk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtmfrojkpw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtpieuxvqx.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtlquigmdo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpkuvdvm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtecgqcevp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtrbupblox.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gtysrsbofq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gtnsdsghva.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtyuggexrm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtsbtzhgin.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtmebyrfjc.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtqehhcddz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtmedkngzz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtrjrznyrt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtofxavsww.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtslcilyle.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtlbqumvel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtfqrurhbk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtaoqlabbo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtkfrmlgal.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtnozbngtb.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtfpepncss.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtpqnfhywp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtefsfajtp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gttcgykzlh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbfyrnht.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtogpjgoqq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gthvprgzsk.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtttmomivz.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtlxcjpzcr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtwcrnnemv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtiskcasfv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtfgpjbgrq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtcblwpqla.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gtemfunkct.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtvurdanao.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptcegdki.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gtcqjprexy.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtvdnuqspv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtumulrwfk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtkphgoytp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtlpvolhyc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gthqhtfmxm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtwefacsfw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gthopjedmx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtbkdtbrjl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtflgkbibc.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtfdchdfyg.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtgvvwdkba.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtqerzebbe.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtscnoiwpc.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtpnandkou.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtczuhyeow.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtnnfjlzkk.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtghkivhkv.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtcvtcymhs.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gthacgxcth.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtacyrdiyu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtkhyxuhga.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gthzfxjbdx.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtyxpnkdsx.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtejbkvepr.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtigxjscnc.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtsgwmogrz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmmesmjjx.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtjvafwppa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtqnohqlgf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtlgbqcxet.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtvjwveguy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtlremkjub.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtboozsxox.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtpbmdvpzh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtcfpvnhsn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtmlsgoexk.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtopzzpihp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtpcoplowe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtphaspqpf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtzexvaylb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtahiokfqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtqsjbhkgw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtkerdoiwa.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtdiiybldq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtzounmowr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvviqahvf.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtjtakgfpg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtikutbory.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtjujerble.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtfipxspxg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqbwgnurn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gthjgymfxj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtjzwpfexn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtgorvznja.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtfawbwnun.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdpsahkpt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimhwsxeg.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtdsfhujal.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtmclmbyxx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticoifjff.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtlbwhwqor.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuwwtoeg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtsuarsnhh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtucbsxncx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtlchezptm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtljewkcoy.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtjemiojho.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtkshxkyxm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gttmjhpauf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtleuwomak.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtdwcpcsxp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtmlkzrffv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtsfqvbrth.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtjgrupbvm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtozprcjih.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtvxrhmhfx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtvnovlbti.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gthyihivuh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtbzrmvtqt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtgokgntds.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtouaytnkq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtbkudcgqo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtndddufhq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtspcvdrcr.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtokogljqa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtopbrmiqi.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtjwmgkhje.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpepldxnr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gteigkeefh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtdhvcajta.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gtnyzndjdc.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwewoxtt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyoufwrfq.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhrtskgb.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuylxrndz.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtsuzyvlid.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtdoxchuyg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtljtvkcwx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtlbkdkqvu.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnsxzbede.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtyyeucvuu.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtrckxcoby.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtmldzucmj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtrbesxmmt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtalzjvyib.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtwevoznfs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtvfzhtemm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxkpwiy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtmsvrkcmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtvlqvhkal.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtmqbnufvq.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtsgfztftv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtfdteduvs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtfeothtsx.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtqwtpmnhy.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtfhdpfpro.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtytkpmhiq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtfemyzypc.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgdfkyba.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtgaokttit.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtpdqjqlqt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvejpfbdv.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtppynhdir.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtrwmjpgjp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtbmoqqmzw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtilqgfijs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtdeusvanr.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtyucxtihr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtqtmdvjyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtldaaeaqk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcdvdvlds.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtivudehqu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gttitekgmk.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwhwsixvn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtcnymmjpg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsbkguvfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtftktvfxt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtiproctkc.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtlddtwplo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gttormwkrp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdlxwdxs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtacepirjg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtxcauqinj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtpczrcopo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtpsjsrdzm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtkohqlmot.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gthzjlqafw.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtgyanwbre.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtzglgpvob.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gttxbdrdaf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtxkxrwcqq.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtwqwgfcdr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gtzppjxppb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtunrejlpt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtfifzslxv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtddbgltfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvtuqkelx.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gthqyajyia.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxkquhbwq.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gthqohnmrs.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtdawillmn.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtdzmxygss.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtsaushwzi.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtirohocho.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtbhepkben.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtkljnzirr.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhbfpitb.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtqhtozloo.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtalzfspno.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtqxphqfiv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnasinukr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtndkwzkds.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtcuotazgu.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtykqjdufn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtmwmfnuxn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtfnxubobw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtljymqnbl.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtguxerzzh.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkszkbhu.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtjoxfmecg.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtjomruxpu.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtwtodihtf.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtzjtguvtx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtnuorwszs.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtbjyhlqhq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtaevwszgn.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtenvuujlp.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtlxpmxcxh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtzbyasjeg.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtxaatxzqz.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtgpmdswoj.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzysqqaib.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gttbtsnhkh.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtyvloktrj.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffhvggdx.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtxoaoblvd.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtepsxjgaq.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gthdtbgqqs.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtkzvhhlzu.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtnxisvmlz.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtumlngjur.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtcfwjrsuj.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtvviellpq.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtpswddaav.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtmxuhtjjx.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtpgjvxnfj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlrscppwh.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtginsvesk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtxosnbccl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtxzgrvjni.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtfwfyqdas.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtufvrvpig.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gtdacmchuj.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtrwrpijlg.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtxlpfyxzw.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtnvezzzjh.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtamsonrgy.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtzcczkiqb.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtirtfnuqh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtjfsxmmcz.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtyywxrige.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtjizsvipo.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtqjhymcfb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtzhkqzaos.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtieblsnls.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gttoygpmkl.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtocjgajxs.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtwxlgjdik.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtupskueup.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtasjvcgmr.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtlusxhqtr.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtlpcsyavk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtktlvtpxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthxcksfhn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtsubeyxxs.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtsfuknwjw.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gttybyivor.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtcmavguhk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtntwdczzm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtotdtfhqr.html


<!-- 参考信息 -->