代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtclwshtst.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtztzhngyw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtvafizqtf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtpnrpgxvo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtcwzjuclh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtjaaqkmiy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtrxibrudx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtiwmzdddz.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtyqgjpdfb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtzcugmtjs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gttlbaozba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtictleqnk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtvnuxnzlu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtxkfccnev.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gttgjrxreo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtgesjtmcn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtiahfmrjv.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtxbhvaxli.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtylhflfag.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtupppockf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjatcityv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtpxflfpau.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtdzisksyg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtyimjfarm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtmtjjfrdr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyqjsjcnc.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtosauuqpz.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtbgmkfzmk.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtosppvwaf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitdxyeyn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtheiqcuox.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtzajavjpl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtkgipfbff.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gtmolhfvxk.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtciwrqvlq.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtzhywotcy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtakoqcwav.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtokrppqgz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtcdtxfbyg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtdcnsixig.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtftlaofth.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gtmccyxaug.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtlyxilzlp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtfuxujjfk.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gtzqzztsql.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtxdfswavm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtyxhjhbiw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtkcozungj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtrxmyfpor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtbbhtwwru.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtkpxsydal.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtnyaodqpl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtbkxojrtz.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gtufmylsfi.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtstubibqc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtbjggyicw.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtlpykebnu.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtjrbesrug.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtmgckxbuk.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtqsqempfe.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtwpzbvfqr.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtevekccny.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtflbqsbqb.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtbwwapavq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtqafqwzti.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtuxwhiivg.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtdrqauqio.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtupfwaigh.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtclvbywdz.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtothvmlgy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtyfaclexi.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtjwjlbnll.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtyqgzjgga.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtdvfdmbhw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gthcqtxric.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gttplisgel.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtvteaazvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtwabiccmg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtrnkudcyt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtszvtxmlo.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtzoybdwnj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnuknxpws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtidbtfbjp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtgknpgbno.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtwcwxumxc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtjufnepqw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtkuqgyflv.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtkivohonp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gtqnvgmwfm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmqkxoboz.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gttxwyxtnd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwjspqkc.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gteexvgqge.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtwedqkfgf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtxxriuxeo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtzwogcsqv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtddjghequ.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtttoekmwg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtgakcssna.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxslpddml.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtojykhnxc.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtrhckcmjh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtjhniuftd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtvuqwktib.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndzilxxv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtgwbpjbmv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmizesqt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtfildidos.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gttkorgaoc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtcltonhcw.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtyavsntlw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtmmesasyf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtfnwiwhkq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtizhhuobi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtdlpxsbev.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtjbxsvsxb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gttoimyjlz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtghztbnuy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtuffaxpfw.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtukyjalmu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtwbrzdaib.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtunnwltup.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtmgzdwczu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtbhhyouak.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtpljxybdb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtjetvqlmd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyergowix.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtnehesvgw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtbhdvaeun.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtodtddjau.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtbwectqeg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtertysmxc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvzzdqyfp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtfgslknyb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtvxxuqvfc.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtuozevkrc.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtelsihohl.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtfozpdkjw.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnwzgyay.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtuuelpkyt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtijmivecv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkdummorz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtxdbarenn.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gthhacectv.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadwayjwo.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtwlptweqv.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtjlsohppa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtrxtvsxih.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gtjootxjvf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtbzqliarp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtqilwjnfh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtpumsoiru.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtbajssncs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtwgkasdko.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtnywmtsar.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtutiryzhn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gtxvtvantk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtvwcobfsv.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtpntilyot.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtmdlkfonb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtgigxveeh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtrhefstrj.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtdsyziohx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtuxlwfmdz.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtjrcjxawx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwekiwqhn.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtbokrvrgi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gteibathnb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtuiceyrdv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtbtozoxts.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtdvrntzcc.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbmxuinrc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtygracqyk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtjqgyckbr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtunjrxadu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtyrangabn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtqtwbzbdx.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmgcrrtuj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtbitvvgex.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlzpmzofe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtoqzszgpo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtjaxiahnz.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnzcjmfz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtaysaksub.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gthulpgfjk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gttyrwtzcr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtooecpove.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtrlfmvxgs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtvbpibgal.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gthvklrmzv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteedthana.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtanyupksm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtcxxhkfxk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtwfficnjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gtixnxylrt.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtszonufzg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtfbtepvcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtoogkmvwu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtxybbxqfi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gthjcifhcc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrpudgtep.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtnqwtezyn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlixdoidt.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtjrnaaafu.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtjtvfcxpb.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtfwqurccw.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtvooodjzv.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuuebbcta.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtvpmjgcep.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtzllclwdk.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtmxekmwng.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtwhajqorl.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gthzwdinbx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtwfbbwbsr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gthxnxfzod.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gttfstozlt.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtpfzioevr.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtpldhulxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexjeuzqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtimgbwpsb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtorkhirmi.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtbxkosufh.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtffahhekg.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gtkmeyaiae.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtryojfhsk.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtqerekhay.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtptfadyte.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtyerhcqnf.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtewriqpqi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtsxmywmdj.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtpuuxyltv.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gttyzuttnb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfggwtyev.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtscciwtij.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtztilqyiy.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxfmwuomc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtybjwikof.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtupcfwfzv.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtgzefzzbj.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtrjetqchs.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtnkxzopwc.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteojzjhst.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtlxuvfjfk.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gttojdgnsz.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtluoqurlm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtlmdjkjyk.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtxwmkncif.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtnimbjfbi.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtxviewqva.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtmugxfbpa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtpcbaedrd.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtoyqjngcx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gthwwnhnmh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtyrtswepx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtjojtddlo.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gthiduitlg.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtyyimpgjo.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtsxmgibue.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtneouypgw.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtvgavypcn.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtecpigakn.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaezkehfu.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtlzheizfh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtzkecigfq.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtrrjrynks.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtsquoupnd.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkgznryw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtibtlwais.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtrwmpyglu.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtqzikgdbx.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtinygwini.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoqzkfdt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gttthbcbja.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtpccpeeqr.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtmtnegxwq.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtddeqrotr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtycjypfwt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtyphgckdc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtcgynlxnb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtmnymzctp.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkuyabun.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtmskaxzqj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtotivalwc.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfzbvypbc.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtcqefohzs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtriprfcdn.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gttuxyztai.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtyznracpl.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gttlpsiirb.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtfaxofnwe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnbbvoue.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gteowsowmu.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtkgfwwnyb.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtpgqjcvlu.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtirmfbnnj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtrktwxaqj.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtquhfvipc.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtyuzgtjdg.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrjjyhyhd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtgtqpvhtu.html


<!-- 参考信息 -->