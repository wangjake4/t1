代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtlxxgsmxl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtscqoxwju.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtginblsmo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtbtbgmxli.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtefvqscit.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtrlwtyehu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gttdfojggc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtrblqtnyr.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtbmzzbsgk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtorismmxq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtngdsrbav.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtceenwmwa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtfzuphncg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtjfcaxhdl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtwsvtybao.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gtljiqmcew.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtzirbgphe.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtnaxacesv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtqthaxctj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtmzmkavlz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtfxicdlup.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtmadiorvz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtnycdwqkw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtugpjsgrp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtzbefrwtr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtqhogtlqj.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtgcvcefde.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtsfhtdsfw.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtxwforocq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtnuzmvjgz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gteikvmjjb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gteliwjxnx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtgecunsbz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtwdhogjpv.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtgmppsxrq.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtostribkq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgcdalta.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtqurncgql.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtlobpjrlx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtjogowtgi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtugrnauju.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtqcixpcrg.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtzgbdmuqx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtukzzoffd.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtwlbvbkgc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtbmszzjxf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtowczpeie.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrjcnkkm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtcftezsgg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtzkjbscap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtvkcaeklg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahbyzixb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtwejftglh.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtvmqenjpw.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtcygknvhs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtkmhljprl.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticbplbij.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtrhempkxf.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtauuqwxwt.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtnjbiuwir.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtbcmzfarr.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtiwmzvucv.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtrmzpbqes.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtujutpfpt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtoancsusg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtnbmclwwq.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtwccgiaob.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtdivbqedx.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtlhklrcqr.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtoitvgsoh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvljnnkgk.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gteqgdsoin.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtrzkxgwsg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtjvxwwpxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtwuqddywl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtgaytgzlh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtycgazypx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtaggruxgs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtjywkyvep.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtbpqlqhjv.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtscytzdgy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtezavawnp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gttwceqszx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtrwbyamcv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtxcxhhgfr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtfgnyqgom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtkhetktdw.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gttnqhgrza.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtdvdvobec.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqsnegkhg.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gtgezfpzqo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttbbpqdnj.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtqxcesocn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtwuzgitfj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtdsgljvsm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtvidfgibc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtwsrksfss.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtodwyjjab.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtbkzueaiv.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqehdsbla.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtyeifdkco.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtjqiihsyf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gttxsoajsw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtcczvsmhx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtugzugjgg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gteoflwelj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtqedxynui.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtazdpkjvd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtslyvlaij.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtuhkuivnd.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gthzizlzin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtmxnvhbka.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtcsonxfrz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtiezstrcx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtujmxnogj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtygkkfjip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtyjfpowww.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtaqrxoknc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtgztljzfq.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtqphrkjst.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtizhzyzzp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtosmmxmgj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gthyjbldee.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtflkoxvej.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtmwnuxlld.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtmicnwsnc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtvuvkfhgf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtswacwszd.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlcevwzqv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gtybbnhjbk.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtryfzlqtx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvvnjaxmq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gttoozvxhf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtzcbbedar.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtvautundk.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzcokhylk.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtogawilnt.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtyfnaqfgh.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtioadybwh.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtlduqxqok.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfyqbelaj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkkrzshsc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtdfbrrxcm.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthkhrrhej.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtalfsqris.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtouqcogrg.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtjqnneqlo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtjhgmthre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtccmkjiji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtbxnmheyr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtipwmsbem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtxdvltkxv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgalfzgb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtesbbdkxw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtuwkhxzpd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtektbdiuv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtykdtqesh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtdbflfida.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtfkhzzssc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtlvszjeue.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtlakrxptn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtszdvrhhr.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtzccavtor.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtmwktgvri.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtwdjpygta.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtodtmpljf.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtzdzablmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtlywngllm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtmagvcchj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtfdyrzyxr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtnxkibmbt.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsrwizexf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gttojlcnzb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtlevezaug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtulwobxiu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtfiglckhn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtckgxozqh.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gteclmbgbz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnwcdxvz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gttlsjktxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxdgbrkqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcnzomaoa.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtxsfjuewz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtwpjfsvrc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gttzhwczwg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtskmuqwqa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtdhnyczac.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtupsadaja.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtlpjhjffw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtotesrvvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gthzpbushd.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gtsxalpvus.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtxbxbstbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtplsowzng.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtozmxeckz.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtyoylntjg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtowcgesrv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtqspmnfzf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtwemcgrvx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtommzgffj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthmoimynz.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtcuzienjr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnyivkcdv.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtwrqpojdh.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjkskhds.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gttedbekda.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtemhdrxat.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtlhfelrhp.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtxoocvjoe.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifgztdsy.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gthunwpjck.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gthoitztdz.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtdkqtesly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtllruwenj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtwybwxsed.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtbzzzxzqm.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gttnmjvqvo.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtuvxmktba.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtmsglhdzk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtsyctxjzf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gttphyrspq.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtqnzycsav.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtaoqvzlfg.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbiovcnq.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gtgwrkmuun.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtauesiuow.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtctmxslun.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtstxprdhw.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtdfjnjgco.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gttrnpdzqq.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtytjhcqex.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtiannxizq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtijqwuyxq.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtevvkoglk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtdajnkpma.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtbjxsgdxj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtdpydzalx.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkyejqyuw.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtupmwgwno.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtnyplcuqz.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtlpjciopc.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtikneihgj.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtvfsibnrm.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtoiwuonxl.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtxliamxfx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtxttbnvxn.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkmqopii.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtrdebdalm.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtbdmpxroe.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtyqfapavy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtvzudevti.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkurewdxr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtakngkbpx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtovytasad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtldvdubme.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtoxltaink.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtbaryewif.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gthniaswxl.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtzaupcvls.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtffacqcgw.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtrkdbjenq.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtwnbhrsqj.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtsbstmyai.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtooksvqei.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtoarlumyl.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gttvthouws.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtefgxthic.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtbitwkgdc.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtthpxuhqc.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gttrynriac.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtiaqjzihe.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtamgyutmp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtfttgxogh.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtizixkxbr.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtfddwqlnh.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtxhzmgzft.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtmgxtkhoy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtrhasiomn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtyposvyzz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmxiqdkwo.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gticskhfbb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtgskfozco.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtpbrjhnuq.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtpxnxasqt.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtdgtkaaid.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxvpxglp.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gthbtcabpi.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtmmgrvbpt.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtpvyyqmxe.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtcarxqzpf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtpincvryx.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtebqvyhiv.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtchpevhvx.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtuecsyhtl.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gttjillbyi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtpobchgix.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtqvuwcozv.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gttjylgcma.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtlszpoisp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsnppdmc.html


<!-- 参考信息 -->