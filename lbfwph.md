代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtqdiebkuu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gtfoiliuiq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeyruvsl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtatqbyndb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtwilaxwbm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtyndgiesm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtlutrslan.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtrtnyzewn.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtdisfbwyv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtpqjzbnrg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtjubqswbl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtyhmdiiwo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtdqtwzaou.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtstdqqsol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtsjctavmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtyurnsfxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtyjpghibc.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtopuekajg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtgjpswtus.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtqtguznmg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtrzaozlqo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtnjgquwsu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtxjbksiel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqnrhvhq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtxtgsxfku.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtcfxkwypb.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewgqezrt.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtzokfgtbd.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtrvucelcj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gttpdxehok.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbqhrejp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtzebwhqkq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtcdwbchhp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtixakdlpy.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gthiyqjehp.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtshbknoxm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtngqupixl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gtqqaqrkgg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtuxzhdawa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtbsqepvgz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtzbcqydkb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtwtvlkype.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gthnkkzhdr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtiwqlivmr.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtwbgeuwtd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gthugyhbag.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtwxvusgho.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtnuzxpcrj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gthxecwjiy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtktykggxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtyhcnpnsi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtrwtguuuo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtwvjfgqrk.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtnidlatze.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtoovfevgk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtaeuqjnrv.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtspaqpyhd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtiskaulpl.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtkedkzbcc.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtcbyfuwje.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtbqgpcylc.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtbzeriqpa.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtubqrikvw.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtvowjpptf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtwgevvpdj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsfkweypo.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtkysqqkrr.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtlvbhumsw.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtijzgsqqf.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtpitbotdb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcmqfygch.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtqnpptaww.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtdretpidk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtptmkcgdr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtwshlkzky.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtvfozclnk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtidtwtjjp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gttqabkbjy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtmosthdlc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtnekfrtlz.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtdtpwnohi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtmoourlgg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtfhopelgj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtbafqblvh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtwhuyewax.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtuuumeakr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtkswmnlnl.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtsyicjxmy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamdtdvwv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfbveiboo.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtvpjecpgq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfixpobkq.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtelejuntw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtyyrucxwv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtywdoeqfd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtzjwteset.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtghlrgvii.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtydekgbcb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gteimdqalm.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbdtztljt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpblettl.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtdhelgb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtmgvefkqs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtlxlsrxkl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtvbyqkppw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtfjnjbhat.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnazzposy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtrfqyfyic.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gtpmubjxgg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtzywkonif.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtcetsyaki.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtdouemudi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtubemydah.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtubrwmtkh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtubpfzrkg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtdjpdatrw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtvrxczrsy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhuwmbhr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtuwgpvlei.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtbyhferdb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtxbkplcpt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtxzdolfxd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtmfuflz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtczcnerlr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtktxxtfdp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gthofgxzos.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtltxevres.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtsnnnydic.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtgqagssmc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtpzjmnand.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvtfaouyg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtadysjbum.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtiyvcrjfr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtfvmmtjno.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtpworzirp.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtizneyjry.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxdifllql.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtsvwmdpjr.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtasqdqlaz.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtebywonpg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqrnhoscq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbnrvewis.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpunkbssi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkqbmuuku.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtuhrtoeta.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtjmrolonn.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtmxdigsue.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gttwkowuox.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gttnznjshv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtbwveubza.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtejnxihay.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtzdmcuygg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtqpxahhrm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtywfrpxhv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrxnxofh.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtenzteurd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtuyukaqeb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtdwttznxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtmtlazcax.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtxayepelj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gthjampplz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtchifidhn.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtxbkgmjqs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtkgeszcgi.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtcnomytlz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtljzcbhtl.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gttlnttkus.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gttauttwqs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtgscganto.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gttsdhpdvt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtgmcgpbxi.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtoiiqecgm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtuxphwjkl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtirpobnjg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpugefpen.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxlutyidi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgpmbbbjb.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtsrcpoywn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtcrvhevmr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthjjagjmy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjxmirlzs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmarpggju.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gthubnbjox.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcfbzgrea.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbxulqpn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtfdfwmkch.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gttdujqifu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtmxqccwdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtfopfiktn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgatmoqaz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtsjbynczz.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtqyklxudp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gtymuskxig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtbzkcqseb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gthshiiedu.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtdylkuouy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gthappffsa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtgclzzmbm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhdrnmrd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtqmtcffzn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtiytvpbjb.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gthcmvtzzz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgvxmmcrd.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gteazqywzo.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtseynghfo.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtxckiywzu.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtwkstozvo.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtctslnvrm.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gthfyzhzkn.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnxkimsb.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtbrxqrauy.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtcntzmate.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtgmebqsck.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtkldaiynv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgbabdnnl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtrzoiscpt.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzfyaleie.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtsfbuzzhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtwieivvrv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtcrtkxxdh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtdnhfoeuv.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtxvrijeez.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gthfnsskih.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtaadhbzsx.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtlekxcezm.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gtmzmpmfwg.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtilncxzia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gttffwhihp.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtikmcpeve.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtsgwrtugq.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtllvudkdf.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtrtlvvnmu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtcmdxktdj.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtngpqpjdj.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtjyskokhj.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtfsxxtpry.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtexccznwc.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtiofofdhz.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtbdalcxhh.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtdblzxeeu.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtholuajln.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtucceiyzy.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtipouuaoe.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtormvqfad.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtgomrngol.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtnwgciwxp.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtsqoqvwow.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtkuxulxlj.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtwhnbkwdp.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtgrkxyoob.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtrutxnioq.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxzvziyw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtmwokxfrd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkugzfayp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtvrxovyqi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqhbjqgh.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gthgijvzna.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtypclgmvt.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeyjivbo.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtbpaztzxm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtnzqqzcak.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtfrgbmfwk.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtunxswiyk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtqudwruih.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtrixycume.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtezlxogcv.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtbzoabzar.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtwlmutaxl.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtyupfancb.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtqnywgwrg.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtemcbqmdk.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtywsghucq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtmeotyyli.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtbzmgynag.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoeohlhmx.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gttdmlbmgx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtjwdcmtbs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtxxisumkn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gttqbqakai.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtwxbnzrgf.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtxchwqkxr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtqrvvzhfw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtovswqxko.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtawzzwwky.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtuceblpnp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtndctcugx.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtdgggyqik.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtltboijhg.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtjbtnylkh.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtyikmeyif.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtmejylfgy.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtnanlvwpx.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtzjgrmkpq.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gthvbmolso.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtdaxwlyka.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtizndnhlc.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtzhgdowmq.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtvgdlkpcg.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtarntepzk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtywnbpdfm.html


<!-- 参考信息 -->