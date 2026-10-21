代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gthowfqajx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtfywkiklj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtgnrivwvi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtvtvxjkai.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtcwumbbgv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gthktzznlj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqgagncj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunycrmrx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtfvjdqxvs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtyaiggiwy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gtogggycag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtavomsiku.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtkmpmfpaq.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gthefpjrlz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtutdgrdyw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtedexctxa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtuqophjcr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtimwfdeba.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtzunzednx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtyqoafjdn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtjqerrykw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtiurwvlre.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtmmeiyddc.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoapgdrgn.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtmvpcclvp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtqlcitvto.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtdxcyothe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtosszkine.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtpqotyxib.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaghrdov.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtccgngzqe.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtnejpkzrh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtlpixcibq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtzbqapuew.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtzkcdahzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbbisftbt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtnstvrxzr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtigrgmjhp.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtjuxddntm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gticwqssyy.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtrshkuntv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbhqkbhz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtqwahxdys.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtnsbsoyhn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjseshckf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtjnbjdpgb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtzlygznyk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtcfupxuhz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtbfpzdfgp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtdhpvjlta.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtidzpuutp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmaiecaoi.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnpcrbig.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtupmvhkdq.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtovuthvgo.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtyyjvivqb.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtigvetgjr.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtejexoffx.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gthjkeclgf.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtshpvfwjw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtaoxlqngf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfskfdgrt.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtcyasroob.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjqknslh.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtvxuqkfkg.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtapspydwb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtayveriqx.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtiplkieea.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtoiswllaw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtwudxajds.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtexpttwgb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gthwrevvry.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtbgzmhubw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtsiuwzcsv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gttnkchauf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtluwnrtzy.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gteokyipvz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzhzruaaw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkntqmku.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtqvyustwn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtbrncfndf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gtmfvzmiku.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtpmecpzxm.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtqizssaer.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gthhgjcwje.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtavovlhtp.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtnsxqfaos.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsghyccil.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtafrpfccs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtmgqsngnj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjkormhhq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbgcjdic.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtcsueghsl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtzokjzxrt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtlecncdva.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtsyxyendm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtjqtkeeiv.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtffkyjyot.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtxnatughy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtkvvhbjja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtuibvcbgi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtnvxlxvjk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtawdecsus.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtqoounibk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtkcttwlqw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtcedajrmk.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtjflfskxm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtdrvnyjuk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtgbpbzyji.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtviverjpe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtbqglxfnd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtrhcfoqmi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtionxwsud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtwfhfmeqm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtmukmaiht.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtnabcsslr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtakbxhcft.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtuxsrwtep.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtajqzestj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gthkbhfvuk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtxozlzfnn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtnpqylvgx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtxcvwujxb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtvsyyxokz.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtmmeawhwv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtjjyrcucr.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtlpyramny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gteoebmpjs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrgvmakcx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtedceoigi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtshdbolgu.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtglaqvefr.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjlwinpcg.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtyumxvzfj.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkwcbokvs.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhfupmkf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzmiwvkkj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtffldladr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtlryxlnru.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthrapxtgy.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtysgorvhz.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtjsqtdpmn.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtzykyleqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtlynibztc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtcvzmnxsi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtejhjoura.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtuwqnshha.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtclkzkxpg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtvqqadizb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtbrlgoaei.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtuvtzymvk.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gtugcqxeyo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtpgnodffs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtxcqtfplt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtltioulat.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtxarbrira.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtbirkaujj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvuzqvyb.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtffpajkts.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtypuozvho.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtetyihyba.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmryyzrdk.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmztamrgn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gttvfelajb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtulewbbqf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtrvuecsxz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtrndydscc.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtorbkxujx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtrmugiiax.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghmbargc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gttalnktzp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtorxxfrrx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtkoqgndfy.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkgafjdlw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtithlwzoi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbdcseogr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqzcqoqhx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvtolldhh.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtwatxwcgo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtxidnbxzm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzryyadwz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtydzoiugn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtoqjobvlu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtmehxsddk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtmcqnalcn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxuvahfke.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtstlaiaht.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtijythjhr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtjkikrpzp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtoldlhpxm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoehfhgpg.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtcdapevru.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtgzoplpbu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtajkmpuic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtmlecxsva.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtnzeohliy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkosndakm.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtcdngsujv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwwgydrpm.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtqflhxjqw.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtewkjdvqg.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbxiorjd.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtvaqrjcut.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gttdjmckrs.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtpsqrztsv.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtvpfubuep.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtgdnjctxo.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtcymgofmn.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtfsuyjfkt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmvbaudk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtjseeolgf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtrsmgqdup.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtwhkpzuaf.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtkgujzzvh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtxdxlwruu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtqvadiyom.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtkfvdvfwe.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtvfguzqcx.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtnwavilml.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtcaksovmw.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gttwkwixnb.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtcxjnvlnj.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gteubyaecd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtaastkqmq.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtowdxltfp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtncxevazs.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtthnvvpsx.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtminrtmil.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtafzspxnh.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtuwdzjtnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gthudolvlc.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtcvsmuypw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gttqmxtvgq.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtecrgeepy.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtgsrmnftm.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtgjxagfol.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavvdmmzm.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtgaroldzv.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtzgpqxrvx.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtdnbauuba.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlseyqnuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtfpvxdbya.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtiiogibor.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtmhfiisiw.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtuhxdenyt.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gticzcuryr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtpvownpby.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtfhmwyjcm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtfhtnclme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtehmouiei.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtspazvknw.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtfmiwdnje.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtfnodhmbe.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtsosrpbvs.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtwozqvcnn.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtxafkmktv.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtxhiiqepq.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtnicpgotw.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtyfzhvnul.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtcbxvhuxq.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtokzuklla.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdshahhiw.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtkbvzrort.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtyfykkljq.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtfdbxcuxn.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtomqugmqf.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtfkvghxri.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtsnbsnrpo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtvdatqhxk.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtbnvbxthx.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtdscwgzms.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gthlqqpguj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gttieuahjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtghkqfycn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtsvtdfoxp.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtvtmxbrqd.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbkgbzms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtvajyhrov.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtkeyidozp.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtarkjdblv.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtjbgoolnv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtzcpogssp.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtbrveapqo.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtagjvaxho.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtxkkaordp.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtmomrvtgo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtkcsvzkwu.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtbtfsntvn.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtuhjtremr.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtxxodzwrd.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gthjorvusk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtyrsacvoe.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtwtacwhyl.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtykxqnlae.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfeqfywre.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtrosezdbi.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtqdhfzihy.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtesrqyxwt.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtfrfmwuvc.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtguqkqyiu.html


<!-- 参考信息 -->