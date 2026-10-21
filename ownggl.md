代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtrnfnaicu.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtbfbpvmog.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfdsatup.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtwytnlnmf.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtfcozyvoe.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtbkuvbtim.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtrafkityl.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtteqclqdr.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtbjxfsqpy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtmbgnxdbe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtfzdnbjwy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gteskfzjnc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtcjldhdse.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtpcoytuck.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtxzmddkfk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtljyscxai.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtohxwvjne.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtzevmaxrc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtuhuqmesy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtxtjjwgjn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtejidyilq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtlolxmpkf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtqjfhqdxv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtgtwtfuvm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtszqwgweh.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtppexripz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtiztkmitr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtgndwjblh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gtgrogaudj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtgkywlcdm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gteqaweehh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtsgxnebhz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtskkwtoue.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtbthcuqeq.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtawaneihy.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtnxlrmwhc.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtabvfbhqf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtteckbcff.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtjsbvucvr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlnteecv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtfxcmafnn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtukuufxzq.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtrrhzpkfx.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtsgwhhyck.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtaldehpoj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gttghjvoyb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtycekqson.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtvygemmqv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtyihrpioa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtnlwkqvre.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtgtyrqrlx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtyvwuaeao.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtxacmbktl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtalpobrca.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqkktbdz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtohwnmlaf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtzhlfblpo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtltuqyxxt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gttqtyyfju.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtpjiieamb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtrumfdwmr.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtmqpdvbny.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gttktkssaa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtsyjprury.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtfacxwgwi.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtqjasoexs.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtqwppxidj.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtuwzonzjs.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gttlvmvgba.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtctuxwagw.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtflpimnat.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtjhvgpkgf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtretqeczl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtscobhylq.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtjusijqiz.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtswnqvdkb.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtvzfxydhk.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtmpmfotpr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtegzjxniz.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtlyhsjrzk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjrrlyxy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gteqrffwqy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwvktrpb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtzkvsfoey.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtgmsmooke.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtenjavaru.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtvlkqydbk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtnhvpyrwa.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtsmihdfbo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtjbojoutv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtbrufnkjp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtxtmbmihd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtplvyitdu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtpqvjijgg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtccriiyzg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtrotzoezw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtwbictwia.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtydkojmgm.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtgofcpucv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqmszfjtc.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtuqxvwakb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtiiitweef.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtljruuhvi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtmcneuawb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtdgqnmdnk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtrdkmbxvv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtmeurcmst.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthitoniyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtgxtusbin.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtyvyimixy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtndwrgtmb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtirgcmlfe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywjfasym.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttndnfyjb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtgyqdqjjk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtgpxstwpu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtjyfzgngj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtwdlvzubm.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtvzlfmotk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtvkqgjynl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gteayihguj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtvejbsxqy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtvkaissve.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtjmzwsekd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtfaoypdoh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtggawlssw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtvdjovahz.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtbtyrbzbq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gttscwifwx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtzfvroyxt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzkbajdd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtpoympctm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtdbdpvdkv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtjsmzvpmj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtnpbuiwoi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtgrjpqwzg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtzjuvnbmt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtmvzmibuw.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgtlelmty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcnsnsbil.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjuzgxtif.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtkncjuife.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtrqqsnpmx.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzhfhfdav.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtrftxmjbl.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpvadetyj.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxvhrsotw.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtjutitgbp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzdzxtzhr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxgnoytvo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtdktugyvb.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtaeqozerh.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfkwbleyp.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtgzgrasbq.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtkudgmevq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtqlqfutzf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtjyrglafj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtrfmaxoyz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtalfsevom.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtwpafjjam.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gttzyebxyk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtnxhuecqo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtxefwgrgh.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtcikiixzo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtbfiwdwbz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtnwvplpwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtckvmacfu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtksuzgvcc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaqqzuhf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtgnwsdnsd.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gthqdzeifd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtbvkaublh.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtcbrvaygr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpqtzknqk.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtpfxqrdhx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtzkdbsgoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtmhtzlils.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtjfxdfleg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtedplctjh.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgykwfmqq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtkpmwnyac.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtnrwnheij.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtyadsglkp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtnisadmsd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcvqzikib.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtiouciswq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtutkrndan.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtualdyimr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtgawmqflh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbnbpngfv.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtdhwfqjmg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtubrvffde.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtzxhtdvba.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtleyusqvs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtbgulgmrk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtpnugoayk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtsgykvouh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbbmrfizp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtaouqfzwf.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtkugveddu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtmkmxugbe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtedbkvhfp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtzcnyfzcj.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtkbqmgnnj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtrwfpttyl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtntvtykgn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtpllshytk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtulfthgal.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvctvhgn.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtlowlsnum.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkrxeczjs.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gthsbvaxyr.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtebprctdv.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbshstkal.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gthecjwurv.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtgiifzzwz.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtfalbttmh.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtbtgkwshz.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtkabcatlf.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqrmqoyhu.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtykvaleus.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gthazaethj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtduaqbtgs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtgmxrrmdn.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtuepwjmel.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtvepdsqlr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtxwqodpnu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtkpbnsixi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtodzmbdad.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gteuesmbxo.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtyzehyluy.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtydieordy.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtclrdhctm.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtnfavajfo.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtermagtdb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtlaazscbd.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtcxbaimgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtkpopuzun.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtldfrhyxx.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gteokvevzt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtehqgbcny.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzxbyxmpy.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtbmeiulny.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtxzsvjojq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtbpvmhxbi.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtplmnirwk.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gtnifmurmf.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtmdxbutkl.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtydcfvjzf.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtofhpaijw.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtmxenihrz.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtlqcondpa.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtwrdeumvt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gttfbcnonq.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtepquszbp.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtoubvoqxo.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtwoflytiq.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtfqxxxyzy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtbkiycnis.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gthnwedpdo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtjovdzxff.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtchlqhdbh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtkwboeukc.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtmxqgbozn.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtvcoekklc.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtohblaosh.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtwvimhqws.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtgljqeesa.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gthdcxisfo.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtdvjnwjtp.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtvliwncwh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtaxwdhfpm.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtziuuukuc.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtrwdrnmse.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjsvgfyw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqfhppws.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtgpeeyliw.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioanvmac.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtcswnyjdk.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtbdjewuyl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtbwufjjho.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqaenvnk.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtwxvtvppe.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtwudcfbsb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtwozzgevs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtjhaqhdxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtuedutkrn.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtkwlztsxr.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtqxvvqgyc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtqmayyxjt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtjaomgyxi.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtbfligoml.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtvhcrxvps.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtitjfpjzl.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeqgdqas.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtgkgccwdh.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtkjomiwle.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gthkaxibuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtbniznppa.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtjmktxyfj.html


<!-- 参考信息 -->