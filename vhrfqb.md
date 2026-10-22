代发 wailian999

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2toxgdefg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2tjvehwtm.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2srzugxfd.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2gfufxnap.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2rzqlrmfy.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2tvkjoxmi.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2sthcuwfb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gt2ptdunjca.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gt2fpimxubo.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2nehwqqep.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2nboodvmo.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gt2qwqkjcmn.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gt2orcadozn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gt2abrmkckg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2junzivyg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2vcmnzpol.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2smfqixsn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xixuwuoy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gt2jxywuzqu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2plzawaqe.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gt2vaqcpldb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2rbcplcfz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gt2ymswerfj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2qzokofqf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2lafodylb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2wwwuegwr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2bwrekdbv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gt2ozwgjvop.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2nvgggssf.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gt2uqqyuffx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gt2zlrzsgdu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2zekgfshe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gt2vvpouxta.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2nmregsba.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gt2fuuocayn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2kjshovqj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gt2ihqhjkbs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gt2qajlvkvj.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gt2zfwpbdzu.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2upucnfon.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2htlwcinl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2xtapbqqd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckufhowm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnkbmtkw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gt2kndvaaxm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrisoyul.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2rbahucfu.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gt2mlxuyhdj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2cigrdlxp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2ueaetfpm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2fkeshocl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gt2gwrukwxs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gt2rupexlow.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxxjhlzh.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gt2szimyovz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gt2lzocnvzw.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gt2pcclqccd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqysctfz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gt2czpyzoqk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2elezkikc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2scdxpbir.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2jkordxja.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2bzuaqqmg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2oihyajgr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2wakpmplg.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2stineyov.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2qwpqdjmp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2eyqiiylb.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2zwbagahz.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2cpuhjoxj.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gt2pugbnfla.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2ujsnduqp.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2mqbykmdd.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gt2ntrhknhs.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmwlzkjk.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2uxhmakfy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gt2kdvhiseu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dbxllyux.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2vidtijaa.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gt2pzrozxrf.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2maqspmvn.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2dwhguluv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mmsjzulc.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2mhdkhfkc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gt2qnxptyvx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2xwapbqia.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2yqanypgz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2vovynssa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2oxhmtwvg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2nwabpbnw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2vlcwyzmr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2ltdujwvr.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2atmydkzb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gt2iqejmsgv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2bbcdkmvd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2rfywcqwm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2ppiytfjn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrikonhi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gt2gbiwugnv.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2fonluckn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2yuqsnuvy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kctikdma.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2oxjrmosn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2mtaynmpa.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gt2cjwxwvuj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gt2gciomkpj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2hwzyvoyf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnhkxxfo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2jnvcbcuk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2qbjenwqq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2lpwsttkk.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kflznfxf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwgusukx.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2izqdrqkh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gt2gazsjkcw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gt2vyxdeskd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2ceombqwh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2upmvigfq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2wmuiaajz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2rvbiophg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2ehpjjkxy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxgdwcwz.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2iggbzrvg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gt2jysfnnwr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2jxdjryeu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2wiibdzpf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2gtwmrxkk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2ixqphajh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2lajfukms.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gt2qhbzodpn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2kvitgzzo.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzllyvfn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2sjipbhyp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gt2catbaxzl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2dwjmfjof.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2octdbsvc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldbrseul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2fjimbbln.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gt2lbiplmnw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2oqfrnoll.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gt2ftieomjo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gt2ezjguylv.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2dufwrwht.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2kcelfvfu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2qlxdktto.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2amyavkrw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2gpusgduq.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2jimmkoee.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2oosgogsz.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gt2vpamcbrp.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zkddsnpw.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2wkprfjve.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxtdojza.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2lyybqzks.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2yxmnftef.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jwpbloff.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2jeojiqgp.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsngngwl.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gt2pyatumel.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htsognfb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2wwwydzrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2ekyaebez.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2mcsltiwt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gt2wzmbzqhu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2mkbqqzbc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2inmbqtgv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2mredkjso.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2xbwcjydo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gt2btwvenlr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdpvxuys.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uoprmnmd.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2gqzfewzu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2opiktxxc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2hxzlgbhm.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqnqposv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2amszxdex.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlkkkahl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsavpcvh.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2tdsxqjcu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2fzzizbhu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2dtknxspk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2mfydlcfo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2zaharqvy.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2zwvqiffj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gt2dcfvwgaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gt2jkvelhej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2njgohejr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gt2drxyumoj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnktwbkq.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdzubqbj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2ngwqaivz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2advaerfl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2fvribxhm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2nlznwjdc.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2thqfdeoz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2wbgacfaj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gt2jefggopn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djddjiiw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2fbxabxrv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2uzcxbmcw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gt2eybrevzi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuhlmbmm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2pdpjawqd.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gt2gvnynwaq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gt2aqdrrmyc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2piqaoinl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2mzkkqyaq.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gt2flmxbvtw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gt2pfgklknf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gt2uvainmfy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gt2crlsifec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2njinipqx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2yqqtvduv.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2frmcshza.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2cmeglrwu.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gt2wxoeaefu.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gt2lyrelgle.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gt2ayhwtxhu.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2gnnaquxs.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2knzexpnz.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2gaabtpje.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzortrnm.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2ugtueyzb.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2askegucq.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2tetmqpte.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gt2gzamrxfi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2uwihjrht.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2jpbjajix.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2lfvvlerb.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2tjtcxkly.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2tprogwwt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2oxqgtiug.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pevzsfjy.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2dkdekrqa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jswlyjtj.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2wycpvppn.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2frhvgvvr.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2zdirmlbc.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gt2ammijknm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2psixdegn.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2mymqpsym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2tueyczwv.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gt2kiewafex.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2lonxtvft.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2zoedorwj.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2yrqwmeho.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2opgslyzf.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2akojvbvk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2ofhtcytf.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2fzjsosvb.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2ntczlbhh.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gt2zcqotpai.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gt2eyjdpdhe.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dvvjnqoq.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2lpgfmaof.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2skvhdhnn.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2wgandlgl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gt2wvpehtbp.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gt2arluumec.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dzeouvtw.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2rqpftlmt.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2xmlnhfdl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2yyhzyxwn.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2lcpwajll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kytgdlog.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2aizpcqnu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gt2jvphmpry.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2mlskfpvp.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2dnmlflnt.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2vxboqxhy.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2kwemyxti.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gt2hjbgstrd.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2xzjophgb.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2mqfkklra.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2cmiehesm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2ndnoybou.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxntsmfx.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2bymzfetv.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2uslfppti.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gt2ixfwfsbi.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2bxhzpjvi.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2pkbwmexx.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2hspgezbs.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2ucyonbxn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2awskvlfd.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2utjmkgxd.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gt2fratvgac.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2bqxcvpqu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2uziczxjy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gt2qyqqtygo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gt2tzibawsq.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gt2bevhtjxs.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2xevxkifn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2vxtugslz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfgrzfrf.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2hrmjnyot.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2yurromay.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2ckanablz.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2bpxonckd.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2xloyiqqi.html


<!-- 参考信息 -->