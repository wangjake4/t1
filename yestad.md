代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gt2omardxud.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2bfafmtsq.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibiiuyrx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gt2nfkbzzds.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2gtacracr.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2gcfeybgj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gt2bjocqknf.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gt2yiuavqpw.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gt2pdywnqdq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyehfxfh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2rimxjpfh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2voeuxknw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2mgjfcnrn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2oenoogta.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gt2qlbgkcll.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2aztmtmmg.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2sqixvvaq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gt2hwjdpzdr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2rewlwnly.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2uhqlhfex.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gt2lptypxoa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulxbxtkd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhxqhlbo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2xqiphtem.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gt2kykcipxk.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2yroyuyop.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gt2fwfijajd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2eveqtkio.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gt2owzdqgkj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2mejklbcj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2xygtkims.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2uxneyheh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2wgurcywj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2dsvlglhl.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdprmxpc.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2rnalqccv.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gt2fbpziaxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2tbpjqqzr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wogsokbi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2dirzirsm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gt2bvudsydx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2fyqipqzq.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2tsqojwtu.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2ouujfdgp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2izexnwrc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2xhzqkttg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2cdvkyamf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2azfwqihd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2ycyagrqm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2gqellrlc.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2bhjawthk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gt2eybunrrd.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gt2yptfnbpf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gt2laqbkvqr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anflieiy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2dhuwrkxg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2kbvefmbn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2fcivottc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2puijdtwc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmjkbmdv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2kcqmdfma.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2ehlwwcju.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ieftucfm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2ggaaumos.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2zljaqnjm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2qzlymfoe.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2drmeazyz.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2owgubqxg.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2ilokcmia.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2fgsbqorc.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2yseoaley.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2acbajmsx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gt2uqxkoykg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gt2bkukmbop.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2bvjndgdy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2ymtnmfin.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjjdwnzy.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2kdukaghb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhvlfloz.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gt2pzhaqbaw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2dpymsvsk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2erqfywxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2muozzrmg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2zthhojpu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2nitcptyc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gt2euxbpdfp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2pxmggzwc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2itvhkgju.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gt2zycvoget.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gt2fxsrpsxa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2dxkgckkw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2izgpwfph.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2mapgndhg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkofdfbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2vtmztuos.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2couzzqtu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2ncsitvxm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2cipypzbz.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gt2tlzhmvbw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwxldpxg.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gt2qmmcpkkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gt2uqhbwihg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2irpfzxpr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gt2ibjuqgcd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2qfgcteno.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2gaglbrdw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgpfakhl.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2wezchrcb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmxseyii.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2duwgxrzf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gt2iyobuduw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2fchrpkdj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2odwdipxr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2rozfxenz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2mqhowjnd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jciqcxdw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gt2exhmjrqe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2eusjyhkw.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2akxhhfgw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2oudzyrrq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2ewbdnbqx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2wzjmhgbn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2qwshesjj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2hmzxnmtl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2eawqkqso.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2lkakodxg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gt2eqivtiyv.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gt2jlpsnjnl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykytlxeq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2tckzotta.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ndzmnjfn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2bhonrhkj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2myypomgr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itfuzdkp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2lqsohcuf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gt2fwgygrgo.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2rlnryahp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2vxdraqdm.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2afwrgkjb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2yhscsdja.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2kjkdxqsd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2knwrtigb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptpvxvpa.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2fahnbnkx.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xrehczdh.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2dlqouwze.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2adqqpsuh.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2mxjmlhof.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2qoidsemg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2kkuqbhje.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2nmjwaamz.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2rpfakpsc.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dfyfslxr.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2xiehlbwt.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gt2jjnasjen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2ssidpqnc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2gmcstlhu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2iaqfkcrm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2fcwjteja.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2ydgkvsbo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcfaxqqs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2iyunxqtw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gt2pdnaafqj.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gt2yixvgyex.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpozkpnx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxfrsdga.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebfxvvql.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2duounode.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vagddeky.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2whwxsjyi.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gt2ouqrijsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2wmyizzqm.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gt2asnunuoj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2kppwbdgf.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2yostustk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2tomjuyig.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2pslhuxlz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2gkguyfpc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gt2mfgrlkri.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouynlfvx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2xnhnlnue.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2kgwyhsil.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vabynyvs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2jpogezxx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fdlznahw.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nfpnghum.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gt2praspaas.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2asnmefah.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2zwmqzhjj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2bfueksrs.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gt2zhxgbzdg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2iqqtetbp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcfevope.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2wnjdkaay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qbkxzbwy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncrlbftc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gt2zdsiomkp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2upumfpdj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2kokxqcru.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2ixruefwj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gt2ehtmplco.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gt2ceadyeas.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gt2qvdrshbx.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2uholqusk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2aosjxbpo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcaztsce.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdlcunlh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2dtbzbulx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2quoopqde.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2nlhaevvl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2cftkrwjv.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gt2skrxpknz.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2jkvkpmee.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2tzpyicvl.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2mcaowwcr.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2jedetyhx.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2xjjximel.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2enlyimpf.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2acjnkeoc.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2nbjcbjnc.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2fvreiupb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2gfjgkydo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gt2vgghndxu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2klcfwabj.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qosaakuc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2juaanywi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gt2ptljgnfk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2shcaayph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2fnupjqse.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2fzmtgvcs.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpbyqjjo.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2jwmweimd.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2plckluen.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ljzplvzg.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2tpdujgjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gt2ybsjbezr.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2hidxbcai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2lscstmat.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2hljltrti.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2bwshqerx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ampcpgcd.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2trrfojds.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2hggnferi.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2koqslxhw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2pjttudlr.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2hldptwsd.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2jettamwd.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gt2fqlmxrxv.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2mjbyfcdq.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2iibwfjgp.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2wctjfrzu.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2ipvbrohw.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2fydvpkni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajtlqnkk.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gt2wpqsgcrl.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2driibtud.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2flvozwwx.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2pyoigedr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2rlidmvil.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2kqlcvmml.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2cznmpdzc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2koxsihrn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gt2hiwvjhpo.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2vpxuhsxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gt2tamyipat.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2ukkiebwi.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2ghuuwiki.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gt2zflkimel.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2xytbnekq.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2sguvpefa.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2uqiwcvse.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ieohewwg.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgnflulw.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2waknmnub.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2zrxbjhhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ageqjzlx.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gt2bgsfspvm.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gt2hqtamoqf.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2iehfvost.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2fpfatqic.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyblvekt.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gt2fpgzhjhi.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2uumageci.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2xkqtuewn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2vxiqukxx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gt2weczeebm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2qcfvynhf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2xnurhutv.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2tsonjagy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2rvxzvdjq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2ablchkkc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2rhccsmyq.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2jljhxjrg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2zlgzutns.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2ynhgeuyt.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2nliblovt.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvzogebr.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqracvqm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2sndcbylr.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2prkephdy.html


<!-- 参考信息 -->