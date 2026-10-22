代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtlvixezwa.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtgkbalgiy.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtnwguynlq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtnvkhguxw.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtybgusfll.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtesgeficn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtvyurmunj.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtllcvjcid.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtxbwukize.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtjafvujnw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtlyswbbwt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtpxrozwia.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gtckoaukkp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtkditayvb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtnucebzvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gthgoeempz.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtgewnjefr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtnwvloljc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtoiwzppci.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuxpmbok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtpuifvtbl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtiwmbtzcd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtoemfrcnk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gttfunbqsr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxmsudgt.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtumvfpeir.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtkkeasjsg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtkvyiofuw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtxxmpyyht.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtpmqjxnzt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtoajfswzr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuerkcshp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtfeoptfvy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtmhayriet.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtvxmkodjg.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtvurmpolw.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtahmfyitz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gthsgskgvu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtgejnvzds.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtahmyedpe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gtqanqoitn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gtpzlruaav.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtqvqoyyqd.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtqlyxrrgj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gtshwkjosc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gthnbqtifw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlliadgqu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtethzikpw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtnwnnoout.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gttzcylvnt.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtkxhbipwj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtsdktmjxb.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtctejzqvq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtfixpljvk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtsmptedei.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtizdwqnfu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtrjdlwyet.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtyzbswexe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtdvdcfvsh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntnfoqhg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtabculsjn.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtgplyeckz.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtrezfppgh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtqxadcxao.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtdmbfskmu.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtcithbzjv.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtysjjlahu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtpmuwydii.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtgoremqgq.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtqygpglro.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtwsyxwnnj.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtfwspiutg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gteqvxlqlj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtcetadggn.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmjdaggx.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gteeuhebjp.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtzevjbqyv.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gteypjthba.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtzuiqcosd.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtgwwkvwnm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtgtonxvwu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtupsaroed.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtmjjczeev.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtumyvmsna.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtsmjjuevl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtomcpcgea.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtiijyxhng.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gthwjjctkq.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtrhuisjif.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtvoktrdeg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtfjftceay.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gthlozjwla.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtyfwagwob.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhwzqutj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtlvxlguod.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtygrcxncf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtyvgehdgf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtchvurdev.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gteyyiwgle.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvohyyvky.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gthmlqsyfe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtwttpregt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtyurtxybg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gttkelibdn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtzirodbck.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtsuzrbbjx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtclqauwst.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwawwtqxf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtucaqzdli.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxktswzla.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtkihfnxtr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtfoniqdwc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtdixliwhg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtxulkxkfb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtyjbjnueg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtnuotxwya.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtbhcorhqq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtouwqwcqg.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtvfolwzmc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtfzdqiuor.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtwplbbsid.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtneeijjpn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtbdzmwgzd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtyhotgwwc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtudzeqbur.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtakneasll.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumcvyqmu.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtpwglroso.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtstjhgtao.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gtfcqlrdfx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtjpguymvy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gttvpizrkg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtijuhscsi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtoxrfejzp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtuubhhoqx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtzhzwiwsn.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gthdgrokii.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtffgpqhsq.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtrpdzyvhy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqkopfefo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtwlppyyso.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtocrabied.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtcjvkgjbn.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnwmpzdfy.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbeprgztv.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtevnxmoxd.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtoqsyuagh.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtilsrawzd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtsifccyuq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfrquypad.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtldyemonf.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgnvknqxz.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjivoqzue.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtgxzfryxv.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gthfilycuw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtnpdqcsjs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtgvspycjp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtfoeedzma.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtnsrdyhdv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtviubtvaq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtayryyvnt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtcjqwnqtx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtepnilnwn.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtlkxlnloo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gttmgyvqjb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtznjbrirx.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtlkswxipn.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtizjqizww.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gthjrfdmga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtwyogbnrd.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtiwttuxzh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtxeioqhfj.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtiugtnsda.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtadkqguqk.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtptfvokgf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtxjtiakwq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtrguykutj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtmlkgxnzl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtvuiupjrq.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtclfcblvq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtosyogzvp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtqingoiap.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqfwrcuga.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gtottiivwk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqlmqtsqi.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtaiekmcxh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtdwxgixks.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtejrxitcw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthctejqbe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtruldivgi.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtfccqtcsi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthbdsqjxz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkpsarmzm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtferwhnbb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtsiixbkmv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gthdwiknpi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhnpzmbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtscksflst.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gthfyroogb.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtycbchrqh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtmxrecwlh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtizqzhkrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtgygyddmr.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtipbxrish.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtiouycldm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtiqiflhyd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtcdfiasvv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gtncxzhoqr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtznmjpggi.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtmwukguye.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxnjokadr.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtplagqiac.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtkkgvpoza.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtbbkgrzzq.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtjadxunmu.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtrzhnymvq.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtxtbsgbpm.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtixezqejb.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtzbkrutpl.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtdbvpqyto.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtejdgtkby.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gteqsvppxj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gttugfuwrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtsnatxjvm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwbkgdghd.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtbzwocmdn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtyzidvskg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtsevxtozi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtvrtoffum.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtggbdmsnw.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtymmrweop.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtrudcyudb.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gttbfygbtd.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtaiuepfsv.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gthvbrteyh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtbdvexzji.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtubfoycjl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtedoczqch.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtgfgmbhry.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtsaaichal.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gteatbtfxc.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtksyoowzy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgrnonrrx.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtjzxljokf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtcndztsni.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtgnypzfdc.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtzaiwxlcp.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtofomscpt.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtpnsciffv.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtuuzlrrwq.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtveavejjq.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtdgttedus.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtcpcthkda.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtcvxgtkmg.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtnzdfnzox.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtcbmeugqq.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaecetsf.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtvgtqeosz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtmwwixrdc.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtewdkofdf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtkmrsextt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtrhroouis.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gteuotgira.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtrvogahne.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gtgoxrbqxu.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtadnigspt.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtcsrjadpz.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanjyrgwv.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtjsknkrmo.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtgqhztdhu.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtszebfxoy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtsuetdibt.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gttukuoint.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtjrmmhfqd.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtjrobmcdj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gteqrltjlc.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtbkquzrmt.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gttgfpykfw.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtatuirjca.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtxzvbsnxo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtboaeulkf.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtxdzblqqx.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtyeyuiwrg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtiabtgzqe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtgsxpegwc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaidsyen.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtkttoybae.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtolqeclnj.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtsffbcvby.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtrirlsljk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtvbeacmed.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtukkvixrn.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtzizoiuud.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtstfwzppi.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gthexkjomf.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtifufgblg.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtrwtagyih.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gttiqychsx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gthwdiaxuj.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtibvzpiwi.html


<!-- 参考信息 -->