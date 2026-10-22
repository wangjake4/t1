代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gt2vdhdhokj.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuzvuyxs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2frotnnvs.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gt2spelxiqv.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gt2gqbjptkc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gt2llymxfbc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2qpwdvaht.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhcygqkf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2ooqjstpx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2jsqyflqb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gt2qilqoihp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhethq.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gt2kfkvzgfe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gt2pyjrjxfk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gt2qxmeeome.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gt2xfclzsqn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrmwboe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2ontoyuhz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hswavacu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2icdygyif.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2wcuphxkl.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2sfvrgzze.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2qyomrfnr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ebfgwqii.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2qxafjidm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2tejlsklo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2zsppyima.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2vtyyqfti.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mcdveogk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gt2pyenxahs.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2duwiczdv.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2tqzaixdd.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2efyfwost.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2gtosxgrr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yflhxxrz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcttrxmm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2ullzjgye.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gt2sxowgebw.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2gljtoeck.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2lkcgbfkb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2iewlmcom.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2khmsngxn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2yaemjifc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2wtxnecai.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2giqnhpte.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2idgzmplh.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2tzpfmatz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gt2pppurenl.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gt2causzery.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gt2fomaxfmn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gt2xnnspuen.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2rrfvfhng.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2epksjrak.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrjudesg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2tnfudbha.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gt2tigrdeqs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gt2vdrldutc.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2bnnuyabr.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2pupivsur.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2vgveeckf.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2xjfdmqiq.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdueenoo.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2nqygmliq.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2kcslwbge.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2czedrnly.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gt2pkewuiyb.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2xjxmvurk.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gt2glnzjraa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gt2iywsuiss.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gt2rurrmnem.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2snwdpcmp.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2wpbyvoch.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gt2vnmrwxcd.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gt2bqkgndop.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qaeolvsd.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gt2weudbbxf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gt2dmwqtfrl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2ohztunsb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcizeihq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2hravguwj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2brjmuldv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjxwrfyb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2sifgyblm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2kakztdxf.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2nttkdktg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gt2oqdrmuws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2kvsqqwps.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2iimdbqqh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2ixdgebjz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2ywjrdekp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2mvhaawzh.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2enyctmxt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2esqombrw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2baaqelvr.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gt2bizdakcs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rhqrqdln.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajwdowkt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gt2kbuggwdh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2wbhekojp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gt2opoltqwy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2ojxxaakf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfeajuvs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gt2fnjmarpl.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2xsarubjp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2aivamtpa.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gt2clpkzqtl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enggvmia.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fgujcgkc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2ihkoyvli.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2uqzregfk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2kwdnjyzi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gt2zgsxonzr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2ijdbxoxx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2qnelnsln.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2vrwxtftt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2tcyqfgwz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2enwvzkyu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2rbapbopf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2yndejqzc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2ztbtiqqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gt2fjqqgxcg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2xjpatuan.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2vzhfmuvc.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2snuzuznr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2reguxced.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2snqtladq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2qqmiyvmz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzbgdrrp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgfdjltd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bikngfit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gt2yqjjsbnk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gt2pepakkgw.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gt2mhjpmqfg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpxgpvkl.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2mbhcsnwx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2lceewtdg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2cbypupbg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2ssqmgyub.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gt2npmxooip.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2nrntazgr.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2wmiflshp.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgapwwft.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2nrblyida.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2npnbreto.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2afjowbjm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2hmwfmphc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2xkaeqgcw.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2oblhuqrp.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2fnrzodzn.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ipiejjze.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhdzohhv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2fgonuano.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gt2uxuncnwb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2ymmkkcun.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2edgmfuvp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clakevql.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2uxdivmyj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2rvcgnskp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gt2zkrfagan.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gt2tzwnufof.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2gcxehxrh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2zcmdojdl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxijgwi.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2zihjimjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2hrauanqy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2klgodcaa.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pehmsdju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2iipqeyxo.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2kicetmfn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2nysbopvs.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2csiwbpyw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccrqsbms.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2gehbrext.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2zltceijh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgzalltu.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ebytokle.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2hbeoisnc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2ismtnmoc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2poohamzk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2qvwffmwc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojutanbd.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2tqmpbqsn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2hujdbeqj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zplmvfet.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2vihkkrqh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2navxwcii.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2dwdexwsb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2dqfwemfd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2xhwpyslo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2xisribia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2mmywfonb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2iostzezp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gt2rjmtrjgc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2xpiqeydz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqufelfv.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2nzkzfufd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gt2kqwxfgnl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gt2huxqdjec.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iakzhxyi.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2bwgnxhig.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2anwdkzph.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2wxnmvwqu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2dckdjuwz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gt2ireypygq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aowtntej.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2hgbskxrk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2cirlfskx.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2kqujgudr.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gt2vhwwfnij.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hmqbxymq.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2ymgmlwxk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xetpuaxy.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2veepgbcc.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2exxinsfa.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndlyhtac.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2xoxiavar.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gt2dfkwluuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2wougxgbp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gt2annbypjx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2bnysxhyw.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gt2enrxsjpd.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fjgtpvmn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2ihsdqcpd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohrrejkv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2susuhhet.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqqzaery.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktyrjsgd.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2maxhjimi.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2rmjpkwyi.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2iulutlyn.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gt2zzvfgzjv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2oqramfll.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wooaptdb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nugzvhap.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gt2gdrroejf.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2bzgpvdcf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2jqbsrjus.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2bjutdpqn.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2cmpngmcy.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2mnkvmizj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpmjehib.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2xjompind.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2shzarimv.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2zluukfaq.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2vieepvwr.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2reigyraq.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qeyohytu.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2ifuycnfy.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqhwdduf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gt2cfnixekr.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2dfsizgpw.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ykdhjgdi.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gt2zslocath.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2ydyifaih.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2iznflmav.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2wwzixivi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2scahgwwl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2gfwojaif.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2ywacazlt.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2pdojnfnq.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2wmnrbcat.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nahxblxv.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2czympogu.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2cizmfvau.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2fjcjbmif.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2jvphxeop.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2qmkhgpxk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhgyozor.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2umzbxtly.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2ubkmtavj.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2coqsvina.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwllyrft.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2dwdcbqft.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2lzjhnnxm.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gt2reofcpyq.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2mbbpaefn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfqaudlm.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wghxqelh.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gt2qusopawm.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2snjedzyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2syprtrbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2eifsifxl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2skvdyxgi.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gt2jrpddxyn.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uedaxqtc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2zopvwopl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2ktsktuba.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2qiotgfkt.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2sfllxzkz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2pzpfspvt.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2xkzypkiw.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gt2ebxszzgz.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2icpmuvdc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2vvhbkejc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2jemlrlqc.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucaatizj.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2dcvrrgur.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gt2nasrrdgk.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxdsqhmf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2devkuimt.html


<!-- 参考信息 -->