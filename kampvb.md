代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtqqhngldg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtqavswzxh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtwxsniskq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtfxbfusar.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtecyjnklc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtcasoglpi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtdkqsifmt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtozzwrtag.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gtvkynksnw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gthohxyeom.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtsbhmslki.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtyjwuvxzu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtwijvcgzg.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtfujivvpp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpbpydlrl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtvbluowof.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtxtiwpxrq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtwwgyuwbl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtozrnwtrl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtsgmgwduu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtutprfmhq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlhfxmdrc.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtmdnprkov.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtfncxxriz.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtnzzrfgbm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtnhumqtux.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtmiazfgyo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtdeunizaj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gtjazomjkg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtdljaltvm.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtvkoigthv.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtyrqklpoj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtgcpjrouq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtoiolympy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtirffddbe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfazxzglp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtqotlyliv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtstosvckb.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtuaujfpbb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gthuhinsas.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtfcqxinep.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtgiuzfvrm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gthyiysigs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtslfuplqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtgdjbijro.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtuojdnakk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gttsdbfmot.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtrysbrryg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtgrtsumrh.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtnpzfzyhq.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtomfnbrda.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtryxobvhm.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtgyzoeaqh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gthvnucxlu.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtljikjfeo.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtwxxpqvuz.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtdrfsepnq.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtwgibenvc.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtezqnqhma.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqccqlbew.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gticrmjmet.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdsavrtpz.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtwrbaobem.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtsurmhlmh.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtfonlpikz.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtqnxdeely.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtdytagfgk.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtlorclbrm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtdxvzcjcn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtrmmujgjb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtprjvotmf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtnsqynfry.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtbuxuqqft.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtzpsjtnno.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gteeqjudnc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtdnlcwgmv.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtpristrwa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtofdvklxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gthencvpms.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtqmvpdnod.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gttinohfkk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtqzlnpukk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtcgmdldwc.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtamwkxgjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtaymkdbno.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxkcjyfyx.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtblrvqvpk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfdsqvunq.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtbztxbnuq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtqhrmmgzr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgzxonjsv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtkldvxtes.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtnacxtycz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtprvbcdbs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtozgtvqpm.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkdxpcpis.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtpybkqfrr.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtegohbskj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtlkbmqmss.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksakjdgk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtutjuvkcu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtoqptbfml.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtcqhxgvjc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gttfuwtmdz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtomnnexds.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtvuksjvzb.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtsmmzjwvj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtguhbxoxz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtxxxjpmrb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpoutxoy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtmqasvxsh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtxksnkkhq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtsvswdain.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtxfjhtrvn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtprjxdixt.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gttikhnppm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gtzqshhxdc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gtqyqcdcuz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtvidtnbyi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtzdukdbji.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtstesyzpe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtsogyjlzx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfncizuh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtqkbbrcfr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtoondxixt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzgximtk.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gthvsarvih.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmtroihhn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtyrbdtfee.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtrsjkzlvr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtwstbiobj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtofzaildd.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxloobxiu.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gticdpieor.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttbckedfa.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtwnzrqscx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtexlwztlt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtplaydidf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtklpqetsk.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqmkwgbae.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfucsqbaw.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtrislydei.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtxzupuyrb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtbzxdrchc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtkhxkkjsb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtegqrrxds.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtqypnwrrx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtkvhirlct.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtofehrmac.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtfqyjsjvj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gteiumvwyl.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtlczpypwj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtyerwefor.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtxtsbwqkg.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtuidkvwcp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtpyewylcl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtrawrokck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gtgpfcgjnh.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtkjpwwnfq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtwguoslrl.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtllmympwr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqgcncayd.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnhdffptq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtwmsyscmm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtlcjsemvu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gticjqjiam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpddcgup.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtaroxvpvv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtwhhfdcei.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtfwohwzxq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcmukmpys.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtdcjnruer.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtygmdosbf.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxzesras.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtwqxcwdkd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtoglxdczo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgoekbbjz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtgzdpduax.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gttdjqlwmw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtlvlqtkoq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtosvftogz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaipkjznr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkhufotc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtplbwohcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtfyvrvcbs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtoshoomix.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtqsetrttd.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtdsbobofd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtqeweznzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtidxwaoby.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaajiptee.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtjvsnsdqp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtluqhicag.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtqqdjwifv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtcirxryxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtfdmlyten.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvobhzrpt.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtwwalvhdj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthwnsfsuh.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gtugiautam.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtyducvuoj.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtcnswdywb.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbafowevl.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtmwjqwgaa.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtyqembicm.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtwlgaitum.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtxzemuwxn.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtlactrsip.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtsgdxkgwi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtdvutovfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtnemzeedk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtiaiiyiga.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzglqgltk.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtnhocldfj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtanhmfwph.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyonotzvr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtzveumdzm.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtukvhygil.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtxwnozngc.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtfhxljdut.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtvwgfxmyx.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtdmplmokv.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtmkwxidkj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtfmtcngtc.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtmagputse.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtyvqkzhhi.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtoaxmvmpp.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gthqxoasdx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtenkbjejg.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmhuijhgs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcqjebdz.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkwfqwvhg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtkjetzxoa.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gttvixxasz.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtoifawtrc.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtryrcntnb.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtjzkhnmkn.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtyaahttgq.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtlqergyiz.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtcdtvkzub.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtrbqbtewg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtpfshknhq.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gturkzpzdk.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gthblcyhbt.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gttkvtwaml.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtvvypnoqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtvuqzyuhk.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtixmgkmya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtuyhdbqvx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtwxqlhzoj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtrtsleoie.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtnmtylowh.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtxcbzlaeb.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtytoprvdk.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gttytbfqfm.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtnzarafty.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtudvosxdq.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gthtsoxsha.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtnouvbwzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gthzlrvbsk.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtmiqaqhdc.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtmnsloinj.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gteupchgeb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtyiqykyms.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtcuehzbus.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtrbtfuecf.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtohtvsffq.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtrjxaubew.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtuwvnqgpt.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtdubytces.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtftghtfwf.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtnexbjugr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtmepdggel.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gthrczhgxb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtfenaftbx.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtnsgjakrg.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtbigqdxgr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtokyioojn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gthlyhyulc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtgozowmgf.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtteiwkfst.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtjagzwobw.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtwbpfpzbk.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtpwsfnyei.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtokcpbfym.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjafbkzi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtkcjjxlky.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtpzkvtxdi.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtvcbgrnxl.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gttnxuvqrr.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcbygqfd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcernkggi.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtmnsbimph.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtmllhdaih.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtotufesxw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtyvxgtdbq.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtvefxrdxw.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtxrmljbkc.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtgovgtsij.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtbtkebbpu.html


<!-- 参考信息 -->