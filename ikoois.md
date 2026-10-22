代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gt2czasvyus.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2ezbcasyb.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2yyqruoqp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2ibsiwnwm.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gt2eivfwqvn.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2fcmdyqzq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gt2wzbhqmcm.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpkjumkb.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmzvmtsk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gt2clxplycb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppmtczvf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2mairziit.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2brzlhuuj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2amraeqlf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2movpmwyj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2vqbdhjan.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mumzgspy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrqffntq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2krdybbhf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gt2nbeubehl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ljhaxdpd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2gvagaivu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lufgpcmt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmhiobki.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kljhoqoa.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gt2bpgwcwni.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gt2cqfluxxa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gt2rxgeexge.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gt2kbzcehta.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2pdmaeoxl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2qpihcacx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gt2fnqnofrb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ywivbxqq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gt2krkeuual.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2ollknfen.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2wkulqvns.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2fvrlfaqy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzdqjcsx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2myppywpr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2laviczba.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gt2iitdefvm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gt2nlsrsrto.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2irrxevmb.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyzzlxcq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyskopxz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2yksqcjwm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2fnqxaowo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdfhmcwt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ohnehyan.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2ygjwhpfs.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2kbxormxq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbopjxwt.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scqevzwf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gt2qshjvinl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2bimyulmt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjivhthf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2sbhbbsoe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2vekyyxrg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2bwdxmbnm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gt2pwneebqu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2aepitywz.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gt2zcvxhiok.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2hqioqplb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2wvhudsul.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2wyiaubvn.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2twdtyzep.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2bjwjrple.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gt2ptymjvgo.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2flgnusfw.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2gmebrjts.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2xvgudgjm.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gt2cbfjjstd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gt2jurkojtc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlnyksbk.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gt2grxcausx.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2kifhcuwz.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gt2ximyojeo.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gt2acqbtxgf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfsupuli.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2xmjdmgew.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzsctius.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2ncjxpzkq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2fhtqubwz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofckizts.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2wvzcqxno.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2cumvibyb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2epczujkx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2qluqvuep.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2yciojhtp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2zqtcofgd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2jdbcwwho.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2uwfagste.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmlsyuiv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2avtpougo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gt2veglnhbn.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2gxujdntz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqqrunnd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2srcvndpy.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2bdicpzqe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nilgjzva.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zygslprh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djhsfbfe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2vnvjzlts.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2octomqcu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2zceljxxb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2lwwqogmt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gevyfwqd.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2qsroalmu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2zbbffgdw.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhiqppwk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2kejtnuie.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2vtqcdcuf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2tmpraemk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2qoncxwle.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2exbwllqu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2rmrqtdta.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gt2lvulycdf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2azgmkjpr.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2zxsrmbii.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2kzzttlxb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2bmhojwew.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2ckelikrc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2kohrhnay.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2srvrlirl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2wjlgbryw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2weftvqvl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2lreujuwy.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2ptowcbph.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztdlobpk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gt2mczhvwtp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2uacegcvf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2knxywquo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2bneflolh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2iugnxawf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gt2adzxgjzp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2hvcbfzgs.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2ifvsnazs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2qnnyhucb.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mojiagqx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2jouwgelc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zxztcuyl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2phlvcgez.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2upblqdag.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bajysgyl.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2idxzigql.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2dveheehu.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2pjtbpxmc.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2wddgaopj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2isboykfj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2jkubevnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2bzaafnmc.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ftdfekiu.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2upbsiihf.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eadtdicf.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gt2hjfgpjnh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2byuvqurg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gt2prcztybq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrfbjliy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2qpfjginr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gt2dgrdosdh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2mwswsowu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gt2eevohazy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2hwvuciip.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2dptyokwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2asecdldn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2abczqych.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2ufrpnymd.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptpmzlgq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2okjdpoqt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gt2wkbczlqd.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2lpjvvvcw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlunglvv.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gt2ycpqatky.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qztfnsrw.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdxcaqxd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2sqlqagtj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2tgdcxqhl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2csbyfzqp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2tbelwvtd.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2yjipbtvm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2rxonybbp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2khgsenuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2zgmifxcn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2gmymbndg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vrdspler.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2pdlsumue.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2bdlrrebi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2khmtmxin.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmdepzny.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2qajvetod.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2wthklboe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2awcddvsp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bghztfnc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2izdmsyxa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wksdwlbg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2ixzbhifp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gt2siwyoxak.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2zdjjpryr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2ajagzcsn.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gt2nnibskow.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2ngmbxgzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqagaoxo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gt2kchllwhs.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gt2lvthfbfa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gt2ldwrnqfd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2vvqfixpr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2sbravclf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2aynvojuo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glggkime.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2yluqistn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2docleqhe.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2xdicbefs.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gt2rxhsngwc.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gt2yhduddez.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2anvvjanx.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2hajsxidr.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2sosqnrlk.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2zzxmqojm.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2jaomjwnw.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2ffxlesyf.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2llisfdah.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2pxidfefc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2hytrpgcs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2amhiyees.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2nadennri.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2fimvwxso.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgubecer.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2snyqjhif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2khxkjguc.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gt2wbfpqqbn.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2hkxsdchf.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gt2kzzptexn.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2dstfajrl.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gt2uojnammo.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2byzemtlv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2ptykqqxy.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2zankbzfr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2yqvpexra.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2lnercqnx.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2spekymka.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oixhzecb.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2ihabqzqo.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2jsuxbkyt.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2hnwvutih.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxlktvlv.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2igytysji.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2mzufhoax.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbqjyhvh.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2piogpqwo.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2xtrdxive.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ogrvcahp.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2cpzetxyv.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2odxwwpmq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2gcrevllo.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2iztoyize.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2niqslgvk.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2pfqxywpw.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2ttizcplc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hojsaepw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydqjighk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2utaocrmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2hopkmnxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2yizzrzzq.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gt2yndqspqz.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2ovqwxaur.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gt2pchdbqhi.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gt2ztbfuknf.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gt2nhuzlxcn.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2hwtqcctf.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2paijcfhc.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2beaqkdfd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gt2zbtermqd.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2rlayqurg.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2fwhcpzlx.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gt2rqfbkzjo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2mlqhedqp.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2vrjceoyz.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmtkaifd.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2hmzmsdgf.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gt2ugytueff.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2jhfaoxov.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gt2jtiqiuln.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gt2xpgdujix.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbsoiowm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gt2qyolcmne.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smqdpzdr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2mzpiizuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aatwopup.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rzawbrok.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gt2kxargphs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2inqsiran.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2yqoqofjw.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2jqfglhsk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gt2sjvatdtg.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2wtoumuzb.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2ummyghqs.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2kopehjuq.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2dbqljqtm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrxgluqu.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2usrxivcj.html


<!-- 参考信息 -->