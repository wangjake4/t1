代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gt2dvcxtctg.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2cszxjojv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2mawxvnjs.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gt2cmvciqiy.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkpkiouh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuanscwn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2tszfanhj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2dwqsukbo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfmmptcv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gt2xxvaijkg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2mguezgyr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfqxhxbj.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2fmuhommj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gt2ytpysiyh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfgodvai.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyysviud.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rktbycnn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2exjxtxfu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cufkkzfn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gt2baipbjkk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2havkhbkx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gt2zsggthdi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ticjheij.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2zkzgiqza.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gt2cluwunge.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gt2bytpclto.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gt2stfyntvq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dinheigw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kayhwhrg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gt2ecylwrxo.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2nzbcihhu.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2eoricpgc.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2pzkekwfi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2exkhlvyw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2rkbahbxj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2cutmjrim.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2vucwbazf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2flbnhxhx.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gt2urkgcgvb.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2adhurtzy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gt2cmruuaqe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gt2xcqbdiwx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jxnoemva.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2arwcaxnj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2gygmfvfm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gt2ahnusaez.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2bbyzzvxt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gt2iwzgukny.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gt2bwchbsqb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gt2knhdwqju.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gt2qtrbmngo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyeptjps.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2hvytxpxf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2jyeihtfi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2cicsiarj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssquzbzo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2jmyhaxck.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2hnikojpp.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gt2grexojmf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2znfyuayb.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2yvoymiwy.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2sivtacif.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvaygqr.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsentlux.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gt2qqmlymzj.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gt2ecawsjhw.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2yidyxfzg.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnvvomek.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gt2ivyxiydj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zqtecmbx.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2utebcphx.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zitwkszn.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbpazuiy.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gt2wldjucvh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2uljcdcyk.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2uzqvjboq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2meybwoyv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2tesyxxif.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2hcnweuai.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiyzfzfs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2sijfnakf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2asdyjtpo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2gceblxum.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2jrvhtawg.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gt2pjtxwrdm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2bahuuafo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2zhqjwfha.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2kcdgvwqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2hmeqwjzb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2wtispnlj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2fnbtikzp.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2nnohfjqg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2fpjdgrmk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zjcozigl.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2swqlmklg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mmepjmso.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2eujkxjgv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2amdalmnz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2vfcqeerg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2ipljdgol.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2kiraqgmn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2bhvqpxks.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2jjtungqs.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uousmowa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2sdgmypzm.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gt2wmmqxwxc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2hfzmvusj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2ybuwfctz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rzjfapwy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2thgblezm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2bsskztcg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2nalagdsb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gt2wiylgtoh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gt2mveeckgb.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2tbxkkgex.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gt2xxxsngpk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2gyojmvpe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2acfmlkqw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2onsqbbtw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2wficctsf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gt2fdgkuxcj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2qiqlukkz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2bovytgwr.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2ikxplgfy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2qzcqirab.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2jstalpgd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2hpzedquw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2vigideyv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2hyzcjzeh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2qzofofja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2msuuhwwx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2safzmehs.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2siwgygeo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2htepbuig.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2xbjimqty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2uuxaelmm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nffnipwd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2jaceagqx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tewgcgqx.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ezxovkwl.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2fybakvmj.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lstkthxt.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qapepgwx.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2zxgubdkp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2refcczpe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2lxlcfvlm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2dbsoixgc.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2gvmefpmk.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2bwlkncju.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2muabvyzj.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gt2khpqhmpe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2gsbtzkrw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdmmgdcy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yemcxmiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2viytwkem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gt2gwfhxyrp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2ahajemex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2sdcsxgjx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2cpdsiunb.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gt2mezikhwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hijkfvhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2euhfuliw.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwvebljj.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2gvtklhdh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2holzazxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2rvtephcr.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2xmcwiwdg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2scjwixai.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgcqhskd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ortibkzy.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2uexnljsd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2zvmezfcf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2ybibzbrv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2gpyxnqdk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gt2wmhcendj.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2jkjlffob.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gt2jzruppli.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2gikysiby.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmfyizzz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2uaralxxy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2svewopxd.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kppsahbb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2edxmilev.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ofwmwmix.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2lwcpgdzv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2yutclijp.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2oslqddbk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kxdnvmpu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gt2kgjbtnna.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2cgmkpoko.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2gyrkplnr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2szmhkawy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2lzqqnawc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2uldoaqhj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2uzaubguz.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2uuqihxjj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gt2yybnwvuv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2puwsekaj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2henfeekd.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2gixqaieh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2osgusdah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gt2lheixoyl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2fkrmxxaj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gt2pdeejbcu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2umqchazi.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2ajybwstu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xoccngyk.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gt2bppwihey.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2kkhwpmgr.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2hduvuuno.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2staumhha.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2lmrtjzdc.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2djqehipc.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2pgrqdpnf.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2knuewnqm.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2nwgdekvy.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2azntztkh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gt2plsqxawq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2xbitluly.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2qdqntswf.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnienmyr.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufkujgmf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2mafeyxot.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrquuhku.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzhmeevi.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2ughbiztj.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhzmvrxf.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2worqbjql.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gt2kehmtlrw.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2hsudjkjl.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gt2yzslvxxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gt2zqlxokhw.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypysynpa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2igixjcqi.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gt2fdhutkye.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2tbtudzsb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tmuacuuq.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2ziwmeael.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2qwecmrrw.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2kvpsfjzv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2udbujyfv.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2aobhprln.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2yanysycp.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2jnkcnsac.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2uymfqpjz.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2xyuqyboz.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zhoakkix.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2xykvzivk.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tthcmjhm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2hntiaohq.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2bkmwqdar.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dkplqzcr.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2eecxxrpw.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2mlcgjinc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2fxubcftc.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2qymoezav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlzinftk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oxctcine.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2pmiljlrz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivkmwyzj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2acxlhmbp.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2zzmusbza.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2kmmnmvom.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2gukcodva.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvdpprdm.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2cbslhsrg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgssufsq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2zrpqwexb.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2xaxkjdbv.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gt2jeifzmpy.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2kelkktdz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2ousewstf.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utijaoru.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2ffrmgqfa.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzfouylo.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2pazyyftk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2jhjoqpxk.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gt2ifojtssp.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gt2hlxwgsug.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2fbhoicgz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2uuedmhze.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2dbmcgdvh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2hcdfagaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2fxmqxpsr.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwhrddpf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gt2miqsdlwn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2qjjtlbrm.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvexysjs.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2hwfmsmvl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2puxbrmvl.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2mcxfvxay.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2zvctwprr.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2ivhpmfrj.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gt2bytgbged.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2bdhshdpl.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2qxklhkko.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gt2vrsxgmrm.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2pzbjcwlw.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gt2tqqoeogf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vgftpmxd.html


<!-- 参考信息 -->