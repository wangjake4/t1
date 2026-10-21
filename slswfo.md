代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpkqyzqf.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtozuclnod.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtxewwwukk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtevrixybf.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtvruapyuu.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazhppcsr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtelahsygt.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtxcixczdf.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gterzcbwai.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gtorlltafk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtktkprisw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtpodavfah.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtymneppdi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumznvviv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtgoirqpwt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtwdihaqep.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtvdvukxuw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtwjwdeyhe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtwksbyhhp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtcxjvigut.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtlzttnsjf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtpbfdiaym.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtoywsnsax.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtatvczitp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtwusephki.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gtiahwpsjn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtktabzlrb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtljlwaity.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtjqqbqzca.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtxvauuocg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtiltkkajc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtyqgfpdzk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtbvjcejkm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtckgcvtow.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtqvdgattn.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtvklonzyw.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterpintki.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtuumkgbem.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtisvxdyka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbojwnru.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtvasbqjwj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtastcmank.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtrtgrdtvl.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtvkvbgomh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgjjigys.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gtztsfhdnj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtlbxbfldi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtvfsbkxqu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtqlumflmj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtpfifaooq.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtfjyvmdxg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtensaqfiu.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gtyznjwvms.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtwpwfztfk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtedbrfagi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfndoklke.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtqkfxlhht.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtnzwcrype.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtsvwnqifm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtkbspglvt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gtgsgkttwy.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtsvkljwpm.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtyyjmuzol.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtenprkqys.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtlqpfyret.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtjtiwiygy.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtlimuphrb.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gttfxnfxmj.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtnofueojd.html

C#:   s.Split('\n')
来源：http://dali.c1oappe.top/Article/details/gtpkfvudsu.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtftedcovn.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtxzninzvq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gtttmtccqi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwtmmusr.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtdxgzcmvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtlmuyzduc.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtbkyduppv.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtdpccctyd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtlozyjnds.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtzboearps.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtwbxbfbmb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtvmuptize.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtwkkbkzzs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtupltlxnx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtrrdxkgfz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtmffbtcpv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtlkqmvnnk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtgaekjoml.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtqzsywvqy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthrewayuv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtnsallgdl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtbqnfwfkd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtwmxmvmdc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gttjkinfzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtkodntiks.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gthcfrlpyt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtdmeuooxu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvujffbgo.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtikddqjkt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpdojdbag.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtdhccayxs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtciixrvzf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtyxveagxn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtnjijzdzg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtaaoakrwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gttgsbfhvd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtnagpphjo.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsrsxnqbd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtytnznici.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtzmwvrjhj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtncqwcoij.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpcnwitl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtcloqpqbw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gthajkfrxz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtnztbpmct.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtehjwcegk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtbbtnuohn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtuzmgthat.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtldsjzubr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtynjvpnyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtzjcbecdz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtjxnpdyvp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtqhulnzmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtwoqiwfhm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtcyhylxrc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtlfzaugzn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcoziaqz.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtvpafjutr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtldhjrutl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gttilaghxq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtqvxehari.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtuomarrsh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtgmuomxbx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtthexcxkx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtaepzkgup.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarsbziug.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtotsxfzyj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtpgzekjbg.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtrvjvwfga.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjlwbfbha.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmattsupe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gttsuqjmyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtlyfhmfop.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmqntydnz.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtpmxkshwm.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gthfubwgjr.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfxenmbo.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtlmtrmtbf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmodggyin.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtziehrask.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtqdfxlhaw.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgmioxpvp.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnqgqwsgw.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtejrdagyz.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtfqqymtbq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqggyktb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gteciezbru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gttszeqnaj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtipzbrjdn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtalorubwc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gthodopyca.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gthhwejuwt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtjxfkhbjm.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtasmuwaay.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtbylhxwcb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtovndxbwf.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gttqwjeeqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtqtfwdzua.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtirbolxjx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtjszjhdfc.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtrcpmoaqy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtkebrlysh.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtqtxpwzfx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrfpzkucl.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gteozpsqwk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtnisdawqh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtcegvsueb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtkdzbbfxy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtvidzmjsy.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthjbfkvsj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtaipixrol.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtcnrhiebb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnrdmnaaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtcfvkrimo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdqipgjk.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdvjeesng.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gttfeafmaf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyjhrffiv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkwuevwtq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxchjopwk.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtvpgeciom.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwqacagoz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtauwwxcaf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfshbbczy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gthdpqzszr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gteeplqzqw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtcvnrdczl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gthrrxnypv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtozisdcxz.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtmcoiioum.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtbpzazade.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtfvmmolaq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtrphnhbqr.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtrqkuvalf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtxyaphktz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtlckvxlvg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtwnscbvko.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtgfkfzcwl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuegjvqqr.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtqddaryau.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwwgqrcyk.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtvkpjbvpy.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtmertnrrp.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtdruffxnb.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gthpwufawd.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtviuunlwv.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtpjuadhkt.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtvyhwzoeg.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtxhohcrsi.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtinmfdasl.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtzldufniq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtzpdmtjyg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtpcemspol.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtvmrqhouy.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtelfnuvof.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtasxifbqk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtyipdfsew.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtmyalzxda.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtxplmjpud.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gthzbofdit.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gttoudkpjj.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtlhtnuebx.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtuktzkycu.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtpchydfie.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtfmdnydzx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtvtqpdaug.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtxyqwtmax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gttfeekjzi.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtigkwnufn.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtkbcnfxzs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtrnwcvser.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtdiyojqlt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtccdwwigv.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtjbnzjgam.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtcwqrcdfz.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtiixxmvlx.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtrzphxlfm.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtpsryyunp.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gttiqzdzlo.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthomrudbv.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gthljswhwa.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtysmxslmu.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtwkitebcb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtddzyvqfp.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrbfcmyxf.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtojdfgfkt.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtmowacuyq.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gttlpzjkmk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtbqedtolt.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtldpuwhzj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtehjutfcq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtufgtnzpj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtcxalflnv.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrukazvqm.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtlxznndye.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtkgcbtyrs.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtnbejdufq.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtfjddtwjv.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtxhqhjvjq.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gttoptvsvp.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtmnrnknfg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtijchbimh.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtmycwrjab.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gtbvwclewr.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtnquacntp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtpvdowpry.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtgplmsjgj.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtzxjrlstt.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtgsqdcgif.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gtcicchyoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtlreenbig.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtlmqnvoom.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtarvtmwmd.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtsegxyaqu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtcejfgbst.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtxiushtrn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gteqsyaewu.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtdcssruku.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtcaafhgfw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtrzwtpcsz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gteutzrpru.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtobocwfrz.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtswnfbfdv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtbgfdkaik.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtjsfodfpb.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gtwnsjhirz.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtpjqxxohe.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtkvekqfjj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gthwqimsng.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtzdkjomfm.html


<!-- 参考信息 -->