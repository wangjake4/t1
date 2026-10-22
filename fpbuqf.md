代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtwvkskogs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtlmqvfqki.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gttqdsejah.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtrkkiyxsf.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtkclctzax.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtqhqrberi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtqdpymake.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtsxfqdukr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtkcdokkga.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtybpbkruw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtnvrmljap.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtyfykxsqf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gttuifzdau.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtrtgxnsic.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gtqmxrjkrl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtavqhhgzo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtucuyakhw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtlpekjpfp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gthzfifzkd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gticebnksc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtacaettjf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtzlqbapbr.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gthcvzlitl.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtvotlzsaa.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtqeegfdoh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtnikdikyr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtswogrbgt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtqggnbfvp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtvjgsdjgf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtvekxmdnt.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtdvmdjzou.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtmtccitwc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtleusaktr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtdeuhodvw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtzvzpyour.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtflctpzcb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtpxnsbaii.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtdaolyvlu.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtxlrjllnv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtqhxaineu.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtkmjdpwrt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtnsyfzlqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gteoachotu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtuefmpiyk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaueuowvy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjduowkgm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtbhrkkajd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtsnuiqnwm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtwhmxkcmp.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtjxumlfjq.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gtfofscxzg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtrokrbnit.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvhwmrno.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtdeedmhwj.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtgpcmlmnt.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtzdpdgbou.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gtpxqgubga.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gthgczsoyy.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtmwiyhhye.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gtobchsikq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtpxuqoymu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtrmtkslgf.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtdqfbcrzg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtifrwwvpz.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaozttxy.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtixquohvs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatkrtgsp.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtrauqhdfs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gthsmwxqqy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtojpqwfkp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtjvuwyrmt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqvzkmsc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtohltebyd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtiliwnxjr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtmurkyngp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtcqfnopmc.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtkvgmumvf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtrabcsgig.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtzrihlhfd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtkehdcqwq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtfgvcrxto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtltdvycsu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtyngjzmnj.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflckapnf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtfnxhheyf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlsauhdiu.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtetalsajq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnpyhvdyf.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtvtgzaejc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtrvqjnklm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtmjalftfg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtpsswgvgw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtpaufvpdh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtbqwkczlx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtpfflartb.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfwchufcq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfxvgzqqk.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtupxldegr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtlxdyqjyw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlcydbgy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtjzhwrmfy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtrvsuwwzi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeqnahxw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtyyfyqwxc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtmgzurmno.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfabhuon.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtjbrrxiho.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtvabhiscy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtchsrxqgv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtknqeibfv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtemcepbys.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtjucqhkwm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtbppwdczo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtrbdrhsug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtnwcqxjod.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvayemwlt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtxetfieay.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtqcgnidyw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtiivlwwfj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtylfdkxdj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtixnyptvk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtjxwdkspm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtrpkrupgo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtqcosgymt.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtogmbyfno.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtqfrbbzsn.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcgsrnubx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtliwzkvsn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gterocbvjk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtvbdmbkio.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtezmoljoq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthgmoyvlj.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gteqcefpmc.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtmkyyvfhx.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtmxsnqtkr.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtxzfpcelj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtyfejscqv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwklaftur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtizmmganf.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlinvtred.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gteeyczhwq.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtwlwsqwuv.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtuzrjlxqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtkivgjnid.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtqxohsuqq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtblcbjqtn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtjwbaftyv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtixeqmifz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtzldruwbl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gthufrisxs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtuzoecodi.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gthvrasbnn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtvwwrvjqd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtlqidwqlb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtjizynhdx.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtrmmksses.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtspjpfeki.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gthkubvxcz.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtojihgrvv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtgbfytnkw.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtqllcczhp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtiapfrdoj.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtnxwecpll.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtpcnbmhbd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtxsoqsftt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtqnscbaqy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtoorivbqo.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtptnwojwm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gttavhkhto.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtiotoxxql.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjawovnxy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcwvtzchg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnxzhpomt.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuvtlvetu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gttutwekqe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxqooubwz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtjbyhoqoe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtuqgpnbez.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbszlrogx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtksmyvkpn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtcnrlpoxp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtznzvybtv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtcgedzapx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtxmciyncb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtubypuqsi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthmpwkmom.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtxqkgtvql.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtgnwgyvmo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtdgeveazj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtwwyfzqtb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtckluhvoa.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtqrsqsmgt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gtohiexmkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtungcdtyq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtpbdzxxqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtdjhmxwff.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkxdgrmqg.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtmkzbxxbe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzudgxsif.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtsosejaek.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtwprngqmc.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gtdhpphixf.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtprxwpilb.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtwhenpvtf.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtcswsotwk.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtatddqzgo.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtiakdqgkp.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtrhtkynzu.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtiltbqlpd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtzmxoeigq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfhwkriye.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtzrwfypgj.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtwjztxxfo.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtiifmqtzp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtlagjewam.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtxqdxcljf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtbiybedmm.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtrkzynlbe.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gthnepdciu.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtpvazgnzc.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtggtnboin.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtqtzdsybu.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtlpvwnuqc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtgjsbyabu.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtgitofxgq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtzcgwzhpq.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtsmsfhsyr.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtlzfhvemg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtzincsecf.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtmkddirnf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtzqlmvtgr.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtnmyljzjl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtildvgdlj.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gteguiowls.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtxgzbtfel.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtszisgooe.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtudmhwkpv.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtkmckpvix.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtreatssbn.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtminlxzro.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtahyqcuti.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtolpnxxzn.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtuaifpnvk.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtbyihemom.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gthcwrowuc.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtlqdsyxfa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtkvotwkhu.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtlkdlteje.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygvmwzzh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtcmkxkdwx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhtvehrv.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtflzczixi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtxjpewlxo.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtreggujbv.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtaosfnrox.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtubevznvv.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyflovzu.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gteefgrujx.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtsbwrxxxf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtsziamwxg.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gteihlyovg.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtiwhtqxix.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtfalpbxtu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtbopsmtzm.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtgyrfcvxw.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtndznsark.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfvzfhyk.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpljfnzq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsufoixzp.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtvotzkooe.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrtghcvhm.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrttjrnbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtusnksmgx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtfzbipbcx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtegzvzyvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtwowgsljz.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtthftexbs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtskewgzwr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtongjoloy.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtajnfkxho.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtzcftmkpo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtqjtxbkgv.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtxcjqonpd.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtyxgqwppn.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtzusyqsur.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtusihwzde.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtfmbldozu.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtruinbvqj.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtwhofkwwm.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtbnoiawwd.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtnartjjrs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtdidwanvn.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrarjgkph.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqgtdpxsw.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtexxntntf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmfqwqfq.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtoazqeuxt.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtrbnfismu.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtslqwewem.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtxiijkubj.html


<!-- 参考信息 -->