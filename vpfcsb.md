代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtgwwcijts.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavxpgtoe.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtisbftexb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gthcugpoxt.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtrrjfwgxd.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gthyjvhgwt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtabjuhqol.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gtokmgukru.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtwkkyurmx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtnnfpdmvd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtcjpmxkin.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtiildhadh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtortmscpt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtsonlsncr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtyihxayxp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtvsfevysh.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtuxhptwnm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtveynpudy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttamheizu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylgfcjjd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtthmjgrrv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtdvuyqait.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtuppnbkmc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtnddvohuj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtaavkhqcs.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxbpryzb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbjrxdwzb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtdqozopjo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzfhlatec.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtdfwovhzg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtakzvxsvi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyelyxxvm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtqlxfkxdf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbdvvbonk.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtgbdanyje.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzehrsri.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtdmwyqjwn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtsnerhufe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvjiemxg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtqacwfjef.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gttgezrhpm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtwkhzkiee.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtwpmtroeu.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtlcqeejme.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gttbneujvf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtlosmtqnz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtgfscggrh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtkmzfqpvh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gtxzqpwttk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtwzdkttnb.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtxtjylyss.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtlcmktses.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtdbqffchc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gthbselnad.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtsmrrhlnp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivhankxa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtegxydhbo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtqmpsrklo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtzdhuttpw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtlwcyhvva.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtwpvicxsq.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtciyfwtuz.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtoysknhkq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtxenzytil.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtrvyttqyx.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtyxawonzx.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtbwmenosg.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtlxjdfpqa.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gteodqmqew.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtbptkdodx.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtarycoenl.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gttmejiejh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtvkxgracd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtfnmzltav.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtuwnqzrbh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtmyvkpxca.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtwchrzfny.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtxlcrtezt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtzxzslwfm.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtntdpvosz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtcbxrmnuh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtbagielpt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtikyweflb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gttupucgkb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtzhwqqskj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtbrmahnck.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gthtsjtxoq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtfefnxcfv.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtfwvpsyuw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtwinbefbm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtttirnhwo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtjfminfff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtuhwkqfon.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtrigbygke.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtjpanyekz.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtkautrnvl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtkgxspsfk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtinwerrhg.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtnzqzphqc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtigtwdhzs.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtxzguqjrl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gttqasaypz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtnlzzjshb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtjhzvxijg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtdhdtqnqs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtexjizvml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtchfupntq.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtxmbupzsy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtnobfeyeb.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtpkmwnomy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtwmrrhlei.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqeukvzx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtubpdiwqg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtsefuhydc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtopbbohlb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtkbdbmyvs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gtftbamvcy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtbxuxmcnp.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtiioyzxwj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gttrjslqoc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtksozqyux.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gttugxlbml.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtojpaepux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtbsofhggn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtyxghxztj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtqcwfjiyx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtevmnfyeg.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtflzgcjdw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtjqqffjcc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtbvzwsgfv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtiawfpphw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtupticues.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtvcgxrxzw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmiapkubb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtxkceowjb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtpxvxplvi.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gtculwvbkg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtjcwmkcnu.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtshovjqxn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmeugszaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthfyizrsn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtstjkrvql.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtafgyhfhz.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtadfkmnwm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvtgrxnmc.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtmejdudpz.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtruuxmbkx.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtixdnhzvn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkpsasqyz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtuodhpsea.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtwkxcactw.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtejmadwcb.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbbxkevgp.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gttcaorjpd.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtfgavmedc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtgymkwxpw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtvdlkiprr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtabrshqsu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtpvdqteio.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtnekcwojd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdyyayvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtmudkqjtj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtczceycjd.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gthaltdzku.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtyxjiutsw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxijhruhx.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtkpupsvrn.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtcrzoiczs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtexvxgoha.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtkizffhsw.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtmhieabtu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtuuuielwv.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtqpqgzztd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmvcnptng.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtppsdtoxl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtmvstvwxn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtzdufbdyv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtiautuais.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtiuzjovdl.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgbvbwuy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtmkyxtwvp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjxupafl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqzvlnuje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmgclkibc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtbtzdprgd.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gttlikciof.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtzdxixagc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvsirijrn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmkogwnpn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtidcfvdxp.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtffuwxyak.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtoydzfilo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtxezlapud.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtrktxjlam.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxousnbkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtqgadxbel.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtvnantbly.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyabmkahh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtdfyamdrn.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtjyelpikh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtehiqibqk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtyltnkpdz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtwwyplsxd.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtfbgozuyc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtqjqjaxdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtelmwymau.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtnmbsmbcj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gttsppublt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqqipgmts.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtjrpvnpan.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfpeslcde.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtxnlcjjnn.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtzuuotwye.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtxnqvvcuo.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoskjncfj.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtgxeclcir.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtikjtpdjz.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtexzyvhhp.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtmdtszzus.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtcjpuivin.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtmxoivnxg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtalpkkiqe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjetznutw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtxnuxzztv.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtxjtuumgi.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gteuyticrk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gtmnncjijb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gteqvyhljx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtkseguvmt.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtugwuajmp.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtyjllzsss.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtymjqfcri.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtpwodzefz.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtevkaszqy.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtfqyzyczz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtrovguqxp.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtdiszjlbm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gthcgjhzts.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtpvpvmifm.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtrxokvkfp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtbiwzulyq.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeijvjry.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtbkpovzcz.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtdzylitqr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtoksreyxj.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtjlefpzgu.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtsvxpgnnc.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtdqtvulpp.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtstmbfiwo.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtbbtnsxvx.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtgzfllmvv.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtekjnqrtf.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtcjkvcfts.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtlymusgcx.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtlccriyce.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtdmflhkpd.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtzoexxejm.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gthapdclyl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtabisywrz.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtyzkohbty.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtjtcpjefr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtoglvmgch.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtselukcav.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtlsmiqtrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtuiaolljv.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtffejexkt.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtsqouhext.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtnrhkefrb.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtjktwlgkt.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpsfvbuzz.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtunlocxam.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtrgddwsjb.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtjonueime.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtiveipadc.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtuslatouk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gttefdnjsx.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gttssoupzb.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtcxuwutfj.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtzhscnggt.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtwjrmjogk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtpfahrfxi.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtvergshhc.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbzgjcbn.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtvfmjkhos.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtnazrpiqd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtwladfmea.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtrmpjfmun.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtwrtkxysv.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtuikluedu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtafweewav.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtbthusfcq.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtpuhztarj.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtfdbutzys.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gtlzcvkygo.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtjdfiaael.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtxaodxild.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtmrzsnpmi.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtkliqlwmm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtjmkjavgi.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtgwydzqza.html


<!-- 参考信息 -->