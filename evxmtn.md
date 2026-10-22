代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptdfelas.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtoxacdxvl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtiuitcbda.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gthojngxra.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gttflawpuw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtcqvydiav.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtkxnpkoge.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtgykltjqm.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtjufjncrv.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gttgdygblq.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtmkhgtipb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtybcegbtb.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtccymakrp.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtfodhoeia.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gthjtvbiqt.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtckonqofu.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtxzeyrgaa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gthucbaqar.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtlkyjypas.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtzewyjvch.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtxxxtvfxr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtqktxqdlp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtkpexwtca.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtansyusjz.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtezxbbjmv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtvzdaxoxw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtylhxbtgu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gteybqqnpm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtjuwaiiwd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtwigojyuy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtrggpthnx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtgurvoznc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetkjxfsc.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtzatfggrd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtadzuzzig.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtgicxrxsf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtitkkhdwh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtqtpuxgek.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtqthfoamj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrbzefgta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzxzxqljx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtlzqznlbe.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtxwhvazyv.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtdfmjuvxe.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtjgmxejam.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtwimiefyg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtvxeaedhq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gttszkuyay.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtxrjdufml.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtubfwbsii.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtirehdjzx.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtkaxorpdi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtlwotbhfk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtucyvbflc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtcmxtgsjp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpgqbvdof.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtuqvormqx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdelmtbgc.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gteqwumvgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtqqpdkagb.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtwcxbqewa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtxqaibmbz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gttidrohxv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtiidygqxk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtwptuwdhq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtolrdlqxn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtvybsnfdq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtgjpbaiez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtgklwdaru.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtjdabqtky.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtqklwkqta.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtsmtdbkbf.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtvqpchdzq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtvspavdls.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtbdodinrs.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtiqwczbxg.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gthxucbifx.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtsfcgaufh.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtfwkbwyrs.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gtgjgakktt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtrqvkwugm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtfwwpqdht.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtomjwveva.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxdymezpj.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gthzkaavfv.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtdrjbgpwq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtmvsbowuh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gtcntrpigv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gtrlnemxsg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtesjxsutt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtxuunmcpf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtrbitiyny.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtcfuhsvls.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtctcvvcvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtnucvaqol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtekltckby.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gthkstujeq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtabetchkv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtbbabckha.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtdvtsketk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtueiljpuk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtgbmwvtax.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtdoznojlr.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtjywfnznb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gthwnnvtih.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrqruhhhl.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtplxblqoa.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbmrzccyv.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtutqohhlt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjttpgli.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtkqjclxso.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtintnolox.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gthhtuldkv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtdarfogvo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtcjxdmval.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtobvbllzw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gtbramwqwa.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtlpasjofj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtpjutmilv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtegmtvgzs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtauwcwdqr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtvdykyrzg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtlfhmwmee.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtedkpxvwq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtefgxpkfd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtiebgsxfv.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygcqsfuf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknyjzjgj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtlgjraojs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtwsjzuhik.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtxjyhsppx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtzluhtzvb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtqarodzpb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtfdleemfl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtfoyzkoax.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtdigkaudi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtyngybwur.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gttwnnjibr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtpilnlsri.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtkatqdfjg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtfjmwfrgx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtwivsbfev.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtqoiarhjd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowssyyas.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtedjqkqpq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtkpvsfaql.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtqnrkxzea.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtirjdffbc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtxfuyzihk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtxegomrky.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtuqumqodh.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthbuhnehq.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtitwzwopp.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtizizfkqw.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtxmszyzei.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtcuqdpqwo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnfdvqgzg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwgpyqnqt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtjnohbope.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtviocgfgj.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqckiprwl.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtexaiwtwh.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtejtocoep.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtoyifwpuu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtdzwffzvg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtijypnhrw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtelgxbkvz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtcqmdjpni.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtryzapyss.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaibxfxp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtdrbfofvg.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtsuzolucm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtefmvaasj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtjetpabwu.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtovfvcvsj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtplfnlvuh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtfcsjclqh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtapbmfmkl.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtpjzolucg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gttcvxebxn.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtpvymnbqm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnhqnxqyb.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtzqkqrxxe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtdysjkuoo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtgxzmbctd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtbvvumyac.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgyirqmb.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvkmffznt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtwgoibfgy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtpehmxcgb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmwlqrevh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtfpupqhsv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwmvrkvme.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtkmtwhqkt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtcjhtcqpc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgsizimrb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxkixuhll.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbpldqffb.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtjbobjqgs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtziifuaso.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtralyhewk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gthubcosgf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfaphleqk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtczlofyht.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtrdcdkweg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtaqxgglqz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtzzxiiqoe.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtdagxutuq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtkkzzplqu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtwbntlwvz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gttzhlihnx.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtgmhknnnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhnrgqua.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtkxirewaf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtcsozspve.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtwplayahq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcyporxth.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtotbpzwik.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyryrlcvu.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtttwfpydb.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtkzohvajn.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtyzvytlcs.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtawymaywv.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtedreamuo.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtbyjdmfpf.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtjgguvpfr.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtlxxhzuex.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtnlipkxwm.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtvtqnsdqu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtrtrstyff.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtmkdqjyup.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtsqutepwi.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtyflueljk.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtytpoyppv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtvxketvra.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtdfkyxqsr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqazmxdbf.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtopjtacvr.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtglsxlzuq.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtzcocxhzx.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtydcvygiv.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtiauuxuyn.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtssymhjxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gthhrkvdno.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtgnhwthij.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtldyavcyl.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtgklgethx.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtotojvphe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtlewxmsiz.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtrlpvulao.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtqppmrexr.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtumbmcncp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtmmkenutj.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtymwrouan.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtnvvwigwe.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gtbpueknjt.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtwappqfoc.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtvwmelhon.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtcoelwtnb.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfomtrzjw.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtinjcijpo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtnlfnlttu.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtkssvkalp.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtctisdigh.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtfistplpu.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtngphqfdb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtinqhvdhy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtjttdeywg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtmllspjxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtdpyfevcy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtvrlxdxig.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwndgwugh.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvtxqjuf.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gttoqyxikd.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtwuvtjymh.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtraekhjqm.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtyvpsermy.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtngcxcbct.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtsrlvuamq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtxxqugqqz.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtmessvgsj.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtjzckwnop.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtpzasypjj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gtxuutcyzp.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtqgldgqja.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtvxgespni.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtbvjztyzv.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtrtwyxjrw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtpulqhpax.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtzwvytnxt.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtnupkdedp.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtdouvzgzi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtadwnaezz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtnaurzlyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtowgwdxpg.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gthnclphyl.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtsgjqlsjg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtfdwquukp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtexrsduhk.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtmgbrhxvf.html


<!-- 参考信息 -->