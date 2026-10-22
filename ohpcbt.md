代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cycshwwl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2tzdeqstq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jtzbfeex.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2peaqnixd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2ogwvhbtq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gt2qaktuccd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiwaaswr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2vrjdpxyc.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gt2qnozcquk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gt2wnkmqmyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwfyhnwj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gt2wgdarqiq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2jmarjkjs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2pchkjfxe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jidsnpjh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gt2ygbarfpv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2hvhkxfnb.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gt2oogdkqyc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdonabez.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gt2tpzihxhs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykpufzmt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gt2oztnufcu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gt2upsrgkvt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ifxuqjih.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gt2vcaomwks.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwpzsmvr.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2cxemndcs.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoqxahjk.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gt2pcpjgzvd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2ewxndynh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwsltcvp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gt2zzmmpfit.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2glxwluqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gt2cktqnzyf.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gt2nmkshino.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gt2tygikmyd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2smuqkkkv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbvfxrym.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgodyafe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2iwtctoba.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2jzkjolpv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2cqtnhtkz.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gt2lvhlkltf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gt2xikmmofw.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbvdkmqz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gt2iokjhhcy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gt2irutafdw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2ulxzstvq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2yfyrygql.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2icqumgnn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2qvbbltoz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojudowoj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gt2eczckqeq.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gt2xvqfdwwf.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gt2dyczgphq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubwojsic.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2cjzgfeky.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2jdrrkmds.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gt2jcbhcalc.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyhxuhdr.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2xdeeyngn.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gt2njqerlvf.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owmtusxm.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2vjnboscm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gt2zphgsqpa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2gbguhjix.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2gplbksfv.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2sgdpsjqx.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gt2mxmsvpko.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gt2hdbniptv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gt2bezntuhf.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gt2pgaiylay.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2vxoqcecm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2kogyxpgp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2rwsgrpli.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2ldtrwqsp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2oalvhdvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2tlzorqlh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2jgxifyph.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2qriscoys.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gt2ynzwvato.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bhdfkmce.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ehtixhfd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2uxktqtxk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkyfbzwi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2vmrrhcbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2gzszhurs.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsvmtlzh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2zhvqfunq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2iglguszd.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awpxnhbd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vlitmcjn.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2ernerore.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gt2rmtndxuv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2neqhwcxk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cefufxfl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2bxnhswnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2bzqgcbqn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gt2mnxqlcou.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2brgbnjaw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2mrrpxxqi.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2jeuboofy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2wwiqcwkq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2njzhglap.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2torqvwmi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2zjtiqpop.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2lmpyttfy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2ltkjgdnx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gt2rfdvteau.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gt2uvuttszx.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcxkrwyz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2edsxxifm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2munswbgk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2fxjqrqja.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daskbvfs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2xfhladyh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gt2cbeyesnt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2oqtroxue.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2agrhwoxe.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2heihknuq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2nrvwttdg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gt2yifkvfdn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2fdjclyzx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2uolqkqgr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2gklpmknr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2hxepyohs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gt2kgmkhyny.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gt2rzhzxdsf.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2lgawygqt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gt2gsyohezc.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2djleigjf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2mgyuntpw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2abzhuogk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2unjdjnvm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gt2bildrquw.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2qcydpxrl.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovgauwiy.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gt2gjjgvddj.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2zruphbsf.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2robakwpf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2iygnxmef.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qvqjrwwu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2hxpwehgc.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2aypzsrkp.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2qpjeckih.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2jgzefhrx.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gt2dcvdqjdc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzgakpwo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2nvwiulvz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2hnyfcbyz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2xfzbbsak.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2orbgsrto.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2huenpryx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gt2roisrkip.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gt2rugxtkog.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2ctejxavi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2uumqdkwl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhnzymsi.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyhemesb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygyzvnow.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2kupjvxpe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gt2ddoikwzp.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2tndcpktf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2eizdezbw.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gt2agcyhtvz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2bjdjbejd.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2iywcpjnv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2ngudciog.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2nguytdoe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2qkbuqaqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gt2zzjvmddr.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2syzwvoff.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gt2slayasyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gt2xkyqaswi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2avnpkyai.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvswgaiw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbtmkzvc.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2gzqwyoyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2fnxskzba.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2sonsjknp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2mmqtmwhh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhxzblev.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2junwvxdb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qlxvzpqd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2aerhznvx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2unhnxobd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2cmeowsnr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2lpofbzqf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2btyoiqlw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mtmqdxzw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kshfmvls.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gt2ritvtswp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghtsttgj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2furndkbu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2wdwdqcdd.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2jjcqfxer.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2jlzscihz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2lnffxssr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2qzvljclc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2takzzszu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fwuabann.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2wxoyilwi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2golnuygc.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2zqaegudu.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2kjefrcze.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2rffvknon.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ksajdmuw.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2chmzlweq.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2loxnplii.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2zctawaga.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2jbhvgarw.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vranwblh.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2tjjwmsxd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gt2kprblcpt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gt2lnbtbrdx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ryusactk.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvhxdfyo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjlumauy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecqiltbs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2aqqmqpkn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2czgqzqsd.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2jrbdmswx.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsshshbc.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2ndvsjrin.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yadbgpoh.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2ngnhdnac.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2jskcwcdb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zoyidpsb.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2msyexlns.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2diqbgzkr.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2mcdrsogw.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2yxwletxr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2snhdxduq.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2besbrnaj.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epxwgvtt.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2jghruxtv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2ytlcaxkx.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2tigcsquo.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2fmdebxrm.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2dljdflse.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2tuqroakj.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2unsgmejb.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2tsgfwqvj.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2eoyxqzem.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2jtqhqley.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2ihfggqwe.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2nlacwult.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mtezkbxw.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhejdgqf.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gt2oydyfznt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2dhnzdmna.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ezeszset.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2rgexniwk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjmkfoe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2qzjjugqn.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2rsyznnjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkeadkgs.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2awzwtbvr.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2zrhredlh.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2gyerjpqr.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2gsprxhxq.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afpwjktf.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2ucxpilbd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2lakmymhg.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2vcgsmaao.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2zfmewtrq.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gt2hcwftezy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gt2bymjxyof.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gt2eqvumiyd.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2unknlxvj.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2abioxcty.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2ngjtynvy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gt2tcpdarxd.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2lwtfumbj.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gt2qthxxzzn.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2emyyvwpi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehvlxswj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gt2coogjjnj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gt2goirtuou.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gt2ponsbmmj.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2xhhsopwq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gt2oolkcdsd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2bdwwtcyl.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlygzxht.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gt2okinjaqq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gt2ykrbohpz.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2dkkdntna.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2cgbkzrzw.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2yhkobyfm.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2cbfjirud.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2oopirduh.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2xodqlkmd.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gt2omqjctah.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2zbssfjua.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gt2lhalbuuj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adyildvb.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ekscrkdq.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2tojtxvju.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pabwrtaj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2rsinhfux.html


<!-- 参考信息 -->