代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtuxepmnzk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwhnrmmr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtgtbjwufk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtzdwcltaj.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtmqcnzrvz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtenvbfrbp.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtxezqnncp.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtnxfldqdq.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gtekmngsla.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugetoscb.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtwdtputpg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtqakswckp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgqpyush.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtdnhovupo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtfaijnpxu.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtmjsamcji.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtrncmrdkg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtvvgdrjiy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtwganvotc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqrzixhmc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtfwxcffmt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtkyukizca.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtjazhdfry.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gtouibmevb.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gtcygfxmnu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtroyqniqx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtbdysbhjb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtobqjoynn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtywmzhqwm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtyikpjsig.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtkdblzzpj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtzlhklecb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtukodhlqx.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtoyrhyyyy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjbebrsy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtmtxmdiuz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gthpdkoiwx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtjxkcjnut.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtrkqwwqof.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoshthmqq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtqhfffcih.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtydqwymgj.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtnaonvlgu.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtbeqevakl.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtuvauvznr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtmsuntkzu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtylrblvuc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtosmucieh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtqisxajqe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtfjucxbst.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtpblzppox.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtccllqnxe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtzgirmbft.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtskoczour.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtqxdebgqy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtyawjnksl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtkwxcdqwo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtnauxzjda.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtowatusaj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtsctivnpp.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gttutbxjpc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtbcpfizjd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtkijqhqfp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtfqrvrazs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtpfiwqjgb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtbwzqslhq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtphrvvvsf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtqdiebtxu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtvcmejhcr.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtoqrgnjjk.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtfttkqzcv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtzwbhkssm.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtgahhnvne.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gthywmmmoj.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gthxvrtnyq.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtbpnbrmmm.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtbjaacyzp.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gteehmqwbf.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtnzlrdvzo.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gtububyztk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtokathlnp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdxsyzczx.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gthteehwls.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtpxcvdwwq.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtcdyzcexb.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtojzxkigz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtucbavclu.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gtxogchdtg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtnzcyfftt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtjtcykeys.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtkhvajwdq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtvxekgkug.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtwfebgnmy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtwrmlhcqp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtinckkiti.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtkdhswtmh.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtjxyhqolx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gthmsgetnv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtvdbxkfba.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtmuxojyew.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtempmgoiz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtvoflzuwu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtdkynjqkt.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtohrnpwxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtgirabeys.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtykkfmvhj.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtldwscfex.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfusuhlts.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtmgqpjeoj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtrpzpzmob.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gttcxlpfex.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtdvwkqdof.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtsxjrutqx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtlekfhhor.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtzpyqampd.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gthrzortmx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksisfcgl.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtkidrmhir.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtcmjqvfxg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtagesawtc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmqzolwmp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtlvxjhxkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtabixilag.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtbdfluydr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtrzuallco.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtvfcaurok.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtazpthmcc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gthtxbncbz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtkzcdbnbs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtetpapofs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtibgmibnz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtnyzhhtgv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtpewyrtcj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gtgipjjsox.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gthduhzlsx.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtztxhhrlh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gtoaimhcyn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtdmnlblyo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtivvbtfsx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtwdxvxqxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtlapywjkc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtqavxhljp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjobegwu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtakeiiojk.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtxovhbsde.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtdekblaee.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtdmuruiew.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtcselwnrr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtiqydrinb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfezdvah.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtcqupjlev.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfreseoqb.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkylofaih.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtsavjwdbr.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtktlcwckh.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtyeylcjyp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfaqiywxc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrdtgxcrg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtmzjyvmkb.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqfrjbgwr.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtesmccsom.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtuvpetucr.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtimjizyxo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtjvfcsnju.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtvqovhrxd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtjhsrpbbt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtzrjumudg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtyffglzyx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtjboeojhk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtrpbntzbg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtttdfkilk.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtrvnjslnf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttracoals.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtdgpgdfsi.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtsnbatyxv.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtipihczdl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtqcptsoxk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtteyycovk.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtugmuapfd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gteaybswel.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtzeigmnfv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtrgeeqlup.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtbixoosqh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtklgdybze.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtmgvhinln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtuutnnteb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtulrfjoed.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvggsdnrc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gtaykcgaaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtitdsugli.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtmthbtzpo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtzahtuynk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkuejszsz.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthjhevelq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtnochawkl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtelsvbnqr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxhzhvhxq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwrhoezrm.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtdykrwflk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtvwznxjdo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtrxbwwovp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtodqfwpal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtghlxbzrr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtxudxllml.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gttdpeyaej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlrgfkvtx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gteqcrzgua.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtaiuluioh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvutsmiol.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtoqpfrluq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtgcejtpwq.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtizkhjcna.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtwyaochyx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtjxjimjzl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtebstazek.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtnsuotdbb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmxmebwjj.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtcglxorei.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtopelnasl.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtpbnpkhpw.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtxzscyhnb.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtlfsgdhyi.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtqpagojjm.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtaojmvgjt.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtqfwkifdi.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtfvsiijpj.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtirpijpcr.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtmwimfqfc.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtequpspde.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtkknuyrhg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtvwthukfh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtewerkemd.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gteaxforhu.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtnfbdcnsf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtcobvatik.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtairnjwcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gttgckdhrc.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtvzzbvljw.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtsmwoyqdf.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtsnntzpsw.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtksykqrdp.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtmyevyfei.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtncxjeccn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtcfpdmbvo.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuanpocxf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtxqremhiq.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtnobnditz.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtdjnpalms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtzdatlror.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmpedxmif.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtxklqfdnc.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtemoidiee.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gthcpwiril.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtbrxpdbcq.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtethhkuxb.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwqndpsx.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtfannewcg.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtnfywdltc.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtvdcwsxcv.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gttgzrutoe.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtchkmaijv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtqrdakgkw.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtrdveflde.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtqhruuafn.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtajqavxuz.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtmezihjqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtranglqkj.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtgujbkjhd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtplfazzlh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gterxklouy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtpglljqki.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtqxjilavu.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gthttiawho.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtexnvypbz.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtxnrdeafk.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtfwmpevnw.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghmtacro.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtvaorpvwz.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtrozakhad.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtsegkknpe.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtacmagrlx.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtcxdmqnga.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtekuzabbm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtvqezhxgc.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gthbplttfy.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtdtyftbvr.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtcuvqykcn.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtewkwsjba.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtqsyopniw.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtoktokerf.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtjiuzcgay.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtffchtunp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtedtlyzhv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtmwsafudf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtvzomxlqh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtceuwpiqa.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtlwhuvnul.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtyjkvxavu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtmyexfmwf.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtlcqgzsci.html


<!-- 参考信息 -->