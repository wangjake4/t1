代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtkraxuzkg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gtgcnpgeoe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtxvfqpjts.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtcbunabjc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtzxjdsfeo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnsmlfwe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtngzhiaip.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtumtswcvc.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtmvzfmpgq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gteoejkzsu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtyrxmzzvq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtthlxtgcc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzfzpmtyf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtglqpyqdw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtmwkclltk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtlfzwexey.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtchrbfyjx.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtpihmlawv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtqifznfyh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gtprwdmcuk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtihjsvbos.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtycxllbci.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtgoncqhch.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtzhknmtye.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtwanvceam.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gttiaguiqt.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtwcnjvxcw.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtfxgsokff.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtvklkkcsu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtrjgwilfz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtwipvmftt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtxqkymmfo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtgwdeswvl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtyzopienw.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gticuxijmz.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtfjpwvycf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdavyqcx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtvsttdqko.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtmwcuelxd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtlcbxmsiq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtonpkdcxh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gttvtsawis.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtfoocnnpq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtogeqjski.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtzaokwbht.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gttpdsryxh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtitlvhzqr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtllwjkffg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtyatnzdvj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtfifjujig.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtvhrtgimz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtnhndcmfy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtythsymxv.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtnyxbwpvq.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtvpuzewrt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtbvrnxnaw.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gthtnbrefa.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtjagvqrxd.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtbtkbbvea.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoroawcwq.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtrebqliqg.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtjoairqcx.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gteqqubwtf.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gtausjoqjz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtipvtrngw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gtccuzbdud.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtuuxzqnir.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtsfujbopd.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gttffywpoj.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtqqctvsxr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtshzhtgta.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtmvoorhnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtoztglecw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtoanzppab.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtlahslycu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtxlpicrdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtniiffyxu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtvvhavwwg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtvmltjcue.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtdprbkeni.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtkmtitdxo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtoifhhuwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtxywpbksl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtdnkeyell.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtizzjpypd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtyrrtjbqd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtlahgkdkj.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtatstajwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtnpksqhsl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrvxxnzrn.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtcuskgqtc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgxhjuwsc.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtoegqmguy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtusmuxqsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwjskmuc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gthsjhhznm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtwxdrnvtl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtoohxlebi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtwfvivnnv.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcbeawndc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtgnlfivpd.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtzzvrmcxk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtqymrceer.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtklncrcni.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtovvpyhhr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzansbvpv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtbtouvvml.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtlwnahcpw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtexotbhvq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtgjbhwskx.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtosatxsts.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtujgbhskm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtgfqkhnvt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtkwwydixt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtwttdiaix.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtotfkezad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtajazbsdu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtjpiczgsw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtgmmsordw.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtqzuicqpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtwwrmgyor.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvrhjaol.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtdukhclmy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtacyovnge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gttwtqzqqs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtukhgotmb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtfuikxeue.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtlfhpsfgk.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gtzizunbad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtjmpxbifm.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtowdzbhgu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbhpclimk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvkldysf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtqgnysvxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtidnmkmrr.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtoufjhoji.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtimjlunzp.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtkbmbjlyv.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpfwmwmrc.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtxuunnxrv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkbrnuqmi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjtqwhojk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtoxjesujs.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvaicmipm.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmhmhchmm.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtmvnxtzen.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtoqvqxwjx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtajoabsju.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtjpynjclg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtbtouktoz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtxwrbrctk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtysomdxqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtarxcshgf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gttkjquasn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtltjeobub.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxclxdtsf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtemagxnmx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtgykhucmp.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtmrqokwej.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gthfmbdmwr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtawmwabdh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtwyahsidj.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtjcintaje.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtaixdrlwz.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtkuyjcnyn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxjesqtto.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtbayydyiw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtejzhwkya.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtkqymbtxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gteiugnahx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gttvnqvgth.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpofrnipa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtdtyktuec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gthmdiqfck.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtizajmazy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtjozhzkcz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgiadxsub.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlfwqrcpd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtfxpopnrp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtqgscxrez.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuenqffbn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gteegzszvc.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbkyifews.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmitkyazv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gthddxmimm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtloplxnah.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpxnnxjbs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtvxgencud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtmomlhxri.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxvlllhnt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtnckpydes.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gttnorofnc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtcffhpqdo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtqnkodvzd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxlfqoxq.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtneslaylf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtmhugkdek.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtmfdduxwc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gttrhvvrtu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtsgvpfzsd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtujionpab.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtqcvpjifn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwyxteniq.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtiwmaswdq.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtulmkyhcm.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtxphvfckd.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrnrgsuy.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfukwbocv.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtohqoyelg.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtxycmdnst.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtvhgcxfgk.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtdbrjwuyo.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtevngnkbf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtisqyhrhi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttujxzwtz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtrlejettz.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtuvwjvnpq.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtypexoicy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtrwysxvji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gttdpmwgyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtwkfyzyar.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwblegkr.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gthllevgmz.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtrfpescno.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtbmlfkcmf.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gthwkwbqzo.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtljkqofet.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtkgqynrfa.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtzvajcror.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtovkcwiqi.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtceqhklza.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gthlvhzgvc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtedzfuowv.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtthranutd.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtykwdvdur.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtpgwonpjx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtoncripnm.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtanynycue.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtkwohthqi.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexmvsaxt.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gteaecmdop.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjomgszab.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtloprebft.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtrppsycal.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbudfnbco.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtbpyvgthk.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfwbfevc.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtcvwybyik.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtmigvasaq.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtdxnjzery.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturcrullq.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtzgzxbkfv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtonwrmehj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gthtvefqfa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtqoykoayz.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtdpeuofea.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gthtmewacs.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtnrxltzjb.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnuqrddm.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtxvtmodcx.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtqbvrxqlj.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtbjwhofgc.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtdzyqtevg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtuotzxjdu.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtioqxteqg.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtlbiwujoz.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtbzqtloga.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlofvncyx.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gttqqzzmmm.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtunjngwqt.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtreozhelr.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtotnbunll.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtepbaljri.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtocarvqbj.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvkthxqw.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtitzemgbe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtukjbcruz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtnwgfyjrm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtjfphoxtm.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtmbaclptu.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtjkjrbzar.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtijniymnx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtiksaxukm.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtimvfzmsx.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtezgjaeav.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtfnhirrrr.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtyizwlffd.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzyekbhn.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtcynidzdy.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtkrpqemar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtjvnbjwir.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtvigrufgb.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtflzkgota.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtxubtgbrh.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtwvwsdssx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtrwwpxofr.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtidahzplw.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtnlkhbiqg.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsjgostwo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtrlyrrcyi.html


<!-- 参考信息 -->