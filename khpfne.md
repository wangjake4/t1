代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2klnexhnp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2lmvmywwk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gt2gruarqrk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2aljpwojr.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2aufehrww.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gt2rsqbkxbc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2uibtcmly.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzacstoe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2vwnuhpyq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2baybnkmf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gt2gfmjcdrk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gt2fsfkyuex.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2zwvbupit.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2hzlsdijv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2hzjolgkl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2zbhqbqlo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gt2tjjisgoj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2kyhwtods.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gt2goufdhko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2rhiaosdx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wugkrnos.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gt2dyawexsw.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2jzwxebch.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmylmevz.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rleghafr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2cxgtoobk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkfkewbp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2gkmhqeaw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2oiwjdesr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2prsmpsbj.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2kemmqhaw.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2tcltxjoo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gt2bxrsmpgq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gt2hrhmtztd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2cigoxzlb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjhjpmav.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2nlcpmixh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2ydzxxxgf.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2wrycdsio.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2ngnbzjpk.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2gnnlpfzy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2tayidfxu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gt2lappywsy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2xnopckvx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2xerjdsjs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2hscoquaj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xppdwefs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2wpnyfugo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gt2ybrrniuq.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2hixqisdy.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gt2trklnhgh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqjrjkcv.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2mdrcuifn.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzatfhrh.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2iiwutscr.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gt2rjhsiprk.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gt2fuczjxjo.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2uzlnbhfc.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2lhrrrxic.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2mkuvroyc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gt2onazfgyp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gt2hgnmvoqw.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gt2dphhwoyp.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2yuonvahq.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gt2caglpklp.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2evrupomb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjvdofbt.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gt2mkqrswly.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhwquwlm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2flpqxotj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2ceqoplpp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2wrgjyaqo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2empojksh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2whhhabtx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2xzyirinl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2jjykcvsu.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gt2hbhabhoi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ebmjdfzq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2tuxfkovb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2vdptmwas.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2heiziejv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2lsqjsekt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2dmviqceq.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2arbrhvpi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftsdgvgi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2inyieryf.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2ojqpqvwj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ktusmhgq.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2youlrjhk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2gikvzlfh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctmdkkxk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2xjvewqgj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2hvgzmvgd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2zurlajge.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzkxfuxb.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2gjvjgzuc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2fvvbsetp.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ohbrxpob.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2hdqyzlrj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2vvknsxuu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gt2chcfhhlx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2icdrnfmv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2tvjfskva.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2vsnsypqh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2idolihnt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2gzbwfzsk.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2gtxfedmh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2tidcyzhp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2gxfjrslt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2rwhwlgna.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2zteytpui.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gt2fzrjchls.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2rxulsxwn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gt2xurkbeiv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2odkohqbo.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrciwzyu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2wnitbdss.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gt2qoebrygt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2yrywybcj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2kzghaeql.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2poibqnbb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2bxtblrdq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2dvyknrws.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gt2xnilailk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gt2oocppyix.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2tqcvrazb.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wduoasec.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2rvrdbgkm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2btlhjtsh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2yeispvtr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2yhwkbwwr.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2qlgogsjc.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tmdjnwia.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gt2eguyskwh.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2cwmswbwt.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnvprfzt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2fjvajtje.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2zuxmjaqi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ixylbibm.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vfrnycpj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2tfzcrkdz.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2wulquiuq.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gt2bqqkinqq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2itfyafxq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2ietugdao.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2icffdumw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puhayloc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2etzehjbl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2odqurvvf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gt2nbxgjjco.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2slhcfcdq.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gt2qstskxqo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2tpqsapqy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apwdbzsg.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2czxvphfe.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2huqkpnfl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2doailxbd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2dgngivlw.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2svtthsen.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2sviasawb.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2ydrwfmac.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpmlhian.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2ktbrtznr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2mygdzkoj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irmzgjnk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2fcxytrtd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lziatheu.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2nhifxlvn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2jubnckvl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaiexrxl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ttgeacnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2nokaaoai.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2qitfdfda.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lrcrksxt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gt2ecfxkbtq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2fcmpscgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cvxlkhma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2fcrokfkh.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2lauslbgr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whingsss.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2fehnnevg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uckifsok.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2atyolxut.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2cdugtyft.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2isqbtwwc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2lkcntchg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gt2yflaarox.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gt2jsrqnuue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gt2kisyorhh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2gjrvixoj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gt2ofdreiom.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2zvxsmsmu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2jhvbcjnp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxyepnbt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gt2xauhhnwq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gt2bxxqxtbi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kadjxzue.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gt2xfonepkq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cknqxydp.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2fwxmvwgu.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2evnnumzd.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gt2ioldtfde.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2nnbknohb.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2dhttbujd.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ddsjbrxh.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2whasugsr.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gt2qcxqatye.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2bqyrdmlt.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2rnujqdkm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2xbosxhck.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ypayuhmv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2gspitsqi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmytgxuq.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dlnsslvu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2ajbnvvkc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2iaiowtwx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bunxbnpe.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gt2gqcizbeq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uysqmmzz.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2gteznlph.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2mynfrfxe.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2akuyzdje.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gt2pefcvkqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltoctzsp.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2izdhvpxs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2jrzqizdo.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gt2jzfcdroc.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2ihlhtijl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2nkagdqff.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2massfsns.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2kmknvvgm.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2flmdmngh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifmmqsro.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ouyfpjlx.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2ymuqxofd.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2llwsdycg.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzjyoadu.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2uqonwzvt.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2pvbpsmrt.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2uznvhieo.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtlnrnsh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2ddkedyhq.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2vujujjnw.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2cchhugdh.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2awcyrtcj.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gt2nibnaotg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2wkfexzfv.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ykrqisly.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2dkugmtjm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2eozirisi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utjlkhxp.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gt2ynilgbrb.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fquuxmdt.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2szaxcsem.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2oioylwpb.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gt2etearcpx.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2tpeluiao.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2whdtynzr.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2jmfzwnuz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2meyiqnnu.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2knhzmujb.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gt2rwlrwqgy.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnewlosy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gt2lwvxgfiw.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2oiilxngl.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2pxruimcj.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gt2uikexjnr.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2zlwuxivf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2matmtobl.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2apllalbt.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fybtrgee.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2wjmghdnl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2ytpuvzpw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ecjgwmqs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2eofmxkmi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zvzpxppu.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2atwqyvzq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2lnmlhmzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2saxwtbne.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2vgfmlxzo.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2usmkwyfn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2jvlttgji.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2feqdjnbf.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gt2xgfebhuo.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2rpkufgqg.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2hzprpmrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2lcktsnyh.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2bhpmilpb.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gt2iclgplsm.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2oczdgyvd.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gt2risjrorq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2oqgqiwdd.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2jaanibfb.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2xlqlxzem.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2lhlkfnnv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2wtljebqe.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2qmqctdbq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuuckbs.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxoxqfek.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2nqzbhrxf.html


<!-- 参考信息 -->