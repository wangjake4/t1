代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtidplhbza.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gtwudxulxb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtbjcjyfup.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtbhbruzan.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtltyijfuo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdkuvccj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtrjtmdymc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtdhizbxnt.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtapnjaxni.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtbcopudnb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtqttjmdas.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtbyxqfada.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtoizplqpj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtpulgqhfs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtngryptnf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtgdtegvfv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtibtonsmu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtoexiysuv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gttxcfqpqa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtidbttwgv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgmomdlt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafxjdymd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtwfujwucq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtiuonrryx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtpafcuvwy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaiqulau.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtrepqthbp.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtlfcpqjqs.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtevcjrmyg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtcmcitany.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtqgykubyd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtglnlvjzy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtddhpjmyx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtyrgsbrwx.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtlbirsjsc.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtgcgaicbc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gttcgkqwyf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtuimwmvbk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtjaesvust.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtaheoyund.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtezuhifsi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtopppblip.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gttvtbxjgc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtsmirvdjo.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtfeeksunb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtnjqptyzz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtqtkvgemb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gteykowhzr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtcpvftkfp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwbfkwmk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtaxekjkhl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqkuxxmg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtotqpspzt.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtsjdjucwr.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtgpjqsiba.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtxopfweng.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtcayafvxx.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtwgentxxr.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gthlbqyteh.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtkhcfflcu.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtmeofbjcy.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtavqfvlky.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtgqgnzidh.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtqczzsnxo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtndyakgbu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtogzelflw.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtbwnfrkxm.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtckwdoodf.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyncyytlx.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gttpxkrtmp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxchqimij.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtbtouhlfz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtrcegmujw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtfdtyzmwq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gthrqmvlbi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtylgqiqdn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtwucligbb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtocdpddcw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gttjucwprd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtnibugfmy.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtljisnwgs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gttryhlxae.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtmljvkzng.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtywsgtrtl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtcurboyue.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtbrceyvdo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtbgbovjah.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gteqkrvmfc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmpnpkfo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnxslhhfu.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtpjfdbcgd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlnrhkwyi.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtrfjhwntk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtvrxyzums.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtylujeidk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtaysmvurz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gthxzkubvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtvialvtqe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtuvdgfbxk.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtlmsvfdxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxnqrxjln.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtoccjpgub.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtcwbeyzhj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtldvolxgl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjpmybxnb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdkxzwsrp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtuogsmhlv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtwcapcxpz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtqowpvgzc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gttjxsfzur.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gthesashvn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtnldklbch.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gttfbeuvbd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gttrdvqdfj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtwemrgifz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtmqkfmfqk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gthwqctmcg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtbcdibftf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtpvmjxeit.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtsenvgdro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtufzyurmv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtmmamblwc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtgqaxlhib.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtiveuqnyn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtbqslqawu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtrgcslnaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtmyegjucp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtkuqjbemw.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtwloccoxt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtqkellagn.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpydmsape.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gttwweryot.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjcmkbnfm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtjmjoxawp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtdlqgfgol.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttkpxjgjk.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtdslvpuek.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtqxtbkqaw.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkhnwplty.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmxhcekdo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtktejymrn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttxnkyzgu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtktumeijb.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlpmzcvwp.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgzeiimow.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttgmusszw.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtibqoyynj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtgasmftuj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtxiahxhlt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtskhljuau.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtlfojsuyu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtehpnaamj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgehfbrn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtrxyoqqob.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtpswejuje.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gthtqkrlic.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtkaoaotqs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gtokrvyprt.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gttemunlbi.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtqozmzdhg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtvyxtnrvw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtaimpdhxy.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtigmariru.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtsyqomhhd.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtbbnumuct.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtibjqloyb.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvifawjwm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtrfgmipqp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtxckaryzj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtzuncytmn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtrirsjtbb.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvqgsbfov.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtrvdiukpm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtsboizqkv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthmdwftdf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtupsophoh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtqjxqkoty.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgpcvhqmi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtyxcqbioj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxfbmtnyv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsrekzlxw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmszhbryg.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtaipulqrt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtfnaifysg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgoelrnl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzcncvtxn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtnybrxqcb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtmgxtsxuw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gthngclmlt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gttpcipyls.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtfyfagmbv.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtyvvlrjmw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtrzkzxqdk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtztmribws.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gtblmoczze.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtjrbpdzma.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtlvshxkzd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtnonyjumu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtnrfprnns.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrjtfdmx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmktsfezf.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtzndzzqwr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvbegwrkn.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtluxmbqzw.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtnvvooztl.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtafgnnlsz.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtdsezlwuc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gthwpntllc.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtybvnstyv.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtwmclvxtq.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtbncfdyvz.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtoxmkiuzz.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtcroeinml.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtjaporzlr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtpdpibidz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtviiibjvk.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtbqkoybwp.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtreczgfqu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtyjseathk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtatmtdfkk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtbjibcynu.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gttcahmjgb.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtxhotzrfe.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtofttamga.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtmlzzfrlu.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtxxmtbcxl.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtmeqffqfr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtjjikylyj.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcznfjio.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtxjbmyjhd.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtnjbkkibj.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtywfeqpzs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtibpxphhr.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtqjgdshvo.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtnbrftjge.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwrarffj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtyvjpcitm.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtosnymipb.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gteekpobut.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtmmaqhzej.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtftrhdmqg.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gttdobcgze.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtvccgnwkl.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbteqpuhc.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gttiabhivp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtxufthxtm.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gthmsukcya.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtnupqgtay.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gttketehkb.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtshpedjwn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtluvqfysp.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtgnrhripn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtsqiuwrfa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtyzobnefx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtikaguozs.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtqryaxhno.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtnerudhbs.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtghhqmjqn.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtykxjflms.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtcmzkfftr.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtrgbufdqw.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtuaagxqhn.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtwkwxmwer.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtxyisiboo.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtytaayoww.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtcskensxv.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtmwjhfvyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gthefhbgis.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gthrtjljut.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtkrkgiyja.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtmucdoypx.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlmorzed.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtjajegszg.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtevcpdwkr.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gteuclrcvg.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtwjjvdkze.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtxugzxlao.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtodcwdkvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtofvdvylc.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtsejonbni.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoixjnjex.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwqyztjb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtlwknqztl.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkrdfxzc.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtjynlguoh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtlcugdeob.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtfimhqfum.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtvimnixxy.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtwqtbefwn.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtypdhqfwj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtytsxuidl.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gthczxvjsb.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gttrazibuh.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtpiccwhsw.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtrklzvcto.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtqnrndegb.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gthglyxglv.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtbbwlszjf.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmgohoimq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtepfmlxwo.html


<!-- 参考信息 -->