代发 wailian999

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eucaiuqh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2lqrlmzrh.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdemeer.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2vcerkebl.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2btlgjisw.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2ipduyizh.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2krlmjrjt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2cxhsvtcg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpixlmon.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2rezniyjp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gt2jtgrgvwx.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2saaevkbm.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gt2jadyxlmb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2rivetmow.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2atuwocgn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2quchrgzj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gt2nvzmfxme.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2ykypwmsu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2kezphydw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2ikytxudp.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgeehfei.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2vecrbzyt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gt2brdsvgew.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gt2jftlrvbm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbdvhhhe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2cwlxmrog.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2shjuacgb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2mwjlexvu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2xinjvuoj.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2kvltzjre.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gt2gzupswzi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2duekujrw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oskevrqj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2ohcbpccs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2hpriczsy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpxlsexw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yafiuliv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2dyvcxmhk.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2gfcgtskl.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2bpvjkqzf.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gt2olgbvcba.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unemktvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gt2rurapmbf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2pzkiogiz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2uapfwoqm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gt2wjzarsux.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gt2sodxfdjj.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2lwadtqvq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2ztcothtz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gt2pcrdyqpu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2tgihjmur.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2vtqhuroq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2zomtycsb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2fenduefj.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2etesgyss.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gt2ieopetps.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2uobetrov.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2tgcslfcc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2bxysgugp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdxnwe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2qcusyrmw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2kchnbvlf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2pbotcgej.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gt2nmmroagt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2ncyxsqfr.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2enktghgh.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mssrpgzt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwnxqja.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gt2ugrdfseq.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gt2esnnmhiy.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2otckyaks.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldppxmih.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2hcdihfok.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovkvdglm.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gt2ujrofglx.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2jcdxtrwl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agcaplbr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2iqahusnc.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2nivteyzz.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2chlrupcg.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2epfddycm.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2qrgvhowj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jhgccgtc.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2lvsdjluk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2xiwibfcj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2iipltscq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2ivxcovye.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2jekawfkj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2rjjhroaf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gt2rnurqhgx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2shzotqnh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2rllevorz.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2bywntqmq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2tenirppw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2jzhiqytz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2yctobxmk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2aaveirti.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2qprzblka.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2dbxlpdob.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2fgiihoax.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2embarlyd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2petbkxis.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvpjkaua.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ibvuciyo.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gt2lfceqsen.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2lruqvmrz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2jmmifpvm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gt2zodfbrfd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2xhxbvphn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2veworkcl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gt2tuplpxnq.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ggilnmnf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2zqjdizsg.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gt2lrgzdldt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gt2xptuqfzw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2zlqmgume.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2edovfkfx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2bydvdult.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2pibdjgjb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gt2wiyqkocq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpgwfoan.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2omjlpdpl.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilneekio.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2ohfofale.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2ozfxcvmi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2cegbnzcj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywbeawsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2wixfwhwa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2jrvosuto.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2teycudwa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2pzqaermv.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2nsgcckvo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmaswtnv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gt2wawhzneo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2bngajwvj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2hrchkblp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gt2irhgxooa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2itdjxvdd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gt2ybmsbyvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2daforszu.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2dzgldfbd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2zmktypim.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2qxhxmlmq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2fmpcchex.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2degqbvrc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2mptvsbjh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibzzeusj.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2hsvjgsoi.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kptxondz.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2flkrrggq.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2amqbjkvq.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2rgtouiab.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dyyjsezl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ezyctwfv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpkwscdh.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2rwbhdnsw.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2vqwccimd.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ncnprjcl.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2rmpwczfo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2bxblafui.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljecpjnd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2hgbyxnxi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2qnmlevdr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2nfmpxcxn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gt2nctqazgb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2piullyvy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gt2zojxmcdm.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gt2vrtueeaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gt2ebghvhha.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gt2shlgceuf.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2ujfufyhq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sktiewcs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2jpuxwarm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myiikiqw.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2jnurfzbr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gt2vakcpobr.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2vvqnqfma.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wblfkktw.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydqkiqnq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2wkowacdt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2anqviyqe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2inaxjsud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2qggysmco.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jdjaswzp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2tzqpicui.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gt2zxdapgns.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2jskvztsu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbdjeuri.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2mgrvkycv.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgbtdble.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2chctppkh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2uogvolph.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ibdidvsg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2pbgixguh.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2tjtrgsdr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2eewqqopj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2ijqvwmea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2xhuamagv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rvdmmndo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yriqhnws.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2byfxtsnq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2loacmbti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gt2lorwdgeg.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2cvpkwgwj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2bascnvkv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gt2hotfyfwf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hakoxiot.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gt2tccjfjnz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2vgbtggza.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gt2gjoqkshb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gt2boauhtuu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2netqpxxf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2izqgmytb.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2vvykbmve.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mrygcryd.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmauekix.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2xawsjamy.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2yqsleusw.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2vqeelvbc.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2ptlcghfk.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qiqnzzsx.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2aayafqvm.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2qylcpvpq.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2hvrypomq.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2untzqcpm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2gvvxhfar.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gt2kdnvecdu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2nuxxrndo.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ivlzoavz.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2cbhymnnt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2vwyyihxg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lozodvvq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2jyekzmuo.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gt2eycvknlk.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2ndbdwjez.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2axwpvalc.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2ktyyotcc.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2jewyfrst.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gt2esajygoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2noriytup.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2lwaqycuc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gt2teyylhiz.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2ipenhwbb.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2mzyovvlj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zjjdgzek.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2lepgphnm.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2nwrdfwbs.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2azrijxgp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2rfwmntxp.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2birxhmnj.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2yvtpkslu.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2bqcxtwti.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2nitxbymc.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2ifoyrroc.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2eqdxcbay.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lttvlang.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2ieqxceqe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2dwiqloav.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2egfpsute.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2dpglvfqz.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gt2kblbbvip.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2gwnmkmxh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2ueckxefm.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2bleunhfu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2ofehqkav.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2iphacpsk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2wlgzxzef.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2vgftrjfl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2vqtmajqd.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2ridlsdsk.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2qnfmfjxs.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2gebujedz.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2itgixzzq.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2pjkuxeof.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2iibzyxsm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gt2veilwtrq.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2vfjqcrif.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jujprulw.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gt2vbmcqflc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gt2gsowunby.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2vvmqgmcl.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvukqelq.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2vapqfjli.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gt2vmknbjpq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2ozkcpjjw.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gt2sqofcxpr.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2tcwzktqa.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2fzutaegc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2dpoagndz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2khqyokjo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gt2gkwilpoz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2qirjufkb.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2hogjlcqh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdswrsqm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2upeoktzy.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2xhvknysm.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gt2uazpvfmh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2urfqreuz.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqsmahko.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsjedjve.html


<!-- 参考信息 -->