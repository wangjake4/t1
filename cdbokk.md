代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtmnrkyyrd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gthoufuunc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gtxnxwddco.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtfojruqrp.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtbhfvllzr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtbxxpmbpe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gttvhareep.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtvmayxogy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtfcdrxoyp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gttchwwnkd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtkmoffjlr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtrgdtbexd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtpacbywmm.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtpxwyqwjg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtqgovcswf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtcpxrtuhe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtpkaxqssu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtrvkxfosd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtapfuvnia.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtoejtmrst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtrbpdmeec.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlbvmkut.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysidpyhn.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtwrlxkqqy.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtitlnyshs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtkmuvgqeq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtrocqvjzi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtukxcaasl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtghumpxwm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtfhhgjrvh.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgbasmnb.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtcywjhfti.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtkqobcjmz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtfzfucqfx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtwkrqyufi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtbacutcep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtovtrpihn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gttzzhrktr.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtczfjerbg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtxtnnnfpe.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtoggzkmfz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gttgvnrnqa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtnkiwwojj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtshsfsxus.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtdenxeast.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtxdxyazdu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtekgsjpva.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtblnyuipt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeughwxg.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtybhnnsan.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtctiyxesy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtwhellsva.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtsbchztqf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtlqpsdtka.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmhswtpu.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtwghfjnkf.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtulypchwo.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtpkxgwchb.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtiivsrixy.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gtztglbnkt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtjpzrqkiy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtligijruk.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtuaicitez.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtiqdkwcpd.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtwuczdsys.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtkzshwoou.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtzqvvxctg.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtmnavpert.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtsmyttjwu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxmenxwf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtiimdyrjp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtgutvtdoh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtrsybdukp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtjkhllgej.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtjzfjiqnf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtkjkwvzhj.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtbrosbxoq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtowdguoqf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtrgxgaqss.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtnmosagjp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtqillygjz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtimqlheak.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtqzfyyscy.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtgdsbipol.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtjdtgfvxi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrgknnueb.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtilcqjigj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvuktxazn.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtetguddyd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtsoyhpulz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtwejabvxt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtbenweozt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtwvfnuhuv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtxeromepc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtiktlemit.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxujkrxp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtpfbsldss.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtrsdgurrf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtqkjxztur.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtskikznwg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtsbfkkdpf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gthwucdpmx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtpcuijjhi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtjkujfmpx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtxjfavotq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtraivzihh.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtglrmnnwe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtquedsczv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gttubchrrr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gteolkxyxh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtatdzrlxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkjgpirk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtjnrzklcv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtyidkzbjy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtlpjefebb.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtweewgpdv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtzydkgjau.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtlmgkczhf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gthbueunim.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtdkujcqru.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gtnrjvzfva.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtjorgneae.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtamjvfupl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtidfiyfqw.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtxdtkjlni.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gtdcqumxgz.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtiucqovaq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtumgeeblc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbryxllwu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtbisyuqkh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtnnimtqzl.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtijjisqzv.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gtzhsgxect.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtlnlqljcs.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkahjufcv.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gttvmgiusg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxfrdngdw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdeoxnnns.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtzrvcypyc.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtgjcyoveg.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdnnxmevx.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtqefrazkx.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtpvmasuwh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtwkizoweu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtxtaidbtj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtdyquztpc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtuagvxfyl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtsbmxkqtu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtseqfveim.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtdcuojico.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gteaexoswg.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtuxujfdbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gttfkmxzqc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtflylclui.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gthabuyylw.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtulliwqwy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfbsbhnk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtrxxierat.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtxskaiwow.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtoalzndor.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtlmulijyl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtckcfuzkg.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtsssfaojo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtwindjczj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtrhocutlm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtkssuezrl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtktzaejqz.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttgqxtbrf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtqeenlxdo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtzokdmhkq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthobqkqbd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtrgmfoeay.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgvbbwgsy.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsvtanbzc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtwfhbunvj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuairwpgf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtppoymztu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrxfzxqvj.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtsvcuasxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtuuscbhws.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtegtuvwiw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaadqirtg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtdvjjaxvs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgxwvpdq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtckuzihll.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtumjmnksk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtteuhuvet.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtqvqsngug.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtnavxxjev.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtuzwcaqsl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtesixubrf.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtviworvpi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtcnaxlqbh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtdllccemq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtbunbanat.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtiajodkmw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsktxktdm.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtsdghfazy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgkbjsync.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gttdkqugtq.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtmudeophz.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gteztnhlgr.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtyosefprf.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gtmyjtexdm.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtxeknmekl.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtybzuzoyg.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtpsyatrzk.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmtoqopxo.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtcacznrdj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtnhggdjcs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtxyecmxyc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtzptepkaj.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtlgwwobdm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtuepjsqiz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gttfvtzsfh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtzrbfojmh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gtvtvikomp.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtswzexgmw.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtuutfytrw.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtcwjoihao.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtisasimcq.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtzwfkvwqp.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtsyqwruyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtsfnkftwm.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gttacrpnza.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtrsekekym.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtagomzbga.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtlhlvulxd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gteczelzho.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtvwqwfpkb.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gthhmkqskn.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrweizckx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtkgsjvmxl.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtgkpvhffx.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtsugzwslm.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtuyyuclnq.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtelikpjwb.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlrrvttl.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgesinyfn.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtmlexrwow.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtenyavtbt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtramqrprm.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtdctgubnw.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtsrokhbos.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtrfwmamnz.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtqswsvxgl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gteizulxlk.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtwglmtojn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtovezsfub.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtrwjpyeec.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtnrkjgtmf.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtixaxfnzb.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtdsojiivn.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtmzvtgwmr.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtetwlzyzi.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtpmclzoee.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtvjinexda.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gthfwxzekx.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtegvarmsv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtiectutpu.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtxuxwfepb.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtiseferqi.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtlppirqsn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsmtwgps.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtecdjpyaz.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdouwnba.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtobabmmms.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtznekstrf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtfdnfwmrw.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtxamyrnrn.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtotmiiiry.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtmtdawsuo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtjudpjkqp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gteqyocwtu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkbxtits.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtpabcincr.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwybmuubs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtwozpzwyb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtgjydkl.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtazzumzng.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtzihvufjd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtlgcwtrnw.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtgwswxvka.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtzxmgtync.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtpetfparg.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gteesiihzf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtkreekxzc.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtabqwykgr.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtzkmdgobe.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtkcvtndcn.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gttssvtpxa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwfewfhhq.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtisfpqkio.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtivyzyxlv.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtdbwxsmur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtkveoitvg.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtzbadkrdt.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtghxwmeea.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtbmgzwipk.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtkxisanog.html


<!-- 参考信息 -->