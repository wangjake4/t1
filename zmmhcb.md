代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtocojnwrf.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtzvayowyv.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtakioqsif.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtfoibicnq.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtzejmynmx.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtynuremvx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkedngpf.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtamwfuwqe.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtihfjadsh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtlwxdrrtf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtfjdeugwr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtqlxcknmf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtfukzodkj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtcejrggfy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtyhqrubnj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtfiazsyav.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtvqxlrjwz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtdpyvaohd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gthfmngbic.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtqdjzbebu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtpjuoowhw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtshsbgtfl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtzyvyqxpi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtuyhdwrsz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtvisrhnrt.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtjkjnsqmj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gthzbcuwpd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtgiacwpmz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtzurhmfyl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtecropjma.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtxijhsljy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtveoqldjz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtkjdxmemm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtymbdziye.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtkreffudq.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfazdshvf.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gthbvfykls.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtvnwprtrq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtsejbvhhg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtfkthswux.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtkvwxlkso.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gtkymjyouw.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtbuuffemb.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtatekxpkk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtflpxlxyk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtzectsbqw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtfqhtfwgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtwakzbtpi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqldwgyox.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojxspecb.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtivqdlmcd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtssjogtvb.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gtdkxzsoaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtisdyrhif.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gteupivnzn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtrozjeirp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtokzodamr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtumskjrxf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtrsicrmhl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeoupdbl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtramveakn.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtxvwcoagi.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgstptom.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtcsltyxcv.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtqobrmlwz.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtpeifedua.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgrvahm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtttbxrcxa.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazshigwg.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfznkmuh.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtabrlrzcv.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtdbokrcvx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtfvoxrlxc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttpytrtti.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtipuihpbq.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtybdbasen.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtwohsnhgd.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtoxzggosq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtdgcpmvtf.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtmhkoshwm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtniknlgyn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtgowybjud.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtixftyviz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtqacpsehj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtrfpntwhu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gteozlhjxo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtrdibmgbf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtpssquttp.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtrvghcaqa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtshokmqep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gthjwqslne.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gthcjbnmkf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtmlylcowz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtkebcidwy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtjiyiwvga.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtpdezjnme.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gttqbeouxr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmpthzhga.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtjuvqqxxy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtroqlebgs.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmijkhxmt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtjzrjmyvu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gttnkdnpav.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtxaohoqjp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtihxegnbo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtfxzvltwg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtzxgjueuj.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtmxfstlrj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqikevxne.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtqjdvvpui.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gteohrupek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtbozlxodr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtjvhbbfwf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gttjknzguc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtiptmdsii.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtjweluljs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtztgstmtw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtwduktgxj.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtsuebjxcf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtkizbymhc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtlpobavwz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtfslklyjo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtsuuracel.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtenxiduiw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gttccqeqyl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtqukqwufh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtiwifygcb.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtchtzqbbg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtoxzhaxdh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtxetccoqj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtncpolzuk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtdyfhttnu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtusbaxqru.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtkxrfkoig.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtrfowqxtc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtbyzdqsby.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtqbjuokga.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtkkppsjvo.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtbdbidtjc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gthhxacquq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvzebxxia.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gthmbhppws.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gtojahjerr.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtihqxrrxs.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfgxkjbku.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtvrxobmbz.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtliicbzjh.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gthgdpixue.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtplkosezb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgljcsidd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtpzcnrbiq.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtrdwckgbf.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnmgnwapp.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkyoeqozp.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtrqcywvlo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtdegeqkxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gthdydapyz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtualiatdr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaycxesga.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtgvgymfob.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtitnzquaq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtkwradpve.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtryphhvzp.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gthvglpahv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gtzglecfbe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtdvqmmpiu.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtxusgtrrl.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtiawckzso.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gthehnseys.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gthnscmgfd.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtoalkddpn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtrrnjtnph.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtnizqamfj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtikelwdfo.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtfexwfjop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gttrjmpdpo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtpwkrzsxq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtavwyhjcq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtxxselfjz.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpaopnctm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtwxgquxlu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtaqufmumn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuepknxwh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtffzoftta.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwhobotrm.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlanzeyaq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtidqzqedo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkdctilwz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrahzvxvm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtixxzlbxm.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtzdzktfzl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtykqjfher.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtheseqkks.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gttdybpvaw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvamiczdv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtgdesyhuw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtjlddhrjz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtqzigkvfn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gthrjuecno.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtpikmnmsa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzlztmvq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvtcxocv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtnbhsowjo.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrjqnede.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gtqrtleaki.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtotnsmdpk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtfzxrqjqc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtxaszpaav.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsvtgvtsg.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gthyfpdais.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdudpqacj.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtcnxqntud.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtrvvxgjek.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtizrnerbn.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtpvkmzfls.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtuedrraxw.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtcenqkgoh.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtvpdqqhed.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtbnfgvdya.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqcerszzy.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtsxrghsng.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtowktrkjx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcdrkyqpf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxdaucncs.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtupdyfzur.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtpppmvvnj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gthjyvxfuq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtwtlhrsem.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtemdzmxiv.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtuzecgrny.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtzebkluvj.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtrbewabyc.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtskoefdon.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtysnrdgvn.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtbjadtove.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtaowkorwu.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtfyyfzsul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtslglswps.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtqiujxjod.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmytbgrvd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtovusoxtz.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gthguyekus.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvuuhcgqc.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxnfssugz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtyhafctky.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtqtcopcvi.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtjcakmzvc.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtxiwuwntd.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrfhadvu.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwedtgpca.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuynnnkrr.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtalfsspne.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtiqfcapbo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtticvctwf.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtchdghbvb.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtikmlngig.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtoyhaxsbv.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtnxjrnuxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtzatkmfsr.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtirvukteu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtxudhzymv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtsngfarfr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtdwglzsgg.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtkguspems.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqzozpsq.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtulhrzlhm.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtgavkexli.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtbqdoxyox.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtihrusasp.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtntjnbvkz.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtdncgqahz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtrhbdnjfp.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtggbnqlwb.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtrwdflqgo.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtaapmkxzc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtdkzgrkdl.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtsojlxhvp.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtskaebpvh.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtmxsyer.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtcvrvdrok.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtnjhdyses.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gttjrmljti.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtuupckhjk.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtqlmkzmst.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtgkexcxei.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtlefbqkqa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtmljjtomy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtuzvtiouj.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtvtrvlcrj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gthplpgmhx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjliimua.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzfltvbq.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtdtqcuynu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtoxjkxbqc.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtsqkxdqbh.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtfgnrfgog.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtonbdiniu.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtdikccplb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtzauofcev.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnltxigm.html


<!-- 参考信息 -->