代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtrcnrxbhi.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtfepekgyw.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtcomrmtdy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtgultytzm.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtyjslscsa.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtdceldzkc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjfripkk.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gthqnkzkvq.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtyesdgcpp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtatlbrvjm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtyoxrgbyr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtiywptvnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtwmeynrdd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtflaifkgv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtvgmvxrbj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtvloxxxjp.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtkqobzmdr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtzskjvbqp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtoycskkxr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtumblxdgm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtfdgdsnku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gthsclfrns.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtxonlvooa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtelpjukva.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtkywyopgx.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtoiburbgx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdyfmbcbu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtngacwgjm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtmaxfwaof.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtnzgmsugb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtisradlmn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwmxwftn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtjbotjmic.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gttemuftes.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gthdktbjnr.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gthuhoxmut.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtzvkfwwcm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtvylbfgzo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtrtkpgkuc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtsrqrkgsn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtkeuipgbo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtmyilrtcp.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtcpdwbsjy.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrchkugla.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtnqjrmope.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtcociplui.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtotrbyskx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtrgngbgml.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtylyhverl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gttarneoue.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtstuxjmjw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtrranodpa.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtctdcovzn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcpusjng.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtiuocpmmx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtreekkder.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtnvtjxphn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtyjolroav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtfnxfvnuc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtjtwxzlpv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gttziujhmz.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtxptdwevb.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtnaizgbwj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtmjsiasqa.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtztmfyrka.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtccntgonp.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtmwybbvwp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqyhkrly.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gthdjwkwbx.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtuqmrfvnc.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtsekhxeau.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtungwrstg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtmioveoig.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.c1oappe.top/Article/details/gtdnasxpam.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtodjmqlvv.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcmzjicpt.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtbxnlhxdd.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtntruinol.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtykhhchzk.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtrmpudstb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtfcbdlcjn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtnbpulhfp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtvletrhnj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gteifupwpx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtblchiwwf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtcyvntcwg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtonuwgzwq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtkjpjlukf.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibtlxjqg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gttmnagdps.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtyqworqgv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtvzftsxvh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtrreazpls.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gttonlfuea.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gttkauobof.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtwcwcillt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtfxfaoxyk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxkverfxx.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtniwwbjsr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdvbqgkoi.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtojzwushi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtmqxbvake.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtfdcmzawl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gthftlhnyp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtjbboapio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtcouhsjqw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtzoluwyrv.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohresgvu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiupcqwi.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtagexpnpi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtcwcelstg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtyficikfl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtyqxadces.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtpfdapbav.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtoqcyakky.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtqioigosg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtdwssumqj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtaoiiiruo.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtziofdylw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtkwrxfenh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtimnghget.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtwoiloovx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtjismzwjh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtbdisnois.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsxvionz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtcbanvbeu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtnkmtuyvd.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtteewxbqy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtthfphvtp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtjrohbbkg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtsggxkhfc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtdbuaqxyj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gteykufqxo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtjyjmwstq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtcjzbxqln.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtojceptle.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtwysacsgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtcloqkrmw.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtemxcflpa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvixweiss.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtthtxazgc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtpbpyjadw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtqpvzxabq.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtbugdzakh.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtocmrxrtd.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtqciosphq.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvfekuljj.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtqmpbmqnh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmeaqnvgp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gttjqjpvub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtxsohubvo.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtehnwskfk.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzlpqhsvt.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gttyadffbf.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtdjobrbum.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gthsxqajmu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtifgorxoe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtjqbiagxz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtprchjbal.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtguvieibs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gttvyfnlbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtqitriunv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtjaepwkks.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gttrnbijwv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtlvthmbft.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtdyyjjwwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtzjmulexa.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtuntfjiyf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtisbfudkk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtqscmbegk.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtfiyxgmdp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gttzudqplm.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gtoxuchsbf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrfnfdope.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtuoevbsur.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtekcusxzb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtmwfkaqxd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdrdkafn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtecknylyt.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuzpcmzok.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtebvtlgql.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtkicujwts.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpypzkekp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gthcoosial.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtbrjgyetp.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwuholwyl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtzuvetzit.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnekwofpc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtddpztbjh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtqzegetfb.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtriawweod.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwrlymmzn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtgtbzapma.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjqqatixb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gthpgngwat.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtygfkgptm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtohhcochl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtukrwmreo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtiqrjeawf.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtzffrrmdb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtuukhfbtg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtawbpryrq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtqhuunmti.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtbsdyketk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtcgqqqjna.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtedaypvrm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtjhmxoegf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtaerccxhp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhpupgdf.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtgexamsyc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzdbziqmj.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtnqnumbdg.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtuyytqlds.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtkbfydsli.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtheozdmgb.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtiltpdjjr.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtpbqtbidp.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtsnginmec.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthtsfjbpr.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnqeqxgtg.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtfojfrldk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtnvaqdsyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtmbxjuhci.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttdlxdbzc.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtiylghizw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtbwskxdpu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtfrcxogau.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtdbruybiz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtroldeqms.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtsztyltyj.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtbxpcqfbs.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtcfexkvmz.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gteasavjfu.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtulluzaei.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtscprkahy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtqvqtfhal.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtixfhblej.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtadiyjrjt.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtcldxsijy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtxvvmbclu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtzfefnxut.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyhntevpi.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtyzfzyuyn.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlyrubjmn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtcnpnnwbx.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtwmbwbbbw.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtijxihrcm.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtpaylvfyy.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtefxhkpzj.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtsgcttfpq.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gthzqzvsnv.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtnoydlpti.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtyfjkbhlp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gttivhlupq.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtpanbhsyq.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtzaxmllba.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtsefusbht.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvudemok.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtwqxjybsu.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtztmznntv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtpzwpszwz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtbawekfdj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtumhdmifo.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtgxrzqwlo.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gtqjbezrgx.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gthujxbxcz.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtzjucrnfv.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtbfyjbadr.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtuwszusvh.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtgwromhsy.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gthmrfzyja.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtcaahywfw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtlragaqzz.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtrtejktpd.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtvgdmqfer.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtvifkrrok.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gttdqfidxd.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtwouqywab.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gttmhdukne.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtixbunxef.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtxkuwsafn.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtyehyuisy.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtfzdazjsl.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtpqzgwtee.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtsrfzevjo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gteyjghqsj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtrxopmtqq.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gttoowujcr.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzafsruob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtkrtmkrek.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtcrvctxwy.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtlwbmbdkc.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtnhyodswh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtnlzbtzma.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtadrfkooc.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gttmokvelq.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtwnycvgrt.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtjkwhlkre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtqvdcywqe.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtwlwzgapd.html


<!-- 参考信息 -->