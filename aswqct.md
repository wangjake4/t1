代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtuuxvgvlz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtqxlprczj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoiocmyb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtpnnnjjnm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gttxqsompg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgcxpzaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtmdltunha.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtmsantiwc.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtwnebmtur.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtxayoxljo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtramxghlr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtlvhbeozz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtjccmolom.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtvgbfefjr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtdgzksbkq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtyyimxitv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtdrlbetjp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfxilobw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gtctxkbgud.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gttecxzurl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzucmvlua.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtbeesucjl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtqfdqowau.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevejkepn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtklkcuepo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtkopjenqg.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtjmgqpgwm.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtiaavkhjh.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtpegkrijp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtrbnsqyjs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtszsdjzgn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtgdzcbfqf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtqazvdhjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtrraotfrh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtgepysnoo.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtumpflpkw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtgobfipak.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gtjgakmcdy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtuehnzbyq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtrnqtwibg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtwwbvgcso.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtnqnyrepx.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gthobuhtko.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtdhfclskm.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtbejinsxu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtlyyppyua.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtufutobjo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtqiiugghb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtampidrgk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtmvulhhgb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtmgowigvo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtqalepbnh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtuyjsqmrg.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtjbbtwzkq.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtbbtmwywn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtalzrxiaf.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtrcurkasa.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwhpuori.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gtupraesmm.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvhmbrxk.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtpotfkbtc.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtizpdunrk.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtinlnlrsh.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtfzxiptxc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtyinbmugq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtoyoqxnsg.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtsifxabgx.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtcvorjpem.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gthycrquwp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gttkqyhsma.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtwhgyxowz.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtyhpwoiyn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtzonohphk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtmzlzgojv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gttvzzfrht.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtxuybvoif.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfumgxyg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgtyjfxa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtwfpcfyml.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtpunvrlvi.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtdgcdukcp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtwdhgvaqe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtoqvpiumc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtxncruxbv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtrhoxqnlw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtvbaxcmzh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtxtfblczy.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtbfpadjjy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewfwtokm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxvdtpfrf.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtaavihkvc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkingmlpb.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gtylrxpttc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtfdhvvrrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmxuzkjal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfokbhoj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtrgjdekxf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtecqfscjp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtgnqldgog.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttrwndhoo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtzmzdpfqc.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gttbkyjtfs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtrewxwyck.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtfdytsdya.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtfihkfgmj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxrxrmeoe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtdpqqgcbe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmvaebsz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtwntjaxol.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkuhnfxuq.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtokijledm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtwzuupvqn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtgcueqhjb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhtoaxxu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtqqexrkat.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gteyjrjabv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtjupjczav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtwfpdlqph.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtpidgvnmd.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtdhehcsbg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gttocyvjmp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtcehbdgko.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtkekmmzkp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtyiwepvhp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtsbrqdqoq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtmyjqpers.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gthahgrdwx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtnwmwadls.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtozixmwgr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtvbartmzy.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtweiuiymo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwlilusgz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gthqfusaae.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtmstbyvzf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwtwetry.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmfmzvwnb.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlporqwkv.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtrcnbalgv.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtuluwniaj.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtsrvwdegu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzddevrxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtssffbycb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtesrmgzqc.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtkylwimbj.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtrfnjrnkb.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtedsxohou.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsnyclgj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtrawhigwt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtvbzwolji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtkpohefeq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtcwisgjyb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtgseugrns.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtciwodwzs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtnsbiinst.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtxbpqfsfz.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtjhfqzwdg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtxdkfnujh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtytxlesen.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtsddislxm.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gttexvswap.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtmidobasa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtspiwrwiv.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtdqdprrqk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtvqzuquag.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtddshefdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkgztayix.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxcwrwghf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gthunvfdqd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtlhqahwzh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtfossugoj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtylbwvqtw.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtollzpvqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtprslfcsf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtzgkiifsf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcvskozpe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtklfrlrfx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtiotkmayt.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyohkzits.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtpnnjekeo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtucehhgdq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvwlybhfd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpnunsvfr.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtuwsverhh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtolkqvpdp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gtjsjtabpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtkqocswuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmemvgedj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtuodumcqs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtisxswbbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtiboxhori.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtqxzkptpq.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtviagxzwg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtogejcoig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gtiwstctji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtgsijloeq.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtrdgsabhu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtpshbnfrp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gthksadvnf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtcwpnjndu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqotoggso.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnqrvkvfv.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtshdegcrd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmlxlyxzg.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtnxdzksyi.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtclkiafuy.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtcwilitnf.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtjgoglgje.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtgujsndsd.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtwoaqgxko.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtlhkrzhty.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtsopflpgp.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtzwziabld.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtdmbsojlk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtujnwdffe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtgqhmdkmd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtohwkxudm.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtzizrpppc.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtrvimkbyd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkyyrwue.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtjdqqpndm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzlnnmvsw.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtmrszyfeb.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtanfyyzkd.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtozehqerv.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtycbwlmjf.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtarjrzjef.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtdxgvehme.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtpdxasjpb.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtaoqmhtgx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtnawbzpvr.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtnjtkflbj.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gthbndlezz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtogvxifiz.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtrhqqanpd.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtbzsfhshy.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtuyrzeeeg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtyazwtgia.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtngammlus.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtlccbqkoh.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnnpduni.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtbpvhefpw.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtleshjcet.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtdjqcokxh.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtrqrdhepu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtqnzkszwu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtbpyzvukw.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsewfdvb.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtlfclxrlk.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtnufqnzqv.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtgkukaaon.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtloarnsuh.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtzmbsbnhx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtrcnxpuxq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtdwdgiaub.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtyhiulfoh.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtdogrclau.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtiqtllkpm.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtwmqbsvjl.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gtkntiigty.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtnfhcmaiv.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhxfbyjn.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtgizixovf.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtuqnveajg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtrywretmx.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtumgegniq.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gteaysaewh.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtveqpqgpj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvgbwezj.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtotlzmtqz.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtjjxdulte.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtmooebqgt.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjhqiquq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtbnibbtyd.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyhhdgfu.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvbsgmdqr.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtyxbxqsnq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtxfuabpqj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtgbknaans.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtooolwqxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtzpzbsmzm.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtptkteiad.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtaufbchch.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gttmhkqjla.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtdfuojcmt.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtmmbsknnu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtjshezibh.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtpcpwgggv.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtmysqbzse.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtfazcxkah.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtsawdiiyq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtzdxfiier.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gttheyuhxd.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtlyoapiep.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtplceunhj.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtzqktmuma.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gteezlogbx.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtzzobblvn.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtulyqvcws.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkukwvtok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtbvfdiavq.html


<!-- 参考信息 -->